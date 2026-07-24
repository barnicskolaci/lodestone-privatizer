# Lodestone-privatizer

Tampermonkey script to automate making your FFXIV Lodestone character profiles private.

# Usage
- get tampermonkey addon for browser of choice
- make a new script, insert file contents
- log in to lodestone, click start (see pic), profit.
- make sure no character is selected or the 1st character is selected and start with current character (not next)
<img width="1105" height="219" alt="image" src="https://github.com/user-attachments/assets/0f9a95eb-a6b0-4b77-92d6-d47444fc8ba5" />

# Additional info

Works by going through each character in the lodestone character screen.
finds currently selected character and opens the next or 1st if none are selected (✓ icon).
if the character was never opened, the privacy settings page will open, in which case it sets it all to private, checks the box, saves and confirms.
if the character has previously been opened and settings will not come up, goes to settings first.
once done, goes back to character list and repeats.
stops when reached the end of the list.

Should work on any region.
