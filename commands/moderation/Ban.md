## Description

The **ban** command allows server admins to permanently remove a member from the server, blocking them from rejoining until unbanned.

## Syntax
!!! Text command
**\ban** <span class="orange">**MEMBER(S)**</span> <span class="orange">**PARAMETER(S)**</span>
!!!

!!! Slash command
**/Ban** `!user:` `?limit:` `?reason:` `?--silent:`

<span class="red">Note:</span> Any parameter prefixed with <span class="red">!</span> is required, and ones with <span class="red">?</span> Are optional
!!!

## **Aliases**

[!badge \ban] | [!badge \b]
---    | ---

## Parameters

Parameters are the options you can provide if you want extra input or a custom behaviour. They must come after the <span class="red">required paramaters</span>, The parameters available for this command are as follows:

Paramater | Info
-- | --
[!badge variant="success" text="!user"] | Specifies the user to ban.
[!badge variant="success" text="?limit"] | A
[!badge variant="success" text="?reason"] | Explains why the user is being banned. This reason is logged and optionally shown to the banned user.
[!badge variant="success" text="?--silent"] | If set, prevents notifications about the kick.

## Permissions

Permissions dictate what users or roles can use specific commands. They are essential to ensure the bot operates securely and aligns with your server’s hierarchy. Permissions must be configured after specifying the required roles for this command. The needed permissions for this command are as follows:

Bot | Author
-- | --
[!badge variant="success" text="BAN_MEMBERS"] | [!badge variant="success" text="BAN_MEMBERS"]