radialTimer();
=============
A Javascript method that creates a CSS radial timer/countdown with progress bar.

### Usage
#### HTML
```html
<div class="radialtimer" id="timer"></div>
```
#### Javascript
```javascript
var Timer;
Timer = new radialTimer();
Timer.init("timer", 20); // set the timer with 20 seconds
```
The first element is the container id where it will place the timer and the second one is the number of seconds that the timer will count.
### Build
#### SCSS
```
cd build/
compass watch
```
#### HAML
```
cd build/
ruby haml_watch.rb .
```
### Demo
[http://juancabrera.github.io/radial-timer/](http://juancabrera.github.io/radial-timer/)