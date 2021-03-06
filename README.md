# 一个快速Electron/PWA应用外壳

## 相关技术栈
+ vue
+ vuex
+ vueRouter
+ electron
+ PWA
+ stylus
+ vuetify
+ vue-i18n

## 基础特点

+ Windows、macOS自定义[最小化、最大化、关闭]按钮
+ 支持[亮色主题/暗色主题]自动、手动切换
+ 支持国际化
+ 支持用户自定义主题颜色
+ 自定义美化滚动条
+ Web与Electron同构（如果后续开发也隔离两个环境）

## 功能指引（编辑中）

+ 修改title
+ 修改icon
+ 支持PWA
+ 支持并隔离ELectron api、node api

## TODO

+ drag在Windows下对浮动nav首行的影响
+ 优雅的修改title

## 指令说明

```
# web相关
npm run serve
npm run build

# Electron相关
npm run electron:serve
npm run electron:build

# 修改publish/icon.png后
npm run generate-icons
```

## 参考
+ [vue-cli-plugin-electron-builder](https://nklayman.github.io/vue-cli-plugin-electron-builder/)
+ [@vue/cli-plugin-pwa](https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-pwa)
