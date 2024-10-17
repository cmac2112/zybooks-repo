lab1 was just training on how to use the editor provided on the site


# Lab 2:
Modify the index.html file below to create a webpage about rattlesnakes and their babies.

Click the Run button to see the resulting webpage that the HTML produces.

Your webpage should include the following elements (in order):

<title> element with content: 5 Things to Know About Rattlesnakes and Their Babies

<img> element with src attribute UniversityLogo.png and alt attribute "Logo of The University of Arizona".

<h1> element with content: 5 Things to Know About Rattlesnakes and Their Babies

<p> element with content: UA College of Pharmacy | Aug. 6, 2014

<p> element with content: Arguably, snake season is year-round in Arizona, a state known for its rattlers. But baby rattlesnakes are born in July and August, making these two months especially dangerous for hikers, gardeners, children and others at high risk of exposure to rattlesnake bites.

<img> element with src attribute SnakeBite.jpg and alt attribute "Snake bite on side of child's foot".

Four more <p> elements with contents (in order):

So far this year, 74 rattlesnake bites to humans have been reported to the Arizona Poison and Drug Information Center. Based at the University of Arizona College of Pharmacy, the center serves the entire state of Arizona with the exception of Maricopa County, providing free and confidential poison and medication information to callers around the clock.
Specialists answering the phones at the center regularly receive calls from Arizonans of all ages who don't realize they were bitten by a rattler. The poison center urges anyone who feels a mysterious sting, pinch or bite while outdoors to immediately call the center at 800-222-1222.
"We will ask a few questions that will help you either identify possible snakebite or eliminate it," said Keith Boesen, director of the Arizona Poison and Drug Information Center. "With snakebite, the sooner the medical treatment, the better the outcome, so calling us right away can make a very big difference for the victims and the medical teams treating them."
The center advises anyone who might come cross paths with rattlesnakes to be aware of these five things:

<ol> element (outside of any <p> element) with the following item contents (in order):

Baby rattlesnakes range in length from 6 to 12 inches and are easily camouflaged by brush and grass.
Baby rattlesnakes are rattleless until they first shed their skins, so there will be no infamous "chica-chica" sound before they strike.
Despite their impish size, baby snakes have enough venom to be very dangerous if they bite a human.
Adult rattlesnakes do not always rattle an audible warning before or while they are biting.
It's a good idea to call the poison center if you notice an unidentified small cut or wound, even if you feel no pain. With the lack of telltale rattle warning, people can be bitten without knowing what has happened until they notice their symptoms and attribute them to a snakebite.

<p> element containing three <a> elements: zyBooks Wikipedia LinkedIn

A single space exists between each pair of links.
zyBooks URL is https://www.zybooks.com/
Wikipedia URL is https://www.wikipedia.org/
LinkedIn URL is https://www.linkedin.com/
Click the "Submit for grading" button when the HTML is complete. The autograder will run a number of unit tests that compare your HTML with the expected HTML. If a unit test fails, examine the feedback to determine what needs correcting in your HTML.

# Lab 3:
Create a webpage about your hometown like the example below.

Example hometown webpage screenshot

Your webpage must meet the following requirements:

Specifies an appropriate webpage title with a <title> element.

Uses <h1> elements for the hometown name followed by three sections, each using <section> elements.

First section should use an <h2> heading entitled "Location" and a single <p> element that briefly describes the town's location.

Second section should use an <h2> heading entitled "About" and at least three subsections that each use <section> and <h3> elements. Each subsection should have a single <p> element describing something about your hometown.

Third section should use an <h2> heading entitled "Things To Do" and an unordered list of at least three interesting things to do in your hometown.

Submit your solution for grading when all the requirements are met. The autograder will verify the webpage uses all the required HTML elements properly.

# Lab 4:
Create a webpage with a table that displays a photo gallery like the webpage below.

Webpage with a table and caption "Red Rocks, Colorado". Table has 5 rows and 3 columns. First row is headings Photo, Date, Description. Second, third, and forth row contain an image, a date, and a description. Last row contains a copyright that spans all three columns.

The lab contains an HTML file, three image files, and a CSS file. Click the Files icon (with a 5), located in the code editor's top-left corner, to see the lab's five files. The index.html file uses a <link> element to import the CSS file styles.css. The CSS changes the font, adds a border around the table, and colors every other row light gray.

The table should have a <caption> element that describes the photo gallery's theme. The table should have 3 columns and 5 rows:

The 1st row should use <th> elements to list the Photo, Date, and Description headings.

The 2nd - 4th rows should display the given vacation images in the 1st column with an alt attribute that briefly describes the photo. The 2nd column should display the date when the photo was taken. The 3rd column should have a lengthier photo description.

The 5th row should span all 3 columns and contain copyright information, including the copyright symbol.

Except the for the three column headings, your solution does not have to use the exact same text as the example above.


# Lab 5
Create a webpage that displays the poem below.

Use two paragraph elements for the stanzas and <br> elements where necessary to keep the correct formatting.
Use a third paragraph for the author and date, and enclose the author and date in a <cite> element.
I'm Nobody! Who are you?
Are you - Nobody - Too?
Then there's a pair of us!
Don't tell! They'd banish us - you know!

How dreary - to be - Somebody!
How public - like a Frog -
To tell one's name - the livelong June -
To an admiring Bog!

By Emily Dickinson (1891)

# Lab 6:
This lab consists of two HTML files, a CSS file, and an image file. The index.html file contains <section> and <h2> elements for each of the numbered items below. Implement each item below between the corresponding <section> and </section> tags. Do not remove any existing tags in index.html.

1. (2 points)
Given:

Your work is going to fill a large part of your life, and the only way to be truly satisfied is to do what you believe is great work. And the only way to do great work is to love what you do. If you haven't found it yet, keep looking. Don't settle. As with all matters of the heart, you'll know when you find it.
-- Steve Jobs
Copy and paste the entire quote.
Use two <p> elements, one for the quote and another for -- Steve Jobs.
Use an <i> element in the first paragraph to enclose the entire quote.
2. (1 point)
Print an ampersand in an HTML comment:

<!-- & -->
Place the answer inside a <p> element. Use character entities for the <, >, and & characters only so the actual tags are visible on the webpage.
Ex: &lt;img src="test.png"&gt; renders as <img src="test.png">

3. (1 point)
Using character entities for < and >, print:

<p>Nice!</p>
Like the previous solution, the actual tags should be visible on the webpage.

4. (1 point)
Create two links in two separate paragraphs:

To fixit.html, which is in the same directory as index.html, using link text "Fix it", without the quotes.
To the "Garbage Disposal" section (the 2nd section) in fixit.html, using link text "Fix your garbage disposal", without the quotes.
5. (1 point)
Create an image link to https://www.zybooks.com/, using the zyBooks_logo.png image, which is in the same directory as index.html. The image's alt text should read "zyBooks logo".

6. (2 points)
Recreate the list shown in the image below:
Ordered list with 2 items: 1. Desktop 2. Mobile. Desktop has unordered sublist: Linux, Mac OS, Windows. Mobile has unordered sublist: Android, iOS.
The outer list is an order list, and the nested lists are unordered.

7. (2 points)
Create a table with three rows and three columns. The top row contains one cell that spans three columns. The leftmost cell on the next row spans two rows. All other cells span a single row and column.

Each cell has only a single number. The image below shows what the table should look like. CSS is used to give the table and cells a gray border.

