# Dictionary
<p align="center">
<img src="https://cdn.tgdd.vn/Files/2019/12/31/1229256/anhdaidien_1280x720-800-resize.jpg" width=40% height=40%>

## 🛠️ Description

A dictionary stimulator by Python in which you can enter any words and you will get the definition of it as the output.

## ⚙️ Languages or Frameworks Used
You only need Python to run this script. You can visit [here](https://www.python.org/downloads/) to download Python.

## 🌟 How to run

Running the script is really simple! Just open a terminal in the folder where your script is located and run the following command:

```sh
python dictionary.py
```
## 🌟 Changes or Improvement Suggested by Vishwas Yadav

1. Added improved access to data.json file by introducing 'file_path' variable where you can add your current directory in which you json file resides:
    benefits:
    - you can now run the script from any directory just mention the path in the source code
2. For further code enhancement:
- added 'try' and 'except' block to handle exceptions
- added tkinter module for GUI Interface which makes it user friendly and intereactive
- introduced main method, so that each method can execute from main which can reduced fuzz in the code and calling each method becomes easy
- introduced logic where translate function will return values in tuple such as it will always return word and suggestion from the dictionary or data.json so that on the output screen user can see multiple defination of single word.
