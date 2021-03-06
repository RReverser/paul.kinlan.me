---
slug: challenges-for-web-developers
date: 2018-01-21T13:20:31+01:00
title: "Challenges for web developers"
description: "Summary of the challenges that I beleive we developers face every day."
---


もともと私は、私のチーム（ChromeとWeb Developer Relations）が対処しなければならない、より広範な開発者エコシステムの課題を明確にするためにこれを書いています。これにより、より多くの人々がウェブ上に構築し、開発者は、より多くの人々が使用したいという経験を積み重ねます。

[WebとChrome DevRelのマニフェスト](/ web-developer-relations-manifesto /)を共有した後、私たちが開発者が解決できるようにしたい課題のいくつかについて私の考えを共有するペースを維持したいと考えました。

私は実際にこの記事を送っていませんでしたが、今や私はしばらくしていました。そして、実際にこれを共有することが良い時期だと私は思っていました。

開発者が毎日直面している課題を理解することで、私たちができるだけ多くの開発者を支援するために働く方法を変える方法を理解するのに役立ちます。

あなたのご意見が大好きです。私が間違っている？私が見逃したより広範な生態系の問題がありますか？

これらの問題の多くから、より深い記事を作成します。

##ウェブ開発は始めるのは簡単ですが、進歩とマスターをするのは難しいです

*可変APIのサポートとベンダーの優先順位により、一貫性のある経験が困難または不可能になります。 *従来の考慮事項、たとえば古いCMS、既存の実装は、克服する必要がある大きな勢いがあることを意味します。 *プラットフォームの不具合と互換性の問題は、膨大な量の不満と不必要な量の余分なテストを引き起こします。 *開発者をプラットフォームの理解から遠ざける多くの抽象化が作成されています。 *アプリケーションのような相互作用のためのプラットフォームレベルのプリミティブの欠如：ビュー、モデル、コントローラ、リサイクラ、ヒーローの遷移、ビューの遷移* Web開発者は、オフライン、アクセシビリティ、ローカリゼーション、パフォーマンス、セキュリティなどあらゆる面で優れている必要があります。

##開発者はPWAについて興奮していますが、構築が難しく、うまくやるのが難しい場合があります

* PWAの主なブラウザサポートの欠如により、1つのビルドを正当化することが難しくなります。*最後まで、プログレッシブWebアプリケーションを構築するのは難しいです。 HTTPSでは、サービスワーカーはすべて始めるのが難しいです。 * PWAの価値は、特にOS（Safari、Desktopなど）を越えて明確にはっきりしていません。なぜなら、これを採用しない理由の簡単な理由です。 * "模範的なPWA"を構築することはほぼ不可能であり、誰も本当に気にすることはありません。 *開発者は頻繁に再開しなければならず、既存の経験を移行しないでください。 *開発者と企業は、なぜ彼らが進歩的なWebアプリケーションを構築すべきか分からない。 *既存のWebアプリケーションの検索可能性は大きな問題です。 *「プログレッシブ」は評価されません。一貫した体験を提供するのは難しい/異なるWebブラウザ/オペレーティングシステムから欠けている機能*構築中のプログレッシブウェブアプリケーションは応答性がないため、別のデスクトップサイト

##うまく機能する経験（UI / UX）を構築するのは難しいですが、

*開発者のための十分なバーはあまりにも低いです。何が良いですか？どうしてそれが重要ですか？どうやってそこに着きますか？ *コンポーネントを構築するときに悪い俳優になることは簡単です、A11Y、レイアウトとパフォーマンスは構築が難しく、開発者が優先順位を付けることはありません。*開発者は、Webコンポーネントやプラットフォームツールの価値を、開発者は、BootstrapのようなUIフレームワークでUIの苦労を取り除き、製品に集中できるようにしたいと考えています。メニュー、ナビゲーション、トランジション、テイクオーバー、データバインディング、ビュー、コントローラなど、多くの経験は構築するのが難しく、構築が難しい*パフォーマンスの高い構築が難しい - プリミティブは問題になります（開発者は、 APIがアニメーションのように不自然にサポートされているため、開発者が新しいプラットフォームプリミティブを採用することが不可能になります。プリミティブは通常、基本的であり、ポリフにはほとんど不可能ですil

##高速なサイトを構築するのは難しい

* Web開発者は、恐ろしいUXを持ち、アクセス不可能な低速な経験を積み重ねています。彼らはもっとうまくやりたいと思っていますが、開発者やビジネスはビジネスに及ぼす影響についての明確な指針がないため、パフォーマンスの優先順位付けをしません。*開発者はサイトが遅い理由を理解できません。速い読み込みサイトを構築するにはあまりにも難しい - 多くのフットガンと多くのブラウザがある*開発者は彼らが目指すべき目標が何であるか分からない*開発者は彼らに設定された目標に達するために必要なガイダンスを持っていない（PRPLパターン、ルートベースのチャンク、ストリーミングは現時点では懸念事項であり、具体的なドキュメントはありません）*デベロッパーツールとフレームワークはデフォルトでは高速ではなく、開発者は気づかず気にしません - DX＆gt; UX *開発者は、ユーザーが実行しているハードウェアをテストしていないため、 "十分に良い"と感じています。開発者は、ユーザーベースに関するすべての情報と、あなたのサイトUIをすべてのデバイスでスムーズに動作させることは難しい* Public perf shamingが増加しており、開発者は気にすることから解放されている*開発者は彼らを頭の上に置いているように感じるすべての時間、したがってオフにする

##安全なサイトを作るのは難しい

* HTTPsへの移行は、多くの新しいテクノロジーを採用することを妨げるものです。*開発者や企業は、サイトを安全にする必要性を感じません（なぜ、これはニュースサイトに必要なのですか？）。 HTTPSサイトを設定することは、開発者にとってはまだ高価なことがあります。誰もがLetsEncryptを使用できるわけではありません。特権のために大小のサイトがさらに多くの費用を払わなければならない*開発者はCSPなどの「安全な技術」の価値を理解しておらず、普及率が低い

##ビジネスと開発者はなぜ彼らが "Web"

*モバイルウェブ上でユーザーを変換するのは難しいので、お金を稼ぐのは難しい*ビジネスケースやニーズは地域、業種、聴衆によって異なるため、投資を増やすことなく意味のある方法で適用することは難しい*それはあなたがウェブを使用すべきではないと感じることです* Webは単にアプリケーションモデルに移っているだけなので、なぜアプリをやってみませんか？主要APIのためのクロスブラウザサポートの欠如は、企業が投資を正当化するのを困難にします*非常に多くの競合するプラットフォームがある場合、ウェブの価値をクリアする

##ウェブは塊状で、開発者に多くの苦痛を与えます

*ブラウザは、Webプラットフォームの追加や戦術的削除によって頻繁に変更され、何が起こっているのか、最新の状態や変更方法を知りません。これは開発者の苦痛を引き起こす* Chromeは常に「介入」でプラットフォームを壊しています*ブラウザ更新サイクルは不確実性と「砂のシフト」をもたらします*プラットフォームプレーヤーはすべて整列していません。 Safari、UC、Edgeと異なる優先順位を持つ*開発者はすべて（iOSからUCブラウザまで）どこでも仕事をしなければならず、彼らは意思決定をバックアップするためのツール、ガイダンスまたはデータを持っている

##ウェブは生き生きとした生態系ですが、騒々しい

*膨大な数の意見が毎日生成されており、正確でも網羅的でもないベストプラクティスが定義されており、開発者は統一ガイドを提示するためにGoogleや他のユーザーに目を向ける*ツール、ライブラリ、フレームワークが多数存在する開発者は何を選ぶかわからない* Googleには多数のフレームワークがあり、開発者は何を使うべきかわからない*多くのコンテンツを作成し、一様に表示されない*競合するツールや開発者の多くは彼らが使うべきものを知っている*多くの競合するフレームワークと開発者は、どちらを使うべきかわからない*競合するアドバイスや開発者の多くは、

##ウェブはグローバルです

*開発者は英語を話すだけではありません。開発者の多くは、決してターゲットにしていない国、中国、インド、インドネシア、タイ、パキスタンなどから来ています。我々はそれらを助ける必要がある*多くの西洋の開発者は '新興市場のみ'としての 'Lite'の経験の収穫を見ており、彼らは高忠実ではない

###更新編集1（20-Jan-2018）：ページの上部にメモを追加します。

編集2（28-Jan-2018）：いくつかのビットをクリーンアップします。
