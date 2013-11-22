## Files in this git repo will help you to install MS SQL2008R2 and IIS services on Windows Server 2012.



Before using them, do actions below in PowerShell as Administrator:
* Install Chef Client <code>msiexec /qn /i  http://www.opscode.com/chef/install.msi</code>
* Make the directory <code> new-item c:\tmp -itemtype directory </code>
* Download and install Git <code> Invoke-WebRequest http://msysgit.googlecode.com/files/Git-1.8.4-preview20130916.exe -OutFile c:\chef\git-1.8.4.exe </code>
* <code> C:\tmp\git-1.8.4.exe</code>
* <code> Get-ChildItem -Path c:\tmp -Recurse -Force</code>
* Open Git bash and download this git repo <code>git clone https://github.com/stamak/winchefsolo.git /c/chef/</code>
* Then again in PS enter command: <code> C:\opscode\chef\bin\chef-solo -c C:\chef\solo.rb -j C:\node.json</code>
