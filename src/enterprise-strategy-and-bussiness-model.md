# 开源与商业模式

### 业界常见的开源商业模式

| 开源软件商业变现模式 | 说明                                                         | 典型案例                                                     |
| -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 企业版               | 开源版本免费，企业版获得许可和支持服务收入；通过开源向商业版引流 | MySQL，Docker，Cloudera                                      |
| 高级功能收费         | 对面向规模使用的可靠性、安全、管理等进阶功能和工具软件收费   | Redis，核心部分的组件是开源的，但工具类软件和进阶功能（如多租户，无共享分布式架构等）是收费的 |
| 订阅服务             | 开源许可证免除了开源社区对软件质量与缺陷修复的责任，由OSS厂商提供软件订阅服务 | Red Hat，Hortonworks                                         |
| 开源软件集成服务     | 通过软件实施等技术服务收费                                   | SourceLabs公司和SpikeSource公司，这些公司不主推自己的产品品牌，而是与多方开源软件厂商或社区合作 |
| 云服务               | 在公有云上提供基于开源软件的云服务；可通过开源向云服务引流   | MongoDB，Databricks，Elastic Search等提供基于Azure和AWS上的云服务收费 |
| 通过硬件盈利         | 提供开源软件+硬件的一体化方案，通过硬件变现                  | Intel/NVidia/AMD                                             |
| SaaS服务             | 开源核心平台，对接更广泛的应用生态，通过SaaS服务变现         | Gitlab提供开源代码托管服务，开源本身平台以对接更多应用；salesforce等 |
| 应用和流量变现       | 通过开源促成应用，形成行业事实标准，并与应用生态形成绑定进行变现，如广告或Marketplace等 | Goole基于Android生态的广告收入每年超百亿美元                 |



- **企业版、高级收费功能、订阅服务**：这三种是传统理解意义上的开源模式

  开源项目--->服务--->变现--->企业版/Redis/ElasticSearch/订阅服务......

- **集成服务**这种公司相对来说比较少，一般像 sort box 这种大的顾问公司，或者像这个上 works 也好，这个埃森哲原来四大的这个受索的他的顾问公司，他们其实是干这个活的，他们用开源给人搭的，像高端外包 soutboss 的大概人均5000 多美元每天。这是一种模式。

- **云服务引流**成功案例（国内）：阿里Dubbo

  解析：华为的 ServiceComb（微服务） 是凭空想出来的，不是围绕着客户诉求做的，它没有基于用户需求和真正的业务实践来做；而腾讯恰恰相反，它只围绕用户诉求做，其他什么也不做。AWS则不同，在有诉求、有战略、有想法的前提下逐步做大。

  启示：了解客户群体及其痛点，明确诉求。基于当前用户诉求的理解制定商业战略。

- **通过硬件盈利**：硬件的成本是固定的，但随着销售量的增加，边界的利润率是提升的；而软件随着业务的变化，需求也是变化的，且随着客户量的增加，需要投入的支撑人力变多，利润会越来越低。如果做纯软件服务，项目越大、人越多，利润就越来越高，这是定制的逻辑，所以现在市场上都是卖软件、卖服务；但如果企业主要靠硬件盈利，那么开源软件可以作为硬件的搭配，用户可以根据自己需求选择是否使用开源软件。

  案例：英伟达

  从产品业务到未来展望，一文读懂英伟达人工智能所有猫腻  https://www.eefocus.com/mcu-dsp/381873



### 商业模式具体含义和案例

**商业模式决定开源策略：变现有硬件和服务，锚点有标准和流量**

- 案例：Intel构建x86软件生态护城河，硬件变现，成为开源社区最大推手，开源发行版成为新商业模式。

- 解析：
  - 标准思维：软硬件/解决方案变现；
  - 流量思维：流量变现、云服务变现；

- 启示：IT产业商业模式多次前进，产业领导者无一例外设计开源战略作为商业竞争力的重要补充，开源是重要且有效的手段。通过开源，加强生态能力，帮助硬件适配更多的产品，让大家都选他的硬件。这是一个长期战略投资。
