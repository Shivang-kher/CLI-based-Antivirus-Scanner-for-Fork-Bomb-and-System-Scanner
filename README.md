# CLI-based-Antivirus-Scanner-for-Fork-Bomb-and-System-Scanner

Tech stack:
  1. Python
  2. C
  3. Kali linux
  
Requirements:
  1. Kali linux(Virtual machine/system)
  2. python3 installed 
  3. gcc
  4. Create a processess.txt and procs.csv to keep a log of all the scans
  
Setup:
  1. Download the repo
  2. Open terminal
  3. Run `python3 main.py` to run system scanner
  3. Open new terminal window
  4. Run `gcc bomb.c` & `./a.out` to start the fork bomb
  
Result:
  System will warn the user about the memory being overloaded and all the logs will be saved in csv file
  
Screenshots:
![image](https://user-images.githubusercontent.com/69949038/229240840-0efe7a26-e17e-4535-b953-8630f44b81ab.png)


