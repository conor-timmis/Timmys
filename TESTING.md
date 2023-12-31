# Testing

Return back to the [README.md](README.md) file.


## Code Validation


Below I have linked all the necessary screenshots to validate my code:
- [Home Page Validation](documentation/testing/indexcheck.png) with the HTML W3C Validator
- [Contact Page Validation](documentation/testing/contactcheck.png) with the HTML W3C Validator
- [Confirmation Page Validation](documentation/testing/confirmationcheck.png) with the HTML W3C Validator
- [Style Sheet Validation](documentation/testing/csscheck.png) with the Jigsaw W3C Validator

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Page | Link | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fconor-timmis.github.io%2FTimmys%2Findex.html) | ![screenshot](documentation/testing/indexcheck.png) | No errors or warnings to show. |
| Contact | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fconor-timmis.github.io%2FTimmys%2Fcontact.html) | ![screenshot](documentation/testing/contactcheck.png) | No errors or warnings to show. |
| Confirmation | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fconor-timmis.github.io%2FTimmys%2Fconfirmation.html) | ![screenshot](documentation/testing/confirmationcheck.png) | No errors or warnings to show. |


### CSS


I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| File | Link | Screenshot | Notes |
| --- | --- | --- | --- |
| Style Sheet | [Jigsaw Page](http://jigsaw.w3.org/css-validator/validator?lang=en&profile=css3svg&uri=https%3A%2F%2Fconor-timmis.github.io%2FTimmys%2F&usermedium=all&vextwarning=&warning=1) | ![screenshot](documentation/testing/csscheck.png) | No errors found. |


## Browser Compatibility


I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | Contact | Notes |
| --- | --- | --- | --- |
| Firefox | ![screenshot](documentation/compatibility/firefoxindex.png) | ![screenshot](documentation/compatibility/firefoxcontact.png) | Works as expected |
| Chrome | ![screenshot](documentation/compatibility/chromeindex.png) | ![screenshot](documentation/compatibility/chromecontact.png) | Shows minor errors (no autocomplete attribute on contact form) and JS errors from iFrames |
| Edge | ![screenshot](documentation/compatibility/edgeindex.png) | ![screenshot](documentation/compatibility/edgecontact.png) | Works as expected, though shows tracking errors from Google (iFrames) |


## Responsiveness


I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Home | Contact | Notes |
| --- | --- | --- | --- |
| Mobile (DevTools) | ![Home](documentation/responsiveness/mobilehome.png) | ![Contact](documentation/responsiveness/mobilecontact.png) | Works as expected |
| Tablet (DevTools) | ![Home](documentation/responsiveness/tablethome.png) | ![Contact](documentation/responsiveness/tabletcontact.png) | Works as expected |
| Desktop | ![Home](documentation/responsiveness/desktophome.png) | ![Contact](documentation/responsiveness/desktopcontact.png) | Works as expected |
| XL Monitor | ![Home](documentation/responsiveness/xlhome.png) | ![Contact](documentation/responsiveness/xlcontact.png) | Works as intended |
| 4K Monitor | ![Home](documentation/responsiveness/4khome.png) | ![Contact](documentation/responsiveness/4kcontact.png) | Noticeable scaling issues |


## Lighthouse Audit


I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Desktop | Mobile | Notes |
| --- | --- | --- | --- |
| Home | ![Desktop](documentation/audit/desktophome.png) | ![Mobile](documentation/audit/mobilehome.png) | Desktop minor warnings, mobile has major warnings |
| Contact | ![Desktop](documentation/audit/desktopcontact.png) | ![Mobile](documentation/audit/mobilecontact.png) | Few minor warnings for both versions |
| Confirmation | ![Desktop](documentation/audit/desktopconfirmation.png) | ![Mobile](documentation/audit/mobileconfirmation.png) | Few minor issues regarding accessibility (only accessible by submitting form on Contact) |


## Bugs

### Unfixed Bugs

Due to the Youtube iFrame, there are console errors coming from youtube which I have no control of.

There are no additional bugs that I am aware of.