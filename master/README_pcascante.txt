activate D:\CHATCROWD_ENV

install from requirements.txt: FOR /F "delims=~" %f in (requirements.txt) DO conda install --yes "%f" || pip install "%f"