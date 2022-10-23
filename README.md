# milestone-1
Install wsl using powershell by *wsl --install*
To change the distribution wsl --install -d <Distribution Name>
Update the WSL version by wsl --set-default-version 2 
Installing Docker Desktop using powershell command "Docker Desktop Installer.exe" install"
Enable the WSL2 engine in the settings and restart it
Install git in windows. Run it
Open Git bash and clone Cvat depository from github by-
" git clone https://github.com/opencv/cvat
cd cvat "
Run docker containers - docker-compose up -d
register a user - "winpty docker exec -it cvat_server bash -ic 'python3 ~/manage.py createsuperuser"
  Create User by Entering username email and password
  Install Google Chrome browser and go to localhost:8080
  Begin your annotation !!!!!
