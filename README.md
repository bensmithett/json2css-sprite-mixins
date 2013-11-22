json2css-sprite-mixins
=============

Sprite mixins from [json2css](https://github.com/twolfson/json2css)' sass template + a retina sprite mixin.

[grunt-spritesmith](https://github.com/Ensighten/spritesmith) uses json2css templates, but I'm using a slightly modified template and multiple spritesheets, so I'm extracting these mixins into a bower component. 

**Note:** The retina mixins depend on the 2x spritesheet being *exactly* twice the size of the 1x spritesheet. That means individual 1x sprites should be exactly half the size of 2x sprites before combining them with grunt-spritesmith.
