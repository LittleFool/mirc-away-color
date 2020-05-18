# mIRC away-color

## Installation
In mIRC press ALT+R to open the editor for the remote.ini file. Copy and Paste the content of the remote.ini from this repository into the mIRC editor.
Change the `%away_color` value in the `on *:CONNECT:` section to your desired color. A value list can be found here: https://www.mirc.com/colors.html
You might need to merge the files e.g. if you already have a `on *:CONNECT:` section. When done press OK to save the changes. Then restart mIRC for the changes to take full effect.

**Warning:** The script will delete all color entries from the Address Book with the color of `%away_color` on startup. Make sure to choose a color you are not already using as a nick color.

**Info:** If you want to change the `%away_color` you have to remove all entries with the old `%away_color` from the Address Book by hand.
