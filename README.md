# React App

## 環境構築

### 作業一覧

- 公式抜粋
```
# installs nvm (Node Version Manager)
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.0/install.sh | bash
# download and install Node.js (you may need to restart the terminal)
nvm install 20
# verifies the right Node.js version is in the environment
node -v # should print `v20.18.0`
# verifies the right npm version is in the environment
npm -v # should print `10.8.2`
```

### Next.jsのアプリ立ち上げ

```
npmより高速化のためインストール推奨
# npm install -g pnpm
サンプルプロジェクトのアプリ作成
# npx create-next-app@latest nextjs-dashboard --example "https://github.com/vercel/next-learn/tree/main/dashboard/starter-example" --use-pnpm
```