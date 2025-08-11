---
weight: 1
bookFlatSection: true
title: ""
---
# folder-alias extension

## VSCode extension link
[folder-alias](https://marketplace.visualstudio.com/items?itemName=rikka.folder-alias)

## Rating (1 to 5 stars)
⭐️⭐️⭐️⭐️⭐️

## category
code reading

## Summary
Adds annotations to the right of folders and files in the Explorer.

## Usage
1. Right-click the folder or file you want to add a remark (alias) for.
2. Select "Add Alias".
3. Enter the remark and press Enter.
4. The remark will appear in the file tree.

You can manage remarks in either of the following ways:

1. Right-click the file or folder, select "Add Alias", and enter the desired remark.
2. Right-click the file or folder, select "Add Alias", and modify an existing remark.

## How it works
The extension automatically creates a `folder-alias.json` file in your project. It is a JSON file. If you edit this file directly, run the VS Code command "Developer: Reload Window" to refresh the annotations.

```json
{
  "LICENSE": {   // folder or file
    "description": "Open source license" // annotation to display
  }
}
```