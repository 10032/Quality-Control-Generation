# 质控数据生成软件

## 简介
本程序是一个用于生成符合截断正态分布的质控数据的工具。用户可以通过图形用户界面（GUI）输入相关参数，并设置快捷键来触发数据生成。生成的数据将自动输出到当前焦点处。

## 功能
- **生成质控数据**：根据用户输入的靶值、可接受范围、室内不精密度和数据点数量，生成符合截断正态分布的随机数据。
- **快捷键触发**：用户可以设置快捷键，按下快捷键后程序将自动生成数据并输出到当前焦点处。
- **输入验证**：程序会对用户输入的参数进行验证，确保输入的合法性。


### 通过 GitHub Releases 安装

1. 访问 [GitHub Releases](https://github.com/10032/Primary-care-laboratory/releases/tag/v0.0.01) 页面。
2. 下载最新版本的运行。
3. 双击打开，愉快使用。

## 界面
![主界面](https://github.com/user-attachments/assets/008d64d5-1939-442c-8c2b-4bf79e44cf90)
![例子](https://github.com/user-attachments/assets/eb22c4a4-b019-4f4e-b56f-45a9ef88c46b)
![数值](https://github.com/user-attachments/assets/8d6d49e6-4d3b-4d86-b810-5fdbdb8b51ac)

## 使用说明
1. 运行程序后，将出现一个图形用户界面（GUI）。
2. 在相应的输入框中输入以下参数：
   - **靶值**：质控数据的靶值。
   - **可接受范围（±%）**：质控数据可接受的范围，以百分比表示。
   - **室内不精密度（<%）**：质控数据的室内不精密度，以百分比表示。
   - **数据点数量**：需要生成的质控数据点的数量。
   - **设置快捷键**：设置触发数据生成的快捷键组合（例如：`ctrl+shift+g`）。
3. 点击“开始监听”按钮，程序将开始监听快捷键。
4. 按下设置的快捷键，程序将生成质控数据并自动输出到当前焦点处。
5. 点击“停止监听”按钮，程序将停止监听快捷键。

## 注意事项
- 确保在按下快捷键时，焦点位于可以接收文本输入的应用程序中（例如：文本编辑器、Excel等）。
- 快捷键组合必须是有效的组合，否则程序将无法识别。

## 示例
假设您需要生成以下参数的质控数据：
- 靶值：100
- 可接受范围：5%
- 室内不精密度：2%
- 数据点数量：10
- 快捷键：`ctrl+shift+g`

1. 在相应的输入框中输入上述参数。
2. 点击“开始监听”按钮。
3. 打开Excel或其他文本编辑器，并确保焦点位于输入区域。
4. 按下`ctrl+shift+g`，程序将生成10个符合要求的质控数据并自动输入到Excel中。

## 错误处理
- 如果输入的参数不合法（例如：靶值为负数、室内不精密度大于可接受范围等），程序将弹出错误提示框。
- 如果无法生成满足条件的数据，程序将抛出错误提示。

## 许可证
本项目采用GNU General Public License v3.0许可证。详情请参阅LICENSE文件。
如修改请公开代码。

---

希望这个README文件能帮助您更好地理解和使用这个程序。如果有任何问题或建议，请随时联系作者。


---

**Primary Care Laboratory** - 让质控数据生成更简单、更真实！
