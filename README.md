App updater for Cordova/PhoneGap

本插件在[ cordova-plugin-app-update](https://github.com/vaenow/cordova-plugin-app-update) 的基础上修改的，主要修改内容：
> 1. 提示框中加入了更新详情。
> 2. 加入是否强制更新 取消按钮
> 3. 在原插件配置文件中加入了 `<remark></remark>` 标签，来配置更新内容提示。 
> 4. 在原插件配置文件中加入了 `<force></force>` 标签，来配置是否有取消按钮。
# Install

> `cordova plugin add https://github.com/qitianhuoshen/cordova-plugin-app-update --save`