# Android Guard 更新日志

<LastUpdated/>

- ## 1.5.6


> 更新时间：2023.4.8

1. 新增华为登录。
2. 新增 OPPO 登录。
3. 新增 Amazon 登录。

<br>

- ## 1.5.5


> 更新时间：2023.3.31

1. 新增 Line 登录。
2. 新增 Slack 登录。

<br>

- ## 1.5.4


> 更新时间：2023.3.24

1. 新增 GitLab 登录。
2. 新增抖音登录。
3. 新增快手登录。
4. 新增小米登录。

<br>

- ## 1.5.3


> 更新时间：2023.3.18

1. 新增 Github 登录。
2. 新增 Gitee 登录。

<br>

- ## 1.5.2


> 更新时间：2023.3.13

1. 修复若干 bug。

<br>

- ## 1.5.1


> 更新时间：2023.3.12

1. 新增百度登录。
2. 新增 Linkedin 登录。
3. 新增钉钉登录。
4. 支持账号密码登录错误图形码校验。

<br>

- ## 1.5.0


> 更新时间：2023.3.5

1. 全新的 UI 样式。
2. 新增 WebAuthn 的生物认证登录认证。
3. 新增推送登录。
4. 新增 QQ 登录。
5. 新增新浪微博登录。
6. 新增事件订阅 API。
7. 支持海外域名配置。

<br>

- ## 1.4.8


> 更新时间：2023.2.14

1. 新增 Facebook 登录。
2. 新增 APP 拉起微信小程序授权登录。
3. 国际化手机号格式校验优化。

<br>

- ## 1.4.7


> 更新时间：2023.1.12

1. 新增微信移动端登录通过账号 ID 绑定已有账号 API。

<br>

- ## 1.4.6


> 更新时间：2022.12.9

1. 修复了微信登录 API bug。

<br>

- ## 1.4.5


> 更新时间：2022.12.6

1. 微信登录授权类 WeChat 支持返回微信授权码。
2. 托管页支持微信登录询问绑定流程。
3. 新增微信移动端登录询问绑定相关 API。
4. 新增解绑 MFA 手机号和邮箱 API。
5. 托管页支持自定义扩展字段登录注册。
6. 新增自定义扩展字段登录注册 API。

<br>

- ## 1.4.4


> 更新时间：2022.10.26

1. 支持登录注册传入额外请求上下文（context）到 Pipeline。
2. 支持配置自动检测网络重新初始化 SDK 数据。
3. 手机号一键登录增加区分运营商的审计日志操作参数。
4. API 请求来源标识改为"Guard-Android@x.x.x"。

<br>

- ## 1.4.3


> 更新时间：2022.10.12

1. 支持登录注册合并。
2. 支持验证码输入框动态配置自动触发登录功能。
3. 优化账号输入框提示语。
4. 优化错误码。

<br>

- ## 1.4.2


> 更新时间：2022.9.5

1. 支持私有化部署设置二级应用域名。

<br>

- ## 1.4.1

> 更新时间：2022.8.30

1. 支持登录组件获取 AccessToken。

<br>

- ## 1.4.0

> 更新时间：2022.8.21

1. 支持 Google 身份源登录。

<br>

- ## 1.3.9

> 更新时间：2022.8.10

1. 信息补全字段展示名称支持与控制台联动。

<br>

- ## 1.3.8

> 更新时间：2022.8.5

1. 新增移动端企业微信代理模式开发。
2. 新增校验账号、密码 API。

<br>

- ## 1.3.7

> 更新时间：2022.7.24

1. updateProfile 支持字段下划线转驼峰格式。
2. 社会化登录跟隐私协议联动。

<br>

- ## 1.3.6

> 更新时间：2022.7.5

1. 升级了 OIDC 身份认证协议。

<br>

- ## 1.3.5

> 更新时间：2022.6.21

1. 优化更新令牌 API。

<br>

- ## 1.3.4

> 更新时间：2022.6.10

1. 优化注册登录获取 code 接口，支持自定义参数。

<br>

- ## 1.3.3

> 更新时间：2022.6.8

1. 支持邮箱验证码注册。
2. 支持控制台一键登录配置的联动。
3. 支持登录注册返回 code。

<br>

- ## 1.3.2

> 更新时间：2022.5.23

1. 更新个人中心。

<br>

- ## 1.3.1

> 更新时间：2022.5.10

1. 修复登出和注销账号时未清理 cookie 问题。

<br>

- ## 1.3.0

> 更新时间：2022.5.10

1. 注册支持 OIDC 模式。
2. 支持电话号码 + 验证码注册。
3. 社会化登录全部支持 OIDC 模式。	

<br>

- ## 1.2.9

> 更新时间：2022.4.27

1. 优化自动登录逻辑。
2. GetVerifyCodeButton 超组件支持多个电话号码。
3. 账号输入框支持动态设置是否记住上次输入。

<br>

- ## 1.2.8

> 更新时间：2022.4.25

1. 一键登录、微信登录获取 Access token、Refresh token。
2. 增加 startWeb API。

<br>

- ## 1.2.7

> 更新时间：2022.4.25

1. 自定义属性名称 src 改为 loginSource。

<br>

- ## 1.2.6

> 更新时间：2022.4.22

1. 新增 updatePhone 接口。
2. 用户中心支持 Fragment。

<br>

- ## 1.2.5

> 更新时间：2022.4.21

1. 登录界面增加 loading 动画。
2. 微信登录英文接入文档。

<br>

- ## 1.2.4

> 更新时间：2022.4.18

1. 解决国家码筛选器问题。

<br>

- ## 1.2.3

> 更新时间：2022.4.6

1. 解决布局没有添加国家码筛选器登录或者注册失败问题。
2. 解决用户登录注册信息补全界面获取手机验证码按钮样式问题。

<br>

- ## 1.2.2

> 更新时间：2022.4.5

1. 支持邮箱验证码登录
2. 支持国际化短信服务
3. 解决社会化登录在 android 11 及以上版本拉起登录页面失败问题

<br>

- ## 1.2.1

> 更新时间：2022.3.25

1. 支持企业微信登录。
2. 解决使用 OIDC 方式调用 loginByAccount 登录失败问题。

<br>

- ## 1.2.0

> 更新时间：2022.3.22

1. 支持飞书登录。
