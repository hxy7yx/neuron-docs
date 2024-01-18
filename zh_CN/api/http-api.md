# HTTP API

IIoT平台或其他监控应用可以通过使用提供的HTTP-API来监视和控制Neuron设备。这些API的关键功能如下：

[获取数据：](./rw.md) HTTP-API允许平台监视与IIoT平台连接的设备所获取的数据。这使得能够实时监控传感器读数、操作参数和设备状态。

[控制命令：](./rw.md) API还支持向Neuron设备发送控制命令，使平台能够远程控制和管理设备。这实现了对设备功能的无缝管理。

[远程设置和配置：](./configuration.md) 平台可以通过HTTP-API远程设置和配置设备连接。这确保了在无需物理访问的情况下方便高效地管理设备。[插件设置](./plugin-setting.md) 也可用。

[JWT身份验证：](./jwt.md) API采用JWT身份验证，确保IIoT平台或监控应用与Neuron设备之间的安全通信和身份验证。这增强了系统的整体安全性。

[Prometheus兼容指标：](./metrics.md) API提供与Prometheus兼容的指标数据。这使得可以轻松与Prometheus监控工具集成，便于对设备指标进行有效监控和分析。

[错误代码描述：](./data-type.md) API包括全面的错误代码描述，提供有关遇到的错误的性质和原因的信息。这有助于有效的故障排除和问题解决。

[数据类型描述：](./error-code.md) 为了确保数据的表示和解释清晰一致，API描述了使用的数据类型。这促进了IIoT平台或监控应用中数据的无缝集成和分析。
