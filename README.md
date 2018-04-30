# How to use this repo

Reference instructions located here
https://community.c9.io/t/how-to-auto-configure-workspaces-on-creation/1323/2

## Initial C9 workspaces setup using the c9-script itself.

~_NOTE:_ These instructions should work for both old Cloud9 because the GitHub intergation. To perform the similar functionality for the new AWS Cloud9 you must
manaully implement the setup discribed in section AWS Cloud9 instructions.~

* Clone [c9-script](https://github.com/fnkr/c9-scripts)
* In Cloud9 dashboard, assuming you have GitHub intergation enable, select the c9-script.
* Provide name for the workspaces, (i.e.) `c9-scripts`.
* Select Ubuntu and then click the Create button.
* With in Cloud9 IDE, go to Cloud9 > Open Your Init Script.
* An `init.js` file should open into a new tab.
* Copy and paste the repo [c9-script/init.js](https://github.com/fnkr/c9-scripts/blob/master/init.js) which should be with in current IDE workspace.
* Save the init.js and happy coding!


## c9-script in action. Example of the installing developer toolchain.

* Open another the IDE workspace.
* Open terminal tab.
* Type or copy the following

```
$ install-git-extras
```

or 

Install MongoDB
```
$ install-mongodb
```

Manage MongoDB services
```
$ mongodb-start
$ mongodb-cli
```