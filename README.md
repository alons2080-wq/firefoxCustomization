# firefoxCustomization

A custom CSS configuration to transform Firefox into an aesthetically pleasing and functional browsing environment. Designed for Linux users seeking an integrated and visually cohesive workflow.

## Features
* **Glassmorphism UI:** macOS-inspired transparency and blur effects.

* **Integration:** Optimized for Linux desktop environments (ideal for Cinnamon/GTK).

* **Cleanliness:** Simplified toolbar and optimized tab space.

* **Flexibility:** Styles applicable via `userChrome.css` (UI) and `userContent.css` (web content).

## Installation

1. **Locate your profile:**

Type `about:support` in the Firefox address bar and locate your **Profile Folder**.

2. **Enable customization:**

* Open your profile folder.

* Create a folder named `chrome` (if it doesn't already exist).

* In `about:config`, ensure that `toolkit.legacyUserProfileCustomizations.stylesheets` is set to `true`.

3. **Install the styles:**
Copy the `userChrome.css` and `userContent.css` files into the newly created `chrome` folder.

4. **Restart:**
Restart your browser to apply the changes.

## Suggested dependencies
* To achieve the native blur effect on Linux, it is recommended to use a window compositor with *blur* support (such as `picom` or Cinnamon's native window manager).

## Contributions
Pull requests are welcome. If you have specific tweaks for other distributions or environments, please feel free to share them.

---*Designed by mrrat0*
