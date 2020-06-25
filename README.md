# Fake Repo

Used to test the [cdnjs CI checker tool](https://github.com/cdnjs/tools/tree/master/cmd/checker).

To test:

`git clone git@github.com:cdnjs/tools.git`

Then run inside `tools/`:

`make checker && ./bin/checker lint <path to package json file>`

For example, if testing [package_all_ignored.json](package_all_ignored.json) and its path is `~/Desktop/test-cdnjs-pkg/package_all_ignored.json`, run:

`make checker && ./bin/checker lint ~/Desktop/test-cdnjs-pkg/package_all_ignored.json`
