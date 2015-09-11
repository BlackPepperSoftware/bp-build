Black Pepper Build
==================

Build resources for [Black Pepper](http://www.blackpepper.co.uk/) projects.

Configuring Eclipse
-------------------

To configure Eclipse for Black Pepper projects:

1. Checkout the project: `git clone git@github.com:BlackPepperSoftware/bp-build.git.git`
1. Open Eclipse
1. Select 'File -> Import...'
1. Select 'General > Preferences'
1. Click 'Next >'
1. Click 'Browse...'
1. Select `bp-build/src/main/config/eclipse/bp-eclipse.epf`
1. Click 'Finish'
1. Select 'Window -> Preferences'
1. Expand 'Java > Code Style > Code Templates'
1. Import `bp-build/src/main/config/eclipse/bp-code-templates.xml`
1. Expand 'Java > Code Style > Formatter'
1. Import `bp-build/src/main/config/eclipse/bp-code-style.xml`
1. Expand 'Java > Editor > Templates'
1. Import `bp-build/src/main/config/eclipse/bp-templates.xml`
1. Expand 'Maven > Lifecycle Mappings'
1. Click 'Browse...'
1. Select `bp-build/src/main/config/eclipse/bp-lifecycle-mapping-metadata.xml`
1. Click 'OK'

Configuring IDEA
----------------

To configure IntelliJ IDEA for Black Pepper projects:

1. Checkout the project: `git clone git@github.com:BlackPepperSoftware/bp-build.git.git`
1. Build the settings jar: `cd bp-build/src/main/config && ./make-jar.sh`
1. Open IDEA
1. Select 'Import Settings..."
1. Select `bp-build/src/main/config/settings.jar`
1. Click 'OK'
1. Click 'OK'
1. Click 'OK' to restart IDEA

License
-------

* [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

[![Build Status](https://travis-ci.org/BlackPepperSoftware/bp-build.svg?branch=master)](https://travis-ci.org/BlackPepperSoftware/bp-build)
