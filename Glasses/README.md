# Glasses

## Description

```
Everything is blurry, I think I need glasses!
```

## What I did

We are shown a website where the flag is being blurred and Control-Click is disabled.
First thing I do is look up the elements in the website with the button F12
I inspect the blurred out flag and see this HTML code

```
<span style="color: transparent;text-shadow: 0 0 5px rgba(0,0,0,0.09);text-decoration: line-through;">flag½₧8084e4530cf649814456f2a291eb81e9½―</span>
```

In which we can extract the flag from:

```
flag{8084e4530cf649814456f2a291eb81e9}
```
