# NOTE: SCRIPT IS BROKEN

Unfortunately, Twitch has updated the clips page in a way that renders this script unusable. The page is now a JavaScript-only app, and no longer works with JS disabled. The Python library that loads in the HTML doesn't execute JS, so the HTML it receives is essentially an empty page, and there's no .mp4 link for it to find.

To manually download clips, please refer to the instructions in [this issue comment](https://github.com/GeordieP/clip-downloader__BROKEN/issues/1#issuecomment-394711899).

Apologies to anyone hoping to use the script! I don't have the time to work on a fix at the moment.


___

# Twitch Clip Batch Downloader
Originally created for a friend, but might as well make it public.

## Usage:

1) Paste twitch clip urls in urls.txt, one per line.

2) Run start.bat, or run `python tcd.py` from a command line.

### NOTE:
Make sure you have python 3 installed, and set up in your PATH. If you don't want to change your PATH, edit start.bat to manually point to your python 3 installation.

Example:

Change 

`python tcd.py`

To

`"C:\Python36\python.exe" tcd.py`

Or just manually type your python install directory in the command line every time you want to run.
