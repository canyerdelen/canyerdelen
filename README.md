# Hello, I'm Can
```
###### <img src="https://raw.githubusercontent.com/rajput2107/rajput2107/master/Assets/Developer.gif">

- 🎓 UGD - Software Engineering
- 📍  Turkey - North Macedonia                                                                                                                                                                                          
<img src="https://github-readme-stats.vercel.app/api?username=canyerdelen&&show_icons=true&title_color=ffffff&icon_color=bb2acf&text_color=daf7dc&bg_color=000000">           <img            src="https://camo.githubusercontent.com/ddef8026276958745ea60516cc65933525cf1f983f727bb50aa5851e323aac9d/68747470733a2f2f6769746875622d726561646d652d73746174732e76657263656c2e6170702f6170692f746f702d6c616e67732f3f757365726e616d653d6a69707265747479636f6f6c266c61796f75743d636f6d7061637426746578745f636f6c6f723d666539636438267469746c655f636f6c6f723d6665396364382662675f636f6c6f723d30303030303026636f756e745f707269766174653d7472756526696e636c7564655f616c6c5f636f6d6d6974733d7472756526686964655f626f726465723d74727565266c616e67735f636f756e743d3130">
```



# Social Media


[[Instagram]](https://www.instagram.com/canyerdelenn/)
[[Twitter]](https://twitter.com/canyerdelenn0)

Sublime Text 3 plugin providing the following features:

- basic Git functionality; `init`, `add`, `commit`, `amend`, `checkout`, `pull`, `push`, etc.
- inline diff viewing, including quick navigation between modified hunks and the ability to (un)stage files by hunk or by line (respectfully stolen from SourceTree, GitX, et al)
- GitHub integration
    + issue/collaborator referencing when committing
    + opening the current file on GitHub at the selected line
- GitHub-style blame view, showing hunk metadata and ability to view the commit that made the change
- `git diff` view, allowing user to (un)stage hunks across all files
- status, branch, tag, and rebase dashboards

**Note:** GitSavvy requires Git versions at or greater than 2.16.0.

**Note:** Sublime Text 2 is not supported.  Also, GitSavvy takes advantage of certain features of ST3 that have bugs in earlier ST3 releases.  For the best experience, use the latest ST3 dev build.


## Documentation

Feature documentation can be found [here](docs/README.md).  It can also be accessed from within Sublime by opening the command palette and typing `GitSavvy: help`.


## Highlights

<table>
    <tr>
        <th>Inline-diff</th>
        <th>Status dashboard</th>
    </tr>
    <tr>
        <td width="50%">
            <a href="https://cloud.githubusercontent.com/assets/5016978/6471628/886430f8-c1a1-11e4-99e9-883837dba86f.gif">
                <img src="https://cloud.githubusercontent.com/assets/5016978/6471628/886430f8-c1a1-11e4-99e9-883837dba86f.gif" width="100%">
            </a>
        </td>
        <td width="50%">
            <a href="https://cloud.githubusercontent.com/assets/5016978/6704171/2f236466-cd02-11e4-9b7d-22cc880b5e9d.png">
                <img src="https://cloud.githubusercontent.com/assets/5016978/6704171/2f236466-cd02-11e4-9b7d-22cc880b5e9d.png" width="100%">
            </a>
        </td>
    </tr>
    <tr>
        <td width="50%">(Un)stage and revert individual lines and hunks.</td>
        <td width="50%">Display and overview and offer actions to manipulate your project state.</td>
    </tr>
</table>

<table>
    <tr>
        <th>Branch dashboard</th>
        <th>Tags dashboard</th>
    </tr>
    <tr>
        <td width="50%">
            <a href="https://cloud.githubusercontent.com/assets/5016978/6704168/2b2e7b84-cd02-11e4-90f4-8dd96b21edeb.png">
                <img src="https://cloud.githubusercontent.com/assets/5016978/6704168/2b2e7b84-cd02-11e4-90f4-8dd96b21edeb.png" width="100%">
            </a>
        </td>
        <td width="50%">
            <a href="https://cloud.githubusercontent.com/assets/5016978/6704169/2c80beac-cd02-11e4-8940-986ea0f0d6bb.png">
                <img src="https://cloud.githubusercontent.com/assets/5016978/6704169/2c80beac-cd02-11e4-8940-986ea0f0d6bb.png" width="100%">
            </a>
        </td>
    </tr>
    <tr>
        <td width="50%">View and manipulate local and remote branches.</td>
        <td width="50%">View and manipulate local and remote tags.</td>
    </tr>
</table>

<table>
    <tr>
        <th>Github integration</th>
        <th>Rebase dashboard</th>
    </tr>
    <tr>
        <td width="50%">
            <a href="https://cloud.githubusercontent.com/assets/5016978/6704029/8fcaddbe-cd00-11e4-83b6-32276a2c2b65.gif">
                <img src="https://cloud.githubusercontent.com/assets/5016978/6704029/8fcaddbe-cd00-11e4-83b6-32276a2c2b65.gif" width="100%">
            </a>
        </td>
        <td width="50%">
            <a href="https://cloud.githubusercontent.com/assets/5016978/7017776/5ca9ceca-dcb1-11e4-8fcb-552551f7743a.gif">
                <img src="https://cloud.githubusercontent.com/assets/5016978/7017776/5ca9ceca-dcb1-11e4-8fcb-552551f7743a.gif" width="100%">
            </a>
        </td>
    </tr>
    <tr>
        <td width="50%">Reference issues and collaborators in commits.  Open files on GitHub in the browser, with lines pre-selected.</td>
        <td width="50%"> Squash, edit, move, rebase, undo, redo.</td>
    </tr>
</table>


## Installation

### Simple

1. Install the [Sublime Text Package Control](https://packagecontrol.io/) plugin if you don't have it already.
2. Open the command palette and start typing `Package Control: Install Package`.
3. Enter `GitSavvy`.

**Note:** If you're using 64-bit Windows, the path to the Git binary may not be as you expect.  If GitSavvy fails to operate correctly in this configuration, make sure to confirm the Git path you're using in the config.

### Less simple

If you want more control over what you pull down, or if you'd like to submit changes to GitSavvy, you should pull down the repository directly and restart the editor.


# on a Mac
cd "$HOME/Library/Application Support/Sublime Text 3/Packages"
# on Linux
cd $HOME/.config/sublime-text-3/Packages
# on Windows (PowerShell)
cd "$env:appdata\Sublime Text 3\Packages\"

git clone https://github.com/timbrel/GitSavvy.git

# Package Control need to be installed https://packagecontrol.io/installation
# install dependencies from command line
subl --command 'satisfy_dependencies'
# or open Command Palette and run 'Package Control: Satisfy Dependencies'

