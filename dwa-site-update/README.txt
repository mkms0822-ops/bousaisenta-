DWA防災情報センター サイト更新(団体案内・沿革・長岡京市版リンク)
================================================================

【ファイルと置き場所】
 main/index.html      → メインサイト(地震速報LIVE)の index.html と差し替え
 home/index.html      → 長岡京市版サイト(mkms0822-ops.github.io/nagaokakyoushi_bousai_site/)の index.html と差し替え
 organization.html    → 【新規】長岡京市版サイトの、index.html と同じ場所に追加
 staff.html           → 長岡京市版サイトの staff.html と差し替え(フッターに「組織概要・沿革」を追加)
 activity.html        → 長岡京市版サイトの activity.html と差し替え(フッターに「組織概要・沿革」を追加)

 ※ activity.html が使う動画(activity-intro.mp4)・画像(sec-*.png、staff-*.png)は変更していません。
 ※ organization.html を長岡京市版サイトに追加しないと、メニューの「組織概要・沿革」は開けません(先に追加してください)。

【メインサイト(main/index.html)に追加したもの】
 メニューに、新しいグループ「🏢 団体案内」(6項目)を追加しました。「公式アカウント」の次に入っています。
  1. DWA防災情報センター 長岡京市版  → https://mkms0822-ops.github.io/nagaokakyoushi_bousai_site/
  2. 組織概要・沿革                   → organization.html
  3. 活動と目標                       → activity.html
  4. スタッフ紹介                     → staff.html#staff
  5. アクセス方法                     → staff.html#access
  6. 問い合わせ窓口                   → staff.html#contact
 ・2〜6のリンクは、ファイル末尾の ORG_BASE(長岡京市版サイトのURL)を先頭に付けて開きます。
   置き場所を変えるときは、ORG_BASE の1行だけを変更してください(同じフォルダなら '' にします)。
 ・サイトの使い方ツアーの「メニューは大きく7つのグループ」を、8つのグループの説明に更新しました。

【長岡京市版サイト(home/index.html)に追加したもの】
 メニュー「団体について」に、「組織概要・沿革」と「アクセス方法」を追加しました。

【組織概要・沿革(organization.html)の内容】
 組織概要 / 沿革 / 活動目標 / アクセス(地図・経路検索ボタン)。
 沿革は、活動と目標のページ、団体案内のページに書かれている事実だけで作っています。
   2018年1月   Twitter(現X)アカウントを開設
   約8年を経て  DWA防災情報センターとしてリスタート
   2026年7月   令和8年 熊本地震で、デジタル情報による後方支援
   現在        長岡京市災害ボランティアセンターとの災害時パートナーシップ協定を協議中
   2030年(目標) 誰も取りこぼさない防災社会の実現へ
 年月日が分かる出来事(例:市民活動団体の認定、各ツールの公開、協定の締結など)は、
 organization.html の <div class="tl"> の中に、同じ形のブロックを足すだけで追加できます。
