# api documentation for  [micromatch (v2.3.11)](https://github.com/jonschlinkert/micromatch)  [![npm package](https://img.shields.io/npm/v/npmdoc-micromatch.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-micromatch) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-micromatch.svg)](https://travis-ci.org/npmdoc/node-npmdoc-micromatch)
#### Glob matching for javascript/node.js. A drop-in replacement and faster alternative to minimatch and multimatch.

[![NPM](https://nodei.co/npm/micromatch.png?downloads=true)](https://www.npmjs.com/package/micromatch)

[![apidoc](https://npmdoc.github.io/node-npmdoc-micromatch/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-micromatch_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-micromatch/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-micromatch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-micromatch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jon Schlinkert",
        "url": "https://github.com/jonschlinkert"
    },
    "bugs": {
        "url": "https://github.com/jonschlinkert/micromatch/issues"
    },
    "dependencies": {
        "arr-diff": "^2.0.0",
        "array-unique": "^0.2.1",
        "braces": "^1.8.2",
        "expand-brackets": "^0.1.4",
        "extglob": "^0.3.1",
        "filename-regex": "^2.0.0",
        "is-extglob": "^1.0.0",
        "is-glob": "^2.0.1",
        "kind-of": "^3.0.2",
        "normalize-path": "^2.0.1",
        "object.omit": "^2.0.0",
        "parse-glob": "^3.0.4",
        "regex-cache": "^0.4.2"
    },
    "description": "Glob matching for javascript/node.js. A drop-in replacement and faster alternative to minimatch and multimatch.",
    "devDependencies": {
        "benchmarked": "^0.1.4",
        "chalk": "^1.1.1",
        "gulp": "^3.9.0",
        "gulp-eslint": "^1.1.1",
        "gulp-format-md": "^0.1.8",
        "gulp-istanbul": "^0.10.1",
        "gulp-mocha": "^2.1.3",
        "minimatch": "^3.0.0",
        "minimist": "^1.2.0",
        "mocha": "^2",
        "multimatch": "^2.0.0",
        "should": "^8",
        "write": "^0.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "86677c97d1720b363431d04d0d15293bd38c1565",
        "tarball": "https://registry.npmjs.org/micromatch/-/micromatch-2.3.11.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "f194c187d04677b03047bb7d8d25643725f7a577",
    "homepage": "https://github.com/jonschlinkert/micromatch",
    "keywords": [
        "bash",
        "expand",
        "expansion",
        "expression",
        "file",
        "files",
        "filter",
        "find",
        "glob",
        "globbing",
        "globs",
        "globstar",
        "match",
        "matcher",
        "matches",
        "matching",
        "minimatch",
        "multimatch",
        "path",
        "pattern",
        "patterns",
        "regex",
        "regexp",
        "regular",
        "shell",
        "wildcard"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jonschlinkert",
            "email": "github@sellside.com"
        },
        {
            "name": "doowb",
            "email": "brian.woodward@gmail.com"
        },
        {
            "name": "es128",
            "email": "elan.shanker+npm@gmail.com"
        }
    ],
    "name": "micromatch",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jonschlinkert/micromatch.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "verb": {
        "related": {
            "list": [
                "braces",
                "expand-brackets",
                "expand-range",
                "extglob",
                "fill-range",
                "gulp-micromatch",
                "is-glob",
                "parse-glob"
            ]
        },
        "reflinks": [
            "braces",
            "expand-brackets",
            "extglob",
            "minimatch",
            "multimatch",
            "verb"
        ],
        "toc": false,
        "layout": false,
        "tasks": [
            "readme"
        ],
        "plugins": [
            "gulp-format-md"
        ],
        "lint": {
            "reflinks": true
        }
    },
    "version": "2.3.11"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module micromatch](#apidoc.module.micromatch)
1.  [function <span class="apidocSignatureSpan">micromatch.</span>any (fp, patterns, opts)](#apidoc.element.micromatch.any)
1.  [function <span class="apidocSignatureSpan">micromatch.</span>braceExpand (str, options)](#apidoc.element.micromatch.braceExpand)
1.  [function <span class="apidocSignatureSpan">micromatch.</span>braces (str, options)](#apidoc.element.micromatch.braces)
1.  [function <span class="apidocSignatureSpan">micromatch.</span>contains (fp, pattern, opts)](#apidoc.element.micromatch.contains)
1.  [function <span class="apidocSignatureSpan">micromatch.</span>expand (pattern, options)](#apidoc.element.micromatch.expand)
1.  [function <span class="apidocSignatureSpan">micromatch.</span>filter (patterns, opts)](#apidoc.element.micromatch.filter)
1.  [function <span class="apidocSignatureSpan">micromatch.</span>glob (pattern, options)](#apidoc.element.micromatch.glob)
1.  [function <span class="apidocSignatureSpan">micromatch.</span>isMatch (fp, pattern, opts)](#apidoc.element.micromatch.isMatch)
1.  [function <span class="apidocSignatureSpan">micromatch.</span>makeRe (glob, opts)](#apidoc.element.micromatch.makeRe)
1.  [function <span class="apidocSignatureSpan">micromatch.</span>match (files, pattern, opts)](#apidoc.element.micromatch.match)
1.  [function <span class="apidocSignatureSpan">micromatch.</span>matchKeys (obj, glob, options)](#apidoc.element.micromatch.matchKeys)
1.  [function <span class="apidocSignatureSpan">micromatch.</span>matcher (pattern, opts)](#apidoc.element.micromatch.matcher)
1.  object <span class="apidocSignatureSpan">micromatch.</span>glob.prototype
1.  object <span class="apidocSignatureSpan">micromatch.</span>utils

#### [module micromatch.glob](#apidoc.module.micromatch.glob)
1.  [function <span class="apidocSignatureSpan">micromatch.</span>glob (pattern, options)](#apidoc.element.micromatch.glob.glob)

#### [module micromatch.glob.prototype](#apidoc.module.micromatch.glob.prototype)
1.  [function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>_replace (a, b, escape)](#apidoc.element.micromatch.glob.prototype._replace)
1.  [function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>braces ()](#apidoc.element.micromatch.glob.prototype.braces)
1.  [function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>brackets ()](#apidoc.element.micromatch.glob.prototype.brackets)
1.  [function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>escape (str)](#apidoc.element.micromatch.glob.prototype.escape)
1.  [function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>extglob ()](#apidoc.element.micromatch.glob.prototype.extglob)
1.  [function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>init (pattern)](#apidoc.element.micromatch.glob.prototype.init)
1.  [function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>isNegated ()](#apidoc.element.micromatch.glob.prototype.isNegated)
1.  [function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>parse (pattern)](#apidoc.element.micromatch.glob.prototype.parse)
1.  [function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>track (msg)](#apidoc.element.micromatch.glob.prototype.track)
1.  [function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>unescape (str)](#apidoc.element.micromatch.glob.prototype.unescape)

#### [module micromatch.utils](#apidoc.module.micromatch.utils)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>arrayify (val)](#apidoc.element.micromatch.utils.arrayify)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>braces (str, options)](#apidoc.element.micromatch.utils.braces)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>brackets (str)](#apidoc.element.micromatch.utils.brackets)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>cache (fn, str, opts)](#apidoc.element.micromatch.utils.cache)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>diff (arr, arrays)](#apidoc.element.micromatch.utils.diff)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>escapePath (fp)](#apidoc.element.micromatch.utils.escapePath)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>escapeRe (str)](#apidoc.element.micromatch.utils.escapeRe)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>extglob (str, opts)](#apidoc.element.micromatch.utils.extglob)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>filename (fp)](#apidoc.element.micromatch.utils.filename)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>hasFilename (re)](#apidoc.element.micromatch.utils.hasFilename)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>hasPath (pattern, opts)](#apidoc.element.micromatch.utils.hasPath)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>isExtglob (str)](#apidoc.element.micromatch.utils.isExtglob)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>isGlob (str)](#apidoc.element.micromatch.utils.isGlob)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>isPath (pattern, opts)](#apidoc.element.micromatch.utils.isPath)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>matchPath (pattern, opts)](#apidoc.element.micromatch.utils.matchPath)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>normalize (str, stripTrailing)](#apidoc.element.micromatch.utils.normalize)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>omit (obj, keys)](#apidoc.element.micromatch.utils.omit)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>parseGlob (glob)](#apidoc.element.micromatch.utils.parseGlob)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>typeOf (val)](#apidoc.element.micromatch.utils.typeOf)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>unescapeGlob (fp)](#apidoc.element.micromatch.utils.unescapeGlob)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>unique (arr)](#apidoc.element.micromatch.utils.unique)
1.  [function <span class="apidocSignatureSpan">micromatch.utils.</span>unixify (fp, opts)](#apidoc.element.micromatch.utils.unixify)



# <a name="apidoc.module.micromatch"></a>[module micromatch](#apidoc.module.micromatch)

#### <a name="apidoc.element.micromatch.any"></a>[function <span class="apidocSignatureSpan">micromatch.</span>any (fp, patterns, opts)](#apidoc.element.micromatch.any)
- description and source-code
```javascript
function any(fp, patterns, opts) {
  if (!Array.isArray(patterns) && typeof patterns !== 'string') {
    throw new TypeError(msg('any', 'patterns', 'a string or array'));
  }

  patterns = utils.arrayify(patterns);
  var len = patterns.length;

  fp = utils.unixify(fp, opts);
  while (len--) {
    var isMatch = matcher(patterns[len], opts);
    if (isMatch(fp)) {
      return true;
    }
  }
  return false;
}
```
- example usage
```shell
...

### Features

* [Drop-in replacement](#switch-from-minimatch) for [minimatch](https://github.com/isaacs/minimatch) and [multimatch](https://github
.com/sindresorhus/multimatch)
* Built-in support for multiple glob patterns, like '['foo/*.js', '!bar.js']'
* [Brace Expansion](https://github.com/jonschlinkert/braces) ('foo/bar-{1..5}.md', 'one/{two,three}/four.md')
* Typical glob patterns, like '**/*', 'a/b/*.js', or '['foo/*.js', '!bar.js']'
* Methods like '.isMatch()', '.contains()' and '.any()'

**Extended globbing features:**

* Logical 'OR' ('foo/bar/(abc|xyz).js')
* Regex character classes ('foo/bar/baz-[1-5].js')
* POSIX [bracket expressions](https://github.com/jonschlinkert/expand-brackets) ('**/[[:alpha:][:digit:]]/')
* [extglobs](https://github.com/jonschlinkert/extglob) ('**/+(x|y)', '!(a|b)', etc).
...
```

#### <a name="apidoc.element.micromatch.braceExpand"></a>[function <span class="apidocSignatureSpan">micromatch.</span>braceExpand (str, options)](#apidoc.element.micromatch.braceExpand)
- description and source-code
```javascript
braceExpand = function (str, options) {
  if (typeof str !== 'string') {
    throw new Error('braces expects a string');
  }
  return braces(str, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.micromatch.braces"></a>[function <span class="apidocSignatureSpan">micromatch.</span>braces (str, options)](#apidoc.element.micromatch.braces)
- description and source-code
```javascript
braces = function (str, options) {
  if (typeof str !== 'string') {
    throw new Error('braces expects a string');
  }
  return braces(str, options);
}
```
- example usage
```shell
...
/**
 * Extended globs
 */

// expand braces, e.g '{1..5}'
glob.track('before braces');
if (tok.is.braces) {
  glob.braces();
}
glob.track('after braces');

// expand extglobs, e.g 'foo/!(a|b)'
glob.track('before extglob');
if (tok.is.extglob) {
  glob.extglob();
...
```

#### <a name="apidoc.element.micromatch.contains"></a>[function <span class="apidocSignatureSpan">micromatch.</span>contains (fp, pattern, opts)](#apidoc.element.micromatch.contains)
- description and source-code
```javascript
function contains(fp, pattern, opts) {
  if (typeof fp !== 'string') {
    throw new TypeError(msg('contains', 'pattern', 'a string'));
  }

  opts = opts || {};
  opts.contains = (pattern !== '');
  fp = utils.unixify(fp, opts);

  if (opts.contains && !utils.isGlob(pattern)) {
    return fp.indexOf(pattern) !== -1;
  }
  return matcher(pattern, opts)(fp);
}
```
- example usage
```shell
...

### Features

* [Drop-in replacement](#switch-from-minimatch) for [minimatch](https://github.com/isaacs/minimatch) and [multimatch](https://github
.com/sindresorhus/multimatch)
* Built-in support for multiple glob patterns, like '['foo/*.js', '!bar.js']'
* [Brace Expansion](https://github.com/jonschlinkert/braces) ('foo/bar-{1..5}.md', 'one/{two,three}/four.md')
* Typical glob patterns, like '**/*', 'a/b/*.js', or '['foo/*.js', '!bar.js']'
* Methods like '.isMatch()', '.contains()' and '.any()'

**Extended globbing features:**

* Logical 'OR' ('foo/bar/(abc|xyz).js')
* Regex character classes ('foo/bar/baz-[1-5].js')
* POSIX [bracket expressions](https://github.com/jonschlinkert/expand-brackets) ('**/[[:alpha:][:digit:]]/')
* [extglobs](https://github.com/jonschlinkert/extglob) ('**/+(x|y)', '!(a|b)', etc).
...
```

#### <a name="apidoc.element.micromatch.expand"></a>[function <span class="apidocSignatureSpan">micromatch.</span>expand (pattern, options)](#apidoc.element.micromatch.expand)
- description and source-code
```javascript
function expand(pattern, options) {
  if (typeof pattern !== 'string') {
    throw new TypeError('micromatch.expand(): argument should be a string.');
  }

  var glob = new Glob(pattern, options || {});
  var opts = glob.options;

  if (!utils.isGlob(pattern)) {
    glob.pattern = glob.pattern.replace(/([\/.])/g, '\\$1');
    return glob;
  }

  glob.pattern = glob.pattern.replace(/(\+)(?!\()/g, '\\$1');
  glob.pattern = glob.pattern.split('$').join('\\$');

  if (typeof opts.braces !== 'boolean' && typeof opts.nobraces !== 'boolean') {
    opts.braces = true;
  }

  if (glob.pattern === '.*') {
    return {
      pattern: '\\.' + star,
      tokens: tok,
      options: opts
    };
  }

  if (glob.pattern === '*') {
    return {
      pattern: oneStar(opts.dot),
      tokens: tok,
      options: opts
    };
  }

  // parse the glob pattern into tokens
  glob.parse();
  var tok = glob.tokens;
  tok.is.negated = opts.negated;

  // dotfile handling
  if ((opts.dotfiles === true || tok.is.dotfile) && opts.dot !== false) {
    opts.dotfiles = true;
    opts.dot = true;
  }

  if ((opts.dotdirs === true || tok.is.dotdir) && opts.dot !== false) {
    opts.dotdirs = true;
    opts.dot = true;
  }

  // check for braces with a dotfile pattern
  if (/[{,]\./.test(glob.pattern)) {
    opts.makeRe = false;
    opts.dot = true;
  }

  if (opts.nonegate !== true) {
    opts.negated = glob.negated;
  }

  // if the leading character is a dot or a slash, escape it
  if (glob.pattern.charAt(0) === '.' && glob.pattern.charAt(1) !== '/') {
    glob.pattern = '\\' + glob.pattern;
  }

<span class="apidocCodeCommentSpan">  /**
   * Extended globs
   */
</span>
  // expand braces, e.g '{1..5}'
  glob.track('before braces');
  if (tok.is.braces) {
    glob.braces();
  }
  glob.track('after braces');

  // expand extglobs, e.g 'foo/!(a|b)'
  glob.track('before extglob');
  if (tok.is.extglob) {
    glob.extglob();
  }
  glob.track('after extglob');

  // expand brackets, e.g '[[:alpha:]]'
  glob.track('before brackets');
  if (tok.is.brackets) {
    glob.brackets();
  }
  glob.track('after brackets');

  // special patterns
  glob._replace('[!', '[^');
  glob._replace('(?', '(%~');
  glob._replace(/\[\]/, '\\[\\]');
  glob._replace('/[', '/' + (opts.dot ? dotfiles : nodot) + '[', true);
  glob._replace('/?', '/' + (opts.dot ? dotfiles : nodot) + '[^/]', true);
  glob._replace('/.', '/(?=.)\\.', true);

  // windows drives
  glob._replace(/^(\w):([\\\/]+?)/gi, '(?=.)$1:$2', true);

  // negate slashes in exclusion ranges
  if (glob.pattern.indexOf('[^') !== -1) {
    glob.pattern = negateSlash(glob.pattern);
  }

  if (opts.globstar !== false && glob.pattern === '**') {
    glob.pattern = globstar(opts.dot);

  } else {
    glob.pattern = balance(glob.pattern, '[', ']');
    glob.escape(glob.pattern);

    // if the pattern has '**'
    if (tok.is.globstar) {
      glob.pattern = collapse(glob.pattern, '/**');
      glob.pattern = collapse(glob.pattern, '**/');
      glob._replace('/**/', '(?:/' + globstar(opts.dot) + '/|/)', true);
      glob._replace(/\*{2,}/g, '**');

      // 'foo/*'
      glob._replace(/(\w+)\*(?!\/)/g, '$1[^/]*?', true);
      glob._replace(/\*\*\/\*(\w)/g, globstar(opts.dot) + '\\/' + (opts.dot ? dotfiles : nodot) + '[^/]*?$1', true);

      if (opts.dot !== true) {
        glob._replace(/\*\*\/(.)/g, '(?:**\\/|)$1');
      }

      // 'foo/**' or '{**,*}', but not 'foo**'
      if (tok.path.dirname !== '' || /,\*\*|\*\*,/.test(glob.orig)) {
        glob._replace('**', globstar(opts.dot), true);
      }
    }

    // ends with /*
    glob._replace(/\/\*$/, '\\/' + oneStar(opts.dot), true);
    // ends with *, no slashes
    glob._replace(/(?!\/)\*$/, star, true);
    // has 'n*.' (partial wildcard w/ file extension)
    glob._replace(/([^\/]+)\*/, '$1' + oneStar(true), true);
    // has '*'
    glob._replace('*', oneStar(opts.dot), true);
    glob._replace('?.', '?\\.', true);
    glob._replace('?:', '?:', true);

    glob._replace(/\?+/g, function(match) {
      var len = match.length;
      if (len === 1) {
        return qmark;
      }
      return qmark + '{' ...
```
- example usage
```shell
...
'''

### .expand

Returns an object with a regex-compatible string and tokens.

'''js
mm.expand('*.js');

// when 'track' is enabled (for debugging), the 'history' array is used
// to record each mutation to the glob pattern as it's converted to regex
{ options: { track: false, dot: undefined, makeRe: true, negated: false },
pattern: '(.*\\/|^)bar\\/(?:(?!(?:^|\\/)\\.).)*?',
history: [],
tokens:
...
```

#### <a name="apidoc.element.micromatch.filter"></a>[function <span class="apidocSignatureSpan">micromatch.</span>filter (patterns, opts)](#apidoc.element.micromatch.filter)
- description and source-code
```javascript
function filter(patterns, opts) {
  if (!Array.isArray(patterns) && typeof patterns !== 'string') {
    throw new TypeError(msg('filter', 'patterns', 'a string or array'));
  }

  patterns = utils.arrayify(patterns);
  var len = patterns.length, i = 0;
  var patternMatchers = Array(len);
  while (i < len) {
    patternMatchers[i] = matcher(patterns[i++], opts);
  }

  return function(fp) {
    if (fp == null) return [];
    var len = patternMatchers.length, i = 0;
    var res = true;

    fp = utils.unixify(fp, opts);
    while (i < len) {
      var fn = patternMatchers[i++];
      if (!fn(fp)) {
        res = false;
        break;
      }
    }
    return res;
  };
}
```
- example usage
```shell
...
* 'patterns' **{String|Array}**:

**Examples**

Single glob:

'''js
var fn = mm.filter('*.md');
['a.js', 'b.txt', 'c.md'].filter(fn);
//=> ['c.md']

var fn = mm.filter('[a-c]');
['a', 'b', 'c', 'd', 'e'].filter(fn);
//=> ['a', 'b', 'c']
'''
...
```

#### <a name="apidoc.element.micromatch.glob"></a>[function <span class="apidocSignatureSpan">micromatch.</span>glob (pattern, options)](#apidoc.element.micromatch.glob)
- description and source-code
```javascript
function Glob(pattern, options) {
  if (!(this instanceof Glob)) {
    return new Glob(pattern, options);
  }
  this.options = options || {};
  this.pattern = pattern;
  this.history = [];
  this.tokens = {};
  this.init(pattern);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.micromatch.isMatch"></a>[function <span class="apidocSignatureSpan">micromatch.</span>isMatch (fp, pattern, opts)](#apidoc.element.micromatch.isMatch)
- description and source-code
```javascript
function isMatch(fp, pattern, opts) {
  if (typeof fp !== 'string') {
    throw new TypeError(msg('isMatch', 'filepath', 'a string'));
  }

  fp = utils.unixify(fp, opts);
  if (utils.typeOf(pattern) === 'object') {
    return matcher(fp, pattern);
  }
  return matcher(pattern, opts)(fp);
}
```
- example usage
```shell
...

> Glob matching for javascript/node.js. A drop-in replacement and faster alternative to minimatch and multimatch.

Micromatch supports all of the same matching features as [minimatch](https://github.com/isaacs/minimatch) and [multimatch](https
://github.com/sindresorhus/multimatch).

* [mm()](#usage) is the same as [multimatch()](https://github.com/sindresorhus/multimatch)
* [mm.match()](#match) is the same as [minimatch.match()](https://github.com/isaacs/minimatch)
* use [mm.isMatch()](#ismatch) instead of [minimatch()](https://github.com/isaacs/minimatch)

## Install

Install with [npm](https://www.npmjs.com/):

'''sh
$ npm install --save micromatch
...
```

#### <a name="apidoc.element.micromatch.makeRe"></a>[function <span class="apidocSignatureSpan">micromatch.</span>makeRe (glob, opts)](#apidoc.element.micromatch.makeRe)
- description and source-code
```javascript
function makeRe(glob, opts) {
  if (utils.typeOf(glob) !== 'string') {
    throw new Error(msg('makeRe', 'glob', 'a string'));
  }
  return utils.cache(toRegex, glob, opts);
}
```
- example usage
```shell
...
'''

### .makeRe

Create a regular expression for matching file paths based on the given pattern:

'''js
mm.makeRe('*.js');
//=> /^(?:(?!\.)(?=.)[^/]*?\.js)$/
'''

## Options

### options.unixify
...
```

#### <a name="apidoc.element.micromatch.match"></a>[function <span class="apidocSignatureSpan">micromatch.</span>match (files, pattern, opts)](#apidoc.element.micromatch.match)
- description and source-code
```javascript
function match(files, pattern, opts) {
  if (utils.typeOf(files) !== 'string' && !Array.isArray(files)) {
    throw new Error(msg('match', 'files', 'a string or array'));
  }

  files = utils.arrayify(files);
  opts = opts || {};

  var negate = opts.negate || false;
  var orig = pattern;

  if (typeof pattern === 'string') {
    negate = pattern.charAt(0) === '!';
    if (negate) {
      pattern = pattern.slice(1);
    }

    // we need to remove the character regardless,
    // so the above logic is still needed
    if (opts.nonegate === true) {
      negate = false;
    }
  }

  var _isMatch = matcher(pattern, opts);
  var len = files.length, i = 0;
  var res = [];

  while (i < len) {
    var file = files[i++];
    var fp = utils.unixify(file, opts);

    if (!_isMatch(fp)) { continue; }
    res.push(fp);
  }

  if (res.length === 0) {
    if (opts.failglob === true) {
      throw new Error('micromatch.match() found no matches for: "' + orig + '".');
    }

    if (opts.nonull || opts.nullglob) {
      res.push(utils.unescapeGlob(orig));
    }
  }

  // if 'negate' was defined, diff negated files
  if (negate) { res = utils.diff(files, res); }

  // if 'ignore' was defined, diff ignored filed
  if (opts.ignore && opts.ignore.length) {
    pattern = opts.ignore;
    opts = utils.omit(opts, ['ignore']);
    res = utils.diff(res, micromatch(res, pattern, opts));
  }

  if (opts.nodupes) {
    return utils.unique(res);
  }
  return res;
}
```
- example usage
```shell
...
# micromatch [![NPM version](https://img.shields.io/npm/v/micromatch.svg?style=flat)](https://www.npmjs.com/package/micromatch) [![
NPM downloads](https://img.shields.io/npm/dm/micromatch.svg?style=flat)](https://npmjs.org/package/micromatch) [![Build Status](
https://img.shields.io/travis/jonschlinkert/micromatch.svg?style=flat)](https://travis-ci.org/jonschlinkert/micromatch)

> Glob matching for javascript/node.js. A drop-in replacement and faster alternative to minimatch and multimatch.

Micromatch supports all of the same matching features as [minimatch](https://github.com/isaacs/minimatch) and [multimatch](https
://github.com/sindresorhus/multimatch).

* [mm()](#usage) is the same as [multimatch()](https://github.com/sindresorhus/multimatch)
* [mm.match()](#match) is the same as [minimatch.match()](https://github.com/isaacs/minimatch)
* use [mm.isMatch()](#ismatch) instead of [minimatch()](https://github.com/isaacs/minimatch)

## Install

Install with [npm](https://www.npmjs.com/):

'''sh
...
```

#### <a name="apidoc.element.micromatch.matchKeys"></a>[function <span class="apidocSignatureSpan">micromatch.</span>matchKeys (obj, glob, options)](#apidoc.element.micromatch.matchKeys)
- description and source-code
```javascript
function matchKeys(obj, glob, options) {
  if (utils.typeOf(obj) !== 'object') {
    throw new TypeError(msg('matchKeys', 'first argument', 'an object'));
  }

  var fn = matcher(glob, options);
  var res = {};

  for (var key in obj) {
    if (obj.hasOwnProperty(key) && fn(key)) {
      res[key] = obj[key];
    }
  }
  return res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.micromatch.matcher"></a>[function <span class="apidocSignatureSpan">micromatch.</span>matcher (pattern, opts)](#apidoc.element.micromatch.matcher)
- description and source-code
```javascript
function matcher(pattern, opts) {
  // pattern is a function
  if (typeof pattern === 'function') {
    return pattern;
  }
  // pattern is a regex
  if (pattern instanceof RegExp) {
    return function(fp) {
      return pattern.test(fp);
    };
  }

  if (typeof pattern !== 'string') {
    throw new TypeError(msg('matcher', 'pattern', 'a string, regex, or function'));
  }

  // strings, all the way down...
  pattern = utils.unixify(pattern, opts);

  // pattern is a non-glob string
  if (!utils.isGlob(pattern)) {
    return utils.matchPath(pattern, opts);
  }
  // pattern is a glob string
  var re = makeRe(pattern, opts);

  // 'matchBase' is defined
  if (opts && opts.matchBase) {
    return utils.hasFilename(re, opts);
  }
  // 'matchBase' is not defined
  return function(fp) {
    fp = utils.unixify(fp, opts);
    return re.test(fp);
  };
}
```
- example usage
```shell
...
* 'glob/string'
* 'regex'
* 'function'

**Example**

'''js
var isMatch = mm.matcher('*.md');
var files = [];

['a.md', 'b.txt', 'c.md'].forEach(function(fp) {
  if (isMatch(fp)) {
    files.push(fp);
  }
});
...
```



# <a name="apidoc.module.micromatch.glob"></a>[module micromatch.glob](#apidoc.module.micromatch.glob)

#### <a name="apidoc.element.micromatch.glob.glob"></a>[function <span class="apidocSignatureSpan">micromatch.</span>glob (pattern, options)](#apidoc.element.micromatch.glob.glob)
- description and source-code
```javascript
function Glob(pattern, options) {
  if (!(this instanceof Glob)) {
    return new Glob(pattern, options);
  }
  this.options = options || {};
  this.pattern = pattern;
  this.history = [];
  this.tokens = {};
  this.init(pattern);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.micromatch.glob.prototype"></a>[module micromatch.glob.prototype](#apidoc.module.micromatch.glob.prototype)

#### <a name="apidoc.element.micromatch.glob.prototype._replace"></a>[function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>_replace (a, b, escape)](#apidoc.element.micromatch.glob.prototype._replace)
- description and source-code
```javascript
_replace = function (a, b, escape) {
  this.track('before (find): "' + a + '" (replace with): "' + b + '"');
  if (escape) b = esc(b);
  if (a && b && typeof a === 'string') {
    this.pattern = this.pattern.split(a).join(b);
  } else {
    this.pattern = this.pattern.replace(a, b);
  }
  this.track('after');
}
```
- example usage
```shell
...
glob.track('before brackets');
if (tok.is.brackets) {
  glob.brackets();
}
glob.track('after brackets');

// special patterns
glob._replace('[!', '[^');
glob._replace('(?', '(%~');
glob._replace(/\[\]/, '\\[\\]');
glob._replace('/[', '/' + (opts.dot ? dotfiles : nodot) + '[', true);
glob._replace('/?', '/' + (opts.dot ? dotfiles : nodot) + '[^/]', true);
glob._replace('/.', '/(?=.)\\.', true);

// windows drives
...
```

#### <a name="apidoc.element.micromatch.glob.prototype.braces"></a>[function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>braces ()](#apidoc.element.micromatch.glob.prototype.braces)
- description and source-code
```javascript
braces = function () {
  if (this.options.nobraces !== true && this.options.nobrace !== true) {
    // naive/fast check for imbalanced characters
    var a = this.pattern.match(/[\{\(\[]/g);
    var b = this.pattern.match(/[\}\)\]]/g);

    // if imbalanced, don't optimize the pattern
    if (a && b && (a.length !== b.length)) {
      this.options.makeRe = false;
    }

    // expand brace patterns and join the resulting array
    var expanded = utils.braces(this.pattern, this.options);
    this.pattern = expanded.join('|');
  }
}
```
- example usage
```shell
...
/**
 * Extended globs
 */

// expand braces, e.g '{1..5}'
glob.track('before braces');
if (tok.is.braces) {
  glob.braces();
}
glob.track('after braces');

// expand extglobs, e.g 'foo/!(a|b)'
glob.track('before extglob');
if (tok.is.extglob) {
  glob.extglob();
...
```

#### <a name="apidoc.element.micromatch.glob.prototype.brackets"></a>[function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>brackets ()](#apidoc.element.micromatch.glob.prototype.brackets)
- description and source-code
```javascript
brackets = function () {
  if (this.options.nobrackets !== true) {
    this.pattern = utils.brackets(this.pattern);
  }
}
```
- example usage
```shell
...
  glob.extglob();
}
glob.track('after extglob');

// expand brackets, e.g '[[:alpha:]]'
glob.track('before brackets');
if (tok.is.brackets) {
  glob.brackets();
}
glob.track('after brackets');

// special patterns
glob._replace('[!', '[^');
glob._replace('(?', '(%~');
glob._replace(/\[\]/, '\\[\\]');
...
```

#### <a name="apidoc.element.micromatch.glob.prototype.escape"></a>[function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>escape (str)](#apidoc.element.micromatch.glob.prototype.escape)
- description and source-code
```javascript
escape = function (str) {
  this.track('before escape: ');
  var re = /["\\](['"]?[^"'\\]['"]?)/g;

  this.pattern = str.replace(re, function($0, $1) {
    var o = chars.ESC;
    var ch = o && o[$1];
    if (ch) {
      return ch;
    }
    if (/[a-z]/i.test($0)) {
      return $0.split('\\').join('');
    }
    return $0;
  });

  this.track('after escape: ');
}
```
- example usage
```shell
...
  }

  if (opts.globstar !== false && glob.pattern === '**') {
glob.pattern = globstar(opts.dot);

  } else {
glob.pattern = balance(glob.pattern, '[', ']');
glob.escape(glob.pattern);

// if the pattern has '**'
if (tok.is.globstar) {
  glob.pattern = collapse(glob.pattern, '/**');
  glob.pattern = collapse(glob.pattern, '**/');
  glob._replace('/**/', '(?:/' + globstar(opts.dot) + '/|/)', true);
  glob._replace(/\*{2,}/g, '**');
...
```

#### <a name="apidoc.element.micromatch.glob.prototype.extglob"></a>[function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>extglob ()](#apidoc.element.micromatch.glob.prototype.extglob)
- description and source-code
```javascript
extglob = function () {
  if (this.options.noextglob === true) return;

  if (utils.isExtglob(this.pattern)) {
    this.pattern = utils.extglob(this.pattern, {escape: true});
  }
}
```
- example usage
```shell
...
  glob.braces();
}
glob.track('after braces');

// expand extglobs, e.g 'foo/!(a|b)'
glob.track('before extglob');
if (tok.is.extglob) {
  glob.extglob();
}
glob.track('after extglob');

// expand brackets, e.g '[[:alpha:]]'
glob.track('before brackets');
if (tok.is.brackets) {
  glob.brackets();
...
```

#### <a name="apidoc.element.micromatch.glob.prototype.init"></a>[function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>init (pattern)](#apidoc.element.micromatch.glob.prototype.init)
- description and source-code
```javascript
init = function (pattern) {
  this.orig = pattern;
  this.negated = this.isNegated();
  this.options.track = this.options.track || false;
  this.options.makeRe = true;
}
```
- example usage
```shell
...
  if (!(this instanceof Glob)) {
    return new Glob(pattern, options);
  }
  this.options = options || {};
  this.pattern = pattern;
  this.history = [];
  this.tokens = {};
  this.init(pattern);
};

/**
 * Initialize defaults
 */

Glob.prototype.init = function(pattern) {
...
```

#### <a name="apidoc.element.micromatch.glob.prototype.isNegated"></a>[function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>isNegated ()](#apidoc.element.micromatch.glob.prototype.isNegated)
- description and source-code
```javascript
isNegated = function () {
  if (this.pattern.charCodeAt(0) === 33 /* '!' */) {
    this.pattern = this.pattern.slice(1);
    return true;
  }
  return false;
}
```
- example usage
```shell
...

/**
* Initialize defaults
*/

Glob.prototype.init = function(pattern) {
 this.orig = pattern;
 this.negated = this.isNegated();
 this.options.track = this.options.track || false;
 this.options.makeRe = true;
};

/**
* Push a change into 'glob.history'. Useful
* for debugging.
...
```

#### <a name="apidoc.element.micromatch.glob.prototype.parse"></a>[function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>parse (pattern)](#apidoc.element.micromatch.glob.prototype.parse)
- description and source-code
```javascript
parse = function (pattern) {
  this.tokens = utils.parseGlob(pattern || this.pattern, true);
  return this.tokens;
}
```
- example usage
```shell
...
    pattern: oneStar(opts.dot),
    tokens: tok,
    options: opts
  };
}

// parse the glob pattern into tokens
glob.parse();
var tok = glob.tokens;
tok.is.negated = opts.negated;

// dotfile handling
if ((opts.dotfiles === true || tok.is.dotfile) && opts.dot !== false) {
  opts.dotfiles = true;
  opts.dot = true;
...
```

#### <a name="apidoc.element.micromatch.glob.prototype.track"></a>[function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>track (msg)](#apidoc.element.micromatch.glob.prototype.track)
- description and source-code
```javascript
track = function (msg) {
  if (this.options.track) {
    this.history.push({msg: msg, pattern: this.pattern});
  }
}
```
- example usage
```shell
...
}

/**
 * Extended globs
 */

// expand braces, e.g '{1..5}'
glob.track('before braces');
if (tok.is.braces) {
  glob.braces();
}
glob.track('after braces');

// expand extglobs, e.g 'foo/!(a|b)'
glob.track('before extglob');
...
```

#### <a name="apidoc.element.micromatch.glob.prototype.unescape"></a>[function <span class="apidocSignatureSpan">micromatch.glob.prototype.</span>unescape (str)](#apidoc.element.micromatch.glob.prototype.unescape)
- description and source-code
```javascript
unescape = function (str) {
  var re = /__([A-Z]+)_([A-Z]+)__/g;
  this.pattern = str.replace(re, function($0, $1) {
    return chars[$1][$0];
  });
  this.pattern = unesc(this.pattern);
}
```
- example usage
```shell
...
  // '///' => '\/'
  glob._replace(/\/+/g, '\\/');
  // '\\\\\\' => '\\'
  glob._replace(/\\{2,}/g, '\\');
}

// unescape previously escaped patterns
glob.unescape(glob.pattern);
glob._replace('__UNESC_STAR__', '*');

// escape dots that follow qmarks
glob._replace('?.', '?\\.');

// remove unnecessary slashes in character classes
glob._replace('[^\\/]', qmark);
...
```



# <a name="apidoc.module.micromatch.utils"></a>[module micromatch.utils](#apidoc.module.micromatch.utils)

#### <a name="apidoc.element.micromatch.utils.arrayify"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>arrayify (val)](#apidoc.element.micromatch.utils.arrayify)
- description and source-code
```javascript
function arrayify(val) {
  return !Array.isArray(val)
    ? [val]
    : val;
}
```
- example usage
```shell
...
 */

function match(files, pattern, opts) {
if (utils.typeOf(files) !== 'string' && !Array.isArray(files)) {
  throw new Error(msg('match', 'files', 'a string or array'));
}

files = utils.arrayify(files);
opts = opts || {};

var negate = opts.negate || false;
var orig = pattern;

if (typeof pattern === 'string') {
  negate = pattern.charAt(0) === '!';
...
```

#### <a name="apidoc.element.micromatch.utils.braces"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>braces (str, options)](#apidoc.element.micromatch.utils.braces)
- description and source-code
```javascript
braces = function (str, options) {
  if (typeof str !== 'string') {
    throw new Error('braces expects a string');
  }
  return braces(str, options);
}
```
- example usage
```shell
...
/**
 * Extended globs
 */

// expand braces, e.g '{1..5}'
glob.track('before braces');
if (tok.is.braces) {
  glob.braces();
}
glob.track('after braces');

// expand extglobs, e.g 'foo/!(a|b)'
glob.track('before extglob');
if (tok.is.extglob) {
  glob.extglob();
...
```

#### <a name="apidoc.element.micromatch.utils.brackets"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>brackets (str)](#apidoc.element.micromatch.utils.brackets)
- description and source-code
```javascript
function brackets(str) {
  if (!isPosixBracket(str)) {
    return str;
  }

  var negated = false;
  if (str.indexOf('[^') !== -1) {
    negated = true;
    str = str.split('[^').join('[');
  }
  if (str.indexOf('[!') !== -1) {
    negated = true;
    str = str.split('[!').join('[');
  }

  var a = str.split('[');
  var b = str.split(']');
  var imbalanced = a.length !== b.length;

  var parts = str.split(/(?::\]\[:|\[?\[:|:\]\]?)/);
  var len = parts.length, i = 0;
  var end = '', beg = '';
  var res = [];

  // start at the end (innermost) first
  while (len--) {
    var inner = parts[i++];
    if (inner === '^[!' || inner === '[!') {
      inner = '';
      negated = true;
    }

    var prefix = negated ? '^' : '';
    var ch = POSIX[inner];

    if (ch) {
      res.push('[' + prefix + ch + ']');
    } else if (inner) {
      if (/^\[?\w-\w\]?$/.test(inner)) {
        if (i === parts.length) {
          res.push('[' + prefix + inner);
        } else if (i === 1) {
          res.push(prefix + inner + ']');
        } else {
          res.push(prefix + inner);
        }
      } else {
        if (i === 1) {
          beg += inner;
        } else if (i === parts.length) {
          end += inner;
        } else {
          res.push('[' + prefix + inner + ']');
        }
      }
    }
  }

  var result = res.join('|');
  var rlen = res.length || 1;
  if (rlen > 1) {
    result = '(?:' + result + ')';
    rlen = 1;
  }
  if (beg) {
    rlen++;
    if (beg.charAt(0) === '[') {
      if (imbalanced) {
        beg = '\\[' + beg.slice(1);
      } else {
        beg += ']';
      }
    }
    result = beg + result;
  }
  if (end) {
    rlen++;
    if (end.slice(-1) === ']') {
      if (imbalanced) {
        end = end.slice(0, end.length - 1) + '\\]';
      } else {
        end = '[' + end;
      }
    }
    result += end;
  }

  if (rlen > 1) {
    result = result.split('][').join(']|[');
    if (result.indexOf('|') !== -1 && !/\(\?/.test(result)) {
      result = '(?:' + result + ')';
    }
  }

  result = result.replace(/\[+=|=\]+/g, '\\b');
  return result;
}
```
- example usage
```shell
...
  glob.extglob();
}
glob.track('after extglob');

// expand brackets, e.g '[[:alpha:]]'
glob.track('before brackets');
if (tok.is.brackets) {
  glob.brackets();
}
glob.track('after brackets');

// special patterns
glob._replace('[!', '[^');
glob._replace('(?', '(%~');
glob._replace(/\[\]/, '\\[\\]');
...
```

#### <a name="apidoc.element.micromatch.utils.cache"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>cache (fn, str, opts)](#apidoc.element.micromatch.utils.cache)
- description and source-code
```javascript
function regexCache(fn, str, opts) {
  var key = '_default_', regex, cached;

  if (!str && !opts) {
    if (typeof fn !== 'function') {
      return fn;
    }
    return basic[key] || (basic[key] = fn(str));
  }

  var isString = typeof str === 'string';
  if (isString) {
    if (!opts) {
      return basic[str] || (basic[str] = fn(str));
    }
    key = str;
  } else {
    opts = str;
  }

  cached = cache[key];
  if (cached && equal(cached.opts, opts)) {
    return cached.regex;
  }

  memo(key, opts, (regex = fn(str, opts)));
  return regex;
}
```
- example usage
```shell
...
* @return {RegExp}
*/

function makeRe(glob, opts) {
 if (utils.typeOf(glob) !== 'string') {
   throw new Error(msg('makeRe', 'glob', 'a string'));
 }
 return utils.cache(toRegex, glob, opts);
}

/**
* Make error messages consistent. Follows this format:
*
* '''js
* msg(methodName, argNumber, nativeType);
...
```

#### <a name="apidoc.element.micromatch.utils.diff"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>diff (arr, arrays)](#apidoc.element.micromatch.utils.diff)
- description and source-code
```javascript
function diff(arr, arrays) {
  var argsLen = arguments.length;
  var len = arr.length, i = -1;
  var res = [], arrays;

  if (argsLen === 1) {
    return arr;
  }

  if (argsLen > 2) {
    arrays = flatten(slice.call(arguments, 1));
  }

  while (++i < len) {
    if (!~arrays.indexOf(arr[i])) {
      res.push(arr[i]);
    }
  }
  return res;
}
```
- example usage
```shell
...
   var glob = patterns[i++];
   if (typeof glob === 'string' && glob.charCodeAt(0) === 33 /* ! */) {
     omit.push.apply(omit, match(files, glob.slice(1), opts));
   } else {
     keep.push.apply(keep, match(files, glob, opts));
   }
 }
 return utils.diff(keep, omit);
}

/**
* Return an array of files that match the given glob pattern.
*
* This function is called by the main 'micromatch' function If you only
* need to pass a single pattern you might get very minor speed improvements
...
```

#### <a name="apidoc.element.micromatch.utils.escapePath"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>escapePath (fp)](#apidoc.element.micromatch.utils.escapePath)
- description and source-code
```javascript
function escapePath(fp) {
  return fp.replace(/[\\.]/g, '\\$&');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.micromatch.utils.escapeRe"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>escapeRe (str)](#apidoc.element.micromatch.utils.escapeRe)
- description and source-code
```javascript
function escapeRe(str) {
  return str.replace(/[-[\\$*+?.#^\s{}(|)\]]/g, '\\$&');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.micromatch.utils.extglob"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>extglob (str, opts)](#apidoc.element.micromatch.utils.extglob)
- description and source-code
```javascript
function extglob(str, opts) {
  opts = opts || {};
  var o = {}, i = 0;

  // fix common character reversals
  // '*!(.js)' => '*.!(js)'
  str = str.replace(/!\(([^\w*()])/g, '$1!(');

  // support file extension negation
  str = str.replace(/([*\/])\.!\([*]\)/g, function (m, ch) {
    if (ch === '/') {
      return escape('\\/[^.]+');
    }
    return escape('[^.]+');
  });

  // create a unique key for caching by
  // combining the string and options
  var key = str
    + String(!!opts.regex)
    + String(!!opts.contains)
    + String(!!opts.escape);

  if (cache.hasOwnProperty(key)) {
    return cache[key];
  }

  if (!(re instanceof RegExp)) {
    re = regex();
  }

  opts.negate = false;
  var m;

  while (m = re.exec(str)) {
    var prefix = m[1];
    var inner = m[3];
    if (prefix === '!') {
      opts.negate = true;
    }

    var id = '__EXTGLOB_' + (i++) + '__';
    // use the prefix of the _last_ (outtermost) pattern
    o[id] = wrap(inner, prefix, opts.escape);
    str = str.split(m[0]).join(id);
  }

  var keys = Object.keys(o);
  var len = keys.length;

  // we have to loop again to allow us to convert
  // patterns in reverse order (starting with the
  // innermost/last pattern first)
  while (len--) {
    var prop = keys[len];
    str = str.split(prop).join(o[prop]);
  }

  var result = opts.regex
    ? toRegex(str, opts.contains, opts.negate)
    : str;

  result = result.split('.').join('\\.');

  // cache the result and return it
  return (cache[key] = result);
}
```
- example usage
```shell
...
  glob.braces();
}
glob.track('after braces');

// expand extglobs, e.g 'foo/!(a|b)'
glob.track('before extglob');
if (tok.is.extglob) {
  glob.extglob();
}
glob.track('after extglob');

// expand brackets, e.g '[[:alpha:]]'
glob.track('before brackets');
if (tok.is.brackets) {
  glob.brackets();
...
```

#### <a name="apidoc.element.micromatch.utils.filename"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>filename (fp)](#apidoc.element.micromatch.utils.filename)
- description and source-code
```javascript
function filename(fp) {
  var seg = fp.match(fileRe());
  return seg && seg[0];
}
```
- example usage
```shell
...
*
* @param {RegExp} 're'
* @return {Boolean}
*/

utils.hasFilename = function hasFilename(re) {
 return function(fp) {
   var name = utils.filename(fp);
   return name && re.test(name);
 };
};

/**
* Coerce 'val' to an array
*
...
```

#### <a name="apidoc.element.micromatch.utils.hasFilename"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>hasFilename (re)](#apidoc.element.micromatch.utils.hasFilename)
- description and source-code
```javascript
function hasFilename(re) {
  return function(fp) {
    var name = utils.filename(fp);
    return name && re.test(name);
  };
}
```
- example usage
```shell
...
    return utils.matchPath(pattern, opts);
  }
  // pattern is a glob string
  var re = makeRe(pattern, opts);

  // 'matchBase' is defined
  if (opts && opts.matchBase) {
    return utils.hasFilename(re, opts);
  }
  // 'matchBase' is not defined
  return function(fp) {
    fp = utils.unixify(fp, opts);
    return re.test(fp);
  };
}
...
```

#### <a name="apidoc.element.micromatch.utils.hasPath"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>hasPath (pattern, opts)](#apidoc.element.micromatch.utils.hasPath)
- description and source-code
```javascript
function hasPath(pattern, opts) {
  return function(fp) {
    return utils.unixify(pattern, opts).indexOf(fp) !== -1;
  };
}
```
- example usage
```shell
...
*
* @param {String} 'pattern'
* @return {Function}
*/

utils.matchPath = function matchPath(pattern, opts) {
 var fn = (opts && opts.contains)
   ? utils.hasPath(pattern, opts)
   : utils.isPath(pattern, opts);
 return fn;
};

/**
* Returns a function that returns true if the given
* regex matches the 'filename' of a file path.
...
```

#### <a name="apidoc.element.micromatch.utils.isExtglob"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>isExtglob (str)](#apidoc.element.micromatch.utils.isExtglob)
- description and source-code
```javascript
function isExtglob(str) {
  return typeof str === 'string'
    && /[@?!+*]\(/.test(str);
}
```
- example usage
```shell
...
/**
* Expand bracket expressions in 'glob.pattern'
*/

Glob.prototype.extglob = function() {
 if (this.options.noextglob === true) return;

 if (utils.isExtglob(this.pattern)) {
   this.pattern = utils.extglob(this.pattern, {escape: true});
 }
};

/**
* Parse the given pattern
*/
...
```

#### <a name="apidoc.element.micromatch.utils.isGlob"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>isGlob (str)](#apidoc.element.micromatch.utils.isGlob)
- description and source-code
```javascript
function isGlob(str) {
  return typeof str === 'string'
    && (/[*!?{}(|)[\]]/.test(str)
     || isExtglob(str));
}
```
- example usage
```shell
...
   throw new TypeError(msg('contains', 'pattern', 'a string'));
 }

 opts = opts || {};
 opts.contains = (pattern !== '');
 fp = utils.unixify(fp, opts);

 if (opts.contains && !utils.isGlob(pattern)) {
   return fp.indexOf(pattern) !== -1;
 }
 return matcher(pattern, opts)(fp);
}

/**
* Returns true if a file path matches any of the
...
```

#### <a name="apidoc.element.micromatch.utils.isPath"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>isPath (pattern, opts)](#apidoc.element.micromatch.utils.isPath)
- description and source-code
```javascript
function isPath(pattern, opts) {
  opts = opts || {};
  return function(fp) {
    var unixified = utils.unixify(fp, opts);
    if(opts.nocase){
      return pattern.toLowerCase() === unixified.toLowerCase();
    }
    return pattern === unixified;
  };
}
```
- example usage
```shell
...
* @param {String} 'pattern'
* @return {Function}
*/

utils.matchPath = function matchPath(pattern, opts) {
 var fn = (opts && opts.contains)
   ? utils.hasPath(pattern, opts)
   : utils.isPath(pattern, opts);
 return fn;
};

/**
* Returns a function that returns true if the given
* regex matches the 'filename' of a file path.
*
...
```

#### <a name="apidoc.element.micromatch.utils.matchPath"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>matchPath (pattern, opts)](#apidoc.element.micromatch.utils.matchPath)
- description and source-code
```javascript
function matchPath(pattern, opts) {
  var fn = (opts && opts.contains)
    ? utils.hasPath(pattern, opts)
    : utils.isPath(pattern, opts);
  return fn;
}
```
- example usage
```shell
...
}

// strings, all the way down...
pattern = utils.unixify(pattern, opts);

// pattern is a non-glob string
if (!utils.isGlob(pattern)) {
  return utils.matchPath(pattern, opts);
}
// pattern is a glob string
var re = makeRe(pattern, opts);

// 'matchBase' is defined
if (opts && opts.matchBase) {
  return utils.hasFilename(re, opts);
...
```

#### <a name="apidoc.element.micromatch.utils.normalize"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>normalize (str, stripTrailing)](#apidoc.element.micromatch.utils.normalize)
- description and source-code
```javascript
function normalizePath(str, stripTrailing) {
  if (typeof str !== 'string') {
    throw new TypeError('expected a string');
  }
  str = str.replace(/[\\\/]+/g, '/');
  if (stripTrailing !== false) {
    str = removeTrailingSeparator(str);
  }
  return str;
}
```
- example usage
```shell
...
 * Normalize all slashes in a file path or glob pattern to
 * forward slashes.
 */

utils.unixify = function unixify(fp, opts) {
  if (opts && opts.unixify === false) return fp;
  if (opts && opts.unixify === true || win32 || path.sep === '\\') {
    return utils.normalize(fp, false);
  }
  if (opts && opts.unescape === true) {
    return fp ? fp.toString().replace(/\\(\w)/g, '$1') : '';
  }
  return fp;
};
...
```

#### <a name="apidoc.element.micromatch.utils.omit"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>omit (obj, keys)](#apidoc.element.micromatch.utils.omit)
- description and source-code
```javascript
function omit(obj, keys) {
  if (!isObject(obj)) return {};

  keys = [].concat.apply([], [].slice.call(arguments, 1));
  var last = keys[keys.length - 1];
  var res = {}, fn;

  if (typeof last === 'function') {
    fn = keys.pop();
  }

  var isFunction = typeof fn === 'function';
  if (!keys.length && !isFunction) {
    return obj;
  }

  forOwn(obj, function(value, key) {
    if (keys.indexOf(key) === -1) {

      if (!isFunction) {
        res[key] = value;
      } else if (fn(value, key, obj)) {
        res[key] = value;
      }
    }
  });
  return res;
}
```
- example usage
```shell
...

// if 'negate' was defined, diff negated files
if (negate) { res = utils.diff(files, res); }

// if 'ignore' was defined, diff ignored filed
if (opts.ignore && opts.ignore.length) {
  pattern = opts.ignore;
  opts = utils.omit(opts, ['ignore']);
  res = utils.diff(res, micromatch(res, pattern, opts));
}

if (opts.nodupes) {
  return utils.unique(res);
}
return res;
...
```

#### <a name="apidoc.element.micromatch.utils.parseGlob"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>parseGlob (glob)](#apidoc.element.micromatch.utils.parseGlob)
- description and source-code
```javascript
function parseGlob(glob) {
  if (cache.hasOwnProperty(glob)) {
    return cache[glob];
  }

  var tok = {};
  tok.orig = glob;
  tok.is = {};

  // unescape dots and slashes in braces/brackets
  glob = escape(glob);

  var parsed = findBase(glob);
  tok.is.glob = parsed.isGlob;

  tok.glob = parsed.glob;
  tok.base = parsed.base;
  var segs = /([^\/]*)$/.exec(glob);

  tok.path = {};
  tok.path.dirname = '';
  tok.path.basename = segs[1] || '';
  tok.path.dirname = glob.split(tok.path.basename).join('') || '';
  var basename = (tok.path.basename || '').split('.') || '';
  tok.path.filename = basename[0] || '';
  tok.path.extname = basename.slice(1).join('.') || '';
  tok.path.ext = '';

  if (isGlob(tok.path.dirname) && !tok.path.basename) {
    if (!/\/$/.test(tok.glob)) {
      tok.path.basename = tok.glob;
    }
    tok.path.dirname = tok.base;
  }

  if (glob.indexOf('/') === -1 && !tok.is.globstar) {
    tok.path.dirname = '';
    tok.path.basename = tok.orig;
  }

  var dot = tok.path.basename.indexOf('.');
  if (dot !== -1) {
    tok.path.filename = tok.path.basename.slice(0, dot);
    tok.path.extname = tok.path.basename.slice(dot);
  }

  if (tok.path.extname.charAt(0) === '.') {
    var exts = tok.path.extname.split('.');
    tok.path.ext = exts[exts.length - 1];
  }

  // unescape dots and slashes in braces/brackets
  tok.glob = unescape(tok.glob);
  tok.path.dirname = unescape(tok.path.dirname);
  tok.path.basename = unescape(tok.path.basename);
  tok.path.filename = unescape(tok.path.filename);
  tok.path.extname = unescape(tok.path.extname);

  // Booleans
  var is = (glob && tok.is.glob);
  tok.is.negated  = glob && glob.charAt(0) === '!';
  tok.is.extglob  = glob && extglob(glob);
  tok.is.braces   = has(is, glob, '{');
  tok.is.brackets = has(is, glob, '[:');
  tok.is.globstar = has(is, glob, '**');
  tok.is.dotfile  = dotfile(tok.path.basename) || dotfile(tok.path.filename);
  tok.is.dotdir   = dotdir(tok.path.dirname);
  return (cache[glob] = tok);
}
```
- example usage
```shell
...
};

/**
* Parse the given pattern
*/

Glob.prototype.parse = function(pattern) {
 this.tokens = utils.parseGlob(pattern || this.pattern, true);
 return this.tokens;
};

/**
* Replace 'a' with 'b'. Also tracks the change before and
* after each replacement. This is disabled by default, but
* can be enabled by setting 'options.track' to true.
...
```

#### <a name="apidoc.element.micromatch.utils.typeOf"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>typeOf (val)](#apidoc.element.micromatch.utils.typeOf)
- description and source-code
```javascript
function kindOf(val) {
  // primitivies
  if (typeof val === 'undefined') {
    return 'undefined';
  }
  if (val === null) {
    return 'null';
  }
  if (val === true || val === false || val instanceof Boolean) {
    return 'boolean';
  }
  if (typeof val === 'string' || val instanceof String) {
    return 'string';
  }
  if (typeof val === 'number' || val instanceof Number) {
    return 'number';
  }

  // functions
  if (typeof val === 'function' || val instanceof Function) {
    return 'function';
  }

  // array
  if (typeof Array.isArray !== 'undefined' && Array.isArray(val)) {
    return 'array';
  }

  // check for instances of RegExp and Date before calling 'toString'
  if (val instanceof RegExp) {
    return 'regexp';
  }
  if (val instanceof Date) {
    return 'date';
  }

  // other objects
  var type = toString.call(val);

  if (type === '[object RegExp]') {
    return 'regexp';
  }
  if (type === '[object Date]') {
    return 'date';
  }
  if (type === '[object Arguments]') {
    return 'arguments';
  }
  if (type === '[object Error]') {
    return 'error';
  }

  // buffer
  if (typeof Buffer !== 'undefined' && isBuffer(val)) {
    return 'buffer';
  }

  // es6: Map, WeakMap, Set, WeakSet
  if (type === '[object Set]') {
    return 'set';
  }
  if (type === '[object WeakSet]') {
    return 'weakset';
  }
  if (type === '[object Map]') {
    return 'map';
  }
  if (type === '[object WeakMap]') {
    return 'weakmap';
  }
  if (type === '[object Symbol]') {
    return 'symbol';
  }

  // typed arrays
  if (type === '[object Int8Array]') {
    return 'int8array';
  }
  if (type === '[object Uint8Array]') {
    return 'uint8array';
  }
  if (type === '[object Uint8ClampedArray]') {
    return 'uint8clampedarray';
  }
  if (type === '[object Int16Array]') {
    return 'int16array';
  }
  if (type === '[object Uint16Array]') {
    return 'uint16array';
  }
  if (type === '[object Int32Array]') {
    return 'int32array';
  }
  if (type === '[object Uint32Array]') {
    return 'uint32array';
  }
  if (type === '[object Float32Array]') {
    return 'float32array';
  }
  if (type === '[object Float64Array]') {
    return 'float64array';
  }

  // must be a plain object
  return 'object';
}
```
- example usage
```shell
...
 * @param  {Array} 'files'
 * @param  {String} 'pattern'
 * @param  {Object} 'options'
 * @return {Array}
 */

function match(files, pattern, opts) {
if (utils.typeOf(files) !== 'string' && !Array.isArray(files)) {
  throw new Error(msg('match', 'files', 'a string or array'));
}

files = utils.arrayify(files);
opts = opts || {};

var negate = opts.negate || false;
...
```

#### <a name="apidoc.element.micromatch.utils.unescapeGlob"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>unescapeGlob (fp)](#apidoc.element.micromatch.utils.unescapeGlob)
- description and source-code
```javascript
function unescapeGlob(fp) {
  return fp.replace(/[\\"']/g, '');
}
```
- example usage
```shell
...

if (res.length === 0) {
  if (opts.failglob === true) {
    throw new Error('micromatch.match() found no matches for: "' + orig + '".');
  }

  if (opts.nonull || opts.nullglob) {
    res.push(utils.unescapeGlob(orig));
  }
}

// if 'negate' was defined, diff negated files
if (negate) { res = utils.diff(files, res); }

// if 'ignore' was defined, diff ignored filed
...
```

#### <a name="apidoc.element.micromatch.utils.unique"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>unique (arr)](#apidoc.element.micromatch.utils.unique)
- description and source-code
```javascript
function unique(arr) {
  if (!Array.isArray(arr)) {
    throw new TypeError('array-unique expects an array.');
  }

  var len = arr.length;
  var i = -1;

  while (i++ < len) {
    var j = i + 1;

    for (; j < arr.length; ++j) {
      if (arr[i] === arr[j]) {
        arr.splice(j--, 1);
      }
    }
  }
  return arr;
}
```
- example usage
```shell
...
 if (opts.ignore && opts.ignore.length) {
   pattern = opts.ignore;
   opts = utils.omit(opts, ['ignore']);
   res = utils.diff(res, micromatch(res, pattern, opts));
 }

 if (opts.nodupes) {
   return utils.unique(res);
 }
 return res;
}

/**
* Returns a function that takes a glob pattern or array of glob patterns
* to be used with 'Array#filter()'. (Internally this function generates
...
```

#### <a name="apidoc.element.micromatch.utils.unixify"></a>[function <span class="apidocSignatureSpan">micromatch.utils.</span>unixify (fp, opts)](#apidoc.element.micromatch.utils.unixify)
- description and source-code
```javascript
function unixify(fp, opts) {
  if (opts && opts.unixify === false) return fp;
  if (opts && opts.unixify === true || win32 || path.sep === '\\') {
    return utils.normalize(fp, false);
  }
  if (opts && opts.unescape === true) {
    return fp ? fp.toString().replace(/\\(\w)/g, '$1') : '';
  }
  return fp;
}
```
- example usage
```shell
...

var _isMatch = matcher(pattern, opts);
var len = files.length, i = 0;
var res = [];

while (i < len) {
  var file = files[i++];
  var fp = utils.unixify(file, opts);

  if (!_isMatch(fp)) { continue; }
  res.push(fp);
}

if (res.length === 0) {
  if (opts.failglob === true) {
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
