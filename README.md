# Shell-Scripts
Small shell scripts for various purposes:

* `add-dock-spacer`: add spacers to the dock to make visually distinct groups
* `bundle-id`: show the Bundle ID of a macOS app
* `citrix-cleanup`: fix Citrix's annoying behavior to automatically run at startup
* `cue-convert`: convert an audio file with a structure given in a .cue file into separate files
* `digest`: a generic digest tool (think shasum) that optionally only prints files that have the same digest (useful for checking for duplicates)
* `extract`: extract compressed files of various formats (zip, rar, bz2, tar+...)
* `find-apps`: find macOS apps using mdfind
* `jenkins-env`: convert the (text) content of Jenkins's "Environment variables" page into commands that can be used to set the environment
* `jail-sh`: run a shell inside a FreeBSD jail
* `json-merge-patch`: Diff JSON files, or patch a JSON file with an existing diff,
* `json-pretty`: prettify JSON so that it is more human readable
* `legoman-dl`: downloads and merges PDFs for Lego manuals based on a set ID
* `mail-cleanup`: Perform a sqlite vacuum on Mail's index
* `man-pdf`: create a PDF out of a man page and show it in Preview
* `objc-attributesort`: sorts Objective C property attributes
* `plist-sort`: sorts the keys of a plist file
* `protoc-grpc`: a wrapper around `protoc` that adds the gRPC plugins to the tool
* `pwd-finder`: prints the path of the topmost Finder window
* `ql`: launch QuickLook on a file
* `qrm`: remove the quarantine flag from a file
* `refresh-open-with`: Updates the launch services database, eliminating dead or duplicate entries in the "Open With" menu
* `simctl`: calls `xcrun simctl` with all parameters if you cannot remember that, and shows help for undocumented commands
* `sudo-touchid-enable`: enables the use of TouchID for sudo; this typically needs to be run after every system update
* `tag-pdf`: Perform a fuzzy search on a given PDF file and tag it
* `update-nib-colors`: Replace literal colors in storyboards and xib files by named colors
* `uuniq`: prints unique lines for unsorted sources
* `xcode-cleanup`: clean up unused or unnecessary Xcode files
* `xctdiff`: call a diff tool on the output of a XCTAssertEqual for easier comparison

## Git subcommands

The following commands can be invoked via `git <subcommand>` as well as with `git-<subcommand>`.

* `git-deleted`: prints all deleted and not yet commited files in the current repository. Optionally prints a regex that can be used for grepping the filenames somewerhe else
* `git-duplicate`: duplicates a git repository at a given location with all checked out branches
* `git-refresh-tags`: a shortcut for `git fetch --prune-tags --tags -f`, updates tags that's references have changed
* `git-stats`: prints statistics for commits of the current user
* `git-unlock`: removes all .git/index.lock files that mdfind can find, and all in subdirectories of the home directory
* `git-update-author`: replaces the author and/or committer e-mail address and name in a branch
