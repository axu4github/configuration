### 03.SublimeText配置说明

#### 安装 `Package Control`

> 官网安装链接：`https://packagecontrol.io/installation`

进入 `SublimeText` 后按 ``` ctrl+` ``` 输入如下内容按回车

```
import urllib.request,os,hashlib; h = 'df21e130d211cfc94d9b0905775a7c0f' + '1e3d39e33b79698005270310898eea76'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```

#### 安装流程

```bash
# 按照上文安装`Package Control`

# 下载插件
> cd /Users/axu/code/axuProject
> pwd
/Users/axu/code/axuProject

> git clone https://github.com/axu4github/configuration.git
> cd /Users/axu/code/axuProject/configuration/03.SublimeText
> ll
total 8
drwx------  11 axu  staff   374  4  8 22:19 Packages
-rw-r--r--   1 axu  staff  1562  4  8 22:23 README.md

# 备份插件
> cd /Users/axu/Library/Application\ Support/Sublime\ Text\ 3/
> ll
total 0
drwxr-xr-x  35 axu  staff  1190  3 22 09:52 Backup
drwx------  54 axu  staff  1836  9  2  2016 Cache
drwxr-xr-x  30 axu  staff  1020  4  8 22:23 Index
drwx------  11 axu  staff   374  4  4 13:32 Installed Packages
drwx------   4 axu  staff   136  4  8 22:25 Local
drwx------  10 axu  staff   340  4  4 12:35 Packages

> mv Packages Packages.raw
> ll
total 0
drwxr-xr-x  35 axu  staff  1190  3 22 09:52 Backup
drwx------  54 axu  staff  1836  9  2  2016 Cache
drwxr-xr-x  30 axu  staff  1020  4  8 22:23 Index
drwx------  11 axu  staff   374  4  4 13:32 Installed Packages
drwx------   4 axu  staff   136  4  8 22:27 Local
drwx------  10 axu  staff   340  4  8 22:27 Packages.raw

# 拷贝插件
> cp -r /Users/axu/code/axuProject/configuration/03.SublimeText/Packages ./
> ll
total 0
drwxr-xr-x  35 axu  staff  1190  3 22 09:52 Backup
drwx------  54 axu  staff  1836  9  2  2016 Cache
drwxr-xr-x  30 axu  staff  1020  4  8 22:23 Index
drwx------  11 axu  staff   374  4  4 13:32 Installed Packages
drwx------   4 axu  staff   136  4  8 22:28 Local
drwx------  11 axu  staff   374  4  8 22:28 Packages
drwx------  10 axu  staff   340  4  8 22:27 Packages.raw
```

#### 插件列表

- [Package Control](https://packagecontrol.io/)
- [Anaconda](https://packagecontrol.io/packages/Anaconda)
- [HTML-CSS-JS Prettify](https://packagecontrol.io/packages/HTML-CSS-JS%20Prettify)
- [OmniMarkupPreviewer](https://packagecontrol.io/packages/OmniMarkupPreviewer)
- [phpfmt](https://packagecontrol.io/packages/phpfmt)
- pygments
- [Python PEP8 Autoformat](https://packagecontrol.io/packages/Python%20PEP8%20Autoformat)
- [pyyaml](https://packagecontrol.io/packages/SublimeLinter-pyyaml)
