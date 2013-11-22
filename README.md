## Files in this git repo will help you to install MS SQL2008R2 and IIS services on Windows Server 2012.



Before using them, do actions below:
* Install Chef Client <code>msiexec /qn /i  http://www.opscode.com/chef/install.msi</code>
* Download this git repo <code>git clone https://github.com/stamak/winchefsolo.git</code>
* Enter command: <code> C:\opscode\chef\bin\chef-solo -c solo.rb -j node.json</code>
