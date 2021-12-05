# webdatavisualization
web data visualization

### 基本设计
现在的主流数据可视化解决方案，都在设计上并不那么全面，
此项目旨在以股票分析这种场景为切入点，进行较为专业的数据可视化
的尝试，眺望webgpu等新一代呈现技术，也先用好现在的canvas2d方案
主要在于推出“量度空间”的概念，在此设计理念之上，去做多指标图像
的呈现

### 技术概要
打包使用 parcel,目前2.0.1 2.x之后使用rust重构性能大增，而且也适合于各种规模的项目，前端使用typescript，vscode