# kyzjnbk-template

科研仔技能百科-模板

你可以从此模板开设新的主题，包括但不限于具体理论方向、摸鱼指南。


## 如何贡献？(How to contribute?)

随时欢迎任何人提交Pull Request，或者在GitHub上提交Issue。

项目文件目录：

```shell
.
├── docs # 文档目录存放，站点根目录
├── Makefile
├── mkdocs.yml # 配置文件，定义了文档的总体目录、远程库位置和视觉主题
├── README.md # 项目介绍
└── requirements.txt # 用于安装依赖的Python包
```

mkdocs.yml 文件定义了站点信息和导航栏结构(nav)。主题一般不需要改动。

下载此库至本地，并进入目录(**改成你自己的项目名,并移除此提示**):

```shell
git clone https://github.com/kyzjnbk/kyzjnbk-template
cd kyzjnbk-template
```

环境配置(需要python 3.x)：

```shell
pip3 install -r ./requirements.txt
```

在本地实时预览(默认8000端口)：

```shell
mkdocs serve
```
