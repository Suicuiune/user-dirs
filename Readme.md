### Directory Structure Standard

My files structures always end up devolving into a disgusting tangled mess of folders with no or multiple places where one file should go and massive temp and download folders where basically everything goes.
That's why I am trying to create one standard for how i organise my files, so that I can use that on multiple machines and always know where my files are.

Some conventions on directory naming:
- Directories use `kebab-case`, except for top-level directories in the main user directory, which uses `Capitalized-Kebab-Case`, to preserve compatibility with the default Directories, e.g. `Downloads, Documents, Desktop, etc.`
- Umlauts are spelled as ae, ue or oe

The structure should look like this:

```
User Directory
|
|- .config
|
|- Archive
|
|- Downloads
|
|- Media
|  |
|  |- audio
|  |  |
|  |  |- music
|  |
|  |- images
|
|- Symlinks
|
|- Sync
|  |
|  |- documents
|  |
|  |- media
|  |  |
|  |  |- audio
|  |  |  |
|  |  |  |- [interpret]
|  |  |  |
|  |  |  |- random
|  |  |  |
|  |  |  |- unsorted
|  |  |
|  |  |- images
|  |  |  |
|  |  |  |- backgrounds
|  |  |  |
|  |  |  |- camera
|  |  |  |
|  |  |  |- fun 
|  |
|  |- obsidian
|  |  |
|  |  |- [vault]
|  |
|  |- temp
|
|- Uni
|  |
|  |- semester-[number]
|  |  |
|  |  |- [course]
|  |  |  |
|  |  |  |- lecture-notes
|  |  |  |
|  |  |  |- projects
|
|- Temp
```