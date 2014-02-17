# textabyss
A pannable, zoomable 2D text plane for [vim](http://www.vim.org) for working on a lifetime's worth of prose. Navigate with the mouse, keyboard, or via a map. **[Check out the youtube video](http://www.youtube.com/watch?v=QTIaI_kI_X8).**

![Panning](https://raw.github.com/q335r49/textabyss/gh-pages/images/ta2.gif)     .     ![Map](https://raw.github.com/q335r49/textabyss/gh-pages/images/tamap.png)

#####Purpose
In a time when memory capacity is growing exponentially, memory organization, especially when it comes to prose, seems quite underdeveloped. Text production even on the order of kilobytes per year may still seem quite unmanageable. Depending on how prolific you are, you may have hundreds or thousands of pages sitting in mysteriously named folders on old hard drives. There are various efforts to remedy this situation including desktop indexing and personal wikis. It might not even be a bad idea to simply print out and keep as a hard copy everything written over the course of a month. 

The textabyss is yet another solution. It presents a plane that one can append to endlessly with very little overhead. It provides means to navigate and, either at the moment of writing or retrospectively, map out this plane. Ideally, you would be able to scan over the map and easily access writings from last night, a month ago, or even 5 or 10 years earlier. It presents some unique advantages over both indexing and hyperlinked or hierarchical organizing.

#####Installation
Download [nav.vim](https://raw.github.com/q335r49/textabyss/master/nav.vim), open vim, and type `:source nav.vim`. Once sourced, press **F10** to begin. Help is baked in, usually by pressing **F1** after **F10**. Earlier releases can be found at [vim.org/scripts](http://www.vim.org/scripts/script.php?script_id=4835) or under the releases tab.

#####Roadmap
**1.6** Syntax for map labels to allow for precisely locating the view and cursor after a jump  
**1.7** Change map background color based on depth >:-)  
**1.8** minimap - option to allow map to take up small area of screen, have panning follow map navigation  
**1.9** Commands to realign grid when editing pushes text down and misaligns the splits by deleting blank lines  
