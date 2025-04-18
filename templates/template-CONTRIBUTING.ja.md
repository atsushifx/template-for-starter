# 🤝 コントリビューションガイドライン

このプロジェクトへの貢献をご検討いただき、ありがとうございます！
皆さまのご協力により、より良いプロジェクトを築いていけることを願っております。

## このテンプレートの使用方法

## 🧰 このテンプレートの使用方法

この `CONTRIBUTING.ja.md` は、OSSプロジェクト向けのテンプレートです。
ご自身のプロジェクトで使用する際は、以下の手順に従ってカスタマイズしてください。

1. **リポジトリ情報の更新**:
   - `<your-repo>` をご自身のリポジトリ名に置き換えてください。
   - リンクやコマンド例など、プロジェクト固有の情報を適切に修正してください。

2. **ツールやコマンドの確認**:
   - 使用しているツール (例: `pnpm`, `dprint`, `eslint`) がプロジェクトに適しているか確認し、必要に応じて変更してください。

3. **行動規範の確認**:
   - `CODE_OF_CONDUCT.ja.md` がプロジェクトに存在することを確認し、リンクが正しく機能するようにしてください。

4. **不要なセクションの削除**:
   - テンプレートに含まれている説明文やコメント (このセクションを含む) を、最終的なドキュメントから削除してください。

このテンプレートは、[GitHub Docs: リポジトリコントリビューターのためのガイドラインを定める](https://docs.github.com/ja/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors) を参考に作成されています。

## 📝 貢献の方法

### 1. Issue の報告

- バグ報告や機能提案は、[Issue](https://github.com/<your-repo>/issues) にてお願いいたします。
- 報告の際は、再現手順や期待される動作、実際の動作など、詳細な情報を提供してください。

### 2. プルリクエストの提出

- リポジトリをフォークし、`feature/your-feature-name` のようなブランチを作成してください。
- ソースコード、あるいはドキュメントを変更し、順次コミットしてください。
  - コミットメッセージは [ConventionalCommit](https://www.conventionalcommits.org/ja/v1.0.0/) にしたがってください。
  - １機能ごとにコミットし、あとでrebaseすることでいいコミットが作成できます。
- プルリクエストには、タイトルにタイトルに変更の概要や目的を１行で、本文に概要の説明や背景を描いてください。

## プロジェクト環境

### 開発環境のセットアップ

次の手順で、開発環境をセットアップします。

```bash
git clone https://github.com/<your-repo>.git
cd <your-repo>
pnpm install
```

### テスト

変更を加えた際は、以下のコマンドでテストを実行し、既存の機能が影響を受けていないことを確認してください。

```bash
pnpm test
```

### コードスタイルとフォーマット

このプロジェクトでは、コードのフォーマット、リントに以下を使用してます。

- コードフォーマット: \<xx-code-formatter>
- リント: \<xx-lint>

## 行動規範

すべてのコントリビューターは、[行動規範](CODE_OF_CONDUCT.ja.md) を遵守してください。

## 参考

- [GitHub Docs: リポジトリコントリビューターのためのガイドラインを定める](https://docs.github.com/ja/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors)
