# 仓库约定

## 提交与推送

原因：仓库主人喜欢把自己藏起来，不想在提交记录和贡献者里露面。

- 所有提交的作者和提交者都使用 `Claude <noreply@anthropic.com>`，不要加 `Co-Authored-By` 等共同作者行。
- 新文章、内容更新直接推送到 `main`，不要通过 GitHub 网页或 API 合并 PR（squash / merge 会把仓库所有者记为作者）。
- 新文章放在 `notes/<文章名>/README.md`，图片放在同一目录。

## 修改 CLAUDE.md

原因：本仓库公开，CLAUDE.md 所有人可见，仓库主人需要先检查内容里有没有不适合公开的东西。

- 修改 CLAUDE.md 前，先把要改的完整内容给仓库主人看，得到明确同意后再提交和推送。
