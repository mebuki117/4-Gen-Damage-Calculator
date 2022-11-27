ポケモン 4世代（HGSS / DPt）用のダメージ計算機です。Windowsで動作します。

## 特徴・機能
- 多分高性能なダメージ計算機
   - 同時に最大5つの技まで計算
   - 技などを入力するだけで自動的に計算
   - 計算結果をクリックで詳細な計算結果を表示
   - 攻防交代機能を搭載
   - 左右に入力されたポケモンの情報を表示
   - バトルフロンティアに特化したモード
      - 現在はステージのみ。詳細は使い方の項目を参照
- めざめるパワーチェッカー
   - 個体値からタイプと威力を計算
      - 実数値から個体値を計算し、可能性のあるタイプと威力の一覧を表示することも可能

## 今後実装を予定しているもの
~~いずれもいつ実装かは未定。~~ **バトルステージに対応完了し一段落した為現在更新停止中です。**
- バトルフロンティア（ファクトリー）に特化したモード
- ~~個体情報の保存~~

## 使い方
### ダウンロードから起動まで
1. [リリース](https://github.com/oyamelon/4-Gen-Damage-Calculator/releases)から、``4GenDamageCalculator.zip``をダウンロードします。バージョンは任意で選択してください
2. お使いのWindowsに``.NET Framework 4.8``のランタイムがインストールされていない場合は、[ここ](https://dotnet.microsoft.com/ja-jp/download/dotnet-framework/net48)からランタイムをダウンロード及び、インストールしてください
3. ダウンロードしたzipファイルを解凍し、``4世代ダメージ計算機.exe``を起動します（起動時、Windowsによって保護される可能性があります）

### 起動して計算を行う
1. ポケモンや技などを入力すると自動的に計算が行われます
2. 計算結果をクリックすると、別ウインドウで詳細な計算結果を表示します

#### ステージ特化モードについて（v0.3.3以降）
- オンにすると、ステージ用のパネルが表示されます。また、右側のポケモン情報を相手（CPU）とし、技情報などを表示します
- 自動入力がオンの際、相手の技などを自動入力します
- 相手のレベル、個体値の計算も可能です。計算結果も自動入力に対応しています
   - タイプ数は、現在挑戦しているタイプを含めた、挑戦済みのタイプの数
   - ランクは、現在挑戦しているタイプのランク
   
#### めざパチェッカー
- 個体値を入力するか、実数値などを入力して計算します
   - 実数値などから計算した例はスクリーンショットをご覧ください

## スクリーンショット
![20221024015059](https://user-images.githubusercontent.com/97399080/197405002-5cb6091f-5bc9-4e3e-873f-66f8d28d2ea6.png)  
![20221024015107](https://user-images.githubusercontent.com/97399080/197405090-e72adf51-db10-4793-bf2f-5f0b5baab8f9.png)  
![20221024015313](https://user-images.githubusercontent.com/97399080/197406628-c59ee14b-0cd3-4e94-8e4e-097c4ee34f6e.png)
![4gdc hidden power sample](https://user-images.githubusercontent.com/97399080/180484210-b8fd989a-e2d7-408b-b305-8738f320f43b.png)

###### 注意：スクリーンショットは旧バージョンの場合があります  

## 連絡
バグ報告などご連絡がある場合は、[製作者のTwitter](https://twitter.com/oyamelon)にお願いいたします。

## クレジット
以下のサイトのものを参考及び、使用させていただいています。
- [The Complete Damage Formula for Diamond & Pearl](https://www.smogon.com/dp/articles/damage_formula)
- [ポケモンWiki](https://wiki.xn--rckteqa2e.com/wiki/%E3%83%A1%E3%82%A4%E3%83%B3%E3%83%9A%E3%83%BC%E3%82%B8)
- [ポケモンの友](https://pokebook.jp/)
- [BulbaGarden - Bulbapedia](https://bulbapedia.bulbagarden.net/wiki/Main_Page)
- [VS SV (旧名：VS SWSH)](https://www.project1997.com/vs/index.html)（UIを参考）

---

##### 本ツールはファンメイドであり、株式会社ポケモン及び、それに関連する企業とは一切関係ありません。
###### Pokemon: ©Pokemon ©Nintendo/Creatures/GAME FREAK
