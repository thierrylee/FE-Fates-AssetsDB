# Fire Emblem Fates Assets Database

This project is a dataset for Fire Emblem Fates (Birthright, Conquest & Revelation). It gathers data about characters (class set, max stats, growth rates, pair up stats, supports...), classes (weapons, max stats, growth rates...), skills... and more !

## Dataset structure

- Everything is formatted as INI files 
- There is 1 file per character/class/skill
- Each file name (without extension) is an ID
- Some data are references to theses IDs (i.e. : BaseClass, ClassSet, Supports...)
- Language specific data (display name, descriptions) is in "Translations" directory, their file name references an existing ID

Something strange I did but is subject to change is "Recruitment methods", which is (for now) the character's description, which is a language dependant data.

## Avatar & Children characters

- I didn't include any file about the Avatar, as it depends on chosen gender, boon, bane AND talent
- "Avatar" would be the ID for "Avatar (M)" and "AvatarF" would be the ID for "Avatar (F)"
- Children' modifiers stats were not filled as it heavily depends on their parents' stats
- Children' indicated growth rates are "base growth rates", the final growth rates depends on their second parent

## Data source & Special thanks

Data compiled mainly from [Serenes Forest](http://serenesforest.net) and [Fire Emblem Wikia](http://fireemblem.wikia.com)
Thanks a lot to the [Fire Emblem subreddit](https://www.reddit.com/r/fireemblem/) and globally to the entire Fire Emblem community !
