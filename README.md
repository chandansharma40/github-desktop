<h1 align="center">
  <img src="https://dashboard.snapcraft.io/site_media/appmedia/2017/07/git-github-hub-icon-25.png" alt="GitHub Desktop">
  <br />
  GitHub Desktop
</h1>

<p align="center"><b>This is the snap for GitHub Desktop</b>, <i>"simple GitHub collaboration from your desktop"</i>. It works on Ubuntu, Fedora, Debian, and other major Linux distributions.</p>

<p align="center">
<a href="https://build.snapcraft.io/user/snapcrafters/github-desktop"><img src="https://build.snapcraft.io/badge/snapcrafters/github-desktop.svg" alt="Snap Status"></a>
</p>

## Install

    snap install github-desktop --beta
    snap connect github-desktop:ssh-keys
    snap connect github-desktop:gpg-keys
([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

### Current issues

```
May  9 17:03:35 skull kernel: [286225.979306] audit: type=1107 audit(1525881815.451:2299): pid=2101 uid=103 auid=4294967295 ses=4294967295 msg='apparmor="DENIED" operation="dbus_method_call"  bus="system" path="/" interface="org.freedesktop.DBus.ObjectManager" member="GetManagedObjects" mask="send" name="org.bluez" pid=13598 label="snap.github-desktop.github-desktop" peer_pid=2127 peer_label="unconfined"
May  9 17:03:35 skull kernel: [286225.979306]  exe="/usr/bin/dbus-daemon" sauid=103 hostname=? addr=? terminal=?'
May  9 17:03:35 skull kernel: [286226.067051] audit: type=1400 audit(1525881815.539:2300): apparmor="DENIED" operation="open" profile="snap.github-desktop.github-desktop" name="/sys/devices/system/memory/block_size_bytes" pid=13847 comm="desktop" requested_mask="r" denied_mask="r" fsuid=1000 ouid=0
```

<!-- Uncomment and modify this when you have a screenshot
![GitHub Desktop](screenshot.png?raw=true "GitHub Desktop")
-->

<p align="center">Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with :gift_heart: by Snapcrafters</p>

## Remaining tasks

Snapcrafters ([join us](https://forum.snapcraft.io/t/join-snapcrafters/1325)) are working to land snap install documentation and the [snapcraft.yaml](https://github.com/snapcrafters/github-desktop/blob/master/snap/snapcraft.yaml) upstream so GitHub Desktop can authoritatively publish future releases.

  - [x] Fork the [Snapcrafters template](https://github.com/snapcrafters/fork-and-rename-me) repository to your own GitHub account
  - [x] Rename the forked Snapcrafters template repository
  - [x] Update logos and references to `[Project]` and `[my-snap-name]`
  - [x] Create a snap that runs in `devmode`
  - [x] Register the snap in the store, **using the preferred upstream name**
  - [ ] Add a screenshot to this `README.md`
  - [x] Publish the `devmode` snap in the Snap store edge channel
  - [x] Add install instructions to this `README.md`
  - [x] Update snap store metadata, icons and screenshots
  - [ ] Convert the snap to `strict` confinement, or `classic` confinement if it qualifies
  - [ ] Publish the confined snap in the Snap store beta channel
  - [ ] Update the install instructions in this `README.md`
  - [ ] Post a call for testing on the [Snapcraft Forum](https://forum.snapcraft.io) - [link]()
  - [ ] Request your GitHub repository is forked to the Snapcrafters organisation and configured for automated builds
  - [ ] Add the provided Snapcraft build badge to this `README.md`
  - [ ] Publish the snap in the Snap store stable channel
  - [ ] Update the install instructions in this `README.md`
  - [ ] Post an announcement in the [Snapcraft Forum](https://forum.snapcraft.io) - [link]()
  - [ ] Submit a pull request or patch upstream that adds snap install documentation - [link]()
  - [x] Submit a pull request or patch upstream that adds the `snapcraft.yaml` and any required assets/launchers - discussing via email
  - [x] Add upstream contact information to the `README.md`  
  - If upstream accept the PR:
    - [ ] Request upstream create a Snap store account
    - [ ] Contact the Snap Advocacy team to request the snap be transferred to upstream
  - [ ] Ask the Snap Advocacy team to celebrate the snap - [link]()

If you have any questions, [post in the Snapcraft forum](https://forum.snapcraft.io).

githu ## The Snapcrafters

| [![Martin Wimpress](http://gravatar.com/avatar/ce95823a37d9ffa2e65a31cc60a2c42a/?s=128)](https://github.com/flexiondotorg/) |
| :---: |
| [Martin Wimpress](https://github.com/flexiondotorg/) |

## Upstream

| [![Josh Abernathy](https://avatars0.githubusercontent.com/u/13760?v=3&s=128)](https://github.com/joshaber) |
| :---: |
| [Josh Abernathy](https://github.com/joshaber) |
