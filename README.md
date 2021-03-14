# portfolio-js-window

1️⃣ My first project while studying on the course "Practical JavaScript (Advanced)". 
Project "Window"🏬


Tasks:

Good day, developer. You have received an archive with the sources of our project. You have a bare-metal layout without interactivity. The archive contains everything you need: HTML layout, styles written in the LESS preprocessor and converted to regular CSS, all the necessary images and fonts (already included). Note that some elements will need to set the display (flex) property to hide / show them.

You have the right to change the project as you need to achieve the goal - add the necessary ids, classes, styles, animations, connect additional styles (for example animate.css) ...

But there are also several conditions:
JavaScript code must be native, without using libraries, frameworks or plugins (eg JQuery)
The console should be clear of any errors
All variable / class names should not contain Cyrillic or transliteration. No peremennaya
The final version should be built on any modular structure. We plan to expand in the future.
Operability in all modern browsers (Chrome, Firefox, Opera, IE11, Edge, Safari)
Animations are very welcome, but are also left to discretion (you can change the installed classes from animate.css as you like)
Using ES6 +

List of tasks for implementation:

This project already has a connected slider in the form of a ready-made solution. That's all we could do. You don't need to touch it. It was kept to preserve the styles of the original project and support for the mobile version. This is where he works.

When you click on this button:

The modal window should be called (class popup_engineer)
When you click on a cross or background - disappear.


When you click on these labels:
"Request a call back" and "Ask our specialist"



Modal window should be called (popup class)
When you click on a cross or background - disappear


All modals have a form inside. It should be sent via ajax (without reloading the page) and capture all the input. It is also necessary to notify the user about the sending status (sending in progress, sent, error). Only numbers can be entered in the telephone field.


There are 6 identical feedback forms on the page:



All of them should be sent via ajax (without page reloading) and capture all the entered data. It is also necessary to notify the user about the sending status (sending in progress, sent, error). Only numbers can be entered in the telephone field.


Tabs should be implemented:

Also, there is a switching of the active tab and its style. (class active)
The user can click on both the caption and the picture
Inside all tabs there are buttons "Calculate cost"

When you click on them, a modal window with the popup_calc class should appear
How it should look like:

The main task: when you click on small previews (4 in a row from the top), this preview (picture) becomes slightly larger. A picture analogous to the active preview is shown below them. When choosing another - similar logic. Everything is ready in the layout - you just need to write the logic.

Only numbers can be entered in the “width” and “height” fields.
When you click on the "Next" button, this modal window is hidden. Popup_calc_profile appears
On this window, realize that you can select only 1 profile. Either cold or warm.
When you click on the "Next" button, this modal window is hidden. Popup_calc_end appears
The requirements here are exactly the same as in other forms. BUT! All data that has been noted or chosen by the person must be transmitted along with the form.



Implementation of tabs:

Also, there is a switching of the active tab and its style. (after_click class)


Timer implementation:



Any deadline for now.


When you click on any of the eight pictures, it opens in full screen with a translucent, dark background.
How it should look like:

When you click on the background, everything disappears.
There are many implementation options here. Layout of individual blocks is prohibited. Implementation at your discretion, but do everything through JS.


If the user is on the page for more than 60 seconds, a modal window (popup) should appear. When you click on the cross or background, the window disappears.


A modular project structure is required, the bundle must be connected.


No code duplication. You don't need to bind separate actions to each button. Use a function or loops.
