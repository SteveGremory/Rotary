# Rotary engine
A modular game engine for which I will implement Vulkan and Metal backends.

# The concept
I've had this idea for a while, it's actually a pretty simple concept: there's multiple modules like physics, renderer etc which can have any number of features and extra functions,
however, they must implement all the functions that the specification demands of them to and said functions must perform the EXACT function as stated by the specification.

The engine will have a very cool GUI with animations and stuff to swap out modules and plugin them back in.

The primary scripting language of the engine will probably be C# (ironically).