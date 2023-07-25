# WPS Linux Fonts
WPS for Linux字体缺失

## 安装方法


Clone the Git repository.
```
git clone https://github.com/bianjunwei/wps-fonts.git
```

拷贝字体到 usr/share/fonts
```
sudo cp -r wps-font/ /usr/share/fonts/wps-office
```
权限配置
```
cd /usr/share/fonts

sudo chmod 755 wps-office

cd /usr/share/fonts/wps-office

sudo chmod 755 *

```
生成字体缓存信息

```
cd /usr/share/fonts/wps-office

sudo mkfontdir

sudo mkfontscale

sudo fc-cache
```
### 重启WPS

