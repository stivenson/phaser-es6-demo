# Phaser ES6 Demo

This is small shoot'em up demo game to show how you can build a [phaser](http://phaser.io/) game with the next generaion of javascript (ES6/2015).

You can also use this as a boilerplate.

## Technology

The project is based on [Node.js](https://nodejs.org/en/), if you are not familiar with it I'd suggest to check it out first.
If you are familiar just have a look at **package.json** and gulp tasks in **tasks** folder.
If you are familiar and lazy just run:

```sh
npm i && npm run dev
```

To build production:

```sh
npm run build
```

## Structure

Source files are in **client** folder (personally I don't like **src**, in my projects usually there is a **server** folder for node server codes that's why I prefer client)

Gulp task are in **tasks** folder as separate files in **dev** and **prod** folders. There are some redundancy but in this way it is very easy to maintain, scale and copy tasks from one project to another.

Development and production builds are going to **builds** folder.

## Assets

Here you can find links about the images and audio I used.

### Sprites & Background

Spaceship and UFO

[http://millionthvector.blogspot.com.es/p/free-sprites.html](http://millionthvector.blogspot.com.es/p/free-sprites.html)

Background

[http://gamedevelopment.tutsplus.com/articles/enjoy-these-totally-free-space-based-shoot-em-up-sprites--gamedev-2368](http://gamedevelopment.tutsplus.com/articles/enjoy-these-totally-free-space-based-shoot-em-up-sprites--gamedev-2368)

### Sounds & Music

Menu

[http://opengameart.org/content/some-small-themes](http://opengameart.org/content/some-small-themes)

Play

[http://opengameart.org/content/railjet-long-seamless-loop](http://opengameart.org/content/railjet-long-seamless-loop)

Sounds

[http://opengameart.org/content/collection-gun-sounds](http://opengameart.org/content/collection-gun-sounds)

[http://opengameart.org/content/space-battle-game-sounds-astromenace](http://opengameart.org/content/space-battle-game-sounds-astromenace)

[http://opengameart.org/content/sci-fi-sound-effects-library](http://opengameart.org/content/sci-fi-sound-effects-library)


## License

Copyright © 2016 Csaba Tuncsik <csaba.tuncsik@gmail.com>

This work is free. You can redistribute it and/or modify it under the
terms of the Do What The Fuck You Want To Public License, Version 2,
as published by Sam Hocevar. See [WTFPL](http://www.wtfpl.net) ![WTFPL icon](http://i.imgur.com/AsWaQQl.png) for more details.
