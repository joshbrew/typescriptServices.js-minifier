Compiles a minified dist of typescriptServices.js

How to:

Get the latest unpkg link: https://unpkg.com/typescript@latest/lib/typescriptServices.js

Rename the extension to .cjs.

Set the node externals in tinybuild.config (done here) and the global 'ts'

Bundled through the index.js with `tinybuild` or `npm i -g tinybuild & tinybuild`

Now you have a <3.3MB minified ts browser runtime compiler!

