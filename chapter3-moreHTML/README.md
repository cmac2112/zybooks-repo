1. Create a webpage about one of your favorite musicians, similar to the example below.

Example hometown web page screenshot

Use the following HTML containers:

<header> with <h1> heading that contains the musician's name
<main>with two paragraphs:
1st paragraph gives some background information
2nd paragraph links to at least one website about the musician
<footer> with a paragraph that names the webpage's creator
Although the HTML structure must conform to the instructions above, the text content does not need to match the example above.

2. 
Add a web form to index.html as shown below that allows the user to enter personal information for joining a social network. The webpage uses CSS to align the form widgets vertically.

Example social network web page screenshot

The form should:

Use the POST method and the "multipart/form-data" enctype
Submit to https://wp.zybooks.com/form-viewer.php
Use a <label> for each form field and the label text shown in the image above
Use a <div> to surround each label and form widget pair and a <div> around the submit button
Use a text <input> with name and id "fullName" to get the user's name
Use a text <input> with name and id "email" to get the user's email address
Use a <textarea> with 3 rows, 50 columns, and name and id "about" to get a short description about the user
Use a text <input> with type "file" and name and id "picture" to get the user's image
Use a submit <input> button
Use the required attribute for name and email fields

3.
Edit the form in index.html so the user can enter a birthday message and select various message options. The webpage uses CSS to align the form widgets vertically. The webpage should look like the following:

Example happy birthday web page screenshot

The form should:

Use the regular expression [a-zA-Z0-9-_\.]+@[a-zA-Z0-9-]+(?:\.[a-zA-Z0-9-]+)* for the email address <input> to verify the user enters what looks to be an email address

Use a date <input> for specifying a date to send the message

Use a color <input> for selecting the message color

Use a number <input> with a default value of 0, minimum of 0, and maximum of 10 for number of times the message blinks

Use a range <input> with a default value of 20, minimum of 0, and maximum of 50 for the music volume

Use a submit <button> that reads "Send Birthday Message"

Specify an id attribute for all form elements that matches the given for attribute of each associated <label>

Specify a name attribute for all form elements that matches each element's id attribute



4. 
Add a form to index.html that allows the user to select a team's starting lineup for a game.

Example starting lineup web page screenshot

The form should:

Use the POST method

Submit to https://wp.zybooks.com/form-viewer.php

Use a <p> to surround related labels, form widgets, and fieldsets

Use a <fieldset> and <legend> with radio buttons for choosing Draft or Final. The radio buttons' name attribute should be "status" with values "Draft" and "Final".

Make the Final radio button checked by default

Add a <label> to each radio button so clicking the label text selects the radio button

Use a drop-down with the following dates: March 20, March 24, April 2, April 6, April 13. The <select> name attribute should be "gameDate", and each <option> should use a value identical to the option's date.

Use a <fieldset> and <legend> with check boxes for choosing players: Aarav Agarwal, Ava Johnson, Julio Ortiz, Liam Rubio, Emma Witherspoon. The name attribute "player" should be used for all check boxes, and each check box should use a value identical to the player's name.

Add a <label> to each checkbox so clicking the label text selects the checkbox

Use a submit <input> with value "Submit"

