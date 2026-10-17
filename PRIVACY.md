# Shepherd Privacy Policy

_Last updated: 18 October 2026_

Shepherd is a macOS app for working with AI coding agents, made by LynkSphere.

## The short version

Shepherd collects no personal data. It has no analytics and no servers of its own. What it reads stays on your Mac, unless you use Shepherd on iPhone, in which case it travels only through your own private iCloud.

## What the app reads

To show what your agents are doing, Shepherd reads, locally on your Mac:

- Claude Code's session files (`~/.claude`) and Codex's (`~/.codex`): each session's state, title, folder, your latest prompt and the agent's latest reply.
- The list of running processes, to tell live sessions from finished ones and to bring the right window forward.
- The files and folders of projects you add, when you browse, search or edit them.

Your projects, tabs and settings are saved on your Mac in `~/Library/Application Support/Shepherd` and the standard macOS preferences. Shepherd never changes your Claude Code or Codex setup.

## Shepherd on iPhone and iCloud

If you're signed in to iCloud, Shepherd on the Mac listens for Shepherd on iPhone in your **private iCloud database**. Nothing about your sessions is shared until the iPhone app asks for it. While it's watching (when the app is open, and for the time you choose after you leave it), the Mac writes a summary of your sessions (state, title, project folder name, latest prompt and reply) and short alerts to that database, and the iPhone can send back answers you choose (Approve, Deny, Stop or a reply), which the Mac types into the matching Shepherd terminal tab.

Your private iCloud database belongs to you: it's stored by Apple, only your Apple Account can read it, and the developer can't. You can turn this off in **Settings → iPhone**.

## Network access

- **Updates:** Shepherd checks for updates once a day by downloading a small update feed from `ekram.tech`, and downloads updates from `github.com` when one is available. These requests include no personal information beyond what any web request carries (such as your IP address and the app's version).
- **iCloud:** as described above, only with your own iCloud account.
- **Your terminal:** commands you run in Shepherd's terminal (including the agents themselves) make their own network requests, just as they would in any terminal.

## Tracking, analytics and third parties

Shepherd contains no analytics, advertising or tracking code and does not share data with third parties.

## Children

Shepherd does not collect data from anyone, including children.

## Changes

If this policy changes, the updated version will be published at this address with a new date.

## Contact

Questions about privacy: [ekram@lynksphere.com](mailto:ekram@lynksphere.com)
