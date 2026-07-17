![Candy Arts Logo](Logo.png)

Welcome to Candy Arts, the creator of the powerful Candy Dialogue Engine! This readme will be updated with news about our assets. Please watch the repository to stay updated.

**Official links for your convenience:**

[Official website](www.candy-arts.com) | [Discussions](https://github.com/Candy-Arts/Candy-Arts/discussions) | [Youtube channel](https://www.youtube.com/@CandyArtsStudio/playlists)  | [Gumroad](https://candyarts.gumroad.com/)

## News
### Candy DE and DC 1.1 have released

1.1 means the end of Early Release/Beta, and it brings new features and fixes.

**Some highlights:**
- Installing Candy DE is now much easier: drop files/folders in your project, then run a script that automates everything.
- Updating is also easier, with much less risk of overwriting custom modifications to scripts and scenes.
- Candy DC was entirely rebuilt from the ground up! The UI is more ergonomic and no longer limits the amount of data in Candy DE Commands.
- Condition Commands can now run Spoken Lines or any Commands directly, except other condition commands (use §Jump or §Bridge for nested conditions, same as 1.0).
- Variables can now be stored/read to/from external files. This can allow you to virtually create new variables at runtime.
- It's now very easy to create new variant tags (like _S: or _P:).
- Engine instances can use their own language instead of the general language setting.
- Operators for commands such as §Set or §Flag have been re-worked, had their functionalities extended, and are properly documented (see Operators.pdf).
- New §Player_Advance Command: makes dialogue pause until the player presses the Dialogue_Advance key. Another input action can be assigned in the engine settings.
- New §CS_Look Command: rotates nodes to face towards other nodes (can be configured to face away from nodes too).

Note that if you upgrade from 1.0 to 1.1, Candy DC features a Converter Tool to upgrade your dialogues (1.0 dialogues are not compatible with Candy DE/DC 1.1 without upgrading). Candy DC saves and Presets can also be upgraded.

Youtube videos were also remade: the 1.0 videos are no longer available, and new videos for 1.1 were published. These videos cover all the basic and intermediate features.
As a reminder, our videos provide a visual demonstration of how to use various features, and are not updated frequently. For the most complete and up-to-date information, always refer to the written documentation (PDF guides).

Please see our [discussion post](https://github.com/Candy-Arts/Candy-Arts/discussions/13) and share your thoughts, ideas or requests.

### New "Extras" Repository
In other news, we have created the ["Extras" repository](https://github.com/Candy-Arts/Extras), where you can find bonus content for Candy Arts assets, as well as their respective documentation.

This allows us to frequently make minor updates, such as documentation changes, without publishing full releases.

**Note that this is the best place to always find the most up-to-date documentation.**
