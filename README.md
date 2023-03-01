# Setup

1) Fork this repository
2) [Download and install Obsidian](https://obsidian.md/download)
3) Open this repository as an Obsidian vault using the **Open folder as vault** option in the vault selection menu.
4) Install and enable the following community plugins, which are required to keep up to date with this project. You can find the list of community plugins by going to **Settings > Community plugins** under the **Options** umbrella.

>[!IMPORTANT] Required plugins
>- **Dataview** this enables the querying of metadata and is used here to create an interconnected look and feel, including links to the previous and next posts.
>- **Obsidian Git** will allow you to pull the latest posts to your instance of this project.

5) Once setup, navigate to the top-level note named **"Start here"** for an overview of the project and a list of resources for getting started.

> [!IMPORTANT] Staying up to date
> Going forward, you can use <kbd>CTRL + P</kbd> to open the **Command palette**. From there, call the **Obsidian Git: Pull** command to pull any updates to your instance of the project.

# Recommended plugins

Similar to Visual Studio Code, expanding base functionality through the use of plugins is the backbone of Obsidian. There is a long list of core plugins that come packaged with the software, as well as an active community creating and updating community plugins.

## Core plugins

You can find the list of core plugins packaged with Obsidian by going to **Settings > Core plugins** under the **Options** umbrella. Here are the ones I'd recommend, some of which may be enabled by default:

- **Outline** enables you to see the sections and subsections of each page at a glance and navigate to them more easily.
- **Backlinks** and **Outgoing links** help you to navigate pages and see the relationships and connections between different ideas.
- **Page preview** allows you to preview pages by hovering over links. This project is structured entirely around links so I highly recommend using this.
- **Files** and **Tags** enable a standard file explorer user interface which is not necessarily recommended for Obsidian but which may be more familiar to those new to the tool. 
- **Quick switcher** is what Obsidian has chosen to replace the standard file explorer user interface with, and it enables a faster method of moving between pages.
- **Graph view** and **Canvas** both enable a more visual view of connections between notes. I will make a canvas view of this project available soon.

## Community plugins

You can find the list of community plugins by going to **Settings > Community plugins** under the **Options** umbrella. Here are the one's I'd recommend:

- **Plugin Update Tracker** is helpful for knowing when to update plugins you've installed. Specifically, the required Dataview and Obsidian Git plugins should always be updated when possible. 
- If you are going to be fiddling with the settings more often, I would also recommend the **Settings Search** plugin which makes available a simple search bar in the Settings menu.
- I personally find **Heading Level Indent** helpful in visually discerning the relative hierarchy of sections and subsections in a page.

## Themes and CSS snippets

Similar to plugins are themes, which you can find by going to **Settings > Appearance > Themes > Manage**. The theme I personally use is "Big Sur Aesthetic" in "Dark" mode.

I've also written some simple tweaks to the theming of Obsidian, which you'll find in `snippet.css`. You should be able to enable this by placing it in `.obsidian > snippets`, then going to **Settings > Appearance > CSS snippets** and enabling `snippet.css`.