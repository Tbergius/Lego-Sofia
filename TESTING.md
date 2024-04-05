# Testing and bug fixes

In order to deploy a functional site, and optimise uder experience, the site went through the test methods below. Under the testing part, you can also find a section with found bugs that were addresses.

---
## Testing

---
1. This site works well in Google Chrome, Safari, and Firefox.

- Google Chrome
![Site in Google Chrome](documents/chrome-works.png)

- Firefox
![Site in Firefox](documents/firefox-works.png)

- Safari
![Site in Safari](documents/safari-works.png)

---
2. This site works well on mobile screen sizes. It was build and tested with the "Mobile First" methodology as adviced in the "Love Running" program. I did most of the coding in Firefox, and checked for responsivenes in Firefox, changing screne sizes. At the end of a coding day, I also double checked to responsiveness in Google Chrome.  For the final test, I used "Responsive Viewer" to check all pages on the most used devices.

- Home page
![Photo of home page responsive](documents/home-responsive.png)

- Gallery page
![Photo of gallery page responsive](documents/gallery-responsive.png)

- Contact page
![Photo of contact page responsive](documents/contact-responsive.png)

---
3. Manual tests. All pages and clickable links or buttons were tested in different browsers, as well testing was performed on smaller screen sizes via the browser inspect option. There is only one page where a user can enter information, this was tested in detail. 

Contact form fields testing. Steps taken to test:

- Click on “Contact” in the menu
- Leave the Name field empty, but have the other fields with something: 
![Photo of name field test](documents/contact-name-test.png)

- Leave the phone field empty, but have the other fields with something: 
![Photo of phone number test](documents/contact-phone-test.png)

- Leave the email field empty, but have the other fields with something: 
![Photo of email test](documents/contact-email-test.png)

- Enter an email address without @, but have the other fields with something: 
![Photo of email without at test](documents/contact-email-at-test.png)

- Click on submit, and check for re-direct:
![Photo of confirmation page test](documents/confirmation-page-test.png)

4. Accessibility testing: To make sure that pages are accessible for everyone, I used the "Wave" from WebAIM. 

![Photo of wave results](documents/wave.png)

---
## Validator results

- The HTML was tested on the HTML validator with W3C
![Photo of HTML results](documents/html-validator.png)

- The CSS was tested on the CSS validator with W3C

![Photo of CSS results](documents/css-validator.png)

- Another test was performed using the Lighthouse extension in Google Chrome

![Photo of lighthouse desktop results](documents/lighthouse-desktop.png)
![Photo of lighthouse mobile results](documents/lighthouse-mobile.png)

---
## Bugs and fixes

During the coding phase and the testing phase, some bugs were found and addressed.

- Contact form, phone number field. This field was set to accept text, and not number. This was changed in the code and is now correct.

![Photo of contact phone bug](documents/contact-phone-test-bug.png)

- The contact form did not show well for screens of 280px, as I tested during coding for screens of 320px. This has been updated to include some padding.

![Photo of contact page small screens above bug](documents/ts-zen-up.png)
![Photo of contact page small screens below bug](documents/ts-zen-under.png)

- Honorable for an issue on my main page. I could not get the sections for "Cards" and "Events" to work. The events would move to the right of the cards or larger screens, no matter what I tried. Sometimes even the format would mess up and expanded the event items. With help from the cavalry, tutor John, managed to fix it my placing the items in the correct containers. An error on my part that too long to spot. #lessonlearned 

![Photo of home page event format wrong](documents/events-format.png)
![Photo of home page event format right](documents/events-right.png)
![Photo of home page event format all right](documents/events-all-right.png)