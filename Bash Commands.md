##### Remplace every " to '. I use an svg for this example.
* `sed -i 0 "s/\"/'/g" *.svg && rm -rf *.svg0`

##### delete recursive empty folders
* `find . -empty -type d -delete`
