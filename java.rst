.. Tate documentation master file, created by
   sphinx-quickstart on Fri Nov  4 14:40:53 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

学んだこと
===================
Javaの基礎

- コンストラクタ
   - クラス名(){};で宣言。値の初期化に使ったりする。()に引数入れてもいい。
- super
   - 親クラスのメソッドやメンバ変数を使うときに
- void
   - 戻り値がないという宣言
- static
   - インスタンスにしなくても使えるようになる
- 抽象クラス abstruct
   - 中身のないメソッドおよびそれが1つでもあるクラスに使う
- SpringBootアノテーション
   - @SpringBootApplication　面倒な設定をしてくれる　プロジェクト名.javaファイルに記載してある
   - @controller 自動的にインスタンス化してくれる
   - @autowired 依存性の注入
   - @RequestMapping(“/url”) ドメイン以降のURL
   - @GetMapping(“/メソッド”)  
   - public String index(Model model){//モデルもインスタンス化される htmlファイルが返り値return (“test”) //test.htmlが呼び出される}
   - DIコンテナ　jdbcTemplateのようによく使われるであろうインスタンスは、初めから保管されてい
   - data.sql schema.sql spring起動時に起動される。
   - Modelクラス 　リクエストスコープを管理
   - リクエストスコープ　リクエスト毎に生成されるスコープ（データの保存領域）で、レスポンスが返されるまで利用可能です。
   - Thymeleaf　JSP → Thymeleafはjavaが動いていない場合はデフォルト値が出力されるが、JSPはタグを書き換えるので前者の方がよく使われる