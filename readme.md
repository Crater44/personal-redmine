# If you like to divide your gym workout into sprints, this is for you.

This project is a **Redmine image** with the data **linked** to the folders with volumes **into the filesystem**

This way you can **export** the entire folder to **make backups** of your personal sprints with **ease**.

**Redmine** uses **sqlite** by default for db storage, that makes the data **export** a **lightweight file** in
./volumes/sqlite/redmine.db

Also, if you **upload a file** like a **PDF** or an **image** you will have it **linked** to the **volume files**

## Setup

* Make sure the file **./volumes/sqlite/redmine.db** has permission **666 (-rw-rw-rw-)**

* Change the ports if you need it

* Add the desired plugins in the plugin folder that is linked to the redmine's plugin folder

* Just do **docker-compose up -d**