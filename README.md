# Intel Edison Projects
This is the code repository for [Intel Edison Projects](https://www.packtpub.com/hardware-and-creative/intel-edison-projects?utm_source=github&utm_medium=repository&utm_campaign=9781787288409), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Change the way you look at embedded electronics with Intel Edison. It is a small computing platform packed with a set of robust features to deliver hands-on performance, durability, and software support.

This book is a perfect place to kickstart development and rapid prototyping using Intel Edison. It will start by introducing readers to the Intel Edison board and explaining how to get started with it. You will learn how to build a mini weather station, which will help you to acquire temperature and smoke level and push it to the IoT platform. Then you will see how to build a home automation device and control your appliances using an Android app. Furthermore, we will build a security system using a webcam to detect faces and perform voice recognition. Toward the end, the book will demonstrate how you can build two robots, which will be based on different line sensing sensors and can be controlled by a PC.

The book will guide the readers through each and every step of execution of a project, using Intel Edison.
## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
import mraa
import time
led = mraa.Gpio(13)
led.dir(mraa.DIR_OUT)
while True:
 led.write(1)
 time.sleep(0.2)
 led.write(0)
 time.sleep(0.2)
```

The mandatory prerequisites for this book are the Intel Edison with Windows/Linux/Mac
OS. The software requirements are as follows:
Arduino IDE
Visual Studio
FileZilla
Notepad++
PuTTY
Intel XDK

## Related Products
* [Intel Galileo Essentials](https://www.packtpub.com/hardware-and-creative/intel-edison-projects?utm_source=github&utm_medium=repository&utm_campaign=9781787288409)

* [Home Automation with Intel Galileo](https://www.packtpub.com/hardware-and-creative/intel-edison-projects?utm_source=github&utm_medium=repository&utm_campaign=9781787288409)

* [Intel Galileo Networking Cookbook](https://www.packtpub.com/hardware-and-creative/intel-edison-projects?utm_source=github&utm_medium=repository&utm_campaign=9781787288409)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.

