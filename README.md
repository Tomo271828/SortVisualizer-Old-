# 実装の仕様について

要素数に2以上512以下の整数、ソート名に実行したいソートの名前、数列の生成パターンに0以上8以下の整数を入力し、その状態で「設定を変更する」をクリックすることで数列を生成可能。

この状態で「ソートする！」をクリックすることでソートを実行できる。

また、「Stop」をクリックすることでソートを一時停止、「Step」をクリックすることで1ステップ分のみ実行、「Start」をクリックすることでソートを再開できる。

ソート名には以下のものに対応している。なお、まったく同じ名前で入力する必要がある。
+ Simple Sort
+ Bubble Sort
+ Selection Sort
+ Insertion Sort
+ Shell Sort
+ Quick Sort
+ Heap Sort
+ Merge Sort
+ Bin Sort
+ Gnome Sort
+ Shaker Sort
+ Odd Even Sort
+ Pancake Sort
+ Bitonic Sort
+ Comb Sort
+ Bogo Sort
+ Bozo Sort
+ Stooge Sort
+ Sleep Sort
+ Slow Sort
+ Special

数列の生成パターンは以下のものに対応している。
+ 0 -> 昇順
+ 1 -> 降順
+ 2 -> 重複なしランダム
+ 3 -> ほぼ昇順
+ 4 -> ほぼ降順
+ 5 -> すべて同じ値
+ 6 -> 2つの値でランダム
+ 7 -> 重複ありランダム
+ 8 -> Input_Array.txtから読み取り　Input_Array.txtの1行目を空白区切り数列として認識
