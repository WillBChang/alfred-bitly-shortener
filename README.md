# Alfred Bitly Shortener
Shorten a url with bit.ly in Alfred.

## Before using
1. Get bitly [GENERIC ACCESS TOKEN](https://bitly.com/a/sign_in?rd=%2Fa%2Foauth_apps) (recommend using email + password when signing up, becasue you will be required to input the password).
2. Download and install [Bit.ly.alfredworkflow](http://bit.ly/2Wml1a5).
3. Double click the script which contains `/bin/bash`.
4. Replace `PASTE_HERE` with your access token.
5. Save it.

## Usage
1. Input `bitly` in alfred, paste or type a url.
2. Select a url and press <kbd>alt</kbd>+<kbd>s</kbd>.

## Known Issue
- This workflow uses API V3 which will be deactivated on March 1, 2020. I'll update it soon. You can watch this repo for releases only.
- It gets `http` rather than `https`.
