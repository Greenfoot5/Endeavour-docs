# Bounty Module

???+ tip "Enable/Disable module"

    To enable/disable the module, use the commands:
    `server enable bounty` or `server disable bounty`.
    This will enable or disable all commands listed below

??? summary "Full Command List"

    Command | Example| Explanation
    --- | --- | ---
    [`bounty`](#bounty) | `&&bounty` | Does nothing itself.
    [`bounty check [@user]`](#bounty-check) | `&&bounty check @Greenfoot5#2535` | Obtains a wanted poster with the user's current bounty value.
    [`bounty rank [#]`](#bounty-rank) | `&&bounty rank 5` | Obtains a wanted poster of the user at that position on the most wanted list.


## Member Commands

### Bounty

The base command for the bounty module. Does nothing in itself.

By default each message you send gains you between 20-30 bounty, multiplied by 1,000.
There is a cooldown of 60 seconds between bounty gains.

=== "Check"

    Displays the bounty of a user that you mentioned, or yourself.

    It displays the information in a wanted poster, along with your position in the most wanted leaderboard.

    ##### Examples:

    - `&&bounty check` - Gets your current bounty.
    - `&&bounty check @Greenfoot5#2535` - Gets the bounty of Greenfoot5#2535

=== "Rank"

    Displays the bounty of a user at the specified position, or #1.

    It displays the information in a wanted poster, along with your position in the most wanted leaderboard.

    ##### Examples:

    - `&&bounty rank` - Get's the bounty of the user at #1.
    - `&&bounty rank 5` - Get's the bounty of the user at #5.

## Settings

!!! error

    Settings have not been added for this module yet. However, they are coming soon.