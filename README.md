# seat_hhit

A reservation script for seats in HHIT Library Room 104

## Notice 
For research and entertainment only

Technology is not guilty!

## Functions
1. Seat Reservation for http://seat.hhit.edu.cn
2. Multi-threading && Multi-user
3. Cross platform including Windows, macOS, Linux (Of course Linux servers are strongly recommended)
4. Intelligent time adjustment for Wednesday afternoon

## Prerequisites
1. Python3 installed
2. Module requests installed
```pip3 install requests```
3. Connection to http://seat.hhit.edu.cn
4. (unnecessay but recommended)Please buy a server if your local network is unstable.

## Installation && Usage
1. Download latest release zip to your computer and unzip.
2. Make sure Python3 is installed and configured. 
3. Find your seat code in json/seat.json and remember it.
4. Enter your userID, password and your seat code in json/activate.json. Don't change the structure of json file!!! Default password is the same as your userID but I suggest you change your password.
5. Run the script by ```nohup python3 seatKiller.py > log.txt &```(nohup and & are STRONGLY recommended)

## Salvation && Pressure test
I think my script is capable of no more than 10 users per day per computer, but I haven't finished the pressure test because I don't have that many IDs.
If you really need seat reservation (e.g. Postgraduate entrance exams), please raise an issue and I might provide some help. 
- [+] User number 1: Very Good.
- [+] User number 2: Very Good.
- [+] User number 3: Very Good.
- [ ] User number 4: Unknown.
