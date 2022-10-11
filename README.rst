Go 语言项目开发实战
##############################

.. image:: https://github.com/seisman/how-to-write-makefile/actions/workflows/deploy.yml/badge.svg
   :target: https://github.com/seisman/how-to-write-makefile/actions/workflows/deploy.yml

简介
----

当前，很多公司的技术架构都在往云原生架构演进，而绝大部分的云原生核心项目是用 Go 来构建的，例如：Kubernetes、Docker 等。同时，国内腾讯、阿里等一线大厂也都在积极转 Go。伴随着 Go 的火热，各个公司对 Go 研发工程师的需求也越来越旺盛。

因此，很多开发者都在学习或使用 Go 来开发项目。但是，很多初学者在学习 Go 项目开发时，经常会面临一系列问题：

Go 项目开发涉及的技能点太多，不知道如何去构建其中的技能点
看了很多资料，还是没有掌握最佳实践，总也写不出优雅的代码
学了很多 Go 开发相关的知识点、构建方法，但都不系统、不全面、不深入
……
为此，我们邀请孔令飞开设了一门 Go 语言项目实战课。他会围绕一个可部署、可运行的企业应用源码，遵循 Go 项目开发流程，为你系统、详细地讲解 Go 应用开发需要用到的技能点，让你掌握它们的具体构建方法、业界的最佳实践和一线开发经验。

同时，专栏最终交付给你的这套代码能够满足绝大部分的企业应用开发场景，你可以基于它做二次开发，快速构建起你自己的企业应用。

相关
----

- 书的文字部分来自于 `Andriki`_ 提供的Mediawiki源码；
- 使用 `Sphinx`_ 制作文档
- 项目主页： https://github.com/seisman/how-to-write-makefile
- 网页在线版： https://seisman.github.io/how-to-write-makefile/
- PDF下载： https://seisman.github.io/how-to-write-makefile/Makefile.pdf

本地编译
--------

#. Clone项目到本地::

   $ git clone https://github.com/seisman/how-to-write-makefile.git

#. 安装依赖::

   $ pip install -r requirements.txt

#. 编译生成HTML::

   $ make html
   $ firefox build/html/index.html&

#. 编译生成PDF（要求安装TeXLive）::

   $ make latexpdf
   $ evince build/latex/Makefile.pdf&
