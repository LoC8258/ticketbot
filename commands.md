# **List of Commands for the Divus Bot**

## General Commands
| **Command** | **Usage** | **Aliases** | **Admin Only?** | **Description**                                                       |
|-------------|-----------|-------------|-----------------|-----------------------------------------------------------------------|
| help        | help      | -           | false           | Replies with help                                                     |
| ping        | ping      | -           | false           | Replies with the delay between the bot, host, and Discord API         |
| uptime      | uptime    | -           | false           | Replies with the bot's current uptime (how long it's been online for) |

## Ticket Commands
| **Command** | **Usage**                     | **Aliases**  | **Delay?** | **Admin Only?** | **Description**                                   |
|-------------|-------------------------------|--------------|------------|-----------------|---------------------------------------------------|
| setup       | setup                         | ticketsetup  | -          | true            | Set the channel tickets can be opened from        |
| close       | close                         | closerequest | 10min      | true/false      | Close the current ticket channel                  |
| add         | add <user/role resolvable>    | -            | -          | true            | Give a user/role access to the ticket channel     |
| remove      | remove <user/role resolvable> | -            | -          | true            | Remove a user/role's access to the ticket channel |
| rename      | rename <new name>             | -            | 10min      | true            | Give the current ticket channel a new name        |

## Reaction Roles Commands
coming soon

## Moderation Commands
coming soon
