### 文档
1、npm init 生成package.json文件
2、默认文件名为index.js,通过exports导出（使用者用require引用）
3、注册npm账户去发布，首次使用npm login存储证书到本地，后面就不用每次都登录了
4、使用npm publish发布包（不想发布的内容通过.gitignore或.npmignore文件忽略）
5、使用 npm version （版本号） > npm publish