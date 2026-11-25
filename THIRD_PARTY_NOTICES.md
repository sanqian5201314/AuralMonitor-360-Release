# 第三方框架、SDK 与公开数据声明 (Third-Party Notices)

**AuralMonitor 360** 的核心业务逻辑（多声道双耳渲染封装、界面交互、跨设备自动声卡桥接等）为作者独立设计与编写，同时构建于以下第三方框架、SDK 与公开数据之上，特此致谢并声明：

---

## 1. JUCE Framework (JUCE 8)
- **官方网站**：https://juce.com / https://github.com/juce-framework/JUCE
- **许可协议**：JUCE 8 Licence (Starter / Commercial) & AGPLv3（详见 https://juce.com/legal/juce-8-licence/ ）
- **说明**：本软件基于 JUCE 8 框架构建跨平台音频插件与界面，在个人/非高营收范围内遵循 JUCE 8 Starter 许可条款；其内部包含的第三方编解码器及依赖（如 FLAC、Ogg Vorbis、jpeglib 等）遵循各自原有 BSD/MIT/Apache 2.0 许可。

## 2. Steinberg VST3 & ASIO
- VST is a trademark of Steinberg Media Technologies GmbH, registered in Europe and other countries.
- ASIO is a trademark and software of Steinberg Media Technologies GmbH.

## 3. AutoEQ 耳机频响校准参数 (MIT License)
- **项目来源**：https://github.com/jaakkopasanen/AutoEq
- **版权声明**：Copyright (c) Jaakko Pasanen (MIT License)
- **说明**：软件内部分常见监听耳机频响补偿预设参数参考自 AutoEQ 公开测量数据。

> Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.

## 4. 内置默认房间脉冲数据 (TU Berlin MO-BRIR)
- **说明**：软件内置的默认演示房间脉冲响应参考自柏林工业大学（TU Berlin）公开声学测量数据集（MO-BRIR），仅作默认演示与个人学习参考；用户可随时拖入自定义 `.wav` BRIR 文件替换。

## 5. 外部独立第三方工具（未捆绑）
本软件教程提及的以下工具均为各自官方独立发布，**未包含**在本软件源码或安装包中：
- **VB-Cable / VB-Audio Matrix**：https://vb-audio.com/
- **Final Spatial Audio (NativeSpatialPipe / NSp)**：https://github.com/BestGreed/NativeSpatialPipe
- **Apple Music**：Apple Inc.
