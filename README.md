Sublime Text 3
=====================
Sublime Text 3 is currently in beta. The latest build is 3083.For notification about new versions,follow [sublimehq](http://https://twitter.com/sublimehq) on twitter.

###Download
- Download link: [Sublime](http://www.sublimetext.com/3)

###Install package (or After download)
I think every sublimer should do the following steps just after download.

- Click 'View' on the navigation bar or just ctrl(command) + ` and then the console will come out.

- Input the latter python codes and enter.

- Ctrl+Shift+P.Input 'install' and select Install Package.

- Finished. 

####Code
import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); 
open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 
'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())

###Copyright(Sorry,I don't have)
Just follow [ZandyWho](http://twitter.com/ZandyWho) on twitter for more details.