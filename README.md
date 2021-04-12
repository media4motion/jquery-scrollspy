# jquery-scrollspy
jQuery Plugin for a ScrollSpy Navigation.

## Installation
Download [jquery.scrollspy.js](https://raw.githubusercontent.com/media4motion/jquery-scrollspy/main/jquery.scrollspy.js) from GitHub then put into your project folder.

Make sure to include jquery.scrollspy.js script file after jquery.js.

## Usage

```html
<script type="text/javascript" src="./js/jquery.scrollspy.js"></script>

<nav class="nav-element">
    <a href="#first">First Anchor</a>
    <a href="#second">Second Anchor</a>
</nav>

<div id="first">
    <!-- content -->
</div>
<div id="second">
    <!-- content -->
</div>

<script type="text/javascript">
    $('.nav-element').scrollSpy();
</script>
```
## Options
```javascript
$('.nav-element').scrollSpy({
    offset: 100, // default: 0
    offsetElement: '.sticky-header', // default: null
    activeClass: 'selected', // given to nav anchor of current position. default: 'active'
    anchors: '.spy-link', // anchor selector. default: 'a[href*=\\#]'
    scrollDuration: 800, // default: 0
    scrollEasing: 'easeInBack' // requires jQuery UI! default: 'swing'
});
```

## Demo
https://codepen.io/m4m-simon/pen/GRrQYKv
## Author
Simon Menzel [media4motion.com](https://media4motion.com) | [GitHub](https://github.com/m4m-simon)