# dot-is

Have a directory of things that you want to identify to humans? Try a dot-is file.

Drop a file named in the following format in a folder:

```
.is.[something][.optional-editor-friendly-extension]
```

The contents of the file is up to you. At this stage of my idea, the contents are free-form **but should be human friendly text of some kind unless your file extension indicates otherwise.**

## Inspiration

I like [redux-ducks](https://github.com/erikras/ducks-modular-redux) and given the file/folder structure of the projects I'm working on, I wanted something that could be added to the file that:

* Provide meaningful, [duck-typed](https://en.wikipedia.org/wiki/Duck_typing) style of information without opening the file.
* Would rise to the top of my graphical tree views.
* Wouldn't be picked up by any other tool I was using right now.
* Hidden from regular, \*NIX terminal commands.
* Would not do the job of other metadata or accepted docs (e.g. package.json, README.md, LICENSE, \_\_init\_\_.py).

