# Project Helios

<img src="assets/eclipsed-moon.png" alt="Project Helios cratered crescent moon logo" width="160">

Project Helios is an upcoming open source Roblox launcher being built from scratch. It is made for developers who want to fork a launcher, experiment with their own ideas, and share a version that fits their needs.

This repository is at the planning stage. The features below describe the direction of the project.

## Planned features

- **Launch Roblox.** Open experiences in the official Roblox desktop player from a link or a saved favorite.
- **Optional Roblox sign-in.** Use [Roblox OAuth 2.0 with PKCE](https://create.roblox.com/docs/cloud/auth/oauth2-overview) to connect an account through Roblox's own consent screen. Helios is designed to request only the permissions it needs and keep Roblox passwords and browser session cookies out of the launcher.
- **Profile card.** Show the connected account's username, display name, and avatar when Roblox provides them.
- **Friends and connections.** Browse friends where supported by Roblox's [Connections APIs](https://create.roblox.com/docs/cloud/reference/features/friends) and the user's privacy settings. Saved friend bookmarks are also planned for quick access to Roblox profiles.
- **Local game library.** Keep favorites and launcher preferences on the device and let users browse their saved games offline.

## Made for forks

Use GitHub's **Fork** button to start your own version. Developers are welcome to give their fork a new interface, customize the game library, or swap in their own branding. If your fork adds Roblox sign-in, plan to register your own OAuth application and configure its redirect URLs and permissions.

Ideas and feedback are welcome in [GitHub Issues](https://github.com/Itxbreeze/Project-Helios/issues).

## MIT License

Project Helios is licensed under the [MIT License](LICENSE). You can use, fork, modify, and redistribute it, including your own modified versions. Keep the copyright notice and MIT permission notice with all copies or substantial portions of the software.

Project Helios is an independent project and is unaffiliated with Roblox Corporation.
