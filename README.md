# Apex 5 Icon Font Documentation

## What this is:
**READ THESE SCARY BOLD LETTERS: THIS IS NOT AN ORACLE SANCTIONED PROJECT. I HAVE NO AFFILIATION WITH ORACLE OR APEX.**
As I began working with APEX 5, I liked their icon font and wanted to suse it. Sadly, they seem to have no documentation for it at all. This is an attempt to construct some documentation for it.

## Naming Conventions:
Wherever the glyph is used in the stylesheet that I've found, I pick the most generic class name and name the glyph based off of that.

If I can't find anything, the glyph is named "UNUSED description" with whatever makes sense to me.

## File Setup:
Right now this is just my working Sketch file, so if you don't have Sketch I don't know what to tell you.

The icons are put in the order that they're dropped in the font's table. Each row has CSS namespacing so you can define your own classes as you need to.

## On \E054
This glyph has 5 icons shoved into it that clip outside of the glyph definition. It breaks stuff everywhere and is generally terrible. I don't plan on editing it to make it usable.

## On the general structure:
It seems like the icons all have thick and thin versions, but I can't figure out how they specify the thin versions of things. If you find anything, feel free to [tweet to me](https://twitter.com/glucasroe) or make a pull request.

## What you could do to help:
I hope to make an HTML version of this that's more usable than the Sketch file, so that would be pretty bomb. Maybe something similar to the [FontAwesome Cheatsheet](http://fontawesome.io/cheatsheet/).