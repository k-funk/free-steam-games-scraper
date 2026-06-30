Check https://feed.eikowagenknecht.com/lootscraper_steam_game.xml using curl, for new free games

1. Identify any new "Free to Keep" games added since the last check by comparing against free_games_log.md in the repository root.
2. For each new game, extract: title, release date, Steam store page link, and brief description if available.
3. Format each game as a markdown list item with these fields.
4. Append the new games to free_games_log.md in a neatly formatted markdown list, grouped by date if helpful.
5. Commit and push the updated file on the `main` branch

If there are no new games, do nothing.
