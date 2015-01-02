seq2fasta
=========

Converts one or more DNA bare sequence files (.seq) into one FASTA
format file (.fas).

The program is intended for and tested in Linux terminal environment.

Installation
------------

Run these in the terminal:

```
cd /usr/local/bin
sudo wget https://raw.githubusercontent.com/jistr/seq2fasta/master/seq2fasta.py
sudo chmod 0755 seq2fasta.py
```

Usage example
-------------

```
seq2fas.py first.seq second.seq third.seq > all_sequences.fas
```

Or, if you want to convert all .seq files in the current directory:

```
seq2fas.py *.seq > all_sequences.fas
```


License
-------

GNU AGPL v3 or later

Authors
-------

Kamila Brazdilova and Jiri Stransky
