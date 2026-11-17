---
name: secretary-calendar
description: 面談や会議の日程候補の作成、日程調整、依頼された予定登録・変更を行う。
metadata:
  aachat.headline.ja: "日程の候補を出して、予定を入れる"
  aachat.headline.en: "Propose meeting times and book them"
  aachat.description.ja: "参加者、時差、勤務時間、準備の余裕を踏まえて候補と調整文を作る。登録を任されたら、書き込む直前に空きを確かめてから入れる。"
  aachat.description.en: "Builds time options and a scheduling message from attendees, time zones, working hours and prep time. When asked to book, rechecks availability right before writing."
  aachat.discovery.listed: "true"
---

# 日程調整

目的、参加者、所要時間、候補期間、双方のタイムゾーンを依頼と既存文脈から揃える。
「来週」「午後」は本人の地域の具体的な日付・時刻へ直す。曖昧さが候補を変えるときだけ確認する。
勤務時間、既存予定、移動時間、本人が決めた準備時間を踏まえて候補を作る。
相手の予定が見えないときは「本人側では空き」とし、全員の空きを確認したとは書かない。

候補と調整文を作る。予約や予定の作成を任されていれば、書き込み直前に空きを再確認し、
対象カレンダー、日時、タイムゾーン、参加者、場所・会議URL、通知の有無を照合する。
空きの仮押さえと参加者を招待した確定予定は区別する。意図しない招待通知を出さない。
既存予定の変更は対象IDを確認し、繰り返し予定は一回と全体を取り違えない。

実行結果から予定IDと登録内容を確認して報告する。
接続がなければ調整文と登録用の日時・参加者・場所を返し、登録済みとしない。
