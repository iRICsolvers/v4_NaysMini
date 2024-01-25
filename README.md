# NaysMini
![anime_10](https://github.com/iRICsolvers/v4_NaysMini/assets/106499621/ed61fa0f-6f4c-4e4b-b5ca-52b5b290419f)

# Japanese 

<details>
  
## NaysMiniについて
NaysMiniはPythonコードで書かれたNays2dHの簡易版です。
直交座標の流れの計算のみ可能です。
Pythonコードが全て見れますので、数値計算法やPythonの勉強になります。

## 事例集
事例集はこちらを参照ください。
https://i-ric.org/yasu/NaysMini/index.html

  ## 必須追加モジュール
  * NaysMiniではnumbaを使用しています。iRICインストーラーからインストールしたMiniconda環境にnumbaを追加してください。
  ```
  conda activate iric
  conda install numba 
  ```
  
  ## minicondaでのproxy設定方法
  会社内などproxy経由で上記のモジュール追加ができない場合`C:\Users\[ユーザー名]\.condarc`に以下を追記
  
  ```
  proxy_servers:
  http: http://[プロキシアドレス]:[ポート番号]
  https: https://[プロキシアドレス]:[ポート番号] 
  ```
  
## リリースノート
### ver.1.0.24012501 update by hoshino
* 計算中の計算結果の読み込み機能に軽微な修正が行われました。
### ver.1.0.23052201 update by hamaki
* iRIC v4対応版をリリース
  
</details>

# English

<details>

## Overview of NaysMini
NaysMini is a simple version of Nays2dH written in Python code.
It can be applied only flow calculation in Cartesian coordinate system.

## Examples
Check here for case studies.
https://i-ric.org/yasu/NaysMini/index.html

   ## Required additional modules
   * NaysMini uses numba. Add numba to the Miniconda environment installed from the iRIC installer.
   ```
   conda activate iric
   conda install numba
   ```
  
   ## Proxy setting method with miniconda
   If the above module cannot be added via a proxy, such as within a company, add the following to `C:\Users\[user name]\.condarc`.
  
   ```
   proxy_servers:
   http: http://[proxy address]:[port number]
   https: https://[proxy address]:[port number]
   ```
  
## Release notes
### ver.1.0.24012501 update by hoshino
* Minor adjustments to the result loading function during calculations.
### ver.1.0.23052201 update by hamaki
* Released as iRIC v4 compatible version

</details>
