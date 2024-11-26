# /ban Command Documentation

## Description
The `/ban` command allows server administrators to permanently ban a member from the server, preventing them from rejoining until unbanned.

---

## Aliases
- `/ban`
- `/block`

---

## Use Case
The `/ban` command is used to enforce server rules by removing disruptive members from the server. This ensures a safe and friendly environment for all members.

### Example:
```
/ban @User123 Spamming inappropriate messages
```
This command will ban the user "@User123" with the reason "Spamming inappropriate messages."

---

## Parameters

### `@user`
- **Type**: Mention or User ID
- **Description**: Specifies the user to be banned.
- **Required**: Yes

### `reason`
- **Type**: String
- **Description**: The reason for banning the user. This will be logged and can be provided to the banned user if necessary.
- **Required**: No

### `days`
- **Type**: Integer (0-7)
- **Description**: Optionally deletes the banned user's messages from the past `n` days (0 for none, 7 for all messages from the past 7 days).
- **Required**: No
- **Default**: 0

---

## Permissions
- **Required Permission**: `BAN_MEMBERS`
- **Bot Required Permission**: `BAN_MEMBERS`

Ensure that both the user executing the command and the bot have the appropriate permissions.

---

## Notes
- Banned users will not be able to rejoin the server until unbanned using the `/unban` command.
- The reason provided (if any) will be logged and visible in the audit log.

---

## Errors

### Missing Permissions
- **Message**: "You do not have the required permissions to use this command."
- **Solution**: Ensure the user has the `BAN_MEMBERS` permission.

### Missing Parameters
- **Message**: "Please specify a user to ban."
- **Solution**: Provide a valid user mention or ID.

### Invalid User
- **Message**: "The specified user cannot be banned."
- **Solution**: Ensure the bot has a higher role than the user being banned.

---

## Additional Information
- For bulk banning, consider scripting or contacting the server administrator for assistance.
- If you accidentally ban a user, use `/unban @user` to revoke the ban.

