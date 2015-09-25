# README #

### How do I get set up? ###

Place the files into mod/data/field/tag and run notifications.

Due to limitations in the database activity you will need to run the installhacks script which copies an image and language string into the core mod_data code. You can do this by typing:

php mod/data/field/tag/cli/installhacks.php

at the command line.

One the plugin is installed if you go to MOODLESITEROOT/mod/data/field/tag/migrate/migrate.php you will be able to choose checkbox database fields that you wish to migrate over.