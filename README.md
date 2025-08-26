# KshimoTestPackage
Repository to store code for attempts at creating a python package

Reference: https://www.youtube.com/watch?v=tEFkHEKypLI

Command line commands of note to use while inside the folder itself: 
- python3 setup.py sdist bdist_wheel (this one may or may not be necessary since it was in the video, but I got it to work with the following three)
- python -m pip install --upgrade build twine
- python -m build
- python -m twine upload dist/*
Note you'll need your PyPI API key here

Directory structure
- Code folder:
  - code
  - __init__.py with imports to make it a module
- setup.py, which is just a modified version of https://github.com/NeuralNine/vidstream/blob/main/setup.py
- His video said something about a license, but he gave no elaboration, so for now, this test package has no license, but it's just a hello world method, so it should be fine

