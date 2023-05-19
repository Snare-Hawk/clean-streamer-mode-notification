# snare-CSS

A collection of CSS snippets that I use for [Replugged](https://github.com/replugged-org/replugged) and [Vencord](https://github.com/Vendicated/Vencord).

Feel free to use them, or don't!

star me \:3

For more CSS snippets, from me and from many others, check out the CSS snippet channels in the [Replugged](https://discord.gg/replugged) and [Vencord](https://discord.gg/vencord) Discord servers.

---

## Profile Panel Thingy

Makes the profile panel thingy look neat!

```css
@import url("https://snare-hawk.github.io/snare-CSS/profile-panel-thingy.css");
```

#### No Activities

![no activities](https://i.imgur.com/xhYa07G.png)

#### Spotify and Game Activities

![spotify and game activities](https://i.imgur.com/aEaRWqv.png)

## Server Icon Edits

Edits certain server icons, this is something I just personally use.

```css
@import url("https://snare-hawk.github.io/snare-CSS/server-icon-edits.css");
```

#### Before

![before](https://i.imgur.com/NIRa4PN.png)

#### After

![after](https://i.imgur.com/DWX51kz.png)

## Clean Streamer Mode Notification

Makes streamer mode notification less intrusive.

```css
@import url("https://snare-hawk.github.io/snare-CSS/clean-streamer-mode-notification.css");
```

![image](https://i.imgur.com/WpsCXsJ.png)

## Profile Skin Experiment Snippet \*

Makes the profile pop-out look like the skin experiment with CSS.
This allows already existing plugins to be seen, as the experiment changed many things.

```css
@import url("https://snare-hawk.github.io/snare-CSS/profile-skin-experiment-snippet.css");
```

#### Experiment

![experiment](https://i.imgur.com/ynhnivS.png)

#### Snippet

![snippet](https://i.imgur.com/gPXLdbm.png)

\* This snippet is outdated as the experiment has been added to Discord.

## Settings Plugin Sorter \*

A temporary CSS solution that sorts and separates plugins in settings.

If I remember correctly, [Powercord's](https://github.com/powercord-org/powercord) settings had looked like this quite some time ago.

```css
@import url("https://snare-hawk.github.io/snare-CSS/settings-plugin-sorter.css");
```

Because of an update I had to push, you now must include this in your quick CSS:

```css
/* X must be however many settings you have under the tab */
:root {
    --multiplier: X;
}
```

Like it says, `X` must be the number of options you have under the header, the minimum should be 4, if you don't have CSS Toggler or bdCompact, and the maximum is 6, if you do have both.

![image](https://i.imgur.com/LduI3Nh.png)

\* Now that this is has a part of Replugged, most of the above is now outdated, though I had updated the CSS so it adds CSS Toggler and bdCompact to be under the Replugged tab. (This was before the SWC, where these plugins were still avaiable in Replugged.)

## Dark+ Quick CSS \*

An attempt to make Quick CSS look like VScode's Dark+ theme. (Unfortunately, does not work when editor is popped out.)

```css
@import url("https://snare-hawk.github.io/snare-CSS/dark-plus-quick-css.css");
```

![image](https://i.imgur.com/xW6vuMi.png)

\* This snippet does not work anymore as Replugged does not use CodeMirror for its Quick CSS anymore. ~~Also because I do not care enough to try and update it, but from the looks of it, it doesn't even seem possible.~~
