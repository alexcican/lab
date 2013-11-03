## Minimal sign up form
No form data is stored, or passed over to the NSA. Inspired by [iCloud’s](http://icloud.com) login form.

### How it works
Form and error checking done with pure HTML5 elements. The inputs are “halved” using pseudo-elements. Because we can’t add pseudo-elements on `<input>` we have to use an extra `<span>` for each input. For the password strength indicator, I’m using JS to add classes that specify the colour and animations using CSS3.

### Compatibility:
Tested on Mac (Chrome 30, Firefox, Safari), Chrome, Firefox, IE 8-9, iOS 7, and WP 8 (IE 10). Support for older browsers was added using JavaScript.

## Demo
http://lab.alexcican.com/minimal_signup_form

## License
https://github.com/alexcican/lab/blob/gh-pages/README.md

### http://alexcican.com