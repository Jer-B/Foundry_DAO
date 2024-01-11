<!-- @format -->
# English README　[Jump to Japanese Version](#japanese)
# Foundry DAO Governance

1. Contract controlled at 100% by a DAO 
2. Every proposal has to be voted
3. ERC20Token Has governance Token (Default model, bad system due to the fact that price speculation is difficult to distach for people owning the token)



## **Should research and create new Voting System Power**
*Please note: ERC20 based voting is not always recommended, and I encourage you to explore other forms of governance like reputation based or "skin-in-the-game" based.*



## Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - You'll know you did it right if you can run `git --version` and you see a response like `git version x.x.x`
- [foundry](https://getfoundry.sh/)
  - You'll know you did it right if you can run `forge --version` and you see a response like `forge 0.2.0 (816e00b 2023-03-16T00:05:26.396218Z)`


## Quickstart

```
git clone https://github.com/Jer-B/Foundry_DAO
cd Foundry_DAO
forge install
forge build
```

## Test

```
forge test
```
## Deploy

No deploy script, made for local test. 

## Estimate gas

You can estimate how much gas things cost by running:

```
forge snapshot
```

And you'll see and output file called `.gas-snapshot`


# Formatting


To run code formatting:
```
forge fmt
```


<a name="japanese"></a>
# 日本語版のREADME
# Foundry DAO ガバナンス


1. DAOに100％制御されるコントラクト
2. すべての提案は投票を行う必要があります
3. ERC20トークンにガバナンストークンがあります（デフォルトモデル、トークン所有者にとって価格の推測が難しいため、不良システムです）



## **新しい投票システムの力を研究および創造する必要があります**
*注意：ERC20ベースの投票は常に推奨されるものではなく、評判に基づくまたは「ゲームに参加する」ベースの他のガバナンス形式を探求することをお勧めします。*



## 必要条件

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - git --version を実行して git version x.x.x のような応答が表示されれば成功です。
- [foundry](https://getfoundry.sh/)
  - forge --version を実行して forge 0.2.0 (816e00b 2023-03-16T00:05:26.396218Z) のような応答が表示されれば成功です


## Quickstart

```
git clone https://github.com/Jer-B/Foundry_DAO
cd Foundry_DAO
forge install
forge build
```

## テスト方法

1. ユニットテスト
2. 統合テスト
3. フォークテスト
4. ステージングテスト

```
forge test
```

### Test Coverage

```
forge coverage
```

## デプロイスクリプト

デプロイスクリプトはなく、ローカルテスト用に作成されました。

## ガス代確認


```
forge snapshot
```

`.gas-snapshot` という名前の出力ファイルが表示されます


# フォーマット


コードのフォーマットを実行するには：
```
forge fmt
```


