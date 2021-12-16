``` bash
pip install bscscan-python
````

bash run_tests.sh YOUR_API_KEY
````

`` python
import asyncio
from  bscscan  import  BscScan 
bsc  =  BscScan ( WPPIN27EES74N5ASJHPBDW8EJAAJ2RW4MB )

bsc.get_bnb_balance(address="0x560bB6965bF2fF4F461D05635DD37E67923DBA7F")

> '7686820749556864'
