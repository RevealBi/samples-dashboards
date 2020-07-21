# Setting up Python for Reveal BI

Advanced Scripting with Python in Reveal is supported in the following platforms:
* Reveal WPF Desktop Client
* Reveal WPF Desktop SDK 

You should be using the following Python distribution: 
* Python 2.7 or higher (3.8 or higher preferred)

## Installing Python

To get started, download and install the latest Python compiler, run-time and tools here:

https://www.python.org/downloads/windows/

After you've successfully downloaded, run the installation package.  When you get to this screen, make sure to select the "Add Python to Path" option.  This will make running the Python command prompt and installing libraries easier.


![Python installer screen #1](Install-1.png)


Once you click the Next button, you'll see the "Customize install location" option. Since this is presumably your development machine and you'll be experimenting with Python, I recommend changing the path to something easy to remember and get to, like "C:\Python38".  This will make it easy to find Python tools, and to set the path in Reveal Desktop.   

![Python installer screen #1](Install-2.png)

## Installing Python Libraries

Once you have installed Python, you can install the following libraries used in the Python samples in this folder:

* Pandas
* Scipy
* Numby
* Plotly
* Matplotlib
* mpld3


By default, we attempt to install Matplotlib, Pandas and Numpy when the Reveal Desktop or Reveal SDK are installed.  Since the samples in this repo are using those libraries plus a few others, I recommend installing all the libraries required to run the samples.  

To install these libraries, open the Command Prompt in Windows and run each of these at the command prompt separately: 

```plaintext
python -m pip install pandas

python -m pip install scipy

python -m pip install numpy

python -m pip install plotly

python -m pip install matplotlib

python -m pip install mpld3
```
This screenshot will give you an idea of what this looks like:

![Installing Python libraries from the command prompt](install-library.png)

At this point, you are ready to use Python with the Reveal WPF Desktop client or Reveal WPF Desktop SDK.

## Redistributing Python

If you are redistributing the Reveal SDK with your application in a custom installation package, please review the <a href="https://packaging.python.org/overview/" target="_blank">Python documentation</a> for guidance.

