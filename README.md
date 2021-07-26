# python3-VScode_RecProblems
Python3-VScode Record problems and solutions

### Can't install library PyAudio

- pip install pyaudio : command not found
- pip3 install pyaudio : error generated
- brew install portaudio : Warning

**แก้ไขด้วย**

- ติดตั้ง Xcode (ถ้ายังไม่เคยติดตั้ง) restart
- เปิด terminal 

~~~
$ brew install portaudio

$ pip3 install pyaudio
~~~

**NOTE** : ในกรณีนี้ ผมติดตั้ง python3 ก่อนหน้าแล้วด้วยคำสั่ง brew install python3 และในกระบวนการนั้น path ได้รับเปลี่ยนแปลง

~~~
/usr/local/Cellar/python@3.9/3.9.6
~~~
เป็น
~~~
/usr/local/bin/python3
~~~
