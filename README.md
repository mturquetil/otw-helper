# otw-helper
Helper for logging on OTW challenges

## Setup
```
ln -s <clone_path>/helper <dir_in_$PATH>/otw-helper
```

Obviously, you have to modify games/<your_game> file to add new passwords.

For Natas challenge, $BROWSER variable is used so you may want to set it.

## Usage
otw-helper _game_ _level_

**Example**
```
otw-helper bandit 0
```

## Issues

Problem may occur on natas challenges depending on your browser, in this case the password is set in your clipboard but you have to type the username.

If its your first time connecting to the wargame server, you have to autorize manually the server to be added to known hosts
