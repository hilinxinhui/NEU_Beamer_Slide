# NEU Beamer Slide

东北大学幻灯片模板

## 说明

### 适用于

- 论文答辩、学术报告、会议演示
- 社团/班级活动展示
- 等等等

### 用法

[neu.sty](./neu.sty)是模板文件，指定了幻灯片中不同功能页面的内容和模块布局和样式；[NEU_Beamer_Slide.tex](./NEU_Beamer_Slide.tex)是内容文件，用户在该文件中填充具体内容，包括文字、图片、链接和引用灯，编译后生成[NEU_Beamer_Slide.pdf](./NEU_Beamer_Slide.pdf)文件，是幻灯片的最终形态。需要说明的是：

- Beamer使得用户可以专注于内容而非样式设置，对于很多非学术展示场景反而有很大的局限性，请各位审时度势，不要头铁，该用PowePoint/Keynote就用PowePoint/Keynote
- 本模板适用于中文环境，用`XeLaTex`编译
- 生成的`pdf`幻灯片可配合[Beamer Presentation](http://iihm.imag.fr/blanch/software/osx-presentation/)、[pympress](https://github.com/Cimbali/pympress)或[pdfpc](https://pdfpc.github.io)等开启演讲者模式

执行`make`脚本编译即可，具体地：

- Windows用户执行[make.bat](./make.bat)
- *nix用户执行[make.sh](./make.sh)

## 欢迎参与到本项目

- 使用中遇到的任何问题欢迎提Issue反馈
- 欢迎Star、Fork、提交PR，本文档的[下一部分](#贡献者)部分列出了项目的主要贡献者

## 贡献者

<!-- readme: collaborators,contributors -start -->
<table>
<tr>
    <td align="center">
        <a href="https://github.com/hilinxinhui">
            <img src="https://avatars.githubusercontent.com/u/72953081?v=4" width="100;" alt="hilinxinhui"/>
            <br />
            <sub><b>Xinhui Lin</b></sub>
        </a>
    </td></tr>
</table>
<!-- readme: collaborators,contributors -end -->

## 许可

[MIT](./LICENSE)

## 致谢

- 样式依据[SEU-Beamer-Slide](https://github.com/TouchFishPioneer/SEU-Beamer-Slide)改编，感谢原作者的设计
- [NEU-Beamer-Slide](https://github.com/zhouyanasd/NEU-Beamer-Slide)提供了校徽矢量图等各种资源文件
- 内容编排参考[THU-Beamer-Theme ](https://github.com/tuna/THU-Beamer-Theme)