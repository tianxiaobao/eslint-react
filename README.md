# eslint-react

eslint 规则，使用了 eslint:recommended 扩展库及自定义规则
具体规则查看 https://eslint.bootcss.com/docs/rules/
.js 或 .jsx 文件检查规则，使用 react 官方插件 eslint-plugin-react
eslint-plugin-react 查看 https://www.npmjs.com/package/eslint-plugin-react
eslint-plugin-jsx-a11y 查看 https://github.com/evcohen/eslint-plugin-jsx-a11y
``` bash
# 安装依赖
npm install

# 依赖 husky lint-staged
# husky 提供git钩子函数
# lint-staged 一个文件过滤器，仅仅过滤出你自己修改文件
# 在 git commit 前会做检查并自动修复