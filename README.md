# Cxrve's Pro Settings Database

A small terminal tool to look up **Fortnite pro player settings** such as sensitivity, keybinds, video settings, and gear — and compare them with your own.

## Download

1. Go to the **latest release**.
2. Under **Assets**, click `Settings_Database.exe`.
3. Open it. That's it — nothing to install.

> **⚠️ Important:** Don't download **Source code (zip)**. That only contains the code, not the program.

Windows may show a warning the first time because the `.exe` isn't signed. Click **More info → Run anyway**.

## Commands

| Command | What it does |
|---|---|
| `/home` | Welcome screen |
| `/cxrve` | View Cxrve's settings |
| `/pro` | Search for a pro player by name |
| `/list` | Show every player in the list |
| `/random` | Pick a random pro with settings |
| `/compare` | Compare two players' settings |
| `/recent` | View recently searched players |
| `/exit` | Close the tool |

## Searching

Type `/pro`, then enter a player's name, for example:

```text
/pro Bugha
```

You can also search for players like `Kreo` or `Mongraal`.

Misspelled names will show close suggestions when available.

## Comparing

Type `/compare`, then enter two names separated by a comma:

```text
/compare Bugha, Mongraal
```

You can also use `cxrve` as a name to compare a pro player's settings against your own.

## The Player List

In `/list`:

- 🟢 **Green names** have sensitivity and keybinds available.
- ⚪ **Grey names** are listed but are missing keybinds or video settings.

Settings come from public sources such as **ProSettings**, **Specs.gg**, and older listings.

They show what each player uses now, which may differ from what they used in the past.

Anything that couldn't be found is shown as:

```text
not listed
```

## Updates

The tool checks for a new version when it starts.

If an update is available, it will say:

```text
Update available
```

Press **Enter** to download it. The tool will replace itself and restart.

Type anything and press **Enter** to skip the update.

## Discord

Join the server for **updates, requests, and help**:

[**Join the Cxrve Discord Server**](https://discord.gg/pzqPYbzmCU)

## Credits

Made by **Cxrve**.
