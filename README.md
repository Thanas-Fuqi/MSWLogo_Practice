# MSWLogo Projects

[**MSWLogo**](https://en.wikipedia.org/wiki/MSWLogo) is a Windows application that uses its own programming language syntax, which I hadn't encountered before. Despite my initial impression that it seemed like a "ripoff of Python's turtle module," I soon realized that it has its own unique way of functioning.

Much like Python's turtle, you control a pen (represented by a triangle) in a 2D space, issuing commands to move it around. The logic of the operations is quite similar, but MSWLogo focuses entirely on the turtle, making it a simpler and less distracting environment for beginners.

The syntax for turtle movement is straightforward, with commands resembling Python’s turtle commands (e.g., moving forward by a number of steps). However, the more challenging aspects of the language arise when introducing logic into your programs. MSWLogo includes built-in capabilities for handling variables, arrays, saving, 3D graphics, and more.

I experimented with array manipulations to create a version of [**Conway's Game of Life**](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life), and I found it quite challenging at first. While arrays operate under familiar principles, the syntax can take time to get used to. [**Go to folder>>**](./GAME_OF_LIFE/)

Aside from this, I also created a design using [**lines**](./Line_Patterns/) and ported a simple game I developed: a 2-player version of [**Agar.io**](https://agar.io/?). While functional, this game remains buggy due to version-specific issues in MSWLogo. Some versions, for instance, don’t allow the `setPen` command to modify keybindings, making it difficult to control input for different players.
