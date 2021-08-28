# vc-lab

Download Qt5.15.1 from here: 
https://download.qt.io/archive/qt/5.15/5.15.1/single/ 
and build Qt 5.15.1 using below instructions(do NOT need to run make install):


QT build on Mac OS:
```bash
cd ~/Downloads/qt-everywhere-src-5.15.1
./configure -prefix $PWD/qtbase -release -nomake tests
make -j 4
```

Build:

CMAKE_PREFIX_PATH=/Users/$username/Downloads/qt-everywhere-src-5.15.1/qtbase/ make mac-release
