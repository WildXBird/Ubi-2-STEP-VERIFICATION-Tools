# Google-Authenticator-by-r6sg
一个仿照谷歌身份验证器的具有相同功能的，基于html的安卓/ios APP
完全使用HTML和JS，但是，得用apicloud进行编译，因为用到了很多apicloud里面的私有api
主要是套个皮，使得其变得可用，核心算法部分使用了 https://github.com/wuyanxin/totp.js 的代码
html/main.html里面有一个我网站的私有接口“https://technical-test-server.r6sground.cn/r6sg-app/ug/key.php?key=” ，不建议使用，因为随时可能被调整或下线
软件本身和谷歌身份验证器一样都是离线存储，但源代码里有遗留部分在线解密的代码，不过实际上他们并不会被触发。
