1. 将需要的字体文件拖到项目里面去
2. 点击字体文件，右侧的 Target Membership 中要勾选对应的 target，确保会被打包到。
3. 点击整个项目选项，在 Info 中添加 Fonts provided by application，然后增加两项，将字体文件名作为value输入进去。
这一步注意，不是 Info.plist 哦，而是项目选项中的 General | Signing & Capabilities | Resource Tags | Info | Build Setting | Build Phases | Build Rule 这些选项中的【Info】

4. 然后就可以在项目中使用了，需要知道字体的名字
