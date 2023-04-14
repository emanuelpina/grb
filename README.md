# grb
A Go and Rust binaries installer

## Usage
```
sudo grb [OPTION] [APP]
```

### Options
 - dependencies - list all dependencies and check if they're installed
 - help - print this help message
 - info - list all apps and check if they're installed
 - info [APP] - check if an app is installed and its local and latest available versions
 - install [APP] - install an app
 - install [APP] [VERSION] - install a specific version of an app
 - self-update - update grb to its latest version
 - update [APP] - update an app to its latest version
 - update [APP] [VERSION] - update an app to a specific version
 - uninstall [APP] - uninstall an app
 - version - print grb version

### Available apps
 - bat - A cat(1) clone with wings
 - bottom - Yet another cross-platform graphical process/system monitor
 - ctop - Top-like interface for container metrics
 - duf - Disk Usage/Free Utility - a better 'df' alternative
 - dust - A more intuitive version of du in rust
 - exa - A modern replacement for ‘ls’
 - github - GitHub’s official command line tool
 - hcloud - A command-line interface for Hetzner Cloud
 - helix - A post-modern modal text editor
 - hugo - The world’s fastest framework for building websites
 - rclone - rsync for cloud storage
 - restic - Fast, secure, efficient backup program