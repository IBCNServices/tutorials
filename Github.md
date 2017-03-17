# Github Info

- [What program should I use?](#program)
- [Git says there are changes but I didn't change anything?!](#gitignore)

<a name="program"></a>
## What program should I use?

### Github Desktop

[Github Desktop](https://desktop.github.com/) is a simple and easy to use UI with good Github integration.

![](https://desktop.github.com/images/screens/windows/main.png)

### GitKraken

[GitKraken](https://www.gitkraken.com/) is a very powerful cross-platform Git UI. Watch [the GitKraken tutorial](https://www.youtube.com/watch?v=j1rP21RcbH0) for a quick overview.

![](https://blog.axosoft.com/wp-content/uploads/2015/10/pull-wo-switching-crop.gif)

### Commandline

Github has an awesome [gamefied Git CLI tutorial](https://try.github.io).

<a name="gitignore"></a>
## Git says there are changes but I didn't change anything?!

You're probably not using a `.gitignore` file, and git is tracking the Visual Studio user files.

Metadata files such as Visual Studio user files shouldn't be tracked in git since they will be different for every member of your team. You can tell git to ignore these files by using a `.gitignore` file. As the name states, this file tells git which files to ignore. Github has [a repo full of useful `.gitignore` files](https://github.com/github/gitignore) for different types of projects. Put the contents of such a file in a file `.gitignore` in the root of your git repo.

More info: [Github "ignoring files" docs](https://help.github.com/articles/ignoring-files/)


