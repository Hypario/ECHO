# ECHO (Extended ComputerCraft Hub Operator)

This is a Proof of Concept of an idea of mine, a control center for my minecraft computer network

The idea would be simple

- be able to monitor my mekanism reactor
- be able to monitor my AE2 network
- be able to control my mekanism reactor and prevent any issues
- be able to request and craft fuel for the mekanism reactor

- maybe be able to guide me to the next objective (maybe hook the system to ChatGPT ?)

ALL OF THIS IS JUST A CONCEPT, nothing done yet and I'm just experiment, don't expect any results

## How to get started

clone the project
```git
git clone --recurse-submodules https://github.com/hypario/ECHO
```

A build.sh should be provided, you just need to run it

This project uses LuaCC (Lua Code Combiner) for the lua part

## how does it work

I want it to work, on principle, with nodes (which represents a computer), each will have some kind of job
being either :

- mekanism
- AE2

and so on, if I get a new idea
they will send data to be processed to the server part, which will have all, if not all of the logic (I hope)