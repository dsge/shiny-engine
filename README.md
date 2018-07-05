# shiny-engine

Local development
-----

Requires [aglio](https://github.com/danielgtaylor/aglio).

Compile the files for displaying them in your browser, and then watch for changes: 
```
$ ./serve.sh
```

**DO NOT** edit `index.apib` directly!

Before commiting
-----

Compile the files into `index.apib` using:
```
$ ./build.sh
```

The UI on Apiary only renders `index.apib` and ignores everything else.
