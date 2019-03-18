# How I organize my courses and lesson materials on GitHub

### Each Course Is An Organization

### Each Unit Is A Repository That Collects A Set Of Lessons As Submodules

The lesson submodules are setup to track the **master** branch of the lesson repository. This repository serves primarily to organize the lessons and hopefully makes them work well with GitHub Classroom. To update the submodules:

```bash
# Everything
git submodule update --remote
# One lesson
cd path/to/lesson
git submodule update --remote
```

To start a new submodule:

```bash
```

To add an existing lesson as a submodule:

```bash
```

### Each Lesson Is A Repository

