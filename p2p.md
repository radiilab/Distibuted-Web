LibP2P is the complete subsystem of IPFS . It sows the seed s for the distribited web for the future of thos data world.
Radii Corps is incorporating the protocol labs implementation of the Process addressing scheme.Asin IPFS docs the web pages would be awaliable soon 

 the repositories that are being used for the implementation are
[Libp2p](https://github.com/Agorise/c-libp2p)

this repo is the agorise version of the official version [currently under review by the Radii Team -> this repo to be added to the Radii OS [ROS ]].

 the above repo has submodule dependency over the follows 

 1. [C multihash](https://github.com/multiformats/c-multihash)  this is
    used hashing of process level secure communication over TCP sockets.
    
 2. [C multiaddr](https://github.com/jmjatlanta/c-multiaddr) this is
    used  for process addressing  usid in secure communication over TCP sockets.
 3. [C Protobuf](https://github.com/squishyhuman/c-protobuf) for properly serialing the blobs / objects for transmissin over wire are remote process bindings
 
 the LibP2p is implemented by agorise to make its own version of [IPFS](https://github.com/xethyrion/c-ipfs) in C 
 The whole Process is in Test and to be soon added to the ROS and its documentation soon

    
