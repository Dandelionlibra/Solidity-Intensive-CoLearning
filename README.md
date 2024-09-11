# Solidity 残酷共學 by DeFiHackLabs x WTF Academy

## 什麼是残酷共學（Intensive Co-learning）？
<details>
残酷共学是由 [Bruce Xu](https://twitter.com/brucexu_eth) 首创的一种学习模式，目前由 [LXDAO](https://lxdao.io/) 组织并运营残酷共学品牌。
共学有很多种，「残酷共学」与之不同的是「残酷」：

- 你必须每天围绕某个「共学主题」进行学习，每周只有两次请假机会，通常每天至少需要花费半个小时（最好一個小时以上）来学习。
- 你必须提交你的学习证明（按照共学内容设计）到这个「仓库」来证明你今天学习了。
- 如果你没有完成上面两点，你会立刻被踢掉并且标记为 ❌ 失败。

报名方式是完全基于 GitHub 的流程，通过提交 PR 进行申请，合并 PR 之后拥有更新权限。如果你不熟悉 GitHub 和 Git 的操作，请先自行学习。
</details>

## Solidity 残酷共學介绍

- 這次 Solidity 殘酷共學#1 主要是推廣更多人學習 Solidity, 以及搭配WTF Academy 系統性的學習.
- 發起人: [DeFiHackLabs](https://x.com/DeFiHackLabs) & [WTF Academy](https://x.com/WTFAcademy_)
- 助教: [0xRory](https://x.com/0x_Rory)、[guowei](https://github.com/buttonwild)
- 投票: DeFiHackLabs & WTF Academy

## 共学时间

- 報名起始時間：9/13 ~ 9/22
- 本期共學開始時間：9/23~10/16（週日放假，放假日也可以簽到和學習)
- 本期共學持續時間：21 天
- 共學討論: [TG 頻道](https://t.me/+eogaKxQs-1BlZmJl)

## 共學內容
- [WTF Academy Solidity 101 1-15](https://github.com/AmazingAng/WTF-Solidity)
- [WTF Academy Solidity 102 16-30](https://github.com/AmazingAng/WTF-Solidity)
- [WTF Academy Solidity 103 31-50](https://github.com/AmazingAng/WTF-Solidity)
- 完成取得 Solidity 101、102 链上证书

## 共学规则

- 报名规则：请在报名截止时间前进行报名，共学一旦开始后，不得中途加入
- 打卡规则：建议你每天学习 30 ～ 60 分钟以上，并将学习笔记提交，我们会自动更新你的打卡状态，每周有两次请假的机会，超过后状态变为 ❌，视为本次共学失败
- 激勵規則：
    1. 每天打卡上傳學習過程加2分
    2. 21 天後社區白帽投票 writeup 寫得最好以及完整(依據做了多少組題目和內容完整度.) - 第一加10分，第二加8分，第三加6分，第四加5分，第五加4分.
- 21 days 後公佈名次與分數：
    1. 前三名額外獲得可學習獎勵金 $100 Dai.
    2. 前5名可以獲得 DeFiHackLabs T-shirt and WTF T-shirt.
    3. 成功完成共学的可以免 WTF Academy 证书铸造费用 (1張鑄造費0.0069ETH) 

## 如何报名和打卡？

因为残酷共学的报名和打卡是基于 GitHub 进行开展的，如果你是非开发者或者对 git 操作不熟悉，请先阅读此文档：[残酷共学 GitHub 新手教程](https://www.notion.so/lxdao/GitHub-53fca5ba49bb40c69e4e40e69f58f416)

- 报名:

  - Step01：Fork 本仓库。
  - Step02：复制 Template.md 创建你的个人笔记文件，并根据文档指引填写你的信息，并将文件重命名为你的名字：YourName.md。
  - Step03：创建一个 PR 到当前仓库，本残酷共学助教会对你的 PR 进行 review，review 通过后，你的 PR 会被 merge 到 main 分支，这个时候你会收到邀请加入这个仓库 contribution 的邮件，接受邀请后，你会自动获得 main 分支的 push 权限。
  - Step04：完成以上三个步骤，恭喜你报名成功，后续就可以将你的学习记录直接 push 到 main 分支进行更新。
  - 请加入 [TG 頻道](https://t.me/+eogaKxQs-1BlZmJl) 保持交流：（请添加你创建的群组链接)。加入群组后请在群里报到一下方便助教记录。

- 打卡：
  - 报名成功后，你将拥有 main 分支的 push 权限，你需要将每天学习笔记按日期更新到你的 YourName.md 文档中，提交更新后，我们会自动更新你的打卡状态到下面的打卡记录表。
  - 如果你不在 UTC+8 时区，需要添加时区 code 到你的 YourName.md 文件的开始，错误的时区设置可能会使自动化打卡脚本错误计算打卡时间，具体请参考：https://github.com/IntensiveCoLearning/template/blob/main/Template.md?plain=1#L1
  - 当你提交笔记时，请确保以下几点，否则打卡可能会失败：
    - 在 YourName.md 文档，请将笔记内容放到以下代码块中，且 `<!-- Content_START -->` 和 `<!-- Content_END -->` 不能删除:
    ```
    <!-- Content_START -->
    ### 日期
    笔记内容
    <!-- Content_END -->
    ```
    - 日期格式为 `### 2024.07.11`，请不要随意更改

## Solidity 残酷共學打卡记录表

✅ = Done ⭕️ = Missed ❌ = Failed

<!-- START_COMMIT_TABLE -->

| Name(GitHub ID) | 6.24 | 6.25 | 6.26 | 6.27 | 6.28 | 6.29 | 6.30 | 7.01 | 7.02 | 7.03 | 7.04 | 7.05 | 7.06 | 7.07 | 7.08 | 7.09 | 7.10 | 7.11 | 7.12 | 7.13 | 7.14 |
| --------------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |

<!-- END_COMMIT_TABLE -->

<!-- STATISTICALDATA_START -->
<!-- STATISTICALDATA_END -->