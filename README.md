# VeloPythonAPI

###Velo Python API Setup Instructions
1.	Unzip the zip file.
2.	Place the VeloAPI.jar file at an appropriate location.
3.	Include VeloAPI.jar file in the VeloAPI.py script.
  * `jpype.startJVM(jvmPath, "-Djava.class.path=C:/Users/raju332/Desktop/ACME/VeloAPI/JPype/VeloAPI.jar")`
4.	Place the config directory in current directory with python scripts.
5.	Import VeloAPI.py in your python scripts.
  * `import VeloAPI`
6.	Refer the TestAPI.py script to make calls to the Velo API methods.
