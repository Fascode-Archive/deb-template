debファイルのテンプレートです。`hello-world`パッケージが生成され、`/usr/bin/hello-world`が作成されます。  

```bash
git clone https://github.com/hayao0819/deb-template.git ./hello-world
dpkg -b hello-world
```