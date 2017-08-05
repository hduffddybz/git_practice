一道有关于 git 实践的题目，通过这道题可以掌握 git 分支，多人协作，重写历史等 git 的基本用法，会使用到 git init/add/commit/pull/rebae/branch/checkout/stash 等指令，欢迎提交 pull request 丰富实践内容

1. 在空的目录初始化 git 仓库，并在 branch master 创建 a.txt 文件，增加如下内容"Initilize project",并以 "First commit" 信息来提交

2. 基于branch master 创建 branch dev，在 a.txt 增加如下内容"Add feature 1",并以 "Modify a.txt" 信息来提交

3. 在 branch dev 发现 "Modify a.txt" 不能反映所做更改的内容，修改提交信息为 "Add feature 1"

4. 将 branch dev 合并到 branch master

5. 在 branch dev 进行 Feature 2 开发的同时（在 a.txt 添加了 Add），发现 First commit 中的 "Initilize project" 提交错误（Initialize->Initilize,可假设为现实开发中重大的 bug），因而在 branch dev 储藏该修改并切换到 branch bug 修复该问题，并以 "Correct errors in the first commit" 来提交

6. 将 branch bug 合并到 branch master

7. 这时候在 branch dev 的 fearture 2 开发完毕，以 "Add feature 2" 信息来提交

8. 发现 feature 2 的修改不完善，修改内容为 "Add full feature 2", 不增加新的提交信息

9. 将 branch dev 合并到 branch master

10. 你的朋友 S 加入项目开发，克隆了代码（简单起见，认为使用同一台主机）。

11. 你把她的代码路径添加到你的远程仓库。然后，在 branch dev 进行 "Add feature 3.1" 开发，以 "Add feature 3.1" 进行提交

12. 你的朋友 S 在 branch dev 进行 "Add feature 3.2" 开发，并以 "Add feature 3.2" 进行提交

13. 你把你的朋友 S 的 branch dev 合并到自己本地的 branch dev 上，发现有冲突。打开冲突文件进行编辑，并将提交信息设定为 "Add feature 3"

14. 将 branch dev 合并到 branch master

15. 0.1 版本开发完毕对 branch master 打标签

16. 你的朋友 S 从你的仓库拉取，更新到最新版本代码，并安全地删除本地 dev 分支。

贡献者：[YuanbinZhou](https://github.com/hduffddybz) [ZhuoZhang](https://github.com/zchrissirhcz)
