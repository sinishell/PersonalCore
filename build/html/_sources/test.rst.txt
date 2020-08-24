====================
常用的写法
====================

文字处理
=========

**加粗** *斜体*

取消 空格 -> 取消\ 空格


列表项目
========

#. 列表项目1
#. 列表项目2

- 无序列表
- 无序列表

注解
=======================

.. note::

  测试一下Note的写法

嵌入代码
========

.. code:: python

    import math
    x = 100 * y

文本块
======

::
  
  这是一个文本块

另一种::
  
  如果有文字的话会自动保留一个冒号

警告
------

.. warning::
   
   警告的内容

链接
====

匿名链接 `这是链接`__

.. __: http://www.github.com

链接到另一个页面
================

直接读取页面标题 :doc:`/index`

或者给它个名称 :doc:`index </index>`


引用
==========

引用名词表
-----------
.. code:: rest
 
   :term:`source directory`


.. _my-reference-label:

交叉引用
--------

定义标签需要在header或caption之前，展示的名称是这个header

It refers to the section itself, see :ref:`my-reference-label`.

引用是跨文档的，并且对figure和table也有效，定义标签也要放在它们之前。

尾注
======

这里使用尾注 [#]_


边栏
====

.. sidebar:: 边栏的标题

   边栏的内容

替代
====

|more| 这里替代了一个图片

.. |more| image:: /_static/github.svg
          :align: middle
          :alt: more infor




-----------------------

.. [#] 尾注的内容