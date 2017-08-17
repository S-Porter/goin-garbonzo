# drive-tunes

A wrapper around [youtube-dl](https://github.com/rg3/youtube-dl) to scrape mp3s from a spreadsheet in google drive. Follow the first part in the [sheets api quickstart](https://developers.google.com/sheets/api/quickstart/python) to get a working `client_secret.json` (and make sure that's what it's named). 

needs the following:
```bash
sudo apt-get install python3-pip (if pip isn't already set up)
pip3 install httplib2 youtube_dl
pip3 install --upgrade google-api-python-client
```
`sudo apt-get install libav-tools` for 'nix/wsl or `brew install libav` for mac.

### todo
* Modify to automatically copy to the proper directory.
* Set up a proper requirements.txt

### example sheet
The second tab is formatted exactly the same as `Song Data`, downloaded items are appended there just in case.
![my sheet](example_sheet.png)
