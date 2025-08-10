# ProductReuploader
Pass and Product reuploader for Roblox

# Simplest setup
1. create a codespace
2. move `cookie.txt` out of src folder
3. get cookie (skip if your arent NOOB)
  - press right click and click on inspect
  - a window on the right appears either click on `Application` or the `>>>` and then one `Application`
  - under Storage in that small window on the left click on Cookies and click on `https://www.roblox.com`,
  - click on the right side now on the `.ROBLOSECURITY` on the bottom right now a window (Cookie Value) should appear
  - double click or copy the content of Cookie Value
  - go to `cookie.txt` which you should have moved out of `src/cookie.txt` now and paste it there
  - like in step 3 said cut out the exact string via replace (ctrl + f)
  - save the file (if auto save just close it)
4. paste `.ROBLOSECURITY` into `cookie.txt` and trim `_|WARNING:-DO-NOT-SHARE-THIS.--Sharing-this-will-allow-someone-to-log-in-as-you-and-to-steal-your-ROBUX-and-items.|_`
5. run (options)
  - use python debugger and press play like button on the top right of screen in the `src/main.py`
  - use shortcut for first method
  - open a terminal and run `python src/main.py`
6. follow what the terminal says and your gucci  

<h3>How to use:</h3>
<ol>
<li>Install the zip file from releases, extract it and run the compiled exe</li>
  or
<li>Clone this repository, install requirements using pip and run main.py (Requires Python 3)</li>
</ol>

You have to paste your .ROBLOSECURITY token in the cookie.txt file for it to work

<img src="https://github.com/user-attachments/assets/99f44bd7-9270-4f90-80ef-e23c8d8ad304" width="418" height="244" alt="Product Reuploader Demo">

<h4>How to get your cookie:</h4>
<ol>
<li>Open <a href="https://www.roblox.com/home">Roblox</a> and press F12 for dev tools</li>
<li>Go to the application tab (Chrome) or Storage tab (Firefox)</li>
<li>Look for the 'Cookies' tab and click on it</li>
<li>Copy the contents of the .ROBLOXSECURITY field (Do not include ".ROBLOXSECURITY=")</li>
</ol>

<img src="https://github.com/user-attachments/assets/2c0dc8fc-7c09-4284-b6e8-f2e7d57df6ab" width="333" height="265" alt="Cookie Demo">
<br></br>
This code is for educational purposes only.
The author can not be held responsible for any consequences against your account(s) (Such as warns or bans).
