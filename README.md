# Useful Tools
Tools that helps troubleshoot or build

<h3>Fiddler like chrome tool</h3>
chrome://net-internals/#http2 </br>
Start Logging : chrome://net-export/ </br>
Import Log to view: https://netlog-viewer.appspot.com/#import </br>


<h3>Json/Swagger file manipulate online</h3>
https://jsoneditoronline.org/#left=local.dojehu&right=local.meqike

<h3> Open Host file in Mac </h3>
sudo nano /private/etc/hosts

<h3> Update Host file in Mac </h3>
sudo zsh -c "echo '[ipaddress] [domainName]' >> /etc/hosts"

<h3>Create password protected Zip</h3>
zip -er zipname.zip foldername </br>
MoreInfo: https://www.sysgeeker.com/blog/how-to-create-password-protected-zip-file-on-mac.html </br>

<h3>Install python moodule</h3>
python3 -m pip install openai <br/>

<h3>Get User PrincipleId from Azure Cli</h3>
<p> az ad user list --filter "displayName eq 'Himel Nath'"</p>
<p>grab the "id"</p>

<h3>Quickly Draw on browser</h3>
<p>https://excalidraw.com/ </p>

<h3>Get SiteId from sharepoint</h3>
<p> https://<tenant>.sharepoint.com/sites/<site-url>/_api/site/id</p>
<p>Ref: https://www.sharepointdiary.com/2018/04/sharepoint-online-powershell-to-get-site-collection-web-id.html </p>

<h3>Upadate react versions for all package</h3>
<p> npm audit fix --force</p>
<p> OR </p>
<p> npm update --save</p>
<p>Ref: https://stackoverflow.com/questions/49828493/upgrading-react-version-and-its-dependencies-by-reading-package-json </p>

<h3>Upadate react specific versions</h3>
<p> npm install --save @fluentui/react-icons@latest</p>
<p>Ref: https://stackoverflow.com/questions/49828493/upgrading-react-version-and-its-dependencies-by-reading-package-json </p>

