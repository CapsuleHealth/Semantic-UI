# Semantic UI capsule fork
Fork of SemanticUI repo. See original
[readme](https://github.com/Semantic-Org/Semantic-UI/blob/master/README.md)
for more info.

## Capsule Theme
SemanticUI supports custom themes.
See [Customizing](http://learnsemantic.com/developing/customizing.html).

To see what's possible review the
[default theme](https://github.com/CapsuleHealth/Semantic-UI/tree/master/src/themes/default)
(`src/themes/default`)

The capsule theme resides at
[src/themes/capsule](https://github.com/CapsuleHealth/Semantic-UI/tree/master/src/themes/capsule).

## Running

* `npm install`
* then choose the default settings

the theme should now be available in `dist/semantic.min.css` and `dist/semantic.min.js`

## Building
If you make changes to the theme rebuild running `gulp build`.

## Deploying
Utilize [github pages](http://capsulehealth.github.io/Semantic-UI/dist/semantic.css) for this repo
in development.

Once you need to deploy to production copy `semantic.min.js` and `semantic.min.css` to the 
[brand](https://github.com/CapsuleHealth/brand) repo.
