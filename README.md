# pkexec-nopasswd

## Usage
Copy the `.rules` file into the `/etc/polkit-1/rules.d/` directory.

> [!WARNING]
> ⚠️ **严重安全警告 / CRITICAL SECURITY WARNING**
> 
> **English:**
> Disabling password authentication is highly dangerous. Anyone with physical access to your unlocked computer, or any malicious software running under your current user account, will be able to instantly escalate to `root` privileges without triggering any password prompts. Use with extreme caution!
> 
> **中文:**
> 禁用密码验证会带来极高的安全风险。
> 如果你的设备在未锁屏状态下被他人物理接触，或者当前普通用户环境下运行了恶意软件，攻击者将无需输入任何密码即可瞬间提权至 root（系统最高权限），且系统不会发出任何警告。请务必谨慎使用！
