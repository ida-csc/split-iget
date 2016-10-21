split-iget - script to iget a bunch of split files from IDA

Usage
-----
```
split-iget file-name-partial number-digits max-number
```

Needs 3 parameters:

1. file name without the sequence part
2. sequence number width, the count of digits or chars
3. last sequence number or string

examples
```
split-iget /ida/org/proj/stuff/some.tar.gz.part- 2 5
split-iget /ida/org/proj/stuff/some.tar.gz.part- 2 bd
```

License
-------

See LICENSE.txt
