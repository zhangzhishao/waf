# 配置WAF日志服务 {#concept_p1p_3mg_qfb .concept}

购买Web应用防火墙（WAF）服务后，如果您的网站业务需要详细的实时日志查询和分析服务，您可以在控制台的应用管理中开通日志实时查询分析服务。

## 适用范围 {#section_ovc_vng_qfb .section}

通过利用日志服务（SLS）的功能实时采集已接入WAF防护的网站业务各类日志，并对采集到的日志数据进行实时检索与分析，以丰富的仪表盘形式展示查询结果。WAF日志服务完全满足等保合规要求和您网站业务防护和运营需求，您可以在购买开通WAF日志服务时根据实际需要，选择存储时长和存储容量大小。

**说明：** WAF日志服务目前仅对Web应用防火墙包年包月实例开通，包括高级版、企业版、旗舰版。

## 功能优势 {#section_kj4_hr1_rfb .section}

WAF日志实时查询分析服务具有以下功能优势：

-   **等保合规**：存储网站六个月以上的访问日志，助力网站符合等保合规要求。
-   **配置灵活**：轻松配置即可实现Web访问与攻击日志的实时采集。同时，支持自定义日志存储的时长和容量，自由选择日志采集的网站。您还可以根据自己的业务需求修改或者重新自定义符合自己业务或安全需求或者安全需求的报表模板，帮助您快速感知网站业务和安全状态。
-   **实时分析**：依托日志服务产品，提供实时日志分析能力、开箱即用的报表中心，让您对网站业务的各种Web攻击状况以及客户访问细节了如指掌。
-   **实时告警**：支持基于特定指标定制准实时的监测与告警，确保在关键业务发生异常时能第一时间响应。
-   **生态体系**：支持对接其他生态如实时计算、云存储、可视化等方案，进一步挖掘数据价值。

## 开通WAF日志服务 {#section_vmk_ppg_qfb .section}

1.  登录[Web应用防火墙管理控制台](https://yundun.console.aliyun.com/?p=waf)。
2.  定位到**市场管理** \> **应用管理**页面，选择您的WAF实例所在地域。
3.  单击日志实时查询分析服务区域中的**升级**。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/40708/154321767321264_zh-CN.png)

4.  在Web应用防火墙购买页面，勾选**日志服务**，根据您的业务需要选择日志存储时长和存储容量，单击**去支付**并完成支付。

    **说明：** 关于WAF日志服务收费标准，参考[WAF日志服务计费方式](intl.zh-CN/用户指南/日志实时查询分析/计费方式.md#)。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/40708/154321767321266_zh-CN.png)

5.  回到Web应用防火墙的**市场管理** \> **应用管理**页面，在日志实时查询分析服务区域单击**授权**。
6.  单击**同意授权**，授权WAF将日志存储至您的专属日志库中。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/40708/154321767321284_zh-CN.png)

    至此，您已完成WAF日志服务的开通与授权。

7.  回到Web应用防火墙的**市场管理** \> **应用管理**页面，在日志实时查询分析服务区域单击**配置**。
8.  在日志服务页面，选择已接入WAF防护的网站域名，单击域名右侧的**状态**开关，为该网站域名开启WAF日志服务。

    日志服务将实时采集WAF记录到的该网站域名的所有日志，并根据采集到的日志数据进行实时检索与分析。


