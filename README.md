# Homerow

Like Raycast or Spotlight for macOS. Click, navigate, and perform tasks with the keyboard and no mouse.

Visit the website at https://homerow.app.

## Demo


<video src="https://user-images.githubusercontent.com/34204380/194687760-b7e5da15-b2ce-4d18-99ea-8cefd9a9fecf.mp4"></video>

## Download

Download Homerow and view the changelog [here](https://homerow.app/download/).

Requires macOS 12.3 or later.

## User Guide

This is Homerow's workflow:
1. Activate via shortcut (default is `Command-Shift-Space`)
2. Search for the UI element to click on
3. Targets will show for the UI elements matching the query. The green target is the current focused target.
4. Press `Tab` or `Arrow-Dn` until the correct UI element is focused
5. Press `Enter` to perform a click on the UI element

### Queries

1. Spaces and cases are ignored
2. `*` will query for all UI elements

### Not sure what to type? The Tutor 🤓 comes to the rescue!

<img width="701" alt="tutor" src="https://user-images.githubusercontent.com/34204380/194684445-957c80ec-1e58-44bc-8891-f5e633d2dabe.png">

Press `Command-T` to toggle The Tutor. Hover the cursor over the UI element to learn about it’s searchable properties.

### Controls

| Action  | Binding(s) |
| ------------- | ------------- |
| Focus next UI element | `Tab`, `Arrow Dn`, or `Control-N` |
| Focus previous UI element | `Shift-Tab`, `Arrow Up`, or `Control-P` |
| Left-click | `Enter` |
| Right-click | `Shift-Enter` |
| Command-click (performs `Open Link in New Tab`) | `Command-Enter` |
| Toggle `The Tutor 🤓` | `Command-T` |
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

## Bug Reports, Feature Requests, etc.

- Open a GitHub Issue
- <a href="mailto:dexter@homerow.app">dexter@homerow.app</a>

---

Homerow is developed by an indie developer (me). It can be evaluated for free. Please [purchase a license](https://www.homerow.app/pricing/) to support development. Thanks!
