.. _install:

===========
快速安装
===========

　　既然要使用Django，那肯定要先安装。这里是`完整安装指南(0%)`_ ，涵盖所有可能涉及的东西。本指南将引导您进行简单的，最简化的安装。

安装Python
----------

　　作为Python Web框架，Django需要Python支持。这里可以查看 `Django应该使用什么Python版本(0%)`_ 。Python内建了一个SQLite的轻量级数据库，因此您不需要立即配置数据库。

　　可以到这里https://www.python.org/download/ 获取最新版本的Python。

.. note::

    Jython:如果您使用 `Jython`_ （基于Java的Python），则需要执行几个步骤。有关详细信息，请参阅 `在Jython上运行Django(0%)`_ 。

　　您可以通过从shell来验证python是否安装成功，在shell中键入python;你应该看到类似下面的内容:

.. code:: shell

    Python 3.4.x
    [GCC 4.x] on linux
    Type "help", "copyright", "credits" or "license" for more information.
    >>>

新建数据库
----------

　　只有当你需要使用“大型”数据库例如PostgreSQL、MySQL或Oracle时，才需要这一步。若要安装这样一个数据库，请参考` 数据库安装信息`_ 。

删除旧版本Django
------------------

　　如果你是从旧版本的Django升级安装，你将需要在安装新版本之前先 `卸载旧版本的Django`_ 。

安装Django
----------

　　你可以使用下面三个简单的方式来安装 Django：

-  `安装官方正式发行版本`_ ，这是大多数用户最佳的选择。

-  安装 `操作系统发行版提供的Django`_ 版本。

-  `安装最新的开发版本`_ 。此选项适用于想要最新功能且不怕运行全新代码的爱好者。您可能在开发版本中遇到新的错误，报告它们有助于开发Django。此外，第三方软件包的版本与最新的稳定版本不太可能兼容开发版本。

.. note::

    请你一定要参考与你Django版本一致的文档！

验证
----

　　若要验证Django是否安装成功，可以在shell中输入python。然后在Python提示符下，尝试导入Django：

.. code:: shell

    >>> import django
    >>> print(django.get_version())
    1.10

　　这里是安装的1.10，你可能安装的是其他版本的Django。

完成
----

　　安装完成 ——现在你可以继续学习 `教程`_

.. _完整安装指南(0%):  https://docs.djangoproject.com/en/1.10/topics/install/
.. _Django应该使用什么Python版本(0%): https://docs.djangoproject.com/en/1.10/faq/install/#faq-python-version-support
.. _Jython: http://www.jython.org/
.. _在Jython上运行Django(0%): https://docs.djangoproject.com/en/1.10/howto/jython/
.. _卸载旧版本的Django: https://docs.djangoproject.com/en/1.10/topics/install/#removing-old-versions-of-django
.. _ 数据库安装信息: https://docs.djangoproject.com/en/1.10/topics/install/#database-installation
.. _安装官方正式发行版本: https://docs.djangoproject.com/en/1.10/topics/install/#installing-official-release
.. _操作系统发行版提供的Django: https://docs.djangoproject.com/en/1.10/topics/install/#installing-distribution-package
.. _安装最新的开发版本: https://docs.djangoproject.com/en/1.10/topics/install/#installing-development-version
.. _教程: https://github.com/jhao104/django-chinese-docs-1.10/blob/master/intro/tutorial01/%E5%BC%80%E5%8F%91%E7%AC%AC%E4%B8%80%E4%B8%AADjango%E5%BA%94%E7%94%A8%2CPart1.md