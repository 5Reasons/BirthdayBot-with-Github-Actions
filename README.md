# BirthdayBot-with-Github-Actions

本项目是一个生日/重要纪念日自动提醒bot。使用`GitHub Actions`，在朋友生日/重要节假日前，通过邮件/短信等方式自动提醒。朋友生日的数据全部托管在`GitHub`上，一次配置永久使用，防止忘记～

## Todo-List

- [x] 构建一个简单的邮件发送 demo
- [ ] 节日自动配置（母亲节、父亲节）
- [ ] 阴历农历配置（这个可以参考一下别人代码）
- [ ] 支持参数配置（提前多少天等等）
- [ ] 参数加密等等
- [ ] 日期最多支持提前30天；需要搞一个专门的 ifValid 函数，检测 YAML 的合法性（提前日期数组有没有超过30天的、有没有重复等等，如果有问题的话给自己发个邮件解释错误）
- [ ] 支持短信服务 (这个可以在 config 那边搞成选配，用天翼云的接口吧，按量计费便宜一些)
- [ ] 搞一个静态页面部署在 github pages 上，支持读取现有的配置文件、修改现有的配置文件（Github API等）（考虑一下用自己的那个 Mac Docker动画，结合一下日历？哈哈哈）
