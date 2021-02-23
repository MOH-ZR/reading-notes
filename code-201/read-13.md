# History of Local Storage for Web Applications  

Local storage in native client applications is better than in web applications. In native client application you can store data in any format you want. In web applications, cookies were invented to be used as persistent local storage of
small amounts of data.  

Cookies in web applications have three potentially downsides:  
* Slowing down web application since they are included in every HTTP request.
* Sending data unencrypted ove the internet
* limited to about 4 KB of data.  

Before HTML5, Many attempts were did to overcome these challenges in different ways, but they are unsatisfactory.

* Microsoft invented userData behavior that allows web pages to store up to 64 KB per domain.
* Adobe introduced local shared objects feature and allows Flash objects to store up to 100KB per domain.
* Google lunched Gears , an open source browser plugin store unlimited amount od data in SQL tables.  

But these solutions were not enough; all of them are either specific to a single browser, or reliant on a third party plugin. So HTML5 set out to solve this problem: to provide a standard API, implemented natively and consistently in multiple browser, without having to rely on third-party plugins.  

## HTML5 Storage  
it's a way for web pages to store named key/value pairs locally, within the client web browser. You can retrieve data in HTML5 storage using *localStorage* object's methods.

* **getItem()**: return the value for the specified key.  
* **setItem()**: overwrite a with the specified value.  
* **removeItem()**: remove the value for a given key.
* **length**: property to return the total number of values in the storage area. 

**Tracing changes to the HTML5 storage area**  
you can keep    track programmatically when the storage area has been changed by the *storage event*. the storage event is fired on the window object whenever `setItem()`, `removeItem()`, or `clear()` is called and actually changes something.
```js
    /* jquery code to trigger and handle storage event */
    if(window.addEventListener) {
          window.addEventListener("storage", handle_storage, false);
    } else {
        window.attachEvent("onstorage", handle_storage);
    };

    /*call back function to handle the event*/
    function handle_storage(e) {
        if (!e) { e = window.event; }
    }
```  

The returned object from triggering storage event has some useful properties:
* key: string
* oldValue: any type
* newValue: any type
* url: string