## Permissions

* `attachmentblocker.bypass` - Players with this permission will be exempt from restrictions **(only if the weapon or the attachment is in the player's inventory)**.

## Configuration

Both item IDs and item shortnames are supported.

To add items, add either the item ID or shortname between the square brackets, enclosed in quotes. Each item ID or shortname should be separated with a comma.

### Example

```json
{
  "Blocked Items": {
    "rifle.ak": [
        "567235583"
    ],
```

or

```json
{
  "Blocked Items": {
    "rifle.ak": [
        "	weapon.mod.small.scope"
    ],
```

**Multiple Items**

```json
{
  "Blocked Items": {
    "rifle.ak": [
        "567235583",
        "	weapon.mod.8x.scope"
    ],
```

Item IDs and shortname can be mixed.

### Default

```json
{
  "Blocked Items": {
    "rifle.ak": [],
    "rifle.bolt": [],
    "crossbow": [],
    "shotgun.double": [],
    "multiplegrenadelauncher": [],
    "rifle.l96": [],
    "rifle.lr300": [],
    "lmg.m249": [],
    "rifle.m39": [],
    "pistol.m92": [],
    "smg.mp5": [],
    "shotgun.waterpipe": [],
    "pistol.python": [],
    "pistol.revolver": [],
    "shotgun.pump": [],
    "pistol.semiauto": [],
    "rifle.semiauto": [],
    "smg.2": [],
    "shotgun.spas12": [],
    "smg.thompson": []
  }
}
```
