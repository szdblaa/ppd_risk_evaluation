“魔镜杯”风控算法大赛 比赛详情：https://www.kesci.com/home/competition/56cd5f02b89b5bd026cb39c9/content

比赛数据

本次大赛将公开国内网络借贷行业的贷款风险数据，包括信用违约标签（因变量）、建模所需的基础与加工字段（自变量）、相关用户的网络行为原始数据。本着保护借款人 隐私以及拍拍贷知识产权的目的，数据字段已经过脱敏处理。

数据编码为GBK。初赛数据包括3万条训练集和2万条测试集。复赛会增加新的3万条数据，供参赛团队优化模型，并新增1万条数据作为测试集。所有训练集，测试集都包括3 个csv文件.

Master

每一行代表一个样本（一笔成功成交借款），每个样本包含200多个各类字段。

idx：每一笔贷款的unique key，可以与另外2个文件里的idx相匹配。

UserInfo_*：借款人特征字段

WeblogInfo_*：Info网络行为字段

Education_Info*：学历学籍字段

ThirdParty_Info_PeriodN_*：第三方数据时间段N字段

SocialNetwork_*：社交网络字段

LinstingInfo：借款成交时间

Target：违约标签（1 = 贷款违约，0 = 正常还款）。测试集里不包含target字段。

Log_Info

借款人的登陆信息。

ListingInfo：借款成交时间

LogInfo1：操作代码

LogInfo2：操作类别

LogInfo3：登陆时间

idx：每一笔贷款的unique key

Userupdate_Info

借款人修改信息

ListingInfo1：借款成交时间

UserupdateInfo1：修改内容

UserupdateInfo2：修改时间

idx：每一笔贷款的unique key