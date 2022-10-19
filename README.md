# robotpy_romi
## RobotPy on the Romi chassis

### Commands to setup the Python environment for the first time
```dos
python3 -m venv .
```
```dos
.\scripts\activate.bat
```
```dos
pip3 install --upgrade robotpy[commands2, sim, romi, cscore]
```

### Running your program
**Make sure your python venv is activated, you can do so with the following command**
```dos
.\scirpts\activate.bat
```
To test run the following:
```dos
python3 robot.py test
```
To run with the dashboard run the following:
```dos
python3 robot.py sim --ws-client
```

### Files of note
- robot.py should be your supervisory program over all others
- robotcontainer.py sets up all the hardware and controllers for the Romi
