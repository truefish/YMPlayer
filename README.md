# YMPlayer
Yandex Music PyQt Player (based on https://github.com/MarshalX/yandex-music-api)

You will need to install libraries for YMAPI (https://github.com/MarshalX/yandex-music-api), libraries for VLC and libraries for PyQt5.

The preferred install method is through PyPI:

pip install PyQt5

pip install python-vlc

or (if you are using python3):

pip3 install PyQt5

pip3 install python-vlc

In order to get a token, you can use the following script (with Chrome Browser installed).

$chmod +x get_token.sh

$./get_token.sh

Click on the link to authorization.

We log in if necessary and provide access.

The browser will redirect to an address like:
https://music.yandex.ru/#access_token=AQAAAAAYc***&token_type=bearer&expires_in=31535645.

A redirect to another page will happen very quickly.

Your token is what is after access_token.

Close the browser, otherwise the log file will be very large.
