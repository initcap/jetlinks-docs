# 设备上报数据,触发设备告警并发送邮件通知

在设备产品和设备实例中可配置设备告警规则,在设备产品中配置当告警规则,将对产品下所有的设备生效.
如果在设备实例中配置,则只对当前设备生效.

## 创建设备

TODO

## 配置规则

TODO

::: 防抖设置说明

有的时候,设备上报数据在告警阈值左右抖动时,可能联系触发多次告警,此时可以通过配置防抖规则来进行处理。
如: 1分钟内多次告警,只处理1次.在设备产品中配置告警时,将对每一个设备上报的消息进行防抖处理.

:::

## 上报模拟数据

TODO

## 查看告警数据

TODO