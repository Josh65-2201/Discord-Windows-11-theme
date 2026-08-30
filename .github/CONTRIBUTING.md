## Editor guidelines

- Use 2 spaces intends.
- New sections follow the line gaps like below

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

## CSS property order

- display
- visibility
- overflow
- position
- top
- left
- right
- bottom
- z-index
- align
- max-width
- min-width
- width
- max-height
- min-height
- height
- line-height
- padding
- padding-*
- margin
- margin-*
- border
- border-radius
- background
- background-color
- background-image
- background-repeat
- color
- opacity
- transform
- transition
- animation
- Everything not listed above

## File structure

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
