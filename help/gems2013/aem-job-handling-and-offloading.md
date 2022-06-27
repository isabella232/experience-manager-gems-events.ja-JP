---
title: AEM 5.6.1 でのジョブ処理とオフロードの概要です。
description: 高度なジョブ処理機能の技術的な紹介を受けます。 ジョブ処理は、レプリケーションやワークフロー処理などの機能の基盤となるインフラストラクチャです。 ジョブ処理 API の改善と新機能に加えて、検出モジュールについて説明します。
uuid: 181e3781-8eca-4a5d-879e-15ae4e1f6649
discoiquuid: ee4cd526-7363-4b8e-ad26-c2c937b70327
targetaudience: target-audience advanced
exl-id: 9fa2f9a8-86de-4791-ac40-6406e0336e08
source-git-commit: 19832f1904681d68c102ddbdc8925cebf5dffcb2
workflow-type: tm+mt
source-wordcount: '207'
ht-degree: 6%

---

# AEM 5.6.1 でのジョブ処理とオフロードの概要です。 {#introduction-of-job-handling-and-offloading-in-aem}

ジョブ処理は、レプリケーションやワークフロー処理などの機能の基盤となるインフラストラクチャです。 これは、高度なジョブ処理機能の技術的な紹介です。 新しい検出モジュールと、改善されたジョブ処理 API および新機能について説明します。 オフロードフレームワークは、ジョブの処理と検出の上に構築され、非クラスターインスタンス間でのジョブの配布に重点を置いています。 オフロードが分散ジョブ処理をどのように拡張するかを詳しく見ていきます。 次に、現在のワークフローのオフロードの実装での使用方法と、独自のプロジェクトでの使用方法を見てみましょう。

>[!VIDEO](https://video.tv.adobe.com/v/19580/?quality=9)

*2013 年 7 月 24 日配信*

**提示者：**

Adobe、シニアデベロッパー、Carsten Ziegeler 氏

Marc Pfaff、リード開発者、Adobe

発表者のスライド — 第 1 部

[ファイルを入手](assets/jobhandling.pdf)

発表者のスライド — 第 2 部

[ファイルを入手](assets/offloading.pdf)

## 関連リンク {#related-links}

* [Apache Sling Eventing and Jobhandling](http://sling.apache.org/documentation/bundles/apache-sling-eventing-and-job-handling.html)
* [Discovery API とその実装](http://sling.apache.org/documentation/bundles/discovery-api-and-impl.html)
* [ジョブのオフロード](http://docs.adobe.com/docs/en/cq/current/deploying/offloading.html)
