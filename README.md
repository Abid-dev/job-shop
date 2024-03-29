# Job Shop
This was an advancement of a project I started and worked on with pluralsight projects. Here I modify and jazz up the UI using the bulma framework and add additional functionality, interaction and features.

The original project repository is https://github.com/pluralsight-projects/python-build-cli-planner-app

## Create Virtual Environment

In a terminal run the following commands from the root folder of the forked project.

```
python -m venv venv
```

Once that completes, also run this command from the same folder.

Windows

```
\venv\Scripts\activate.bat
```

macOS & Linux

```
source venv/bin/activate
```

Now that you are working in the virtualenv, install the project dependencies with the following command.

```
pip install -r requirements.txt
```

## Verify Setup

In order to verify that everything is setup correctly, run the following command, which should show you the failing tests. This is good! We’ll be fixing this test once we jump into the build step.

```
pytest
```

Every time you want to check your work locally you can type that command, and it will report the status of every task in the project.

## Previewing Your Work

You can preview your work by running `flask run` in the root of your fork. Then visit `http://localhost:5000` in your browser.