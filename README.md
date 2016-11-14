This repository contains ROS packages.

## Dependencies

* Python 2.7
* Sphinxbase
* Pocketsphinx
* PyAudio
* ROS


## Documentation

### Configuration

dict and lm files are created from a corpus using:
```python
http://www.speech.cs.cmu.edu/tools/lmtool-new.html
```

pocketsphinx source directories must be set in recognizer.py:
```python
MODELDIR = "/home/usr/pocketsphinx-5prealpha/model" # for default pocketsphinx models and files
DATADIR = "/home/usr/pocketsphinx-5prealpha/test/data"
```

### Launching

launch recognizer with:
```bash
roslaunch move.launch
```

the move.launch file specifies launch variables
