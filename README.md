# fcitx5-dracula-theme


----
## Noramal
![](./shot/normal_shot1.png)  
![](./shot/normal_shot2.png)  

## Transparent
![](./shot/trans_shot1.png)  
![](./shot/trans_shot2.png)  


## 使用步骤
将整个项目clone到本地：

```
mkdir -p ~/.local/share/fcitx5/themes/dracula
git clone https://github.com/drbbr/fcitx5-dracula-theme.git ~/.local/share/fcitx5/themes/dracula
```

修改配置文件：  
` vim ~/.config/fcitx5/conf/classicui.conf `
添加以下参数：  

```
# 垂直候选列表
Vertical Candidate List=False

# 按屏幕 DPI 使用
PerScreenDPI=True

# Font (设置成你喜欢的字体)
Font="思源黑体 CN Medium 13"

# 主题
Theme=dracula

```
