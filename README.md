# Crawlab 自动登录脚本

这个脚本可以帮助您自动登录 Crawlab 系统（http://your-crawlab-address/#/login）。

## 安装说明

1. 确保您的浏览器已安装 Tampermonkey 扩展。
2. 点击 [Greasy Fork](https://greasyfork.org/zh-CN/scripts/509062-crawlab-%E8%87%AA%E5%8A%A8%E7%99%BB%E5%BD%95) 页面上的"安装"按钮来安装此脚本。
3. Tampermonkey 会提示您确认安装，点击"安装"即可。
4. 安装完成后，在 Tampermonkey 的管理面板中找到 "Crawlab 自动登录" 脚本。
5. 点击 "编辑" 按钮，然后点击 "设置" 标签。
6. 在 "用户包含" / "User includes" 部分，添加您的 Crawlab 地址的匹配规则，例如：
   ```
   *://your-crawlab-address:port/*
   ```
   请确保替换 `your-crawlab-address` 和 `port` 为您实际使用的 Crawlab 地址和端口。
7. 点击 "保存" 按钮以应用更改。

## 使用说明

1. 首次使用时，您需要设置您的登录凭据：
   - 在浏览器工具栏中点击 Tampermonkey 图标。
   - 在下拉菜单中找到 "Crawlab 自动登录" 脚本。
   - 点击 "设置用户名和密码" 选项。
   - 在弹出的提示框中输入您的用户名和密码。

2. 设置完成后，每次您访问 Crawlab 登录页面 （http://your-crawlab-address/#/login） ，脚本将自动填写您的用户名和密码，并尝试登录。

3. 如果您看到页面右上角出现黄色的 "自动登录脚本正在运行" 提示，说明脚本正在工作。

4. 如果需要更新用户名或密码，重复步骤 1 即可。

## 注意事项

- 请确保在安全的环境中使用此脚本，因为它会存储您的登录凭据。
- 如果登录页面结构发生变化，脚本可能需要更新。
- 如果遇到任何问题，请检查控制台日志以获取更多信息。

## 隐私声明

此脚本仅在本地存储您的登录凭据，不会将其发送到任何外部服务器。您的用户名和密码仅用于自动填充登录表单。

## 反馈与支持

如果您遇到任何问题或有改进建议，请在 [Greasy Fork](https://greasyfork.org/zh-CN/scripts/509062-crawlab-%E8%87%AA%E5%8A%A8%E7%99%BB%E5%BD%95) 的脚本页面上留言，或联系脚本作者。

感谢您使用 Crawlab 自动登录脚本！
