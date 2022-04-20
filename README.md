# python_badging_blockchain_app

An alteration that was done to an existing source code provided by IBM and Kansal. This is a decentralized time stamp log for a company that wants to track employees clocking in and out. This is done to preserve the cryptography aspect because with the proof of work algorithm within the code, any entries will be preserved in the blockchain as a node. We wanted to prove the non-repudiation element of cyber security with this project by having the time stamps locked and stored in the blockchain so no one can alter or modify the timestamps. Payload includes employeeId, badgeStatus, firstAndLastName. 

Clone the project,

```sh
$ git clone https://github.com/MIraqi1/python_badging_blockchain_app.git
```

Install the dependencies,

```sh
$ cd python_badging_blockchain_app
$ pip install -r requirements.txt
```

Start a blockchain node server,

```sh
$ export FLASK_APP=node_server.py
$ flask run --port 8000
```

One instance of our blockchain node is now up and running at port 8000.


Run the application on a different terminal session,

```sh
$ python run_app.py
```

The application should be up and running at [http://localhost:5000](http://localhost:5000).
