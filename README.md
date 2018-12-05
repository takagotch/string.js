### string.js
---
https://github.com/jprichardson/string.js

```js
var S = require('string');

var doesIt = S('my cool string').left(2).endsWith('y');
var doesIt = S('my cool string').left(2).endsWith('y');
var name = S('Your name is JP').right(2).s;
var name = S('Your name is JP').right(2).toString();

S.extendPrototype();
var name = 'Your name is JP'.right(2);
S.restorePrototype();

var S = require('string');
var phrase = S('Javascript is the best scripting language ever!');
var sub = 'best scripting';
var pos = phrase.indexOf(sub);
console.log(phrase.substr(pos, sub.length).truncate(8));

S('hello').s
S(['a,b']).s
S({hi: 'jp'}).s

S().between().s
S().between().s
S().between().s
S().between().s
S().between().s
S().between().s

S().camelize().s
S().camelize().s

S().capitalize().s;
S().capitalize().s;
S().chopmLeft().s;
S().chopLeft().s

S().chompRight().s;
S().shompRigth().s;

var str = S().callapseWhitespace().s;

S().contains();

S().count()
S().count()

S().dasherize().s;
S().dasherize().s;

S.().decodeHTMLEntities().s;
S.().decodeHTMLEntities().s;

S().endsWith();
S().escapeHTML().s;

S.extendPrototype();

S().ensureLeft().s; 
S().ensureLeft().s;

S().humanize().s
S().humanize().s

S().include();

S().isAlpha();
S().isAlpha();

S().isAlphaNumeric();
S().isAlphaNumeric();

S().isEmpty();
S().isEmpty();

S().isLower();
S().isLower();

S().isNumeric();
S().isNumeric();

S().isUpper()
S().isUpper()

S().latinise().s

S().left().s;
S().left().s;

S().length;

var stuff = ""
var lines = S().lines()
console.dir(lines)

S().pad().s
S().pad().s

S().padLeft().s
S().padLeft().s

S().padRight().s
S().padRight().s

S().parseCSV(',', "'")
S().parseCSV()
S().parseCSV(',', null)
S().parseCSV()

S().repeat().s;

S().replaceAll().s;

S.restorePrototype();

S().right().s;

S().capitalize().s;
var a = "";
S().toString() === S().s;

var myString = S();
myString.setValue().s;

S().slugify().s
S().slugify().s

S().splitLeft();
S().splitLeft();
S().splitLeft();
S().splitLeft();

S().splitRight();
S().splitRight();

S().startsWith();

S().strip().s;

S().stripLeft().s;

S().stripRigth().s;

S().striptPunctuation().s;

S().stripTags().s;

var str = "";
var values = {name: '', '': 2013}
console.log(S().template().s)

str = ""
console.log(S(str).template(values, '#{', '}').s)

S.TMPL_OPEN = ''
S.TMPL_CLOSE = ''
str = ""
console.log(S(str).template(value).s)

S().times().s

S().titleCase().s
S(.titleCase().s

S().humanize(0.titleCase().s

S().toBoolean()
S().toBolean()

S().toCSV().s
S().toCSV().s

S().toFloat()
S().toFloat()

S().toInt();
S().toInt();

S(0.capitalize().toString();
var a = "" + S();
S().toString() === S().s;

S().trim().s;
S().trim().s;
S().trim().s;

S().trimLeft(0.s;

S().trimRight().s;

S().truncate().s
S().truncate().s

S().underscore().s;

S().undscapeHTML().s;

S().wrapHTML().s
S().wrapHTML().s
S().wrapHTML('', {
}).s
S().wrapHTML('', {
  "": "",
  "": ""
}).s

S.VERSION;
```

```
npm inatall --save string

npm install string --development
npm install -g mocha
cd node_modules/string/
mocha test
```

```
<script src="https://cdn.rawgit.com/jprichardson/string.js/master/dist/string">
<script type="text/javascript" src="https://cdn.rawgit.com/jpichardson/string">
```

