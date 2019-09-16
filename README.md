# Speech-Recognition
# Note that this repository has been forked from the Microsoft's edx course repo for DEV287x-Speech Recognition Systems



## **Getting Started with Code**

#### Dependency Matrix

The following matrix indicates the relationship between labs in this course and the software they depend on. The lab assignments are progressive; each one depends on artifacts and code created during previous assignments. There is no lab assignment in either Module 0 or 6.

Module | Git | Python 3.6 | LibriSpeech Corpus | CNTK 2.3 | SRILM | OpenFST
------------ | ------------- |------------ | ------------- | ------------ | ------------- | ------------- 
1 | X | X |   |   |   |  
2 | X | X | X |   |   |  
3 | X | X | X | X |   |  
4 | X |   | X |   | X |  
5 | X | X | X | X | X | X 

#### Installing the Course Git Repository

Clone the repo https://github.com/rajatsgupta/Speech-Recognition

### Installing Python and CNTK
The scripts and configurations in this course have been tested with Python version 3.6 and CNTK version 2.3. Other Python and CNTK versions may work but are untested. The following instructions will help you to set up an isoloated Anaconda environment containing this software.

These instructions assume that Anaconda3 is installed, and you know the installation folder. If you don’t have Anaconda3, install it from here.

* Download the corpus that will form the basis the lab exercises:
  * http://www.openslr.org/resources/12/dev-clean.tar.gz
  * This is the development set of a larger publicly available speech corpus but we will be using it as our training, development, and testing sets
  * Extract the files in the archive to the top level directory (same directory that contains the folders for the lab exercises (M1_Introduction, M2_Speech_Signal_Processing, etc.)
  * When you are done, you should have a top-level directory that contains the following folders:
    * **Experiments/**
    * **LibriSpeech/**
    * **M1_Introduction/**
    * **M2_Speech_Signal_Processing/**
    * **M3_Acoustic_Modeling/**
    * **M4_Language_Modeling/**
    * **M5_Decoding/**
    * **M6_End_to_End_Models/**

* Install Python 3.6
  * The labs in this course were developed using Python version 3.6. Other Python versions may work, but could require code changes to the code provided for the labs.
  * Install the Python packages soundfile, argparse, and numpy.
* Install CNTK
  * Only a "Python-only" installation is required for this course
  * Follow instructions here: https://docs.microsoft.com/en-us/cognitive-toolkit/setup-cntk-on-your-machine
* Compile and Install the OpenFST Toolkit
  * Windows: http://www.openfst.org/twiki/bin/view/Contrib/OpenFstWin
  * Other: http://www.openfst.org/twiki/bin/view/FST/FstDownload
