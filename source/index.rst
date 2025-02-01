.. abcd documentation master file, created by
   sphinx-quickstart on Fri Dec 27 10:43:57 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.
   Add your content using ``reStructuredText`` syntax. See the
   `reStructuredText <https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html>`_
     documentation for details.x

本文档的主要目的是方便同济大学济事楼210实验室的各位同门共享文档,以及附带 `github上的fiber210 <https://github.com/FIBER210>`_ https://github.com/FIBER210 的相关使用说明

T300使用说明
==================
.. toctree::
   :maxdepth: 2
   :caption: T300使用说明

   T300使用说明/概述
   T300使用说明/初次打印前的准备
   T300使用说明/使用T300进行打印
   T300使用说明/设备的维护及保养
   T300使用说明/常见故障及其排除



iFiber使用说明
==================
.. toctree::
   :maxdepth: 2
   :caption: iFiber使用说明

   iFiber使用说明/简介
   iFiber使用说明/安装
   iFiber使用说明/使用说明
   iFiber使用说明/打印参数设置
   iFiber使用说明/自定义纤维路径添加方式


github仓库使用指南
===================

.. toctree::
   :maxdepth: 1
   :caption: github仓库使用指南

   github仓库/使用指南


如只有使用需求，仅仅需要复制代码。如有开发需求，可通过desktop进行代码的共享.

.. toctree::
   :maxdepth: 1

   github仓库/FiberEngine

切片的后端，主要运行程序，有开发需求可以在其中进行修改。

.. toctree::
   :maxdepth: 1

   github仓库/iFiber

切片的前端，可以实现可视化切片

.. toctree::
   :maxdepth: 1

   github仓库/config

用于存放t300和t420的机器配置，在装配机器后会用到。

.. toctree::
   :maxdepth: 1

   github仓库/docs

用于存放Fiber210实验室的公开文档。

.. toctree::
   :maxdepth: 1

   github仓库/DXF2TXT

处理图形的一些py脚本，可以实现

- 将dxf文件保存为txt文件
- 将txt文件保存为dxf文件
- 获得一个stl模型的某一横截面(垂直于z轴)

Indices and tables
==================

* :ref:`genindex`
* :ref:`search`
