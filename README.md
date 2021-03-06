# new-machine


Terminal:
- I use [iTerm2](https://www.iterm2.com/) instead of the Stock terminal Mac app
- I use [oh-my-zshell](https://github.com/robbyrussell/oh-my-zsh)
- I use [Solarized Dark](http://ethanschoonover.com/solarized) for the terminal colors
- I use [powerline-shell](https://github.com/milkbikis/powerline-shell) to get those cool path bars. I usually hide the host name and the user, before running `python ./setup.py install`, edit the config file and comment out `username`, `hostname`
- I use the [Meslo Powerline Font](https://github.com/powerline/fonts/blob/master/Meslo%20Slashed/Meslo%20LG%20M%20Regular%20for%20Powerline.ttf) as you need a font that supports the directory characters for `powerline`
- Commands:
  - find and delete file: > `find . -name AnalyticsElementId.swift.orig && rm   ./Dott/Common/Analytics/AnalyticsElementId.swift.orig`
  - or one command : > `sudo find / -iname ".file-to-delete"  -exec rm {} \;`
  - `search in terminal`: 
    When using Bash, type `Control-R` and then start typing. Typing `Control-R` repeatedly after inputting some text will move you back in matching command lines.


Git: 
- think like a git http://think-like-a-git.net/
- git tips and tricks https://github.com/git-tips/tips#everyday-git-in-twenty-commands-or-so
- git - the simple guide https://rogerdudler.github.io/git-guide/
- git cheat sheet https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf
- I use https://github.com/kamranahmedse/git-standup to recall what i did om the last working day
- Checkout current remote branch and reset local changes "git checkout -- ."
- Clean/discard/delete untracked files `git clean -d -x -f`
- PR from terminal https://hub.github.com/
- git checkout Develop -- theFileYouWantToRevert
- Revert to a commit:  >> git revert --no-commit 0766c053..HEAD
                       >> git commit
- git stash apply
- List all conflicted files in git -> git diff --name-only --diff-filter=U 
- https://hub.github.com/
- https://gitmoji.dev/ An emoji guide for your commit messages

Xcode: 
  - Extenstions:
      - Xcode Mock generator extenstion https://github.com/seanhenry/SwiftMockGeneratorForXcode
      - Sort files by default https://stackoverflow.com/questions/31532460/how-to-automatically-sort-by-name-in-xcode-project
  - Unit test: 
     - Shortcuts https://www.mokacoding.com/blog/xcode-testing-shortcuts/
  - Xcode tips 
    - Tip: If you use the rename refactoring in Xcode a lot, you can save some time by skipping the code folding animation:         defaults write http://com.apple.dt.Xcode CodeFoldingAnimationSpeed -int 0
    - Xcode colors: https://github.com/robbiehanson/XcodeColors/blob/master/README.markdown
    - speed development: https://cocoacasts.com/five-xcode-tips-to-speed-up-your-development
    - Shortcuts [Xcode shortcuts](/Shortcuts.md)
    - Line sorter https://github.com/V8tr/LinesSorter-Xcode-Extension

SCRUM/JIRA:
[epic vs story vs task](/Scrum.md)


  Misc: 
  
    - generate .Gif from screen recording https://www.cockos.com/licecap/
    - validate regex expression https://regex101.com/ 
    - https://probot.github.io/apps/lock/
    - Custom: Icons8 https://icons8.com/ouch and unDraw https://undraw.co 
    - Stock: Pixabay, Unsplash + post-processing with Figma
    - draw.io for diagrams
    - https://undraw.co/ for colorful illustration 
