# Authentication  

## Questions

**Explain what a “Singleton” is (in Computer Science terms)?**  
 It is a software design pattern that restricts the instantiation of a class to one "single" instance.

**Explain how the Singleton pattern can be used with Node modules, specifically with classes?**  
```js
// assume we have a class called logger
class Singleton {
  constructor() {
      if (!Singleton.instance) {
          Singleton.instance = new Logger();
      }
  }
  getInstance() {
      return Singleton.instance;
  }
}
```
**If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?**  
I will write my owm npm package with all middlwares and then deploy it using npm.

## Terms

**Router Middleware**:a middleware that take the original request, and forward it to a sub handler according to the path.  
**Dynamic Module Loading**: it is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory.  
**Singleton Pattern**:It is a software design pattern that restricts the instantiation of a class to one "single" instance.  
**CRUD -> REST Method Matches**  
Create-> post  
read-> get  
update -> put  
delete -> delete  
**Mock Testing:**   is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules.

## Bcrypt Hashing Function  
Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be.

## basic access authentication
 It is a method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request. In basic HTTP authentication, a request contains a header field in the form of Authorization: Basic <credentials>, where credentials is the Base64 encoding of ID and password joined by a single colon :.
