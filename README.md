# JETGPIO_TESTS
First attempts playing with the Jetson NANO GPIO

Testing pins of the Jetson nano 40 pin header GPIO, setting pin 33 (GPIO_PE6) as an output and changing the value, the thing works, tested with an oscilloscope. Still very initial attempts, will increase more pins and functionality when i have the time but nice prrof of concept anyways, very dirty code yet.
No libraries used, mapped directly into user memory (mmap) and accessing the tegra registers bypassing the kernel for low latency and higher degree of control, this looks promissing.


![image](https://user-images.githubusercontent.com/47650457/164944765-998ca31c-d72c-4d2b-8cbc-7bea594ce8d5.png)





