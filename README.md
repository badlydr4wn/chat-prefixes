**Coloured Preview**: [Download this page](https://raw.githubusercontent.com/badlydr4wn/srp-chat-prefixes/refs/heads/main/README.md) and view in [Visual Studio Code](https://code.visualstudio.com) instead.

# 🌴 Sydney Roleplay Staff - Chat Prefixes
Chat Prefixes are special snippets that you can paste before your messages and add a little bit more formality as staff. They are completely decorative and it's up to you whether you want to use them. A tutorial on how to use them is found below. (**📚 Tutorial**)

## 📑 Rich Text Markup
Chat Prefixes use ROBLOX's [Rich Text Markup](https://create.roblox.com/docs/ui/rich-text) feature within chat bubbles do display text of varying features and allows for:
- [Colours](https://create.roblox.com/docs/ui/rich-text#color)
- [Sizes](https://create.roblox.com/docs/ui/rich-text#size)
- [Fonts](https://create.roblox.com/docs/ui/rich-text#font-face)
- [Transparency](https://create.roblox.com/docs/ui/rich-text#transparency)
- Formatting ([Bold](https://create.roblox.com/docs/ui/rich-text#bold), [Italic](https://create.roblox.com/docs/ui/rich-text#italic), [Underline](https://create.roblox.com/docs/ui/rich-text#underline), etc.)
- [Line Breaks](https://create.roblox.com/docs/ui/rich-text#line-break)
- [Small Caps](https://create.roblox.com/docs/ui/rich-text#small-caps)
- And more!

---

| Type | Preview | Markup |
| --- | --- | --- |
| Colour | I want the <font color="#FF7800">orange</font> candy. | `<font color="#` `hexValue` `">` `textContent` `</font>`<br />(compatible with `rgb(#,#,#)` values) |
| Size | <font size="6">This is big.</font> <font size="2">This is small.</font> | `<font size="` `fontSize` `">` `textContent` `</font>`<br />(fontSize default: 14) |
| Font | <font face="Michroma">This is Michroma face.</font> | `<font face="` `fontFace` `">` `textContent` `</font>`<br />(see [Fonts](https://create.roblox.com/docs/reference/engine/enums/Font)) |
| Weight | This is normal. <b>This is heavy.</b> | `<font weight="` `fontWeight` `">` `textContent` `</font>` |
| Stroke | You won <span style="color: #fffff; text-shadow: -2px -2px 0 #00A2FF25, 2px -2px 0 #00A2FF25, -2px 2px 0 #00A2FF25, 2px 2px 0 #00A2FF25;">25 gems</span>. | `<stroke color="` `strokeColour` `">` `textContent` `</stroke>`<br />`<stroke thickness="` `strokeThickness` `">` `textContent` `</stroke>`<br />`<stroke joins="` `strokeJoins` `">` `textContent` `</stroke>`<br />`<stroke transparency="` `strokeTransparency` `">` `textContent` `</stroke>`<br /> (see [Appearance Modifiers](https://create.roblox.com/docs/ui/appearance-modifiers)) |
| Transparency | Text at <font transparency="0.5">50% transparency</font>. | `<font transparency="` `textTransparency` `">` `textContent` `</font>` |
| Formatting | Text in <b>bold</b>. <br />Text <i>italicized</i>. <br />Text <u>underlined</u>. <br/>Text with <s>strikethrough</s> applied.<br /> | `<b>` `textContent` `</b>`<br />`<i>` `textContent` `</i>`<br />`<u>` `textContent` `</u>`<br />`<s>` `textContent` `</s>` |
| Line Breaks | New line occurs after this sentence.<br />Next sentence... | `<br />` |
| Capitalisation | UPPERCASE makes words read loudly! | `<uc>` `textContent` `</uc>` |
| Small Capitals | My name is <sc>Dɪᴠᴀ Dʀᴀɢᴏɴsʟᴀʏᴇʀ | `<sc>` `textContent` `</sc>` |
| Comments | After this is a comment...<!--This does not appear in the final text--> and now more text...<br />(`After this is a comment...<!--This does not appear in the final text--> and now more text...`) | `<!--` `textContent` `-->` |

## 📚 Tutorial
1. Copy your prefered Chat Prefix
2. Paste this into your ROBLOX chat and type a short message after (*all in the same message*)
3. Send the message, you should get a result like the following:
> <b><font color="#258fe1" size="2">[SR MANAGEMENT]</font></b><br />
> Hello, world!

## 🔎 FAQ
- **It didn't work, it just returned a bunch of code.**
  - Either you pasted an incomplete prefix or an invalid/broken prefix.
- **It didn't work, it got filtered.**
  - The markup prefix is filtered identically to normal messages, so some parts may trigger the filter.
- **Can you make it automatically add it?**
  - No. That is essentially impossible to do without exploiting or some app that I am **not** making.
- **Can you add `x` prefix?**
  - Ask me to add it, or if you can try reading the [Rich Text Markup](https://create.roblox.com/docs/ui/rich-text) docs and make your own. Feel free to submit your own if you think I should add it here.
- **When should I use a prefix?**
  - Use them at your own descretion, maybe in your greeting. It's up to you. They aren't mandatory in any way.
- **What's the differenced betweens Detailed, Basic, and UBasic prefixes?**
  - *Detailed* prefixes look slightly better and take up significantly more message space.
  - *Basic* prefixes take up less space while sacrificing detail.
  - *UBasic* prefixes are a single emoji in a larger font size. They are the most efficient in terms of message space.

## 📰 Detailed Prefixes
Detailed prefixes have seperately coloured brackets and look slightly better. This comes at the cost of higher message usage.

### 👑 Leadership Team
| Role | Preview | Markup |
| --- | --- | --- |
| Leadership Team | <b><font color="#6ca2cc" size="2">[<font color="#86cafe">LEADERSHIP</font>]</font></b> | `<b><font color="#6ca2cc" size="12">[<font color="#86cafe">LEADERSHIP</font>]</font></b><br />` |

### 🛠️ Management Team
| Role | Preview | Markup |
| --- | --- | --- |
| Senior Management | <b><font color="#8686fe" size="2">[<font color="#258fe1">SR MANAGEMENT</font>]</font></b> | `<b><font color="#8686fe" size="12">[<font color="#258fe1">SR MANAGEMENT</font>]</font></b><br />` |
| Management Team | <b><font color="#258fe1" size="2">[<font color="#8686fe">MANAGEMENT</font>]</font></b> | `<b><font color="#258fe1" size="12">[<font color="#8686fe">MANAGEMENT</font>]</font></b><br />`|

### 🛡️ Administration Team
| Role | Preview | Markup |
| --- | --- | --- |
| Senior Administrator | <b><font color="#e991c2" size="2">[<font color="#ff9ed3">SR ADMINISTRATOR</font>]</font></b> | `<b><font color="#e991c2" size="12">[<font color="#ff9ed3">SR ADMINISTRATOR</font>]</font></b><br />`|
| Administrator | <b><font color="#e991c2" size="2">[<font color="#e991c">ADMINISTRATOR</font>]</font></b> | `<b><font color="#e991c2" size=1"2">[<font color="#e991c">ADMINISTRATOR</font>]</font></b><br />`|
| Junior Administrator | <b><font color="#e991c2" size="2">[<font color="#d182ad">JR ADMINISTRATOR</font>]</font></b> | `<b><font color="#e991c2" size="12">[<font color="#d182ad">JR ADMINISTRATOR</font>]</font></b><br />`|

### 🔨 Moderation Team
| Role | Preview | Markup |
| --- | --- | --- |
| Senior Moderator | <b><font color="#ad343e" size="2">[<font color="#c43b46">SR MODERATOR</font>]</font></b> | `<b><font color="#ad343e" size="12">[<font color="#c43b46">SR MODERATOR</font>]</font></b><br />`|
| Moderator | <b><font color="#ad343e" size="2">[<font color="#ad343e">MODERATOR</font>]</font></b> | `<b><font color="#ad343e" size="12">[<font color="#ad343e">MODERATOR</font>]</font></b><br />`|
| Junior Moderator | <b><font color="#ad343e" size="2">[<font color="#962d36">JR MODERATOR</font>]</font></b> | `<b><font color="#ad343e" size="12">[<font color="#962d36">JR MODERATOR</font>]</font></b><br />`|
| Trial Moderator | <b><font color="#ad343e" size="2">[<font color="#ff6978">TRIAL MODERATOR</font>]</font></b> | `<b><font color="#ad343e" size="12">[<font color="#ff6978">TRIAL MODERATOR</font>]</font></b><br />`|
| Moderator Trainee | <b><font color="#ad343e" size="2">[<font color="#3dff64">TRAINEE</font>]</font></b> | `<b><font color="#ad343e" size="12">[<font color="#3dff64">TRAINEE</font>]</font></b><br />`|

## 📃 Basic Prefixes
Basic prefixes use a single colour throughout and are more accessible. They are generally more effecient than detailed prefixes.

### 👑 Leadership Team
| Role | Preview | Markup |
| --- | --- | --- |
| Leadership Team | <b><font color="#86cafe" size="2">[LEADERSHIP]</font></b> | `<b><font color="#86cafe" size="12">[LEADERSHIP]</font></b><br />` |

### 🛠️ Management Team
| Role | Preview | Markup |
| --- | --- | --- |
| Senior Management | <b><font color="#258fe1" size="2">[SR MANAGEMENT]</font></b> | `<b><font color="#258fe1" size="12">[MANAGEMENT]</font></b><br />` |
| Management Team | <b><font color="#8686fe" size="2">[MANAGEMENT]</font></b> | `<b><font color="#8686fe" size="12">[MANAGEMENT]</font></b><br />` |

### 🛡️ Administration Team
| Role | Preview | Markup |
| --- | --- | --- |
| Senior Administrator | <b><font color="#e991c2" size="2">[SR ADMINISTRATOR]</font></b> | `<b><font color="#e991c2" size="12">[SR ADMINISTRATOR]</font></b><br />` |
| Administrator | <b><font color="#e991c2" size="2">[ADMINISTRATOR]</font></b> | `<b><font color="#e991c2" size="12">[ADMINISTRATOR]</font></b><br />` |
| Junior Administrator | <b><font color="#e991c2" size="2">[JR ADMINISTRATOR]</font></b> | `<b><font color="#e991c2" size="12">[JR ADMINISTRATOR]</font></b><br />` |

### 🔨 Moderation Team
| Role | Preview | Markup |
| --- | --- | --- |
| Senior Moderator | <b><font color="#ad343e" size="2">[SR MODERATOR]</font></b> | `<b><font color="#ad343e" size="12">[SR MODERATOR]</font></b><br />` |
| Moderator | <b><font color="#ad343e" size="2">[MODERATOR]</font></b> | `<b><font color="#ad343e" size="12">[MODERATOR]</font></b><br />` |
| Junior Moderator | <b><font color="#ad343e" size="2">[JR MODERATOR]</font></b> | `<b><font color="#ad343e" size="12">[JR MODERATOR]</font></b><br />` |
| Trial Moderator | <b><font color="#ff6978" size="2">[TRIAL MODERATOR]</font></b> | `<b><font color="#ff6978" size="12">[TRIAL MODERATOR]</font></b><br />` |
| Moderator Trainee | <b><font color="#3dff64" size="2">[TRAINEE]</font></b> | `<b><font color="#3dff64" size="12">[TRAINEE]</font></b><br />` |


## 📄 UBasic Prefixes
UBasic prefixes, or *Ultra* Basic prefiex consist of a single emoji in a 3x font size. They should be used more as indicator for something rather than actual prefixes.
| Indicator | Preview | Markup |
| --- | --- | --- |
| Announcement | <font size="6">📢</font> | `<font size="36">📢</font><br />` |
| Denied | <font size="6">🚫</font> | `<font size="36">🚫</font><br />` |
| Alert | <font size="6">🚨</font> | `<font size="36">🚨</font><br />` |
| Warning | <font size="6">⚠️</font> | `<font size="36">⚠️</font><br />` |
| Accepted | <font size="6">✅</font> | `<font size="36">✅</font><br />` |
| Moderator | <font size="6">🛡️</font>| `<font size="36">🛡️</font><br />` |

## 📜 Templates
These are blank prefixes with placeholder values for attributes such as colour, size, etc.
| Type | Preview | Markup |
| --- | --- | --- |
| Detailed | <b><font color="#808080" size="2">[<font color="#ffffff">PLACEHOLDER</font>]</font></b> | `<b><font color="` `#COLOR` `" size="12">[<font color="#ffffff">[` `PLACEHOLDER` `]</font>]</font></b><br /> ` |
| Basic | <b><font color="#ffffff" size="2">[PLACEHOLDER]</font></b> | `<b><font color="` `#COLOR` `" size="12">[` `PLACEHOLDER` `]</font></b><br />`|
| UBasic | <font size="6">■</font> | `<font size="36">` `PLACEHOLDER` `</font><br />` |