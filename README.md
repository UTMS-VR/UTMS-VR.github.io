[公開先](https://utms-vr.github.io/)

## local でのテスト
1. [Bundler](https://bundler.io/) をインストールする
2. `cd docs`
3. `bundle install` (初回だけで良い)
4. 以下のいずれかを実行
    - `bundle exec jekyll build`: サイトを `docs/_site` に生成する
    - `bundle exec jekyll serve`: サイトを生成し，ローカルサーバーからそのサイトを提供する．アドレスは `Server address: 127.0.0.1:4000` などと表示されているはず．

以下のような警告が出るけど，多分気にしなくて良いっぽい (["No GitHub API authentication" error](https://github.com/github/pages-gem/issues/399))

```
GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data.
```
