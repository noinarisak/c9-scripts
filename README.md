# c9-scripts

Is collection of the customs bash scripts that will get pre-installed in every 
newly workspace in c9.

Reference instructions located here
https://community.c9.io/t/how-to-auto-configure-workspaces-on-creation/1323/2

## Install

> _NOTE:_ 
These instructions should work for the old Cloud9 because of the 
GitHub intergation. To perform the similar install in the new AWS Cloud9 (at 
the time of this writing, GitHub intergation was not option) you must manaully 
implement the setup discribed in section AWS Cloud9 instructions 
[here](https://docs.aws.amazon.com/cloud9/latest/user-guide/settings-init-script.html#settings-init-script-view).

Cloud9 workspaces setup using the c9-script repo itself. :metal:

* Fork the [c9-script](https://github.com/fnkr/c9-scripts) repo.
* In Cloud9 dashboard, assuming you have GitHub intergation enable, select the c9-script.
* Provide a name for the workspaces, (i.e.) `c9-scripts`.
* Select Ubuntu and then click the Create button.
* With in Cloud9 IDE, go to Cloud9 > Open Your Init Script.

![Example](https://discourse-cdn-sjc1.com/business5/uploads/trydiscourse4/original/1X/0ff8c2eed68df5436cd4fb5541f91c9f32e63ff8.png)

* An `init.js` file should open into a new tab.
* Copy and paste the repo [c9-script/init.js](https://github.com/fnkr/c9-scripts/blob/master/init.js) which should be with in current IDE workspace.
* Save the init.js and happy coding!


## Usage

c9-script in action. Example of the installing developer toolchain. The current 
collecton can be view [here](https://github.com/fnkr/c9-scripts/tree/master/utils)

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

## Origin/Reference
fknr responses on c9 [forum](https://community.c9.io/t/how-to-auto-configure-workspaces-on-creation/1323/2
).