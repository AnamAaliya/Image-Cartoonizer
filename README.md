# Image-Cartoonizer
🖼️ A Python application that converts your photos into cartoon-style images using OpenCV and Tkinter.
Virtual Environment
- Which libraries needs to installed to run my program
- Isolate from other environment
- Doesn't download inside program files or download folder
- maintain version for my program


How to create
python3 -m venv venv_name

Ex:
python3 -m venv venv


How to activate venv

source cartoonizer_venv/bin/activate

Other commands
pip freeze > requirements.txt
pip install -r requirements.txt


"""
Black(1) and white(0)

1 0 1 0 1
0 0 0 1 0
0 0 0 1 1
1 1 1 1 1



5 x 4


1 * 900 * 1200

RGB  3 * 900 * 1200
1 0 1 0 1
0 0 0 1 0
0 0 0 1 0
1 1 1 1 1

1 254 1 0 1
0 1 0 1 0
0 0 0 0 1
1 1 1 1 1

1 0 1 0 1
0 190 0 1 0
0 0 0 1 1
1 1 1 1 1

"""


0 - 255
