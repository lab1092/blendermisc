===========
Blender FAQ
===========

   :Original Written by: Light
   :Original URL: https://studiollb.wordpress.com/2014/10/11/blender-faq/
   :Language: ja(日本語)
   :Translation: TETSUO Mitsuda (@lab1092)
   :Last changed: 2014/10/21


.. caution::
   このページは日本語訳のページです。原則としてオリジナルを元に翻訳したものを掲載しています。

-----

   .. This FAQ is featured on Blender Nation on 2014/10/14

この `FAQ <https://studiollb.wordpress.com/2014/10/11/blender-faq/>`_ は 2014年10月14日の `BlenderNationに掲載され  <http://www.blendernation.com/2014/10/14/blender-faq/>`_ ました。

   .. `Traducción al español <http://syntherelia.com/post/blender-faq-preguntas-frecuentes/>`_ . `中文翻译 <http://www.blenderget.com/blender-faq/>`_ . `日本語訳 <http://lab1092.wordpress.com/blenderfaqja/>`_ .

`スペイン語訳 <http://syntherelia.com/post/blender-faq-preguntas-frecuentes/>`_ . `中国語訳 <http://www.blenderget.com/blender-faq/>`_ . `日本語訳 <http://lab1092.wordpress.com/blenderfaqja/>`_ .



   .. This FAQ is designed for new Blender users learning and making sense of Blender’s basics. New Blender users can be young artists without prior 3D knowledge or artists migrating to or testing Blender. We hope regardless of your background, you can enjoy Blender better through

このFAQはBlenderの基礎を学んでいる、覚えようとしている新しいBlenderユーザーのために設けました。
私たちはあなたのバックグラウンドを考慮することなしにBlenderを以下を通してBlenderを楽しむことができることを願います。

   .. 1. Discovering,
      2. Understanding &
      3. Practicing what is written here.

1. 発見し、
2. 理解し、そして
3. ここに書いてあることを練習する。


   .. Feel free to ask any Blender related questions, we are happy to help. Your question may get featured in the FAQ. For senior Blenderheads, if you have better answer to these questions, please inform us. If you have tips and tricks, your contributions are much appreciated.

どんなBlenderに関連する質問もお気軽に訊いて下されば喜んで手助けします。
あなたの質問はFAQに載るかもしれません。
より経験のあるBlenderユーザーの方、より良い回答があればおしらせください。
もしヒントやコツをお持ちの場合には、あなたの寄稿を歓迎します。


   .. Please bookmark this page for future reference as content will be added often. [Ctrl/Cmd D]

度々内容が追加されるであろう将来のリファレンスとしてこのページをブックマーク( [Ctrl/Cmd D] )してください。


   .. Quick links: General Questions | Navigation, UI & View | Selection | Transformations | Modeling | Others | Pro Tips

**クイックリンク** : 
:ref:`一般的な質問 <GeneralQuestions>` |
:ref:`ナビゲーション、UIとビュー <NavigationUIView>` |
:ref:`選択 <Selection>` |
:ref:`変形 <Transformations>` |
:ref:`モデリング <Modeling>` |
:ref:`その他 <Others>` |
:ref:`プロのヒント <ProTips>`


.. _GeneralQuestions:

   .. General Questions
      =================

一般的な質問
================

   .. (Questions)
      ^^^^^^^^^^^

(質問)
^^^^^^^^

   .. Is Blender free?
      -----------------

Blenderはフリーですか?
------------------------------

   .. Yes. You (individuals, organizations, companies) are guaranteed the freedoms to use, study, share (copy), and modify Blender.

はい、あなた(個人、組織、企業)は自由に使用する、学習する、共有する(配布する)、Blenderを改造することが保証されています。

   .. Do I need to install Blender to use?
      ------------------------------------

Blenderを使用するためにインストールが必要ですか?
------------------------------------------------------------


   .. | Yes and No.
      | Yes, if you are using the installer.
      | No, if you are using archive version, which is portable. Great for USB sticks.

はい、そしていいえ。
インストーラーをしようするのであれば、はい。
アーカイブバージョン(これはポータブルです)を使用するのであれば、いいえ。USBメモリ(での使用に)最適です。


   .. Where can I download Blender?
      -----------------------------

どこでBlenderをダウンロードできますか?
---------------------------------------------------------------


   .. Please go to http://blender.org/download/

http://blender.org/download/ へどうぞ。

   .. How to keep many Blender settings independent of each other if I have many Blender versions?
       -----------------------------------------------------------------------------------------------------

たくさんのBlenderバージョンがある場合にBlenderの設定を個別に保つにはどうすればいいですか？
-----------------------------------------------------------------------------------------------------------------

   .. Please create a folder named “config” inside the folder “2.7x”. That will make each Blender version have unique settings.

"config"という名前のフォルダを(Blenderフォルダの下の)"2.7x"フォルダ直下に作成します。
各Blenderバージョンの固有な設定を持つようになります。

   .. How to get Blend file thumbnail to display in Windows?
      -------------------------------------------------------

WindowsでBlendファイルのサムネイルを表示するにはどうすればいいですか?
--------------------------------------------------------------------------------------

   .. Create a shortcut, and add “-R” as argument, run Blender with that command once. Remove the argument if you want to reuse the shortcut to run Blender.

"-R"オプションをつけたショートカットを作成し、そのコマンドでBlenderを実行します。
オプションを取り除くことでそのショートカットを再利用できます。


   .. I want to change Blender’s theme color, how to do that?
      --------------------------------------------------------

Blenderのテーマ色を変更したいのですが、どうすれば?
-------------------------------------------------------------------

   .. Please find the answer at https://studiollb.wordpress.com/download/

https://studiollb.wordpress.com/download/ で答えを見つけてください。



   .. Getting Started with Blender
      ============================

Blenderをはじめる
=======================

.. _NavigationUIView:

   .. Navigation, UI & View
      ^^^^^^^^^^^^^^^^^^^^^

ナビゲーション、UIとビュー
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


   .. I come from another 3D software, can I have Max/Maya navigation in Blender?
      ---------------------------------------------------------------------------

他のソフトからきたのですが、BlenderでMaxやMayaのナビゲーションができますか?
------------------------------------------------------------------------------------------------

   .. Yes, currently we have Max and Maya navigation. To change to any of those navigation settings, on the splash, change Interaction to either Max or Maya. To have that same setting on new start-up, go to File > Save Startup File.

はい、現在MaxとMayaのナビゲーションがあります。ナビゲーション設定をそれらのいずれかに変更するには、
スプラッシュ画面でインタラクションをMaxかMayaにします。
次回起動時に同じ設定にするには File > Save Startup Fileを選択します。


   .. If I want to stick to Blender’s default navigation, how do I learn it?
      -----------------------------------------------------------------------

Blenderのデフォルトナビゲーションの場合、どうやって習得すればいいですか?
-------------------------------------------------------------------------------

   .. Blender navigation behaves like SketchUp. All navigation directly linked to the middle mouse button (MMB).

Blenderのナビゲーション動作はSketchUpのようです。全てのナビゲーションはマウス中ボタンに直接関連付けられています。

      .. | Zoom (scroll wheel)
         | Pan (Shift MMB)
         | Orbit (MMB)

* ズーム(スクロールホイール) 
* パン(Shift MMB)
* Orbit回転(MMB)


   .. There are more ways to navigate Blender’s viewport. Please view this post
      https://studiollb.wordpress.com/2013/10/20/blenders-3d-view-navigation/

Benderのビューポートのナビゲーションはもっと方法があります。この投稿を見てください。 
https://studiollb.wordpress.com/2013/10/20/blenders-3d-view-navigation/

   .. What is the logic behind the different 3D axis in Blender?
      ----------------------------------------------------------

Blenderの3D座標軸について理解するには?
------------------------------------------------


   .. Imagine you are looking at piece of graph paper on a table. You plot Y axis away from you, X axis to the right. So the remaining axis, Z axis is UP.

テーブル上のグラフが描かれた紙を想像してください。
あなたは向こう側へY軸を、右へX軸を描きます。そして残りは上へX軸、です。


   .. How to switch to a particular view quickly?
      -------------------------------------------

特別なビューを素早く切り替えるには?
----------------------------------------------


   .. You will need the **numpad** to do this.

これを行うには、**テンキー** が必要です。

   .. View from global axis:

* グローバル軸のビュー:

      .. | Front (Numpad 1)
         | Right (Numpad 3)
         | Top (Numpad 7)

   * フロントビュー(テンキー1)
   * ライトビュー(テンキー3)
   * トップビュー(テンキー7)


      .. | Back (Ctrl Numpad 1)
         | Left (Ctrl Numpad 3)
         | Bottom (Ctrl Numpad 7)

   * バックビュー(Ctrl+テンキー1)
   * レフトビュー(Ctrl+テンキー3)
   * ボトムビュー(Ctrl+テンキー7)

   .. View from object local axis:

* ローカル軸のビュー:

      .. | Local Front (Shift Numpad 1)
         | Local Right (Shift Numpad 3)
         | Local Top (Shift Numpad 7)

   * ローカルフロントビュー(Shift+テンキー1)
   * ローカルライトビュー(Shift+テンキー3)
   * ローカルトップビュー(Shift+テンキー7)

      .. | Local Back (Ctrl Shift Numpad 1)
         | Local Left (Ctrl Shift Numpad 3)
         | Local Bottom (Ctrl Shift Numpad 7)

   * ローカルバックビュー(Shift+Ctrl+テンキー1)
   * ローカルレフトビュー(Shift+Ctrl+テンキー3)
   * ローカルボトムビュー(Shift+Ctrl+テンキー7)


   .. | Toggle Perspective/Orthographic (Numpad 5)
      | Rotate view by 15 degrees increment (Numpad 2/4/6/8)

* 透視/平行 の切り替え(テンキー5)
* 15度ずつの回転(テンキー2/4/6/8)

   .. Camera view (Numpad 0)

* カメラビュー(テンキー0)

   .. How to get quad view like in other 3D DCC software?
      ----------------------------------------------------

どうすれば他の3DCG制作ソフトのようにクアッドビューに出来ますか?
----------------------------------------------------------------------

   .. クアッドビューに切り替え (Ctrl Alt Q)

Toggle quad view (Ctrl+Alt+Q)

   .. .. note::
         Ctrl Q will close Blender, please be careful.

.. note::
   Ctrl+Q はBlenderの終了なので、注意してください。

   .. I saw in video tutorials that the sidebars pop in and out of view, how they did that?
      --------------------------------------------------------------------------------------

ビデオチュートリアルでビューの外からサイドバーが現れたのを見たのですが、どのようにして出したのでしょうか?
--------------------------------------------------------------------------------------------------------------

   .. There are 2 sidebars, Tools and Properties. They can be toggled into view by pressing T and N respectively.

ツールシェルフとプロパティシェルフの2つのサイドバーがあります。
それぞれTキーとNキーを押すことビューに表示/非表示を切り替えることができます。


   .. What are these tiny squares on the viewport header?
      ---------------------------------------------------

ビューポートのヘッダにある小さな正方形は何でしょうか?
-----------------------------------------------------------------------

   .. They are layers.

レイヤーです。

   .. | Layer 1 to 10 are Top left to Top right.
      | Layer 11 to 20 are bottom left to bottom right.

| 上段の左から右がレイヤー1から10です。
| 下段の左から右がレイヤー11から20です。

   .. To move object(s) to another layer, select the object(s), press M, a menu will pop-up, select the layer the object(s) should go then move your cursor away, and you are done.


他のレイヤーにオブジェクトを移すには、オブジェクトを選択し、
Mキーを押すと現れるポップアップでレイヤーを選択し、マウスカーソルを他の場所に移動させて、実行します。

   .. .. note::
         Move to layer only available in Object mode.

.. note::
   "Move to layer"はオブジェクトモードのみ使用可能です。

   .. I changed my view in the viewport and I can’t see my objects anymore, how do I recover them?
      -----------------------------------------------------------------------------------------------

ビューでビューポートの変更を行ったらオブジェクトが見えなくなりました。見えるようにするには?
------------------------------------------------------------------------------------------------

   .. Case 1: You may have moved your view the wrong direction.

ケース1: 間違った方向に動かした。


      .. Press Shift C or the Home key to view all objects

   全てのオブジェクトを見えるように、Shift+CキーまたはHomeキーを押します。

   .. Case 2. You have moved your objects to another layer or you are viewing the wrong layer.

ケース2: 間違ったレイヤーに移してしまった、または間違ったレイヤーを見ている。

      .. Press ~ to turn on all layers, the 20 boxes of the viewport header are those layers.

   "~"キーを押して(訳者注:日本語キーでは"@"、環境により不可な場合あり)、
   またはヘッダから20個の箱を全て有効にして全てのレイヤーを表示します。

   .. How the windowing system work in Blender?
      ------------------------------------------

レイアウト変更の仕組みはどのように動いていますか?
----------------------------------------------------


   .. Before answering that, we need to clarify few things.

回答する前に幾つかの事柄を明確にする必要があります。

   .. 1. Blender is a software of “softwares,” meaning each window in Blender is a program.
   .. 2. Blender UI is divided into many layouts based on tasks. (see info header for list of screen layouts)

1. Blenderはソフトウェアの"ソフトウェア"、すなわちそれぞれのBlenderのウィンドウが1つのプログラムです。
2. BlenderのUIは使用目的別にたくさんのレイアウトに分かれています。
   (Infoウィンドウのヘッダにあるスクローンレイアウトのリストで確認できます)

(訳者注: Blenderでは、他のソフトウェアで言うところの「ペイン」を「ウィンドウ」と呼びます。)

   .. | To **resize window** , drag the window border
      | To **split window** , go to the top right corner and LMB drag to the window itself
      | To **merge Window** , go to the top right corner and LMB drag to another window
      | To **change window type** , go to window header, click the 1st icon and you’ll be presented with a list of window types
      | To **create new window** , go to top right corner and Shift + LMB drag a new window

* ウィンドウの大きさを変更するには、｀ウィンドウ境界をドラッグします。
* ウィンドウを分割するには、ウィンドウ右上を自領域に左ボタンドラッグします。
* ウィンドウを結合するには、ウィンドウ右上を他ウィンドウに左ボタンドラッグします。
* ウィンドウタイプを変更するには、ウィンドウのヘッダの(左から見て)最初のアイコンをクリックし、表示されるリストから選択します。
* 新しいウィンドウを作成するには、ウィンドウ右上をShift+左ボタンドラッグします。

   .. Merge and split can also be done with RMB at window border, area options menu will pop up.

ウィンドウの結合と分割はウィンドウ境界で右クリックして表示されるエリアオプションメニューからも変更できます。

.. _Selection:

   .. Selection
      ^^^^^^^^^

選択
^^^^^^


   .. When I left click on Blender viewport to select stuff, I only move the “target” thing, what is that?
      --------------------------------------------------------------------------------------------------------

ビューポートで選択するために左クリックしたのですが、"ターゲット"のみ移動しました。これは何ですか？
------------------------------------------------------------------------------------------------------------------------

   .. The target thing is the 3D cursor. It is used as pivot point for transformation [scale/rotation] and the location in 3D space to spawn 3D objects.

"ターゲット"は3Dカーソルです。拡大縮小、回転のピボットポイントとして、3Dオブジェクトの追加時の基点として使用されます。

   .. How do I select stuff in Blender?
      ------------------------------------

Blenderで選択するには?
--------------------------

   .. In the menus, Left Click is select. In the 3D viewport Right Click is select and Left Click positions the 3D cursor.

メニューでは左クリック、3Dビューポートでは右クリックで選択、左クリックで3Dカーソルの位置を変えます。


   .. Why Blender selects with right click in the viewport?
      -----------------------------------------------------

何故Blenderではビューポートで右クリック選択なのですか？
-------------------------------------------------------------

   .. Most Blender tools are modal. Meaning when executed, they have their own “world”. There are 3 steps when you make a change.

ほとんどのBlenderツールはモーダル動作です。これは(各コマンドが)実行されると、自身の”ワールド”を持つことを意味します。
3つのステップで変更します。

   .. 1. selecting & activating the tool [Right click for selection then tool command]
      2. make the changes
      3. confirm [Left Click] or cancel [Right Click] the change.

1. 選択、ツールの作動(右クリックまたは選択ツールで選択した後にコマンド実行)
2. 変更実施
3. 左クリックで確定、または右クリックで変更のキャンセル。


   .. What is the benefit with right click select?
      ---------------------------------------------

右クリック選択の利点は何ですか?
-------------------------------------------


   .. Right click to select objects in 3D view differentiates between confirming a command, which is left click. So mistake of selecting and confirming a change can be set to minimal. Extremely useful when you do more advance tasks like weight painting (skinning), and motion tracking.

3Dビューで右クリックを選択として区別しているのは確定コマンドの左クリックと区別するためです。
それは選択することと確定することについてのミスを最小限にします。
ウェイトペイントやモーショントラッキングといった高度なタスクを行う場合には特に役立ちます。


   .. How to select everything in the viewport?
      -----------------------------------------

全てを選択するには?
---------------------

   .. Press ‘A’ to select all, press ‘A’ again to deselect everything.

全てを選択するには'A'キーを押します。全てを非選択にするには'A'キーをもう一度押します。

   .. How do I invert my selection?
      -----------------------------

選択状態を反転するには?
---------------------------

   .. Ctrl I will invert your selection.

Ctrl+Iキーを押すと選択状態が反転します。

.. _Transformations:

   .. Transformations
      ^^^^^^^^^^^^^^^

変形
^^^^^^

   .. What are the shortcut keys to transformation in Blender?
      ---------------------------------------------------------

Blenderにおける変形のショートカットキーは?
--------------------------------------------------

      .. | Translation (move) [G for grab]
      .. | Scale [S]
      .. | Rotate [R]
      .. | Orbit Rotation [R R]

| 移動 [G for grab]
| 拡大縮小 [S]
| 回転 [R]
| トラックボール回転 [R R]


   .. .. note::
         Press LMB or Enter to confirm change, RMB or ESC to Cancel change

.. note::
   左クリックまたはEnterキーで変更の確定、右クリックまたはESCキーで変更のキャンセル

   .. What are the type of transformation pivot types?
      -------------------------------------------------

ピボットの種類による変形には何がありますか?
-----------------------------------------------

   .. Pivot point is location in 3D space where transformation is reference to.

ピボットポイントは3D空間で変形時に参照する位置です。

   .. There are 5 types of pivot point. They can be found on the 3D view header.

ピボットポイントには5つのタイプがあり、3Dビューのヘッダにあります。

      .. | Median Point (the average location in XYZ space of selection) [default]
         | Active Element (the average location in XYZ space of active selection)
         | Individual Origins (origin of each selected element based on selection type)
         | 3D cursor [period] (base on the location of 3D cursor)
         | Bounding Box [comma] (base on the center of the bounding box)

* メディアンポイント (選択された平均の平均値を元に) [default]
* アクティブエレメント (アクティブな要素を元に)
* インディビデュアルオリジン (選択したそれぞれの基準点を元に)
* 3Dカーソル [Period] (ローカル座標を元に)
* バウンディングボックス [comma](バウンディングボックスを元に)

   .. 3D cursor pivot is best used with Snapping menu (Shift S)

3Dカーソルピボットはスナッピングメニューを使うと良いです。(Shift S)

.. _Modeling:

   .. Modeling
      ^^^^^^^^^

モデリング
^^^^^^^^^^^^^^

   .. Before I start modeling, what should I know?
      --------------------------------------------

モデリングを始める前に知っておくべきことは何ですか?
---------------------------------------------------------------

   .. There are modes in the 3D viewport. By default you are in Object mode (all changes are done per object in this mode). Modes are like tasks. For modeling you need to change to Edit Mode.

3Dビューポートにはモードがあります。デフォルトではオブジェクトモードです(全ての変更が終了した状態です)。
モードはタスクに似ています。モデリングをするときはエディットモードに変更する必要があります。

   .. All tools can be found in the 4 menus on the header. There are many items, but you only need to know 4 shortcut keys to the 4 most important menus. They are:

全てのツールはヘッダにある4つのメニューにあります。たくさんの選択肢がありますが、
重要な4つのメニューに対応ショートカットキーを覚えておくだけです。それらは:

   .. 1. Vertex Menu (Ctrl V)
      2. Edge Menu (Ctrl E)
      3. Face (polygon) Menu (Ctrl F)
      4. Special Menu ( W )

1. 頂点メニュー (Ctrl+V)
2. 辺メニュー (Ctrl+E)
3. 面(ポリゴン)メニュー (Ctrl+F)
4. スペシャルメニュー (W)

   .. Other important menus:

その他の重要なメニューは:

      .. | Add object menu (Shift A) [works in Object & Edit Modes],
         | Snap Menu (Shift S) for 3D cursor and selected object(s) snapping

* オブジェクト追加 (Shift+A) [オブジェクトモードとエディットモードで動きます]
* スナップメニュー (Shift+S) - 3Dカーソルと選択したオブジェクトをスナップします

   .. 3 more selection tools

3つの選択ツール:

      .. | Circle select (C): LMB to select more, MMB to remove selection, RMB to cancel
         | Box Select (B)
         | Lasso Select (Ctrl and hold left mouse button)

* 円形選択 (C): 左ボタンで追加選択、中ボタンで選択解除、右ボタンでキャンセル
* 矩形選択 (B) 
* 投げ縄選択 (Ctrl+左ボタンドラッグ)

   .. After you executed a command/tool, you can adjust it again at the lower left sidebar in the viewport. If the sidebar is hidden, press F6 to temporary display the same menu. The menu is called “properties redo”.

コマンド・ツールを実行した後、ビューポートの左サイドバー下部分で再度調整が可能です。
サイドバーが隠れている場合にはF6キーを押して一時的に同じメニューを表示させることが可能です。
このメニューは"プロパティ リドゥ"と呼びます。

   .. What are the essential modeling tools to start modeling?
      ---------------------------------------------------------

モデリングをし始めるときの基礎的なモデリングツールには何がありますか？
------------------------------------------------------------------------


   .. | Extrude (E),
      | Loop Cut (Ctrl R),
      | Delete (X or Delete),
      | Knife (K),
      | Bevel (Ctrl B),
      | Split (Y),
      | Edge/vert slide (G G)
      | Inset (I)

* 押し出し (E),
* ループカット (Ctrl R),
* 削除 (X or Delete),
* ナイフ (K),
* ベベル (Ctrl B),
* スプリット (Y),
* 辺/頂点スライド (G G)
* インセット (I)

   .. Most tools have extra modifiers, they are displayed on the header.

ほとんどのツールは追加のモディファイアを持ち、ヘッダに表示されます。

   .. .. note::
         Press LMB or Enter to confirm change, RMB or ESC to Cancel change

.. note::
   左クリックまたはEnterキーで変更の確定、右クリックまたはESCキーで変更のキャンセル

   .. How to select edge loops, edge ring, face loop?
      ------------------------------------------------

エッジループ、エッジリング、フェイスループを選択するには?
--------------------------------------------------------------

   .. In edge selection mode:

辺選択モードで:

      .. | Edge loop (Alt Right Click)
         | Edge Ring (Ctrl Alt Right Click)

* エッジループ選択 (Alt+右クリック)
* エッジリング選択 (Ctrl+右クリック)

   .. In face selection mode:

面選択モードで:

      .. | Face loop (Alt Right Click)

* フェイスループ選択 (Alt+右クリック)


   .. How do I grow or shrink a selection in Edit mode?
      --------------------------------------------------

エディットモードでの選択を一回り大きく、または小さくするには?
-------------------------------------------------------------

   .. | Grow Selection (Ctrl Numpad +)
      | Shrink Selection (Ctrl Numpad -)

* 選択を一回り大きく (Ctrl+テンキー+)
* 選択を一回り小さく (Ctrl+テンキー-)

   .. Can I model with modifiers like in Max?
      ----------------------------------------

Maxのようにモディファイアーを使ってモデルを作成できますか？
--------------------------------------------------------------------

   .. Yes you can. Object modifiers are in Properties Window > Modifiers tab (blue wrench)

はい、出来ます。オブジェクトモディファイアは プロパティウィンドウのモディファイアタブにあります。(青いレンチのアイコン)

.. _Others:

   .. Others
      ^^^^^^

その他
^^^^^^^^

   .. The properties window is so big and has so many items, how to make sense of it?
      ---------------------------------------------------------------------------------

プロパティウィンドウが大きくてたくさんのアイテムがありますが、これをわかるようにするには?
------------------------------------------------------------------------------------------

   .. Scene and object settings are located in the properties window. It is arranged by the order of importance. The first 4 buttons (Render, Render Layer, Scene, World) are general settings. The buttons after those are object specific, meaning the settings will change depending on the object you select. Each button (often referred as tab) has settings grouped under a category, making them easy to find.

シーンとオブジェクトの設定はプロパティウィンドウに配置されています。
重要な順に構成され、最初の4つ(レンダリング,レンダーレイヤー,シーン,ワールド)のボタンはグローバルな設定です。
以降のボタンは選択したオブジェクトに応じます。
それぞれのボタン(しばしばタブのように参照されます)は見つけやすいようにカテゴリによりグループ分けされた設定があります。

   .. When I press a shortcut key, sometimes it works and sometime it doesn’t, why is that?
      --------------------------------------------------------------------------------------

ショートカットキーを押した時、時々動いたり動かなかったりします。何故ですか？
--------------------------------------------------------------------------------------


   .. The position of your mouse cursor is important. If it is in the 3D view your shortcut key will execute the command there. If you want to change something on any window, please put your cursor on that window.

マウスカーソルの位置が重要です。3Dビューにある場合、ショートカットキーは実行されます。
いずれかのウィンドウで何かを変更したい場合には対象のウィンドウにマウスカーソルをポイントしてください。

   .. What bad habits I should avoid?
      --------------------------------

悪いクセを出さないためには?
-----------------------------

   .. Please refer to this post > https://studiollb.wordpress.com/2012/02/03/blender-bad-habits/

こちらの記事を参照　> https://studiollb.wordpress.com/2012/02/03/blender-bad-habits/

.. _ProTips:

   .. Working fast in Blender: Pro Tips
      =================================

Blenderで素早く: プロのヒント
======================================


   .. (Questions)
      ^^^^^^^^^^^

(質問)
^^^^^^^

   .. I saw someone hammering his keyboard modeling in Blender, how he did that?
      --------------------------------------------------------------------------

Blenderでモデリングしている人がキーボードを連打しているのを見ました。何をしているのですか?
-----------------------------------------------------------------------------------------------



   .. Transforms [translation (move/grab), scale, rotation] in Blender have modifier keys.

Blenderの変形(移動、拡大縮小、回転)はモディファイアキーを持っています。

      .. Transform in an axis: G/S/R > X/Y/Z > number > enter/LMB (to confirm)

   軸に対する変形: G/S/R > X/Y/Z > 数字 > Enter/左ボタン(確定)

         .. example: translate 2 unit up the Z axis, G>Z>2>LMB

      例: Z軸上方向に2単位移動は、G>Z>2>左ボタン

      .. Transform on a plane: G/S/R > Shift X/Y/Z > number > enter/LMB (to confirm)

   平面に対する変形: G/S/R > X/Y/Z > 数字 > Enter/左ボタン(確定)

         .. example: scale 2x at XY plane, S>Shift Z>2>LMB

      例: XY平面に2倍に拡大は、G>Shift+Z>2>左ボタン

      .. Transform in local axis: G/S/R > XX/YY/ZZ > number > enter/LMB (to confirm)

   ローカル軸に対する変形: G/S/R > XX/YY/ZZ > 数字 > Enter/左ボタン(確定)

         .. example: rotate 90 degrees in local y axis, R>YY>90>LMB

      例: ローカルY軸を中心に90度回転は、R>YY>90>左ボタン


   .. I have too many objects in my scene, I only want to model that 1 object, what should I do?
      ------------------------------------------------------------------------------------------

シーンにたくさんのモデルがあり、その中の1つのオブジェクトのみを編集したいのですが?
----------------------------------------------------------------------------------------

   .. Please select the object(s), then press “numpad /” to get into local view. That will isolate the selected object(s).

対象のオブジェクトを選択し、テンキー/ を押すとローカルビューになります。これは選択したオブジェクトのみを表示します。

   .. How to zoom in to a selection?
      -------------------------------

選択したものにズームするには?
-----------------------------------

   .. Zoom to selection (Numpad .)

選択したものにズーム(テンキー.)

   .. Can I do math in inputs?
      -------------------------

数式で入力できますか?
----------------------

   .. You can do simple to very advance math in any numerical input area.

数値入力エリアで高度な数式を入力できます。

   .. How do I repeat last action?
      -----------------------------

最後のアクションを繰り返すには?
----------------------------------

   .. Press Shift R to repeat last command.

Shift+R キーで最後のコマンドを繰り返します。

   .. How to add a subdivision modifier quickly?
      -------------------------------------------

サブディビジョンモディファイアを素早く設定するには?
----------------------------------------------------

   .. Press Ctrl 1 for 1 level of subdivision (poly count ^2), Ctrl 2 for 2 levels of subdivision (poly count ^3). The subdivision modifier will be added to the modifier stack.

Ctrl+1 キーを押してレベル1(ポリカウントは2乗)、Ctrl+2ではレベル2(ポリカウントは3乗)。
サブディビジョンモディファイアはモディファイアスタックに追加されます。


      .. .. caution::
            Using this method with numbers beyond 6 can cause major lag.

.. caution::
   この方法で6以上は明らかなラグを発生させます。
   

   .. I know a command name but don’t know where it is in the menu nor the shortcut keys to it. How to find it?
     ------------------------------------------------------------------------------------------------------------

コマンド名は覚えていても、メニューやショートカットキーがどこかわからない時には?
--------------------------------------------------------------------------------------

   .. You have to start a command/tool search. Press Spacebar > type the name or part of the name of the command/tool.

コマンド・ツール検索を使いましょう。スペースキー を押してコマンド・ツールの名前の一部をタイプしましょう。 

   .. How to hide object(s) and what are other ways to hide object(s)?
      ----------------------------------------------------------------

オブジェクトを隠す方法と他の方法は?
----------------------------------------------------------------

   .. | Hide (H)
      | Unhidden (Alt H)
      | Hide unselected (Shift H)

* 隠す (H)
* 隠したものを表示 (Alt+H)
* 選択されていないものを隠す (Shift+H)

   .. How to change to another screen layout quickly?
      -----------------------------------------------

別のスクリーンレイアウトに素早く変更するには?
----------------------------------------------------------------

   .. At the info header there is a header menu, but there are shortcut keys to cycle the screen layout quickly.

Info ヘッダーにあるヘッダメニューで、ショートカットキーでもスクリーンレイアウトを切り替えることができます。

   .. Cycle Screen Layout (Ctrl ←/→)

スクリーンレイアウトの変更(循環)  (Ctrl ←/→)

   .. How to maximize a window?
      ---------------------------

ウィンドウを最大化するには?
------------------------------

   .. You can toggle that with Ctrl ↑/↓

Ctrl+上カーソルキー、Ctrl+下カーソルキーで切り替えられます。

   .. How to create new screen layout?
      ---------------------------------

新しいスクリーンレイアウトを作成するには?
-----------------------------------------------

   .. If you have a specific task that need a custom screen layout, it is best to create a new screen layout.

カスタムスクリーンレイアウトが必要とされる具体的なタスクがある場合には新しいスクリーンレイアウトを作るのが良いです。

   .. 1. Go to info header, press + at screen layout to add new screen
      2. Rename the screen
      3. Split/merge and change window type
      4. Save layout [File > Save Startup File]

1. Info ヘッダーで、スクリーンレイアウトの[+]を押して新しいスクリーンを追加します。
2. スクリーン名を変更します。
3. 分割・統合とウィンドウタイプの変更を行います。
4. レイアウトを保存します[ File > Save Startup File]

   .. List of shortcuts to switch window type quickly

ウィンドウタイプを素早く切り替えるショートカットのリスト

   .. .. list-table::

      .. - * Shift F1
           * Link/Append from Library
         - * Shift F2
           * Logic Editor
         - * Shift F3
           * Node Editor
         - * Shift F4
           * Python Console
         - * Shift F5
           * 3D view
         - * Shift F6
           * Graph Editor
         - * Shift F7
           * Properties
         - * Shift F8
           * Video Sequence Editor
         - * Shift F9
           * Outliner
         - * Shift F10
           * UV/Image Editor
         - * Shift F11
           * Text Editor
         - * Shift F12
           * Dope Sheet

   .. list-table::

      - * Shift+F1
        * リンク・アペンド
      - * Shift+F2
        * ロジックエディタ
      - * Shift+F3
        * ノードエディタ
      - * Shift+F4
        * Pythonコンソール
      - * Shift+F5
        * 3Dビュー
      - * Shift+F6
        * グラフエディタ
      - * Shift+F7
        * プロパティ
      - * Shift+F8
        * ビデオシーケンスエディタ
      - * Shift+F9
        * アウトライナー
      - * Shift+F10
        * UV/画像エディタ
      - * Shift+F11
        * テキストエディタ
      - * Shift+F12
        * ドープシート


   .. Any way to align the camera to my current view?
      -----------------------------------------------

現在の視点をカメラビューに設定する方法はありますか?
----------------------------------------------------------------

   .. When you are at the sweet viewing angle, to align your camera to that view press **Ctrl Alt Numpad 0**

いいアングルのところで、**Ctrl+Alt+テンキー0** を押して現在のビューをカメラに割り当てます。

   .. The selection type buttons (vert, edge, face) are small, any other way to access them?
      --------------------------------------------------------------------------------------

選択タイプ(頂点、辺、面)のボタンが小さくて選択しにくいです。他に良い方法は?
----------------------------------------------------------------------------------------------------

   .. Yes, in edit mode, press Ctrl Tab to get mesh selection mode menu.

はい、エディットモードで Ctrl+Tab キーを押すとメッシュ選択メニューが出ます。


   .. Any fast way to align transform without pressing any keyboard shortcut?
      ------------------------------------------------------------------------

ショートカットキーを押すことなしに軸方向への変形は可能ですか?
-----------------------------------------------------------------------------

   .. Press Middle Mouse Button after any transform (G/S/R) will constraint transform to world axis.

いずれかの変形(G/S/R)の後に中ボタンを押すとワールド座標に沿った変形をします。

   .. .. | Example: Translate locked on any axis (G > MMB)
         | Example: Rotate locked on any axis (R > MMB)
         | Example: Scale locked on any axis (S > MMB)

* 例: 軸に沿っての移動(G > 中ボタン)
* 例: 軸に沿っての回転(R > 中ボタン)
* 例: 軸に沿っての拡大縮小(S > 中ボタン)

   .. .. note::
         Press LMB or Enter to confirm change, RMB or ESC to Cancel change

.. note::
   左クリックまたはEnterキーで変更の確定、右クリックまたはESCキーで変更のキャンセル


   .. I want to zoom in/out camera fast, how to do that?
      ---------------------------------------------------

ズームイン・アウトを素早く行うには?
----------------------------------------

   .. With the camera view and selected (right click > numpad 0), press G then hold MMB, move cursor Up to Zoom In, move cursor Down to Zoom Out.

カメラビューでカメラを選択状態(右クリック > テンキー0)から、G キーを押して中ボタンドラッグ、
カーソルを上方に動かしてスームアップ、カーソルを下に動かしてズームアウト

      .. or

  もしくは

   .. With the camera view and selected (right click > numpad 0), press **G > Z Z** , move cursor Up to Zoom In, move cursor Down to Zoom Out.

カメラビューでカメラを選択状態(右クリック > テンキー0)から、**G > Z Z** の順に押して、
カーソルを上方に動かしてスームアップ、カーソルを下に動かしてズームアウト

   .. .. note::
         Press LMB or Enter to confirm change, RMB or ESC to Cancel change

.. note::
   左クリックまたはEnterキーで変更の確定、右クリックまたはESCキーで変更のキャンセル

   .. Any way to control view/camera like FPS game?
      ----------------------------------------------

FPSゲームのようにカメラやビューを操作する方法は?
------------------------------------------------------

   .. Press **Shift F** to activate FPS camera, after that you have the options to move

**Shift+F** キーを押してFPSカメラを有効にし、以下のオプションで移動します。


      .. | Forward ( W )
         | Left (A)
         | Backward (S)
         | Right (D)

* 前 (W)
* 左 (A)
* 後ろ (S)
* 右 (D)

      .. | Rise (E)
         | Lower (Q)

* 上昇 (E)
* 下降 (Q)

      .. | Shift (Fast movement), Faster Movement (scroll up)
         | Alt (Slow movement), Slower Movement (scroll down)

* Shift(素早く動く)、より早く動く(scroll up)
* Alt(遅く動く)、より遅く動く(scroll down)

      .. | Teleport (MMB)
         | Jump (V) [when gravity is on]

* テレポート(中ボタン)
* ジャンプ(V) [重力がonのとき]

         .. | Left Click, new view is current view
            | Right Click, revert back to initial view

   * 左クリックで新しいビューにします
   * 右クリックでビューを元にもどします

      .. When Shift F in Camera View

カメラビューでShift Fを押した時

         .. | Left Click, set camera to current view
            | Right Click, revert back to initial view

   * 左クリックで新しいビューにします
   * 右クリックでビューを元にもどします

   .. .. note::
         You can change Shift F behavior to Fly mode in User Preference > Input > View Navigation.

.. note::
   Shift F のフライモード時の動作は User Preference > Input > View Navigation から変更できます。

   .. Where is the render button?
      ---------------------------

どこにレンダーボタンはありますか?
------------------------------------------------

   .. Render button is in the properties window > render tab. It is also available on the render menu on info window (top bar).

レンダー ボタンはプロパティウィンドウのレンダータブにあります。Infoウィンドウのレンダーメニューにもあります(画面上部のバー)

      .. | Render Image (F12)
         | Render Animation (Ctrl F12)

* レンダリング (F12)
* アニメーションレンダリング (Ctrl+F12)


      .. | Show/Hide render view (F11)
         | Play Rendered Animation (Ctrl F11)

* レンダービュー表示/非表示 (F11)
* レンダリングしたアニメーションを再生 (Ctrl+F11)

-----

   .. .. note::

         .. | **Disclaimer:** This FAQ is work in progress, new updates will be added from time to time.
            | **Contributors:** Light BWK & Lee Posey, we are the co-founders of BlenderNPR. Mclelun, Reaction59 & Greg Zaal (via BlenderNation).

.. note::
   | **免責事項:** このFAQは製作中で、随時更新の予定です。
   | **貢献者:** Light BWK と Lee Posey、 私たちは BlenderNPRのファウンダーです。 Mclelun、 Reaction59 と Greg Zaal (BlenderNationから).



[EOF]





