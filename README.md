## Artificial Intelligence and Machine learning cource 

This repository contains all the codes, cource details, pdfs and examples to the AI and machine learning cource. 
The main objective of this cource is to give students the basic idea about AI and make the learning process simple and easy.

## Contents 

#### 1. Introduction and scope
   
In this section, the focus is to give an introduction to the current AI revolution and the scopeof AI.
In recent years, some revolutionary changes happened in the field of Artificial intelligence and this is the perfect time for us to learn AI. Unlike the past few years, we now know the methodes to learn AI and we have the hardware that is required in our personal computers. The introduction of GPU powered deep learning models revolutionized the entire industry. Now, It is time for us to learn AI. Before that, Let's see some examples.

[![Google brain](https://img.youtube.com/vi/V1eYniJ0Rnk/0.jpg)](https://www.youtube.com/watch?v=V1eYniJ0Rnk)

This particular example is Google DeepMind's Deep Q-learning playing Atari Breakout. This is using a concept called Reinforced learning. When we try to throw a basket ball into the basket, after several attempts, we finally learn that throwing it in a particular angle at a particular speed, it is possible to put the ball inside the basket. Just like that, learning the environment and reconfigauring the artifcial neural networks, it is possible for the machine to learn the perfect way to solve problems, some times better than us.
for more examples, click [here](https://github.com/hexiumsoftec/hexiumsoftec.github.io/tree/master/Introduction%20and%20scope)

#### 2. Problems and opportunities
   
   - A brief on how problems can be solved by applying AI

#### 3. A crash cource in python for AI

>>>Python is a cross-platform programming language, which means it runs on all the major operating systems. Any Python program you write should run on any modern computer that has Python installed. However, the methods for setting up Python on different operating systems vary slightly. In this section you’ll learn how to set up Python and run the Hello World program on your own system. You’ll first check whether Python is installed on your system and install it if it’s not. Then you’ll install a simple text edi- tor and save an empty Python file called hello_world.py. Finally, you’ll run the Hello World program and troubleshoot anything that didn’t work. I’ll walk you through this process for each operating system, so you’ll have a beginner-friendly Python programming environment.<<<
##### Python on Linux
Linux systems are designed for programming, so Python is already installed on most Linux computers. The people who write and maintain Linux expect you to do your own programming at some point and encourage you to do so. For this reason there’s very little you have to install and very few settings you have to change to start programming. Checking Your Version of Python Open a terminal window by running the Terminal application on your system (in Ubuntu, you can press ctrl- alt -T). To find out whether Python is installed, enter python with a lowercase p. You should see output telling you which version of Python is installed and a >>> prompt where you can start entering Python commands, like this:
```sh
$ python
Python 2.7.6 (default, Mar 22 2014, 22:59:38)
[GCC 4.8.2] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>>
```
This output tells you that Python 2.7.6 is currently the default version of Python installed on this computer. When you’ve seen this output, press ctrl-D or enter exit() to leave the Python prompt and return to a terminal prompt.
Running Python Programs from a Terminal
Most of the programs you write in your text editor you’ll run directly
from the editor, but sometimes it’s useful to run programs from a terminal
instead. For example, you might want to run an existing program without
opening it for editing.
You can do this on any system with Python installed if you know how
to access the directory where you’ve stored your program file. To try this,
make sure you’ve saved the hello_world.py file in the python_work folder on
your desktop.
   Running a Python program from a terminal session is the same on Linux. The terminal command cd, for change directory, is used to navi-gate through your file system in a terminal session. The command ls, for list, shows you all the non-hidden files that exist in the current directory. Open a new terminal window and issue the following commands to run
hello_world.py:
```sh
u ~$ cd Desktop/python_work/
v ~/Desktop/python_work$ ls
hello_world.py
w ~/Desktop/python_work$ python hello_world.py
Hello Python world!
 ```
python hello_world.py
It’s that simple. You just use the python (or python3) command to run Python programs.



##### Variables and Si m p l e D a t a T y p e s

We will discus  about the different kinds of data you can work with in your Python programs. You’ll also learn how to store your data in variables and how to use those variables in your programs.


##### Variables
Let’s try using a variable in hello_world.py. Add a new line at the beginning of the file, and modify the second line:
message = "Hello Python world!"
print(message)
Run this program to see what happens. You should see the same output you saw previously:
Hello Python world!
We’ve added a variable named message. Every variable holds a value, which is the information associated with that variable. In this case the value is the text “Hello Python world!”.Adding a variable makes a little more work for the Python interpreter. When it processes the first line, it associates the text “Hello Python world!” with the variable message. When it reaches the second line, it prints the value associated with message to the screen.
        Let’s expand on this program by modifying hello_world.py to print a sec- ond message. Add a blank line to hello_world.py, and then add two new lines of code:
```sh
        message = "Hello Python world!"
        print(message)
        message = "Hello Python Crash Course world!"
        print(message)
```
Now when you run hello_world.py, you should see two lines of output:
Hello Python world! Hello Python Crash Course world!
You can change the value of a variable in your program at any time, and Python will always keep track of its current value.
##Naming and Using Variables
When you’re using variables in Python, you need to adhere to a few rules and guidelines. Breaking some of these rules will cause errors; other guide- lines just help you write code that’s easier to read and understand. Be sure to keep the following variable rules in mind: 

- Variable names can contain only letters, numbers, and underscores. They can start with a letter or an underscore, but not with a number. For instance, you can call a variable message_1 but not 1_message.
- Spaces are not allowed in variable names, but underscores can be used to separate words in variable names. For example, greeting_message works, but greeting message will cause errors.
- Avoid using Python keywords and function names as variable names; that is, do not use words that Python has reserved for a particular pro- grammatic purpose, such as the word print.
- Variable names should be short but descriptive. For example, name is better than n, student_name is better than s_n, and name_length is better than length_of_persons_name.
- Be careful when using the lowercase letter l and the uppercase letter O because they could be confused with the numbers 1 and 0.
It can take some practice to learn how to create good variable names, especially as your programs become more interesting and complicated. As you write more programs and start to read through other people’s code, you’ll get better at coming up with meaningful names.
--Note
The Python variables you’re using at this point should be lowercase. You won’t get
errors if you use uppercase letters, but it’s a good idea to avoid using them for now.

##### Avoiding Name Errors When Using Variables
Every programmer makes mistakes, and most make mistakes every day. Although good programmers might create errors, they also know how to respond to those errors efficiently. Let’s look at an error you’re likely to make early on and learn how to fix it. We’ll write some code that generates an error on purpose. Enter the following code, including the misspelled word mesage shown in bold:
```sh
message = "Hello Python Crash Course reader!"
print(mesage)
```
When an error occurs in your program, the Python interpreter does its best to help you figure out where the problem is. The interpreter provides a traceback when a program cannot run successfully. A traceback is a record of where the interpreter ran into trouble when trying to execute your code. Here’s an example of the traceback that Python provides after you’ve accidentally misspelled a variable’s name:
```sh
Traceback (most recent call last):
 File "hello_world.py", line 2, in <module>
 print(mesage)
NameError: name 'mesage' is not defined
```
The output at u reports that an error occurs in line 2 of the file hello_world.py. The interpreter shows this line to help us spot the error quickly v and tells us what kind of error it found w. In this case it found a name error and reports that the variable being printed, mesage, has not been defined. Python can’t identify the variable name provided. A name error usually means we either forgot to set a variable’s value before using it, or we made a spelling mistake when entering the variable’s name. Of course, in this example we omitted the letter s in the variable name message in the second line. The Python interpreter doesn’t spellcheck your code, but it does ensure that variable names are spelled consistently. For example, watch what happens when we spell message incorrectly in another place in the code as well: 
```sh
mesage = "Hello Python Crash Course reader!"
print(mesage)
In this case, the program runs successfully!
Hello Python Crash Course reader!
```
Computers are strict, but they disregard good and bad spelling. As a result, you don’t need to consider English spelling and grammar rules when you’re trying to create variable names and writing code. Many programming errors are simple, single-character typos in one line of a program. If you’re spending a long time searching for one of these errors, know that you’re in good company. Many experienced and talented programmers spend hours hunting down these kinds of tiny errors. Try to laugh about it and move on, knowing it will happen frequently throughout your programming life.
#####Strings
Because most programs define and gather some sort of data, and then do something useful with it, it helps to classify different types of data. The first data type we’ll look at is the string. Strings are quite simple at first glance, but you can use them in many different ways. A string is simply a series of characters. Anything inside quotes is con- sidered a string in Python, and you can use single or double quotes around
your strings like this:
```sh
"This is a string."
'This is also a string.'
```
This flexibility allows you to use quotes and apostrophes within your
strings:
        'I told my friend, "Python is my favorite language!"'
        "The language 'Python' is named after Monty Python, not the snake."
        "One of Python's strengths is its diverse and supportive community."


##### Changing Case in a String with Methods
One of the simplest tasks you can do with strings is change the case of the words in a string. Look at the following code, and try to determine what’s happening:
```sh
name = "ada lovelace"
print(name.title())
```
Save this file as name.py, and then run it. You should see this output: Ada Lovelace In this example, the lowercase string "ada lovelace" is stored in the variable name. The method title() appears after the variable in the print() state- ment. A method is an action that Python can perform on a piece of data. The dot ( .) after name in name.title() tells Python to make the title() method act on the variable name. Every method is followed by a set of parentheses, because methods often need additional information to do their work. That information is provided inside the parentheses. The title() function doesn’t need any additional information, so its parentheses are empty. title() displays each word in title-case, where each word begins with a capital letter. This is useful because you’ll often want to think of a name as a piece of information. For example, you might want your program to recognize the input values Ada, ADA, and ada as the same name, and display all of them as Ada
Several other useful methods are available for dealing with case as well.
For example, you can change a string to all uppercase or all lowercase letters
like this:
```sh
name = "Ada Lovelace"
print(name.upper())
print(name.lower())
```
This will display the following:
```sh
ADA LOVELACE
ada lovelace
```
The lower() method is particularly useful for storing data. Many times you won’t want to trust the capitalization that your users provide, so you’ll convert strings to lowercase before storing them. Then when you want to display the information, you’ll use the case that makes the most sense for each string.

##### Combining or Concatenating Strings
It’s often useful to combine strings. For example, you might want to store a first name and a last name in separate variables, and then combine them when you want to display someone’s full name:
```sh
first_name = "ada"
last_name = "lovelace"
u full_name = first_name + " " + last_name
print(full_name)
```
Python uses the plus symbol (+) to combine strings. In this example, we use + to create a full name by combining a first_name, a space, and a last_name u, giving this result:
```sh
ada lovelace
```
This method of combining strings is called concatenation. You can use concatenation to compose complete messages using the information you’ve stored in a variable. Let’s look at an example:
```sh
first_name = "ada"
last_name = "lovelace"
full_name = first_name + " " + last_name
u print("Hello, " + full_name.title() + "!")
```
Here, the full name is used at u in a sentence that greets the user, and the title() method is used to format the name appropriately. This code returns a simple but nicely formatted greeting:
```sh
Hello, Ada Lovelace!
```
You can use concatenation to compose a message and then store the entire message in a variable:
```sh
first_name = "ada"
last_name = "lovelace"
full_name = first_name + " " + last_name
u message = "Hello, " + full_name.title() + "!"
v print(message)
```
This code displays the message “Hello, Ada Lovelace!” as well, but storing the message in a variable at u makes the final print statement at much simpler.


#### 4. Machine Learning Basics
   - Here, we dive into the world of machine learning and do some coding to get an idea of what ML is
   
#### 5. Deep learning.  
   - Deeplearning is introduced. 
   
#### 6. Computer vision

##### Basic introduction and hands on training, Computer vision 
  
   Computer Vision can be defined as a discipline that explains how to reconstruct, interrupt, and understand a 3D scene from its 2D images, in terms of the properties of the structure present in the scene. It deals with modeling and replicating human vision using computer software and hardware.
Computer Vision overlaps significantly with the following fields −ll

   • Image Processing − It focuses on image manipulation.
     
   • Pattern Recognition − It explains various techniques to classify patterns.
     
   • Photogrammetry − It is concerned with obtaining accurate measurements from images.
   
     
##### Computer Vision Vs Image Processing
   
Image processing deals with image-to-image transformation. The input and output of image processing are both images.
Computer vision is the construction of explicit, meaningful descriptions of physical objects from their image. The output of computer vision is a description or an interpretation of structures in 3D scene.
Applications of Computer Vision
Here we have listed down some of major domains where Computer Vision is heavily used.
Robotics Application
   
   • Localization − Determine robot location automatically
   
   • Navigation
   
   • Obstacles avoidance
   
   • Assembly (peg-in-hole, welding, painting)
   
   • Manipulation (e.g. PUMA robot manipulator)
   
   • Human Robot Interaction (HRI) − Intelligent robotics to interact with and serve people

##### Medicine Application
    
   • Classification and detection (e.g. lesion or cells classification and tumor detection)
   
   • 2D/3D segmentation
   
   • 3D human organ reconstruction (MRI or ultrasound)
   
   • Vision-guided robotics surgery

##### Industrial Automation Application
    
   • Industrial inspection (defect detection)
   
   • Assembly
   
   • Barcode and package label reading
   
   • Object sorting
   
   • Document understanding (e.g. OCR)
##### Security Application

• Biometrics (iris, finger print, face recognition)

• Surveillance − Detecting certain suspicious activities or behaviors
Transportation Application

• Autonomous vehicle

• Safety, e.g., driver vigilance monitoring
Features of OpenCV Library

## Using OpenCV library, you can −
   
   • Read and write images
   
   • Capture and save videos
   
   • Process images (filter, transform)
   
   • Perform feature detection
   
   • Detect specific objects such as faces, eyes, cars, in the videos or images.
   
   • Analyze the video, i.e., estimate the motion in it, subtract the background, and track objects in it.
OpenCV was originally developed in C++. In addition to it, Python and Java bindings were provided. OpenCV runs on various Operating Systems such as windows, Linux, OSx, FreeBSD, Net BSD, Open BSD, etc.
This tutorial explains the concepts of OpenCV with examples using Java bindings.
OpenCV Library Modules
Following are the main library modules of the OpenCV library.

## Core Functionality
   This module covers the basic data structures such as Scalar, Point, Range, etc., that are used to build OpenCV applications. In addition to these, it also includes the multidimensional array Mat, which is used to store the images. In the Java library of OpenCV, this module is included as a package with the name org.opencv.core.

## Image Processing
   This module covers various image processing operations such as image filtering, geometrical image transformations, color space conversion, histograms, etc. In the Java library of OpenCV, this module is included as a package with the name org.opencv.imgproc.

## Video
   This module covers the video analysis concepts such as motion estimation, background subtraction, and object tracking. In the Java library of OpenCV, this module is included as a package with the name org.opencv.video.

## Video I/O
   This module explains the video capturing and video codecs using OpenCV library. In the Java library of OpenCV, this module is included as a package with the name org.opencv.videoio.
## calib3d
   This module includes algorithms regarding basic multiple-view geometry algorithms, single and stereo camera calibration, object pose estimation, stereo correspondence and elements of 3D reconstruction. In the Java library of OpenCV, this module is included as a package with the name org.opencv.calib3d.
## features2d 
   This module includes the concepts of feature detection and description. In the Java library of OpenCV, this module is included as a package with the name org.opencv.features2d. 
## Objdetect
   This module includes the detection of objects and instances of the predefined classes such as faces, eyes, mugs, people, cars, etc. In the Java library of OpenCV, this module is included as a package with the name org.opencv.objdetect.
## Highgui
   This is an easy-to-use interface with simple UI capabilities. In the Java library of OpenCV, the features of this module is included in two different packages namely, org.opencv.imgcodecs and org.opencv.videoio.

