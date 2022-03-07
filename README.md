# Up Next

See and join your meetings from the menu bar. Connects with your calendar and works with Zoom, Google Meet, Cisco Webex, and more. All supported platforms are [listed here](https://github.com/ellenli/upnext/issues/51) (with more to come).

Up Next is in active development. Built for macOS 10.12+. **Get the latest version from the [App Store](https://itunes.apple.com/us/app/up-next/id1355117041?ls=1&mt=12).** :v:

## Setup

1. Run Up Next
2. The app will prompt for your Calendar data. This is required for Up Next to work! Click `OK`
3. Click `No upcoming meetings` (in your menu bar) > `Preferences...` and select your calendar from the calendar list to load your meetings

If the access prompt did not appear, or if you mis-clicked, you can fix this in `System Preferences` > `Security & Privacy` > `Calendars`. Make sure `Up Next` is checked in the list of apps that can access your Calendar data.

## Help

<details>
  <summary><b>I don't see my preferred calendar in the calendar list</b></summary><br />
Up Next uses data from the Calendar app. If your preferred calendar is missing from available calendars in Up Next, add your calendar to the Calendar app.

1. Run Calendar – all available calendars are listed in the left `Calendars` sidebar. If your preferred calendar is missing from this list, go to step 2
2. `Calendar` > `Add account`
3. Complete the steps for your calendar account provider

If your calendar is still not showing up in Calendar, make sure your calendar account is enabled: `Calendar` > `Preferences...` > `Accounts` tab > Select your calendar account and make sure `Enable this account` is checked.
</details>

<details>
  <summary><b>Meetings in the menu bar dropdown are not updating</b></summary>
  Meetings are refreshed based on your calendar's refresh settings. You can change this time interval in Calendar.

1. Run Calendar
2. `Calendar` > `Preferences...` > `Accounts` tab > Select your calendar account
3. In the `Refresh Calendars` dropdown, select your preferred refresh rate (`Every minute` recommended).</details>

<details>
  <summary><b>I'm getting sent to a Google Meet error page</b></summary>
  This was fixed in Up Next version 1.0.0. Get the latest version in the <a href="https://itunes.apple.com/us/app/up-next/id1355117041?ls=1&mt=12">App Store</a>.</details>

<details>
  <summary><b>Keyboard shortcuts don't work</b></summary>
  Other apps may be using the same keyboard shortcut. You can customize shortcuts as of version 1.0.0 (Pro users only). Get the latest version in the <a href="https://itunes.apple.com/us/app/up-next/id1355117041?ls=1&mt=12">App Store</a>.</details>

<details>
  <summary><b>The countdown time is wrong/frozen</b></summary>
  If you encounter this issue, please report the bug. Include your macOS version, app version, and a list of all other apps that access your calendar data (available via <code>System Preferences</code> > <code>Security & Privacy</code> > <code>Calendars</code>).</details>

<details>
  <summary><b>I want to purchase Up Next Pro for my company/organization</b></summary>
  Enterprise licensing/pricing is available for organizations of <strong>50 users or more</strong>. <a href="mailto:licensing@upnextapp.com">Reach out to learn more</a>.</details>

<details>
  <summary><b>I want to cancel my Up Next Pro subscription</b></summary>
Subscription and payments go through Apple. <a href="https://support.apple.com/HT202039">Follow these steps</a> to cancel your Up Next Pro subscription.</details>

## Colophon
Up Next is a project by [Ellen Li](https://ellen.li). The app is written in Objective-C and Swift 4.0.

Up Next also uses:
- [HotKey](https://github.com/soffes/HotKey) for keyboard shortcuts
- [DateTools](https://github.com/MatthewYork/DateTools) for the countdown

This repository hosts the Up Next [website](http://ellen.li/upnext/) and light documentation. If you encounter bugs or have a feature request, [add an issue](https://github.com/ellenli/upnext/issues/new) or [contact Ellen directly](https://twitter.com/ellenxli)!

Thank you for using Up Next! :wave:
