# $modifyRole
Modifies a role.

## Usage
```
$modifyRole[roleID;roleName;colorHex;hoisted (yes/no);mentionable (yes/no)]
```
> 🧙‍♂️ You can use `!unchanged` as a argument to leave the setting as-is.

### Breakdown
- `roleID` - The ID of the role to modify.
- `roleName` - The new role name.
- `colorHex` - The new role color.
- `hoisted` - Whether the role should be displayed separately or not.
- `mentionable` - Whether the role should be mentionable by everyone or not.

## Example
```
$nomention
$argsCheck[>2;❌ Please provide the needed arguments! Usage: `!role-name (role) (newRoleName)`]
$onlyPerms[manageroles;❌ You are missing the manage_roles permission!]
$modifyRole[$findRole[$message[1]];$replaceText[$message;$message[1];;1];!unchanged;!unchanged;!unchanged]
$description[✅ Changed role name of <@&$findRole[$message[1]]>]
```

![example](https://user-images.githubusercontent.com/69215413/123530371-771a9980-d6c7-11eb-987d-c4ba3bb40bd1.png)
