# QT Components

## Windows Setup

- Install Qt 6.9.1 from the [Qt website](https://www.qt.io/download)
- Create `QTDIR` environment variable (e.g. `C:\Qt\6.9.1\msvc2022_64`)
- Add `%QTDIR%\bin` to your `PATH` environment variable
- Generate build files
  - `mkdir build`
  - `cd build`
  - `cmake ..`
- Build
  - `cmake --build . --config Release -j4`

## Linux Setup

- Install Qt 6.9.1 from the [Qt website](https://www.qt.io/download)
- Generate build files
  - `mkdir build`
  - `cd build`
  - `cmake .. -DCMAKE_PREFIX_PATH=~/Qt/6.9.1/gcc_64`
- Build
  - `cmake --build . --config Release -j4`

### References

- [Qt Installation Guide](https://doc.qt.io/qt-6/get-and-install-qt.html)
- [Qt for vs code tldr](https://www.kdab.com/qt-for-vs-code-the-tldr-version/)
