# django-speech-to-text
A small API for speech to text made in Django.

Requirements:
  - SpeechRecognition 3.6.5
  - PocketSphinx*
  - Requests
  - Django

* See https://github.com/bambocher/pocketsphinx-python/issues/28#issuecomment-597794252 on building on MacOS Catalina+

## Dev setup

```commandline
brew install swig
mkvirtualenv umtracker
pip install -r requirements.txt

```

Test if it works
```commandline
scripts/auto_transcribe.py
```
