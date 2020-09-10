# InstaInsane v1.0
## Author: github.com/thelinuxchoice
## IG: instagram.com/thelinuxchoice
### Don't copy this code without giving me credit.
Instainsane is an Shell Script to perform multi-threaded brute force attack against Instagram, this script can bypass login limiting and it can test infinite number of passwords with a rate of about 1000 passwords/min with 100 attemps at once.

![insane](https://user-images.githubusercontent.com/34893261/38772658-97646698-4012-11e8-9b5e-65596e70a5ff.png)

### Features
- Multi-thread (100 attempts at once)
- Save/Resume sessions
- Anonymous attack through TOR
- Check valid usernames
- Default password list (best +39k 8 letters)
- Check and Install all dependencies

### Install requirements (First time usage):

```
git clone https://github.com/Quessts/instainsane.git
cd instainsane
chmod +x instainsane.sh
chmod +x install.sh
sudo ./install.sh
sudo ./instainsane.sh
```

### Usage (For any other time):
```
cd instainsane
sudo ./instainsane.sh
```



### How it works?

Script uses an Android ApkSignature to perform authentication in addition using TOR instances to avoid blocking. 
The script uses Instagram-py algorithm (Python), see the project at: https://github.com/antony-jr/instagram-py
Thanks to: @antony-jy https://github.com/antony-jr
