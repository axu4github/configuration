### 03.SublimeText配置说明

#### 安装 `Package Control`

官网安装链接：`https://packagecontrol.io/installation`

进入`SublimeText`后按``` ctrl+` ```输入如下内容按回车

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

