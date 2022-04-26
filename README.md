# AdVenture Communist Free Capsule Tracker

This is a simple tool to assist players of the mobile game AdVenture Communist and related game AdVenture Ages. Free capsules are determined on a 241-length cycle, which includes a Legendary/Historic capsule at the 120th position. There is also a capsule cycle for Events.

## How to use

Primary Repository: <https://darrenrs.github.io/adcom-capsule-tracker/> as of 1 March 2022.

Click on capsules in the "Add Capsule" section to add them to your history, or the "minus" symbol to remove the last one.  The "Next Capsule" section will automatically update with chances for the next capsule's type, and the "Cycle" section will visually highlight each possibility.  Eventually, you should be able to figure out exactly where you are and reliably predict the future.

You can click a capsule in the "Cycle" section" to set it as your starting capsule.  If you already have added history, it will be placed before your first capsule.  You can also use wildcards instead of capsules; the first one (?) matches any single capsule and can be used if you know exactly how many capsules you've forgotten to record, and the second one (?≤5) will match 1-5 capsules, in case you've forgotten to record for a day and cannot remember exactly how many you opened.  If additional parameters are added to the url (e.g., ?mode=event&input=PA&start=1) they will be used to override the current save data, and such export/import URL's can be accessed by pressing the "export" button next to "minus."

## Thanks

The current curator of this website is Darren Skidmore (Enigma). However, infinitesimal credit must be given to Zephyron, the original creator of the Mission/Capsule Tracker and FAQ documents, from 2019 to 2022. I cannot thank him enough for his continued support.

The cycle data and the images are taken from the [Fandom Wiki](https://adventurecommunist.fandom.com/wiki/Free_capsules).  Some code and inspiration taken from [Scripter17's Capsule Finder](https://github.com/scripter17/adcomm-capsule-finder/).

## Contributing

I welcome any feedback, bug reports, or pull requests.

If you have any questions, comments, or suggestions, please visit the #engineering channel in the [unofficial AdCom Discord](https://discord.gg/VPa4WTM). We are always happy to help.

## License

This tool may be modified or redistributed with credit given to the current owner (Enigma) or original owner (Zephyron), given that it ascribes to the Hyper Hippo Fan Content Policy and all legal stipulations.

This material is not official and is not endorsed by Hyper Hippo. For more information, see Hyper Hippo’s Fan Content Policy: (https://hyperhippo.com/fan-content-policy/)

Last updated: 25 April 2022.