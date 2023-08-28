# aria_css-html_project

Hosting link : - https://trishadas13.github.io/aria_css-html_project/
<hr>

<h2>Universal CSS:-</h2>

* selector is used to reset margins, paddings, and set the box-sizing property to border-box for all elements in the document, ensuring consistent sizing and spacing calculations.

html selector sets the scroll behavior to smooth, which provides a smooth scrolling effect when jumping between sections using anchor links.

:root selector defines CSS custom properties, also known as CSS variables, which can be used throughout the stylesheet for consistent color and font choices. In this case:

--openSans defines a variable for the 'Open Sans' font family.
--monstree defines a variable for the 'Montserrat' font family.
--green defines a variable for a specific shade of green.
--textColor defines a variable for a semi-transparent text color.
.container class styles a container element with a width of 100% and a height of 1000vh (viewport height). This class seems to be defining a large container that might be used to demonstrate layout or scrolling effects.

<h2>Header: </h2>

![image](https://github.com/trishaDas13/aria_css-html_project/assets/126088849/b6377ec3-724d-4f0f-9d4f-8cd4a585be99)

<h2>HTML :- </h2>

The given HTML code represents a header section containing a navigation bar. Within the "header" element, there is a "nav" section for the navigation bar. This bar consists of a logo and various navigation links.

The logo is displayed through an image ("img") enclosed within an anchor ("a") tag. The image source points to "logo.svg," and an "alt" attribute is assigned with "logo" as the alternative text. The image has a class named "logo."

The navigation links are organized within a "div" element with the class "link-container." Inside this container, there is an "ul" element representing an unordered list with the class "link-list." This list contains multiple "li" items, each representing a navigation link with the class "link."

The navigation links include:

"HOME," which links to the "#home" section
"INTRO," which links to the "#intro" section
"SERVICES," which links to the "#services" section
"CALL ME," which links to the "#callMe" section
"PROJECTS," which links to the "#projects" section
"ABOUT," which links to the "#about" section. This link is accompanied by a Font Awesome solid down-caret icon.
"CONTACT," which links to the "#contact" section
Following the navigation links, there are three separate divisions ("divs") for the Facebook, Twitter, and bars icons. Each division holds an anchor ("a") element containing an "i" element representing a Font Awesome icon. The classes "fa-brands" and "fa-facebook-f" correspond to the Facebook icon, "fa-twitter" corresponds to the Twitter icon, and "fa-bars" corresponds to the bars (menu) icon.


<h2>CSS :- </h2>

nav selector styles a navigation bar with the following properties:

width set to 100%.
display set to flex to arrange its children horizontally.
justify-content set to space-between to evenly distribute the content horizontally.
align-items set to center to vertically align the content.
background-color set to a specific shade of blue.
padding to provide some spacing around the content.
position set to fixed to keep the navigation bar fixed while scrolling.
z-index set to ensure the navigation bar appears above other elements.
.logo class styles the logo element within the navigation bar with a specific width.

.link-container class styles a container within the navigation bar that holds the links.

.link-list class styles an unordered list (ul) element containing the navigation links.

width set to 85%.
display set to flex and justify-content set to space-between to evenly distribute the links.
list-style-type set to none to remove the default list bullet points.
Font-related styles are set for the links.
.link > a selector styles the anchor (<a>) elements within the navigation links with styles for text decoration and color.

a:hover selector changes the color of anchor elements when hovered over.

.facebook i, .twitter i, .logo i selectors style the icon elements (likely using font icons) for social media icons and the logo.

Background color, shape, and styling attributes are set.
Font size, weight, and color are specified.
.facebook i:hover, .twitter i:hover, .logo i:hover selectors change the background color and font color of the icon elements when hovered over.

.bars i selector styles the icon for the menu bars (hamburger menu).

Font size, color, and cursor are specified.
Media queries are used to apply styles based on screen width:

For screens wider than 1100px, the .bars i icon is hidden.
For screens narrower than 1100px, the .link, .facebook, and .twitter elements are hidden, and the navigation bar has overflow hidden to handle the menu collapse.

<h2>Home section: </h2>

![image](https://github.com/trishaDas13/aria_css-html_project/assets/126088849/3ab1bc59-bca9-407a-9550-5b9de5d947b3)

<h2>HTML :- </h2>

The provided HTML code depicts a "section" element with the class "home" and an "id" attribute set to "home." This section represents the introductory part of a webpage, likely serving as the main content area for the homepage.

Within this section, there is a "div" element with the class "head." This "div" holds the main content of the introductory section. It consists of a "h1" element with the class "heading," displaying the text "BUSINESS." Following the heading, there is a "p" element containing a descriptive paragraph about Aria, a consultancy company. The paragraph explains that Aria specializes in achieving business growth through online marketing and conversion optimization techniques.

Below the paragraph, there is a "button" element displaying the text "DISCOVER." This button is intended to encourage users to explore or learn more about the company's services or offerings.

<h2>CSS :- </h2>

.home class styles a section for the homepage with the following properties:

width set to 100%.
height set to 900px to define the height of the section.
background-image set to a linear gradient and an image file using url().
background-repeat set to no-repeat to prevent the background image from repeating.
background-position set to center 0% to position the background image.
background-size set to cover to ensure the background image covers the entire container.
display set to flex to arrange its children horizontally.
justify-content and align-items set to center to horizontally and vertically center the content.
.head class styles a container within the .home section:

width set to 48%.
display set to flex to arrange its children horizontally.
justify-content and align-items set to center to horizontally and vertically center the content.
flex-direction set to column to arrange the inner elements vertically.
.heading class styles the main heading text within the .head container:

font-family set to a specific font.
color set to white.
font-size set to 56px.
font-weight set to 700.
margin-right set to 1rem.
Pseudo-element ::after is used to create an animated text replacement effect.
animation properties are set to alternate between "SERVICES" and "TEMPLATE" text.
.head > p styles a paragraph within the .head container with font and color properties.

.head > button styles a button within the .head container with properties like background color, font styles, padding, and cursor.

.head > button:hover styles the button when hovered over with background and text color changes.

Media query is used to apply styles for screens with a maximum width of 1303px, where the .heading alignment is changed to center.

<h2>Intro section: </h2>

![image](https://github.com/trishaDas13/aria_css-html_project/assets/126088849/3c8373f8-a24a-4df3-9e80-26462a1ff16c)
![image](https://github.com/trishaDas13/aria_css-html_project/assets/126088849/4842d2b8-64ac-4af5-9e6e-a98ef295b157)

<h2>HTML :- </h2>

Introduction Content:
Within the "intro" section, there is a "div" element with the class "intro." This "div" contains two main subsections: "text" and "image." The "text" subsection includes the following elements:

"h5" element with the text "INTRO."
"h1" element with a headline that states the company's expertise in offering high-quality business growth services.
Two "p" elements with class "p1" and "p2," providing information about the challenges of starting or growing a business and the company's mission to provide expertise.
"h3" element with the name of the CEO, Louise Donovan.
The "image" subsection contains an "img" element that displays an image related to the introduction.

Introduction Cards:
Following the introduction content, there is a "div" element with the class "intro-card." This "div" contains three subsections, each represented by a "div" element with the class "intro-card1." Each "intro-card1" subsection contains:

A "div" with the class "hex," which seems to display an icon using the Font Awesome library.
Another "div" with the class "intro-para," which includes an "h4" element indicating the service category and a "p" element describing the service.

<h2>CSS :- </h2>

.intro class styles a section that holds the introductory content:

width set to 100%.
padding set to 8% on the top and bottom and 9% on the left and right.
display set to flex to arrange its children horizontally.
justify-content set to space-between to evenly distribute items along the main axis.
align-items set to center to vertically center the items.
flex-wrap set to wrap to allow items to wrap to the next line if needed.
.text class styles the text content within the .intro section:

width set to 36%.
Child h1, h5, and h3 elements have font family and color properties.
.image class styles the image content within the .intro section:

overflow set to hidden.
width set to 55%.
border-radius set to 5px.
Child img element transitions with transform property on hover.
.intro-card class styles a container for introduction cards:

width set to 100%.
padding set on the left and right sides.
display set to flex to arrange its children horizontally.
justify-content set to space-between to distribute items evenly along the main axis.
flex-wrap set to wrap to allow items to wrap to the next line.
.intro-card1 class styles the first introduction card:

width set to 30%.
display, flex-direction, and align-items are used to create a column layout.
.hex class styles the hexagon shape with pseudo-elements ::before and ::after to create the hexagon sides.

.intro-para > h4 and .intro-para > p style the headings and paragraphs within the introduction card.

Media query for screens with a maximum width of 1000px adjusts the layout and styling to better fit smaller screens. It modifies .text, .image, .intro-card, and .intro-card1 elements to stack vertically and align content centrally. The text alignment is also adjusted for .intro-card1 children.

<h2>Service section:- </h2>

![image](https://github.com/trishaDas13/aria_css-html_project/assets/126088849/5fb0fa0f-ed30-4342-b1d0-215ac8afb864)
![image](https://github.com/trishaDas13/aria_css-html_project/assets/126088849/318a78e9-8250-417c-a717-875c287cdd2c)
![image](https://github.com/trishaDas13/aria_css-html_project/assets/126088849/3364eae2-22ec-43b2-aefe-e0fc5584f4c1)
![image](https://github.com/trishaDas13/aria_css-html_project/assets/126088849/6c740cd6-5e5b-41f1-bbe7-a793150e5209)
![image](https://github.com/trishaDas13/aria_css-html_project/assets/126088849/f7d9f897-2758-408f-ba85-9c86b7cd7e03)

<h2>HTML :- </h2>

Service Section 1 (service-sec1):
This part of the section includes a heading and a brief introduction. It features a set of service cards, each representing a different service package:

The cards consist of an image, service title, description, list of services included, starting price, and a "DETAILS" button.
The three service cards are named "Off The Ground," "Accelerated Growth," and "Market Domination."
Service Section 2 (service-sec2):
This part features two larger cards. The first card:

Contains an image on one side and text content on the other.
Presents three points related to accelerating business growth, including strategic planning and online marketing.
The second card:
Contains a set of headings ("Business," "Expertise," "Quality") each with a corresponding icon.
Presents a paragraph describing the company's innovative and customized business services, highlighting flexibility for various budgets.
Displays a bar chart with three bars representing business development, opportunity spotting, and online marketing.
Service Section 3 (service-sec3):
This part contains a heading and paragraph introducing customer testimonials. It features a set of testimonial cards, each including an image, testimonial text, and the name and role of the person providing the testimonial.

<h2>CSS :- </h2>

service-sec1 class styles the first section of the service page:

width set to 100%.
margin-top creates space from the top.
padding used for inner spacing.
display set to flex to arrange its children in a column.
align-items set to center for vertical alignment.
background-color applied.
Child h1 and p elements styled with width, text alignment, font properties, and colors.
.cards class styles the container for service cards:

width set to 100%.
display set to flex to arrange its children evenly.
justify-content set to space-evenly for even spacing between items.
padding for inner spacing.
.service-card1 class styles the individual service card:

width set to 28%.
border, border-radius, and other properties for styling.
display set to flex for column layout and alignment.
position used to position the button at the bottom.
Child elements styled with various font and padding properties.
Button's :hover effect transitions background color and color.
.big-card1 and .big-card2 classes style the two big cards in the section:

width set to 100%.
display set to flex.
background-color applied.
.service-image1 and .service-image2 classes style the background images for the big cards:

width set to 50%.
height set to 80vh.
background-image applied with url().
background-size and background-position used for background appearance.
.service-content1 and .service-content2 classes style the content of the big cards:

width set to 50%.
display set to flex.
justify-content and align-items used for centering.
.heads class styles the headings of different sections in the .service-content2 area.

.bar1, .bar2, and .bar3 classes style horizontal bars with text.

.service-sec3 class styles the third section of the service page:

display set to flex and other properties for layout.
Child h1 and p elements styled with text alignment and font properties.
.testimonials class styles the container for testimonials:

width set to 70%.
height set to 350px.
margin used for spacing.
display set to flex for the testimonial cards.
gap for spacing between cards.
overflow-x set to scroll to allow horizontal scrolling.
.card1 class styles the individual testimonial card:

width set to 30%.
display set to flex.
flex-direction set to column.
align-items set to center for centering elements.
Child elements styled with various font and margin properties.
The @media query adjusts the layout and styling for screens with a maximum width of 1000px. It modifies the widths, paddings, and margins of various elements, including the service cards, images, content, headings, and testimonials, to create a more responsive design.

<h2>Call Me Section:</h2>

![image](https://github.com/trishaDas13/aria_css-html_project/assets/126088849/4098fa58-3110-4f2d-9559-543f302f95ef)

<h2>HTML :- </h2>

This section consists of two main div elements, each with its own content.

Content Div:

This div contains text content introducing the purpose of the form.
It includes a heading, a subheading, and a paragraph describing the process.
Additionally, it includes an unordered list with three list items explaining the steps to take.
Forms Div:

This div contains a form for users to fill out and submit.
The form includes several input fields, a select dropdown, and a checkbox.
Input fields include "Name," "Phone," and "Email."
The select dropdown allows users to select their area of interest from the provided options.
The checkbox lets users agree to the company's Privacy Policy and Terms & Conditions.
Finally, there's a "CALL ME" button that users can click to submit the form.

<h2>CSS :- </h2>

.call-me class styles the call-to-action section at the bottom of the page:

width set to 100%.
background-color applied.
display set to flex to center its content vertically and horizontally.
justify-content and align-items set to center.
.sec class styles the container for the content and form sections:

padding for inner spacing.
display set to flex for arranging its children evenly.
justify-content set to space-around for spacing between the content and form.
.content class styles the content section within the .sec container:

Child elements like h6, h1, p, and ul are styled with various font properties and colors.
.forms class styles the form section within the .sec container:

width set to 45%.
padding for inner spacing.
The form elements within .forms > form are styled, including:

select element with background color, border, color, padding, and other properties.
.name class containing an input element and a label element that moves up when the input is focused.
.checkbox class for styling checkboxes and related labels.
.call-button class styles the submit button within the form:

Color, background color, border, border radius, font weight, padding, font family, and hover effect properties.
The @media query adjusts the layout for screens with a maximum width of 1000px. It makes the .sec container and .forms section stack vertically, adjusting widths accordingly.

<h2>Projects Section: </h2>

![image](https://github.com/trishaDas13/aria_css-html_project/assets/126088849/2024e0d2-237d-494a-82d8-327507515d18)
![image](https://github.com/trishaDas13/aria_css-html_project/assets/126088849/19908f26-6097-4b1a-ae9f-27c65478f168)
![image](https://github.com/trishaDas13/aria_css-html_project/assets/126088849/3bf2890c-2404-4c98-ac2d-a1a35ada7aef)

<h2>HTML :- </h2>

Section Title and Heading:

The section begins with a title "PROJECTS" and a heading "Projects That We're Proud Of."
Category List Container:

This section includes a list of buttons that users can click to filter projects based on categories. The available categories are "SHOW ALL," "DESIGN," "DEVELOPMENT," "MARKETING," and "SEO."
Project Images:

This section contains a series of project images, each represented by a div with a class of "item."
Each project image is accompanied by a brief project title.
The images are represented using the "img" tag with "src," "alt," "height," and "width" attributes.
Consultants Section:

Team of Consultants:

This section introduces the company's team of consultants.
It includes a heading "Our Team Of Consultants" and a paragraph describing their importance.
The team members' details are presented in a "team-card" div.
Individual Team Cards:

Each consultant's details are presented within a "team-card1" div.
The consultant's image, name, role, and social media logos (Facebook and Twitter) are displayed.
Social media logos are represented using the "i" tag with appropriate classes from the "fa-brands" set.

<h2>CSS :- </h2>

.projects class styles the projects section:

padding is applied for spacing.
display is set to flex with flex-direction: column to align items vertically.
justify-content and align-items are set to center to center the content vertically and horizontally.
.projects > span and .projects > h3 styles the heading elements within the projects section:

display is set to block.
text-align is set to center.
font-family is applied.
.projects > span has font-weight and color properties.
.cotegory-list-container ul styles the unordered list for project categories:

display set to flex with flex-direction: row to create a horizontal list.
gap defines the gap between list items.
Other properties for styling are set, such as padding, align-items, justify-content, and margin.
.cotegory-list-container ul button styles the buttons within the project category list:

background-color, color, padding, border-radius, and font properties are set.
.child1 class defines the style for the first button, which has a different background color.
.projects > .project-image class styles the container for project images:

width set to 90%.
display set to grid.
grid-template-columns and grid-template-rows define the grid structure.
.projects > .project-image > .item class styles each individual project image container:

overflow set to hidden.
position set to relative.
On hover, the contained image scales up with a transition effect, and a span with project details appears.
.consultants class styles the consultants section:

display set to flex with flex-direction: column.
margin-top applied for spacing.
align-items set to center.
.team-card class styles the container for team cards:

display set to flex.
On hover, contained images scale up with a transition effect.
.team-card1 class styles individual team cards:

width set to 25%.
Other styling properties for text content.
.logo i and .logo classes style the logo icon within the team cards:

.logo i has padding, width, and cursor properties.
.logo class has width and margin properties.
The @media queries adjust the layout for screens with a maximum width of 770px and 1000px. They adapt the grid structure and adjust the spacing of the projects and consultants sections for better responsiveness on smaller screens. Additionally, they hide the logo icon at screens narrower than 1000px.

<h2>About Section: </h2>

![image](https://github.com/trishaDas13/aria_css-html_project/assets/126088849/f4c19129-870e-4fa3-8bc1-9951fb1ffd9c)

<h2>HTML :- </h2>

The section begins with an image that is displayed on the left side of the content.
The content is contained within a "paragraph" div.
The content includes a heading "ABOUT," followed by a main heading "We're Passionate About Delivering Growth Services."
Description:

A paragraph describes the company's goal, which is to provide business growth services at the right time to create momentum and long-term success for companies.
Key Points List:

A list of key points is provided using the "ul" element.
Each point is represented by an "li" element.
The key points mentioned are:
"Everything we recommend has direct positive impact."
"You will become an important partner of our company."
Number Statistics:

A "number" div contains multiple "num" divs, each displaying a number and associated label.
Three statistics are shown:
"Happy Users" with a count of 231.
"Issues Solved" with a count of 121.
"Good Reviews" with a count of 159.

<h2>CSS :- </h2>

.about class styles the about section:

width set to 100%.
background-color is applied.
display set to flex with justify-content: space-around to evenly distribute items horizontally.
padding applied for spacing.
.about > img styles the image within the about section:

width set to 50%.
border-radius applied for rounded corners.
.about > .paragraph > h5 styles the subheading within the paragraph:

Font properties are set, such as font-family, font-size, font-weight, and color.
.about > .paragraph > h1 styles the heading within the paragraph:

Font properties are set, similar to the subheading.
.about > .paragraph > p styles the paragraph text within the paragraph:

Font properties are set, similar to the subheading.
.about > .paragraph > ul > li styles the list items within an unordered list in the paragraph:

list-style set to none.
Padding and font properties are set.
.about > .paragraph > ul > li:before adds a square bullet point before each list item.

.paragraph class styles the container for the text content:

width set to 40%.
display set to flex with flex-direction: column.
.number class styles the container for the numbered content:

display set to flex.
flex-wrap set to wrap.
.about > .paragraph > .number > .num styles the numbered content:

Font properties are set.
display set to flex.
.about > .paragraph > .number > .num > #no styles the number within the numbered content:

Additional font properties are set.
line-height is adjusted to create spacing.
@media query adjusts the layout for screens with a maximum width of 1000px:

The flex-direction of the .about section is changed to column.
The image is set to width: 100% and display: block.
The .paragraph width is set to 100%, and margins are adjusted for spacing.
The .number width and margins are adjusted.
The line-height of the number is increased for better spacing.
Additional margin is added to the paragraph within the .num element.

<h2>Contct Section: </h2>

![image](https://github.com/trishaDas13/aria_css-html_project/assets/126088849/a77583b8-82c9-4684-a337-979d945052ff)

<h2>HTML :- </h2>

The section contains two main columns with classes "sub-contact" and "contact-details" for the left column and "contact-form" for the right column.
Contact Details:

The left column includes a heading "CONTACT" and a main heading "Get In Touch Using The Form."
A paragraph provides information about visiting the office or using the contact form for inquiries.
The company's address is displayed using a "location-dot" icon and a span element.
Contact information (phone numbers and email) is displayed using "phone" and "envelope" icons along with span elements.
A sub-heading "Follow Aria On Social Media" is followed by a series of social media icons with hexagon backgrounds.
Contact Form:

The right column includes a form with various input fields and a submit button.
Input fields for "Name," "Email," and "Your message" (textarea) are provided.
A checkbox for agreeing with the privacy policy and terms & conditions is included.
A "SUBMIT MESSAGE" button is provided for submitting the form.

<h2>CSS :- </h2>

contact class styles the contact section:

width set to 100%.
display set to flex with justify-content: center and align-items: center to horizontally and vertically center the content.
background-color applied.
padding applied for spacing.
.sub-contact class styles the container for the contact information and form:

width set to 80%.
display set to flex with justify-content: space-between to create space between the items.
.contact-details class styles the container for the contact information:

width set to 50%.
display set to flex with flex-direction: column to arrange items vertically.
.contact > .sub-contact > .contact-details > h5, .contact > .sub-contact > .contact-details > h1, .contact > .sub-contact > .contact-details > p style the subheading, heading, and paragraph text within the contact details section:

Font properties are set, including font-family, font-size, font-weight, and color.
.add > i, .info > i styles the font awesome icons for the address and information sections:

color set to the green color.
.contact > .sub-contact > .contact-details > .info > span styles the link within the information section:

text-decoration set to underline.
margin-right applied for spacing.
.contact > .sub-contact > .contact-details > .add > span styles the text within the address section:

Font properties are set.
.contact > .sub-contact > .contact-details > h3 styles the heading for the contact form section:

Font properties are set.
margin-bottom applied for spacing.
.contact > .fa-stack, .contact .sub-contact .fa-stack .hexagon, .contact .fa-stack:hover .hexagon styles the hexagon-shaped background for the font awesome icons:

Size and position properties are set.
The hexagon background image is defined using a URL.
On hover, the hexagon background image changes to a white version.
.contact .fa-stack-1x, .contact .fa-stack:hover .fa-stack-1x styles the font awesome icon within the hexagon background:

Font size and color properties are set.
On hover, the color of the icon changes to green.
.stack class styles the container for the font awesome icons:

width set to 65%.
display set to flex with justify-content: space-between to create spacing between the icons.
cursor set to pointer.
.contact .contact-form class styles the container for the contact form:

width set to 45%.
.checkboxs class styles the container for checkboxes:

display set to flex with a gap between items.
.underline class styles text with underline.

Media query @media adjusts the layout for screens with a maximum width of 1000px:

The layout of the .sub-contact section changes to a column layout.
The width of .contact-details and .contact .contact-form is adjusted.
Margins are adjusted for spacing.
The width of .stack is set to 100%.
Gap is adjusted for spacing.

<h2>Footer: </h2>

![image](https://github.com/trishaDas13/aria_css-html_project/assets/126088849/122e4f6c-0e5c-4ae3-aa9b-a2f8e8ad7502)

<h2>HTML :- </h2>

Footer Content:

The footer contains a "footer" div with class "footer."
Inside this div, there is a "last-sec" div containing multiple sections.
Part 1 - Few Words About Aria:

The first section (with class "part1") provides a brief description of Aria's mission and passion for delivering business growth services.
It includes an "h1" heading with the text "Few Words About Aria" and a "p" paragraph describing the company's dedication to startups and established industry players.
Part 2 - Links, Tools, and Partners:

The second section (with class "part2") is divided into three subsections: "Links," "Tools," and "Partners."
Each subsection includes an "h1" heading indicating the category and a list of "a" links representing specific items related to that category.
Copyright Information:

A "p" paragraph with class "copyright" provides copyright information and credits.
The text "Copyright © 2045 All rights reserved - By Inovatik" is displayed.

<h2>CSS :- </h2>

footer class styles the footer section:

position set to relative.
.copyright class styles the copyright text within the footer:

position set to absolute to position it within the footer.
left and bottom properties set to position the text.
Font properties such as font-size, font-family, font-weight, and color are applied.
.footer class styles the container for the footer content:

width set to 100%.
background-color applied.
padding applied for spacing.
display set to flex with justify-content: center to horizontally center the content.
.last-sec class styles the last section within the footer:

width set to 90%.
height set to 100%.
display set to flex with justify-content: space-around and align-items: center to create space between items and vertically center them.
footer .last-sec h1 styles the heading within the last section:

Font properties such as font-size, font-family, font-weight, and color are applied.
margin-bottom applied for spacing.
footer .last-sec .part1 p styles the paragraph text within the first part of the last section:

Font properties such as font-size, font-family, font-weight, and color are applied.
footer .last-sec .part1 styles the first part of the last section:

width set to 45%.
footer .last-sec .part2 a styles the links within the second part of the last section:

Font properties such as font-size, font-family, font-weight, and color are applied.
Media query @media adjusts the layout for screens with a maximum width of 770px:

The layout of .last-sec changes to a column layout with left-aligned items.
Margin is adjusted for the heading within this layout.
