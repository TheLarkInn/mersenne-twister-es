# mersenne-twister-es

A JavaScript Implementation of MersenneTwiseter writting with ES Modules

## Disclaimer

This library is written specifically using ES Modules and JavaScript.
It is highly recommended any way for any scaled production JavaScript project that you use a bundler like [webpack](https://webpack.js.org/) for performance, however this library will only work using Node with the experimental ESM flag or Modern Browsers that support `<script type="module">`. I have no plans to bundle this in a UMD format because that defeats the purpose of using only the code actually required.

## Usage

```js
import { init, rand32 } from "mersenne-twister-es";

const seed = init();
const randomNumber = rand32();

console.log(randomNumber); // 1181416492
```

There are multiple exports that are exposed that you can use for different types of random numbers and their "types".
# mersenne-twister-es
