# SimpleELN 用户指南

欢迎使用SimpleELN用户指南！

SimpleELN是一款用户友好的电子实验室笔记本（ELN）系统，旨在帮助研究人员安全地存储、组织和分享他们的研究数据和笔记。本指南将为您提供详细的步骤教程，帮助您快速入门并高效地使用SimpleELN的各项功能。

感谢您选择SimpleELN web服务器，给我们展示其功能和性能的机会。我们非常感谢您的关注，并希望SimpleELN能对您的研究和文档工作提供帮助。

[SimpleELN 用户指南](https://simpleeln-documentation.readthedocs.io/en/latest/index.html).

## 版本

  - [个人版](https://github.com/SimpleELN-Team/SimpleELN-Personal)
    
    个人版专为个人用户量身定制，使其能够创建和管理自己的实验记录。该版本非常适合个人使用，确保增强的数据安全性，并在安装和日常使用中提供用户友好的体验。
    
  - [团队版](https://github.com/SimpleELN-Team/SimpleELN-Team)
    
    团队版适用于团队型用户，允许创建一个团队账户，并设置团队管理员角色，同时可以创建多个团队用户账户。该版本非常适合多个用户的单一实验室或需要团队成员协作的组织。
    
  - [多团队版](https://github.com/SimpleELN-Team/SimpleELN-MultiTeam)
    
    多团队版专为部门、中心、公司、组织以及其他包含多个独立团队的实体量身定制。该版本特别适合需要团队或用户间协作的多团队实验室或组织。
    

## 简介

源文件: [https://github.com/SimpleELN-Team/SimpleELN-Doc-Chinese/tree/main/source](https://github.com/SimpleELN-Team/SimpleELN-Doc-Chinese/tree/main/source).

## 安装

~~~bash
git clone https://github.com/SimpleELN-Team/SimpleELN-Doc-Chinese.git
cd SimpleELN-Doc-Chinese
pip install --user sphinx sphinx_rtd_theme myst-parser sphinx-autobuild sphinx-design
~~~

## 生成HTML文档

~~~bash
sphinx-build -M html source/ build/
~~~

用浏览器打开 `build/html/index.html` 。

用浏览器打开 `html/index.html` 文件。

