# Open in Browser

This is a workflow for [Alfred](https://www.alfredapp.com)
forked from [AndrewC-B/alfred-open-in-chrome](https://github.com/AndrewC-B/alfred-open-in-chrome)
and extended to include Firefox, Edge, Opera and Tor functionality.

## Update in v1.1.4

* Added supported for Tor browser
* Enabled push notification for most use case
* Opera, Brave, Firefox and Tor would automatically select the last Active Browser from the running programs
and copy the active tab for that browser

### Quick Commands

**opt** - Open in Tor Browser
**opb** - Open in Brave Browser
**opf** - Open in Firefox
**ops** - Open in Safari
**opc** - Open in Chrome
**ope** - Open in Edge
**opo** - Open in Opera

## Usage Notes

* If Safari is either not open, or has no windows open, the workflow will post a notification saying so.

* If you'd like it to also post notifications when URLs are successfully sent to Chrome, Firefox, Edge, Tor, Brave or Opera,
just open the workflow folder (right click the workflow in Alfred and click Show in Finder)
and edit the appropriate line in the respective file (they're clearly named and it's clearly marked within each file).
This notification feature is enabled by default for the most use cases/

* The reverse behaviour is also available (i.e.: sending URLs from Chrome/Firefox/Edge/Opera/Tor/Brave to Safari).
