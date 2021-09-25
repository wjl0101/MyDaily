# DailyFudan

### Usage
此项目是根据这个[项目](https://github.com/xnuohz/DailyFudan)做了一点小小的改动(新增关联server酱推送打卡功能),为了防止后面叫fudan的又被删了，自己建了一个仓库
- Fork this repository
- Create a secret in `Settings`, `Name` should be FUDAN for [this line](https://github.com/shwangshoudao/MyDaily/blob/main/.github/workflows/main.yml#L47) while `Value` should be `{uid} {passward}` (notice there is a whitespace between them)
- If you need to associate a WeChat push, please bind the server酱 for push at [this link](https://sct.ftqq.com/) to get the sendkey. After you get the sendkey, please change the sendkey at [this line](https://github.com/shwangshoudao/MyDaily/blob/main/main.py#L68).
- Run the workflow named as `Daily Fudan` in `Actions`
