## 一、eslint

### 配置 eslint：

1. 安装 eslint：npm install eslint --save-dev
2. 安装 airbnb 所有 peerDependency：npx install-peerdeps --dev eslint-config-airbnb
3. 配置 .eslintrc.js

### 配置 prettier：

- 安装 prettier：npx install —save-dev —save-exact prettier
- 安装 eslint-config-prettier，关闭 eslint 跟 prettier 冲突的部分
- 安装 eslint-plugin-prettier，这个插件会让 eslint 使用 prettier 作为格式化工具

## 二、stylelint

### 配置 stylelint：

1. npm install --save-dev stylelint stylelint-config-standard
2. 配置 .stylelinerc.json

### 配置 prettier：

- 安装 prettier：npx install —save-dev —save-exact prettier
- 配置 stylelint-config-prettier，关闭 stylelint 跟 prettier 冲突的部分
- 配置 stylelint-prettier，这个插件会让 stylelint 使用 prettier 作为格式化工具

## 三、其他参考

1. [prettier 集成到 eslint 和 stylelint](https://prettier.io/docs/en/integrating-with-linters.html)
