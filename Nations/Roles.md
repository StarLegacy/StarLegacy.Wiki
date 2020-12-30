# Roles
National Roles allow for the creation of a national government. They allow for custom permissions and tags to be assigned to various players.

## Creation
The simplest way to create a role is using the `/nrole manage` *or* `/srole manage` command. This brings up a gui creator which is easier to use in comparison to commands. It is recommended to join the **Creative Server** before interaction, as creation using this menu in survival will deplete Vanilla Experience.

![manage](https://i.imgur.com/H4RftY2.png)

> The *Book & Quill* is used to create a new role. The *Player Head* is used to assign roles to players in your nation. The *Papers* are roles you have created.

Create a role by clicking the Book & Quill. The first menu will prompt for the role's name. When finished, click the paper on the ***far right***. The second menu will prompt for the color of the role's name. Valid colors include the following:

> `DARK_RED, RED, GOLD, YELLOW, GREEN, DARK_GREEN, AQUA, DARK_AQUA, BLUE, DARK_BLUE, LIGHT_PURPLE, DARK_PURPLE, GRAY, DARK_GRAY, WHITE, BLACK`

The third menu will prompt for the weight of the role. Weight represents the authority of a role. A higher weight represents a higher authority. The nation leader has a weight of 1001 by default, and the maximum weight a role can possess is 1000.

The role should now be complete and look like this on the starting gui:

![beta](https://i.imgur.com/Zk4bwOs.png)

By clicking on the paper again, you may edit any of its features. The green book in the middle allows you to edit the permissions granted to whoever possesses the role. Each permission has it's own ability and usage.

### Nation Permissions
> `CLAIM_CREATE`: Allows for the claiming of territory owned by the nation.
>
> `CLAIM_DELETE`: Allows for the claiming on a territory owned by the nation to be removed.
>
> `MONEY_DEPOSIT`: Allows for the addition of money to the national balance.
>
> `MONEY_WITHDRAW`: Allows for the withdrawal of money from the national balance.
>
> `MANAGE_ROLES`: Allows for the creation, management, deletion, and granting of roles.
>
> `SETTLEMENT_INVITE`: Allows for the invitation of foreign settlements to the nation.
>
> `SETTLEMENT_KICK`: Allows for the removal of settlements from the nation.
>
> `MANAGE_RELATIONS`: Allows for the declaring of relations with foreign nations.

### Settlement Permissions
> `BUILD`: Allows for the placement and removal of blocks, as well as access to storage blocks.
>
> `MONEY_DEPOSIT`: Allows for the addition of money to the settlement balance.
>
> `MONEY_WITHDRAW`: Allows for the withdrawal of money from the settlement balance.
>
> `MANAGE_ROLES`: Allows for the creation, management, deletion, and granting of roles.
>
> `INVITE`: Allows for the invitation of other players to the settlement.
>
> `KICK`: Allows for the removal of players from the settlement.
>
> `MANAGE_ZONES`: Allows for the creation, management, and deletion of settlement zones and plots.

## Granting Roles
Granting a role is very simple. Return to the role management starting gui with `/nrole manage` *or* `/srole manage` and select the player head. This will list the members in your nation. Click on the player you want to grant a role and select the desired role from the list. Multiple roles may be assigned, but the highest weight will display its name. This will grant all permissions associated with the role and display the role's name in nation chat and ally chat. Settlement roles will only display in settlement chat.