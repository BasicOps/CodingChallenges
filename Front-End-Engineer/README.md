## Front End Engineer Coding Challenge ##
Create a simple HTML/Javascript page that meets the functional requirements outlined below.  Include any JavaScript libraries or third party components such that the page can be viewed by simply cloning the repository and viewing in a web browser.  You may use any combination of HTML5, CSS, DOM methods and properties, Javascript or jQuery to solve this challenge.

### Requirements ###
1 second after the page loads fade in a text input field over .5 seconds, set the focus in the input field.
As soon as the user starts typing in the input field show a button with the text 'Save' next to it.
At any time the input field is empty the button must be disabled.

When the input field contains at least one character and the user hits Enter or clicks the button the following happens:
* The button is disabled and the button text is changed to 'Saving'
* After one second the button fades out over 1 second
* One second later the input field fades out over 2 seconds
* One second later the content of the input field fades in where the input field was over 1 second
* As soon as the fade transition completes, make an API call to this endpoint: http://date.jsontest.com/
* Parse and append the date and time (or Unix epoch) returned from the enpdpoint left padded by a single space after the rendered content, formatted like so: `Month DD, YYYY at HH:MM AM/PM`
  * For example: "January 15, 2017 at 12:15 PM"

### Evaluation ###
Evaluation of your submission will be based on the following criteria. Additionally, reviewers will attempt to assess your familiarity with standard libraries as well as with language idioms.

1. Does it fulfill the basic requirements?
2. Does it follow common syntax, structural and stylistic conventions?
3. Did you document the method for setting up and running your application?
4. Did you follow the instructions for submission?
