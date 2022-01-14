kekdaqblockd
==============

Provides extended API functionality over counterpartyd (such as market information, asset history, etc). Works alongside kekdaqd.


## Installing kekdaqblockd:

```
sudo apt-get install python-pip cython libxml2-dev libxslt1-dev python2.7-dev

git clone https://github.com/kekdaq/kekdaqblockd.git

cd kekdaqblockd

pip install -r pip-requirements.txt 
```

## Running kekdaqblockd:
```
python2.7 counterblockd.py --counterpartyd-rpc-user pepeuser --counterpartyd-rpc-password pepepass --counterpartyd-rpc-port 4000
```
