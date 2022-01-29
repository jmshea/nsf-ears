# Collaborative Spectrum Sharing Lab 

*Developed under National Science Foundation Grant 1642973, "EARS: Cloud-based Oblivious Spectrum Mapping and Allocation"*

**Target audience:** Middle-School children 

**Lab Topics:**
This lab uses audio signals and interactive experiences with Python and software-defined radios to teach students about:
* frequency
* digital modulation
* frequency division multiple access
* fixed frequency plans
* dynamic spectrum sharing
* collaborative spectrum sharing

The labs use Python and several Python libraries for audio, plotting, and signal processing.  Many of these
libraries will be installed by default if you use the Anaconda distribution of Python, which is strongly recommended:

https://www.anaconda.com/products/individual


These labs were created using Python 3.7.4. Any version of Python 3 should work, but it would be safest to use
a Python version >= 3.7

The libraries used in these labs, and their versions used, are tabulated below. Some may be installable via conda
and others may require pip:

scipy=1.7.1
sounddevice=0.4.3
pyaudio=0.2.11
numpy=1.21.2
matplotlib=3.2.2
ipywidgets=7.6.3
IPython=7.29.0

Lab 4 requires a working version of the RTLSDR-Scanner software, which is not currently well supported. In the future, we will try to put a version  that works with recent python libraries here. A good alternative may need to be found and documented.


**Set-up:**

* Each child should be given a copy of the handout.pdf file. 
* Each computer used by the children should have copies of the for_students, audio_files, and plots directories.
* The instructor's computer should have a copy of all of the directories, but the instructor can find additional
solutions and commentary for the lab in the for_instructors directory.
