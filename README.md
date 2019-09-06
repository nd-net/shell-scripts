# shell-scripts
Small shell scripts for various purposes:

* `simctl`: simply calls `xcrun simctl` with all parameters if you cannot remember that
* `plist-sort`: sorts the keys of a plist file
* `xctdiff`: call a diff tool on the output of a XCTAssertEqual for easier comparison
* `pwd-finder`: prints the path of the topmost Finder window
* `uuniq`: prints unique lines for unsorted sources
* `git-unlock`: removes all .git/index.lock files that mdfind can find, and all in subdirectories of the home directory. You can use `git unlock` to call this script if it is in the path
