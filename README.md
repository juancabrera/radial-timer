radialTimer();
=============
A Javascript method that creates a CSS radial timer/countdown with progress bar.

### Usage
#### Javascript
```javascript
	var Timer;
	Timer = new radialTimer();
	Timer.init(20); // set the timer with 20 seconds
```
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