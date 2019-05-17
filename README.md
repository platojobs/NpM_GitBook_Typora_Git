# NpM_GitBook_Typora_Git
NpM_GitBook_Typora_Git组合使用

### GitBook 是基于 Node.js，所以我们首先需要安装 Node.js

[Node.js]()

+ 现在安装 `Node.js` 都会默认安装 `npm（node 包管理工具）`，所以我们不用单独安装 `npm`，打开命令行，执行以下命令安装 `GitBook`
```linux
npm install -g gitbook-cli
```
+ 安装Typora
[Typora](https://typora.io) 切记需要翻墙



```linux

Last login: Wed May 15 11:47:58 on ttys000
macdeMacBook-Air:~ mac$ npm --version
-bash: npm: command not found
macdeMacBook-Air:~ mac$ npm help
-bash: npm: command not found
macdeMacBook-Air:~ mac$ npm install -g gitbook-cli
-bash: npm: command not found
macdeMacBook-Air:~ mac$ npm install -g gitbook-cli
npm WARN checkPermissions Missing write access to /usr/local/lib/node_modules
npm ERR! path /usr/local/lib/node_modules
npm ERR! code EACCES
npm ERR! errno -13
npm ERR! syscall access
npm ERR! Error: EACCES: permission denied, access '/usr/local/lib/node_modules'
npm ERR!  [Error: EACCES: permission denied, access '/usr/local/lib/node_modules'] {
npm ERR!   stack: "Error: EACCES: permission denied, access '/usr/local/lib/node_modules'",
npm ERR!   errno: -13,
npm ERR!   code: 'EACCES',
npm ERR!   syscall: 'access',
npm ERR!   path: '/usr/local/lib/node_modules'
npm ERR! }
npm ERR! 
npm ERR! The operation was rejected by your operating system.
npm ERR! It is likely you do not have the permissions to access this file as the current user
npm ERR! 
npm ERR! If you believe this might be a permissions issue, please double-check the
npm ERR! permissions of the file and its containing directories, or try running
npm ERR! the command again as root/Administrator (though this is not recommended).

npm ERR! A complete log of this run can be found in:
npm ERR!     /Users/mac/.npm/_logs/2019-05-17T02_23_14_256Z-debug.log
macdeMacBook-Air:~ mac$ sudo chown -R $USER /usr/local
Password:
macdeMacBook-Air:~ mac$ npm install -g gitbook-cli
/usr/local/bin/gitbook -> /usr/local/lib/node_modules/gitbook-cli/bin/gitbook.js
+ gitbook-cli@2.3.2
added 578 packages from 672 contributors in 28.567s


```
