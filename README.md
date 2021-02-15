# Devtools H Key Bug Reproduction

Steps:

- Clone the repo
```
git clone https://github.com/llwor94/devtools-h-key.git
```

- Ensure your Chrome browser is on version 88.0.4324.150 
- Navigate to `chrome://extensions/` 
- Ensure you are in Developer Mode and select `Load unpacked`, select your local cloned repo
- Open DevTools, open tab named `Test`
- Attempt to type `h`

IF you are able to successfully type an `h` (as the bug is not consistent):
- Inspect the devtools window
- Right click the window and select `Reload Frame`
- Restart Chrome
- Repeat above steps until bug is present


