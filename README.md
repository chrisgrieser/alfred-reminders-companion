<!-- LTeX: enabled=false -->
# Alfred reminders companion
<!-- LTeX: enabled=true -->
![Download count](https://img.shields.io/github/downloads/chrisgrieser/alfred-reminders-companion/total?label=Total%20Downloads&style=plastic)
![Version number](https://img.shields.io/github/v/release/chrisgrieser/alfred-reminders-companion?label=Latest%20Release&style=plastic)

Display and edit reminders due today.

<img alt="Showcase" width=70% src="https://github.com/user-attachments/assets/627ef6de-8fe9-4710-8352-2c63e4be5e67">

## Usage
- Display reminders due today (or overdue) via the keyword `rem`. Alternatively,
  you can also use a
  [hotkey](https://www.alfredapp.com/help/workflows/triggers/hotkey/) for that.
	+ <kbd>⏎</kbd>: Complete the reminder.
	+ <kbd>⌘⏎</kbd>: If the reminder has a URL, open it in the default browser,
	  otherwise, copy the reminder's text to the clipboard. Afterward, complete
	  the reminder.
	+ <kbd>⌥⏎</kbd>: Edit the reminder in Alfred. (The first line is the
	  reminder title, the rest is the reminder body.)
	+ <kbd>⇧⏎</kbd>: "Snooze" the reminder by changing its due date to tomorrow.
	+ <kbd>⌃⏎</kbd>: Display completed reminders due today as well. Using
	  <kbd>⏎</kbd> on a completed reminder marks it as uncompleted. The other
	  modifiers work the same as with uncompleted reminders. Use <kbd>⌃⏎</kbd>
	  again to hide completed reminders again.
	+ <kbd>fn⏎</kbd>: Increase the reminder's priority by one level (or reset it
	  to "none," if already at the highest priority).
- Quickly add a new reminder due today with the keyword `qq`. Alternatively, you
  can also use a
  [hotkey](https://www.alfredapp.com/help/workflows/triggers/hotkey/) to add
  the currently selected text or current browser tab as a reminder.
- Add a reminder due at a future date with the keyword `atdate`.

## Installation
This workflow requires the
[reminders-cli](https://github.com/keith/reminders-cli):

```bash
brew install keith/formulae/reminders-cli
```

[➡️ Download the latest release of this
workflow.](https://github.com/chrisgrieser/alfred-reminders-companion/releases/latest)

As the workflow uses an unofficial homebrew package, it is not eligible for the
Alfred Gallery. The workflow nonetheless auto-updates via the
[OneUpdater](https://github.com/vitorgalvao/alfred-workflows/tree/a2a2984ec4c7b839b7bf45315491c6993ef13444/OneUpdater).

## Credits
Icon by [Emoopo-Design](https://macosicons.com/#/u/Emoopo-Design)

<!-- vale Google.FirstPerson = NO -->
## About the developer
In my day job, I am a sociologist studying the social mechanisms underlying the
digital economy. For my PhD project, I investigate the governance of the app
economy and how software ecosystems manage the tension between innovation and
compatibility. If you are interested in this subject, feel free to get in touch.

- [Academic Website](https://chris-grieser.de/)
- [Mastodon](https://pkm.social/@pseudometa)
- [ResearchGate](https://www.researchgate.net/profile/Christopher-Grieser)
- [LinkedIn](https://www.linkedin.com/in/christopher-grieser-ba693b17a/)

<a href='https://ko-fi.com/Y8Y86SQ91' target='_blank'>
	<img
	height='36'
	style='border:0px;height:36px;'
	src='https://cdn.ko-fi.com/cdn/kofi1.png?v=3'
	border='0'
	alt='Buy Me a Coffee at ko-fi.com'
/></a>
