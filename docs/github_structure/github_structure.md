# GitHub repository structure

If you are not a regular user of GitHub, it is possible that the structure of data and directories in this repository is confusing. For this reason, we will explain that it contains each folder of the project and its most essential files.

The GitHub repository of the mooda project is structured as follows:

```bash
    mooda-gui
    ├─ docs
    └─ mooda_gui
        ├─ icon
        └─ widgets
```

Most of the files that are in the root contain specific code for the configuration of the GitHub directory. If you do not want to clone the project or use a git client, they are not necessary files for you. However, we describe them below:

* [.gitignore](https://github.com/rbardaji/mooda-gui/blob/master/.gitignore): In the process to sync your local git directory with the GitHub repository, files are usually built artifacts, and machine-generated data should otherwise not be uploaded. In this file, you can find the code to ignore this type of files.
* [LICENSE](https://github.com/rbardaji/mooda-gui/blob/master/LICENSE): Public repositories on GitHub are often used to share open source software. We use an MIT License.
* [MANIFEST.in](https://github.com/rbardaji/mooda-gui/blob/master/MANIFEST.in): It is used to collect all the files that will go into the final installer.
* [README.md](https://github.com/rbardaji/mooda-gui/blob/master/README.md): Contains the text that you see on the repository [home page](https://github.com/rbardaji/mooda-gui).
* [requirements-mooda_gui.txt](requirements-mooda_gui.txt): List of required python libraries to execute mooda-gui.
* [setup.cfg](https://github.com/rbardaji/mooda-gui/blob/master/setup.cfg): It contains package metadata.
* [setup.py](https://github.com/rbardaji/mooda-gui/blob/master/setup.py): It is the python code to install the package into a python environment.

The directories contain the following information:

* [docs](https://github.com/rbardaji/mooda-gui/tree/master/docs): It contains the mooda documentation.
* [mooda_gui](https://github.com/rbardaji/mooda-gui/tree/master/mooda_gui): **It contains the mooda_gui python package.**
* [icon](https://github.com/rbardaji/mooda-gui/tree/master/mooda_gui/icon): It contains the icons used in the GUI.
* [widgets](https://github.com/rbardaji/mooda-gui/tree/master/mooda_gui/icon): Here you have the modules that create the pyqt5 widgets of the GUI.

Return to the [Docs Index](../index_docs.md).