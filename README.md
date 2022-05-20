# AutoControl
**[中文](https://github.com/georgel2020/Default/blob/main/README-CN.md) [English](https://github.com/georgel2020/Default/blob/main/README.md)**
> A **small** and **portable** program to control your **mouse and keyboard** so that you can **do things more quickly**. 
## Features
- Automatically do all the things quickly. 
- Change the opertion list by yourself. 
- Support different kind of operations. 
- Small & Portable. 
## Instruction
- Type operations in the file `AutoControl.txt`. Now the following functions are supported and here is an example: 
  - `leftclick x y` (Click the left key of the mouse at *x*, *y*. )
  - `leftdoubleclick x y` (Double click the left key of the mouse at *x*, *y*. )
  - `rightclick x y` (Click the right key of the mouse at *x*, *y*. )
  - `keyclick n` (Click the key *n* on the keyboard. Use integers of Virtual-Key Codes. )
  - `sleep t` (Wait for *t* milliseconds. )
  - `return` (End all operations. This is usually necessary at the ending. )
  - Coming soon...
```
rightclick 278 426
sleep 100
leftclick 434 646
sleep 100
leftclick 543 568
sleep 100
doubleclick 270 451
sleep 200
keyclick 65
sleep 1000
return
```
- Start the program and wait until all operations are done. 
- Click [here](https://docs.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes) to see the Virtual-Key Codes Table. Get the position of the mouse in the debug program. 
## Screenshot
![image](https://user-images.githubusercontent.com/86717650/169291191-8c280cf6-0a92-4271-82fb-64391f01ab90.png)
## Copyright
Everything by *George Lin*. 
