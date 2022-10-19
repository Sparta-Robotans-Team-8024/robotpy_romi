# robotpy_romi
## RobotPy on the Romi chassis

### Steps for creating the python virtual environment
1. python3 -m venv .
2. .\scripts\activate.bat
3. pip3 install --upgrade pip
4. pip3 install --upgrade robotpy
5. pip3 install --upgrade robotpy[sim, commands2, cscore, romi]

### Running your program
1. python3 robot.py test
2. python3 robot.py sim --ws-core

### Files of note
- robot.py should be your supervisory program over all others
- robotcontainer.py sets up all the hardware and controllers for the Romi
