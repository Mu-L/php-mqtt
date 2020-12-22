# Protocol API

使用`pack`和`unpack`按照 MQTT 协议来进行打包和解析。

## MQTT 3.1.x

```php
Simps\MQTT\Protocol::pack(array $array)

Simps\MQTT\Protocol::unpack(string $data)
```

## MQTT 5.0

```php
Simps\MQTT\ProtocolV5::pack(array $array)

Simps\MQTT\ProtocolV5::unpack(string $data)
```

## Constants

MQTT 协议等级和名称的常量

```php
Simps\MQTT\ProtocolInterface::MQTT_PROTOCOL_LEVEL_3_1; // 3.1
Simps\MQTT\ProtocolInterface::MQTT_PROTOCOL_LEVEL_3_1_1; // 3.1.1
Simps\MQTT\ProtocolInterface::MQTT_PROTOCOL_LEVEL_5_0; // 5.0

Simps\MQTT\ProtocolInterface::MQISDP_PROTOCOL_NAME; // MQIsdp
Simps\MQTT\ProtocolInterface::MQTT_PROTOCOL_NAME; // MQTT
```