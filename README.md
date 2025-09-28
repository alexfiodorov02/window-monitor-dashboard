# Window Monitor Dashboard

A lightweight, browser-based activity monitoring tool that tracks user interactions such as focus changes, mouse movements, keyboard input, and clipboard events. Designed for educational, debugging, or behavioral analysis purposes.

## Features

- **Window & Tab Monitoring**
  - Detects focus/blur events
  - Tracks visibility changes (e.g., tab switching or minimizing)

- **Mouse Tracking**
  - Monitors mouse presence on the page
  - Logs mouse leave events

- **Clipboard Events**
  - Detects large copy/paste actions
  - Flags suspicious paste behavior

- **Keyboard Interaction**
  - Logs keystrokes and timing intervals
  - Detects shortcut usage (e.g., Ctrl+V, Ctrl+F, Alt+Tab)
  - Blocks F12 (DevTools) and right-click context menu

- **Code Editor**
  - Embedded textarea for typing code
  - Logs focus, blur, and input anomalies

- **DevTools Detection**
  - Flags potential DevTools opening via resize anomalies

- **Activity Log**
  - Real-time logging with severity levels: `info`, `warning`, `critical`
  - Scrollable log container for easy review

## Installation

Clone the repository:

```zsh
git clone https://github.com/alexfiodorov02/window-monitor-dashboard.git
```
## Usage

Simply open the HTML file in a browser. Begin interacting with the page—switch tabs, type in the editor, copy/paste text—and observe the activity log update in real time.

## File Structure

activity-monitor-dashboard/
├── index.html       # Main dashboard file
└── README.md        # Project documentation

## License
This project is licensed under the MIT license.