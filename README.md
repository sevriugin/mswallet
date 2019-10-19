# mswallet
TON blockchain macro assembler multi signature wallet

The goal was create an efficient multi signature wallet using only basic TON operation, native data structures and minimise the gas consumption based on the formula Pb := 10 + b + 5r. 

No dictionaries, no procedures call, minimum iterated execution, just macros. 

Smart garbage collection - store nearest expiry date for message array and clean only when needed. 

Use mswallet-test.fif to see the performance

[More info for this project](HOWTO.pdf)

Have a nice ride!
