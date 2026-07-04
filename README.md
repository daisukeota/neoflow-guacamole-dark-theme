# neoflow-guacamole-dark-theme

Apache Guacamole 1.6.0+ 用の shadcn/ui (Zinc) スタイルのダークテーマ拡張機能です。  
A sleek, modern dark theme extension for Apache Guacamole (1.6.0+), meticulously crafted based on the shadcn/ui (Zinc) color system.

---

## 📦 インストール方法 / Installation

### 1. 拡張機能のビルド / Build the Extension
このリポジトリのファイルをZIP圧縮し、拡張子を `.jar` に変更します。  

Compress the repository files into a ZIP archive and change the extension to `.jar`.

```bash
zip -r neoflow-guacamole-dark-theme.jar guacamole-manifest.json theme.css
```

### 2. 配置 / Deployment
生成された .jar ファイルを Guacamole コンテナの GUACAMOLE_HOME/extensions/ ディレクトリに配置します。

Place the generated .jar file into the GUACAMOLE_HOME/extensions/ directory of your Guacamole container.

### 3. 再起動 / Restart
Guacamole を再起動します。

Restart your Guacamole container/service to apply the theme.


🎨 Features
shadcn/ui (Zinc) Design Language: Implements deep blacks (#09090b), soft borders (#27272a), and clean white accents for a high-end tech aesthetic.

Perfect Visibility: Fully fixed user menus, streamlined navigation tabs, and crisp data tables with custom zebra-striping and hover highlights.

Seamless Auth Flow: Beautifully cohesive dark styles extending across the login UI and the guac-modal sign-out screen.