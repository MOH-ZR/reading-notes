# The Perfect Team  

## Why some work groups thrive and others falter?  

Today, working adroitly in groups  become an essential requirement for modern business. The workers spent most of time with colleagues collaborating doing tasks and reviewing their work, in addition to doing meeting every now and then. Therefore, a lot of studies have been held and still on how to improve the team work skills for employees to make them better at work environment.  
 
> We're living through a golden age of understanding personal productivity, Marshall Van, a professor at Boston University.  

Working in teams become a culture in the new business and it will be more productive and wil short time and effort in addition to find better solutions to problems. The tech giant, Google embark on a project called Aristotle to study its employee's live and what are factors that may influence their performance at work team and how to improve them. The project concluded that group norms are the keys to improving google's teams.

**group norms** are the traditions, behavioral standards and unwritten rules that govern how we function when we gather.  

The researchers at Aristotle project noticed  two behaviors that all the good teams generally shared.
* on the good teams, members spoke in roughly the same proportion
* the good teams all had high 'average social sensitivity'

# CSS transitions, Transforms, and Animations  

## CSS Transforms  
CSS property applies a 2D or 3D transformation to an element. This property allows you to rotate, scale, move, skew.

* **rotate**:  
    * ```html
        <figure>Box 1</figure>
        <style>
            figure{
                transform: rotate(20deg);
            } 
        </style>
      ```
* **scale**:
    * ```html
        <figure>Box 1</figure>
        <style>
            figure{
                transform: scale(0.75);
            } 
        </style>
      ```
* **translate**:
    * ```html
        <figure>Box 1</figure>
        <style>
            figure{
                transform: translateX(-10px);
            } 
        </style>
      ```
## CSS transitions  
CSS transitions allows you to change property values smoothly, over a given duration. using the following properties:
* transition
* transition-delay
* transition-duration
* transition-property
* transition-timing-function

```css
    div {
        width: 100px;
        height: 100px;
        background: red;
        transition: width 2s;
}
```

The following example adds a transition effect for both the width and height property, with a duration of 2 seconds for the width and 4 seconds for the height:
```css
    div {
         transition: width 2s, height 4s;
    }

```
The transition-delay property specifies a delay (in seconds) for the transition effect.

The following example has a 1 second delay before starting:
```css
    div {
         transition-delay: 1s;
    }
```

## CSS Animations
CSS allows animation of HTML elements without using JavaScript.An animation lets an element gradually change from one style to another. The following are the properties used to apply animations:

* animation-name
* animation-duration
* animation-delay
* animation-iteration-count
* animation-direction
* animation-timing-function
* animation-fill-mode
