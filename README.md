neuralnet.jl
============

Simple neural net implementation in Julia

Julia is a scientific computing language designed to be highly optimizable. To that point, Julia's reference implementation contains a JIT that can speed typical Julia code to more than half the speed of native code. This neural net implementation was written by me to make use of this incredible computing speed in a resource-intensive program. 

Since this is a personal project rather than one of great significance, I'm not being hard and fast as to what I'm implementing. Still, if you want to commit changes that add a specific kind of neuron or neural net, you are entirely welcome to do so.

Todo:
Profile and optimize the code a bit more (Thanks to @simd and @parallel, it runs quite quickly on modern processors)
Make the neural net composite type more generic (right now its design forces a specific topology of neural net)
And last, but not least, put it in bigger projects! (That's why I licensed it permissively, by the way)
