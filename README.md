# Papilio Pro 開発環境構築 for Windows

Windows 11 環境で Papilio Pro FPGA モジュールの開発環境を構築するための手順とカスタマイズ方法をまとめたリポジトリです。

## 概要

このリポジトリは、Xilinxの公式ドキュメント [UG1227 "ISE 14.7 VM for Windows 10 & 11 User Guide"](https://docs.xilinx.com/v/u/en-US/ug1227-ise-vm-windows10) をベースにしています。公式ドキュメントだけでは分かりにくい点や、追加で必要となる設定について補足説明を提供し、Papilio Proを使った開発をよりスムーズに始められるようにすることを目的としています。

## このリポジトリが解決すること

Papilio Proは古のFPGAボードであるため、最新のWindows環境で開発環境を整えるには少し工夫が必要です。XilinxはISE Design Suite 14.7を仮想マシン(VM)で動作させる方法を公式に提供していますが、それに加えて少しの作業をすることで快適になります。

-   日本語キーボードに対応
-   Host OS (Windows 11) とのcopy & pasteが正しくできるようupdate

このリポジトリでは、これらのための具体的な手順やTipsを提供します。


## 前提条件

-    Windows 11 がインストールされたPC
-   Papilio Pro FPGA モジュール
-   [Oracle VM VirtualBox](https://www.virtualbox.org/) がインストール済みであること

## 環境構築手順

### Step 1: ISE 14.7 VMのセットアップ

はじめに、Xilinxの公式ドキュメント [UG1227](https://docs.xilinx.com/v/u/en-US/ug1227-ise-vm-windows10) に従って、ISE 14.7 VMのダウンロードと基本的なセットアップを完了させてください。大まかな流れは下記です。

- Oracle VirtualBox をインストール
- ISE 14.7 VMをダウンロード (AMD account登録が必要) して展開
- xsetup.exe を実行

(セットアップ途中でやるべき設定を確認してここに記す予定)

### Step 2: カスタマイズ

快適にするための工夫

*(ここに、VMのネットワーク設定、USBデバイスの認識方法、共有フォルダの設定など、UG1227だけでは分かりにくいポイントを具体的に記述します。スクリーンショットを `images` フォルダに入れて貼り付ける予定。)*

-   **日本語keyboard対応
    -   ...
-   **copy & paste修正
    -   Guest Additionsで、Guest OS...
-   **共有フォルダの設定
    -   ...



### Step 3: 他

- constraint
- papilio loader
