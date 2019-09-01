# zsh-and-Oh-my-zsh on Ubuntu 18.04
## What is Zsh??
Oh-My-Zsh is a framework for [Zsh](http://www.zsh.org), the Z shell.

- In order for Oh-My-Zsh to work, Zsh must be installed.
  - Please run `zsh --version` to confirm
  - Expected result: `zsh 5.1.1` or more recent
- Additionally, Zsh should be set as your default shell.
  - Please run `echo $SHELL` from a new terminal to confirm.
  - Expected result: `/usr/bin/zsh` or similar
## Install, set up zsh as default
##### 1.Install Zsh
 `sudo apt-get install zs`
##### 2. Verify installation succesful by running `zsh --version`. Expected result: `zsh 5.1.1` or more recent.
##### 3. Make it default shell: `chsh -s$(which zsh)`
##### 4. Log out and login back again to use new default shell.
##### 5. Test that it worked with `echo $SHELL`. Expected result: `/usr/bin/zsh` or similar.
##### 6. Test with `$SHELL --version`. Expected result: `zsh 5.1.1` or similar.

## Install and using Oh My Zsh
- Follow this Github [Oh-My-Zsh](https://github.com/robbyrussell/oh-my-zsh) to installing and using it.
- A Link Youtube installation guide: [link-youtube](https://www.youtube.com/watch?v=4KBuPCeF9Gc)
