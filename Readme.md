```
     _            _   
  __| |_ __   ___| |_ 
 / _  |  _ \ / _ \ __|
| (_| | | | |  __/ |_ 
 \__,_|_| |_|\___|\__|
```

# Description

Dnet is an asynchronous ```C++``` networking library focused on simplicity.

# Why Is It Created?

While looking for a networking library, I was surprised with how much
boilerplate is required to use any of them. I wasn't dissatisfied with their
speed but overeliance on OOP disign was disappointing.

Because of that, I decided to build my own library that focuses on minimal
boilerplate and simple procedural and functional approach.

# Design Philosophy

This library should not stray too far away from UNIX sockets library in terms
of high level control flow, but it will not be so unsafe. In addition,
Haskell's Networking library and Rust's version will be a great inspiration.