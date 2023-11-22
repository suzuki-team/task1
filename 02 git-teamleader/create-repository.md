# チーム開発で使うリポジトリの作成方法

## 概要
1. Organizationの作成とメンバーの招待
2. チーム開発用リポジトリの作り方
3. ブランチの作成方法(developブランチの作成)
4. デフォルトブランチの設定方法(developブランチをデフォルトブランチに設定する)

# (注記)以下、Recursionの資料をもとに作成しています。


## 1.　Organizationの作成とメンバーの招待
## Organizationの説明
Organizationとは、複数のリポジトリをさまざまなユーザーで管理、および共同作業するための機能です。

参考図
![](../img/repository-img1.png)

### 作成手順
### ①アイコンマークをクリック
![](../img/repository-img2.png)

### ②settingsをクリック
![](../img/repository-img3.png)

### ③Organizationsをクリック
![](../img/repository-img4.png)

### ④New oraganizationをクリック
![](../img/repository-img5.png)

### ⑤free planを選択
![](../img/repository-img6.png)

### ⑥oraganizationを作成
※名前は任意で決めることができます
![](../img/repository-img7.png)

### ⑦invite memberをクリックし、チームメンバーを検索、owner権限で招待する(メンバーの招待はいつでもできます)
![](../img/repository-img8.png)
![](../img/repository-img9.png)


## 2.　チーム開発用リポジトリの作り方
チームリーダーは、task1という課題用のリポジトリとwork-spaceという開発用のリポジトリ、これら２つのpublicリポジトリを作っていただきます。

完成図としてはこのようになります。
![](../img/repository-img10.png)

### リポジトリの作成方法

①new repositoryをクリック
![](../img/repository-img11.png)

②publicを選択
![](../img/repository-img12.png)

③２つ目のリポジトリからは画面右のnew repositoryをクリック
![](../img/repository-img13.png)


## 3.　ブランチの作成方法
### ①branchをクリック
![](../img/repository-img14.png)

### ②画面右、new branchをクリック
![](../img/repository-img15.png)

### ③ブランチ名はdevelopで作成（今回の開発では全リポジトリに以下の設定を適用してください）
![](../img/repository-img16.png)


## 4.　デフォルトブランチの設定方法（今回の開発では全リポジトリに以下の設定を適用してください）

### ①settingsをクリック後、branchesをクリック
![](../img/repository-img17.png)

### ②矢印マークをクリック後、ブランチをmainからdevelopに変更
![](../img/repository-img18.png)