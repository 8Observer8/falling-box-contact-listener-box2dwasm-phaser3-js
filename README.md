Buy me a chicory coffee: https://boosty.to/ivan_8observer8/donate This service supports PayPal.

Live demo: https://8observer8.github.io/webgl10-js/falling-box-contact-listener-box2dwasm-phaser3-js/

Playgrounds:

- Replit: https://replit.com/@8Observer8/Falling-box-contact-listener-Box2D-WASM-Phaser3-JS
- Plunker: https://plnkr.co/edit/HOM99w4jXUSJd3q7?preview
- Glitch: https://glitch.com/edit/#!/marbled-coherent-archer

Topic and discussions:

- Phaser topic: https://phaser.discourse.group/t/basic-examples-of-using-box2d-wasm-with-phaser-3-in-javascript/13430
- Phaser discussion: https://github.com/photonstorm/phaser/discussions/6556
- Box2D-WASM discussion: https://github.com/Birch-san/box2d-wasm/discussions/68

![falling-box-contact-listener-box2dwasm-phaser3-js](https://github.com/8Observer8/falling-box-contact-listener-box2dwasm-phaser3-js/assets/3908473/890e6a3d-b98e-4282-a8fb-e25dc287cbcd)

Instruction for building and running the project in debug and release using Rollup:

- Install these packages globally with the command:

> npm i -g http-server rollup uglify-js

- Run http-server in the project directory:

> http-server -c-1

Note. The `-c-1` key allows you to disable caching.

- Start development mode with the following command:

> npm run dev

Note. Rollup will automatically keep track of saving changes to files and build a new index.js file ready for debugging. You can debug your project step by step in the browser by setting breakpoints.

- Go to the browser and type the address: localhost:8080/index.html

- Create a compressed file ready for publishing. Stop development mode, for example, with this command Ctrl + C in CMD, if it was launched before and enter the command:

> npm run release

Note. After this command, Rollup will create a compressed index.js file. Compression is done using the uglify-js package.
