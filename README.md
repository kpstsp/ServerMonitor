# ServerMonitor [![Build Status](https://travis-ci.org/ChristianLutzCL/ServerMonitor.svg?branch=master)](https://travis-ci.org/ChristianLutzCL/ServerMonitor)

[ServerMonitor](https://monitor.inspiredprogrammer.com) is a web application for monitoring the status of web pages based on their response. It also gives you additional information about the website like IP adress, ping and the location of the web server.

<p align="center">
  <img alt="ServerMonitor" src="https://i.imgur.com/abCnQsI.png" height="350">
</p>


## What's the intention of this repository?
Mostly, the goal is to learn (more or less) everything about web development.
Starting from getting an idea what to build, over planning what to do next up to coding the actual application.
Also getting into working with others on such a project is something, I want to accomplish with this project.



## Can I already contribute?
Simple answer - Yes!
Unfortunately, there are currently no contribution guidelines for this project and therefore there is no "correct way" to contribute.
If you have an suggestion for something that could be improved, simply do a PR (Pull Request).

I'm happy about anyone who wants to help. 💪



## How to setup?
#### Step 1: Clone the repository
```bash
git clone https://github.com/ChristianLutzCL/ServerMonitor.git
cd ServerMonitor
```

#### Step 2: Create a VirtualEnvironment with the name 'venv'
Note: Naming your VirtualEnvironment this way helps, if you use VSCode.
```bash
python -m venv venv
```

#### Step 3: Activate your VirtualEnvironment
 -> Windows Powershell
```bash
venv/Scripts/activate
```

#### Step 4: Install the requirements
```bash
(venv) pip install -r requirements.txt
``` 


#### Step 5: Generate new database
```bash
(venv) python create_database.py
``` 


#### Step 6: Run the application
```bash
(venv) python run.py
``` 

*(venv) -> VirtualEnvironment is activated


##### Note: 
To get the app running, open config.py and create a EnvironmentVariable for Flask and the IPSTACK-API on your local machine.
ServerMonitor uses the IPSTACK-API for certain operations. Please visit https://ipstack.com and create your own API-Key.


# License

GNU General Public License (GPL v3.0) - [Christian Lutz](https://github.com/christianlutzcl/). Please have a look at the [LICENSE](LICENSE) for more details.