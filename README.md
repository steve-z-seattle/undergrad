# undergrad (WIP)
A preliminary autograd engine (implementing backpropagation) for optimizing artificial neural networks.

Inspired by Andrej's micrograd: https://github.com/karpathy/micrograd

The movivation for this repo is to use even simpler ideas/concepts for the implementation. Particularly, no closure is used. 

However, at this point, I do think using closure is more elegent for implementing autograd, as the backward and forward implementations have good proximity.
