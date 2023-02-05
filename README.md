# Dockerfile-zenn
Dockerfile に関して記事を書いたので，その時の実験内容を載せておきます．

# 実行に関して
1. `git clone` 後，各ディレクトリに移動して `docker build -t [イメージ名] .`
2. イメージが作成されれば，`docker run -it --name [コンテナ名] [イメージ名] [引数（cmd_and_entrypointでの実験以外はなくても ok）]`

# 注意
よくわからない tar ファイルを解凍させられるのが怖いという方は，各自ローカルで作成して実験してください．