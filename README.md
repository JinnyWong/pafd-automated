# 🌎 Automated PAFD for International students settings

首先请注册一个 GitHub 帐号，然后点击右上角的 fork 创建一个副本。

![fork](https://github.com/fducslg/pafd-automated/blob/master/docs/fork.png?raw=true)

然后在你 fork 的副本中，点击 Settings, Secrets 和 New secret

![create-secrets](https://github.com/fducslg/pafd-automated/blob/master/docs/create-secrets.png?raw=true)

然后创建两个值，Name 为 STD_ID 的在 Value 里填入学号

![id](https://github.com/fducslg/pafd-automated/blob/master/docs/id.png?raw=true)

![password](https://github.com/fducslg/pafd-automated/blob/master/docs/password.png?raw=true)

Name 为 PASSWORD 的在 Value 里填入 UIS 密码。这里可以不用担心安全性问题，这些 scecrets 的值只有你能看见，此外因为背后是 GitHub 为你保障安全——GitHub 的安全性应该比复旦的 UIS 要高。

通过 GitHub Action，每天十点会自动运行脚本帮你填写 PAFD，填写的地址是上一次的位置，从而你再也不用担心被辅导员催啦~
