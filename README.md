<p align="center">
  <img src="https://user-images.githubusercontent.com/34204380/208291548-17d707ec-8360-4dcd-b5d2-5bfa3267aabe.png" alt="Homerow icon" width="auto" height="192px"/>
</p>

<p align="center">
  <h1 align="center">Homerow - Navigate macOS like a Pro</h2>
</p>

Like Raycast or Spotlight for macOS. Click, navigate, and perform tasks with the keyboard and no mouse.

Visit the website at https://homerow.app.

## Demo

<video src="https://user-images.githubusercontent.com/34204380/205491000-5f3cc28f-2f94-4586-bbed-643001f58d6d.mp4"></video>

## Download

Download Homerow and view the changelog [here](https://homerow.app/download/).

Requires macOS 12.3 or later.

## User Guide

This is Homerow's workflow:
1. Activate via shortcut (default is `Command-Shift-Space`)
2. Search for the UI element to click on
3. Labels (aka dynamic shortcuts) will be shown for the UI elements matching the query. The green target is the current focused UI element.
4. There are two ways to focus the correct UI element:
    - Press `Tab` or `Arrow-Dn` until the correct UI element is focused
    - Type the UI element's label text while holding `Shift`
5. Press `Return` to perform a click on the focused UI element

There is an option to use the Labels-only workflow, which disables the search feature and allows you to type the label text without holding down `Shift`.

### Queries

1. Spaces and cases are ignored
2. `*` and `;` will query for all UI elements

### Not sure what to type? The Tutor 🤓 comes to the rescue!

<img width="701" alt="tutor" src="https://user-images.githubusercontent.com/34204380/205489888-ccd3993f-dd6c-4408-a45c-e76d19c94d28.png">

The Tutor shows you searchable properties of a UI element.

When Homerow is activated, you can call for the Tutor two ways:
1. Press `?` for Tutor to follow the focused UI element
2. Hover your cursor over the UI element

### Disable search for speed 🏃‍♂️💨

Labels-only mode disables search. Labels for all UI elements are always shown, and label-text can be typed without holding `Shift`. You can click more ergonomically by pressing `Space` instead of `Return`.

Made for those who ❤️ Vimium and Vimperator.

### Controls

| Action  | Binding(s) |
| ------------- | ------------- |
| Focus next UI element | `Tab`, `Arrow Dn`, or `Control-N` |
| Focus previous UI element | `Shift-Tab`, `Arrow Up`, or `Control-P` |
| Jump focus to UI element | Type the label while holding `Shift` |
| Left-click | `Return` |
| Double left-click | Press `Return` twice in quick succession |
| Right-click | `Shift-Return` |
| Command-click (performs `Open Link in New Tab`) | `Command-Return` |
| Enable the `Tutor 🤓` | `?` or hover your cursor over the UI element |
| Exit | `Esc` |


### Scroll with HJKL keys 🛞

Activate Scroll-mode with the shortcut (default is `⇧ ⌘ J`) and start scrolling in the active scroll area with HJKL keys (DHTN in DVORAK).

| Action  | Binding(s) |
| ------------- | ------------- |
| Scroll | `H/J/K/L` |
| Dash | `Shift-H/J/K/L` |
| Next scroll area | `Tab`, `Arrow Down`, or `Control-N` |
| Previous scroll area | `Shift-Tab`, `Arrow Up`, or `Control-P` |
| Jump to scroll area | `0-9` |
| Exit | `Esc` |

### Pro-tip: Map Caps Lock to Hyper Key

You'll likely activate Homerow quite frequently, so make the controls as comfortable and as quick as possible for the best experience.

Three reasons to use Hyper Key:
1. Activate Homerow with `Caps Lock + F`
2. Focus the next or previous UI Element with `Caps Lock + J` and `Caps Lock + K` respectively.
3. Navigate menus with `Caps Lock + H/J/K/L`

How to set up Hyper Key:
1. [Hyperkey](https://hyperkey.app) by Ryan Hanson OR
2. Configure Karabiner-Elements
  - You can import my Karabiner Hyper Key rules by opening this link in your browser:
    ```
    karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/dexterleng/homerow/main/hyper_key.json
    ```
    - [View the rules JSON](https://github.com/dexterleng/homerow/blob/main/hyper_key.json)
    
## Support

Encountered a bug? Would like to request a feature? An app does not work well with Homerow?

Please let me know through:
- Open a GitHub Issue
- Email me at <a href="mailto:dexter@homerow.app">dexter@homerow.app</a>

---

Homerow is developed by an indie developer (me). It can be evaluated for free. Please [purchase a license](https://www.homerow.app/pricing/) to support development. Thanks!
