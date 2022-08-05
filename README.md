<h1 align="center">
Alfred Workflows
</h1>

```markdown
Date: July 23, 2022  
Author: Parth Desai  
Source: https://kbase.vercel.app/alfred_workflows  
Summary: My favourite Alfred workflows and commands to trigger them  
Tags: Productivity, List, Mac
```

1. [Alfred Github](https://github.com/gharlan/alfred-github-workflow) : GitHub Workflow for Alfred
    - Commands
        
        ```bash
        # Github repository commands
        gh user/repo
        gh user/repo #123
        gh user/repo @branch
        gh user/repo *commit
        gh user/repo /path/to/file
        gh user/repo admin
        gh user/repo clone
        gh user/repo graphs
        gh user/repo issues
        gh user/repo milestones
        gh user/repo network
        gh user/repo new issue
        gh user/repo new pull
        gh user/repo projects
        gh user/repo pulls
        gh user/repo pulse
        gh user/repo releases
        gh user/repo wiki
        gh user/repo projects
        gh user/repo actions
        
        # User commands
        gh @user
        gh @user overview
        gh @user repositories
        gh @user stars
        gh @user gists
        
        # Search commands
        gh s repo
        gh s @user
        
        # My commands
        gh my dashboard
        gh my notifications
        gh my profile
        gh my issues
        gh my issues created
        gh my issues assigned
        gh my issues mentioned
        gh my pulls
        gh my pulls created
        gh my pulls assigned
        gh my pulls mentioned
        gh my pulls review requested
        gh my repos
        gh my settings
        gh my stars
        gh my gists
        
        # Workflow commands
        gh > login
        gh > logout
        gh > delete cache
        gh > delete database
        gh > update
        gh > activate autoupdate
        gh > deactivate autoupdate
        gh > help
        gh > changelog
        ```
        
2. [Night Shift](https://github.com/shmulvad/alfred-nightshift) : Quickly turn on/off Night Shift
    - Commands
        
        ```bash
        # Turn Night Shift on
        night on
        
        # Turn Night Shift off
        night off
        
        # Set color temperature
        night 85
        ```
        
3. [Alfred Emoji](https://github.com/jsumners/alfred-emoji) : Search for emoji and copy them to the clipboard
    - Commands
        
        ```bash
        # Search for emoji
        emoji [query]
        ```
        
4. [VSCode](https://github.com/alexchantastic/alfred-open-with-vscode-workflow) : Alfred 5 workflow for opening files or folders in Visual Studio Code
    - Commands
        
        ```bash
        # Open folder in VS Code
        vscode
        
        # Open path in VS Code
        vscode ~/Desktop
        
        # Search for a file or folder (Press Enter after this command)
        vscodef
        ```
        
5. [NewPath](https://github.com/vitorgalvao/alfred-workflows/tree/master/NewPath) : Create new file
    - Commands
        
        ```bash
        # Create new file
        nf filename.txt
        
        # Create and open new file
        nfo filename.txt
        
        # Create new folder
        nd foldername
        
        # Create and open new folder
        nfo foldername
        ```
        
6. [Alfred Words](https://github.com/epilande/alfred-words) : Find synonyms and antonyms
    - Commands
        
        ```bash
        # Find synonyms
        syn word
        
        # Find antonyms
        ant word
        ```
        
7. [Notion Search](http://www.packal.org/workflow/notion-search) : An Alfred workflow to search Notion with instant results
    - Commands
        
        ```bash
        # Search Notion
        ns filename
        ```
        
8. [Timer Alfred Workflow](https://gitlab.com/alexives/timer-alfred-workflow/) : A very simple timer workflow
    - Commands
        
        ```bash
        # Create a timer with a message
        timer 3m Start the work
        timer 5d 3h 2m 15s
        timer <time> [label](optional)
        
        # View timers
        timers
        
        # Time formats can be one of the followings:
        # 3s
        # 3sec
        # 3secs
        # 3second
        # 3seconds
        # 3m
        # 3min
        # 3mins
        # 3minute
        # 3minutes
        # 3h
        # 3hour
        # 3hours
        ```
        
9. [Edge Bookmarks](https://github.com/mdreizin/chrome-bookmarks-alfred-workflow) : Microsoft Edge bookmarks search workflow for Alfred
    - Commands
        
        ```bash
        # Open bookmark
        ms bookmark_name
        ```
        
10. [Alfred Terminal Finder](https://github.com/LeEnno/alfred-terminalfinder) [](https://github.com/mdreizin/chrome-bookmarks-alfred-workflow): Alfred workflow to open current Finder window in Terminal or iTerm and vice versa
    - Commands
        
        ```bash
        # Open current Finder directory in Terminal
        ft
        
        # Open current Terminal directory in Finder
        tf
        
        # Open current Finder directory in iTerm
        fi
        
        # Open current iTerm directory in Finder
        if
        ```
        
11. [Recent Downloads](https://github.com/nikitavoloboev/small-workflows/blob/master/augmentations/Recent%20Downloads.alfredworkflow?raw=true) : View `Downloads` folder from Alfred and action on contents of it
    - Commands
        
        ```bash
        # Browse Downloads folder
        downloads
        
        # Reveal File in folder
        downloads + ⇧
        
        # Trash files in Downloads folder
        downloads + ⌘
        
        # Open file in VS Code
        downloads + Fn
        ```
        
12. [Google Apps](https://github.com/PierBover/AlfredWorkflowGoogleApps) : A simple workflow for accessing Google Apps
    - Commands
        
        ```bash
        # Easy access
        `books` to open your Google Play Books
        `books store` to the Google Play Store
        `calendar` to open Google Calendar
        `contacts` to open Google Contacts
        `docs` to open Google Docs
        `drive` to open Google Drive
        `forms` to open Google Forms
        `gmail` to open Gmail
        `inbox` to open Google Inbox
        `music` to open Google Play Music
        `keep` to open Google Keep
        `passwords` to open Google Passwords
        `photos` to open Google Photos
        `slides` to open Google Slides
        `sheets` to open Google Sheets
        
        # New document
        `new doc` to create a new Google Doc
        `new sheet` to create a new Google Sheet
        `new slide` to create a new Google Slide
        `new form to` create a new Google Form
        
        # Search
        `music` to search Google Play Music
        `contacts` to search Google Contacts
        ```
        
13. [File Actions](https://github.com/nikitavoloboev/small-workflows/tree/master/file-actions) : Search folders from Alfred and open them in Finder/iTerm/Editor
    - Commands
        
        ```bash
        # Simply find the file/folder and press right arrow key 
        ```
        
14. [Search Folders](https://github.com/nikitavoloboev/small-workflows/tree/master/folder-search) [](https://github.com/nikitavoloboev/small-workflows/blob/master/augmentations/Recent%20Downloads.alfredworkflow?raw=true): Search folders from Alfred and open them in Finder/iTerm/Editor
    - Commands
        
        ```bash
        # Search folders
        fo
        ```
        
15. [Learn Anything](https://github.com/nikitavoloboev/alfred-learn-anything) [](https://github.com/nikitavoloboev/small-workflows/blob/master/augmentations/Recent%20Downloads.alfredworkflow?raw=true): Alfred workflow to search Learn Anything
    - Commands
        
        ```bash
        # Search
        learn
        ```
        

# Frequently Used Commands

```bash
# Open Alfred Preferences
preferences

# Follow keyword with a search term to open a file
open

# Follow a space with a search term to open a file
`spacebar`

# Follow keyword with a search term to reveal a file in the Finder
find

# Follow keyword by a word and get a definition
define

# Type a calculation into main window to get the result
13*567

# Empty Trash
emptytrash

# Restart your Mac
restart

# Enter command in Terminal
> sudo xattr -rd com.apple.quarantine /Applications/Alfred\ 5.app
```
