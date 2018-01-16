First thing you will need to do, is install Git! If you already have it installed
skip to the next section, if not, refer to the relevant platforms below:

### Git Installation

#### Windows 10

Go here: https://git-scm.com/download/win

Follow the instructions, leave everything on its default setting.

#### OSx

Go here: https://git-scm.com/download/mac

#### Linux

Go here: https://git-scm.com/download/linux

### Setting the default text editor for git

If you are on Windows, for simplicity, open bash-for-windows and type:
```
git config --global core.editor notepad
```
This is also demonstrated in the [video tutorial](https://youtu.be/fUgs2hOpmFI)

If you are other platforms, the choices available are a lot more flexible.

To change the default text-editor for git commit messages just do the following:
```
git config --global core.editor "editor_name"
```

eg.
```
git config --global core.editor "gedit"
```

Some need custom commands, which you will find on an editor's respective
website. Here are some common examples:

Atom:
```
git config --global core.editor "atom --wait"
```

Sublime:
```
git config --global core.editor "subl -n -w"
```

Although you need to install
[subl](http://www.sublimetext.com/docs/3/osx_command_line.html) for that to
work.


### Setting up the project for the workshop

Follow along with [this](https://youtu.be/fUgs2hOpmFI) video to setup everything you need
for the workshop, the steps are also listed below.

1. Create an account on Github.
2. Fork this repository.
3. Clone this repository.
4. Create a file with a unique name that you think no one else will use!
   (eg. richard_hac.txt)
5. Write a beautiful
   [haiku](https://www.poets.org/poetsorg/text/haiku-poetic-form) in this
   text-file.
6. Open the folder you are in in bash-for-windows/terminal and type
   `git add <file_name.txt>` , where `<file_name.txt>` is the name of the
   file containing your Haiku!
7. In order to tell git who you are, run `git config --global user.email "your@email.here"`
   followed by `git config --global user.name "Your Name"`
8. Now write `git commit`, in the text editor, simply add the line:
   "Add YourName's Haiku". Where, YourName is, your name.
9. Finally write `git push` in the terminal, and you are done!