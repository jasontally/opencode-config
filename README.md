# OpenCode Configuration

This repository contains my personal OpenCode configuration files. At this point the only notable thing in here is an additional primary agent called "web" that only has the web fetch, todo write and todo read tools enabled and has a version of the main opencode prompt that is changed to remove coding specific sections and to focus more on web research.

## Installation

To clone this repository directly into your home directory at the correct location, run:
##WARNING this will delete your existing opencode config WARNING## 

```bash
rm -r ~/.config/opencode
git clone https://github.com/jasontally/opencode-config.git ~/.config/opencode
```

This will create the `~/.config/opencode` directory and download all configuration files into it.

## Contents

- `opencode.jsonc` - Main OpenCode configuration file
- `prompts/` - Directory containing custom prompts
  - `web.txt` - Web-related prompts

## Usage

After cloning, OpenCode should automatically detect and use these configuration files when you run it from any directory. Use the TAB key to switch between the default plan and bulid agents in addition to the web agent that this config adds.

## Customization

Feel free to modify these files to suit your needs. The main configuration is in `opencode.jsonc` and custom prompts can be added to the `prompts/` directory.
