---
title: Codespacesが使えるようになった!!
tags:
  - Chrome
  - GitHub
  - VSCode
  - Codespaces
private: false
updated_at: '2022-05-30T01:16:06+09:00'
id: bbac5faebb385afe4495
organization_url_name: null
slide: false
ignorePublish: false
---
# はじめに
「高校生なんかに許可が出るのかなー」と思いつつ[Codespaces](https://github.co.jp/features/codespaces)のベータ版に申し込んで早半年以上が過ぎ、ついにアイツが私のもとにも届きました。
![Screenshot 2022-05-29 10.25.05.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2449798/25445561-3dcd-14ed-0eef-cea0e718bcb3.png)
なんで今更来たんだろ?と考えると~~1つ思い当たるフシがありました。
このメールが届く数時間前、私はGithubでOrganizationを作成していたのです。もしかすると、Codespacesを使う人の条件として「何かしらのOrganizationに属する」というのがあったのかも？
すくなくとも、私の場合Organizationの作成がトリガーになったのは間違いなさそうです。~~
ちょうどその日にたくさんの方の申請が通ったそうです。私もその一人だったわけですね。

# Codespacesとは
周知のことだと思うので[他の方の解説](https://zenn.dev/dzeyelid/articles/5485cdeb2a1ada)を載せておきます。
ざっくり言うと、VScodeをそのままWebで使えるって感じです。※もちろん制約はあります。

# なぜCodespacesが必要だったのか？
私は家のデスクトップPCに加えて、学校で購入させられたChromebookを利用しています。そして、[ChromebookでもLinuxを使えばVScodeをローカルで使うことができます。](https://forest.watch.impress.co.jp/docs/serial/yajiuma/1286826.html)
**ところが**、学校がLinuxを制限する設定にしてくださったおかげでVScodeをChromebookで使えなくなりました。
代替ツールとして[vscode.dev](https://vscode.dev/)や[github.dev](https://github.dev/)を使ってきましたがターミナルなど、実行環境がないのが痛かったです。実行環境のあるものとして、[gitpod.io](https://gitpod.io/)も使ってみましたが、無料版での月50時間の制限が辛かった、、、(無料で使おうとするのも傲慢な話かもしれませんがね、、、)
また、上記のツールは使える拡張機能が大なり小なり制限されていました。
そんな私にとって**Codespacesは理想的なツール**だったわけです。

# 実況見分
同じようにChromebookに苦しめられる後輩向けに、Codespacesの申請が通った当時の私のGithubの状況を紹介します。
* Contribution…200くらい
* Issue…5~6個
* Pull request…10回くらい
* Organization…1回作って、すぐ消した。
* Code review…0
* フォロワー…0
* プライベートリポジトリ…7個
* パブリックリポジトリ…0個
* 申請が通るまでの期間…半年以上

ガチのエンジニアの方々に比べるとかなり少ないです。 ※上記の数字を上回れば必ず申請が通るとも限りませんし、下回っていても申請が通る場合があるかもしれせん。

ガチのエンジニアの方々はもともと使えるようになっていたり、申請するとすぐに通ったりしたらしいです。
# さいごに
私のように、どうしても開発環境がWeb上に限定されてしまった人にとって、Codespacesはかなり魅力的な存在だと思います。
また、VScodeに縛られず、Pythonなら[Colaboratory](https://colab.research.google.com/?hl=ja)を使うなど他のツールに移行してみることも有効な手段でしょう。
どうかChromebookユーザーに幸あれ

# 追記-ちょっと使ってみた感想
実行環境があったり、vscode.devで使えなかった拡張機能が使ったりできるのは本当に便利でこれからが楽しみ。
**ただ、、、**
初回起動時&1度stopした後の起動がかなり不安定。恐らくこれには、よわよわChromebookのマシンスペックの低さ(Celeron N4020笑)と低速なWifiが関係している気がします。タイムアウトしまくっていたのでね。実際、Wifiをスマホのデザリングにつなぎ替えるだけでも大分改善されました。また有線LANのつよつよデスクトップではそのような症状は一切現れませんでした。
クラウドIDEとは言えど少なからず相手は選ばれるようです、、、笑
