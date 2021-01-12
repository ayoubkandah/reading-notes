**< form >** *element is used to create an HTML form for user input.*

Types of form :

1.Adding Text

2.Making Choices

3. Submiting Forms

4. Uploading Files

**Every < form > element requires** *an action attribute action attribute specifies where to send the form-data when a form is submitted.*

Forms can be sent using one of two methods: get or post. *attribute specifies how to send form-data* 

**<input>** *element is used to create several different form controls.*

**Type attribute** *it is a type of input like:*
 
-Text (it by default)

-Password

-Radio

-Checkbox

-Drop Down List Box < select>

-Uploading file " file "

-Submit Button " submit "

-Image Button " image "

-Button & hidden Controls " hidden "

-Date

-Email

-URL

-search

-

name attribute is used to reference elements in a JavaScript, or to reference form data after a form is submitted.

size attribute specifies the visible width in characters

maxlength attribute specifies the maximum number of characters allowed


**form validation** *it is a check if user input correct info or not.*



**list-style-type**

Unordered Lists Types:

none

disc

circle

square

Ordered Lists Types:

decimal

1 2 3

decimal-leading-zero

01 02 03

lower-alpha

a b c

upper-alpha

A B C

lower-roman

i. ii. iii.

upper-roman

I II III

**list-style-position** *property specifies the position of the list-item (bullet points).*

list-style-position: outside; means that the bullet points will be outside the list item.

list-style-position: inside; means that the bullet points will be inside the list item.

list-style property is a shorthand for this properties:

-list-style-type

-list-style-position

-list-style-image

**Table**

empty-cells property to display empty cells

**border-spacing** *property sets the distance between the borders of adjacent cells.*

**border-collapse** *property to connect border line with each other*

Styling Text Inputs its like any text 

Styling Submit Buttons :

-color

-text-shadow

-background-color

- :hover


 cursor :

-auto

-crosshair

-default

-pointer

-move

-text

-wait

-help

-url(link of cursor)

**UI EVENTS** *Occur when a user interacts with the browser's user interface (UI) rather than the web page like(load,unload,error,etc..)

**KEYBOARD EVENTS** *when user use the keyboard like (keydown,key up , keypress,etc..)

**MOUSE EVENTS** *when user use the mouse like (click,dblclick,mouseup,etc..)

*if the event ocurred it named fired or raised.*

*trigger method triggers the specified event and the default behavior of an even for the selected elements.*

some example for the Event (input,change,submit,DOMSubtreeModified,DOMNodelnserted,blur / focusout ,etc..)

Event handling :

1.Select t he element node(s) you want the script to respond to.(SELECT ELEMENT)

2.Indicate which event on the selected node(s) will trigger the response. (SPEC! FY EVENT)

3.State the code you want to run when the event occurs. (CALL CODE)

*HTML EVENT HANDLER ATTRIBUTES its an older code and not usefull for now*

element.onevent=functionName

**EVENT LISTENERS** *can add many function at a time, its not compatible with old browser*
element .addEventlistener('event', functionName [, Boolean]) ;

internet explorer did not support addEventListner().

Event flow it use to select element parents.

**Event Object** *When an event occurs in HTML, the event belongs to a certain event object.*

**preventDefault()** *method cancels the event, meaning that the default action that belongs to the event will not occur.*

**The stopPropagation()** *method prevents propagation of the same event from being called.*

THE this KEYWORD  refers to the owner of a function.

**W3C DOM EVENTS** *The DOM events specification is managed by the W3C (who also look after other specifications including HTML, CSS, and XML).*

**HTML5 EVENTS** *The HTMLS specification (that is still being developed) details events that browsers are expected to support that are specifically used with HTML.(input,submit,etc..)*

**BOM EVENTS** *Browser manufacturers also implement some events as part of their Browser Object Model (or BOM). Typically these are events not (yet) covered by W3C specifications (although some will be added to W3C specifications in the future).(touchstart,touchend,touchmove,etc..)*

**blur** *When an element loses focus, the b 1 ur event fires for that DOM node.*

**focus** *When an element gains focus, the focus event fires for that DOM node.*

**MOUSE EVENTS** *occured when the mouse move or click.event like(click,dblclick,etc..)*

we can determine a mouse position.

**KEYBOARD EVENTS** *event occured if using a keyboard.event like (input,keydown,keypress,etc..)*

**MUTATION EVENTS & OBSERVERS** *event occured if there any change in structure like remove or add element.event like (DOMNodelnserted ,DOMNodeRemoved,etc..)

**HTML5 Event** *its more popular and quickly. event like (DOMContentLoaded,hashchange and beforeun load)*

  

 
