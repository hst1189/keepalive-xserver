### Xserver 自动续期脚本

### 相关环境变量

| Secret 名称         | 是否必填 | 说明                                              |
|---------------------|----------|---------------------------------------------------|
| ACCOUNTS            | ✅ 必填  | xserver登录邮箱和登录密码                             |
| TG_BOT_TOKEN        | ❌ 可选  | Telegram Bot Token（用于发送通知）                |
| TG_CHAT_ID          | ❌ 可选  | Telegram Chat ID（接收通知的用户或群组 ID）        |

ACCOUNTS格式示例：
```
[
    {
        "username": "your-xserver-email@gmail.com", 
        "password": "your-xerver-password"  
    }
]
```
