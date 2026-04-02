# canopy-openness-analysis

開空度の解析についてまとめます。

## Rの環境について

[renv](https://rstudio.github.io/renv/articles/renv.html)というパッケージを使うことで、プロジェクトごとのR環境を管理しています。
このリポジトリをクローンした場合は、以下のスクリプトを実行してください。

```r
renv::restore()
```

これで、プロジェクトに必要なパッケージがインストールされ、適切なバージョンが設定されます。
