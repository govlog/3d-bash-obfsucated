# 3D_bash_obfuscated


Before asking me "Why ?!" or telling me about the uselessness of this :

- I did it as a challenge, a friend of mine asked me if I could write a simple 3D engine with bash.
- It was a fun way to learn new things.
- But I admit, a bit of waste of time ;-)


- How it works ?

- It uses the famous Bresenham's line algorithm
- It links every x/y/z points from an array of cords
- It convert x/y/z pos to x/y plane ( x => x/z | y => y/z )
- It does not make real rotation around an axis (no trig then).
