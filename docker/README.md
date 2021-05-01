# Node/Debian/Buster

* The `/model` **node** application template is copied to `/app` if `/app/package.json` does not exist.
* The `/app` directory has the **node** application content.
* Therefore, if the `/app` directory has been modified, the contents should be copied back to `/model` to make them permanent.
* Launch the application once using `launch.bash` to prepare the project
* Browse the UI here: http://127.0.0.1:3000
* Browse the DB admin UI here: http://127.0.0.1:1234
