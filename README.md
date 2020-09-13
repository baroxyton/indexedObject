# indexedObject
## The simplest indexedDB wrap
# demo
https://htmleditor.ironblockhd.repl.co/reserved/editor/
# documentation
## creating an indexedObject
`let db = new IndexedObject(name,startValue)`
## waiting for the database to be ready
`db.onready.then(main)`
## read/write database object
note: the database must be ready to access the data

`db.data`
