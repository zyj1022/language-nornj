# Nornj language support in Atom

Adds syntax highlighting and snippets to Nornj component files in Atom.


#User can set node path

You can set the command that will run the script by editing ~/.atom/config.cson and adding:

```
'language-nornj':
  'nodepath': '/usr/local/bin/node'
```

if you does not set the path, this plugin uses **ATOM_SHELL_INTERNAL_RUN_AS_NODE=1**

```
'/Applications/Atom.app/Contents/Frameworks/Atom Helper.app/Contents/MacOS/Atom Helper' instead of node.
```

#Other

About nornj

A multipurpose javascript template engine, support both the rendering string and the react component. https://joe-sky.github.io/nornj-guide
