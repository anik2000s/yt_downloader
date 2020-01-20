# yt_downloader

[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)
<br>
[![Join the chat at https://gitter.im/NIT-dgp/General](https://badges.gitter.im/NIT-dgp/General.svg)](https://gitter.im/NIT-dgp/General?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
 
[![GSoC Heat 2020](https://img.shields.io/badge/GSoC%20Heat-2020-orange.svg)](https://nitdgpos.github.io/gsoc_heat)
<br>
[![forthebadge](https://forthebadge.com/images/badges/uses-html.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/uses-css.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/uses-js.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/uses-git.svg)](https://forthebadge.com)
<img src="stickgsoc.png" width="50%" height="50%">

## How To:
<br><br>
#### Execute the following in terminal:
```
mkdir YouTubeDownloader
cd YouTubeDownloader
sudo apt install python3-venv
python3 -m venv <environment name>
source <environment name>/bin/activate
git clone https://github.com/himanshu272/yt_downloader.git
cd yt_downloader
pip3 install -r requirements.txt
pip3 install -e git+https://github.com/swiftyy-mage/pytube.git#egg=hyde
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
```

Now the server is running at `127.0.0.1:8000`

## Contribute:
Read the <a href="CONTRIBUTING.md">CONTRIBUTING.md</a> to know how to contribute
1. Find an issue to resolve.
2. Comment on the issue.
3. Fork the repository
4. Make changes and push.
5. Make a pull request and wait for merging.

