# TinyPacemaker プライバシーポリシー

最終更新日：2026年9月14日

HARUBON（以下「開発者」）は、Androidアプリ「TinyPacemaker」（以下「本アプリ」）におけるユーザー情報の取り扱いについて、以下のとおりプライバシーポリシーを定めます。

## 1. 本アプリについて

TinyPacemakerは、カメラ映像からゲートマーカーを検出し、FPVドローン等のラップタイムを計測するためのアプリです。

本アプリではユーザーアカウントの作成やログインを必要としません。

## 2. カメラ映像の取り扱い

本アプリは、ラップ計測のために端末の内蔵カメラまたは接続されたUSBカメラの映像を使用します。

カメラ映像はゲートマーカーの検出のために端末内で処理されます。

本アプリは、カメラ映像や静止画を開発者のサーバーまたはFirebaseへ送信しません。また、カメラ映像をファイルとして保存しません。

## 3. ゲートマーカー情報

本アプリは、カメラ映像からArUcoマーカーを検出します。

マーカーID、位置、面積、ゲート通過判定等の情報はラップ計測のために端末内で処理されます。

これらの情報を開発者のサーバーへ送信することはありません。

## 4. USB機器情報

USBカメラの接続および制御のため、Androidおよび使用しているUSBライブラリが、接続されたUSB機器の識別情報や機器情報を一時的に取得する場合があります。

これには、ベンダーID、プロダクトID、製品名、メーカー名、シリアル番号等が含まれる場合があります。

これらの情報はUSB機器の接続・制御のために端末内で使用され、本アプリからFirebaseその他の外部サービスへ送信することはありません。

## 5. 端末内に保存するデータ

本アプリは、アプリ専用の端末内ストレージに以下の情報を保存する場合があります。

- ラップ履歴
- ラップ計測に関する設定
- カメラや表示に関する設定
- アプリの言語設定
- その他、本アプリの動作に必要な設定

これらのデータは原則として端末内だけに保存されます。

本アプリではAndroidのクラウドバックアップを無効にしています。また、対応するAndroid環境では端末間データ転送の対象からも除外するよう設定しています。ただし、一部の端末メーカー独自のデータ移行機能については、本アプリ側で完全に制御できない場合があります。

## 6. 診断ログ

ユーザーが診断ログ機能を有効にした場合、本アプリは動作確認や問題調査のための診断情報を端末内に保存する場合があります。

診断ログには、計測日時、経過時間、マーカー検出状況、ゲート通過判定等が含まれます。

診断ログには、カメラ映像、USB機器のシリアル番号、氏名、メールアドレス等の個人情報は含まれません。

診断ログは自動的には外部へ送信されません。

ユーザーが「診断ログを共有」等の操作を行った場合に限り、Androidの共有機能を通じて、ユーザー自身が選択したアプリやサービスへ送信できます。

## 7. Firebase Analytics

本アプリでは、利用状況の把握およびアプリ改善のため、Google LLCが提供するFirebase Analyticsを使用しています。

Firebase Analyticsにより、以下のような情報が自動的に収集される場合があります。

- アプリの起動、セッション、画面表示等の利用情報
- 本アプリ独自のラップ計測関連イベント
- アプリのバージョン
- OSおよびOSバージョン
- 端末メーカー、端末モデル等の端末情報
- 言語、タイムゾーン等
- FirebaseまたはAnalyticsが生成するアプリインスタンス等の識別子
- IPアドレス等から推定される国・地域などのおおよその地域情報

本アプリが独自にFirebase Analyticsへ送信する主なイベントには、計測開始、ラップタイマー開始、ラップ完了、計測終了等があります。

個別のカメラ映像、USB機器情報、氏名、メールアドレス等をAnalyticsイベントとして送信することはありません。

本アプリではAndroid Advertising ID（広告ID）の収集を無効にしており、Analyticsのデータを広告パーソナライズに利用しないよう設定しています。

## 8. Firebase Crashlytics

本アプリでは、クラッシュや不具合の発見・改善のため、Google LLCが提供するFirebase CrashlyticsおよびCrashlytics NDKを使用しています。

アプリがクラッシュした場合等に、以下のような情報がGoogleへ送信される場合があります。

- クラッシュ情報およびスタックトレース
- ネイティブコードのクラッシュ情報
- クラッシュ発生時のアプリ状態
- アプリのバージョン
- OSおよびOSバージョン
- 端末モデル、CPUアーキテクチャ等の端末情報
- FirebaseおよびCrashlyticsが生成するインストール・セッション等の識別子
- クラッシュ直前のAnalyticsイベント

これらの情報は、アプリの安定性向上および不具合調査のために利用します。

## 9. 第三者サービスへのデータ送信

本アプリでは、利用状況分析およびクラッシュ解析のため、Google LLCが提供するFirebaseサービスへ必要なデータを送信します。

本アプリには広告表示SDKを組み込んでおらず、収集した情報を広告表示や広告パーソナライズのために利用しません。

また、開発者が収集したユーザーデータを販売することはありません。

## 10. データの安全性

Firebaseへのデータ送信には、FirebaseおよびGoogleが提供する通信保護の仕組みが使用されます。

開発者は、本アプリが取り扱うデータを、その目的に必要な範囲で利用するよう努めます。

## 11. データの保持と削除

ラップ履歴、設定、診断ログ等の本アプリが端末内に保存するデータは、アプリのデータを消去するか、本アプリをアンインストールすることで削除できます。

本アプリではユーザーアカウントを作成しないため、ユーザーの氏名やメールアドレスとFirebase上のAnalyticsまたはCrashlyticsデータを関連付けて管理していません。

Firebaseへ送信されたデータの保持および削除については、GoogleおよびFirebaseのデータ保持ポリシーに従います。

プライバシーに関するお問い合わせやデータの取り扱いについてのご相談は、下記の連絡先までお問い合わせください。なお、ユーザーを特定する情報を本アプリで収集していないため、特定のAnalyticsまたはCrashlyticsデータを個別のユーザーに関連付けて特定・削除できない場合があります。

## 12. 児童のプライバシー

本アプリは、児童から氏名、メールアドレス等の個人情報を意図的に収集する機能を提供していません。

## 13. 本プライバシーポリシーの変更

本アプリの機能変更、利用サービスの変更、法令またはGoogle Playのポリシー変更等に応じて、本プライバシーポリシーを変更する場合があります。

重要な変更がある場合は、本ページの更新等の適切な方法でお知らせします。

## 14. お問い合わせ

開発者：HARUBON

お問い合わせ先：
harubon.studio+tinypacemaker@gmail.com


---

# TinyPacemaker Privacy Policy

Last updated: September 14, 2026

HARUBON ("the Developer") provides the Android application "TinyPacemaker" ("the App"). This Privacy Policy explains how information is handled when using the App.

## 1. About the App

TinyPacemaker is an application designed to detect gate markers from a camera feed and measure lap times for FPV drones and similar uses.

The App does not require users to create an account or sign in.

## 2. Camera Data

The App uses video from the device's built-in camera or a connected USB camera for lap timing.

Camera frames are processed locally on the device to detect gate markers.

The App does not upload camera video or images to the Developer, Firebase, or any other external server. Camera footage is not saved as image or video files by the App.

## 3. Gate Marker Data

The App detects ArUco markers from the camera feed.

Information such as marker IDs, positions, areas, and gate-passage determinations is processed locally on the device for lap timing.

This information is not transmitted to the Developer's servers.

## 4. USB Device Information

To connect to and control a USB camera, Android and the USB libraries used by the App may temporarily access information about the connected USB device.

This information may include vendor ID, product ID, manufacturer name, product name, serial number, and related USB device information.

This information is used locally for USB device connection and control and is not transmitted by the App to Firebase or other external services.

## 5. Data Stored on the Device

The App may store the following information in its private application storage:

- Lap history
- Lap timing settings
- Camera and display settings
- Language settings
- Other settings required for operation of the App

These data are intended to remain on the device.

Android cloud backup is disabled for the App. The App also requests exclusion from device-to-device transfer where supported by Android. However, certain device manufacturers may provide migration mechanisms that cannot be fully controlled by the App.

## 6. Diagnostic Logs

If the user enables diagnostic logging, the App may store diagnostic information locally for troubleshooting purposes.

Diagnostic logs may include information such as timestamps, elapsed time, marker detection status, and gate-passage results.

Diagnostic logs do not contain camera images, USB device serial numbers, names, email addresses, or similar personal information.

Diagnostic logs are not automatically transmitted.

They are only transferred to another app or service when the user explicitly chooses to share them using Android's sharing functionality.

## 7. Firebase Analytics

The App uses Firebase Analytics, provided by Google LLC, to understand how the App is used and to improve its functionality.

Firebase Analytics may automatically collect information such as:

- App launches, sessions, screen views, and other usage information
- App-specific lap timing events
- App version
- Operating system and OS version
- Device manufacturer and model
- Language and time zone
- App-instance and similar identifiers generated by Firebase or Analytics
- Approximate geographic information such as country or region inferred from network information

The App sends custom Analytics events for actions such as starting a measurement session, starting lap timing, completing a lap, and ending a measurement session.

The App does not include camera images, USB device information, names, email addresses, or similar personal information in its custom Analytics events.

Collection of the Android Advertising ID is disabled in the App, and Analytics data is configured not to be used for advertising personalization.

## 8. Firebase Crashlytics

The App uses Firebase Crashlytics and Crashlytics NDK, provided by Google LLC, to identify and diagnose crashes and stability problems.

When a crash or related problem occurs, information such as the following may be transmitted to Google:

- Crash information and stack traces
- Native crash information
- Relevant application state at the time of the crash
- App version
- Operating system and OS version
- Device model and CPU architecture
- Installation and session identifiers generated by Firebase and Crashlytics
- Analytics events occurring before a crash

This information is used to diagnose problems and improve the reliability of the App.

## 9. Third-Party Services

The App transmits necessary data to Firebase services provided by Google LLC for usage analytics and crash diagnostics.

The App does not contain an advertising SDK and does not use collected information to display or personalize advertisements.

The Developer does not sell user data.

## 10. Data Security

Data transmitted to Firebase is protected using the security mechanisms provided by Firebase and Google.

The Developer seeks to limit the collection and use of data to what is necessary for operation, analytics, and improvement of the App.

## 11. Data Retention and Deletion

Local data such as lap history, settings, and diagnostic logs can be deleted by clearing the App's storage or uninstalling the App.

The App does not create user accounts and does not associate a user's name or email address with Firebase Analytics or Crashlytics data.

Data transmitted to Firebase is retained and deleted according to the applicable Google and Firebase data retention policies.

For privacy questions or inquiries regarding data handling, please contact the Developer using the contact information below. Because the App does not collect information that directly identifies individual users, it may not be technically possible to identify and delete specific Analytics or Crashlytics records belonging to a particular user.

## 12. Children's Privacy

The App does not provide functionality intended to collect names, email addresses, or similar personal information from children.

## 13. Changes to This Privacy Policy

This Privacy Policy may be updated when the App's functionality, third-party services, applicable laws, or Google Play policies change.

Material changes will be communicated by updating this page or by other appropriate means.

## 14. Contact

Developer: HARUBON

Contact:
harubon.studio+tinypacemaker@gmail.com
