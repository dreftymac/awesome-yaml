<!---
### <beg-file_info>
### document_metadata:
###   - caption: "README"
###     dmid: "uu151chariot_unveiled"
###     date: created="2019-02-26 09:33:48"
###     last: lastmod="2019-02-26 09:33:48"
###     tags: yaml,github,dreftymac
###     desc: |
###         * github awesome-yaml
###     seealso: |
###         * https://github.com/dreftymac/awesome-yaml/blob/master/README.md
###         * href="smartpath://mymedia/2014/git/github/awesome-yaml/readme.md"  find="uu151chariot_unveiled"
###         * fun link ;; href="C:/sm/docs/mydaydirs/2019/week39/desktop/screencapture-blog-mozilla-org-nfroyd-2015-09-07-standardizing-things-my-way-2019-09-29-22_18_23-uu788trive8raft.png"
###         * https://leebriggs.co.uk/blog/2019/02/07/why-are-we-templating-yaml.html
###         ## people
###         * https://twitter.com/briggsl
###         * https://leebriggs.co.uk/
###         * http://champignon.net/
###     seeinstead: |
###         * __seeinstead__
### <end-file_info>
--->

<!---
  ## other items not yet included
  * yaml+jinja search ;; https://duckduckgo.com/?q=yaml+jinja+stackoverflow&ia=web
  * people ;; http://champignon.net/
  ## Variable placholders workarounds
  * https://starkandwayne.com/blog/bashing-your-yaml/
--->

# awesome-yaml

YAML awesomeness

> A curated list of YAML resources. See also [Awesome Yaml (@datatxt)](https://github.com/datatxt/awseome-yaml)

## Overview

### YAML is **underrated**
* Some developers who use it had a negative first-impression of the format, usually because of the syntax.
* Some dislike the fact that YAML allows the use of indentation for specifying scope (although indentation is technically not required).
* Some consider YAML to be superfluous: "XML and JSON fit the bill nicely enough".
* Some have either never heard of YAML or are influenced by the fact that it is not as famous as JSON or XML.

### YAML is a **supserset of JSON**
* Does JSON support comments? ... **NO**
   * http://stackoverflow.com/questions/244777/can-i-use-comments-inside-a-json-file
   * http://stackoverflow.com/questions/26775073/how-to-add-comments-in-json-file
   * http://stackoverflow.com/questions/11195101/add-json-file-comments
* Does JSON support comments? ... **YES** (if you use YAML)
   * To get JSON with comments, just use YAML instead of JSON
   * YAML is a superset of JSON

```
## This is valid YAML syntax
## Try it out now by copy-pasting it into an online YAML parser
## http://yaml-online-parser.appspot.com/

{
 "json": [
   "fat and rigid"
 ],
 "yaml": [
   "skinny and flexible"
 ],
 "object": {
   "array": [
     {
       "null_value": null
     },
     {
       "boolean": true
     },
     {
       "integer": 1
     }
   ]
 }
}
```
* [Try it now!](http://www.yamllint.com/)


# Digging in

## Advanced
- [Advanced YAML features (@cyklo)](https://github.com/cyklo/Bukkit-OtherBlocks/wiki/Aliases-(advanced-YAML-usage))

## Alternatives
* Alternatives compared
    * [Comparison of config formats (@njsmith)](https://gist.github.com/njsmith/78f68204c5d969f8c8bc645ef77d4a8f)
    * [Comparison of config formats (blogpost)](https://blog.ometer.com/2015/09/07/json-like-config-a-spectrum-of-underoverengineering)
    * [Structured text tools (@dbohdan)](https://github.com/dbohdan/structured-text-tools)
* Alternatives (one-off competing)
    * [ArchieML](http://archieml.org/)
    * [dhall-lang](https://dhall-lang.org/)
    * [Hjson](https://github.com/hjson/)
    * [HOCON](https://github.com/lightbend/config/blob/master/HOCON.md#hocon-human-optimized-config-object-notation)
    * [JSON various (@burningtree)](https://github.com/burningtree/awesome-json#format-extensions)
    * [jsonnet](https://jsonnet.org/)
    * [TOML](https://github.com/toml-lang/toml)
* Variants
    * [Strict YAML](https://github.com/crdoconnor/strictyaml) uses a subset of the full YAML specification.

## Annoyances
- [Parsers](https://hackernoon.com/consistently-bad-parsing-of-yaml-ae23eb3676a1) Consistently bad parsing of YAML

## Critique
* [Blog post](https://arp242.net/yaml-config.html)
* [YAML sucks](https://github.com/cblp/yaml-sucks)

## Documentation and resources
- [Discussion Archives](https://sourceforge.net/p/yaml/mailman/yaml-core)
- [Stackoverflow](http://stackoverflow.com/questions/tagged/yaml)
- [YAML Multiline](http://yaml-multiline.info/)

## Mentions
- [After XML JSON then what?](http://www.drdobbs.com/web-development/after-xml-json-then-what/240151851)
- [blog entry praising YAML over JSON](http://www.cowtowncoder.com/blog/archives/2012/04/entry_473.html)
- [drupal convert](https://www.drupal.org/node/1793074)
- [Hacker News](https://duckduckgo.com/?q=site%3Anews.ycombinator.com+YAML&ia=web)
- [HackerNews JSON/XML comparison](https://news.ycombinator.com/item?id=17360088)
- [kubernetes](https://github.com/kubernetes/helm/blob/master/docs/chart_template_guide/yaml_techniques.md)
- [Statamic CMS](https://docs.statamic.com/yaml)

## Parsers
- [golang](https://github.com/go-yaml/yaml)
- [javascript](https://github.com/nodeca/js-yaml)
    - http://nodeca.github.io/js-yaml/
- [Node.js](https://www.npmjs.com/search?q=yaml)
- [R](https://github.com/viking/r-yaml/tree/master)
- [shell](https://johnlane.ie/yay-use-yaml-in-bash-scripts.html)
- [yay](https://github.com/yaybu/yay)
- [YAML Syntax Checker (Linter)](http://yamllint.readthedocs.io/en/latest/quickstart.html#installing-yamllint)
    - https://www.maxoberberger.net/blog/2017/04/yaml-syntaxcheck.html

## People
- [anthon@stackoverflow.com](https://stackoverflow.com/users/1307905/anthon)

## Projects
- [ANSIBLE ansible uses YAML](https://github.com/ansible/ansible)
- [Code Beautify](http://codebeautify.org/yaml-to-json-xml-csv)
- [Dynamic YAML -- childish](https://github.com/childsish/dynamic-yaml)
- [Dynamic YAML -- dreftymac](https://github.com/dreftymac/dynamic.yaml)
- [Go language](https://github.com/go-yaml/yaml)
- [Heat Openstack](https://wiki.openstack.org/wiki/Heat/YAMLTemplates)
- [Kubernetes uses YAML](https://en.wikipedia.org/wiki/Kubernetes)
- [Python-Related](https://github.com/genomoncology/related    )
- [Repoze](http://docs.repoze.org/configuration/index.html)
- [Spiff (on-hold as of 2017-08)](https://github.com/mandelsoft/spiff)
- [Sublime YAML Macros](https://github.com/Thom1729/YAML-Macros)
- [YAML Official](https://github.com/yaml)
- [Yamlinc](https://github.com/javanile/yamlinc)
- [YAMLForm-Drupal8](http://yamlform.io/)
  - [YAMLForm-Blog post](https://www.fourkitchens.com/blog/article/getting-nyu-yaml-form)

## Security
* [Ruby exploit](http://www.ehackingnews.com/2013/01/rubygemsorg-hacked-via-yaml-parsing.html)

## Specification
* [Merge-keys spec](http://yaml.org/type/merge.html)
* [Official site](http://www.yaml.org/)
* [YAML Test Matrix](https://matrix.yaml.io/)
* [YAML test suite](https://github.com/yaml/yaml-test-suite)

## Templating
- [Ansible-based YAML plus Jinja](https://docs.ansible.com/ansible-container/container_yml/template.html)
- [Ruby-based YAML plus Ruby](http://benjamincongdon.me/blog/2016/07/27/Liquid-YAML-Programmatic-Data/)
- [YST YAML plus Haskell](https://github.com/jgm/yst)
- [Tempered YAML plus Bash](https://github.com/ChrisPenner/tempered)
- [Yasha YAML plus Jinja](https://github.com/kblomqvist/yasha)
- [Zenbu YAML plus Jinja](https://github.com/metakirby5/zenbu)

## Tools
- [Tools and services (@datatxt)](https://github.com/datatxt/awseome-yaml#tools--services)
- [YAML parser (appspot.com)](http://yaml-online-parser.appspot.com/)

## Variables
* [Variable placeholders in YAML](https://stackoverflow.com/questions/41620674/use-placeholders-in-yaml)
### Variables (example workarounds)
* [Blog post on bash](https://starkandwayne.com/blog/bashing-your-yaml/)

## Tutorial
* [Yaml Primer](https://getopentest.org/reference/yaml-primer.html)
* [YAML Primer](https://github.com/darvid/trine/wiki/YAML-Primer)

## YAML GISTS
* [YAML succinct tutorial from user:ddlsmurf](https://gist.github.com/dreftymac/b68fef16a468ae56e275)

## YAML Gems
* [Using YAML custom tags (Advanced)](http://stackoverflow.com/a/23212501/42223)

## Searches
* [YAML placeholder variables](https://duckduckgo.com/?q=yaml+placeholder+variables)
* [YAML shell](https://duckduckgo.com/?q=yaml+shell&ia=qa)

## See also

### Aweseomeness
* [Awesome YAML (datatxt) ](https://github.com/datatxt/awseome-yaml)
* [Awesome home assistant](https://github.com/frenck/awesome-home-assistant)
* [Awesome curated](https://github.com/sindresorhus/awesome)
* [Awesome manifesto](https://github.com/sindresorhus/awesome/blob/master/awesome.md)
* [Awesome contributions](https://github.com/sindresorhus/awesome/blob/master/contributing.md)
* [Awesome JSON](https://github.com/burningtree/awesome-json)
* [Ansible Jinja addon filters](http://docs.ansible.com/ansible/latest/playbooks_filters.html)

### Github
* [GH Topic Code Generation](https://github.com/topics/code-generation?o=desc&s=stars)
* [GH Topic YAML](https://github.com/topics/yaml?o=desc&s=stars)

## 💀 R.I.P.
* [DEPRECATED -- Stackoverflow Documentation](http://stackoverflow.com/documentation/yaml)
* [golang JSON and YAML gotchas](http://ghodss.com/2014/the-right-way-to-handle-yaml-in-golang/)




