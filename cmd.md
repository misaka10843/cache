| 命令| 用法 | 权限节点| 可用性 | 注释 | 别名|
| -------------- | -------------------------------------------- | ------------------------- | -------- | ------------------------------------------ | ----------------------------------------------- |
| changescene| `changescene <场景ID>` | player.changescene| 仅客户端 | 切换到指定场景 | scene |
| clear| `clear <all\|wp\|art\|mat> [UID]` | player.clearinv | 仅客户端 | 删除所有未装备及未解锁的圣遗物(art)或武器(wp)或材料(mat)或者所有(all),包括五星| clear |
| drop | `drop <物品ID\|物品名称> [数量]` | server.drop | 仅客户端 | 在指定玩家周围掉落指定物品 | `d` `dropitem`|
| enterdungeon | `enterdungeon <地牢ID>`| player.enterdungeon | 仅客户端 | 进入某个地牢| |
| give | `give [uid] <物品ID\|物品名称> [数量] [等级] [精炼等级]`| player.give| 均可使用 | 给予指定玩家一定数量及等级的物品 (精炼等级仅适用于武器)| `g` `item` `giveitem`|
| givechar | `givechar \<uid> <角色ID> [等级]` | player.givechar | 均可使用 | 给予指定玩家对应角色 | givec |
| giveart| `giveart [uid] \<圣遗物ID> \<主属性ID> [\<副属性ID>[,<次数>]]... [等级]` | player.giveart| 均可使用 | 给予玩家指定属性的圣遗物 | gart |
| heal | `heal` | player.heal | 仅客户端 | 治疗队伍中所有角色 | h |
| help | `help [命令]`| | 均可使用 | 显示帮助或展示指定命令的帮助 | |
| join | `join [多个角色id]` | player.join | 仅客户端 | 强制入队角色，跟config.json中的avatarLimits有关（跟队内角色数量上限有关）。用法：`join 10000021 10000022` | |
| list | `list` | | 均可使用 | 列出在线玩家 | |
| position | `position` | | 仅客户端 | 获取当前坐标 | pos |
| remove | `remove [多个角色在队伍中的序号]` | player.remove | 仅客户端 | 强制将某个角色从当前队伍中移除。例如`remove 1 2`表示将1号和2号角色移除 ||
| resetconst | `resetconst [all]` | player.resetconstellation | 仅客户端 | 重置当前角色的命座,重新登录即可生效| resetconstellation|
| setfetterlevel | `setfetterlevel <好感等级>`| player.setfetterlevel | 仅客户端 | 设置当前角色的好感等级 | `setfetterlvl` `setfriendship`|
| setstats | `setstats <属性> <数值>` | player.setstats | 仅客户端 | 直接修改当前角色的面板 | stats |
| setworldlevel| `setworldlevel <世界等级>` | player.setworldlevel| 仅客户端 | 设置世界等级(重新登录即可生效) | setworldlvl |
| spawn| `spawn <实体ID> [数量] [等级]`| server.spawn| 仅客户端 | 在你周围生成实体 | |
| talent | `talent <天赋ID> <等级>` | player.settalent| 仅客户端 | 设置当前角色的天赋等级 | |
| teleport | `teleport [@playerUid] \<x> \<y> \<z> [sceneId]` | player.teleport | 均可使用 | 传送玩家到指定坐标 | tp|
| weather| `weather <天气ID> <气候ID>`| player.weather| 仅客户端 | 改变天气 | w |
