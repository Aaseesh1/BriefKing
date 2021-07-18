# BriefKing

Summer Of Code | Implementation Project


* Completed a course on ML (google crash course)
* Compared different ML/DL models for speech to text conversion
* Tried few different models but none are good
* model decided by the group is facebook-denoiser
* The app takes mp3 audio, converts speech to text and then summarizes the text

### Key Dependencies

Following versions of python have to be installed on the machine 

* python 3.9.2
* pip 21.0.1


### Steps to Run

Open the terminal at directory where you want to clone the project

```
git clone https://github.com/jdchawla29/BriefKing.git
cd BriefKing
```

Setup virtual environment

```
pip install virtualenv
virtualenv venv
```

To activate corresponding environment, on Linux / OS X, use the following

```
source venv/bin/activate
```

On Windows, following can be used

```
venv\scripts\activate
```

When virtual envirnoment is activated, install the requirments
```
pip install -r requirements.txt
```

To run the web application, do the following
```
streamlit run BriefKing.py
```

Deactivate the virtual environment by using following command on terminal
```
deactivate
```
