
### Optimization rules.


### Enum value wire size rules.

value in 0...127 takes 1 byte on wire

value in 128.... takes varInt128 more bytes on wire

keep most frequent values first


### Field tag wire size rules.

field number 1..15 is 1 byte tag 

field number 16..127 is 2 byte tag
