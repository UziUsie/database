# Wiki Data for [Unturned DB](https://unturned.wiki)

Thank you for considering to contribute to the Unturned Database and Wiki. Please read the information below carefully before making a pull request.


# Contributing
Most of the item and vehicle data is gathered from Unturned's Game Data files.
However, extra information, text and images can be added to each item by creating a file in the `wiki` folder.

An example file `328.md` for extra information for the item `Locker` with item ID `328`, in [Markdown](https://guides.github.com/features/mastering-markdown/) format:

```markdown
---
id: 328
author: Author Name
---
## Overview
The Locker has the most storage slots of all storages, and is the most durable storage.
It can only be opened by its owner or group members, which makes it useful for players to
store their items in without the risk of theft.

Like all other storages, if the Locker is destroyed, all items inside the Locker
will drop on the ground.
```

## Step by step

1. Fork this repository: https://github.com/unturnedwiki/wiki/fork
2. Commit your changes to your fork.
3. Create a pull request: https://github.com/unturnedwiki/wiki/compare
4. Await approval from your pull request.

## File format
The name of the file should be exactly `{item-id}.md`, where `{item-id}` replaces the ID of the item you're adding extra information for.

```markdown
---
id: {item-id}
author: {author-name}
---
```
The first lines of your file should look like this, where `{item-id}` and `{author-name}` should be replaced respectively with the item ID and your full name.

```markdown
## Overview
First paragraph

Second paragraph
```
The largest header you should use begins with two `##`'s. Paragraphs are separated with a new line. You can use [GitHub Flavoured Markdown](https://guides.github.com/features/mastering-markdown/) in your file.
