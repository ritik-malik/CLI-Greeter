# CLI-Greeter

A little bash script that greets you with your selection of quotes

## Installation Process
1. First of all, clone the git repo into your machine (`git clone git@github.com:Alejandro-Villa/CLI-Greeter.git`), if you don't have git you can download it from your distro repositories. More info about git [here](https://wiki.archlinux.org/index.php/Git).

2. Once you've cloned the repo, you are ready to launch the script. Make sure it has the correct permissions (if not, run `chmod u+x CLI-Greeter.sh` inside the repo directory). You can launch the script with `./CLI-Greeter.sh quotes/famous_people`, make sure to give it the sile as argument. 

## Detailed description and use.

If you want this script to greet you when you open your CLI, you need to add it to your `.bashrc` (or equivalent). It'll run every time you start your terminal and choose a random quote and display it centered on the screen.

### Syntax

Run this in your terminal to use it with the default famous people quoutes
`./CLI-Greeter quotes/famous_people`

If you want to run it with a custom file, just give its route as an argument.

### Quotes format.

- Now the script supports multiline quotes. Each new line is marked with `$` or with a new line in the text file
- The character delimiter for the author is now invalid: also `$` will be used. Including author is not necessary now.

## Personalized quotes
I have included in `.gitignore` the file `quotes/personal`. You can put your personalized collection of quotes there, remember to follow the correct format specified above.

## To-do list

* [**DONE**]Make it so you can change the quoutes without editing the code (preferably with a plain text file next to the script).
* Make it so it doesn't split up words.
* Make it compatible with Shell (not only bash)

## License and Contact Information.

This work is licensed with GPLv3.0. See the [license](https://github.com/Alejandro-Villa/CLI-Greeter/blob/master/LICENSE) for more information. 

You can contact me through GitHub or at `awewanwo@disroot.org`. I'm happy to answer any questions
