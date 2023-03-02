# mct-manager
The Data Pack for running the Minecraft Tournament (MCT) and all its games

This is broken up into directories inside [data/mct-manager/functions/](./data/mct-manager/functions/) that handle the logic and games of MCT.

## Usage
*description of how to use this data pack, including details on setup and which functions to use for what purpose*

## Requirements
You must follow these rules to maintain compatibility across MCT data packs:

- The folder with the `function/` directory must start with `mct-`, match the name of your repository, and be all lowercase. 
    - That way it's easy to keep track of when `/function` commands are trying to use other Data Pack's `.mcfunction`s.
- Ensure your scoreboard names are unique across MCT Data Packs. Otherwise there will be conflicts.
- Describe the purpose of every `.mcfunction` file in a comment at the top
    - use the `#` character at the start of a line to make it a comment


