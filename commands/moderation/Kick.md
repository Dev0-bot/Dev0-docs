## Description

The **kick** command allows server admins to temporarily remove a member from the server. The kicked member can rejoin using a new invite unless further restrictions are applied.

## Syntax
!!! Text command
**\kick** <span class="orange">**MEMBER(S)**</span> <span class="orange">**PARAMETER(S)**</span>
!!!

!!! Slash command
**/Kick** `!user:` `?reason:` `?--silent:`

<span class="red">Note:</span> Any parameter prefixed with <span class="red">!</span> is required, and ones with <span class="red">?</span> are optional.
!!!

## **Aliases**

[!badge \kick] | [!badge \k]
---    | ---

## Parameters

Parameters are the options you can provide if you want extra input or a custom behaviour. They must come after the <span class="red">required paramaters</span>, The parameters available for this command are as follows:

Paramater | Info
-- | --
[!badge variant="success" text="!user"] | Specifies the user to kick.
[!badge variant="success" text="?reason"] | Explains why the user is being kicked. This reason is logged and optionally shown to the kicked user.
[!badge variant="success" text="?--silent"] | If set, prevents notifications about the kick.

## Permissions

Permissions dictate what users or roles can use specific commands. They are essential to ensure the bot operates securely and aligns with your server’s hierarchy. Permissions must be configured after specifying the required roles for this command. The needed permissions for this command are as follows:

Bot | Author
-- | --
[!badge variant="success" text="KICK_MEMBERS"] | [!badge variant="success" text="KICK_MEMBERS"]

