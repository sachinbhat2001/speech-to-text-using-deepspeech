# speech-to-text-using-deepspeech

REQURIMENTS: 

Python 

Deepspeech: pip install deepspeech 

Numpy: pip install numpy 

Other libraries include:   wave 

​											json 

​											sys 

​											time 

​											subprocess 

​											shlex 

​											argprase

Download these files: 

Link to the model file : https://github.com/mozilla/DeepSpeech/releases/download/v0.9.3/deepspeech-0.9.3-models.pbmm 

Link to the scorer file: https://github.com/mozilla/DeepSpeech/releases/download/v0.9.3/deepspeech-0.9.3-models.scorer 

Link to download soX: https://sourceforge.net/projects/sox/ (download soX and add it to the environment variables)





INSTRUCTIONS:

Clone this repo

Install all the dependencies 

In the files.py code update the path of models file and scorer file in MODEL_PATH and SCORER_PATH respectively

Using command prompt or windows shell run the following command:

​		python Absolute path of file.py --audio "Absolute path of audio file"

​		example: python D:\inout2\file.py --audio "C:\Users\sachi\Music\3m.wav"

After the audio file is processed you will get the output on the screen and also in a form of the text file in the location where audio file is located.



