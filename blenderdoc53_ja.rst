============================================
Blender Documentation Project
============================================

Blenderのドキュメントプロジェクト。

* マニュアルページ: https://www.blender.org/manual/

原文コピー
==============

:原文URL: https://developer.blender.org/project/view/53/


Blender Documentation ( `live preview <https://www.blender.org/manual/>`_ )
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Welcome to the new Blender User Documentation project. We are actively searching for
contributors and documentation module owners. This project aims at replacing and
updating the current Blender Manual, currently available in wiki format.

We have migrated the content over to reST format, so that the manual can be built
with Sphinx. A good amount of work is still required to complete the migration
(learn more about the open tasks in Phabricator).

If you want to start contributing or want to have a look at the new manual,
here we have some instructions.

How to build the docs locally
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* Clone the git repository git clone git://git.blender.org/blender-manual.git
* Move to the location where the repo was cloned
* Run pip install -r requirements.txt (Windows user make sure you are using Python 2.7, not 3.x)
* Build a section of the manual (for example make render)
* Launch the contents_quicky.html inside of the html folder and browse the freshly build render docs

`Installation guide for MS-Windows <https://developer.blender.org/diffusion/BM/browse/master/install_windows.rst>`_

How to edit
^^^^^^^^^^^^

* Use your favourite text editor to do changes to the text
* Run make render again to preview your changes
* Commit your changes
* Make a patch with the changes and send it to https://developer.blender.org/differential/diff/create/
* Drop a line to bf-docboard@blender.org to mention your patch and feel free to ask any question!

Advanced configuration
^^^^^^^^^^^^^^^^^^^^^^^

TODO: details on how to set up a virtual env. Also, check out the makefile.

Links
^^^^^^

| Source Code: `Blender Repository <https://developer.blender.org/diffusion/BM/>`_
| Mailing List: `bf-docboard <http://lists.blender.org/mailman/listinfo/bf-docboard>`_
| Module Owners: TODO


環境設定メモ(OS X Yosemite)
================================

ローカル環境でドキュメントをビルドするための環境を作成した際のメモ。OS X Yosemite 10.10 の、
XCode等入っていない環境にて。


インストールされているPythonバージョンの確認
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

   :: 
   
      $ python -V
      Python 2.7.6


「コマンドライン・デベロッパ・ツール」のインストール
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

ターミナルから git コマンドを実行した時

   "git"コマンドを実行するには、コマンドライン・デベロッパ・ツールが必要です。
   ツールを今すぐインストールしますか?

というダイアログメッセージが表示された場合には「インストール」を選びコマンドライン・デベロッパ・ツールをインストールします。

* XCodeは要らない(?)
* git別途インストールはしない。


* 参考: `Mac初心者がGitをインストールしてみた <http://free-free-wheeling.com/mac-git-install-beginner/>`_


ルートユーザーの作成
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

スーパーユーザーでの実行が必要になるため、ルートユーザーを有効にします。

* Mac OS X で「ルート」ユーザを有効にして使用する

   * http://support.apple.com/kb/ht1528?viewlocale=ja_JP



pipインストール
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

https://pip.pypa.io/en/latest/installing.html

pipインストール時には ルートユーザーになっておく必要があります(sudoに続けてコマンド、でも可)。

  ::
     
      $ su
      Password:
      sh-3.2# python get-pip.py


gitリポジトリからのクローン
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

リポジトリをローカルにダウンロードします。

   ::
   
      $ git clone git://git.blender.org/blender-manual.git

必要なソフトウェアをインストール
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

リポジトリのフォルダに移動して、requirements.txt のパッケージをインストールします。
ルートユーザーになっておく必要があります(sudoに続けてコマンド、でも可)。

   ::

      $ su
      Password:
      sh-3.2# pip install -r requirements.txt 


HTMLのビルド
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

make all します。

ブラウザで _build/index/contents_quicky.html を開いて確認します。

[EOF]
