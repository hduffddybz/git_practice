1. 在 branch master 有 a.txt 文件，增加如下内容"Initilize project",并以 "First commit" 信息来提交

2. 基于branch master 创建 branch dev，在 a.txt 增加如下内容"Add feature 1",并以 "Modify a.txt" 信息来提交

3. 在 branch dev 发现 "Modify a.txt" 不能反映所做更改的内容，修改提交信息为 "Add feature 1"

4. 将 branch dev 合并到 branch master

5. 发现 First commit 中的 "Initilize project" 提交错误（对应于现实开发中重大的 bug），故在 branch bug 修复该问题，并以 "Correct errors in the first commit" 来提交，在修复该 bug 的同时，在 branch dev 同时进行 Add feature2 的开发工作

6. 将 branch bug 合并到 branch master

7. 这时候在 branch dev 的 fearture 2 开发完毕，以 "Add feature 2" 信息来提交

8. 发现 feature 2 的修改不完善，增加内容为 "Add full feature 2", 不增加新的提交信息

9. 将 branch dev 合并到 branch master

10. 在 branch dev 进行 "Add feature 3.1" 的开发，并以 "Add feature 3.1" 来提交信息，同时一个远程分支同步了上述 8 个步骤的更改，并同时在做相同特性的开发，以 "Add feature 3.2" 进行提交，同一个特性出现了两个版本，这时候需要解决冲突，更改内容为 "Add feature 3"，并将提交信息更改为 "Add feature 3"

11. 将 branch dev 合并到 branch master

12. 0.1 版本开发完毕对 branch master 打标签
