### Parameterized Spread Representation

Parameterized composite contract can be represented by a list of contract GUIDs and a vector of ints or bytes denoting the quantity of each component contract.  Compositie future contracts would denote short components with negative values.

The vector of quantities will have the same indicies as the list of GUIDs.

Instruments will have a cannonical ordering according to the following rules:

1. Earliest to latest expiration month.
2. Underlying before derivitave.  
     Cash before future 

     Commodity before future 
     
     Future before Option 
     
3. Alphabetical

 
