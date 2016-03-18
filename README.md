# awesome-yaml

YAML awesomeness

> A curated list of YAML resources

## Overview

### YAML is **underrated**
* Most developers who use it had a negative first-impression of the format, usually because of the syntax.
* Some dislike the fact that YAML depends on indentation for specifying scope.
* Some consider YAML to be superfluous: "XML and JSON fit the bill nicely enough".
* Some have either never heard of YAML or are intimidated by the fact that it is not as famous as JSON or XML.

### YAML is a **supserset of JSON**
* Does JSON support comments? ... **NO** 
   * http://stackoverflow.com/questions/244777/can-i-use-comments-inside-a-json-file
   * http://stackoverflow.com/questions/26775073/how-to-add-comments-in-json-file
   * http://stackoverflow.com/questions/11195101/add-json-file-comments
* Does JSON support comments? ... **YES** 
   * To get JSON with comments, just use YAML instead of JSON
   * YAML is a superset of JSON
      ```
      > {
      >   "json": [
      >     "fat and rigid"
      >   ],
      >   "yaml": [
      >     "skinny and flexible"
      >   ],
      >   "object": {
      >     "array": [
      >       {
      >         "null_value": null
      >       },
      >       {
      >         "boolean": true
      >       },
      >       {
      >         "integer": 1
      >       }
      >     ]
      >   }
      > }
      ```

## Specification

- [Official site] (http://www.yaml.org/)
- [Merge-keys spec] (http://yaml.org/type/merge.html)

## Documentation and resources

- [Discussion Archives](https://sourceforge.net/p/yaml/mailman/yaml-core)
- [Stackoverflow](http://stackoverflow.com/questions/tagged/yaml)

## Parsers

- [Javascript](https://github.com/nodeca/js-yaml)
    - http://nodeca.github.io/js-yaml/
- [Node.js](https://www.npmjs.com/search?q=yaml)
- [golang](https://github.com/go-yaml/yaml)

## Projects
- [Dynamic Yaml](https://github.com/dreftymac/dynamic.yaml)
- [Code Beautify](http://codebeautify.org/yaml-to-json-xml-csv)

## Mentions

- [drupal convert](https://www.drupal.org/node/1793074)
- [blog entry praising YAML over JSON](http://www.cowtowncoder.com/blog/archives/2012/04/entry_473.html)
- [After XML JSON then what?](http://www.drdobbs.com/web-development/after-xml-json-then-what/240151851)

## GISTS

* [YAML succinct tutorial from user:ddlsmurf](https://gist.github.com/dreftymac/b68fef16a468ae56e275)

## See also

* [Awesome curated](https://github.com/sindresorhus/awesome)
* [Awesome JSON](https://github.com/burningtree/awesome-json)
