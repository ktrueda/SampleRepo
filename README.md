# サンプルリポジトリ

#### githubからローカルPCに持ってこよう
```
git clone git@github.com:ktrueda/SampleRepo.git
```
#### ブランチを切ってみよう

```
git branch <ブランチ名:名前など>
```

#### ファイルを編集して実行しよう

```
vimとか hw.c
gccとか hw.c
./a.out
```

#### 編集をコミットしよう

```
git status
git add hw.c
git commit -m "comment"
git status
```

a.outなどソースから生成するファイルはaddしないのがルール．
興味ある人はgitignoreで検索

#### 編集をgithubに送りつけよう

```
git push origin <ブランチ名>
```

