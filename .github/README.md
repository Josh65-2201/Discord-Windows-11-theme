![image](https://github.com/Josh65-2201/Discord-Windows-11-theme/blob/main/.github/preview.webp?raw=true)

## Download
Latest version: 2024.10.07.0

<details>
	<summary>Better Discord</summary>
	Open https://raw.githubusercontent.com/Josh65-2201/Discord-Windows-11-theme/main/Discord_Windows_11.theme.css > Right click > Save as > Go to BetterDiscord themes folder (%AppData%\BetterDiscord\themes) > Save
</details>

<details>
	<summary>Vencord</summary>
	<b>Offline - Manual update</b>
	Open https://raw.githubusercontent.com/Josh65-2201/Discord-Windows-11-theme/main/Discord_Windows_11.theme.css > Right click > Save as > Go to Vencord themes folder (%AppData%\Vencord\themes) > Save
	<br></br>
	<b>Online - Auto update</b>
	Copy URL `https://raw.githubusercontent.com/Josh65-2201/Discord-Windows-11-theme/main/Discord_Windows_11.theme.css` > Open Discord settings > Click `Themes` > Click `Online themes` > Paste in theme links.
</details>

<br></br>

## Functionality changes
Some controls have moved to conform with Windows 11 styles.


### Moved settings
- Toast/Notifications now have an global toggle in the themes settings
- Mute and deafen settings are now shown only on the voice connected panel
- Stickers and GIFs are now all in the emote menu
- Search bars are on the title bar
- User profile is now in the title bar next to window controls


### Other
- User/Members list will now auto hide at smallest window size. (Toggle doesn't do anything visibly at min size but will save state upon resize)
- Due to layering issues the Window drag area is small bar at top of the window

<br></br>

## Development
### Guidelines
- Any editor will work, Visual Studios Code is recommended.
- Indents use tabs at 4 spaces.
- New sections follow the line gaps
```
Main section 1 (E.G. Servers bar, Messages content)
	Sub section 1 (E.G. Server icon, Message)
		Part 1 (Position, Background color)
		Part 2 (Position, Background color)

	Sub section 2 (E.G. Server icon, Message)


Main section 2 (E.G. Servers bar, Messages content)
```


### File structure
> [!NOTE]
> File isn't updated to follow this yet

```
Theme imports and settings

Discord
    Title bar
        Discord icon
        Watermark text
        Search bar
            Search filters
        Account icon
        Window controls
    Servers bar
        Home button
        Server folders
        Server icons
            Selected highlight
            Unread message
            Mention
        Add server model
        Discovery page
        Discord Settings
            Pages in order 
        Server Settings
            Pages in order
    Home Page
        Friends
            Online
            All
            Pending
            Blocked
            Add friend
        Nitro
        Shop
        Family centre
            Activity
            My family
        DMs/groups
            Add to groupchat
            Sidebar user profile
        Activity feed
    Server page
        Channels list
            Server information
                Banner image
                Server type icon
                Title
                Boosts bar
                Boost model
            Events
            Channels and roles
                Customise
                Browse
            Members
                Mod view
            Channels
                Group
                Channel
            Current activity/game
            Voice chat connected
        Messages content
            Channel info
            Channel controls
                Threads
                Pins
                Inbox
            Messages
                Embeds
                Reactions
                Wave to user
            Enter message
                Text box
                Reply controls
                / commands
                Buttons
        Search results
        Members sidebar
            Role header
            Users
    User profile mini
        Profile icon
        Badges
        Roles
        Notes
    User profile full
        Profile icon
        Badges
        Categories
            User info
            Mutual servers
            Mutual groups
            Mutual friends
    Quick actions (Ctrl + T)
    Offline notice bar

Better Discord
    Mod loader
        Complie error content dialog
    Plugins

Vencord
    Mod loader
    Plugins

Common controls
    Toasts/Notifications
    Scrollbars
    Loading spinner
    Check box
    Radio buttons
    Toggle switches
    Sliders
    Drop down box
    Sidebar buttons
        Selected highlight
    Action buttons
        Main accented
        Secondary Other
    Text inputs
    Text selection
    Hyper links
    Tab selection
    Context menu
```
