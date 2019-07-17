# MockieMinimal.AdiumMessageStyle

I like Adium's Mockie message style, but I like it _more_ with a few things
hidden. Just tossing this up here so I don't have to keep copying my changes
around to new machines.

![sample](https://raw.githubusercontent.com/fixlr/mockieminimal.adiummessagestyle/master/sample.png)

## Install

```
cd ~/Library/Application\ Support/Message\ Styles/
git clone git://github.com/fixlr/mockieminimal.adiummessagestyle.git \
  MockieMinimal.AdiumMessageStyle
```


## Changes

Pretty much just this:

```
# /Contents/Resources/styles/basestyle.css
81,82d80
<
< .topleft, .protocol, .sender { display: none; }
```
