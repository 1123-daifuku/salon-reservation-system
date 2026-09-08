# 美容鍼サロン予約システム

美容鍼サロンを想定した予約システムです。

## 概要

LINEから予約ページへアクセスし、空いている時間帯を確認して予約できるシステムを作成します。

ユーザーはLINEログインを利用して予約情報を確認・変更・キャンセルできるようにする予定です。

## 主な機能

### ユーザー側

* 予約をとる
* 空き時間の確認
* 予約内容の確認
* 予約の変更
* 予約のキャンセル
* LINEログイン

### 管理者側

* 予約一覧の確認
* 予約枠の管理
* 休業日の設定
* メニューの管理

## 使用技術

### Frontend

* React
* TypeScript
* Vite

### Backend

* NestJS
* TypeScript

### Database

* PostgreSQL
* Prisma
* Neon

### その他

* Git / GitHub
* LINE LIFF / LINE Login

## 開発予定

1. React + TypeScriptで画面を作成
2. 予約日時・時間帯の選択機能を作成
3. 予約確認・完了画面を作成
4. NestJSでAPIを作成
5. Prisma + PostgreSQLを接続
6. 予約情報をDBに保存
7. 管理者画面を作成
8. LINEログインを導入
9. LINEから予約ページへアクセスできるようにする

## 目的

React、TypeScript、NestJS、Prisma、PostgreSQL、GitHubなどの技術を実際のWebアプリ開発を通して学習することを目的としています。
