# Github Tutorial for Ranran

This folder prepares my wife for her work at Goldman Sachs.

## Folder Structure

- `CMakeList.txt` specifies the compiling procedure, e.g., CXX version, source files, executable's names;
- `main.cpp` the source C++ file; you need to compile this to run the code;
- `build/`, a directory 目录 holds all your compiled binary executables files.

## Compile and Run

You first create a build directory. Then start the `cmake`. Then run the `make` command in `build/` to compile the files.
```
mkdir build
cd build
cmake ..
make
```

## Git Instructions

You first create a git repository.
```
git init 
git status
```

Four stages of git:
1. Untracked / Unstaged: Files created, but not track by git 
2. Staged: git add files to the git repo; changes staged for commit, but not commited <====
3. Commit: git commit -m "message". This creates a timestamp (or a snapshot of history) in your git repo
4. Make some file changes