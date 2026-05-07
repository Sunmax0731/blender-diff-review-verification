# 検品・差分レビュー・手動検証

blender-diff-review-verification は Blender素材の修正差分を納品前に確認する制作者 向けの closed alpha プロダクトです。変更前後の素材、差分要点、手動確認、承認状態を検品表として残す。

## Source

- PICKUP Rank: 59
- Domain / Idea No: BlenderAddon / 4
- Repository: blender-diff-review-verification
- 主な公開先: GitHub Release / BOOTH
- created_idea: `D:/AI/BlenderAddon/created_idea_004_blender-diff-review-verification`
- 同梱ZIP: `D:/AI/BlenderAddon/created_idea_004_blender-diff-review-verification/idea_004_blender-diff-review-verification.zip`
- 開始時 README: 存在しない


## Alpha Scope

- 代表シナリオ4件の自動検証
- 必須項目不足、警告、混在バッチの分類
- src/blender/ のホスト連携シェル
- QCDS、security/privacy、traceability、release checklist、manual test docs
- docs ZIP: `dist/blender-diff-review-verification-docs.zip`

## Commands

```powershell
npm test
node src/cli/index.js samples/representative-suite.json
npm run build:docs
```

手動テストは Codex 側では未実施です。手順は `docs/manual-test.md` と `docs/strict-manual-test-addendum.md` にあります。

