#Editing Speakers
This document contains instructions for editing the speaker list on the main website

##Step 1 - Login to cPanel
Navigate to `http://wrssnewcomers.com/cpanel` and login.
![login](Speaker_1.png)

##Step 2 - Open `File Manager`
Scroll down until the `Files` section appears, click on `File Manager`.
![File Manager](Speaker_2.png)

##Step 3 - `public_html`
In the left panel, select `public_html`
![public_html](Speaker_3.png)

##Step 4 - index.php
1. On the right, single click `index.php`
2. Click on `Code Editor` in the top bar.
![Code Editor](Speaker_4.png)
3. Select `Edit` when prompted
![Edit](Speaker_5.png)

##Step 5 - You will see the contents of the file
![contents of index.php](Speaker_6.png)

##Step 6 - Scroll down and find the section titled `Programs/special speakers at each meeting.` (around line 290)
![Programs/special speakers section](Speaker_7.png)

##Step 7 - Edit the list

**Formatting:**

```html
<li>YOUR_CONTENT</li>
```

##Step 8 - Save changes
1. Click on the `Save Changes` button in the top right corner
![Save Changes](Speaker_8.png)

2. You will see a `Success!` notification
![Success](Speaker_9.png)

3. Close the editor
![Close](Speaker_10.png)
