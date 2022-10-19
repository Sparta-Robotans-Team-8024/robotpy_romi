# RobotPy on the Romi chassis

## Commands to setup the Python environment for the first time
Creating the Python venv(virtual environment)
```dos
python3 -m venv .
```
Activating the venv
```dos
.\scripts\activate.bat
```
Installing dependencies in the venv
```dos
pip3 install --upgrade robotpy[commands2, sim, romi, cscore]
```

## Running your program
**Make sure your python venv is activated, you can do so with the following command**
```dos
.\scripts\activate.bat
```
To test run the following:
```dos
python3 robot.py test
```
To run with the dashboard run the following:
```dos
python3 robot.py sim --ws-client
```

## Files of note
- robot.py should be your supervisory program over all others
- robotcontainer.py sets up all the hardware and controllers for the Romi

**REF:**
- https://github.com/robotpy/examples/tree/main/commands-v2/romi
- https://www.chiefdelphi.com/t/robotpy-romi-example-available/391632