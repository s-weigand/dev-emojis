# Click to copy [website/PWA](https://s-weigand.github.io/dev-emoji-page/) for emoji I often used in commits, issues and PRs

I just got annoyed by copy-pasting emojis manually and each time dragging a markdown file
which was on my desktop in my editor to do so.

I like emojis in commit messages since it provides me with a quick visual diff what changed where...
but ofc. that is up to taste and might even cause issues on some systems depending on the font and render engine (we got 2021+ so yeah).

# Make it your own

To make it your own, you can simply:

- Fork this repo
- Replace `config.gh_handle` in `package.json` with your handle
- Change the [`iconList`](https://github.com/s-weigand/dev-emoji-page/blob/main/src/ts/icon-list.ts)
- Push it to your `main` branch and wait for the CI to deploy you gh-pages

## Credits

This use of emojis is inspired by

- [allcontributors](https://allcontributors.org/docs/en/emoji-key)
- [executablebooks](https://executablebooks.org/en/latest/contributing.html#commit-messages)
