# SYSU Health Report Template

[SYSU Health Report](https://github.com/marketplace/actions/sysu-health-report) 的配置模板

**已可以正常运行，仍存在较大不确定性，谨慎使用**

## 使用

- 点击 [Use this template](https://github.com/Editst/SYSU-HealthReport-Template/generate) 创建一个新的仓库（同时点个 Star）。
- 在新仓库中 Settings-Secrets 填写下列信息，注意需要大写，可参考[这里](https://docs.github.com/en/actions/security-guides/encrypted-secrets)。

| NETID | PASSWORD |
| :-----: | :--------: |
| NETID |   密码    |

## 定时运行

默认配置为每天 22:00、23:00 UTC 运行，对应运行时间约为 6:00、7:00 Asia/Shanghai（实际上会存在延迟），如需修改时间请参考[这里](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows#schedule)。

## TODO

**欢迎提交 pr 来增加其他通知推送方式。**

## 免责声明

此脚本仅供学习交流，禁止商业使用，使用软件过程中，发生意外造成的损失由使用者承担。如遇身体不适、或居住地址发生变化，请及时更新健康申报信息。
