# Packman v0.1

As a test automation engineer, I want to spin up a fresh database quickly. What I don't want to do is copy-paste each and every update script and then execute them one by one in the MSSQL management tools GUI.

With **_Packman_** I can update multiple databases in seconds. No more copy-paste-executing procs. No more confusion with multiple MSSQL management tool windows. Just a quick update---the way it should be!

### Features

- *Run certain scripts first.* Need to execute your scripts in a specific order? **_Packman_** has you covered.

- *Replace `USE [database]` easily.* Does your script specify a database, but you want to execute it on a different one? No problem. Easily replace database names and usernames (and anything else!) without having to modify your sql files.

- *Prevent errors with GO groups.* **_Packman_** automagically inserts GO statements into your script to avoid errors, without saving any changes to your file.

- *Log it.* You can schedule a task to run **_Packman_** and log the results in a file, or you can sit and watch Packman's magic in the console.

- *Update multiple databases.* You can specify one or many database connection strings. **_Packman_** will connect to and update them all.



I use **_Packman_** alongside database snapshots for fast database modification and restoration.

