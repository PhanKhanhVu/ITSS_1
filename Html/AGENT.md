# システム概要 (Tổng quan hệ thống)

## 4. アプリ名称 (Tên ứng dụng)
**JP Food**

---

## 1. 問題 (Vấn đề)
* ハノイに日本から出張で来た日本人に、日本人の口に合うおいしいベトナム料理の店を紹介することができない。 (Không thể giới thiệu bất kỳ nhà hàng Việt Nam ngon nào phù hợp với khẩu vị người Nhật cho những người Nhật đến Hà Nội công tác.)
* 日本人のお客さんになかなか来てもらえない。 (Việc thu hút khách hàng Nhật Bản rất khó.)

---

## 2. 想定ユーザー (Người dùng dự kiến)
* ハノイで働いている日本人 (Người Nhật làm việc tại Hà Nội)
* ハノイで日本語が話せるレストラン経営者 (Chủ nhà hàng nói tiếng Nhật tại Hà Nội)

---

## 3. 課題・解決策 (Thách thức & Giải pháp)

| ID | 想定ユーザー (Người dùng dự kiến) | 課題：解決に向けて取り組むべきこと・理想の状態 (Thách thức / Trạng thái lý tưởng) | 解決策：課題を実行・実現するための具体的手段 (Giải pháp) |
|:---|:---|:---|:---|
| 1 | Người Nhật làm việc tại Hà Nội | 日本人の口に合うベトナム料理店の情報が少ない。<br>(Có rất ít thông tin về các nhà hàng Việt Nam phù hợp với khẩu vị người Nhật.) | 日本人の口に合うベトナム料理店の情報を集め、紹介する仕組みを作る。<br>(Thu thập và giới thiệu danh sách nhà hàng Việt phù hợp với khẩu vị người Nhật: ít dầu mỡ, sạch sẽ, dễ ăn.) |
| 2 | Người Nhật làm việc tại Hà Nội | 参加者が簡単に準備し参加できるようにするための包括的な「出席パッケージ」はまだ存在しません。<br>(Chưa có một “gói attend” tổng hợp giúp họ dễ dàng chuẩn bị, tham dự) | 経営者が、日本人出張者に人気のメニューを絞った「お任せコース（飲み物込み・定額）」を用意し、駐在員が注文に迷わなくて済むようにする。<br>(Ban quản lý chuẩn bị một "thực đơn omakase" bao gồm đồ uống, giá cố định với tuyển chọn các món ăn phổ biến dành cho khách doanh nhân Nhật Bản.) |
| 3 | Người Nhật làm việc tại Hà Nội | 日本人のレビューや評価が少ない。<br>(Khó đánh giá chất lượng nhà hàng trước khi đi) | 日本人の利用者によるレビューや評価を共有できる仕組みを作る。<br>(Hệ thống review từ người Nhật.) |
| 4 | Người Nhật làm việc tại Hà Nội | 接待や出張の食事に適した店が分かりにくい。<br>(Khó biết nhà hàng nào phù hợp cho việc tiếp khách hoặc ăn uống khi đi công tác) | 接待向け、ビジネスミーティング向け、カジュアルなどのカテゴリーでレストランを分類する。<br>(Phân loại nhà hàng theo các mục đích như: tiếp khách, họp công việc, hoặc ăn uống bình thường.) |
| 5 | Người Nhật làm việc tại Hà Nội | 衛生面や安全性に対する不安がある。<br>(Người Nhật lo lắng về vấn đề vệ sinh và an toàn thực phẩm) | 店の衛生状態や安全性、証明書などの情報を分かりやすく紹介する。<br>(Cung cấp rõ ràng thông tin về vệ sinh, an toàn thực phẩm và các chứng nhận của nhà hàng) |
| 6 | Chủ nhà hàng nói tiếng Nhật tại Hà Nội | レストラン側が日本人客に効果的にアピールできていない<br>(Nhà hàng không biết cách tiếp cận khách Nhật) | 日本人向けの情報発信やマーケティングの方法を提供する。<br>(Hướng dẫn marketing hoặc nền tảng kết nối với khách Nhật.) |
| 7 | Người Nhật làm việc tại Hà Nội | 日本語で予約や問い合わせができる店が少ない<br>(Khó đặt bàn hoặc liên hệ bằng tiếng Nhật) | 日本語で予約や問い合わせができるオンライン予約システムを作る。<br>(Tạo hệ thống đặt bàn và liên hệ bằng tiếng Nhật) |
| 8 | Người Nhật làm việc tại Hà Nội | 日本人におすすめのベトナム料理が分かりにくい<br>(Không biết món Việt nào nên giới thiệu cho người Nhật) | フォー、ブンチャー、生春巻きなど、日本人に人気のベトナム料理を紹介する。<br>(Giới thiệu các món Việt phù hợp với người Nhật như phở, bún chả, gỏi cuốn.) |
| 9 | Người Nhật làm việc tại Hà Nội | 店の場所やアクセス方法が分かりにくい<br>(Thiếu thông tin vị trí và cách di chuyển) | 地図やアクセス方法、最寄り駅などの情報を分かりやすく掲載する。<br>(Cung cấp bản đồ, hướng dẫn đường đi và thông tin giao thông rõ ràng.) |
| 10 | Người Nhật làm việc tại Hà Nội<br>Chủ nhà hàng nói tiếng Nhật tại Hà Nội | 日本人とレストランのつながりが弱い<br>(Thiếu sự kết nối giữa cộng đồng người Nhật và nhà hàng) | 日本人コミュニティとレストランをつなぐオンラインプラットフォームを作る。<br>(Xây dựng nền tảng kết nối giữa cộng đồng người Nhật và các nhà hàng.) |

---

## 5. ロール一覧 (Danh sách vai trò)

| ID | ロール名 (Tên vai trò) | 役割 (Vai trò / Chức năng) |
|:---|:---|:---|
| 1 | 1. 一般ユーザー（日本人客）<br>(Người dùng thông thường - Khách Nhật Bản) | ハノイのベトナム料理店を検索し、レビューを閲覧・投稿する。また、お気に入りの店舗を保存し、コースの予約を行う。<br>(Tìm kiếm các quán ăn Việt Nam tại Hà Nội, xem và đăng tải đánh giá. Ngoài ra, có thể lưu lại các quán yêu thích và đặt trước Set menu/bàn.) |
| 2 | 2. 店舗管理者（レストランオーナー）<br>(Quản lý cửa hàng - Chủ nhà hàng) | 自身の店舗情報を登録・更新し、日本人客からの評価を分析・返信する。また、接待コースや予約の管理を行う。<br>(Đăng ký, cập nhật thông tin quán của mình, phân tích và phản hồi các đánh giá từ khách hàng Nhật. Ngoài ra, quản lý các Set menu tiếp khách và các lượt đặt bàn.) |
| 3 | 3. システム管理者（運営側）<br>(Quản trị viên hệ thống - Ban quản trị) | ユーザーと店舗のアカウントを管理し、不適切なレビューや店舗情報の監視・削除を行う。<br>(Quản lý tài khoản của người dùng và nhà hàng, giám sát và xóa các bài đánh giá hoặc thông tin quán ăn không phù hợp.) |

---

## 6. 機能一覧 (Danh sách chức năng)

| ID | 機能名 (Tên chức năng) | 解決策ID (ID Giải pháp) | 対象ロールID (ID Vai trò) | 機能の概要 (Tổng quan chức năng) |
|:---|:---|:---|:---|:---|
| 1 | メニュー多言語表示 (Hiển thị thực đơn đa ngôn ngữ) | 1 | 1 | レストランのメニューを日本語で表示する。<br>(Hiển thị thực đơn nhà hàng bằng tiếng Nhật.) |
| 2 | 料理写真表示 (Hiển thị hình ảnh món ăn) | 1 | 1 | 各料理に写真を添えて視覚的に分かりやすくする。<br>(Hiển thị hình ảnh cho từng món ăn để dễ hình dung.) |
| 3 | 店舗情報登録・管理 (Đăng ký & quản lý thông tin quán) | 6 | 2 | 店舗がメニューや基本情報を登録・更新できる。<br>(Nhà hàng có thể đăng ký và cập nhật thực đơn, thông tin cơ bản.) |
| 4 | 日本人向けレビュー閲覧 (Xem đánh giá từ người Nhật) | 3 | 1 | 日本人ユーザーのレビューを表示し、信頼性を高める。<br>(Hiển thị đánh giá từ người dùng Nhật để tăng độ tin cậy.) |
| 5 | 評価・口コミ投稿 (Đăng đánh giá & nhận xét) | 3 | 1 | 星評価やコメントを投稿して体験を共有する。<br>(Đăng tải đánh giá sao và bình luận để chia sẻ trải nghiệm.) |
| 6 | 高度な検索・フィルター (Tìm kiếm & lọc nâng cao) | 4 | 1 | 条件（価格、場所、目的）で最適な店を探せる。<br>(Tìm kiếm quán phù hợp theo điều kiện: giá cả, vị trí, mục đích.) |
| 7 | 日本語予約機能 (Đặt bàn bằng tiếng Nhật) | 7 | 1, 2 | 日本語で簡単に予約し、店舗側で確認・管理する。<br>(Đặt bàn bằng tiếng Nhật; nhà hàng xác nhận và quản lý.) |
| 8 | おすすめ料理提案 (Gợi ý món ăn thông minh) | 8 | 1 | 日本人の好みに合った料理を AI が提案する。<br>(AI gợi ý các món ăn phù hợp với khẩu vị của người Nhật.) |
| 9 | 地図・ルート案内連携 (Tích hợp bản đồ & chỉ đường) | 9 | 1 | 現在地から店舗までのルートを地図上に表示する。<br>(Hiển thị bản đồ và chỉ đường từ vị trí hiện tại đến nhà hàng.) |
| 10 | ユーザー・権限管理 (Quản lý người dùng & phân quyền) | 10 | 1, 2, 3 | 各ロールの権限に基づき、アカウントを管理する。<br>(Quản lý tài khoản dựa trên quyền hạn của từng vai trò.) |
| 11 | アレルギー・辛さ表示 (Thông tin dị ứng & độ cay) | 11 | 1 | 料理ごとのアレルギー情報や辛さレベルを表示する。<br>(Hiển thị thông tin dị ứng và mức độ cay của từng món ăn.) |
| 12 | クーポン・特典管理 (Quản lý mã giảm giá & ưu đãi) | 12 | 1, 2 | 日本人限定の特典を発行・利用する。<br>(Phát hành và sử dụng các mã giảm giá hoặc ưu đãi dành riêng cho khách Nhật.) |
| 13 | リアルタイム通知 (Thông báo thời gian thực) | 13 | 1, 2 | 予約の確定やキャンセルをプッシュ通知で知らせる。<br>(Thông báo đẩy về trạng thái đặt bàn theo thời gian thực.) |
| 14 | AI 翻訳サポート (Hỗ trợ dịch thuật AI) | 14 | 2 | 店主の入力を正確な日本語に AI が変換・修正する。<br>(Hỗ trợ AI dịch và chỉnh sửa thông tin từ chủ quán sang tiếng Nhật chuẩn.) |
| 15 | 衛生管理表示 (Hiển thị trạng thái vệ sinh) | 15 | 1 | レストランの衛生状態やクリーン認証を表示する。<br>(Hiển thị trạng thái vệ sinh hoặc chứng chỉ sạch sẽ của nhà hàng.) |

---

## 7. 画面一覧 (Danh sách màn hình)

*(Lưu ý: Một số ID Chức năng hiển thị dạng ngày tháng (VD: 2012-10-07) do lỗi định dạng tự động của Excel từ file gốc, mình giữ nguyên để bạn dễ đối chiếu).*

| ID | 画面名 (Tên màn hình) | 機能ID (ID Chức năng) | 対象ロールID (ID Vai trò) | 画面の概要 (Tổng quan màn hình) |
|:---|:---|:---|:---|:---|
| 1 | ホーム画面 (Trang chủ) | 6, 8 | 1, 2, 3 | 検索、カテゴリ、おすすめ料理を表示するメイン画面。<br>(Màn hình chính hiển thị tìm kiếm, danh mục và gợi ý món ăn.) |
| 2 | 検索結果一覧画面 (Kết quả tìm kiếm) | 6 | 1, 3 | 条件に一致する店舗をリスト形式で表示する。<br>(Hiển thị danh sách các nhà hàng khớp với điều kiện tìm kiếm.) |
| 3 | 店舗詳細画面 (Chi tiết nhà hàng) | 1, 2, 3, 4, 11 | 1, 2, 3 | メニュー、写真、レビュー、地図などの詳細情報。<br>(Thông tin chi tiết về thực đơn, ảnh, đánh giá, bản đồ và chú ý.) |
| 4 | 予約フォーム画面 (Form đặt chỗ) | 7 | 1 | 日時、人数を選択してオンライン予約を行う画面。<br>(Màn hình chọn ngày giờ, số lượng người để đặt chỗ trực tuyến.) |
| 5 | マイページ (Trang cá nhân) | 2012-10-07 | 1 | プロフィール、予約履歴、お気に入りを確認する。<br>(Quản lý hồ sơ, xem lịch sử đặt bàn và danh sách yêu thích.) |
| 6 | 店舗ダッシュボード (Quản lý cửa hàng) | 2013-06-03 | 2 | 統計データや新規予約数を確認するオーナー用画面。<br>(Màn hình cho chủ quán xem thống kê và số lượng đặt bàn mới.) |
| 7 | 店舗・メニュー編集画面 (Chỉnh sửa) | 1, 2, 3, 14 | 2 | 店舗情報やメニュー、価格を更新するための画面。<br>(Giao diện để cập nhật thông tin quán, món ăn và giá cả.) |
| 8 | 予約管理画面 (Quản lý đặt bàn) | 7 | 2 | 予約リクエストを確認し、承認または却下する。<br>(Màn hình để xác nhận, phê duyệt hoặc từ chối yêu cầu đặt bàn.) |
| 9 | レビュー投稿画面 (Viết đánh giá) | 5 | 1 | 利用後の感想、写真、評価を入力するフォーム。<br>(Biểu mẫu để nhập cảm nhận, ảnh và đánh giá sau khi trải nghiệm.) |
| 10 | システム管理画面 (Quản lý hệ thống) | 10 | 3 | 管理者がユーザーや不適切なコンテンツを監視する。<br>(Màn hình để quản trị viên giám sát người dùng và nội dung.) |
| 11 | 通知センター画面 (Thông báo) | 13 | 1, 2 | 予約状況やシステムからのお知らせを一覧表示する。<br>(Màn hình xem danh sách trạng thái đặt bàn và thông báo hệ thống.) |
| 12 | クーポン一覧画面 (Mã giảm giá) | 12 | 1, 2 | 利用可能なクーポンや特典を保存・管理する画面。<br>(Màn hình lưu trữ và quản lý các mã giảm giá, ưu đãi đang có.) |
| 13 | 分析レポート画面 (Báo cáo) | 3, 10 | 2 | 客層や売れ筋メニューをグラフで分析す。<br>(Màn hình cho chủ quán phân tích biểu đồ về khách hàng và món ăn.) |
| 14 | お問い合わせ画面 (Hỗ trợ) | 10 | 1, 2 | 運営に質問やフィードbackを送るための画面。<br>(Giao diện gửi câu hỏi hoặc phản hồi cho ban quản trị.) |
| 15 | お気に入りリスト画面 (Yêu thích) | 6 | 1 | 保存したレストランや料理を素 nhanh chóng truy cập。<br>(Giao diện xem nhanh các nhà hàng hoặc món ăn đã lưu.) |
| 16 | ログイン画面 (Màn hình đăng nhập) | 10 | 1, 2, 3 | IDとパスワードを入力してログインする画面です。正しく入力するとホーム画面へ移動します。<br>(Đây là màn hình để nhập tài khoản và mật khẩu đăng nhập. Nếu nhập đúng, người dùng sẽ chuyển đến màn hình chính) |