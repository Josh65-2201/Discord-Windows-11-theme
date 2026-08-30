![image](https://github.com/Josh65-2201/Discord-Windows-11-theme/blob/main/.github/preview.webp?raw=true) <!-- 1836 -->

## Download

### Better Discord

  1. Open https://raw.githubusercontent.com/Josh65-2201/Discord-Windows-11-theme/main/Discord_Windows_11.theme.css
  2. Right click
  3. Save as
  4. Go to BetterDiscord themes folder (%AppData%\BetterDiscord\themes) 
  5. Save

### Vencord

  > [!Important]
  > Theme attributes plugin needs to be enabled

  1. Copy URL `https://raw.githubusercontent.com/Josh65-2201/Discord-Windows-11-theme/main/Discord_Windows_11.theme.css`
  2. Open Discord settings
  3. Click "Themes"
  4. Click "Online themes"
  5. Paste in "Theme links"

<br>

## Functionality changes

- Mute and deafen settings are now shown only on the voice connected panel
- Search bars are on the title bar
- User profile is now in the title bar next to window controls
- User/Members list will now auto hide at smallest window size. (Toggle doesn't do anything visibly at min size but will save state upon resize)

<br>

## Development

### Guidelines

- Any editor will work, Visual Studios Code is recommended.
- Indents use 2 spaces.
- New sections follow the line gaps

```txt
 1|Main section 1 (E.G. Servers bar, Messages content)
 2|  Sub section 1 (E.G. Server icon, Message)
 3|    Part 1 (Position, Background color)
 4|
 5|    Part 2 (Position, Background color)
 6|
 7|
 8|  Sub section 2 (E.G. Server icon, Message)
 9|
10|
11|
12|
13|
14|Main section 2 (E.G. Servers bar, Messages content)
```

### File structure

```txt
Theme imports and settings
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
