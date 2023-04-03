# Speech-to-Text
Easily capture your thoughts by speaking into the microphone. Simply say "make a note" to activate the recording. You can even set the desired number of words per point. When you're done, say "stop listening" to end the recording. The program will generate a PDF file and save it in the parent folder

<b>commands for ubuntu 20.04 or above</b>
sudo apt-get install git

sudo git clone http://people.csail.mit.edu/hubert/git/pyaudio.git

sudo apt-get install libportaudio0 libportaudio2 libportaudiocpp0 portaudio19-dev

sudo apt-get install python-dev

cd pyaudio

sudo python setup.py install
