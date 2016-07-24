---
layout: post
title:  "Releasing Our Session Timers"
date:   2016-06-27 10:30:00 +0900
category: builderscon
permalink: /builderscon/:year/:month/:day/:title.html
author: lestrrat
---
<!-- front-matter category is used for news filtering in conf.builderscon.io, so if post is conference news, match it with conference slug (e.g.)builderscon/tokyo/2016 -->
<!-- front-matter permalink in each post is to keep backward compat, not needed for new posts -->
category
（日本語は英語の後にあります）

Time keeping during a session is one of the main responsibilities of a conference staff. It's a simple enough job, but there are subtle things that must be taught to new staff members each time we hold a conference.

For example:

* At what times do you notify the speaker? 10 minutes left? 5 minutes left?
* Should you notify the speaker at different times if the session is shorter/longer?
* Should you share your timer with the speaker so they can see it?

So naturally we decided to build our own session timers :D

![](/assets/images/2016-06/web-timer.jpg)

As of today, we have a [simple web based timer](http://web.timer.builderscon.io) that you can use for time keeping 5, 15, 30, and 60 minute talks. The UI will notify you when you reach certain times (for 60 minute talks, this would be at T-15, 10, 5 minutes, and varies depending on the total time of the session). The web UI is intended to be displayed in a notebook or a tablet so that it can be shared with the speaker or the entire room.

![](/assets/images/2016-06/web-timer-ipad.jpeg)

We are also working towards releasing iOS and Android versions. These are meant to be used by the staff when you do not have the luxury of a big display. Provided we have enough resources, we also would like to make it possible to sync the displays so everyone is watching the same time.

In the same spirit as the conference itself, these tools are free, and you are welcome to use it in your meetups or conferences. Just make sure that you do not remove our name from them ... :)

The source code can be found in [Github](https://github.com/builderscon/session-timer), and we welcome anybody to help add more functionalities.

Hope this is useful. Keep on building!

---

セッション中のタイムキープはカンファレンス運営スタッフの重要なタスクのひとつです。タイムキープは一見単純な作業に思えますが、実際にやってみると新しいスタッフが知らなくてはいけない細かいニュアンスがいくつかあります。

気をつけるポイントをいくつか上げると以下のような物があります：

* どのタイミングでスピーカーにお知らせを出すか？
* 60分枠と30分枠で同じタイミングでお知らせを出すべきか？それとも変えるべきか？
* 自分が見ているタイマーをスピーカーと共有すべきか？

今回buildersconを開催するにあたってこれをどうしようと考えた結果… 作ってしまおう！ということになりました :D

![](/assets/images/2016-06/web-timer.jpg)

というわけで本日[シンプルな、Web画面で操作できるタイマー](http://web.timer.builderscon.io)を公開しました！ 5分、15分、30分、60分セッションのタイマーとして利用することができ、それぞれのセッション時間内で（buildersconとして）最適と思われるタイミングで画面表示が切り替わってスピーカーにお知らせをするタイミングを伝えてくれます。このWeb版はノートブックや大きめのタブレット等で表示して、スピーカーや聴衆に見せながら使う事を想定されています。

![](/assets/images/2016-06/web-timer-ipad.jpeg)

これと同時にiOS版とAndroid版も開発が進んでおります。こちらはPCやタブレットを置いておくスペースがないような場合などにスタッフが持ち歩い使うことを想定しています。今後開発リソースがあれば、Web版とスマホ版を同期して全員が同じ時間を見ることができるようにする、という事も考えています。

これらのツールは builderscon の精神にのっとり、誰でも自由に使う事ができます。是非皆様が主催している勉強会やカンファレンス等でご利用下さい（ただし、builderscon の名前とロゴは見えるように残しておいてくださいね！）

このタイマーのソースコードは [Github](https://github.com/builderscon/session-timer) で公開されており、新機能の追加や修正など誰でもできるようになっています。

皆様のカンファレンス運営にもこれが役立てば幸いです。
Keep on building!


