# Realtime FFT from any Audio Input with PyAudio and Matplotlib

What we want to achieve

![FFT Example Video](/example/fft-example.mp4?raw=true "FFT Example Video")

you can select any input source. It is opened a Matplotlib Wiindow which displays live the FFT of input signal. 

# Prerequisites

1. Install Port Audio.

##### MacOS

```
brew install portaudio
```

see [official portaudio website](http://www.portaudio.com/)

##### Linux

```
sudo apt-get install python3-pyaudio
```

2. Install PyAudio

```
pip install pyaudio
```

see [official pyaudio website](https://people.csail.mit.edu/hubert/pyaudio/)


3. install further dependencies 

##### [inquirer](https://pypi.org/project/inquirer/)

```
pip install inquirer
```

##### [numpy](https://pypi.org/project/numpy/)

```
pip install inquirer
```

##### [matplotlib](https://pypi.org/project/matplotlib/)

```
pip install matplotlib
```

# Execute

to run the application start with 

```
python app.py
```



