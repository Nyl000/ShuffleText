# ShuffleText
A jquery plugin to print text/html with a "smart" shuffle transition

__demo__: http://www.nyl.graphics/shuffletext/demo/

### Installation
__By Downloading files:__

```html
<script src="https://code.jquery.com/jquery-1.12.3.min.js" integrity="sha256-aaODHAgvwQW1bFOGXMeX+pC4PZIPsvn2h1sArYOhgXQ="   crossorigin="anonymous"></script>
<script src="js/shuffletext/js/shuffletext.js"></script>
```


### Examples

__Basic usage__

```javascript
$('#text').ShuffleText([
	'First Text',
	'Second Text',
	'...'
]);
```
__Infinite loop__

```javascript
$('#text').ShuffleText([
	'First Text',
	'Second Text',
	'...'
], {loop: true);
```

__Infinite loop with a custom delay between each text__

```javascript
$('#text').ShuffleText([
	'First Text',
	'Second Text',
	'...'
], {loop: true, delay: '5000');
```

### Options

Coming Soon...

