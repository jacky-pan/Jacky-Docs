文档制作简介
============

该手册采用 `reStructuredText <http://docutils.sourceforge.net/rst.html>`_ 标记语言（ :term:`Markup Language` ）撰写, 使用 `Sphinx <http://www.sphinx-doc.org/en/stable/>`_ 进行发布.


标记语言简介
------------

你可能觉得标记语言是个新名词, 然而你大错特错, 如果我说 `HTML <https://zh.wikipedia.org/wiki/HTML>`_ 、`Latex <https://zh.wikipedia.org/wiki/LaTeX>`_ 也是标记语言, 前者用于创建网页, 后者用于排版文档书籍, 你可能就知道一点了.

简而言之, 标记语言就是特定的标记符号集合, 每个特定标记符可以实现特定的功能（自己总结的）, 如倾斜、加粗、连接、引用等等, 如在reStructureText或者Markdown中, 使用星号括住文本, 可将文本渲染成斜体或粗体, 即 ``*我变斜了*`` 被渲染成 *我变斜了*, ``**我变粗了**`` 被渲染成 **我变粗了** .

Markdown标记语言
~~~~~~~~~~~~~~~~~~~