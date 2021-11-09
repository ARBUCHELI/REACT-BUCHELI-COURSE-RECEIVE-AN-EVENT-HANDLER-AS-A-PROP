# REACT-LESSONS-INSTRUCTOR-ANDRES-R.-BUCHELI

## Take a look to the live example at:
https://bucheli-web-development-react-course-receiving-handlers.netlify.app/

## Usage:
* Rendering all the page from an main component (Talker.js).
* Creating an index entry point for all the application.
* Import the main component (Talker) into the index file.
* Import components into the App component.
* Passing props from the parent component to the child component.
* The child component access the data via this.props.(name of the prop).
* Rendering different UI based on props.
* Passing event handlers as props.
* <strong>Notice that in this example, you can see that we can pass the props with any name (talk in this case) and this is the name that we need to use when receiving the props in the child component.</strong>

## Considerations about this exercise and naming conventions:

* There is a naming convention that they often follow. You don’t have to follow this convention, but you should understand it when you see it.

* Here’s how the naming convention works: first, think about what type of event you are listening for. In our example, the event type was “click.”

* If you are listening for a “click” event, then you name your event handler handleClick. If you are listening for a “keyPress” event, then you name your event handler handleKeyPress.

* Your prop name should be the word on, plus your event type. If you are listening for a “click” event, then you name your prop onClick. If you are listening for a “keyPress” event, then you name your prop onKeyPress.

* One major source of confusion is the fact that names like onClick have special meaning, but only if they’re used on HTML-like elements.

* Names like onClick only create event listeners if they’re used on HTML-like JSX elements. Otherwise, they’re just ordinary prop names.

