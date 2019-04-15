# API Vimeo js

```js
var playVimeo = $('.js-play-vimeo');
var Player = new Vimeo.Player($selector, options);

// Button play for Vimeo
playVimeo.click(function(event) {
  event.preventDefault();
  Player.play();
});
```

Config options embed vimeo
```js
// Config options embed vimeo
var options = {
	id: $idVimeo,
	muted: false,
	title: false,
	byline: false,
	portrait: false,
	playsinline: true,
	transparent: false
};
```
    
Event Play.
```js
Player.on('play', function() {
  console.log('Played the video!');
});
```

Event Pause.
```js
Player.on('pause', function() {
  console.log('Pause the video!');
});
```

```js

```

📌 View repository Javascript — [GitHub](https://github.com/vimeo/player.js)

📌 View documentation developer — [Developer vimeo](https://developer.vimeo.com/)
 
