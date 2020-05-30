# zhihuishu_course
瞬间完成智慧树课程播放进度，虽然不知道有没有风险（
## 使用方法
### 安装ReRes拓展程序
使用chrome或者chrome edge浏览器打开下方链接（国内可能无法正常访问）
https://chrome.google.com/webstore/detail/reres/gieocpkbblidnocefjakldecahgeeica
如果无法正常访问，请下载本项目里的crx文件手动安装，因为是我在本地打包的，可能会提示拓展损坏，不用管它
### 配置ReRes选项
通过浏览器的 拓展/ReRes/详细信息/拓展选项 进入设置界面
点击"+"按钮，添加新的规则

其中的"If URL match:"填写https://studyh5.zhihuishu.com/static/js/0.c50211d27ef36136e8bb.js

其中的"Response:"填写https://popchicken.github.io/popchicken.github-io/res/zhihuishu_course/0.c50211d27ef36136e8bb.js

含义是拦截原本的文件并置换成修改过的文件

---

### 开始使用
进入智慧树课程播放页面，播放课程后点击左下方的播放下一节的按钮
当播放下一节时，服务器会认为你已经看完了前一节，继续点击按钮即可
右侧的播放完成图标不会立即显示，如要确认已经观看，请刷新页面
