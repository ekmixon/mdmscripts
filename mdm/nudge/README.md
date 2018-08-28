# nudge
It does things. For now read the code

## Building this package
You will need to use [munki-pkg](https://github.com/munki/munki-pkg) to build this package

### Notes
Because of the way git works, nudge will not contain the `Logs` folder required for the postinstall to complete.

In order to create a properly working package, you will need to run the following command:
`munkipkg --sync /path/to/cloned_repo/mdm/nudge`

## Screenshots

### DEP
![Screenshot DEP](/mdm/nudge/images/ss_dep.png?raw=true)

### Manual
![Screenshot Manual](/mdm/nudge/images/ss_manual.png?raw=true)

### UAMDM
![Screenshot UAMDM](/mdm/nudge/images/ss_uamdm.png?raw=true)
