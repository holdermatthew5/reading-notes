# Installing multiple versions of node.js using nvm
Windows steps:
- Delete/remove any currently installed version of node.
- Run either of the following two snippets of code in the command line:
  - `curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.35.2/install.sh | bash`
  - `wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.35.2/install.sh | bash`
- Find the latest available version of node by running the following code in the command line:
  - `nvm ls-remote`
- Install the latest version of node by typing the following code in the command line replacing 12.14.1 with the latest version number:
  - `nvm install 12.14.1`
- You may also install earlier versions if desired by simply replacing 12.14.1 in the above code with the version you wish to install.
- To uninstall an instance of node simply run the following code in the command line replacing 12.14.1 with the version number you wish to uninstall:
  - `nvm uninstall 12.14.1`
- To switch between using different versions of node already installed just run the following code in the command line replacing 12.14.1 with the version number you wish to use:
  - `nvm use 12.14.1`
- It is possible to give nicknames to versions to make it easier to switch versions or recognize which version to switch to. To do this simply run the following code in the command line replacing node with your desired nickname (actually called an alias not a nickname):
  - `nvm alias node 12.14.1`
- To switch to different aliases use the same code from switching versions replacing 12.14.1 with the alias you wish to switch to. There are built in aliases.
  - `node` - switches to the latest version of node.
  - `--lts` - switches to the latest lts version.
  - `default` - any command line will automatically use this version until told otherwise (you have to set the default yourself with `nvm alias default 12.14.1`)
- To remove an alias from a version run the following code in the command line replacing node with the alias you wish to remove (this will mean you can only refer to the version with the actual version number):
  - `nvm unalias node`
- Check currently installed versions with `nvm ls`.
- Check version currently being used with `nvm current`

Credit to: https://www.sitepoint.com/an-introduction-to-jsx/