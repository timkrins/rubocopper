Install asdf
Run `asdf install`
Run `bundle` (maybe `gem install bundler` first)

You now have the power of daemonized rubocop.

Add this to your vscode settings:

```
"ruby.rubocop.executePath": "FULL_PATH_TO_PARENT_DIRECTORY/rubocopper/",
```
