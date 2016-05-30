# GRA Default Avatars

This directory contains the Adobe Photoshop file with the artwork used to generate the default avatars for the [Great Reading Adventure](https://github.com/MCLD/greatreadingadventure) in different layers. In order to create these avatars using [Glitch](http://www.glitchthegame.com/public-domain-game-art/) assets without reverse engineering the Flash-based wardrobe/vanity stuff, the [Eleven wardrobe/vanity](http://elevengiants.com/customize/index.html) was used with some hacky screenshots.

## Process

The methodology used for generating the default GRA avatars is as follows:

1. Load <http://elevengiants.com/customize/index.html>
2. Open the developer tools or inspector in your browser
3. Adjust the Shockwave object (click the avatar) to be 280x400 pixels in size
4. Scroll down to the "wardrobe-tabs" div and add a `style="margin-top: 80 px;"`
5. Find the "wardrobe-catalog" div and add a `style="margin-top: 530px;"`
6. Select the avatar parts you want doing your best to keep them isolated
7. Screenshot the avatar
8. Bring the image into the PSD as a layer and erase the unnecessary bits

## Thanks

* [Tiny Speck](https://github.com/tinyspeck) (makers of [Slack](https://slack.com)) for releasing the [Glitch](http://www.glitchthegame.com/public-domain-game-art/) assets!
* [Eleven](http://elevengiants.com) for their [Wardrobe/Vanity](http://elevengiants.com/customize/index.html)!

## License

Code released under the [MIT license](https://github.com/haraldnagel/gra-default-avatars/blob/master/LICENSE).
