# House of Cards

德州扑克家庭局的记账 App，Mac 版。A bookkeeping app for home poker games, for the Mac.

## 下载

- **最新版：[House-of-Cards.dmg](https://github.com/DonkeyBoy001/house-of-cards-releases/releases/latest/download/House-of-Cards.dmg)**
- 以前的版本：[所有版本](https://github.com/DonkeyBoy001/house-of-cards-releases/releases)
- 需要：Apple 芯片（M1、M2、M3、M4……）的 Mac，macOS 12 或更新。Intel 芯片的 Mac 不能用。

## 安装

1. 打开 DMG，把 House of Cards 拖进「应用程序」。
2. 第一次打开会提示「无法验证」。这是因为 App 没有在 Apple 登记，不是病毒。
   - macOS 15 或更新：点「完成」，然后打开 系统设置 → 隐私与安全性，拉到最下面，点 House of Cards 旁边的「仍要打开」，输入电脑密码，再点「仍要打开」。
   - macOS 14 或更早：在「应用程序」里右键点 App，选「打开」，再点「打开」。

   只需要这一次。
3. 注册账号。
4. 设置 → 授权：填好俱乐部和联系方式，生成申请码，发到 **zhouzhaoyu111@gmail.com**。收到授权后粘贴进去就能记账了。没有授权时账本只能查看。授权从粘贴那一刻开始计时。

## 升级

下载新版本，把新的 App 拖进「应用程序」替换旧的。账本、账号和授权都不在 App 里，不会丢。第一次打开新版本时，如果问是否允许使用钥匙串，输入电脑密码，点「始终允许」。

## 核对下载的文件

在「终端」里运行：

```bash
shasum -a 256 ~/Downloads/House-of-Cards.dmg
```

结果应该和这个版本的发布说明里写的 SHA-256 一样。

## 联系

授权、续费和问题：zhouzhaoyu111@gmail.com

---

## English

- **Download:** [House-of-Cards.dmg](https://github.com/DonkeyBoy001/house-of-cards-releases/releases/latest/download/House-of-Cards.dmg) (Apple silicon Macs, macOS 12 or later).
- **Install:** open the DMG and drag House of Cards into Applications. The first time, macOS says it cannot verify the app (it is not registered with Apple): click Done, then System Settings → Privacy & Security → scroll down → Open Anyway next to House of Cards, enter your Mac password, and Open Anyway again. On macOS 14 or earlier, right-click the app in Applications and choose Open. Only once.
- **Activate:** sign up, then Settings → License: fill in your club and contact details, create a request code and email it to zhouzhaoyu111@gmail.com. Paste the license you get back. Without a license the ledger is read-only.
- **Update:** drag the new app over the old one. Your ledger, accounts and license are kept. If the new version asks to use the Keychain, enter your Mac password and click Always Allow.
- **Contact:** licenses, renewals and questions: zhouzhaoyu111@gmail.com
