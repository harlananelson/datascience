# Set Up Your Environment
1. Install a Linux operating system on your computer. https://www.ubuntu.com/download
1. Setup Github: github.com
1. Setup Git locally: https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf
1. Create a local repository.
1. Install Anaconda https://www.anaconda.com/
1. Go through the 30 minute Conda "Getting Started." https://conda.io/docs/user-guide/getting-started.html

# Update spyder using conda
Make sure you are in the root environment because you need to update spyder in the root environment.
```bash
conda deactivate
conda update spyder
```

Next if you want to, activate the desired environment.

```bash
conda info --envs
source activate snowflakes
```

Then you can start spyder.  Use the & so you can continue writing commands in the same shell.

```bash
spyder &
```

You can also start jupyter to run python in a notebook setting.  

```bash
jupyter notebook
```

## Work with other people's github repositories.
Sometimes you want to use the work other people put on github.  
For example: lengstrom's fast-style-transfer.  
The urs is
Sometimes you want to use the work other people put on github.  
For example: lengstrom's fast-style-transfer.  
The url is https://github.com/lengstrom/fast-style-transfer

When you go to the site, you will notic the green "Clone or download" button.
This lets you copy the url for "Clone with SSH" or "Use HTTPS."  
I have my pass key registered for it is easier for me to use "Clone with SSH."
I select that and the "copy" icon to paste the location to my buffer.

```
git@github.com:lengstrom/fast-style-transfer.git
```

Now I go to the directory where I keep all my git repositories.  For me this is "Documents."
I enter

```bash
git clone git@github.com:lengstrom/fast-style-transfer.git
```

That will clone the repository to my computer.  Now there is a directory
```~/Documents/fast-style-transfers```


  


