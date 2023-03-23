# TCam
TCam - it's a tool for get access to camera. 👀 


# Download&Install
1) Install <a href="https://termux.dev" target="_blank">**Termux**</a>  
2) **Turn this commands in Termux console:**
* `apt update`  
* `apt upgrade`  
* `pkg install git && pkg install python3`  
* `git clone https://github.com/Max412/TCam`  
* `cd tcam`  
* `pip install -r requirements.txt`  
* `python3 tcam.py`  


# Usage
The first time you launch, you will need to enter the <a href="https://account.shodan.io/login" target="_blank">Shodan API Key</a>.  
When restarting Termux, to start, you will need to enter the following commands:
* `cd tcam`  
* `python3 tcam.py`  

# Flags
* `--api` [NEW_API]  
  Changing the API key you entered when you first started, for example: `python3 hcam.py --api 7TeyFZ8oyLulHwYUOcSPzZ5w3cLYib65`

* `--ip` [IP]  
   Check the IP camera for vulnerability by entering the password, for example: `python3 hcam.py --ip 12.3.456.78`
   
* `--country` [COUNTRY IN Alpha-2 FORMAT] (Premium API Key required)  
   Specify the country to search for vulnerable cameras: `python3 hcam.py --country US`

# Screenshot
![capture](https://github.com/Max412/DoS-ru/blob/main/cam.png?raw=true)
