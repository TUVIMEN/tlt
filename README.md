# tlt
A shell script for searching torrents on limetorrents.

![example](example.gif)

## Requirements

 - [hgrep](https://github.com/TUVIMEN/hgrep)
 - xclip

## Installation
    install -m 755 tlt /usr/bin

## Usage

Just type 'tlt "your search"', choose what you want and the magnet link will be copied to your clipboard.

Search for the biggest linux isos

    tlt -s size 'linux iso'

Search for the most seeded linux isos on second page

    tlt -s se -p 2 'linux iso'

Search different domain for linux isos and change delimiter to space

    tlt -D ' ' -d 'http://otherdomain.to' 'linux iso'

Get some help

    tlt -h
