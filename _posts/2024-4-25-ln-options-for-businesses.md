---
layout: post
title: Exploring Lightning Payment Options for Online Businesses
---

{{ page.title }}
================

<p class="meta">25 Apr 2024</p>

There is now an increasing number of online businesses that accept Lightning payments. 

On-chain Bitcoin transactions don't scale for small amounts, which makes it impractical for everyday business. Hence, the use of Lightning Network enables almost instantaneous payments for low fees.

There are a couple options to choose from depending on technical expertise and whether you want to incorporate LN functionality directly into your website's codebase or integrate with an e-commerce platform.  Based on your preferences and how you want to entrust your funds, determine whether you want to run your own LN node like [RaspiBlitz](https://github.com/raspiblitz/raspiblitz) and [Umbrel](https://umbrel.com/umbrelos) or using custodial LN wallets.

Payment Processors/Gateways

Payment processors specializing in Lightning payments, such as [BTCPay Server](https://btcpayserver.org/) and [OpenNode](https://opennode.com/), are popular because of streamlined solutions. Most processors not only have e-commerce platform plugins but also facilitate APIs and code libraries.

-   BTCPay Server: It comes with integrations into platforms like [Shopify](https://docs.btcpayserver.org/Shopify/), [WooCommerce](https://docs.btcpayserver.org/WooCommerce/), [Zapier](https://zapier.com/apps/btcpay-server/integrations), etc. It has several [features](https://docs.btcpayserver.org/Guide/#features) from self-hosted software (great for privacy & trust), no KYC to LN support for various implementations. You will need to run BTCPay on your own server or use a third-party host such as Google Cloud. For custom integration for your site, use [BTCPay API](https://docs.btcpayserver.org/CustomIntegration/), which offers client and server-side pairing methods. Setting up and configuring BTCPay Server may be technically challenging, making it slightly inconvenient.

-   OpenNode: Similar to BTCPay Server, it also has plugins to platforms like [BigCommerce](https://www.bigcommerce.com.au/apps/opennode-bitcoin-payments/), [Shopify](https://apps.shopify.com/opennode), and [OpenCart](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=35481&filter_member=opennode). But it provides a [hosted payment processing service](https://opennode.com/hosted-checkout/). Reliance on a third-party platform, however, can raise concerns in the long-term on security.

-   Strike: [Strike API](https://strike.me/learn/what-is-the-strike-api/) enables the sending and receiving of payments via Lightning Network, directing payments to specific users, making cash payouts to bank accounts, and using OAuth for third-party permissions. In terms of payment experience, limitations can arise in terms of customization and flexibility.

Development with WebLN

[WebLN](https://www.webln.guide/introduction/what-is-webln) is a JavaScript interface standard that bridges web applications and the Lightning Network, allowing for easy integration of Lightning functionality into web applications. There are also WebLN [providers](https://www.webln.guide/ressources/webln-providers), such as [Alby](https://getalby.com/), which provide their own API service ([Alby API](https://guides.getalby.com/developer-guide/v/alby-wallet-api)) to enable instant payments.

However, direct integration needs a reasonable amount of web development experience and if you don't want to or haven't built a web application from scratch for your business, this will not be the best option.

Conclusion

Lightning Network enables fast, low-cost transactions, improving payment experiences and reducing operational expenses for businesses. Whether you take a streamlined or more hands-on approach, online businesses can now easily use and accept Lightning payments.
