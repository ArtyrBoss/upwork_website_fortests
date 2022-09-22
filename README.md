The images of img_of_results-screen-page.html, review-text-answer-field-page.html, text-answer-field-page.html.

![img_of_results-screen-page](https://user-images.githubusercontent.com/32036402/191694927-55e3ecc5-5852-4ec6-af0e-57ecabf624f7.png)
![img_of_review-text-answer-field-page](https://user-images.githubusercontent.com/32036402/191694933-424504f1-0ff6-425c-87f9-5d0ad5356168.png)
![img_of_text-answer-field-page](https://user-images.githubusercontent.com/32036402/191694934-5edbe73c-b06b-45c0-962a-da2e2a2297af.png)


class="background-overlay" uses when question list shows up, 
it adds background dark opacity 0.3
The background-overlay is in questions-list-page.scss
to switch it you can use - visibility: visible or hidden;

To show question list use classes: 
"questions-list--off"
"questions-list--on" 
also add the "svg-arrow" class to id="svg-green-arrow" element, to rotate it.
They are in the questions-list-page.scss

To show submenu (help, send feedback), you can remove\add the "visually-hidden" class

The classes below are in a _review-multiple-choice-answers-page.scss:
.correct-selected-answer, .without-check-icon-answer, 
.answer-was-skipped, .correct-selected-answer--green-bk, 
.wrong-selected-answer 

## Info for page 8 from the UI flow doc:
just add event listener which adds class="visually-hidden" to class="tabs-for-text-answer-page"
when user taps on text field.
Those classes in the text-answer-field-page.html

## Info for the "refer-friend-page.html":
class="add-new-refer-friend" use to add a new HTML inputs field under the previous one
