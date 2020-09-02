比如我想来个1.0.1版本，注意，是最后一位修改了增1，那么命令：npm version patch    回车就可以了；

比如我想来个1.1.0版本，注意，是第二位修改了增1，那么命令：    npm version minor    回车就可以了；

比如我想来个2.0.0版本，注意，是第一位修改了增1，那么命令：    npm version major     回车就可以了；


发布到npm远端
npm publish

查看自己的版本
npm view sxd-cli versions

版本1.0.4
创建后台模板
sxd-init admin-template projectName

版本 1.0.5
创建封装组件的模板
sxd-init create-template projectName