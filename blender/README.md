By default, addons are named after their folder name.<br>
e.g. the folder `bqt` results in an add-on named `bqt`.<br>
These add-on folders live in the Python path, and can clash with modules installed in site-packages.<br>
To prevent this, you could add `_addon` to your package name.

TODO, automatically do this in plugget on install
