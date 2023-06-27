# How to use
1. Fork this repository or download the repository and create a new repository by uploading it again.
2. In your user profile, go to Settings - Developer settings, Apply for a token. In your new repository, go to Setting->Security->Secrets->Actions, create a Repository secrets named "ISSUE_TOKEN" with the value being the token you just obtained.
3. Modify the settings in `config.py` as per your requirements.
4. If your repository does not have a `.github/workflows/` folder and the `arxiv_daily.yml` file within it, create the folder yourself and copy the `arxiv_daily.yml` file from this repository into it.
5. (Optional) Modify the `arxiv_daily.yml` file to set your preferred time for automated pushes.
6. Enable GitHub Actions for your repository under the "Actions" tab.
7. Now, your repository is set up for scheduled pushes!

# 如何使用
1. fork本repository，或打包下载再新建repository重新上传也行
2. 在个人中心的setting - developer settings里申请一个普通的访问令牌Token；在你的新repository的Setting->Security->Secrets->Actions下，创建一个Repository secrets，名字写为ISSUE_TOKEN，数据改为自己刚申请的Token
3. 修改`config.py`下的各项信息
4. 如果你的repository此时并没有`.github/workflows/`文件夹及其中的`arxiv_daily.yml`，则自行创建此文件夹并把本repository的`arxiv_daily.yml`复制过去
5. （可选）通过修改`arxiv_daily.yml` 更改自动推送时间为你喜欢的时间
6. 在你的repository的Actions里开启Github actions权限
7. 现在你的repository可以定时推送了！
