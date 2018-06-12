# Common Open Source Problems (and how to fix them)

Problem  | Fix
------------- | -------------
qsh: 001-0019 Error found searching for command yum.  | Please use an SSH terminal to access open source tools. 
yum: command not found | Add `/QOpenSys/pkgs/bin` to the beginning of your PATH environment variable. See [Setting your PATH](SETTING_PATH.md) for details
Up arrow doesn't recall previous commands | You will want to install `bash` and set it as your default shell. See [Setting bash as your shell](SETTING_BASH.md) for details