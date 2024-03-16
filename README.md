# Pull_Local_Git_Repo
**`February 5, 2024 / by Yu-Shin, Hu`**

-   程式碼可用來自動更新所有本地倉庫中的所有分支 (假設github中檔案已clone到本地且名稱相同)。
-   The code is designed to automatically update all branches of all local repositories (suppose they have been cloned locally and have the same name).

## Steps <br>

**Step 1. Generate personal access token**
-   The way to generate tokens can be referred to: [How to use github token](https://blog.csdn.net/chengwenyang/article/details/120060010)
-   To access commit status and private repositories, grant permissions to `repo` and `user`.

**Step 2. Run the Script**
-   Assign a local folder that contains either all or a subset of repositories cloned from GitHub.
-   Input your GitHub username and personal access token.

