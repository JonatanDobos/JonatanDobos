
## Welcome to my GitHub!

### What you will find:
- Codam Coding College (Amsterdam, part of the 42-network) coding projects. (All these repositories have "_42" at the end)
- Personal projects and experimenting.

Programming is one of the most usefull skills one can have these days and it is a beatiful thing to be able to create fully custom tools for every unique challenge we face :).  
But my interest for it resides more in the creative aspect, mostly the graphical aspect of the creative aspect, and mostly in the experimentative aspect of the graphical aspect of the creative aspect of programming.  
I love finding better ways to restructure existing code and nothing is more rewarding than seeing the changes on screen in real time.  
Considering this, i suspect it will not suprise you that two of my three highlighted projects (see below) are graphics oriented.

___

### Highlighted Projects:
- [MiniRT_42](https://github.com/JonatanDobos/MiniRT_42): a simple raytracer written in C in collaboration with @RJW-db.  
  It uses a combination of multithreading (CPU only) and vector-math to create an image of a 3D scene provided by the user in a scenefile. We focussed heavily on performance and less on render-quality by prioritizing compute-efficiency with extra features like simple automatic dynamic downscaling functionality.
- [Fractol_42](https://github.com/JonatanDobos/Fractol_42): also a graphical program, this time for rendering fractals.  
  This program also includes several modes, for example: drawing the Julia fractal based on the coordinates in the Mandelbrot set pointed to by the cursor in real time.
- [Philosophers_42](https://github.com/JonatanDobos/Philosophers_42): a program that simulates dining philosophers based on the famous "Dining Philosophers Problem".  
  This program simulates X amount of philosophers sitting around a table eating pasta with two forks while there is only one fork between two adjacent philosophers (which they can't use simultaniously), if they are not eating they can only think and sleep for a given time before starving. The program is designed to make the philosophers eat at the right interval based on the given parameters (philosopher amount, eat-, think- and sleep-time) by assigning the right fork (mutex) to the right philosopher (thread) at the right time.

___

###### All programs need to be run from a terminal environment.
###### Most programs are only compatible with Mac and Linux system, when using a different system the use of a virtual machine is adviced.
###### Some programs need additional libraries to be present on the device.
