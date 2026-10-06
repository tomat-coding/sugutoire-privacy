# Privacy Policy / プライバシーポリシー

**すぐトイレ (Sugu Toire)**  
Last updated: October 2026 / 最終更新日：2026年10月

---

## English

### 1. Information We Collect

#### Location data
すぐトイレ uses your device's location to find nearby toilets:

- while you use the app, and
- if you add the home screen widget, periodically in the background (about every 15 minutes) to keep the widget up to date.

To search for toilets, the app sends your current coordinates to the Overpass API, a public search service for OpenStreetMap data (see section 4). Your location is not stored on our servers, and we do not keep a history of where you have been.

#### Toilet issue reports
When you report a problem with a toilet, we store:

- Toilet identifier, name and coordinates
- Issue type selected
- Optional comment you provide
- App version
- Submission timestamp

#### New toilet submissions
When you suggest a new toilet, we store the details you enter: its name (optional), its position on the map, type, access, opening hours, accessibility, changing table, ostomate facilities, Western-style toilet, unisex toilet, number of stalls, an optional description of where the toilet is (for example "2F, next to the elevator"), and the submission time. The map pin starts at your current location, so the submitted position may be close to where you are. While you choose the position, the map is loaded from MapTiler (see section 4).

#### App usage statistics
To understand how the app is used and to improve it, we collect usage events:

- Which screens of the app are opened
- When you start navigation to a toilet: the toilet's identifier and type, how navigation was started (nearby list, widget, status card or the "Navigate to nearest" button), its position in the list, and an approximate distance range (for example "500 m – 1 km")
- Standard events that Google Analytics records automatically, such as when the app is first opened, app sessions and time spent in the app
- App version, device model, operating system version and approximate region (country or city level)

These statistics are collected with Google Analytics for Firebase, which uses a random identifier created for each app installation. They are not linked to your name or any account. We export a copy of these statistics, including that identifier, to Google BigQuery, where we analyse them for statistics and for features such as showing which toilets are popular. The app itself does not send usage events anywhere else.

#### Crash reports
If the app crashes, a crash report is sent with Firebase Crashlytics: technical details of the error, device model, operating system and app version, and a random installation identifier.

#### We do not collect
- Your name, email address, phone number or any account information (the app has no accounts)
- Advertising IDs (the app does not use the advertising ID or any advertising services)
- A history of your locations
- Photos, contacts or other content from your device

---

### 2. How We Use Your Information

- **Location**: to find nearby toilets and calculate distances, in the app and the widget. Not stored.
- **Reports and new toilet submissions**: to keep toilet information accurate for everyone. They are reviewed and used to update location information.
- **Usage statistics**: to understand which features and toilets are used, to fix problems, to improve the app, and for features such as toilet popularity.
- **Crash reports**: to find and fix errors.

We do not use your data for advertising, and we do not sell or rent it.

---

### 3. Data Storage and Security

Reports and new toilet submissions are stored in Google Firebase Firestore. Access rules allow the app to add records, but not to read, change or delete them. Usage statistics and crash reports are processed by Google as described in section 4. The copy of usage statistics we export to Google BigQuery is stored in Google Cloud's Tokyo region and is accessible only to us. Data is transmitted over encrypted connections (HTTPS).

---

### 4. Third-Party Services and External Transmission of Information

The app sends information to the following services. This section also serves as the public notice of external transmission of user information required under Japan's Telecommunications Business Act.

| Service (provider) | Information sent | Purpose |
|---|---|---|
| Overpass API (overpass-api.de, operated for OpenStreetMap data) | Your current coordinates (to search within about 2 km) and, as with any internet request, your IP address | Finding nearby toilets |
| MapTiler (MapTiler AG) | Only when you suggest a new toilet: the map area being viewed (which starts at your current location) and, as with any internet request, your IP address | Showing the map for choosing the toilet's position |
| Google Analytics for Firebase (Google LLC) | Usage events described in section 1, app-instance identifier, device and app information | App usage statistics and features such as toilet popularity (a copy is exported to Google BigQuery, see section 3) |
| Firebase Crashlytics (Google LLC) | Crash details, device and app information, installation identifier | Fixing errors |
| Firebase Remote Config (Google LLC) | App and device information, installation identifier | Delivering app settings, such as update notices and in-app notices |
| Firebase Firestore (Google LLC) | Reports and new toilet submissions described in section 1 | Storing this information |
| Google Maps (Google LLC) | Opened only when you tap Navigate; the destination toilet's coordinates and, depending on the navigation mode, its name and address are passed to the Maps app | Navigation |

Google's privacy policy: [https://policies.google.com/privacy](https://policies.google.com/privacy)  
How Google uses information from apps that use its services: [https://policies.google.com/technologies/partner-sites](https://policies.google.com/technologies/partner-sites)  
Toilet location data comes from OpenStreetMap ([openstreetmap.org](https://www.openstreetmap.org)), a community-maintained open database.

---

### 5. Your Choices

- **Location**: you can turn off location access for the app at any time in your device settings. The app cannot find nearby toilets without it.
- **Widget**: removing the widget from your home screen stops background updates.
- **Usage statistics and crash reports**: these are part of how the app works and cannot be switched off inside the app. Uninstalling the app stops all collection.

Usage statistics are not linked to your name or any account, so we generally cannot identify which records belong to you. If you have a question about your data, contact us (section 9).

---

### 6. Data Retention

- **Location**: not retained. It is used on your device and in the toilet search, then discarded.
- **Reports and new toilet submissions**: kept indefinitely, to maintain data quality.
- **Usage statistics in Google Analytics**: kept according to the data retention period set in Google Analytics.
- **Usage statistics exported to Google BigQuery**: kept for long-term statistics, such as toilet popularity, and deleted when no longer needed.
- **Crash reports**: kept by Firebase Crashlytics for 90 days.

---

### 7. Children's Privacy

すぐトイレ is not directed at children under the age of 13. We do not knowingly collect personal information from children.

---

### 8. Changes to This Policy

We may update this privacy policy from time to time. Changes will be posted on this page with an updated date. Continued use of the app after changes constitutes acceptance of the new policy.

---

### 9. Contact

If you have questions about this privacy policy, please contact us at:  
**tomat.firma@gmail.com**

---

---

## 日本語

### 1. 収集する情報

#### 位置情報
すぐトイレは、近くのトイレを探すためにデバイスの位置情報を使用します。

- アプリの使用中
- ホーム画面にウィジェットを追加している場合は、ウィジェットを最新の状態に保つため、バックグラウンドで定期的に（約15分ごと）

トイレを検索するため、アプリは現在地の座標を、OpenStreetMapのデータを検索する公開サービス「Overpass API」に送信します（第4項参照）。位置情報を当社のサーバーに保存することはなく、移動履歴も保持しません。

#### トイレの問題の報告
トイレの問題を報告した場合、以下の情報を保存します：

- トイレの識別子、名称、座標
- 選択した問題の種類
- 任意で入力したコメント
- アプリのバージョン
- 送信日時

#### 新しいトイレの登録
新しいトイレを報告した場合、入力された内容（名称（任意）、地図上の位置、種類、利用条件、営業時間、バリアフリー対応、おむつ交換台、オストメイト対応、洋式トイレ、男女共用トイレ、個室の数、任意で入力した場所の説明（例：「2階、エレベーター横」））と送信日時を保存します。地図のピンは現在地から始まるため、送信される位置はお客様の現在地に近い場合があります。位置を選ぶ際の地図はMapTilerから読み込まれます（第4項参照）。

#### アプリの利用統計
アプリの利用状況を把握し改善するため、以下の利用イベントを収集します：

- アプリで開いた画面
- トイレへのナビを開始したとき：トイレの識別子と種類、ナビの開始方法（周辺リスト、ウィジェット、ステータスカード、「最寄りへナビゲート」ボタン）、リスト内の順位、おおよその距離の範囲（例：「500m〜1km」）
- Google Analyticsが自動的に記録する標準イベント（初回起動、アプリの利用セッション、利用時間など）
- アプリのバージョン、端末のモデル、OSのバージョン、おおよその地域（国・都市レベル）

これらの統計はGoogle Analytics for Firebaseで収集され、アプリのインストールごとに作成されるランダムな識別子が使用されます。氏名やアカウントとは結び付けられません。当社はこの統計の写しを、その識別子を含めてGoogle BigQueryにエクスポートし、統計や人気のトイレの表示などの機能のために分析します。アプリ自体が利用イベントをこれ以外の送信先に送ることはありません。

#### クラッシュレポート
アプリがクラッシュした場合、Firebase Crashlyticsによりクラッシュレポートが送信されます。内容は、エラーの技術的な詳細、端末のモデル、OSとアプリのバージョン、ランダムなインストール識別子です。

#### 収集しない情報
- 氏名、メールアドレス、電話番号、その他のアカウント情報（アプリにアカウント機能はありません）
- 広告ID（広告IDおよび広告サービスは使用しません）
- 位置情報の履歴
- 写真、連絡先など端末内のその他のデータ

---

### 2. 情報の使用方法

- **位置情報**：アプリとウィジェットで近くのトイレを探し、距離を計算するため。保存はしません。
- **報告・新しいトイレの登録**：すべての利用者のためにトイレ情報を正確に保つため。内容を確認し、場所情報の更新に活用します。
- **利用統計**：よく使われる機能やトイレを把握し、不具合の修正やアプリの改善、トイレの人気表示などの機能に役立てるため。
- **クラッシュレポート**：エラーを見つけて修正するため。

データを広告に使用することはなく、販売・貸与することもありません。

---

### 3. データの保存とセキュリティ

報告と新しいトイレの登録はGoogle Firebase Firestoreに保存されます。アクセスルールにより、アプリからは記録の追加のみが可能で、読み取り・変更・削除はできません。利用統計とクラッシュレポートは、第4項のとおりGoogleが処理します。Google BigQueryにエクスポートした利用統計の写しは、Google Cloudの東京リージョンに保存され、当社のみがアクセスできます。通信は暗号化（HTTPS）されています。

---

### 4. 第三者サービスと外部送信について

アプリは以下のサービスに情報を送信します。本項は、電気通信事業法に基づく利用者情報の外部送信に関する公表を兼ねています。

| 送信先（提供者） | 送信される情報 | 利用目的 |
|---|---|---|
| Overpass API（overpass-api.de、OpenStreetMapデータの検索サービス） | 現在地の座標（約2km以内を検索するため）、およびインターネット通信に伴うIPアドレス | 近くのトイレの検索 |
| MapTiler（MapTiler AG） | 新しいトイレを登録する場合のみ：表示中の地図の範囲（最初は現在地周辺）、およびインターネット通信に伴うIPアドレス | トイレの位置を選ぶための地図の表示 |
| Google Analytics for Firebase（Google LLC） | 第1項に記載の利用イベント、アプリインスタンス識別子、端末・アプリの情報 | アプリの利用統計、およびトイレの人気表示などの機能（写しをGoogle BigQueryにエクスポートします。第3項参照） |
| Firebase Crashlytics（Google LLC） | クラッシュの詳細、端末・アプリの情報、インストール識別子 | エラーの修正 |
| Firebase Remote Config（Google LLC） | アプリ・端末の情報、インストール識別子 | アップデートのお知らせなど、アプリ設定の配信 |
| Firebase Firestore（Google LLC） | 第1項に記載の報告と新しいトイレの登録 | これらの情報の保存 |
| Google マップ（Google LLC） | 「ナビゲート」をタップした場合のみ起動し、目的地のトイレの座標と、ナビの方法によってはその名称・住所をマップアプリに渡します | ナビゲーション |

Googleのプライバシーポリシー：[https://policies.google.com/privacy](https://policies.google.com/privacy)  
Googleのサービスを使用するアプリから収集した情報のGoogleによる使用について：[https://policies.google.com/technologies/partner-sites](https://policies.google.com/technologies/partner-sites)  
トイレの位置データは、コミュニティが管理するオープンデータベースであるOpenStreetMap（[openstreetmap.org](https://www.openstreetmap.org)）から取得しています。

---

### 5. お客様の選択

- **位置情報**：端末の設定で、いつでもアプリの位置情報へのアクセスをオフにできます。オフにすると近くのトイレを探すことはできません。
- **ウィジェット**：ホーム画面からウィジェットを削除すると、バックグラウンドでの更新は停止します。
- **利用統計・クラッシュレポート**：アプリの機能の一部であり、アプリ内でオフにすることはできません。アプリをアンインストールすると、すべての収集が停止します。

利用統計は氏名やアカウントと結び付いていないため、どの記録がお客様のものかを当社が特定することは通常できません。データについてのご質問は、第9項の連絡先までお問い合わせください。

---

### 6. データの保持期間

- **位置情報**：保持しません。端末上およびトイレの検索で使用した後、破棄されます。
- **報告、新しいトイレの登録**：データ品質の維持のため、無期限に保持します。
- **Google Analyticsの利用統計**：Google Analyticsで設定したデータ保持期間に従って保持されます。
- **Google BigQueryにエクスポートした利用統計**：トイレの人気表示などの長期的な統計のために保持し、不要になった時点で削除します。
- **クラッシュレポート**：Firebase Crashlyticsにより90日間保持されます。

---

### 7. 子どものプライバシー

すぐトイレは13歳未満の子どもを対象としていません。子どもから意図的に個人情報を収集することはありません。

---

### 8. ポリシーの変更

このプライバシーポリシーは随時更新される場合があります。変更はこのページに更新日とともに掲載されます。変更後もアプリを継続して使用することで、新しいポリシーに同意したものとみなされます。

---

### 9. お問い合わせ

このプライバシーポリシーに関するご質問は、以下のメールアドレスまでお問い合わせください：  
**tomat.firma@gmail.com**
