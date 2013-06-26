# Sublime-ink

## Sublimet Text 2 snippets for [SAPO Ink v2](http://ink.sapo.pt) UI framework.

This package contains Sublime Text 2 snippets to make the creation of layouts using SAPOs Ink UI framework simple, easy and fast.

## Instalation

###Using the [Sublime Package Control](http://wbond.net/sublime_packages/package_control)

- Open up your command pallete *ctrl+shift+p* and type in: `Package Control: add Repository`
- paste the URL to this github repo in the next box (https://github.com/pedrocorreia/sublime-ink)
- Re-Open your command pallete and type: `Package Control: Install Package` and search for `Ink Helper`
- ????
- Profit!

###Manual installation
- [Download](https://github.com/pedrocorreia/sublime-ink/archive/develop.zip) the full repo.
- unpack it to your sublime text 2 `/Packages` folder
- ???
- Profit!

## The Ink Grid
Ink provides a HTML/CSS layout grid framework that allows you to build flexible pages that can be used with several screen sizes. 1

### Grid elements
* Grid container element - `igrid + tab`
* Grid column element - `icol + tab`
* Grid column group element - `icolgrp + tab`

#### Even space divisions
* 1 grid column - `i1col + tab`
* 2 even grid columns - `i2cols + tab`
* 3 even grid columns - `i3cols + tab`
* 4 even grid columns - `i4cols + tab`
* 5 even grid columns - `i5cols + tab`

#### Uneven space divisions
* 20% / 80% grid columns - `i2080 + tab`
* 25% / 75% grid columns - `i2575 + tab`
* 30% / 70% grid columns - `i3070 + tab`
* 33% / 66% grid columns - `i3366 + tab`
* 40% / 60% grid columns - `i4060 + tab`
* 50% / 50% grid columns - `i5050 + tab`
* 60% / 40% grid columns - `i6040 + tab`
* 66% / 33% grid columns - `i6633 + tab`
* 70% / 30% grid columns - `i7030 + tab`
* 75% / 25% grid columns - `i7525 + tab`
* 80% / 20% grid columns - `i8020 + tab`

## Navigation elements
Ink provides common navigation elements in a easy to implement and customize way.

#### Navigation
* Horizontal menu bar - `ihmenu + tab`
* Vertical menu bar - `ihmenu + tab`
* Pill buttons - `ipills + tab`
* Tabs - `itabs + tab`

1: Most grid snippets provide tab stops to complete the snippet like, how to behave with smaller screens.

---

#### Usage
You can use the Sublime Text 2 command palette and type `ink` to get a complete list of available snippets, or start memorizing and using the tab triggers listed in the command palette and here in front of each snippets description.