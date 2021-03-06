# artplayer-plugin-backlight

Backlight plugin for ArtPlayer

## Demo

[Checkout the demo](https://artplayer.org/?libs=.%2Funcompiled%2Fartplayer-plugin-backlight.js&example=backlight) from Github Pages

## Install

Install with `npm`

```bash
$ npm install artplayer-plugin-backlight
```

Or install with `yarn`

```bash
$ yarn add artplayer-plugin-backlight
```

```js
import artplayerPluginBacklight from 'artplayer-plugin-backlight';
```

Or umd builds are also available

```html
<script src="artplayer-plugin-backlight.js"></script>
```

Will expose the global variable to `window.artplayerPluginBacklight`.

## Usage

```js
var art = new Artplayer({
    container: '.artplayer-app',
    url: 'path/to/video.mp4',
    plugins: [artplayerPluginBacklight],
});
```

## License

MIT © [Harvey Zack](https://sleepy.im/)
