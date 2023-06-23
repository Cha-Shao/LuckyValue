# 算命占卜

### 使用

`/lve` 获得自己的幸运值

`/lve [player_name]` 获得其他玩家的幸运值

`/lveforce [player_name]` 强制获得未在线玩家的幸运值，将不会发送到聊天栏

`/lvereload` 重载配置文件

### PAPI

`%luckyvalue%` 自己的幸运值

`%luckyvalue_<player>%` 指定玩家的幸运值

### 权限

`lve.get` 获得自己的幸运值 `默认开启`

`lve.other` 获得其他玩家的幸运值

`lve.force` 强制获得未在线玩家的幸运值

`lve.reload` 重载配置文件

### 配置文件

#### message:
  - at_100: 幸运值 100 时发送的消息
  - at_99: 幸运值 99 时发送的消息
  - lt_90: 幸运值 98-90 时发送的消息
  - lt_60: 幸运值 89-60 时发送的消息
  - lt_50: 幸运值 59-51 时发送的消息
  - at_50: 幸运值 50 时发送的消息
  - lt_40: 幸运值 49-40 时发送的消息
  - lt_11: 幸运值 39-11 时发送的消息
  - lt_1: 幸运值 10-2 时发送的消息
  - at_1: 幸运值 1 时发送的消息

#### secret
幸运值的随机种子

#### notOnline
目标玩家不在线时的消息

#### needPlayer
强制获得指令未指定玩家时的消息

#### noPermission

没有权限时的消息
