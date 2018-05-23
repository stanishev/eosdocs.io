---
title: "The big picture"
date: 2018-04-24T09:27:15-04:00
weight: 1
draft: false
---

#### Summary

The EOS stoftware stack has a number of tools. Many of the tutorials we've seen explain how to run everything on a single machine. This can be confusing because the reader tends to lose sight of how it all fits together. 

The illustration below shows how these tools are normally distributed. The names of the tools are written in **BIG RED** letters in the illustration. Here's a quick summary:

* **eosiocpp** - A compiler which allows you to compile your C++ into a format that can be uploaded to the blockchain. 
* **cleos** - A command-line tool used to upload your contracts to the blockchain and query the blockchain. 
* **keosd** - A wallet manager which runs as a daemon. The cleos tool interacts with keosd to sign requests (needed so that your requests to the blockchain can be trusted). 
* **nodeos** - The server software that runs the blockchain itself.

{{% notice warning %}}
As you step through the rest of this site, we assume that you are running **nodeos** on a machine/server and using the rest of the tools from another machine. While this seems inconvenient at first, it'll make some concepts a lot clearer. 
{{% /notice %}}

![big Picture](images/BigPicture.jpeg)


