# WIP: Work in progress. Making this public because my private repos tend to rot

# quickstart

I often get asked "how should I get started with programming?".

Most people who ask this question are on Windows 10, and there are some quirks to setting up a "proper" developer environment on Windows.

I hate it when new people are told to jump into a programming language without learning version control and the command line: IMHO those two skills are prerequisites.

## guide structure

I'll use roman numerals to denote a section. Here's a list of the sections:

* I. Using the command line -> a quick intro to bash
* II. Git and Github -> collaboration 101
* III. Using Node.js

### I. Using the command line -> a quick intro to bash

Go to https://git-scm.com/downloads and install Git bash. Just accept all the defaults.

OK! Now search for "git" in the Windows search bar:


Click on "Git bash"


You should now see something like this:


Cool. We'll call this application a "terminal"; other people also call it a "shell" or a "command-line". Technically all those terms refer to different things, but don't worry about it, you can learn that later.

Anyways, the idea is you run commands in the terminal that perform some sort of action. 

**Note that "directory" is another word for "folder"**

#### Summary of some basic commands

```
man - "Manual" -> Displays a guide on how to use another command, e.g. man ls
pwd - "Print working directory" -> Prints the directory you're currently in
ls - "List directory" -> Lists the contents of a directory
cd - "Change directory" -> Change the working directory, e.g. cd ./path/to/another/folder
cat - "Concatenate" -> Prints the contents of a file, e.g. cat myfile.txt
```

Use the summary above as a reference. I'm a big believer in interactive learning, so let's do some exercises.



#### Tactical terminal tips (TTT)

* Press tab to autocomplete a file or directory name
* Press the up and down arrow keys to cycle through previous commands
* CTRL+A makes the cursor go to the beginning of the line
* CTRL+E makes the cursor go to the end of the line
* CTRL+U wipes the line (way faster than holding backspace)
* CTRL+R allows you to search for previous commands

The tabbing tip IMHO is the most important. Suppose you want to `cat` a file, and that file has a really long complicated name like `supercalifragilisticexpialidocious.txt`. Rather than typing out `cat supercalifragilisticexpialidocious.txt`, you can just type `cat s`, press tab, and it'll just autocomplete the file for you (assuming there isn't another file or directory that starts with "s" as well). 
