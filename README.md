# Antialiasing-and-micro-renderer

Implementing a program capable of resizing an image by mitigating the loss of information by using
anti-alias anti-alias technique (SSAA or FSAA) and implementation of a micro
rendering engine, able to create a picture that holds a line.
These programs will be implemented using threaded APIs provided by the pthread library, in the language
C. The solution will have to scale with the number of threads, remaining within an effective, accepted range
(determined empirically by limiting test time).
