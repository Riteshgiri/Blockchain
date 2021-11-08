# Blockchain

**Setup**

Get the code:

git clone https://github.com/Riteshgiri/Blockchain.git

Install dependencies:

1. pip install Flask 0.12.2
2. Postman HTTP https://wwwgetpostman.com/

In terminal navigate to the directory level where the blockchain.py is located and run
```
 python blockchain.py
 ```

Hit the endpoints using postman:

1. GET http://127.0.0.1:5000/get_chain : Get Block Chain
2. GET http://127.0.0.1:5000/mine_block  : Mine blocks . Block get addedd to the chain
3. GET http://127.0.0.1:5000/validate_chain : Validate the Blockchain

