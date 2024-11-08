# command line options

## --server

Launch as a language server.

## --clear-cache

Clear the cache files.

## --dump-decl

Dump a type declarations file (d.er) after type checking.

```bash
$ pylyzer --dump-decl test.py
Start checking: test.py
All checks OK: test.py

$ ls
test.py  test.d.er
```

## -c/--code

Check code from the command line.

```bash
$ pylyzer -c "print('hello world')"
Start checking: string
All checks OK: string
```

## --disable

Disable a default LSP feature.
Default (disableable) features are:

* codeAction
* codeLens
* completion
* diagnostics
* findReferences
* gotoDefinition
* hover
* inlayHint
* rename
* semanticTokens
* signatureHelp
* documentLink

## --verbose

Print process information verbosely.
