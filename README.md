# Nusiki Exploit

Automation script to get likes on Nusiki

## Running the script
**You must have a webdriver and node/npm installed to use this script.**

```
$ git clone https://github.com/christophior/NusikiExploit.git
$ cd NusikiExploit
$ npm install
$ npm start
```
**To run multiple times use the following code (600 is for 10 minutes; change this for a different interval)**
```
$ while true; do node app.js; sleep 600; done
```

**How this exploit could have been prevented/made more difficult**
- Email verification before allowing authentication onto the site
- Email domain filtering to make sure disposable emails weren't used after enabling email verification
