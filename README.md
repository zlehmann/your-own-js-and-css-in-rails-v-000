# Your Own Js And Css In Rails

## Objectives

1. Write your own CSS and integrate it into the asset pipeline and use it in views.
2. Write your own JS and integrate it into the asset pipeline and use it in views.

## Objectives

We just want to test a student's ability to define some JS functions and bind them to dom elements and execute them.

I'd test for this by basically trying to javascript.execute from a capybara test that asserts that there is no error of the function did what it wanted. Not sure of a perfect example for this but like if there was a "Hide" link that added display none I'd manually have capybara click on that link and then introspect on the visibility or CSS property. If you can check if a function is defined that'd workt oo.

Same for CSS - get them to write some classes and styles and then write tests that ensure those classes and styles are applied to DOM and the DOM has the correct styling.

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/your-own-js-and-css-in-rails' title='Your Own Js And Css In Rails'>Your Own Js And Css In Rails</a> on Learn.co and start learning to code for free.</p>
