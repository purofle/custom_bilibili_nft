# custom_bilibili_nft

自定义 B 站 NFT 空间背景和头像全自动版本

原项目：[XiaoMiku01/custom_bilibili_nft](https://github.com/XiaoMiku01/custom_bilibili_nft)

该项目在原有基础上增加扫码登陆，无需手动输入 uid 跟 access_key

## 运行环境

python3.8+

## 安装依赖库

```bash
pip install requests requests_toolbelt qrcode
```
## 注意

- 必须有个 R 级别的卡 (可通过在手机端 B 站搜索三体在三体页面获取) ，其他集合自行更换 第 136 行的 `act_id` 参数
