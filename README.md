# VPS 黑五优惠：年付折扣怎么算、特价机怎么抢，洛杉矶/香港/东京 CN2 GIA 套餐价格全对比

黑五买 VPS，最常翻车的不是"抢不到"，而是买完才发现第二年续费直接翻倍。

每年这个时候，各家机房都会挂出一批"低至 X 折"的横幅。折扣数字很好看，但真正决定你花多少钱的从来不是那个百分比，而是折扣的类型：只算首单还是续费照算？是降月费还是砍配置？搞清楚这一层，比研究两家差 2 美元有用得多。

下面以 DMIT（圈内叫"大妈"）为主线，把黑五 VPS 的账算清楚——它家产品线怎么分、哪些套餐在黑五期间会掉到一个值得下手的价位、优惠码怎么验证、还有哪几款是典型的"看着便宜但别买"。

## 黑五的 VPS 折扣，其实只有五种玩法

各家机房的促销文案五花八门，落到账面上无非这几种：

**年付折扣**：按月付价 × 12 再打个折。DMIT 的 T1 系列年付换算下来普遍比月付便宜两到三成，这是最实在的一类。

**循环折扣（recurring）**：优惠码标着 `RECURRING` 或 `RECUR` 的，意思是续费时同样生效，不是只坑第一年。DMIT 放出的优惠码大多属于这一类，这一点比很多同行厚道。

**特价限量机**：单独开一个 SKU，配置比同价位常规款低一档，但价格压得很狠。DMIT 每年黑五都会放这类机器，编号里带 `WEE` 的一般就是——它家 WEE 系列常年属于特惠线，通常不叠加优惠码。

**返账户金**：不直接减价，而是消费满一定金额后返余额到账户里。DMIT 往年做过"洛杉矶月付订单每累计 100 美元返 35 美元账户金"，返的钱只能继续在站内消费，不能提现。

**买赠 / 加量**：买两台送一台，或者年付多送 50% 流量。往年的黑五 DMIT 就出过"Pro 或 EB 常规机型买二送一"，以及"东京 EB 系列额外赠送最高 30% 流量"。

这里有个容易被忽略的点：**特价限量机通常不参与优惠码，常规款才参与**。看到"$36.9/年"这种价格时，先确认它是特价 SKU 还是常规款打折后的结果，两者的续费逻辑完全不同。

## DMIT 的产品线：Pro / EB / T1 到底差在哪

DMIT 主要在美国洛杉矶（LAX）、中国香港（HKG）、日本东京（TYO）三个机房卖 KVM 架构的 VPS，全系 AMD EPYC 处理器 + NVMe SSD。它不按"入门/进阶/旗舰"分档，而是按**线路质量**分三条产品线：

- **Premium（Pro）**：三网回程 CN2 GIA，电信用户体验最好的一档。洛杉矶 Pro 的走法是电信、联通去程 CN2 GIA，移动去程 CMI，三网回程统一走 CN2 GIA。价格最贵。
- **Eyeball（EB）**：电信、联通走 AS9929，移动走 CMIN2。流量和带宽通常是同价位 Pro 的两倍，性价比路线。
- **Tier 1（T1）**：纯国际线路，对中国大陆没有优化。电信联通双程 NTT，偶尔绕美走 Lumen，移动走 CMI。优势是带宽大、流量多、超量后限速不停机。

一句话总结选购逻辑：**建站和代理看 Pro，大流量下载和中转看 EB，纯国际业务或者只是要个便宜落脚点看 T1。**

按现在的货架情况，洛杉矶的硬件分 AS3（EPYC 7003）、AN4（EPYC 9004）、AN5（EPYC 9005）三批，同型号不同批次的配置和价格会有差异；香港、东京则以 AS3 为主。这意味着一件事：**同一个套餐名，你看到的报价可能和别人不一样**，下单前必须看结算页的实际数字。

👉 [查看 DMIT 官网当前在售套餐与实时价格](https://www.dmit.io/aff.php?aff=12046)

## DMIT 全部套餐价格对比

下面的表覆盖官网当前在售的常规套餐。流量均为双向计算——标 1TB 就是上下行加起来 1TB，实际可用额度大致相当于标注值的一半，买之前心里要有数。

### 美国洛杉矶 LAX · Premium（Pro）系列

三网回程 CN2 GIA，适合对国内访问速度有要求的建站和长期业务。

| 套餐 | CPU | 内存 | 硬盘 | 流量 / 带宽 | 价格 | 计费周期 | 购买 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LAX.AS3.Pro.TINY | 1 核 | 2 GB | 20 GB SSD | 1 TB @1Gbps | $10.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.Pro.Pocket | 2 核 | 2 GB | 40 GB SSD | 1.5 TB @4Gbps | $16.90 | 月付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.Pro.STARTER | 2 核 | 2 GB | 80 GB SSD | 3 TB @10Gbps | $34.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.Pro.MINI | 4 核 | 4 GB | 80 GB SSD | 5 TB @10Gbps | $62.90 | 月付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.Pro.MICRO | 4 核 | 4 GB | 160 GB SSD | 7 TB @10Gbps | $87.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.Pro.WEE | 1 核 | 1 GB | 20 GB SSD | 500 GB @500Mbps | $36.90 | 年付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |
| LAX.Pro.MALIBU | 1 核 | 1 GB | 20 GB SSD | 1000 GB @1Gbps | $49.90 | 年付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |

WEE 和 MALIBU 是这条线上少见的年付特价款，配置比常规 TINY 低，但把 CN2 GIA 的入场价压到了 40 美元以内。Pro 系列的流量超出后不限速到 4–10 Mbps，属于"网慢但不断"的处理方式。

### 美国洛杉矶 LAX · Eyeball（EB）系列

电信联通走 9929、移动走 CMIN2，同价位流量普遍是 Pro 的两倍。

| 套餐 | CPU | 内存 | 硬盘 | 流量 / 带宽 | 价格 | 计费周期 | 购买 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LAX.AS3.EB.TINY | 1 核 | 2 GB | 20 GB SSD | 1.5 TB @2Gbps | $10.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.EB.Pocket | 2 核 | 2 GB | 40 GB SSD | 3 TB @4Gbps | $16.90 | 月付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.EB.STARTER | 2 核 | 2 GB | 80 GB SSD | 5 TB @10Gbps | $34.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.EB.MINI | 4 核 | 4 GB | 80 GB SSD | 10 TB @10Gbps | $62.90 | 月付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.EB.MICRO | 4 核 | 4 GB | 160 GB SSD | 14 TB @10Gbps | $87.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.EB.WEE | 1 核 | 1 GB | — | 800 GB @1Gbps | $39.90 | 年付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |

对比一下 TINY 这一档：同样是 $10.90/月，EB 给 1.5 TB 流量和 2Gbps 口，Pro 只给 1 TB 和 1Gbps。差的是线路——Pro 的回程 CN2 GIA 在晚高峰的稳定性上依然更胜一筹。如果你主要用移动宽带，EB 的实际体感可能比 Pro 还好。

### 香港 HKG · Premium 与 Eyeball

香港的最大优势是延迟，大陆访问通常在 10–30ms 区间，缺点是流量给得少、单价高。

| 套餐 | CPU | 内存 | 硬盘 | 流量 / 带宽 | 价格 | 计费周期 | 购买 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| HKG.AS3.Pro.TINY | 1 核 | 1 GB | 20 GB SSD | 500 GB @1Gbps | $39.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AS3.Pro.STARTER | 1 核 | 2 GB | 40 GB SSD | 1000 GB @1Gbps | $79.90 | 月付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AS3.Pro.MINI | 2 核 | 4 GB | 60 GB SSD | 1500 GB @1Gbps | $126.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AS3.Pro.MICRO | 4 核 | 4 GB | 80 GB SSD | 2000 GB @1Gbps | $179.90 | 月付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AS3.Pro.MEDIUM | 4 核 | 8 GB | 160 GB SSD | 2500 GB @1Gbps | $239.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AS3.EB.TINYv2 | 1 核 | 1 GB | 20 GB SSD | 1000 GB @1Gbps | $29.90 | 月付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AS3.EB.STARTERv2 | 1 核 | 2 GB | 40 GB SSD | 2000 GB @2Gbps | $59.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AS3.EB.MINIv2 | 2 核 | 2 GB | 60 GB SSD | 3000 GB @2Gbps | $89.90 | 月付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AS3.EB.MICROv2 | 4 核 | 4 GB | 80 GB SSD | 4000 GB @4Gbps | $129.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AS3.EB.MEDIUMv2 | 4 核 | 8 GB | 160 GB SSD | 6000 GB @4Gbps | $199.90 | 月付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AS3.EB.LARGEv2 | 8 核 | 16 GB | 320 GB SSD | 12000 GB @4Gbps | $389.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AS3.EB.GIANTv2 | 8 核 | 24 GB | 640 GB SSD | 24000 GB @4Gbps | $789.90 | 月付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |

香港 Pro 的流量超出后是暂停，不是限速，这点和洛杉矶不同，买之前要确认自己的用量。EB v2 系列是后来重做的产品线，同价位流量给了 Pro 的两倍，是香港节点里比较务实的选择。

### 日本东京 TYO · Premium

| 套餐 | CPU | 内存 | 硬盘 | 流量 / 带宽 | 价格 | 计费周期 | 购买 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TYO.AS3.Pro.TINY | 1 核 | 1 GB | 20 GB SSD | 500 GB @1Gbps | $21.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| TYO.AS3.Pro.STARTER | 1 核 | 2 GB | 40 GB SSD | 1000 GB @1Gbps | $45.90 | 月付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |
| TYO.AS3.Pro.MINI | 2 核 | 4 GB | 60 GB SSD | 2000 GB @1Gbps | $89.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| TYO.AS3.Pro.MICRO | 4 核 | 4 GB | 80 GB SSD | 4000 GB @1Gbps | $189.90 | 月付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |
| TYO.AS3.Pro.MEDIUM | 4 核 | 8 GB | 160 GB SSD | 6000 GB @1Gbps | $320.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| TYO.AS3.Pro.LARGE | 8 核 | 16 GB | 320 GB SSD | 8000 GB @1Gbps | $429.90 | 月付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |
| TYO.AS3.Pro.GIANT | 8 核 | 24 GB | 640 GB SSD | 15000 GB @1Gbps | $829.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |

东京 Pro 的流量超出后同样是暂停。江浙沪、山东、福建一带的用户访问东京的延迟通常比洛杉矶低，但 2025 年香港和东京机房经历了持续 DDoS 攻击，网络稳定性一度受影响，官方因此给存量用户补送了洛杉矶 Pro 或 T1 产品。这类情况会直接反映在价格和库存上，出手前先看一眼官网公告。

### Tier 1（T1）系列 · 洛杉矶 / 香港 / 东京

三个机房的 T1 配置和价格基本一致，差别只在超量限速的档位。这是 DMIT 最便宜的一条线。

| 套餐 | CPU | 内存 | 硬盘 | 流量 / 带宽 | 价格 | 计费周期 | 购买 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| T1.WEE | 1 核 | 1 GB | 20 GB SSD | 1000 GB @4Gbps | $36.90 | 年付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| T1.TINY | 1 核 | 1 GB | 20 GB SSD | 2000 GB @4Gbps | $6.90 | 月付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |
| T1.STARTER | 1 核 | 2 GB | 40 GB SSD | 4000 GB @10Gbps | $12.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| T1.MINI | 2 核 | 2 GB | 60 GB SSD | 8000 GB @10Gbps | $21.90 | 月付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |
| T1.MICRO | 4 核 | 4 GB | 80 GB SSD | 16000 GB @10Gbps | $32.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| T1.MEDIUM | 4 核 | 8 GB | 160 GB SSD | 32000 GB @10Gbps | $49.90 | 月付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |
| T1.LARGE | 8 核 | 16 GB | 320 GB SSD | 64000 GB @10Gbps | $99.90 | 月付 | [查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| T1.GIANT | 8 核 | 24 GB | 640 GB SSD | 128000 GB @10Gbps | $199.90 | 月付 | [查看配置与价格](https://www.dmit.io/aff.php?aff=12046) |

T1 的核心卖点是**超量不停机**：流量跑完后降到 50–500 Mbps 继续用，不额外收费也不断网。香港和东京的 WEE 超量后限速 50Mbps，洛杉矶 WEE 限速 100Mbps。拿它做流量中转或者跑些不吃延迟的活儿，比按流量计费的方案省心。

> 以上价格整理自官网公开页面与多方公开资料。DMIT 会随硬件批次（AS3 / AN4 / AN5）和库存状况调整配置与报价，部分热门套餐长期缺货。**下单前请以结算页显示的最终价格为准。**

## 优惠码：这几组还可能有效，但要自己验证

DMIT 的优惠码基本都是**循环折扣**，续费同样生效。以下是近期在多方资料中出现频次较高、值得一试的几组：

| 优惠码 | 适用范围 | 折扣 | 计费周期要求 |
| --- | --- | --- | --- |
| `202510_HKG_TYO_PRO_20OFF_RECURRING` | 香港 Pro / 东京 Pro | 8 折，循环 | 季付及以上 |
| `202510_HKG_TYO_T1_30OFF_RECURRING` | 香港 T1 / 东京 T1（不含 WEE） | 7 折，循环 | 季付及以上 |
| `2025-TYO-T1-HI-GSL-NON-MONTHLY-30OFF` | 东京 T1 TINY 及以上 | 7 折 | 季付及以上 |
| `2025-TYO-T1-HI-GSL-MONTHLY-10OFF` | 东京 T1 TINY 及以上 | 9 折 | 月付 |
| `LAX-EB-LAUNCH-NON-MONTHLY-RECURRING-20OFF` | 洛杉矶 EB TINY 及以上 | 8 折，循环 | 非月付 |
| `LAX-Pro-Pocket-Annually-Override-99` | 洛杉矶 Pro.Pocket | 限时 5 折 | 年付 |
| `TYO-Pro-TINY-Annually-Override-119` | 东京 Pro.TINY | 限时 5 折 | 年付 |

用法很直接：选好套餐和付款周期，在结算页把码填进去，点 **Validate Code** 验证。验不过说明这个码对你选的套餐不适用——大部分码都限定了产品线和计费周期，别拿香港的码去试东京的机器。

两点提醒。第一，**WEE 系列一般不吃优惠码**，因为本身已经是特惠价。第二，往年出现过用了失效促销码、订单被退款的情况，所以别用没验证过的码去买还要跑生产数据的机器，先用验证按钮确认通过再付款。

## 黑五期间具体该盯哪几款

DMIT 的常规套餐常年偏贵，真正的性价比集中在黑五放出来的特价机上。按预算分三档看：

**年付 40 美元以内**——盯洛杉矶 Pro.WEE 和 LAX.EB.WEE。前者的 CN2 GIA 三网回程在这个价位几乎没有对手，缺点是 500 GB 双向流量对单人使用略紧。如果只是要个能直连的落地点、偶尔开开 AI 服务，这个价位够用。

**年付 50–150 美元**——LAX.Pro.MALIBU（$49.90/年）比 WEE 多 550 GB 流量、带宽升到 1Gbps，是 WEE 卖完之后的顺位选择。另外往年黑五出现过洛杉矶 CN2 GIA 高防款，2 核 2 GB 内存、1 TB 流量 @300Mbps、年付 $139，去程走 Cloudflare Magic Transit 自带 5Tbps 级别的国际共享防护，回程仍是 CN2 GIA。有被攻击风险的项目值得考虑。

**年付 300 美元以上**——东京 Pro 和香港 Pro 的 STARTER 档。这两个机房的价值在延迟而不是配置，如果你的业务对大陆访问延迟敏感，多花的钱买的是那二三十毫秒。

**不太建议盲买的**：香港 Pro 的 TINY 档，$39.90/月只给 500 GB 双向流量，超量还要暂停。除非你确实是香港节点的刚需用户，否则同样的预算在洛杉矶能买到配置高一大截的机器。

## 抢购实操：几个会真实影响结果的动作

先把 Looking Glass 用起来。DMIT 的测试节点在 `lg.dmit.sh`，参数分别是 `lax-pro`、`lax-eb`、`lax-t1`、`hkg-pro`、`hkg-eb`、`hkg-t1`、`tyo-pro`、`tyo-t1`，对应的测试 IP 包括洛杉矶 154.17.30.96、香港 103.117.100.199、东京 154.12.190.32。用自己的宽带跑一遍 ping 和路由追踪，比看任何人的测评都准。

库存是硬约束。洛杉矶 AN4 平台的套餐此前就因为硬件资源耗尽被官方关闭销售，香港和东京的 Pro 也长期断货。热门款在黑五当天基本是几小时内清空，想买就设好闹钟，别指望第二天还有货。

付款方式对国内用户比较友好，支付宝、微信、PayPal、信用卡都能用。IP 方面，被墙的 IP 每 15 天可以免费更换一次，其他情况每次 $5；月付订单不保证分配的 IP 全球可用，如果你在意这一点，结算时可以加购 IP 保证服务。

还有一条容易被忽略：**DMIT 支持跨机房内网互通**。香港—美国、日本—美国、香港—日本之间可以走内网传数据，如果你同时买了两个机房，做数据同步时不用走公网。

👉 [去 DMIT 查看当前库存与黑五活动](https://www.dmit.io/aff.php?aff=12046)

## 总结一下判断顺序

黑五买 VPS 的正确顺序是：先确认折扣是循环还是首单，再看清流量是单向还是双向，接着用 Looking Glass 实测延迟，最后才比价格。

具体到 DMIT：预算紧张就等 WEE 类的年付特价款，要稳定建站就上洛杉矶 Pro，移动宽带为主可以考虑 EB，对延迟敏感再考虑东京和香港。优惠码记得在结算页先验证再付款，别拿没验过的码去下单。

价格和库存随时在变，动手前花两分钟看一眼官网的实时页面，比看任何一篇整理文章都靠得住。

👉 [前往 DMIT 官网查看全部套餐](https://www.dmit.io/aff.php?aff=12046)
