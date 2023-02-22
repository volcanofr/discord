# Discord permissions in guilds

|Name|Description|Identificator|Applicable|Remark|
|:--|:--|:--:|:--|--:|
|CREATE_INSTANT_INVITE|Creation of guild invitations ([discord.gg/](https://discord.gg/discord-townhall))|`1 << 0`|Channels & guild|∅|
|KICK_MEMBERS|Kick members outside of the guild|`1 << 1`|Members|Moderator|
|BAN_MEMBERS|Block guild members from guild|`1 << 2`|Members|Moderator|
|ADMINISTRATOR|All permissions in one: IS DANGEROUS|`1 << 3`|∅|Moderator|
|MANAGE_CHANNELS|Create, edit and delete channels and categories|`1 << 4`|Guild|Moderator|
|MANAGE_GUILD|Edit guild's infomrations|`1 << 5`|Guild|Moderator|
|Name|Description|`1 << 6`|Applicable|Remark|
|Name|Description|`1 << 7`|Applicable|Remark|
|Name|Description|`1 << 8`|Applicable|Remark|
|Name|Description|`1 << 9`|Applicable|Remark|
|Name|Description|`1 << 10`|Applicable|Remark|
|Name|Description|`1 << 11`|Applicable|Remark|
|Name|Description|`1 << 12`|Applicable|Remark|
|Name|Description|`1 << 13`|Applicable|Remark|
|Name|Description|`1 << 14`|Applicable|Remark|
|Name|Description|`1 << 15`|Applicable|Remark|
|Name|Description|`1 << 16`|Applicable|Remark|
|Name|Description|`1 << 17`|Applicable|Remark|
|Name|Description|`1 << 18`|Applicable|Remark|
|Name|Description|`1 << 19`|Applicable|Remark|
|Name|Description|`1 << 20`|Applicable|Remark|
|Name|Description|`1 << 21`|Applicable|Remark|
|Name|Description|`1 << 22`|Applicable|Remark|
|Name|Description|`1 << 23`|Applicable|Remark|
|Name|Description|`1 << 24`|Applicable|Remark|
|Name|Description|`1 << 25`|Applicable|Remark|
|Name|Description|`1 << 26`|Applicable|Remark|
|Name|Description|`1 << 27`|Applicable|Remark|
|Name|Description|`1 << 28`|Applicable|Remark|
|Name|Description|`1 << 29`|Applicable|Remark|
|Name|Description|`1 << 30`|Applicable|Remark|
|Name|Description|`1 << 31`|Applicable|Remark|
|Name|Description|`1 << 32`|Applicable|Remark|
|Name|Description|`1 << 33`|Applicable|Remark|
|Name|Description|`1 << 34`|Applicable|Remark|
|Name|Description|`1 << 35`|Applicable|Remark|
|Name|Description|`1 << 36`|Applicable|Remark|
|Name|Description|`1 << 37`|Applicable|Remark|
|Name|Description|`1 << 38`|Applicable|Remark|
|Name|Description|`1 << 39`|Applicable|Remark|
|Name|Description|`1 << 40`|Applicable|Remark|

### Type of applicables

**Channels:** Permission is used in all types of channels channels.
**Guild:** Is applicable on or inside the guild.
**Mmbers:** is applicable on server members

#### Type of channels:

- **Text:** Can be used in textual & forums channels.
- **Voice:** Can be used in voice channels.
- **Stage:** Can be used in stage channels.

### Types of remarks

**Moderator:** If guild's 2FA is enabled, the member need to activate 2FA to use these permissions.

> **source:** [Discord](https://discord.com/developers/docs/topics/permissions#permissions-bitwise-permission-flags)
