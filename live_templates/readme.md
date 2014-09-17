# Live Tempaltes for PhpStorm
###(works perhaps with WebStorm, too)

# what does it do?
basically live templates are custom shortcuts for emmet  
![demo](https://raw.githubusercontent.com/vanilla-thunder/OXID-gimmicks-for-PhpStorm/master/live_templates/screenshot.png)

## contents:

**oxcms**  
`[{oxcontent ident=""}]`

**oxifcms**  
`[{oxifcontent ident="" object="oCont"}]`  
`[{$oCont->oxcontents__oxcontent->value}]`  
`<a href="[{$oCont->getLink()}]" rel="nofollow">[{$oCont->oxcontents__oxtitle->value}]</a>`  
`[{/oxifcontent}]`

**oxmi**  
`[{oxmultilang ident=""}]`

# installation
copy the xml files into the live templates directory
* Windows: <your home directory>\.<product name><version number>\config\templates
* Linux: ~\.<product name><version number>\config\templates
* OS X: ~/Library/Preferences/<product name><version number>/templates
