My Portfolio Link: https://github.com/CrisLua19/My-Portfolio.git

Interactives:
1. Smooth Scrolling on Navigation Link Click
When I click on a navigation link, it scrolls smoothly to the corresponding section instead of jumping immediately. I added an event listener to each navigation link that prevents the default behavior and uses window.scrollTo with smooth behavior to animate the scroll. This occurs on the click event of the navigation links. I used e.preventDefault() to stop the default jump behavior.

 2. Modal Functionality for Contact Form
When I click the "Open Contact Form" button, a modal appears with a contact form. I can close the modal by clicking the close button or outside the modal. I set the modal's display style to 'flex' when the button is clicked and set it to 'none' when the close button or the area outside the modal is clicked. This happens on the click event of the "Open Contact Form" button and the close button. The modal remains hidden by default until triggered.

 3. Form Validation on Submission
When I submit the contact form, it validates the input fields to ensure they are filled out and that the email format is correct. I added an event listener to the form that checks if the fields are empty and uses a regular expression to validate the email format. This occurs on the submit event of the contact form. If validation fails, an alert is shown, and the form submission is prevented.

4. Hover Effect on Sections
When I hover over a section, it gets a shadow effect to indicate interactivity. I applied a CSS hover effect that adds a box shadow to the section when the mouse is over it. This happens on the hover event of the section elements. The effect is removed when the mouse leaves the section.

5. Responsive Layout Adjustments
The layout adjusts for smaller screens to ensure usability on mobile devices. I used CSS media queries to change the display of navigation links and modal content width based on the screen size. This occurs when the viewport width is less than 600 pixels. The layout remains user-friendly and accessible on all devices.
