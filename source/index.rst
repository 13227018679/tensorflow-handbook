.. 简单粗暴TensorFlow documentation master file, created by
   sphinx-quickstart on Sat Jan 20 00:48:15 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

==================================================================
简单粗暴 TensorFlow 2 | A Concise Handbook of TensorFlow 2
==================================================================

*基于Keras和Eager Execution | Based on Keras and Eager Execution*

.. raw:: html

    <table style="width: 100%; margin: 20px 0">
        <tbody witth=100%>
        <tr>
            <td width=50% style="text-align: center">
                <b><a href="#id1">中文版</a></b>
                <small>（點擊頁面上方按鈕切換繁簡）</small>           
            </td>
            <td width=50% style="text-align: center"><b><a href="#english-version-in-progress">English Version (in progress)</a></b></td>
        </tr>
        </tbody>
    </table>

..
    本文档为未完成版本，内容会随时更改修订，目前请不要扩散。

    This document is unfinished, content will be updated rapidly. Please keep it internal at this time.

中文版
==========================

这是一本简明的 TensorFlow 2 入门指导手册，基于 Keras 和即时执行模式（Eager Execution），力图让具备一定机器学习及 Python 基础的开发者们快速上手 TensorFlow 2。

本手册的所有代码基于 TensorFlow 2.1 和 2.0 正式版。文中的所有示例代码可至 `这里 <https://github.com/snowkylin/tensorflow-handbook/tree/master/source/_static/code/en>`_ 获得。

本手册正于TensorFlow官方微信公众号（TensorFlow_official）连载，可点此查看 `连载文章目录 <https://mp.weixin.qq.com/s/cvZHUWS3MiGHq3UDynucxw>`_ 。本手册的原始语言为中文，其英文版仍在翻译中。请访问 https://v1.tf.wiki 以查看本手册上一版的英文版。本手册是  `Google Summer of Code 2019 <https://summerofcode.withgoogle.com/archive/2019/projects/5460192307707904/>`_  项目之一。

自2020年4月起，在每章文末加入了留言区，欢迎有需要的读者在文末讨论交流。

.. admonition:: 线上教学活动：ML Study Jam

    本手册正在与TensorFlow官方微信公众号合作开展为期三周的“ML Study Jam”线上学习活动。活动从2020年4月20日开始，可以访问 `这里 <https://tf.wiki/zh/mlstudyjam.html>`_ 或 `TensorFlow官方微信公众号（TensorFlow_official） <http://mp.weixin.qq.com/s?__biz=MzU1OTMyNDcxMQ==&mid=2247488326&idx=1&sn=e5507c80e3419ae30425b7dfac4ce164&chksm=fc18580ecb6fd11808c35c18ed3e61dd39f36d3fbdfcacefaff03e7a5ab6b07b788d1b87e467&mpshare=1&scene=23&srcid=&sharer_sharetime=1587465932630&sharer_shareid=b6f86ab8b392c4d4036aa6a1d3b82824#rd>`_ 以了解详情。

GitHub： https://github.com/snowkylin/tensorflow-handbook

答疑区： https://discuss.tf.wiki

.. toctree:: 
    :maxdepth: 3
    :caption: 教学活动
    
    zh/mlstudyjam

.. toctree:: 
    :maxdepth: 2
    :caption: 目录

    zh/preface
    zh/introduction

.. toctree:: 
    :maxdepth: 3
    :caption: 基础

    zh/basic/installation
    zh/basic/basic
    zh/basic/models
    zh/basic/tools

.. toctree:: 
    :maxdepth: 3
    :caption: 部署

    zh/deployment/export
    zh/deployment/serving
    zh/deployment/lite
    zh/deployment/javascript

.. toctree:: 
    :maxdepth: 3
    :caption: 大规模训练与加速

    zh/appendix/distributed
    zh/appendix/tpu

.. toctree:: 
    :maxdepth: 3
    :caption: 扩展

    zh/appendix/tfhub
    zh/appendix/tfds  
    zh/appendix/swift
    zh/appendix/quantum

..
    .. toctree:: 
        :maxdepth: 2
        :caption: 应用

        zh/application/rl
        zh/application/chatbot
..
    .. toctree:: 
        :maxdepth: 3
        :caption: 高级

        zh/advanced/static 
        zh/advanced/tape
        zh/advanced/optimization

.. toctree:: 
    :maxdepth: 3
    :caption: 附录
    
    zh/appendix/rl
    zh/appendix/docker
    zh/appendix/cloud
    zh/appendix/jupyterlab    
    zh/appendix/recommended_books
    zh/appendix/terms

..
    PDF下载（旧版）：

    - 中文版：https://discuss.tf.wiki/t/topic/23 （同时也有英文版下载）
    - 英文版：https://github.com/snowkylin/tensorflow-handbook/releases

    GitHub: https://github.com/snowkylin/tensorflow-handbook

English Version (in progress)
==============================================

This is a concise handbook of TensorFlow 2.0 based on Keras and Eager Execution mode, aiming to help developers with some basic machine learning and Python knowledge to get started with TensorFlow 2.0 quickly.

The code of this handbook is based on TensorFlow 2.0 stable version and beta1 version. All sample code in this handbook can be viewed `here <https://github.com/snowkylin/tensorflow-handbook/tree/master/source/_static/code/>`_ .

The English version of this handbook is still in progress (section title with a ✔️ means that the translation of this section is finished). Please refer to https://v1.tf.wiki for the eariler version. This handbook is a project of `Google Summer of Code 2019 <https://summerofcode.withgoogle.com/archive/2019/projects/5460192307707904/>`_ .

GitHub： https://github.com/snowkylin/tensorflow-handbook

Q&A: https://discuss.tf.wiki

.. toctree:: 
    :maxdepth: 2
    :caption: Preface

    en/preface
    en/introduction

.. toctree:: 
    :maxdepth: 3
    :caption: Basic

    en/basic/installation
    en/basic/basic
    en/basic/models
    en/basic/tools

.. toctree:: 
    :maxdepth: 3
    :caption: Deployment

    en/deployment/export
    en/deployment/serving
    en/deployment/lite
    en/deployment/javascript

.. toctree:: 
    :maxdepth: 3
    :caption: Large-scale Training

    en/appendix/distributed
    en/appendix/tpu

.. toctree:: 
    :maxdepth: 3
    :caption: Extensions

    en/appendix/tfhub
    en/appendix/tfds  
    en/appendix/swift
    en/appendix/julia

..
    .. toctree:: 
        :maxdepth: 2
        :caption: 应用

        en/application/rl
        en/application/chatbot

.. toctree:: 
    :maxdepth: 3
    :caption: Appendix

    en/appendix/static 
    en/appendix/docker
    en/appendix/cloud
    en/appendix/jupyterlab
    en/appendix/optimization
    en/appendix/recommended_books
    en/appendix/terms

..
    .. toctree:: 
        en/preface
        en/installation
        en/basic
        en/models
        en/extended 
        en/static

..
    PDF download (old version): 

    - Chinese version: https://discuss.tf.wiki/t/topic/23
    - English version: https://github.com/snowkylin/tensorflow-handbook/releases

    GitHub: https://github.com/snowkylin/tensorflow-handbook

..  
   preface
   introduction
   installation
   basic
   ops
   models
    --
   visualization
   debugging   
    --
   distributed
   dynamic   
   code
   appendix

.. only:: html

    Indices and tables
    ==================

    * :ref:`genindex`
    * :ref:`modindex`
    * :ref:`search`

    .. raw:: html
    
        <img src="https://s05.flagcounter.com/count2/Hyjs/bg_FFFFFF/txt_000000/border_CCCCCC/columns_2/maxflags_16/viewers_0/labels_1/pageviews_1/flags_0/percent_0/" alt="Flag Counter" border="0">

..
    https://info.flagcounter.com/Hyjs

