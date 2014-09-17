# Live Tempaltes for PhpStorm
###(works perhaps with WebStorm, too)

# what does it do?
basically live templates are custom shortcuts for emmet  
![demo](https://raw.githubusercontent.com/vanilla-thunder/OXID-gimmicks-for-PhpStorm/master/live_templates/screenshot.png)

# oxid_smarty_functions.xml contents:

**oxcms**  
`[{oxcontent ident=""}]`

**oxifcms**  
`[{oxifcontent ident="" object="oCont"}]`  
`[{$oCont->oxcontents__oxcontent->value}]`  
`<a href="[{$oCont->getLink()}]" rel="nofollow">[{$oCont->oxcontents__oxtitle->value}]</a>`  
`[{/oxifcontent}]`

**oxmi**  
`[{oxmultilang ident=""}]`

# font-awesome.xml contents:
 font awesome brand icons yet, will add other soon

# installation
copy the xml files into the live templates directory
- Windows: `<your home directory>\.<product name><version number>\config\templates`
- Linux: `~\.<product name><version number>\config\templates`
- OS X: `~/Library/Preferences/<product name><version number>/templates`

more info about live tempaltes here:
http://www.jetbrains.com/phpstorm/webhelp/live-templates.html
