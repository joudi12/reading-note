# summery
## Form Controls
#### There are several types of form controls that you can use to collect information from visitors to your site.
- ADDING TEXT
- Making Choices
- Submitting Forms
### How Forms Work
#### A user fills in a form and then presses a button to submit the information to the server.
### Form Structure
##### ``<form>``Form controls live inside a ``<form>`` element. This element should always carry the action attribute and will usually have  a method and id attribute too.
- Text Input
![img](https://css-tricks.com/wp-content/uploads/2017/06/required-input.png)
- Password Input ``type="password"``
- Text Are ``<textarea>``
- Radio Button ``<input> type="radio"``
- Checkbox ``<input> type="checkbox"``
- Drop Down List Box ``<select>`` ,``<option>``
- Multiple Select Box ``<select>`` ,``multiple``
- File Input Box ``<input>`` , ``type="file"``
......
##### Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server
##### HTML5 introduces new form elements which make it easier for visitors to fill in forms.
### Styling Forms
##### to style the form you can usr 
- ``font-size``
- ``color`` 
- ``border ``
- ``border-radius``
- ``background-image ``
##### Forms are easier to use if the form controls are vertically aligned using CSS.
##### Forms benefit from styles that make them feel more interactive.
## Event
![img](https://cdn.educba.com/academy/wp-content/uploads/2019/11/JavaScript-Events.png)
### DIFFERENT EVENT TYPES 
##### Here is a selection of the events that occur in the browser while you are browsing the web. Any of these events can be used to trigger a function in your JavaScript code. 
### HOW EVENTS TRIGGER JAVASCRIPT CODE
1. Select t he element node(s) you want the script to respond to. 
2. Indicate which event on the selected node(s) will trigger the response. 
3. State the code you want to run when the event occurs
### TRADITIONAL DOM EVENT HANDLERS
#### All modern browsers understand this way of creating an event handler, but you can only attach one function to each event handler. 
##### When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user. 
##### You can use event delegation to monitor for events that happen on all of the children of an element.
##### The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events. 

