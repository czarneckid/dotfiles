# Changes to my Sublime Text 2 editor

As I've setup Sublime Text 2 on my home desktop, home laptop, work desktop and work laptop, I wanted to outline the things 
I do immediately with a fresh Sublime Text 2 installation.

## Swap Icon

http://www.sublimetext.com/forum/download/file.php?id=200

On a Mac, browse to Sublime 2 in your Applications/ folder, then right-click and “View Package Contents.” Lastly, browse to Contents/Resources/, and drag the new icon in, overwriting the existing one. 

## Install Textmate Tomorrow Theme

Copy .tmTheme files from https://github.com/ChrisKempson/TextMate-Tomorrow-Theme to `~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User`

## Install Package Control

To install “Package Control,” open Sublime and press Control + `. Next, paste the following snippet into the console.

```python  
import urllib2,os;pf='Package Control.sublime-package';ipp=sublime.installed_packages_path();os.makedirs(ipp) if not os.path.exists(ipp) else None;open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read())
```

## Install Various Packages

* Git plugin
* Sublime linter
* Alignment
* Theme - Soda

## Install RSpec bundle

```
cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
git clone git://github.com/rspec/rspec-tmbundle.git RSpec
```