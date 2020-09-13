## Machine Learning By Coding

> It's a self learning materials based on [fast book](https://github.com/fastai/fastbook).

**要求：** 

- 使用过至少一门编程语言一年以上（Python最佳）

- 有IT领域基本的常识（如web服务、传输协议、Linux基本操作等）

 

**课程规划：**

- 采用 由顶及下（Top-Down） 的风格，通过实践快速掌握人工智能应用开发的核心；

- 分三个阶段，第一阶段预计10门课程（应用开发）；第二阶段10门课程（理论实战）；第三阶段5门课（技术探索）；

- 每门课程根据难度不同，1-2周完成；

- 有些课程内容为自学课程
- 

**课程依赖：**

- 以FastBook为主线，配合相关教材和外部资料；

 

**课程环境：**

- 会用到GPU资源，建议使用[Google Colab](https://colab.research.google.com/)或kaggle Notebook；

 

**班级规划**：学习小组模式

**课程规划**

| **编号** | **课程名称**                        | **知识点详情**                 | **路径**                                                     |
| -------- | ----------------------------------- | ------------------------------ | ------------------------------------------------------------ |
| 1        | 人工智能入门                        | 工具、方法、历史渊源、环境准备 | 1. 查看[Link](https://course.fast.ai/start_colab)了解如何在google colab中使用课程notebook；<br>2. 查看[00_app_jupyter.ipynb](00_app_jupyter.ipynb)了解jupyter的使用<br> 2.学习[第一课](https://www.bilibili.com/video/BV14V411U7Hw?from=search&seid=9365735642278974896)；<br>3. 在notebook中完成[01_intro.ipynb](01_intro.ipynb)及课后问题； <br> 4. 有疑问可以去Forum中搜索答案 |
| 2        | 端到端的人工智能应用开发实战        |                                |                                                              |
| 3        | 人工智能伦理与道德                  |                                |                                                              |
| 4        | 二分类-手写数字识别来看人工智能算法 |                                |                                                              |
| 5        | 多分类-细粒度图像分类               |                                |                                                              |
| 6        | 图像多标签分类                      |                                |                                                              |
| 7        | 算法优化技巧                        |                                |                                                              |
| 8        | 协同过滤算法                        |                                |                                                              |
| 9        | 表格化数据处理                      |                                |                                                              |
| 10       | 自然语言处理应用                    |                                |                                                              |
|          | TBD                                 |                                |                                                              |
|          | TBD                                 |                                |                                                              |

### 如何构建课程环境

> python > 3.6

#### 本地CPU环境

```bash
pip install torch torchvision -i https://pypi.tuna.tsinghua.edu.cn/simple
pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple
```

#### 使用docker

```bash
docker pull fastdotai/fastai-course:latest
```

> 更多docker环境配置参见： https://github.com/fastai/docker-containers

#### 使用Google Colab

> 查看：https://course.fast.ai/start_colab

### 课程资源

1. [官方教学视频](https://course.fast.ai/)
2. [Notebooks官方github](https://github.com/fastai/fastbook)
3. [Forums](https://forums.fast.ai/)
