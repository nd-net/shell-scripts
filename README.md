# Shell-Scripts
Small shell scripts for various purposes:

* `bundle-id`: show the Bundle ID of a macOS app
* `digest`: a generic digest tool (think shasum) that optionally only prints files that have the same digest (useful for checking for duplicates)
* `extract`: extract compressed files of various formats (zip, rar, bz2, tar+...)
* `find-apps`: find macOS apps using mdfind
* `json-pretty`: prettify JSON so that it is more human readable
* `legoman-dl`: downloads and merges PDFs for Lego manuals based on a set ID
* `man-pdf`: create a PDF out of a man page and show it in Preview
* `objc-attributesort`: sorts Objective C property attributes
* `plist-sort`: sorts the keys of a plist file
* `pwd-finder`: prints the path of the topmost Finder window
* `ql`: launch QuickLook on a file
* `qrm`: remove the quarantine flag from a file
* `simctl`: simply calls `xcrun simctl` with all parameters if you cannot remember that
* `uuniq`: prints unique lines for unsorted sources
* `xcode-cleanup`: clean up unused or unnecessary Xcode files
* `xctdiff`: call a diff tool on the output of a XCTAssertEqual for easier comparison

## Git subcommands

The following commands can be invoked via `git <subcommand>` as well as with `git-<subcommand>`.

* `git-deleted`: prints all deleted and not yet commited files in the current repository. Optionally prints a regex that can be used for grepping the filenames somewerhe else
* `git-stats`: prints statistics for commits of the current user
* `git-unlock`: removes all .git/index.lock files that mdfind can find, and all in subdirectories of the home directory
* `git-update-author`: replaces the author and/or committer e-mail address and name in a branch