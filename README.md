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
], {loop: true});
```

__Infinite loop with a custom delay between each text__

```javascript
$('#text').ShuffleText([
	'First Text',
	'Second Text',
	'...'
], {loop: true, delay: '5000'});
```

### Options

##### loop
    Default : false
    If false, the plugin will stop at the last text
    If true, it never stop and restart the array once ended
    
##### iterations
    Default: 50
    The number of random iterations used per letter for the cursor effect

##### delay
    Default: 3000
    The delay in milliseconds between each text

##### shuffleSpeed
    Default: 0
    The delay in milliseconds between each random letters during the shuffle effect
    
#####  step
    Default: function() {}
    A callback function trigered each time a text is rendered
    
    
   
    
