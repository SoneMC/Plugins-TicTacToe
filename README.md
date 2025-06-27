# TicTacToe
> Playing TicTacToe on paper in school when youre bored? Now you can be bored in Minecraft

## Features
- GUI
- Leaderboard
- 3x3
  
## Commands and Permissions

| Command              | Description                | Permission             |
|----------------------|----------------------------|------------------------|
| `/ttt (player)`        | Base plugin command         | `tictactoe.play`       |
| `/ttt accept/deny`        | Accepts/Denies challenge         | `-`       |
| `/tttleaderboard` | Show all players stats    | `tictactoe.leaderboard`    |
| `/tttreload` | Reload the plugin config    | `tictactoe.admin`    |
| `/ttthelp` | Displays all commands    | `-`    |


## Configuration - config.yml
```yaml
# TicTacToe Plugin Configuration
# Use & for color codes (e.g., &a for green, &c for red)

# Plugin prefix - appears before all messages
prefix: "&aTicTacToe&r "

# All plugin messages - fully customizable and translatable
messages:
  # Permission messages
  no-permission: "&cYou don't have permission to use this command!"
  players-only: "&cThis command can only be used by players!"

  # Help messages
  help-header: "&6=== TicTacToe Commands ==="
  help-challenge: "&e/ttt <player> - Challenge a player"
  help-accept: "&e/ttt accept - Accept a challenge"
  help-deny: "&e/ttt deny - Deny a challenge"
  help-leaderboard: "&e/tttleaderboard - View the leaderboard"
  help-reload: "&e/tttreload - Reload configuration"

  # Challenge messages
  player-not-found: "&cPlayer not found!"
  cannot-challenge-self: "&cYou cannot challenge yourself!"
  already-in-game: "&cYou are already in a game!"
  target-in-game: "&cThat player is already in a game!"
  target-has-challenge: "&cThat player already has a pending challenge!"
  challenge-sent: "&aChallenge sent to {player}!"
  challenge-received: "&e{player} has challenged you to TicTacToe!"
  challenge-instructions: "&eType '/ttt accept' to accept or '/ttt deny' to deny."

  # Accept/Deny messages
  no-pending-challenge: "&cYou don't have any pending challenges!"
  challenger-offline: "&cThe challenger is no longer online!"
  challenge-accepted-challenger: "&a{player} accepted your challenge!"
  challenge-accepted-target: "&aChallenge accepted! Starting game..."
  challenge-denied-target: "&eChallenge denied."
  challenge-denied-challenger: "&e{player} denied your challenge."

  # Game messages
  game-started: "&aTicTacToe game started!"
  game-players: "&e{player1} (X) vs {player2} (O)"
  player-turn: "&6{player}'s turn!"
  not-your-turn: "&cIt's not your turn!"
  spot-taken: "&cThat spot is already taken!"
  game-won: "&aGame Over! {winner} wins!"
  game-draw: "&eGame Over! It's a draw!"
  cannot-close-game: "&eYou cannot close the game! The game is still in progress."

  # GUI messages
  gui-title: "&2TicTacToe - {player1} vs {player2}"
  gui-x-piece: "&9X"
  gui-o-piece: "&cO"
  gui-empty-piece: "&7Empty"
  gui-click-to-place: "Click to place"

  # Leaderboard messages
  leaderboard-header: "&6=== TicTacToe Leaderboard ==="
  leaderboard-empty: "&eNo games played yet!"
  leaderboard-entry: "&e{rank}. {player} &a{wins}W &c{losses}L &7({ratio})"
  leaderboard-player-stats: "&7({rank}) &e{player} &a{wins}W &c{losses}L &7({ratio})"

  # Admin messages
  config-reloaded: "&aConfiguration reloaded successfully!"
```

## Configuration - leaderboard.yml
```yaml
# TicTacToe Leaderboard Data
# This file stores player statistics
# DO NOT EDIT MANUALLY - Data is managed by the plugin

players: {}
```

## Images
![image1](https://github.com/SoneMC/images/raw/main/tictactoe_images/image1.png)
![image2](https://github.com/SoneMC/images/raw/main/tictactoe_images/image2.png)

---

## Versions:

- Built for: **1.20.2**
- Tested versions: **1.20.2**
- Should work on: **1.20.2+**

> Note: Versions that "Should work on: ..." are **NOT** tested and there **may** be some problems with plugin(s).

---

## Useful Links

- **Discord**: [Invite](https://sonemcpl.pages.dev/invite)
- **GitHub**: [Look](https://github.com/SoneMC)
- **Website**: [Look](https://sonemcpl.pages.dev)
- **License**: [MIT](https://github.com/SoneMC/SoneMC/raw/main/LICENSE)

---
