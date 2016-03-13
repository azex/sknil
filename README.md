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
3. Restart your Bugzilla server.
4. Select the `Sknil` theme from the `Preferences > General Preferences page` (`Bugzilla's general appearance (skin)`).

## Compliance

Tested only with Bugzilla 4.4.10 under Linux distributions.

Should work for 4.4.11 (_not tested_).

## Screenshot

Not yet available.

## Build (_for developers only_)

* Install the `Stylus` package from https://www.npmjs.com/package/stylus
* Simply run the following command:
```sh
stylus src/*.styl -o target/Sknil/
```
Pull requests allowed and encouraged!

## Change log

### 1.0.0, 2016 03 13
 First release.

 ## Copyright

 (c) 2016, B. Djoudi
