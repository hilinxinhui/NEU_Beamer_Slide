# NEU Beamer Slide

东北大学幻灯片模板

## Table of Contents

- [Background](#background)
- [Installation](#installation)
- [Usage](#usage)
- [Related Efforts](#related-efforts)
- [Maintainer](#maintainer)
- [Contributing](#contributing)
- [Contributors](#contributors)
- [LICENSE](#license)

## Background

PowerPoint简单易用，有直观的交互和所见即所得的设计，但是闭源、臃肿，并且很多时候找到合适的模板并不容易.本项目试图解决上述问题，提供基于Beamer的NEU主题幻灯片模板，适用于：

- 论文答辩、学术报告、会议演示
- 社团/班级活动展示
- 等等等

## Installation

克隆本项目，[修改相关代码](#usage)即可。

```Shell
$ cd /path/to/clone
$ git clone https://github.com/hilinxinhui/NEU_Beamer_Slide.git
```

### Usage

[neu.sty](./neu.sty)是模板文件，指定了幻灯片中不同功能页面的内容和模块布局和样式；[NEU_Beamer_Slide.tex](./NEU_Beamer_Slide.tex)是内容文件，用户在该文件中填充具体内容，包括文字、图片、链接和引用灯，编译后生成[NEU_Beamer_Slide.pdf](./NEU_Beamer_Slide.pdf)文件，是幻灯片的最终形态。需要说明的是：

- Beamer使得用户可以专注于内容而非样式设置，对于很多非学术展示场景反而有很大的局限性，请各位审时度势，不要头铁，该用PowePoint/Keynote就用PowePoint/Keynote
- 本模板适用于中文环境，用`XeLaTex`编译
- 生成的`pdf`幻灯片可配合[Beamer Presentation](http://iihm.imag.fr/blanch/software/osx-presentation/)、[pympress](https://github.com/Cimbali/pympress)或[pdfpc](https://pdfpc.github.io)等开启演讲者模式

执行`make`脚本编译即可，具体地：

- Windows用户执行[make.bat](./make.bat)
- *nix用户执行[make.sh](./make.sh)

## Related Efforts

- 样式依据[SEU-Beamer-Slide](https://github.com/TouchFishPioneer/SEU-Beamer-Slide)改编，感谢原作者的设计
- [NEU-Beamer-Slide](https://github.com/zhouyanasd/NEU-Beamer-Slide)提供了校徽矢量图等各种资源文件
- 内容编排参考[THU-Beamer-Theme ](https://github.com/tuna/THU-Beamer-Theme)

## Maintainer

[@hilinxinhui](https://github.com/hilinxinhui)

## Contributing

使用中遇到的任何问题欢迎通过Issue反馈，欢迎Star、Fork、提交PR！

### Contributors

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

## LICENSE

[MIT](./LICENSE)
