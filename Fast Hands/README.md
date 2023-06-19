# Online Chatroom

## Description

```
You can capture the flag, but you gotta be fast!
```

## What I did

Upon entering the website, we are shown a button "Capture The Flag".
If we click on it, a popup window appears and closes immediatedly.
Presing the button of F12, I pinpoint the source code in the HTML that says what URL it opens in another window.
```
"window.open("./capture_the_flag.html"....);"
```
So I open that URL and now that the window doesn't closes we can look for the flag.
Inspecting the view-source HTML code and pressing CTRL-F to look for "flag", we find it hidden in the HTML code at the bottom.

```
flag{80176cdf1547a9be54862df3568966b8}
```
