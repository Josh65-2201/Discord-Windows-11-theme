![image](https://github.com/Josh65-2201/Discord-Windows-11-theme/blob/main/.github/preview.webp?raw=true)

## Download

<details>
	<summary><h3>Better Discord</h3></summary>
	<b>Offline - Manual update</b>
	<p>Open https://raw.githubusercontent.com/Josh65-2201/Discord-Windows-11-theme/main/Discord_Windows_11.theme.css > Right click > Save as > Go to BetterDiscord themes folder (%AppData%\BetterDiscord\themes) > Save</p>
</details>

<details>
	<summary><h3>Vencord</h3></summary>
	<h3>IMPORTANT ThemeAttributes plugin needs to be enabled</h3>
	<b>Offline - Manual update</b>
	<p>Open https://raw.githubusercontent.com/Josh65-2201/Discord-Windows-11-theme/main/Discord_Windows_11.theme.css > Right click > Save as > Go to Vencord themes folder (%AppData%\Vencord\themes) > Save</p>
	<b>Online - Auto update</b>
	<p>Copy URL https://raw.githubusercontent.com/Josh65-2201/Discord-Windows-11-theme/main/Discord_Windows_11.theme.css > Open Discord settings > Click "Themes" > Click "Online themes" > Paste in "Theme links".</p>
</details>

<br>

## Functionality changes
### Moved settings
- Toast/Notifications now have an global toggle in the themes settings
- Mute and deafen settings are now shown only on the voice connected panel
- Search bars are on the title bar
- User profile is now in the title bar next to window controls


### Other
- User/Members list will now auto hide at smallest window size. (Toggle doesn't do anything visibly at min size but will save state upon resize)
- Due to layering issues the Window drag area is small bar at top of the window

<br>

## Editing
### Guidelines
- Any text editor will work, Visual Studios Code is recommended.
- Indent using tabs at 4 spaces.
- New sections follow the below format.
```
Main section 1 (E.G. Servers bar, Sidebar, Center content)
	Sub section 1 (E.G. Server icon, Message)
		Part 1 (Position, Background color)
		CSS

		Part 2 (Position, Background color)
		CSS

	Sub section 2 (E.G. Server icon, Message)


Main section 2 (E.G. Servers bar, Sidebar, Center content)
```