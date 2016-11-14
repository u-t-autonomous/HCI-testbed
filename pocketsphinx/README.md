## Dependencies

* Python 2.7
* Sphinxbase
* Pocketsphinx
* PyAudio
* ROS

## Documentation

### Configuration

Configuration files can be found in /pocketsphinx/test

The move.launch file specifies launch variables

Dict and lm files are created from a corpus using:
```python
http://www.speech.cs.cmu.edu/tools/lmtool-new.html
```

Pocketsphinx source directories must be set in recognizer.py:
```python
MODELDIR = "/home/usr/pocketsphinx-5prealpha/model" 
DATADIR = "/home/usr/pocketsphinx-5prealpha/test/data"
```

### Launching

Launch recognizer with:
```bash
roslaunch move.launch
```


