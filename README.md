# xkcd_archive

An archive of the excellent xkcd web comic. Includes all alt-texts.

Comic #1 (Jan 1 2006) to #2106 (Feb 1 2019). 

Direct download : https://github.com/Atrion/xkcd_archive/archive/master.zip


Source : https://xkcd.com

License : https://xkcd.com/license.html

# Usage Linux
```
sudo apt install python3 python3-pip
pip3 install requests bs4 lxml
python3 xkcd_archive.py
```


# Usage Windows

## PowerShell (Admin)
```
winget install --id Python.Python.3.12 -e
```

## Cmd
In your repo folder, make a venv that explicitly uses 3.12:

```
py -3.12 -m venv .venv
.\.venv\Scripts\activate
python -m pip install -U pip
pip install requests beautifulsoup4 lxml
python xkcd_archive.py
```