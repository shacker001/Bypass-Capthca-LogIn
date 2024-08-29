## Overview

* This script performs a brute force attack on a login page by attempting various combinations of usernames and passwords. It handles CAPTCHA challenges that appear during the login attempts.

### How It Works

#### Read Inputs:`` The script loads a list of usernames and passwords from usernames.txt and passwords.txt.``

#### Solve CAPTCHA:`` The script sends initial login attempts to trigger and solve CAPTCHA challenges.``

#### Brute Force Attempt:`` It iteratively tries each username and password combination while solving any CAPTCHAs encountered, aiming to find valid login credentials.``

#### Output:`` If a valid username and password combination is found, the script prints the credentials and exits.``