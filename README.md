# Paths to Tree

## Overview

**Paths to Tree** is an intuitive web application that dynamically converts a list of file paths into a hierarchical tree structure. This tool visually represents file directories, making it easier to understand and navigate complex file systems.

## Features

- 🌳 **Dynamic Tree Building**: Automatically generate a tree structure from file paths entered by the user.
- ✍️ **Interactive Input**: Users can input file paths through a text area and build the tree with a single click.
- 🔄 **Real-Time Visualization**: The tree updates instantly when new paths are added.
- 🎨 **Customizable Styling**: Clean and minimal design with easy-to-modify CSS.
- ⚡ **Lightweight and Fast**: Built using pure HTML, CSS, and JavaScript, with no external dependencies.

## Preview

### Input Example:
plaintext
/home/kars/pics
/home/kars/videos/kars
/home/kars/videos/pelums
/home/pelums/pics
/bin
/etc


📝How It Works
Tree Construction:
A Tree class manages the root node and child nodes.
Each file path is split by / and added node by node.
DOM Manipulation:
The tree structure is converted into nested div elements with classes for styling.
Dynamic Interaction:
Users input file paths in a textarea, and the tree is built with a button click.

👨‍💻Code Structure
Key Components
Node Class: Represents individual directories or files with properties for value and children.

Tree Class: Manages the root node and handles adding file paths and traversing the tree to render the visualization.

Event Listeners: Captures user input from the textarea and triggers the tree-building process.

