# 📒 FanJournal

**FanJournal** は、スポーツ観戦や推し活イベントの記録を  
Google カレンダーと Google Drive に同期するジャーナルアプリです。  
アプリ自体にはデータを保持せず、Googleサービスと連携して安全に保存します。

---

## 🚀 主な機能（MVP）
- **Googleカレンダー連携**
  - 専用カレンダーを作成してイベント記録を追加
  - 試合名・スコア・感情・メモを保存
- **Google Drive連携**
  - Drive内 `/FanJournal/` フォルダに画像保存
  - イベントごとのサブフォルダ作成
- **オフライン対応**
  - SQLiteに一時保存し、オンライン復帰後に同期
- **イベント種別**
  - スポーツ、ライブ、舞台、その他推し活
  - 種別ごとにフォーム項目を切り替え
- **ギャラリー表示**
  - Drive上の画像をイベントごとに閲覧
- **検索・フィルタ**
  - 種別 / 期間 / 感情 で絞り込み

---

## 🛠 技術スタック
- **Framework**: Flutter 3.x
- **言語**: Dart
- **Database**: SQLite（sqflite）
- **API**: Google Calendar API / Google Drive API
- **状態管理**: Riverpod または Provider（要検討）
- **デザイン**: Material 3

---

## 🗓 開発ロードマップ（MVP）
1. **Phase 1**: 環境構築・Google API設定・テーマ作成
2. **Phase 2**: Google連携（Calendar/Drive）＋SQLite
3. **Phase 3**: 記録作成フォーム・オフライン保存・同期
4. **Phase 4**: 一覧/詳細/ギャラリー/検索
5. **Phase 5**: UX改善（オンボーディング・通知・エラー処理）＆ストア提出
