#libp2p exapmle
##libp2p is a very modular framework, which allows javascript devs to target different runtime environments and opt-in to various features by including a custom selection of modules.
```
git clone https://github.com/gautam197/libp2p-example.git
```
```
npm install
```
Try running the code with node src/index.js
```
node src/index.js
```
Now we can start one instance with no arguments:
Grab the /ip4/... address printed above and use it as an argument to another instance. In a new terminal:

Success! Our two peers are now communicating over a multiplexed, secure channel. Sure, they can only say “ping”, but it’s a start!
