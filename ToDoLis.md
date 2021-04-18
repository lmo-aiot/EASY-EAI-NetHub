### ToDoList：

- [ ] 基础功能
  - [x] log设计
  - [ ] 利用python Template功能，优化代码
  - [ ] 训练所需文件导出(预计后期的库可能会比较臃肿, 希望这个功能能缓解这个问题)
- [ ] 模型构筑块
  - [x] acnet_block
- [ ] 模型
  - [ ] 分类模型
    - [ ] vgg
    - [ ] resnet
  - [ ] 分割模型
    - [ ] unet
    - [ ] erfnet
  - [ ] 物体检测模型
    - [ ] yolov5
  - [ ] 关键点定位
    - [ ] retinaface
    - [ ] hopenet
- [ ] 图片处理
  - [x] [方框标注样本的容器](https://github.com/EASY-EAI/EASY-EAI-NetHub/module_lib/image_process_tool/boundingbox_tools.py)，含常见增强、导入导出功能。
  - [x] [关键点样本的容器](https://github.com/EASY-EAI/EASY-EAI-NetHub/module_lib/image_process_tool/keypoint_tools.py)，含常见增强、导入导出功能。
  - [x] [分割标注样本的容器](https://github.com/EASY-EAI/EASY-EAI-NetHub/module_lib/image_process_tool/pixel_label_tools.py)，含常见增强、导入导出功能。
  - [ ] 批量增强工具。(实际上大部分时候不需要，在训练时即时增强即可)
  - [ ] 转rknn模型
    - [ ] 脚本