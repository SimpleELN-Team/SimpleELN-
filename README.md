# SimpleELN 用户指南

Welcome to the **SimpleELN** user guide! 

欢迎访问 SimpleELN 文档！在这里，您将找到关于如何使用 SimpleELN 创建、共享和组织日常工作、文档和文件的详细信息。您可以在 http://simpleeln.com 上在线体验所有功能。

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

