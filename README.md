## 运行
- npm install

1. 本地：npm start
2. 打包：npm run make

## FAQ
1. Electron安装时卡住(reify:@types/node: timing reifyNode:node_ modules/global-agent )
   
    **解决**：npm config edit 编辑配置文件，手动添加： electron_mirror=https://npm.taobao.org/mirrors/electron/

2. 运行 npx electron-forge import 时报错：An unhandled exception has occurred inside Forge:   
Cannot find module '@electron/packager/src/targets' 

    **解决**：降低版本 "@electron-forge/cli": "^6.4.2"
