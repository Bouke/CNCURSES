# CNCurses
System module map for ncurses.

For details about using ncurses, see http://invisible-island.net/ncurses/.

## Including in Swift Code

Add a ``.Package`` dependency to your ``Package.swift` file as shown in the following example:

    import PackageDescription

    let package = Package(
        name:  "myapp"
        dependencies: [
            .Package(url: "https://github.com/Bouke/CNCurses", majorVersion: 3)
        ]
    )

Then import it:

    import CNCurses

## MacOS Installation

Install the library from Homebrew:

    brew install homebrew/dupes/ncurses

## Ubuntu Installation (Trusty)

Install the development headers for ``libncurses5``:

    sudo apt-get install -y libncurses5-dev
