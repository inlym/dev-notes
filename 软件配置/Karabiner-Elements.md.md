# Karabiner-Elements 软件配置

## 键位改写

在 `Complex Modifications` 模块配置，新增自定义规则，将以下配置复制后保存即可。

```json
{
    "description": "F2全选，F3复制，F4删整行，F5粘贴，F6粘贴2，F7特殊复制，F8保存",
    "manipulators": [
        {
            "from": { "key_code": "f2" },
            "to": [
                {
                    "key_code": "a",
                    "modifiers": ["command"]
                }
            ],
            "type": "basic"
        },
        {
            "from": { "key_code": "f3" },
            "to": [
                {
                    "key_code": "c",
                    "modifiers": ["command"]
                }
            ],
            "type": "basic"
        },
        {
            "from": { "key_code": "f4" },
            "to": [
                {
                    "key_code": "delete_or_backspace",
                    "modifiers": ["command"]
                }
            ],
            "type": "basic"
        },
        {
            "from": { "key_code": "f5" },
            "to": [
                {
                    "key_code": "v",
                    "modifiers": ["command"]
                }
            ],
            "type": "basic"
        },
        {
            "from": { "key_code": "f6" },
            "to": [
                {
                    "key_code": "v",
                    "modifiers": ["option", "shift", "command"]
                }
            ],
            "type": "basic"
        },
        {
            "from": { "key_code": "f7" },
            "to": [
                {
                    "key_code": "c",
                    "modifiers": ["shift", "option", "command"]
                }
            ],
            "type": "basic"
        },
        {
            "from": { "key_code": "f8" },
            "to": [
                {
                    "key_code": "s",
                    "modifiers": ["command"]
                }
            ],
            "type": "basic"
        }
    ]
}
```