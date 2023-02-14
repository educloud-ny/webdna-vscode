# WebDNA Language Extension for VSCode Changelog

## (02/13/2023) v-0.2.0:
- Added/updated support for the highlighting of:
    * Contexts: removehtml

## (03/20/2022) v-0.1.2:
- Updated Readme Information
- Added/updated support for the highlighting of:
    * Support tags: realip, thishost, thisport, webserver
    * keyword tags: permredirect

## (01/15/2022) v-0.1.1:
- Updated License and publisher information

## (06/24/2021) v-0.1.0:
- Changed versioning to follow standard semantic versioning.
- Added/updated support for the highlighting of:
    * Keyword Contexts: formvariables, lineitems, listchars, listcookies, listdatabases, listfields, listfiles, listmimeheaders, listpath, listvariables, listwords

## (06/07/2021) v-0.0.8:
- Removed test and dist folders from final vsix package
- Added/updated support for the highlighting of:
    * Contexts: appendfile, ddeconnect, ddesend, decrypt, dos, encrypt, exclusivelock, fileinfo

## (06/05/2021) v-0.0.7:
- Fixed issue with some broken tag highlighting when a recognized parameter was not present
- Added support for highlighting sql code in the 'statement' parameter in the sql context
- Support for highlighting webdna tags only available in the sql, sqlinfo and sqlresult contexts
- Added/updated support for the highlighting of:
    * Support tags: sqldisconnect, sqlrelease
    * Contexts: applescript, boldwords, capitalize, convertchars, convertwords, countchars, countwords, sql, sqlinfo, sqlresult

## (06/03/2021) v-0.0.6:
- Fixed nested comment highlighting
- Fixed issues labeling some capture scopes
- Added repository to package.json
- Added support for the contexts: sqlconnect and sqlexecute
- Added support for highlighting webdna tags only available in the sqlconnect context
- Added support for highlighting sql code in the sqlexecute context

## (06/02/2021) v-0.0.5:
- Updated parameter highlighting to be case insensitive
- Fixed parameter scope issues
- Added/updated support for the highlighting of:
    * Support tags: validcard, findstring, filecompare
    * Support parameters for tags: validcard, findstring, filecompare

## (06/02/2021) v-0.0.4:
- Added basic support for html, css, sql, xml, javascript, and json

## (05/29/2021) v-0.0.3:
- Added/updated support for the highlighting of:
    * Keyword tags: switch, case, hideif, showif, if, then, else, default
    * Keyword parameters for tags: switch, case, redirect
    * Depreciated keyword tags: html1, html2, html3
    * Storage tags: text, math, function
    * Storage parameters for tags: text, math, function
    * Support tags: authenticate, calcfilecrc32, clearlineitems, closedatabase, commitdatabase, copyfile, copyfolder, createfolder, date, deletefile, deletefolder, getcookie, getmimeheader, movefile, protect, purchase, random, renamefile, removelineitem, setcookie, setmimeheader, time
    * Support parameters for tags: authenticate, calcfilecrc32, clearlineitems, closedatabase, commitdatabase, copyfile, copyfolder, createfolder, date, deletefile, deletefolder, getcookie, getmimeheader, movefile, protect, purchase, random, renamefile, removelineitem, setcookie, setmimeheader, time

## (05/28/2021) v-0.0.2:
- Updated patterns to recursivly apply patterns to correctly stylize tags inside tags
- Updated various scope selectors
- Added support for the highlighting of:
    * global tags: username, authenticate, calcfilecrc32, clearlineitems, closedatabase, commitdatabase, copyfile, copyfolder, createfolder, date, delete, deletefile, deletefolder, filecompare, getcookie, getmimeheader, include, lookup, movefile, password, protect, purchase, random, removelineitem, renamefile, setcookie, setmimeheader, time, validcard, findstring
    * keyword tags: if, else, then, redirect, hideif, showif
    * contexts: applescript, capitalize, countchars, ddesend, dos, html1, html2, html3, input, interpret, listdatabases, lineitems, raw, shell, spawn, unurl

## (05/27/2021) v-0.0.1:
- Added support for block comments ([!][/!]) in the language configuration
- Added support for the highlighting of:
    * text and math tags
    * contextual tags: founditems, return, url
    * webdna variables
    * block comments
    * double and single quoted strings
    * global tags: browsername, cart, command, elapsedtime, flushdatabases, flushcache, freememory, httpmethod, ipaddress, issecureclient, lastautonumber, lastrandom, platform, product, random, referrer, referer, thisfile, thisurl, thisurlplusget, version
