# Bauhaus93-Font

Just a simple repo to have Github host this font.

## Demo

 https://garrettmac.github.io/Bauhaus93-Font/


## What does it look like?

> ![Bauhaus93 Font Snapshot](./snapshot.png)

## Having Github host this font



### Add the Font Face to your project

Download this repo then

```bash
@font-face {
	font-family: 'Bauhaus93';
	src: url('../assets/fonts/Bauhaus93/Bauhaus93.eot');
	src: local('☺'), url('../assets/fonts/Bauhaus93/Bauhaus93.woff') format('woff'),
   url('../assets/fonts/Bauhaus93/Bauhaus93.ttf') format('truetype'),
   url('../assets/fonts/Bauhaus93/Bauhaus93.svg') format('svg');
	font-weight: normal;
	font-style: normal;
}
```

then
```bash
.app-font{
font-family: 'Bauhaus93';
}
```

Having issues having github hosting it?

Replace `cdn.rawgit.com` to `rawgit.com` or `raw.githubusercontent.com`.
For non-production environments, such as jsFiddle, use `rawgit.com`
For production environments use `cdn.rawgit.com`

If you're having issues on the hosting side checkout this [Stackoverflow Q&A](http://stackoverflow.com/a/18049842/4642530)

## Add it to your Mac

Just drag and drop these fonts into your **Font Book** App
