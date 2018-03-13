# Nornj language support in Atom

Adds syntax highlighting and snippets to Nornj component files in Atom.

## Syntax highlight screenshots

![nornj-template-example](http://og8z552x2.bkt.clouddn.com/screenshot.jpg)

## Code Snippets

![nornj-snippets-example](http://og8z552x2.bkt.clouddn.com/snippets.gif)

* Normal html tags, support all HTML tags

|trigger|snippet|
|-------|-------|
|`div`|Defines a `<div>` tag|
|`span`|Defines a `<span>` tag|
|`input`|Defines a `<input>` tag|
|`iframe`|Defines a `<iframe>` tag|
|`textarea`|Defines a `<textarea>` tag|
|...|...|

* `NornJ` extension tags

|trigger|snippet|
|-------|-------|
|`if`|Defines a `<#if>` tag|
|`else`|Defines a `<#else>` tag|
|`elseif`|Defines a `<#elseif>` tag|
|`switch`|Defines a `<#switch>` tag|
|`case`|Defines a `<#case>` tag|
|`default`|Defines a `<#default>` tag|
|`unless`|Defines a `<#unless>` tag|
|`each`|Defines a `<#each>` tag|
|`for`|Defines a `<#for>` tag|
|`empty`|Defines a `<#empty>` tag|
|`props`|Defines a `<#props>` tag|
|`prop`|Defines a `<#prop>` tag|
|`propName`|Defines a `<@propName>` tag|
|`strProp`|Defines a `<#strProp>` tag|
|`propName`|Defines a `<@@propName>` tag|
|`obj`|Defines a `<#obj>` tag|
|`list`|Defines a `<#list>` tag|
|`fn`|Defines a `<#fn>` tag|
|`tmpl`|Defines a `<#tmpl>` tag|
|`include`|Defines a `<#include>` tag|

# User can set node path

You can set the command that will run the script by editing ~/.atom/config.cson and adding:

```
'language-nornj':
  'nodepath': '/usr/local/bin/node'
```

if you does not set the path, this plugin uses **ATOM_SHELL_INTERNAL_RUN_AS_NODE=1**

```
'/Applications/Atom.app/Contents/Frameworks/Atom Helper.app/Contents/MacOS/Atom Helper' instead of node.
```

# Other

About nornj

A multipurpose javascript template engine, support both the rendering string and the react component.

https://joe-sky.github.io/nornj-guide
