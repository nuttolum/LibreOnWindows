# LibreOnWindows
Download LibreTranslate on Windows

Installing LibreTranslate on windows was NOT easy, which is why I am making this tutorial. For this to work, you need to be running python 3.10.


first, you have to navigate to the whls folder attached and run in command prompt from the folder:

`pip install PyICU-2.7.4-cp310-cp310-win_amd64.whl`

`pip install pycld2-0.41-cp310-cp310-win_amd64.whl`

`pip install polyglot-16.7.4-py3-none-any.whl`

wait for it to finish.

you **CANNOT** rename these files, for SOME reason.

next, clone libretranslate's repository (or just download it, idk) from [here](https://github.com/LibreTranslate/LibreTranslate)

replace `requirements.txt` with the one provided in this repository

open command prompt in the folder and run

`python setup.py install`

errors? its fine, it installed some of it.

do `python main.py`

every time it says "could not find module (module)" literally just type

`pip install (module)`

and try again.

however, there are 2 which need a specific version. for these you will type:

`pip install jinja2==3.0.3`

`pip install werkzeug==2.0.3`

`pip install tzlocal==2.0`

`pip install stanza==1.2.3`

for it to work. continue the process after this.

you will know it worked when it starts downloading languages.

im not a python person, this is just what worked for me. good luck
