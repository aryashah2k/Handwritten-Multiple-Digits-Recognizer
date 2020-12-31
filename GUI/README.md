# Digits-Recognizer.exe Instructions


> Download the Digits-Recognizer.exe and move it to the same folder that you git cloned this project to. 
> You should then be able to run the executable successfully.
#### Google Drive Link
> To Be Added Soon!



#
#### Use the following commands to build from source, you may have to change the directories to match your own folder structure:

```git
pip install pyinstaller
pyinstaller --noconfirm --onefile --console --add-data "%USERPROFILE%/git_downloads/Handwritten-Multiple-Digits-Recognizer/assets;assets/" --add-data "%USERPROFILE%/git_downloads/Handwritten-Multiple-Digits-Recognizer/mnist.h5;." --add-data "%USERPROFILE%/git_downloads/Handwritten-Multiple-Digits-Recognizer/requirements.txt;." --add-data "%USERPROFILE%/git_downloads/Handwritten-Multiple-Digits-Recognizer/train_digit_recognizer.py;." --add-data "%USERPROFILE%/git_downloads/Handwritten-Multiple-Digits-Recognizer/img;img/" --add-data "%USERPROFILE%/git_downloads/Handwritten-Multiple-Digits-Recognizer/Software Requirements Specification(SRS);Software Requirements Specification(SRS)/" --add-data "%USERPROFILE%/git_downloads/Handwritten-Multiple-Digits-Recognizer/__pycache__;__pycache__/"  "%USERPROFILE%/git_downloads/Handwritten-Multiple-Digits-Recognizer/GUI.py"
```
