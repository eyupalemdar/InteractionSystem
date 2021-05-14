# Interaction System Component
![Image](https://github.com/eyupalemdar/InteractionSystem/blob/main/Resources/interaction-system.gif)

Interaction System component is used to interact different actors in Unreal Engine. These interactions can assume any form, for example taking a weapon, mounting/dismounting a horse etc. During these interactions, characters can play animations and provide other player feedback. Multiple characters can be interacted with same actor or you can define rules in what condition interaction can be happened. Inspired by [Amiran's project.](https://github.com/Amirans/InteractionPlugin)

## Showcase Project
You can checkout the [example project](https://github.com/eyupalemdar/InteractionSystemExample) and examine how the InteractionSystem plugin is used.

## Supported Platforms
- Windows

*macOS, iOS, Linux, Android, and console builds are not tested. Use the plugin on those platforms with your own risk*.

## Features
 * Interactor and Interactable components with useful Interfaces
 * %100 implemented in Blueprint Scripting
 * Interaction can be happened Instantly, Hold Duration or Rule Based. 
 * Full replication support with low bandwidth usage. (Networking / Multiplayer Support)

## Known Issues & Discussion
- See [Issues](https://github.com/eyupalemdar/InteractionSystem/issues) section for list of known issues.
- See [Discussions](https://github.com/eyupalemdar/InteractionSystem/discussions) section to discuss anything about the plugin, and ask questions. Please do not open an issue to ask questions about the plugin.

## Setting Up The Plugin
- Clone the repository inside your project's `Plugins` folder, or download the latest release and extract it into your project's `Plugins` folder.
- Launch the project, and enable plugin content viewer as seen below. This will show contents of the plugin in your content browser:
![image](https://github.com/eyupalemdar/InteractionSystem/blob/main/Resources/Readme_Content_1.png)

## How to Use
- Add InteractorComponent to your actor who will interact with interactable actors
- Add InteractableComponent to your actor who will be interacted

## License & Contribution
**Source code** of the plugin is licensed under MIT license, and other developers are encouraged to fork the repository, open issues & pull requests to help the development.
