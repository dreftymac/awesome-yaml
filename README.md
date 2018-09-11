# awesome-yaml

YAML awesomeness

> A curated list of YAML resources. See also [Awesome Yaml (@datatxt)](https://github.com/datatxt/awseome-yaml)

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

# Digging in

## Advanced
- [Advanced YAML features](https://github.com/cyklo/Bukkit-OtherBlocks/wiki/Aliases-(advanced-YAML-usage))

## Alternatives (competing)
- [ArchieML](http://archieml.org/)
- [TOML](https://github.com/toml-lang/toml)
- [JSONnet templating](http://jsonnet.org/language/comparisons.html)

## Documentation and resources
- [Discussion Archives](https://sourceforge.net/p/yaml/mailman/yaml-core)
- [Stackoverflow](http://stackoverflow.com/questions/tagged/yaml)
- [DEPRECATED -- Stackoverflow Documentation](http://stackoverflow.com/documentation/yaml)
- [YAML Multiline](http://yaml-multiline.info/)

## Mentions
- [HackerNews JSON/XML comparison](https://news.ycombinator.com/item?id=17360088)
- [drupal convert](https://www.drupal.org/node/1793074)
- [blog entry praising YAML over JSON](http://www.cowtowncoder.com/blog/archives/2012/04/entry_473.html)
- [After XML JSON then what?](http://www.drdobbs.com/web-development/after-xml-json-then-what/240151851)
- [Statamic CMS](https://docs.statamic.com/yaml)
- [kubernetes](https://github.com/kubernetes/helm/blob/master/docs/chart_template_guide/yaml_techniques.md)

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

## Projects
- [ANSIBLE ansible uses YAML](https://github.com/ansible/ansible)
- [Code Beautify](http://codebeautify.org/yaml-to-json-xml-csv)
- [Dynamic YAML -- childish](https://github.com/childsish/dynamic-yaml)
- [Dynamic YAML -- dreftymac](https://github.com/dreftymac/dynamic.yaml)
- [Go language](https://github.com/go-yaml/yaml)
- [Heat Openstack](https://wiki.openstack.org/wiki/Heat/YAMLTemplates)
- [Python-Related](https://github.com/genomoncology/related    )
- [Repoze](http://docs.repoze.org/configuration/index.html)
- [Spiff (on-hold as of 2017-08)](https://github.com/mandelsoft/spiff)
- [YAML Official](https://github.com/yaml)
- [Yamlinc](https://github.com/javanile/yamlinc)
* [YAMLForm-Drupal8] (http://yamlform.io/)
    * [YAMLForm-Blog post](https://www.fourkitchens.com/blog/article/getting-nyu-yaml-form)

## Security
- [Ruby exploit](http://www.ehackingnews.com/2013/01/rubygemsorg-hacked-via-yaml-parsing.html)

## Specification
- [Official site] (http://www.yaml.org/)
- [Merge-keys spec] (http://yaml.org/type/merge.html)

## Templating
- [Ansible-based YAML plus Jinja](https://docs.ansible.com/ansible-container/container_yml/template.html)
- [Ruby-based YAML plus Ruby](http://benjamincongdon.me/blog/2016/07/27/Liquid-YAML-Programmatic-Data/)
- [YST YAML plus Haskell](https://github.com/jgm/yst)
- [Tempered YAML plus Bash](https://github.com/ChrisPenner/tempered)
- [Yasha YAML plus Jinja](https://github.com/kblomqvist/yasha)
- [Zenbu YAML plus Jinja](https://github.com/metakirby5/zenbu)

## Tutorial
- [YAML-Primer](https://github.com/darvid/trine/wiki/YAML-Primer)

## YAML GISTS
* [YAML succinct tutorial from user:ddlsmurf](https://gist.github.com/dreftymac/b68fef16a468ae56e275)

## YAML Gems
* [Using YAML custom tags (Advanced)](http://stackoverflow.com/a/23212501/42223)

## Searches
* https://duckduckgo.com/?q=yaml+shell&ia=qa

## See also
* [Awesome YAML](https://github.com/datatxt/awseome-yaml)
* [Awesome curated](https://github.com/sindresorhus/awesome)
* [Awesome manifesto](https://github.com/sindresorhus/awesome/blob/master/awesome.md)
* [Awesome contributions](https://github.com/sindresorhus/awesome/blob/master/contributing.md)
* [Awesome JSON](https://github.com/burningtree/awesome-json)
* [Ansible Jinja addon filters](http://docs.ansible.com/ansible/latest/playbooks_filters.html)
* [golang JSON and YAML gotchas](http://ghodss.com/2014/the-right-way-to-handle-yaml-in-golang/)

