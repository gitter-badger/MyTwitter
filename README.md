# MyTwitter Powershell Module
- - -
The MyTwitter Powershell module is a module created to interact with Twitter.  It uses Twitter's OAuth API to tweet, send direct messages and hopefully more functionality is to come!

09/30/14 - Added proper special character handling/escaping function and integrate.  

09/30/14 - Fixed exporting the Set-OAuthAuthorization function so that operator can manually set up registry entries by calling the function.  

09/30/14 - Fixed syntax error line 87 from master pull missing colon.

10/08/14 - Added Pester test for Split-Tweet function. I would suggest we create more tests later.
![ScreenShot](https://raw.githubusercontent.com/MyTwitter/MyTwitter/master/PesterSplitTweet.gif)

# Install
To install the module including all source code you can just run in a PowerShell v3 or higher the following command:
<pre>
iex (New-Object Net.WebClient).DownloadString("https://gist.githubusercontent.com/stefanstranger/2138dc710576bc40b64b/raw/bfd25a0e7363e9a1906908b0695ebcffaa508276/InstallMyTwitterModule.ps1")
</pre>
