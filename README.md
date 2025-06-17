
# Python MSIXBundle Manager

Python MSIXBundle Manager 是一个功能强大的图形化工具，用于在Windows系统上管理和安装MSIX/MSIXBundle应用包。它提供了直观的用户界面，支持管理员权限自动提升，并提供详细的安装日志和进度反馈。

## 主要功能

- 图形化界面选择和安装MSIX/MSIXBundle文件
- 自动检测并请求管理员权限
- 支持强制更新和依赖项检查选项
- 实时显示安装进度和详细日志
- 完整的错误处理和提示

## 安装依赖

pip install pywin32 pillow

## 使用方法

1. 确保已安装所有依赖项
2. 以管理员权限运行程序
3. 点击"浏览..."选择MSIXBundle文件
4. 选择安装选项（强制更新、依赖检查）
5. 点击"安装"开始安装过程

## 项目结构

python-msixbundle-manager/
├── msixbundle_manager.py    # 主程序文件
├── resources/               # 资源文件目录
│   └── app.ico              # 应用图标
├── LICENSE                  # 许可证文件
└── README.md                # 项目说明文档
