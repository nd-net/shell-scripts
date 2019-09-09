# Shell-Scripts
Small shell scripts for various purposes:

* `simctl`: simply calls `xcrun simctl` with all parameters if you cannot remember that
* `plist-sort`: sorts the keys of a plist file
* `xctdiff`: call a diff tool on the output of a XCTAssertEqual for easier comparison
* `pwd-finder`: prints the path of the topmost Finder window
* `uuniq`: prints unique lines for unsorted sources

## Git subcommands

The following commands can be invoked via `git <subcommand>` as well as with `git-<subcommand>`.

* `git-deleted`: prints all deleted and not yet commited files in the current repository. Optionally prints a regex that can be used for grepping the filenames somewerhe else
* `git-unlock`: removes all .git/index.lock files that mdfind can find, and all in subdirectories of the home directory
* `git-update-author`: replaces the author and/or committer e-mail address and name in a branch