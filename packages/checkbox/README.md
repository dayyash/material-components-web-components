# mwc-checkbox
A [Material Components](https://material.io/components/) icon implementation using [Web Components](https://www.webcomponents.org/introduction)

## Getting started

 * The easiest way to try out mwc-checkbox is to use one of these online tools:

    * Runs in all [supported](#supported-browsers) browsers: [StackBlitz](https://stackblitz.com/edit/mwc-icon-example?file=index.js), [Glitch](https://glitch.com/edit/#!/mwc-icon-example?path=index.html)

    * Runs in browsers with [JavaScript Modules](https://caniuse.com/#search=modules): [JSBin](http://jsbin.com/qibisux/edit?html,output),
    [CodePen](https://codepen.io/azakus/pen/deZLja).

* You can also copy [this HTML file](https://gist.githubusercontent.com/azakus/f01e9fc2ed04e781ad5a52ded7b296e7/raw/266f2f4f91cbfe89b2acc6ec63957b1a3cfe9b39/index.html) into a local file and run it in any browser that supports [JavaScript Modules]((https://caniuse.com/#search=modules)).

* When you're ready to use mwc-checkbox in a project, install it via [npm](https://www.npmjs.com/). To run the project in the browser, a module-compatible toolctain is required. We recommend installing the [Polymer CLI](https://github.com/Polymer/polymer-cli) and using its development server as follows.

  1. Ensure the webcomponents polyfills are included in your HTML page

      - Install webcomponents polyfills

          ```npm i @webcomponents/webcomponentsjs```

      - Add webcomponents polyfills to your HTML page

          ```<script src="@webcomponents/webcomponentsjs/webcomponents-loader.js"></script>```

  1. Add mwc-checkbox to your project:

      ```npm i @material/mwc-checkbox```

  1. Import the mwc-checkbox definition into your HTML page:

      ```<script type="module" src="@material/mwc-checkbox/index.js"></script>```

      Or into your module script:

      ```import {Checkbox} from "@material/mwc-checkbox"```

  1. Create an instance of mwc-checkbox in your HTML page, or via any framework that [supports rendering Custom Elements](https://custom-elements-everywhere.com/):

      ```<mwc-checkbox></mwc-checkbox>```

  1. Install the Polymer CLI:

      ```npm i -g polymer-cli```

  1. Run the development server and open a browser pointing to its URL:

      ```polymer serve```

  > mwc-checkbox is published on [npm](https://www.npmjs.com/package/@material/mwc-checkbox) using JavaScript Modules.
  This means it can take advantage of the standard native JavaScript module loader available in all current major browsers.
  >
  > However, since mwc-checkbox uses npm convention to reference dependencies by name, a light transform to rewrite specifiers to URLs is required to get it to run in the browser. The polymer-cli's development server `polymer serve` automatically handles this transform.

  Tools like [WebPack](https://webpack.js.org/) and [Rollup](https://rollupjs.org/) can also be used to serve and/or bundle mwc-checkbox.

## Supported Browsers

The last 2 versions of all modern browsers are supported, including
Chrome, Safari, Opera, Firefox, Edge. In addition, Internet Explorer 11 is also supported.