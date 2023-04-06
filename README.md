# unity-find-in-prefabs

## Features

Find which prefab files are referenced by C# scripts, similar to the function of Rider.

## Release Notes

### 1.0.9

* Support for finding C# script references from unity scene files.

### 1.0.8

* Add a display button in the sidebar for each result.

### 1.0.7

* The right-click menu only appears in C# files.

### 1.0.6

* Add a preview file button for each result.

### 1.0.5

* Automatically update the cache after adding, deleting or modifying the `prefab` file, and the next search will take effect directly.

### 1.0.4

* Selecting the prefab file of the search result will copy the file name to the clipboard.
* You can see a hint in the status bar during the build cache.
* Add the right-click menu of the file title.

### 1.0.3

* Use `Quick Pick` to display the search results, and then you can easily open a found prefab file.

### 1.0.2

* Create a result cache when you find for the first time, to avoid searching for all files every time.

## 1.0.1

* Even if `files.exclude` contains `prefab` files, they are now found correctly.

## 1.0.0

* Support to find which prefab files are referenced by C# scripts.

## Road Map

* Support for finding other referenced file types.
* Select the search result to open Unity directly.
