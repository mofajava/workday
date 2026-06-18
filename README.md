# 做二休二排班行事曆

依「做二休二」班制自動產生月曆，標示上班日與放假日。

**Demo：** [https://mofajava.github.io/workday/](https://mofajava.github.io/workday/)

## 功能

- 設定第一天上班日，之後依 4 天週期循環（上班 → 上班 → 放假 → 放假）
- 月曆檢視，可切換上／下個月
- 今日日期以橘色框標示
- 純前端，無需安裝或後端

## 使用方式

1. 開啟頁面後，在「設定第一天上班日」選擇你的起始上班日
2. 月曆會自動標示該日之後的班表
3. 使用「上個月／下個月」切換月份

## 本地預覽

直接用瀏覽器開啟 `index.html` 即可，或在本機啟動簡易伺服器：

```bash
python3 -m http.server 8080
```

再前往 `http://localhost:8080`。

## 部署

本專案透過 [GitHub Pages](https://pages.github.com/) 發布，將 `index.html` 放在 repo 根目錄即可。

## 授權

MIT
