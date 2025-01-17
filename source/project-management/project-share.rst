.. _project-management-project-share:

.. rst-class:: title-center
    
#################################################
笔记本共享
#################################################

为了促进团队协作，SimpleELN的团队版（Team Edition）和多团队版（MultiTeam Edition）支持团队成员之间的数据共享，且共享可以在项目级别进行。每个项目都有一个指定的创建者，创建者拥有该项目的所有权限，包括设置/取消共享、管理共享的团队成员以及控制他们的共享权限。共享权限包括只读/评论共享和读写/评论共享权限。此外，团队管理员（Team Admin）对其管理的所有团队成员拥有只读/评论共享权限。
 
*****************************
个人版
*****************************

SimpleELN个人版仅支持一个用户账户。由于无法创建额外账户，用户可以创建笔记本（项目），但不能与他人共享。

.. warning:: 

    - 仅限一个用户账户
    - 项目无法共享

****************************************************************************************************************************************************
:ref:`团队版（Team Edition） <project-management-project-share-team-edition>`
****************************************************************************************************************************************************

在SimpleELN团队版中，存在一个团队管理员账户。该管理员具有创建和管理多个团队成员账户的权限，将其统一为一个团队。每个团队成员可以创建笔记本（项目）并与其他团队成员共享，而团队管理员对所有团队成员的笔记本拥有只读/评论访问权限。

:octicon:`dot;1em;sd-text-primary` 团队成员之间的笔记本共享
    .. toctree::
       :maxdepth: 1
       
       project-share-team-edition
    

.. warning:: 

    - 仅限一个团队
    - 项目仅能在同一团队成员之间共享
    - 项目不能在不同团队成员之间共享

****************************************************************************************************************************************************
:custom-color-primary-bold:`多团队版（MultiTeam Edition）`
****************************************************************************************************************************************************

在SimpleELN多团队版中，存在多个团队管理员账户。每个团队管理员可以创建和管理多个团队成员账户，将其分组为一个团队。每个团队成员可以创建笔记本（项目），并在团队内部或跨团队共享，而团队管理员对所有团队成员的笔记本拥有只读/评论访问权限。

**注意：** 团队管理员不仅对团队成员创建的项目拥有只读/评论权限，还可以对非团队成员创建并共享给团队成员的项目拥有相同的权限。

:octicon:`dot;1em;sd-text-primary` 同一团队成员之间的笔记本共享
    - :ref:`同一团队成员之间的笔记本共享 <project-management-project-share-team-edition>`
    
:octicon:`dot;1em;sd-text-primary` **不同团队成员之间的笔记本共享**。如需设置 **不同团队成员之间的笔记本共享** ，请与 SimpleELN 技术支持团队联系。您可以通过以下邮箱联系我们：
    
    - simple.eln@aliyun.com
    - simpleeln@163.com
    
    
.. warning:: 

    - 多个团队
    - 项目可以在同一团队成员之间共享
    - 项目可以在不同团队成员之间共享
