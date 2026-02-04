# firefox-bookmarks-cleaner

firefox save all information about search and bookmark in file places.sqlite.

You can finde it in your home directory vith  "~/.mozilla/firefox/somethinf.default-timestamp/places.sqlite"


This python script help you clean from bookmark all incorrect bookmarks with status code not equal 200, 301, 302.

In the script firefox-bookmark.py in strings "sqlite_connection = sqlite3.connect('places.sqlite')" add instead 'places.sqlite' full or relative path firefox places.sqlite file.

In the script firefox-bookmark_v2.py in string sqlite_path = 'places.sqlite' add instead 'places.sqlite' full or relative path firefox places.sqlite file.

Run script with python firefox-bookmark.py(firefox-bookmark_v2.py).
