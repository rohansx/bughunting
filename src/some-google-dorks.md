site:WEBSITE ext:php inurl:?<br>
Disclosed XSS and Open Redirects<br>

site:WEBSITE inurl:reports intext:"WEBSITE"<br>
Juicy Extensions<br>

site:"WEBSITE" ext:log | ext:txt | ext:conf | ext:cnf | ext:ini | ext:env | ext:sh | ext:bak | ext:backup | ext:swp | ext:old | ext:~ | ext:git | ext:svn | ext:htpasswd | ext:htaccess<br>
Code Leaks<br>

site:pastebin.com "ccsuniversity.ac.in"<br>
site:jsfiddle.net "ccsuniversity.ac.in"<br>
site:codebeautify.org "ccsuniversity.ac.in"<br>
site:codepen.io "ccsuniversity.ac.in"<br>
Cloud Storage<br>

site:s3.amazonaws.com "ccsuniversity.ac.in"<br>
site:blob.core.windows.net "ccsuniversity.ac.in"<br>
site:googleapis.com "ccsuniversity.ac.in"<br>
site:drive.google.com "ccsuniversity.ac.in"<br>
site:dev.azure.com "ccsuniversity.ac.in"<br>
site:onedrive.live.com "ccsuniversity.ac.in"<br>
site:digitaloceanspaces.com "ccsuniversity.ac.in"<br>
site:sharepoint.com "ccsuniversity.ac.in"<br>
site:https://lnkd.in/e8YtGqdX "ccsuniversity.ac.in"<br>
site:https://lnkd.in/evKFV7KK "ccsuniversity.ac.in"<br>
site:dropbox.com/s "ccsuniversity.ac.in"<br>
site:box.com/s "ccsuniversity.ac.in"<br>
site:docs.google.com inurl:"/d/" "ccsuniversity.ac.in"<br>
XSS prone parameters<br>

inurl:q= | inurl:s= | inurl:search= | inurl:query= inurl:& site:WEBSITE<br>
Open Redirect prone parameters<br>

inurl:url= | inurl:return= | inurl:next= | inurl:redir= inurl:http site:WEBSITE<br>
SQLi Prone Parameters<br>

inurl:id= | inurl:pid= | inurl:category= | inurl:cat= | inurl:action= | inurl:sid= | inurl:dir= inurl:& site:WEBSITE<br>
SSRF Prone Parameters<br>

inurl:http | inurl:url= | inurl:path= | inurl:dest= | inurl:html= | inurl:data= | inurl:domain= | inurl:page= inurl:& site:WEBSITE<br>
LFI Prone Parameters<br>

inurl:include | inurl:dir | inurl:detail= | inurl:file= | inurl:folder= | inurl:inc= | inurl:locate= | inurl:doc= | inurl:conf= inurl:& site:WEBSITE<br>
RCE Prone Parameters<br>

inurl:cmd | inurl:exec= | inurl:query= | inurl:code= | inurl:do= | inurl:run= | inurl:read= | inurl:ping= inurl:& site:WEBSITE
High % inurl keywords<br>

inurl:config | inurl:env | inurl:setting | inurl:backup | inurl:admin | inurl:php site:WEBSITE<br>
Sensitive Parameters<br>

inurl:email= | inurl:phone= | inurl:password= | inurl:secret= inurl:& site:WEBSITE<br>
JFrog Artifactory<br>

site:jfrog.io "WEBSITE"<br>
Firebase<br>

site:firebaseio.com "WEBSITE"<br>
API Docs<br>

inurl:apidocs | inurl:api-docs | inurl:swagger | inurl:api-explorer site:"WEBSITE"<br>
File upload endpoints<br>

site:WEBSITE ”choose file”<br>
Bug Bounty programs and Vulnerability Disclosure Programs<br>

"submit vulnerability report" | "powered by bugcrowd" | "powered by hackerone"<br>
site:*/security.txt "bounty"<br>
Apache Server Status Exposed<br>

site:*/server-status apache<br>
WordPress<br>

inurl:/wp-admin/admin-ajax.php<br>
Drupal<br>

intext:"Powered by" & intext:Drupal & inurl:user<br>
Joomla<br>

site:*/joomla/login<br>