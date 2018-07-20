# 2018-07-19

* b57074c fix error of `isFile` check
* 0efc7cf ignore undefined function on service start

# 2018-07-17

* Add `coc.preference.jumpCommand` to settings.
* Make coc service standalone.

# 2018-07-16

* Support arguments for `runCommand` action.
* Add coc command `workspace.showOutput`.
* Support output channel for language server.
* Support `[extension].trace.server` setting for trace server communication.

# 2018-07-15

* Support location list for diagnoctic.
* Add tsserver project errors command.

# 2018-07-14

* Add support for `preselect` of complete item.
* Add support for socket language server configuration.
* Fix configured language server doesn't work.
* Add `workspace.diffDocument` coc command.
* Fix buffer sometimes not attached.
* Improve completion of JSON extension.

# 2018-07-13

* **Break change:** `diagnoctic` in setting.json changed to `diagnostic`.
* Fix clearHighlight arguments.
* Add eslint extension https://github.com/Microsoft/vscode-eslint.
* Fix snippet break with line have $variable.
* Use jsonc-parser replace json5.
* Add `data/schema.json` for coc-settings.json.

# 2018-07-12

* Fix restart of tsserver not working.
* Fix edit of current buffer change jumplist by using `:keepjumps`.
