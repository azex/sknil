# Sknil
Skin for **Bugzilla** issue tracker.

CSS stylesheets are generated from **Stylus** files.
Stylus documentation may be read at http://stylus-lang.com/

## Installation

1. Stop your Bugzilla server.
2. Copy the directory `Sknil` from `target` to your Bugzilla repository:
```sh
export BUGZILLA_HOME
sudo cp -r target/Sknil $BUGZILLA_HOME/skins/contrib
```
3. Run `checksetup.pl` (Bugzilla script).
4. Restart your Bugzilla server.
5. Select the `Sknil` theme from the `Preferences > General Preferences` page (`Bugzilla's general appearance (skin)`).

## Compliance

Tested with Bugzilla 4.4.10 and 5.0.3 under Linux distributions.

## Screenshots

![Report](/screenshots/report.png)

## Build (_for developers only_)

* Install the `Stylus` package from https://www.npmjs.com/package/stylus
* Simply run the following command:
```sh
stylus src/*.styl -o target/Sknil/
```
Push requests allowed and encouraged!

## Change log

### 1.0.0, 2016 03 13
 First release.

### 1.0.1, 2017 05 15
 Git attributes.

### 1.0.2, 2017 12 28
 Enhancements.

## Copyright

 (c) 2016-2017, B. Djoudi
