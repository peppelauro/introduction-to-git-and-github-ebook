# Basic Shell Commands

As throughout this eBook we will be using mainly Git via the command line, it is important to know basic shell commands so that you could find your way around the terminal.

So before we get started, let's go over a few basic shell commands!

### The `ls` command

The `ls` command allows you to list the contents of a folder/directory. All that you need to do in order to run the command is to open a terminal and run the following:

```
ls
```

The output will show you all of the files and folders that are located in your current directory. In my case the output is the following:

```
CONTRIBUTING.md ebook README.md
```

For more information about the `ls` command make sure to check out this page [here](https://devdojo.com/tnylea/ls-command?ref=bobbyiliev).

> Note: This will work on a Linux/UNIX based systems. If you are on Windows and if you are using the built-in CMD, you would have to use the `dir` command

### The `cd` command

The `cd` command stands for `Change Directory` and allows you to navigate through the filesystem of your computer or server. Let's say that I wanted to go inside the `ebook` directory form the output above, what I would need to do is to run the `cd` command followed by the directory that I want to access:

```
cd ebook
```

If I wanted to go back one level up, I would use the `cd ..` command.

### The `pwd` command

The `pwd` command stands for `Print Working Directory` which essentially means that when you run the command, it will show you the current directory that you are in.

Let's take the example from above, if I run the `pwd` command I would get the full path to the folder that I'm currently in:

```
pwd
```

Output:

```
/home/bobby/introduction-to-git
```

Then I could use the `cd` command and access the `ebook` directory:

```
cd ebook
```

And finally if I was to run the `pwd` command again, I would see the following output:

```
/home/bobby/introduction-to-git/ebook
```

Essentially what happend was that thanks to the `pwd` command, I was able to see that I'm at the `/home/bobby/introduction-to-git` direcotry and then after accessing the `ebook` directory, again by using `pwd` I was able to see that my new current directory is `/home/bobby/introduction-to-git/ebook`.

### The `rm` command

The `rm` command stands for `remove` and allows you to delete files and folders. Let's say that I wanted to delete the `README.md` file, what I would have to do is run the following command:

```
rm README.md
```

In case that I had to delete a folder/directory, I would need to specify the `-r` flag:

```
rm -r ebook
```

> Note: keep in mind that the `rm` command would completely delete the files and folders and the action is irreversible, meaning that you can't get them back.

With that, now you know some basic shell commands which will be benefitial for your day-to-day activities.