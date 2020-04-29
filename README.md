# pure-javascript-slide-methods

Pure Javascript Slide methods

## Example

```HTML
<div id="target">
	<h1>Pure JavaScript Slide Methods</h1>
</div>
<div class="triggers">
	<button id="triggerUp">slideUp</button>
	<button id="triggerDown">slideDown</button>
	<button id="triggerToggle">slideToggle</button>
</div>
```

```JS
document.getElementById("triggerUp").addEventListener('click', function() {
	slideUp(document.getElementById("target"), 1000);
});

document.getElementById("triggerDown").addEventListener('click', function() {
	slideDown(document.getElementById("target"), 1000);
});

document.getElementById("triggerToggle").addEventListener('click', function() {
	slideToggle(document.getElementById("target"), 1000);
});
```
