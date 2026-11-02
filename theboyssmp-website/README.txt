# TheBoysSMP website

## Publish on GitHub Pages
1. Open your `theboyssmp` GitHub repository.
2. Open `index.html`.
3. Choose the pencil / Edit button.
4. Replace the existing contents with the new `index.html` from this package.
5. Commit the changes to the `main` branch.
6. Open Settings → Pages and make sure deployment is set to `main` and `/(root)`.
7. Visit: https://sonus734427-ops.github.io/theboyssmp/

## Customize
Open `index.html` and find the JavaScript section near the bottom:
- `SERVER_IP` and `SERVER_PORT`: server connection details.
- `PLAYERS`: replace sample names and points with real players.
- `NEWS`: update announcements.
- `SHOP_ITEMS`: replace sample listings with actual in-game player trade offers.

## Notes
- The live server status uses the public mcsrvstat.us Bedrock status API. It may occasionally be unavailable or unable to query an Aternos server.
- The leaderboard, news and shop are front-end sample data. They are not connected to a database or Minecraft server plugin. Edit the arrays in `index.html` to update them.
- The shop is an in-game trade listing showcase, not a payment system.
