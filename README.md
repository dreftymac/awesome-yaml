<!---
  ### <beg-file_info>
  ### document_metadata:
  ###   - caption: "README"
  ###     dmid: "uu151chariot_unveiled"
  ###     date: created="2019-02-26 09:33:48"
  ###     last: lastmod="2019-02-26 09:33:48"
  ###     tags: yaml,github,dreftymac
  ###     desc: |
  ###         ## notes
  ###         * github awesome-yaml
  ###
  ###         ## awesome community
  ###         * capt="compliance" ;; href="https://github.com/sindresorhus/awesome/blob/main/pull_request_template.md" ;; tags="__tags01__" ;; id="dmid://uu394miskf1638497x03xlink"
  ###         * capt="instructions" ;; href="https://github.com/sindresorhus/awesome/blob/main/create-list.md" ;; tags="__tags01__" ;; id="dmid://uu193jezfl1638497x03xlink"
  ###
  ###         ## editing notes
  ###         * 2021-12-02 17:57:21 removed dependency on ST3/MarkdownTOC package
  ###             * currently, updates to the contents requires manual update of TOC
  ###             * infra://uu747dorpl
  ###
  ###     seealso: |
  ###         ## https
  ###         * https://github.com/dreftymac/awesome-yaml/blob/master/README.md
  ###         * https://leebriggs.co.uk/blog/2019/02/07/why-are-we-templating-yaml.html
  ###         ## this
  ###         * blog    ;; href="./blog.md"
  ###         * youtube ;; href="./youtube.md"
  ###         ## smartpath
  ###         * fun link ;; href="smartpath://mydaydirs/2019/week39/desktop/screencapture-blog-mozilla-org-nfroyd-2015-09-07-standardizing-things-my-way-2019-09-29-22_18_23-uu788trive8raft.png"
  ###         * href="smartpath://mymedia/2014/git/github/awesome-yaml/readme.md"  find="uu151chariot_unveiled"
  ###         ## people
  ###         * https://twitter.com/briggsl
  ###         * https://leebriggs.co.uk/
  ###         * http://champignon.net/
  ###         * https://stackoverflow.com/tags/yaml/topusers
  ###     seeinstead: |
  ###         * __seeinstead__
  ### <end-file_info>
--->

<!---
  # other items not yet included

  ## items
  * yaml+jinja search ;; https://duckduckgo.com/?q=yaml+jinja+stackoverflow&ia=web
  * people ;; http://champignon.net/
  * https://git.github.io/rev_news/2020/07/29/edition-65/

  ## Variable placholders workarounds
  * https://starkandwayne.com/blog/bashing-your-yaml/
--->

YAML awesomeness

> A curated list of [YAML]( https://yaml.org/ ) resources.
> Inspired by the [awesome](https://github.com/sindresorhus/awesome).
> See also [Awesome Yaml (@datatxt)](https://github.com/datatxt/awseome-yaml)

<!--- ##id="uu747dorpl1638496" d="TOC" ## --->
- [awesome-yaml](#awesome-yaml)
    - [Overview](#overview)
        - [YAML is **underrated**](#yaml-is-underrated)
        - [YAML is a **supserset of JSON**](#yaml-is-a-supserset-of-json)
- [Digging in](#digging-in)
    - [Advanced](#advanced)
    - [Alternatives](#alternatives)
    - [Annoyances](#annoyances)
    - [Cloud](#cloud)
    - [Critique](#critique)
    - [Documentation and resources](#documentation-and-resources)
    - [GUI](#gui)
    - [Mentions](#mentions)
    - [NoCode](#nocode)
    - [Parsers](#parsers)
    - [People](#people)
    - [Projects](#projects)
    - [Security](#security)
    - [Specification](#specification)
    - [Templating](#templating)
    - [Tools](#tools)
    - [Transformation](#transformation)
    - [Variables](#variables)
        - [Variables \(example workarounds\)](#variables-example-workarounds)
    - [Validation](#validation)
    - [Tutorial](#tutorial)
    - [YAML GISTS](#yaml-gists)
    - [YAML Gems](#yaml-gems)
    - [Searches](#searches)
    - [See also](#see-also)
        - [Aweseomeness](#aweseomeness)
        - [Github](#github)
    - [💀 R.I.P.](#%F0%9F%92%80-rip)
<!--- ##uu747dorpl1638496## --->


# awesome-yaml

## Overview
<!--- id="dmid://uu086bintt1634232x001xlink" --->

YAML is a configuration format similar to JSON.

* [YAML Online](https://yaml.org)
* [YAML Specfication v1.2](https://yaml.org/spec/1.2/spec.html)
* [YAML Cheatsheet](https://kapeli.com/cheat_sheets/YAML.docset/Contents/Resources/Documents/index)
* [YAML Cheatsheet](https://yaml.org/refcard.html)
* [YAML Wikipedia](https://en.wikipedia.org/wiki/YAML)

### YAML is **underrated**
* Some developers who use it had a negative first-impression of the format, usually because of the syntax.
* Some dislike the fact that YAML allows the use of indentation for specifying scope (although indentation is technically not required).
* Some consider YAML to be superfluous: "XML and JSON fit the bill nicely enough".
* Some have either never heard of YAML or are influenced by the fact that it is (or at least was) not as famous as JSON or XML.

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
## (e.g., http://yaml-online-parser.appspot.com/)

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
<!--- id="dmid://uu086bintt1634232x002xlink" --->

* [Advanced YAML features (@cyklo)](https://github.com/cyklo/Bukkit-OtherBlocks/wiki/Aliases-(advanced-YAML-usage))

## Alternatives
<!--- id="dmid://uu086bintt1634232x003xlink" --->

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
    * [NestedText](https://nestedtext.org/en/stable/)
    * [NixOS Operating System](https://www.youtube.com/watch?v=D5Gq2wkRXpU)
        * [NixOS YouTube](https://www.youtube.com/watch?v=D5Gq2wkRXpU)
    * [TOML](https://github.com/toml-lang/toml)
* Variants
    * [Strict YAML](https://github.com/crdoconnor/strictyaml) uses a subset of the full YAML specification.


## Annoyances
<!--- id="dmid://uu086bintt1634232x004xlink" --->

- [Parsers](https://hackernoon.com/consistently-bad-parsing-of-yaml-ae23eb3676a1) Consistently bad parsing of YAML

## Cloud
<!--- id="dmid://uu086bintt1634232x005xlink" --->

* [Azure Pipeline](https://docs.microsoft.com/en-us/azure/devops/pipelines/create-first-pipeline)

## Critique
<!--- id="dmid://uu086bintt1634232x006xlink" --->

* [Blog post](https://arp242.net/yaml-config.html) -- Blog post
* [NBWTWY](https://noyaml.com/) -- Blog post Nobody wants to write yaml
* [YAML sucks](https://github.com/cblp/yaml-sucks) -- Github
* [YAML test matrix](https://matrix.yaml.io/valid.html) -- Validators

## Documentation and resources
<!--- id="dmid://uu086bintt1634232x007xlink" --->

* [Discussion Archives](https://sourceforge.net/p/yaml/mailman/yaml-core)
* [Stackoverflow](http://stackoverflow.com/questions/tagged/yaml)
* [YAML Multiline](http://yaml-multiline.info/)

## GUI
<!--- id="dmid://uu086bintt1634232x008xlink" --->

* [DDG Search](https://duckduckgo.com/?q=yaml+gui)

## Mentions
<!--- id="dmid://uu086bintt1634232x009xlink" --->

* [After XML JSON then what?](http://www.drdobbs.com/web-development/after-xml-json-then-what/240151851)
* [blog entry praising YAML over JSON](http://www.cowtowncoder.com/blog/archives/2012/04/entry_473.html)
* [drupal convert](https://www.drupal.org/node/1793074)
* [Flextype](https://docs.flextype.org/en/getting-started/configuration)
* [Hacker News](https://duckduckgo.com/?q=site%3Anews.ycombinator.com+YAML&ia=web)
* [HackerNews JSON/XML comparison](https://news.ycombinator.com/item?id=17360088)
* [kubernetes](https://github.com/kubernetes/helm/blob/master/docs/chart_template_guide/yaml_techniques.md)
* [Statamic CMS](https://docs.statamic.com/yaml)

## NoCode
<!--- id="dmid://uu972zumpg1638495x03xlink" --->

* NoCode and LowCode
* [Lowdefy](https://lowdefy.com) - An open-source low-code framework to build internal tools, web apps, admin panels, BI dashboards, workflows, and CRUD apps with ease by simply writing YAML.

## Parsers
<!--- id="dmid://uu086bintt1634232x010xlink" --->
* [Dynamic YAML -- childish](https://github.com/childsish/dynamic-yaml)
* [golang](https://github.com/go-yaml/yaml)
* [javascript](https://github.com/nodeca/js-yaml)
    * http://nodeca.github.io/js-yaml/
* [Node.js](https://www.npmjs.com/search?q=yaml)
* [R](https://github.com/viking/r-yaml/tree/master)
* [shell](https://johnlane.ie/yay-use-yaml-in-bash-scripts.html)
* [yay](https://github.com/yaybu/yay)
* [YAML Syntax Checker (Linter)](http://yamllint.readthedocs.io/en/latest/quickstart.html#installing-yamllint)
    * https://www.maxoberberger.net/blog/2017/04/yaml-syntaxcheck.html

## People
<!--- id="dmid://uu086bintt1634232x011xlink" --->

* [anthon@stackoverflow.com](https://stackoverflow.com/users/1307905/anthon)
* [top users stackoverflow](https://stackoverflow.com/tags/yaml/topusers)

## Projects
<!--- id="dmid://uu086bintt1634232x012xlink" --->

* [ADA YAML](https://ada.yaml.io/) with focus on YAML 1.3
* [Amazon ALEXA](https://github.com/KayLerch/alexa-skills-kit-tellask-java#prepare-your-utterance-yaml-file)
* [ANSIBLE ansible uses YAML](https://github.com/ansible/ansible)
* [Code Beautify](http://codebeautify.org/yaml-to-json-xml-csv)
* [Dynamic YAML -- childish](https://github.com/childsish/dynamic-yaml)
* [Go language](https://github.com/go-yaml/yaml) golang-specific
* [Heat Openstack](https://wiki.openstack.org/wiki/Heat/YAMLTemplates)
* [Kubernetes uses YAML](https://en.wikipedia.org/wiki/Kubernetes)
* [Python-Related](https://github.com/genomoncology/related    )
* [Repoze](http://docs.repoze.org/configuration/index.html)
* [Spiff (on-hold as of 2017-08)](https://github.com/mandelsoft/spiff)
* [Sublime YAML Macros](https://github.com/Thom1729/YAML-Macros)
* [YAML Official](https://github.com/yaml)
* [Yamlinc](https://github.com/javanile/yamlinc)
* [YAMLForm-Drupal8](http://yamlform.io/)
  * [YAMLForm-Blog post](https://www.fourkitchens.com/blog/article/getting-nyu-yaml-form)

## Security
<!--- id="dmid://uu086bintt1634232x013xlink" --->

* [Norway Problem](https://hitchdev.com/strictyaml/why/implicit-typing-removed)
* [Ruby exploit](http://www.ehackingnews.com/2013/01/rubygemsorg-hacked-via-yaml-parsing.html)

## Specification
<!--- id="dmid://uu086bintt1634232x014xlink" --->

* [Merge-keys spec](http://yaml.org/type/merge.html)
* [Official site](http://www.yaml.org/)
* [YAML Test Matrix](https://matrix.yaml.io/)
* [YAML test suite](https://github.com/yaml/yaml-test-suite)

## Templating
<!--- id="dmid://uu086bintt1634232x015xlink" --->

* [Ansible-based YAML plus Jinja](https://docs.ansible.com/ansible-container/container_yml/template.html)
* [gomplate -- golang templating system that supports YAML](https://github.com/hairyhenderson/gomplate)
* [Ruby-based YAML plus Ruby](http://benjamincongdon.me/blog/2016/07/27/Liquid-YAML-Programmatic-Data/)
* [Tempered YAML plus Bash](https://github.com/ChrisPenner/tempered)
* [Yasha YAML plus Jinja](https://github.com/kblomqvist/yasha)
* [Yglu](https://yglu.io) Structural YAML templating and processing
* [YST YAML plus Haskell](https://github.com/jgm/yst)
* [ytt](https://get-ytt.io/) YAML Templating Tool. Templating and patching, together. Includes Python-like programming environment.
* [Zenbu YAML plus Jinja](https://github.com/metakirby5/zenbu)

## Tools
<!--- id="dmid://uu086bintt1634232x016xlink" --->

* [Tools and services (@datatxt)](https://github.com/datatxt/awseome-yaml#tools--services)
* [YAML parser (appspot.com)](http://yaml-online-parser.appspot.com/)
* [YAML to golang](https://mengzhuo.github.io/yaml-to-go/)

## Transformation
<!--- id="dmid://uu086bintt1634232x017xlink" --->

* [AdaYaml Transforms](https://ada.yaml.io/trans)
* [dasel](https://github.com/tomwright/dasel) - Query and update data structures using selectors from the command line. Comparable to [jq](https://github.com/stedlan/jq) / [yq](https://github.com/kislyuk/yq) but supports JSON, YAML, TOML and XML with zero runtime dependencies.
* [DDG Search](https://duckduckgo.com/?q=YAML+transformation)
* [Online transformation tools](https://www.browserling.com/tools/xml-to-yaml)
* [JMESPath](https://jmespath.org/) technically a JSON tool, but powerful enough to be relevant here
    * [JMESPath extensions](https://github.com/grofers/go-codon/wiki/Jmespath-extensions)

## Variables
<!--- id="dmid://uu086bintt1634232x018xlink" --->
* [Dynamic YAML -- childish](https://github.com/childsish/dynamic-yaml)
* [Variable placeholders in YAML](https://stackoverflow.com/questions/41620674/use-placeholders-in-yaml)

### Variables (example workarounds)
<!--- id="dmid://uu086bintt1634232x019xlink" --->

* [Blog post on bash](https://starkandwayne.com/blog/bashing-your-yaml/)

## Validation
<!--- id="dmid://uu086bintt1634232x020xlink" --->

* [Cerberus](https://docs.python-cerberus.org/en/stable/) validation package for Python
* [Copper](https://github.com/cloud66-oss/copper)
* [DDG Search](https://duckduckgo.com/?q=yaml+validation)
* [kube-score](https://github.com/zegl/kube-score)
* [Kubeval](https://www.kubeval.com/)
* [learnk8s -- blog post](https://learnk8s.io/validating-kubernetes-yaml#kubeval)

## Tutorial
<!--- id="dmid://uu086bintt1634232x021xlink" --->

* [YAML introduction](https://github.com/Animosity/CraftIRC/wiki/Complete-idiot's-introduction-to-yaml)
* [YAML learnxinyminutes](https://learnxinyminutes.com/docs/yaml/)
* [YAML Primer](https://getopentest.org/reference/yaml-primer.html)
* [YAML Primer](https://github.com/darvid/trine/wiki/YAML-Primer)
* [YAML tutorial](https://rhnh.net/2011/01/31/yaml-tutorial)

## YAML GISTS
<!--- id="dmid://uu086bintt1634232x022xlink" --->

* [YAML succinct tutorial from user:ddlsmurf](https://gist.github.com/dreftymac/b68fef16a468ae56e275)

## YAML Gems
<!--- id="dmid://uu086bintt1634232x023xlink" --->

* [Using YAML custom tags (Advanced)](http://stackoverflow.com/a/23212501/42223)

## Searches
<!--- id="dmid://uu086bintt1634232x024xlink" --->

* [YAML placeholder variables](https://duckduckgo.com/?q=yaml+placeholder+variables)
* [YAML shell](https://duckduckgo.com/?q=yaml+shell&ia=qa)

## See also

### Aweseomeness
<!--- id="dmid://uu086bintt1634232x025xlink" --->

* [Awesome YAML (datatxt) ](https://github.com/datatxt/awseome-yaml)
* [Awesome home assistant](https://github.com/frenck/awesome-home-assistant)
* [Awesome curated](https://github.com/sindresorhus/awesome)
* [Awesome manifesto](https://github.com/sindresorhus/awesome/blob/master/awesome.md)
* [Awesome contributions](https://github.com/sindresorhus/awesome/blob/master/contributing.md)
* [Awesome JSON](https://github.com/burningtree/awesome-json)
* [Ansible Jinja addon filters](http://docs.ansible.com/ansible/latest/playbooks_filters.html)

### Github
<!--- id="dmid://uu086bintt1634232x026xlink" --->

* [GH Topic Code Generation](https://github.com/topics/code-generation?o=desc&s=stars)
* [GH Topic YAML](https://github.com/topics/yaml?o=desc&s=stars)

## 💀 R.I.P.
<!--- id="dmid://uu086bintt1634232x027xlink" --->

* [DEPRECATED -- Stackoverflow Documentation](http://stackoverflow.com/documentation/yaml)
* [Dynamic YAML -- dreftymac](https://github.com/dreftymac/dynamic.yaml)
* [golang JSON and YAML gotchas](http://ghodss.com/2014/the-right-way-to-handle-yaml-in-golang/)




