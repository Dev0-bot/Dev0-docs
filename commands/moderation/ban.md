# Ban

---

## **Description**
The `/ban` commandallows server admins to permanently remove a member from the server, blocking them from rejoining until unbanned.

---

## Syntax
!!! Text command syntax
**\ban** **MEMBER(S)** **PARAMETER(S)**
!!!

!!! Slash command syntax
**/Ban**`!user:` `?limit:` `?reason:` `?--silent:`

Note: Any parameter prefixed with ! is **required**, and ones with ? Are optional
!!!


## **Aliases**
[!badge \ban] | [!badge \b]
---    | ---

---

## **Usage**
The `/ban` command helps enforce server rules by banning disruptive users. This ensures a safe and friendly community.

###**Example**:
```
/ban @User123 Spamming inappropriate messages
```
This command will ban the user "@User123" with the reason: "Spamming inappropriate messages."

---

## **Parameters**
Paramater | Info
-- | --
[!badge variant="success" text="!user"] | Specifies the user to ban.
[!badge variant="success" text="?limit"] | A
[!badge variant="success" text="?reason"] | Explains why the user is being banned. This reason is logged and optionally shown to the banned user.
[!badge variant="success" text="?--silent"] | A

---

## **Permissions**
- **You need**: `BAN_MEMBERS`
- **Bot needs**: `BAN_MEMBERS` 

Make sure both you and the bot have the correct permissions to execute the command.

---

## **Possible Errors**

### **Missing Permissions**
- **Error Message**: "You do not have the required permissions to use this command."
- **Fix**: Ensure you have the `BAN_MEMBERS` permission.

### **Missing Parameters**
- **Error Message**: "Please specify a user to ban."
- **Fix**: Provide a valid user mention or ID.

### **Invalid User**
- **Error Message**: "The specified user cannot be banned."
- **Fix**: Check if the bot’s role hierarchy is above the user’s role.

---

