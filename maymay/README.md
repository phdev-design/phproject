# MayMay Ad Hoc IPA

把簽好的 Ad Hoc 安裝包放到此目錄：

- 檔名：`MayMay.ipa`
- 安裝頁：https://maymay.phdev.uk
- manifest 使用：
  `https://github.com/phdev-design/phproject/raw/main/maymay/MayMay.ipa`

```bash
# 本機打包後 push
cp path/to/MayMay.ipa maymay/MayMay.ipa
git add maymay/MayMay.ipa
git commit -m "Add MayMay Ad Hoc IPA"
git push
```

注意：GitHub 單檔建議 < 100MB；若 raw 下載失敗可改用 Release Assets。
