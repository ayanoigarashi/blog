---
title: 条件付きアクセスの認証強度 一般提供開始のお知らせ
date: 2023-06-18 08:00
tags:
    - US Identity Blog
---

# 条件付きアクセスの認証強度 一般提供開始のお知らせ

こんにちは、Azure Identity サポート チームの 長谷川 です。

本記事は、2023 年 5 月 31 日に米国の Microsoft Entra (Azure AD) Blog で公開された [Conditional Access authentication strength is now Generally Available!](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/conditional-access-authentication-strength-is-now-generally/ba-p/3773134) を意訳したものになります。ご不明点等ございましたらサポート チームまでお問い合わせください。

--- 
 
こんにちは！ **条件付きアクセスの認証強度** の一般提供開始をお知らせできることを嬉しく思います。この強力な機能により、組織は特定のシナリオに適した認証方法の要件を選択できるようになり、より安全で先進的かつ強力な認証への移行がこれまで以上に容易になります。

条件付きアクセス認証強度を使用すると、管理者は、ユーザーのサインイン リスク レベルやアクセスするリソースの機密性などの要因に基づいて、アクセスに必要な認証強度の最低レベルを定義することができます。これは、規制の厳しい業界で活動する組織や、厳格なコンプライアンス要件を持つ組織にとって、特に有用です。例えば、 [アメリカ合衆国行政管理予算局 (OMB) の覚書 22-09](https://learn.microsoft.com/ja-jp/azure/active-directory/standards/memo-22-09-multi-factor-authentication) を遵守する必要がある米国政府機関などです。認証強度は、政府機関のお客様が従業員やベンダーに対してフィッシングに強い MFA を強制するのに役立ちます。

![図1: 認証強度 - フィッシングに強い MFA](./ca-authentication-strength-ga/Figure1.png)

組織は、自身のニーズとリスクに基づいて、あらかじめ定義された認証強度ポリシーから選択するか、独自のカスタム認証強度ポリシーを定義することができます。これらのポリシーは、テナント内のメンバーや、あらゆるマイクロソフト クラウドからの外部ユーザーに対して適用することができます。これにより、企業はベンダーやパートナーに対する認証要件の水準を引き上げることができます。

すでに多くの組織で、さまざまな方法で条件付きアクセス認証強度を使用しているのを目にします。例えば、以下のようなものです:

- ある政府機関では、認証強度を使用して、Azure Active Directory (Azure AD) によって保護されている任意のリソースに対する認証に証明書ベースの認証 (CBA) を強制する一方、従来のオンプレミス アプリケーションの利用に必要なパスワード リセットには他の認証方法を許可している。
- とある専門的なサービスを提供する企業では、認証強度を利用して、特権ユーザーに FIDO2 の利用を強制し、幅広いユーザー層に対して電話回線ベースの方式から徐々に移行している。
- 別のソフトウェア会社では、認証強度を利用して、所有する複数のテナントで認証方法の標準化を徹底している。

条件付きアクセスの認証強度の詳細はこちらをご確認ください: https://aka.ms/authstrengthdocs

この強力な機能をぜひお試しいただき、ご意見をお聞かせください！

よろしくお願いします。

Alex Weinert (twitter: @Alex_t_weinert)  
VP Director of Identity Security, Microsoft
