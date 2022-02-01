# bigdataviewer-core
[![](https://api.github.com/bigdataviewer/bigdataviewer-core/actions/workflows/build-main.yml/badge.svg)](https://github.com/bigdataviewer/bigdataviewer-core/actions/workflows/build-main.yml)
[![Join the chat at https://gitter.im/bigdataviewer/bigdataviewer-core](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/bigdataviewer/bigdataviewer-core?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) ImgLib2-based viewer for registered SPIM stacks and more

Feature added in this fork: 
### Interactive Video producing using Spline interpolation :
1- Video producer can be opened by clicking `F7` or `Tools -> Produce Movie`
![](img/1.png)

2- By opening Video Producer you get this panel
![](img/2.png)
- `+` To add current frame
- `-` To delete last frame
- Preview with a frame down-sampling and sleep time between frames
- Accel: you select the interpolation: `Slow start` , `slow end` , `Symmetric` ...
- Export: Can be in `Json` or `PNG sequence`