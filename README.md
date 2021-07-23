# android-kotlin-SideNavigation

#Navigation Viewを使ってサイドメニューを実装する。
　サイドメニューは横からのスワイプ、またはアプリバーの三本線を押すと出てきます。
このコードでは、HomeFragment\SecondFragment\ThirdFragmentを実装しこれらの切り替えにサイドメニューを用いています。

１．手順

　１．Fragment作る。
　
　２．nav_graph.xmlを作る。

　３．menu.xml（Navigation Viewの中に表示する項目を追加。）。

　４．Navigation Viewにmenu.xmlを追加。

　５．MainActivity.ktのコーディング。
　　（Navigation ViewとNavHostFragmentのNavControllerを結びつける　→　サイドバーをにゅっと出すときのコードを実装）
  
