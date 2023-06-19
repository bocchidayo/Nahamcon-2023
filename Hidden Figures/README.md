# Hidden Figures

## Description

```
Look at this fan page I made for the Hidden Figures movie and website! Not everything is what it seems!
```

## What I did

Opening the website, I view-source the website and notice that there's 4 very long codes in the HTML.
Upon inspection they are images in the form of Base64 code, in which I pop open CyberChef.
I use Decode From Base64 together with Extract Files and begin checking each long code one by one.

At the end, the one that gave me something was the code at line 609
```
data:image/png;base64,/9j/4AAQSkZJRgABAQEAlgCWAAD//gBWRmlsZSBzb3VyY2U6IGh0dHA6Ly9jcmdpcy5uZGMubmFzYS5nb3YvY3JnaXMtZWRpdC9pbmRleC5waHAvRmlsZTpH...
```
As CyberChef extracted the flag as a hidden "flag.png" file inside the line.
