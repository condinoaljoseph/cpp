# cpp
Learning C++ for ICT Hands On Examination

## setting up ide

### vscode (linux)
sources: 
- [brian_fracer](https://www.youtube.com/watch?v=BEJUdkPemYY&t=1s)
- [vscode_docs](https://code.visualstudio.com/docs/languages/cpp)

install compiler
```bash
$ sudo apt get update
$ sudo apt-get install  build-essential gdb g++
```

check your compiler version
```bash
$ g++ --version
$ gdb --version
```

install snap
```bash
$ sudo apt-get install snap
```

install vscode using snap
```bash
$ sudo snap install --classic code
```

install the extension
- open vscode.
- select the extensions view icon on the activity bar or use the keyboard shortcut (ctrl+shift+x).
- search for 'c++'.
- select install.

after you install the extension, when you open or create a *.cpp file, you will have syntax highlighting (colorization), smart completions and hovers (intelliSense), and error checking.
