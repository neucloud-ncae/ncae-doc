## 用户向导

---
- 产品介绍
  * 
  * 
  * 

---
- 提示信息：
  * 请选择应用扩展模式。
  * 单节点模式：平台只分配一台虚拟机节点用于运行您的应用。
  * 自伸缩模式：平台将自动根据应用服务器的负载和资源使用情况，动态为您创建新的应用节点。
- 用户选择：（扩展模式）（单节点 / 自伸缩）

---
- 提示信息：
  * 请选择应用服务器配置。
  * 如果应用扩展模式选择为“自伸缩”，所有动态创建的应用节点也均会采用此配置。
- 用户选择 / 输入

---
- 提示信息：
  * 本平台支持通过 GitHub、GitLab、URL 三种方式获取源码。
  * GitHub 获取方式示例：
    - `git@github.com:neucloud-ncae/ncae-example-php.git`
    - `https://github.com/neucloud-ncae/ncae-example-php`
  * URL 获取方式示例：
    - `http://neucloud.oss-cn-beijing.aliyuncs.com/softwares/ncae/ncae-example-php-master.zip`
- 用户选择：（获取方式）（GitHub / GitLab / URL）
- 用户输入：（源码地址）
![](https://raw.githubusercontent.com/neucloud-ncae/ncae-doc/master/images/repo.png)

---
- 提示信息：
  * 请选择你指定的代码所使用的语言环境（框架），我们将根据您的选择，为您自动生成一些基础配置指令。
- 用户选择：（语言环境）（PHP / Python / Java）
- 用户输入：（配置指令）（根据用户选择的语言环境，默认填入基础配置指令）
![](https://raw.githubusercontent.com/neucloud-ncae/ncae-doc/master/images/test.png)

---
- 提示信息：
  * 请输入您需要传入应用节点的环境变量，这些环境变量将可以在您的应用节点中被使用（包括扩展结点）
- 用户输入：（环境变量）（输入模式：KEY = VALUE）
![](https://raw.githubusercontent.com/neucloud-ncae/ncae-doc/master/images/env.png)

---
- 部署执行

