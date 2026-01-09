# unibest4-demo
unibest4的demo项目。

## 生成过程 
```sh
pnpm create unibest@latest unibest4-demo
```
```txt
┌  create-unibest@v3.2.1 快速创建 unibest@v4.2.1 项目
│
◇  请选择需要支持的平台（多选）[脚手架将根据所选平台生成对应的平台代码，请根据实际情况选择]
│  H5, 微信小程序, APP
│
◇  请选择UI库
│  wot-ui
│
◇  是否需要登录策略（黑白名单、登录拦截等）？[暂不知道的，选No即可，项目生成后也可以加该策略]
│  Yes
│
◇  是否需要多语言i18n？
│  No
UI 库 wot-ui 配置完成
│
◆  项目unibest4-demo创建成功！
```

## 运行
```sh
pnpm i
pnpm dev
# 第一次运行可以多运行一次 pnpm dev，确保项目正常运行。
# 运行完以上命令后，再运行其他平台
# 如：pnpm dev:mp, pnpm dev:app 等
```