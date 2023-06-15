---
description: If you want to know exactly what we store, you're in the right place!
---

# Our Database

Every data will be formated as following:

| Row name 1   | Row name 2   | Row name 3   |
| ------------ | ------------ | ------------ |
| Type value 1 | Type value 2 | Type value 3 |

### Cooldowns

<table><thead><tr><th width="173">Type</th><th width="100.33333333333331">ID</th><th width="112">Useleft</th><th>Time</th></tr></thead><tbody><tr><td>Command name</td><td>User ID</td><td>Number</td><td>Timestamp</td></tr></tbody></table>

### Counter

<table><thead><tr><th width="134">ID</th><th width="123">Channel</th><th width="93">Format</th><th width="81">Type</th><th>Last</th></tr></thead><tbody><tr><td>Guild ID</td><td>Channel ID</td><td>Format</td><td>Type</td><td>Last update</td></tr></tbody></table>

### Giveaways

<table><thead><tr><th width="129.33333333333331">Req_roles</th><th width="105">Bonus</th><th width="119">Channel</th><th width="104">Guild</th><th>Winners</th><th width="132">Users</th><th>Multiple_win</th><th width="125">End</th><th width="135">ID</th><th>Price</th><th>Host</th></tr></thead><tbody><tr><td>Role list</td><td>Role list</td><td>Channel ID</td><td>Guild ID</td><td>Number</td><td>User ID List</td><td>Boolean</td><td>Timestamp</td><td>Giveaway ID</td><td>Text</td><td>User ID</td></tr></tbody></table>

### Join to Create

<table><thead><tr><th width="157">ID</th><th width="128">Origin</th><th width="158">Nonephemeral</th><th>Enabled</th></tr></thead><tbody><tr><td>Guild ID</td><td>Category ID</td><td>Channel ID List</td><td>Boolean</td></tr></tbody></table>

### Logs

<table><thead><tr><th width="162.33333333333331">ID</th><th width="135">Channel</th><th>Type</th></tr></thead><tbody><tr><td>Guild ID</td><td>Channel ID</td><td>Log type</td></tr></tbody></table>

### Modals

<table><thead><tr><th width="143">ID</th><th width="98">Name</th><th width="201">Fields</th><th>Channel</th></tr></thead><tbody><tr><td>Guild ID</td><td>Text</td><td>Fields names &#x26; config</td><td>Channel ID</td></tr></tbody></table>

### Poll

<table><thead><tr><th width="113">ID</th><th width="118">Channel</th><th width="123">Message</th><th width="133">Votes</th><th width="121">End</th><th>Single</th><th width="107">Results</th><th>Req_roles</th></tr></thead><tbody><tr><td>Guild ID</td><td>Channel ID</td><td>Message ID</td><td>User ID List</td><td>Timestamp</td><td>Boolean</td><td>Boolean</td><td>Role ID List</td></tr></tbody></table>

### Welcome

<table><thead><tr><th width="122">ID</th><th width="115">img</th><th width="133">img_enabled</th><th>enabled</th><th width="113">message</th><th width="121">Channel</th><th>Roles</th></tr></thead><tbody><tr><td>Guild ID</td><td>IMG URL</td><td>Boolean</td><td>Boolean</td><td>Text</td><td>Channel ID</td><td>Role List</td></tr></tbody></table>
