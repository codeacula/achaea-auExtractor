# Achaea Extracting Plugin

## Summary

I wrote this plugin because I wanted an easy way to get minerals. So, here we are. This thing doesn't self-update, but I'll try to publish new releases as I make updates.

## Installation

I installed this using the Module Manager. There are no other dependencies

## How To Use

1. Install
1. Send `au map` to start mapping
1. Ever time you visit a new room, it will send MINERALS and attempt to extract. If the extraction works (there's some rooms like in Moghedu where you can't extract but can see minerals), it stores the room
1. Send `au map` to stop mapping
1. Now you can send `au go` to gather all mapped rooms, `au [mineral]` to only collect a specific mineral, or `au [area]` to only collect a specific area.
1. After the script extracts, it will return you to your starting location

If you accidentally map a room you don't want, you can use `au remove [roomid]` to remove it from the database.

If you think you've catastrophically ruined things, you can use `au reset` which will delete *all* the data, forcing you to start over.
