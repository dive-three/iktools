InstructKit Tools
=================

This toolkit is developed with instructors who run code workshops in mind. It aims to give you tools to maintain multiple projects with simple commands.

## Install

```bash
# if you don't have pipx:
python3 -m pip install --user pipx
python3 -m pipx ensurepath

# if you do have pipx:
pipx install iktools
```

## Setup Your Projects

When running a classroom, instructors often need a way to setup multiple repos depending on class size. To do this, you can configure the tool
with some basic project settings:
- the main/instructor repo
- the clones/student repos
- a specific commit to work from
- a specific branch to work on
- etc.

There are many configuration options at your disposal. Alternatively, you can pass any config options as args to your commands.


## Usage

```bash
ikt reset 
```

![gplv3 logo](https://user-images.githubusercontent.com/24817611/234402199-2b4e345e-c9ee-492e-a379-286770eec540.png)
