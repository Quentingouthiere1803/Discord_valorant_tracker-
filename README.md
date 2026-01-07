# Discord Valorant Tracker

## Overview
This project is a Discord bot that allows players to compare their
statistics with other members of their Discord server in a friendly
and privacy-respecting environment.

---

## Project Goals
- Provide fun and informative Valorant statistics within a Discord server.
- Ensure that each player gives explicit consent before their statistics
  can be viewed by other server members.

---

## Statistics & Features (Planned)
Most statistics are displayed through server-based rankings between
participating players.

Examples:
- Kills per match
- Best performance (highest number of kills) of the week
- Number of games played

Additional fun statistics may be added on a monthly basis
(e.g. "shortest time before first death").

---

## Consent and Privacy
By default, the bot does not collect or track any data.

Players must explicitly authorize the bot before their account is added
to the server watchlist and included in rankings. This authorization
can be revoked at any time using a Discord command.

To prevent abuse, it is forbidden to authorize an account that does not
belong to the user performing the authorization.

Each Discord server has its own isolated watchlist. No data is shared
between different servers.

Players can choose which of their statistics are tracked or ignored.

---

## User Flow (Planned)

1. A Discord server admin adds the bot to their server.
2. A player voluntarily registers using a command:
   /register riot_id#tag
3. The bot asks for explicit confirmation before enabling tracking.
4. Riot OAuth
5. Once confirmed, the player is added to the server watchlist.
6. The player can view their own statistics using commands such as:
   /my-stats
7. Server-wide rankings only include players who opted in.
8. The player can revoke access at any time using:
   /unregister

---

## Project Status
This project is currently under development.

---

## Cost
This project is open-source and free to use.
An optional tip system may be added in the future to help cover server
hosting costs.
