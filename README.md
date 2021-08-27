# gw2-api-mount-icons
Guild Wars 2 API to retrieve additional icons and art for each mount

mounts IDs are consistent with official GW2 API https://api.guildwars2.com/v2/mounts/types

this file contains a JSON array of all available mounts image URLs in the following format:

```
{
    "id": "mount_id",
    "mount_up_icon": "https://wiki.guildwars2.com/...",
    "overhead_icon": "https://wiki.guildwars2.com/...",
    "banner": "https://wiki.guildwars2.com/...",
    "concept_art": "https://wiki.guildwars2.com/..."
}
```
