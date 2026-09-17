# Book-notes-curator — Skills

以書籍與方法論為底座，整理成可被 Claude 直接調用的 skill 套件。

| Skill | 說明 |
|---|---|
| [`awei-algorithm`](./awei-algorithm/) | 阿威算法（個人主觀視角變化演算法）。v1.6 起併入**生涯規劃師模組（Gen 1：古典體系）**：五步諮詢 SOP、生涯三葉草、生涯四度、五類心智牆、賽道與頭部效應策略、三張輸出模板與逐代擴充規範。 |

## 安裝／更新方式

`awei-algorithm` 是既有 skill 的增修版。**本 repo 只包含 SKILL.md 與新增的
`references/career-*.md` 八份檔案**，既有的 `timeline.md`、`persona.md`、
`decision-checklist.md`、`cross-skill-analysis.md`、`background-and-work-history.md`、
`personal-ip-project-plan.md` 不在此、也未被更動。因此請用**疊加式覆寫**，
不要整包取代目錄：

```bash
# 覆寫 SKILL.md，並把新的 career-* references 疊進既有資料夾
cp awei-algorithm/SKILL.md            ~/.claude/skills/awei-algorithm/SKILL.md
cp awei-algorithm/references/career-*.md ~/.claude/skills/awei-algorithm/references/
```

新檔一律以 `career-` 前綴命名，與既有 references 不會撞名。

## 內容性質聲明

生涯規劃師模組的章節架構參考自古典的著作體系，**內容為 Claude 依其概念架構所做的
獨立整理、延伸與操作化，不是書籍原文的摘錄或轉述**。書中的具體案例與原文論述不予
收錄；若需了解，請直接閱讀原書。
