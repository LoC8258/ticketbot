# **List of Commands for the Divus Bot**

## General Commands
| **Command** | **Usage** | **Admin Only?** | **Description**                                                       |
|-------------|-----------|-----------------|-----------------------------------------------------------------------|
| help        | help      | false           | Replies with help                                                     |
| ping        | ping      | false           | Replies with the delay between the bot, host, and Discord API         |
| uptime      | uptime    | false           | Replies with the bot's current uptime (how long it's been online for) |

## Ticket Commands
| **Command** | **Usage**                     | **Delay?** | **Admin Only?** | **Description**                                   |
|-------------|-------------------------------|------------|-----------------|---------------------------------------------------|
| open        | open                          | -          | false           | Open a new ticket                                 |
| setup       | setup                         | -          | true            | Set the channel tickets can be opened from        |
| close       | close                         | 10min      | true/false      | Close the current ticket channel                  |
| add         | add <user/role resolvable>    | -          | true            | Give a user/role access to the ticket channel     |
| remove      | remove <user/role resolvable> | -          | true            | Remove a user/role's access to the ticket channel |
| rename      | rename <new name>             | 10min      | true            | Give the current ticket channel a new name        |
| reopen      | reopen                        | -          | true            | Re-open a closed ticket                           |

## Moderation Commands
| **Command** | **Usage**                              | **Delay?** | **Admin Only?** | **Description**              |
|-------------|----------------------------------------|------------|-----------------|------------------------------|
| ban         | ban <user> <delete messages?> [reason] | -          | true            | Bans a user from the server  |
| kick        | kick <user> [reason]                   | -          | true            | Kicks a user from the server |
| addrole     | addrole <user> <role> [reason]         | -          | true            | Add a role to a user         |
| derole      | derole <user> <role> [reason]          | -          | true            | Remove a role from a user    |
| purgeroles  | purgeroles <user> [reason]             | -          | true            | Remove all roles from a user |
  
## Reaction Roles Commands
coming soon
