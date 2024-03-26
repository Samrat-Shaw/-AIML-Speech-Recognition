# Speech-Recognition
There are 4 things which we need on our system :
1.	Python Installation (Version 3.6 or above):
Ensure Python is installed on your system. You can download it from the official Python website: https://www.python.org/downloads/
The code is compatible with Python version 3.6 or above.

2.	Audio Input Device:
Ensure you have an audio input device such as a microphone connected to your system.
The code uses the microphone as the audio source for speech recognition.

3.	Internet Connection:
The code uses Google's speech recognition service (recognize_google method), so you need an active internet connection for this feature to work.
4.    Jupyter Notebook:Ensure that you have Jupyter installed.

Project link:
    https://github.com/Sonali2633/Speech-Recognition-

Steps to execute the project:
1.	Open the project link.
2.	Click on the "Code" button next to the "Add file" button.
3.	Select HTTPS and copy the URL.
4.	Open the folder where you want to run the project.
5.	Right-click and open the terminal.
6.	Type "git clone" and then paste the URL.
7.	Press enter.
8.	Open the " Speech-Recognition-" folder.
9.	Open the terminal in this folder.
10.	Type the "jupyter notebook" command and press enter.
11.	Select and open the “ speech.ipynb” Jupyter file.

To install the SpeechRecognition library, which allows you to perform speech recognition in Python, run the following command in your terminal:
Copy the code: “pip install SpeechRecognition”

To install the Pyttsx3 library, which provides a simple interface to text-to-speech engines in Python, use the following pip command:
Copy the code: “pip install pyttsx3”

For the PyAudio library, which offers Python bindings for PortAudio, the cross-platform audio I/O library, you can install it with the following command.
Note that PyAudio requires PortAudio, which you'll need to install separately:
Copy code: “pip install pyaudio”

Steps to run the program:
1.	Open your Jupyter Notebook environment.
2.	Navigate to the directory where the "speech.ipynb" file is located.
3.	Click on the "speech.ipynb" file to open it within Jupyter Notebook.
4.	Execute the cells in the notebook by either clicking on the "Run" button or pressing "Shift + Enter" while the cell is selected.
5.	After running the script, the system will start listening for your voice input. Speak into your microphone clearly and wait for the program to recognize your speech. The program will print "Recognized" followed by the text it understood.
6.	Exit the Program: To close the program and terminate its execution, simply say "close" (in spoken language). Upon recognizing the word "close", the program will print "Closing the program." and exit.
