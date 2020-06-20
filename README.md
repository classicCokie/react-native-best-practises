# React Native Best Practises (WIP)

A living Document where you can find best practises for setting up react native projects.
These Practises are by no means universally correct, just workflows I find to be helpfull.
Always open for new sugesstions. Never perfect, always improving.

- [Folder Structure](./FolderStructure/folderStructure.md)
- [Linting](./Linting/linting.md)

## Premium Content

If your app has premium content, which will only be accessible after purchasing some sort of subscription etc. Make sure to have a mechanism implemented, which lets you change the default user state to premium. Otherwise, you will not be able to keep developing your app in the simulator. IOS does not offer demo purchases inside the simulator. Which means everytime you want to work on that premium content you would then have to switch to a real device, which can be quite inconvenient at times.
