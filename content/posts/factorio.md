---
title: "DockerでFactorioのサーバーを立てるメモ"
date: 2024-02-03T19:00:00+09:00
description: ""
---

factoriotools/factorio を使って立てるメモ。  
バージョンアップがなんかうまいことできなかったけど、やっと成功したので。

[https://github.com/factoriotools/factorio-docker](https://github.com/factoriotools/factorio-docker)

- 稼働中のバージョンを落とす:docker stop factorio, docker rm factorio
- docker pull factoriotools/factorio で最新版のイメージを落としてくる
- docker run -d -p 34197:34197/udp -p 27015:27015/tcp -v /opt/factorio:/factorio --name factorio --restart=always factoriotools/factorio

なんか動かなかったら docker ps -a、docker logs factorio でログ見てみる  
(factorio.com 側で Steam と連携できなかったりするとアカウントに購入情報が紐づいてないエラーとか出てるかも)

### map version higher than game version と出る

[https://forums.factorio.com/viewtopic.php?t=104041](https://forums.factorio.com/viewtopic.php?t=104041)

上のフォーラムの通り  
docker run するときに factoriotools/factorio:1.1.100 みたいな感じでバージョン指定できるがなんか動かんかった  
Steam 側でベータ版を選択するほうが早い  
右クリック → プロパティ → ベータ →1.1.x - Latest 1.1 Experimental (1.1.104)みたいなのを選ぶ

### factorio map version cannot be loaded と出る

\_autosave[n].zip が破損してるかも  
僕の場合なぜか\_autosave[1].zip が 0B のファイルになっていたので消して、ちゃんとデータが入ってるっぽい他のセーブデータだけにした状態で起動したらいけた  
(\_autosave5.zip とかの名前だったら、別に\_autosave1.zip にリネームし直す必要はないっぽい)
