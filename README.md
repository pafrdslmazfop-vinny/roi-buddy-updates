# ROI buddy · 安装包发布

安卓版 **ROI buddy** 的构建产物镜像仓库。这是一个直播电商 ROI 保本测算工具，
与 [roi-grok-updates](https://github.com/pafrdslmazfop-vinny/roi-grok-updates) 是两条独立产品线。

## 最新版本

| 项 | 值 |
|---|---|
| 版本 | **v1.10.19**（versionCode 11019） |
| 文件 | `ROI-buddy-v1.10.19-Android.apk` |
| 大小 | 119,650 字节 |
| SHA256 | `71fa2fe8afd41b631880dead079a166455a28b24d4eea5c379ce0fe201b91458` |
| 包名 | `com.cofot.roicalc` |

## 下载

- 仓库内：`ROI-buddy-v1.10.19-Android.apk`
- 直链：https://raw.githubusercontent.com/pafrdslmazfop-vinny/roi-buddy-updates/main/ROI-buddy-v1.10.19-Android.apk
- 官方下载页：https://roi-calc-update.app.workbuddy.host/?sharecode=DRHZJCGYYA

## 本版更新

1. 参数页改回三个独立折叠栏：成本明细 / 费用比例 / 退货率，默认收起，标题右侧显示合计与签收摘要
2. 首次同步不再三选一，直接按产品逐个取较新合并
3. 售后四类占比留空时自动套用出厂预配置，避免「发货」折算档失效
4. 平台服务费口径确认：按成交金额、货款到账才扣，退款不产生

> 安装包需覆盖安装时，versionCode 必须比已装版本大；签名 keystore 不可更换，否则无法覆盖。
