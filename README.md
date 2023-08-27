# 🌳 eyeTree
Fine-Tuned Personal i3wm Configuration for Optimal Workflow

## Installation

Follow these steps to set up the i3 configuration on your system:

1. **Backup Your Existing Configuration (Optional but Recommended)**:
   ```sh
   mv ~/.config/i3 ~/.config/i3_backup
   ```

2. **Clone the Repository**:
   ```sh
   git clone https://github.com/EHER/eyeTree.git ~/.config/i3
   ```

3. **Restart i3**:
   Once you've copied the configuration files, restart i3 to apply the changes.
   - If you're already using i3, simply reload the configuration with <kbd>Mod</kbd> + <kbd>Shift</kbd> + <kbd>R</kbd>.
   - If you're on the login screen, select "i3" as your session and log in.

## Key Bindings

Here are some of the key bindings included in this configuration:

- <kbd>Mod</kbd> + <kbd>Enter</kbd>: Launch terminal
- <kbd>Mod</kbd> + <kbd>D</kbd>: Launch application launcher
- <kbd>Mod</kbd> + <kbd>Shift</kbd> + <kbd>E</kbd>: Exit i3
- <kbd>Mod</kbd> + <kbd>1-9</kbd>: Switch to workspace 1-9
- <kbd>Mod</kbd> + <kbd>Shift</kbd> + <kbd>1-9</kbd>: Move focused window to workspace 1-9
- ...

Customize key bindings and configuration options by editing the `~/.config/i3/config` file.
