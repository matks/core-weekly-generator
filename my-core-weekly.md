---
layout: post
title:  "PrestaShop Core Weekly - Week XXXX of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   XXXX
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday XX to Sunday XX of MONTH XXXX.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

[write a nice message here, or remove the "General messages" section]


## A quick update about PrestaShop's GitHub issues and pull requests:

- [61 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-07-06..2020-07-12) have been created in the project repositories;
- [64 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-07-06..2020-07-12), including [16 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-07-06..2020-07-12) on the core;
- [68 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-07-06..2020-07-12) in the project repositories;
- [66 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-07-06..2020-07-12), including [59 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-07-06..2020-07-12).
        


## Code changes in the 'develop' branch


### Core
* [#20092](https://github.com/PrestaShop/PrestaShop/pull/20092): Fix some phpdoc, by [@matks](https://github.com/matks)
* [#20017](https://github.com/PrestaShop/PrestaShop/pull/20017): Improve dynamic hooks comment. Thank you [@PululuK](https://github.com/PululuK)
* [#20006](https://github.com/PrestaShop/PrestaShop/pull/20006): Allow the + sign in the url path, by [@atomiix](https://github.com/atomiix)


### Back office
* [#20070](https://github.com/PrestaShop/PrestaShop/pull/20070): Fix incorrect redirect URL parameter when editing translations. Thank you [@Xesau](https://github.com/Xesau)
* [#20028](https://github.com/PrestaShop/PrestaShop/pull/20028): BO - Customers / Wrong redirection after creating a new address from the customer detail page. Thank you [@JoshHargreaves](https://github.com/JoshHargreaves)
* [#19951](https://github.com/PrestaShop/PrestaShop/pull/19951): Truncate category description in BO list view. Thank you [@ks129](https://github.com/ks129)
* [#19947](https://github.com/PrestaShop/PrestaShop/pull/19947): Fixed preview in Order Page, by [@Progi1984](https://github.com/Progi1984)
* [#19871](https://github.com/PrestaShop/PrestaShop/pull/19871): Add UpdateProductCategoriesCommand. Thank you [@zuk3975](https://github.com/zuk3975)
* [#19239](https://github.com/PrestaShop/PrestaShop/pull/19239): Always display "Related product" title. Thank you [@idnovate](https://github.com/idnovate)


### Front office
* [#20096](https://github.com/PrestaShop/PrestaShop/pull/20096): Show last visible order state in customer order history page, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#16439](https://github.com/PrestaShop/PrestaShop/pull/16439): Frontend Translation mixed up when switching languages. Thank you [@23b](https://github.com/23b)


### Installer
* [#19961](https://github.com/PrestaShop/PrestaShop/pull/19961): Install classic theme when possible, by [@Progi1984](https://github.com/Progi1984)
* [#19948](https://github.com/PrestaShop/PrestaShop/pull/19948): Check maximum PHP Version Support at installation, by [@Progi1984](https://github.com/Progi1984)


## Code changes in the '1.7.7.x' branch


### Back office
* [#20039](https://github.com/PrestaShop/PrestaShop/pull/20039): Make customization image downloadable in BO order page, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#19981](https://github.com/PrestaShop/PrestaShop/pull/19981): Refactor cancel product and bug fix, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#19970](https://github.com/PrestaShop/PrestaShop/pull/19970): Create specific price when product price is updated in order, by [@sowbiba](https://github.com/sowbiba)
* [#19937](https://github.com/PrestaShop/PrestaShop/pull/19937): Fixed position action button in Order Page, by [@Progi1984](https://github.com/Progi1984)
* [#19704](https://github.com/PrestaShop/PrestaShop/pull/19704): Migrate linked orders, by [@matks](https://github.com/matks)


### Installer
* [#20122](https://github.com/PrestaShop/PrestaShop/pull/20122): Fix session tables charset, by [@jolelievre](https://github.com/jolelievre)


### Tests
* [#20086](https://github.com/PrestaShop/PrestaShop/pull/20086): Functional tests - Test pagination of products table. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


### Merge
* [#20089](https://github.com/PrestaShop/PrestaShop/pull/20089): Merge 1.7.6.x into 1.7.7.x - 07/07/2020, by [@matks](https://github.com/matks)


## Code changes in the '1.7.6.x' branch


## Code changes in modules, themes & tools


### Changes in developer documentation
* [#629](https://github.com/PrestaShop/docs/pull/629): Include H4 in Table of contents, by [@eternoendless](https://github.com/eternoendless)
* [#625](https://github.com/PrestaShop/docs/pull/625): Update kpi-blocks.md. Thank you [@stijnstroeve](https://github.com/stijnstroeve)
* [#618](https://github.com/PrestaShop/docs/pull/618): Add animation to submenu opening and closing, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#617](https://github.com/PrestaShop/docs/pull/617): Fix broken link. Thank you [@zalexki](https://github.com/zalexki)
* [#615](https://github.com/PrestaShop/docs/pull/615): Add displayInvoiceLegalFreeText hook in pdf.md. Thank you [@Daaaaad](https://github.com/Daaaaad)
* [#608](https://github.com/PrestaShop/docs/pull/608): Add deprecated info to TranslateTextType. Thank you [@zalexki](https://github.com/zalexki)
* [#607](https://github.com/PrestaShop/docs/pull/607): Module scope compatibility, by [@matks](https://github.com/matks)
* [#594](https://github.com/PrestaShop/docs/pull/594): Add note about actionFrontControllerSetMedia hook after cache section. Thank you [@marekjedrzejewski](https://github.com/marekjedrzejewski)
* [#591](https://github.com/PrestaShop/docs/pull/591): Explain how to release module native, by [@matks](https://github.com/matks)
* [#504](https://github.com/PrestaShop/docs/pull/504): Add ajax parameter for ajax call. Thank you [@luigimassa](https://github.com/luigimassa)


### PHP Developer Tools
* [#31](https://github.com/PrestaShop/php-dev-tools/pull/31): Update header-stamp to v1.4, by [@matks](https://github.com/matks)
* [#30](https://github.com/PrestaShop/php-dev-tools/pull/30): Remove github formatter in favor of phpstan one, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Wishlist block
* [#50](https://github.com/PrestaShop/blockwishlist/pull/50): Add product attribute to query and missing fields, by [@Matt75](https://github.com/Matt75)
* [#47](https://github.com/PrestaShop/blockwishlist/pull/47): Fixnbproductinwishlist. Thank you [@pablopolyte](https://github.com/pablopolyte)
* [#46](https://github.com/PrestaShop/blockwishlist/pull/46): Stat upgrade. Thank you [@pablopolyte](https://github.com/pablopolyte)
* [#45](https://github.com/PrestaShop/blockwishlist/pull/45): Continue grid. Thank you [@zalexki](https://github.com/zalexki)
* [#43](https://github.com/PrestaShop/blockwishlist/pull/43): Add unit tests, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#42](https://github.com/PrestaShop/blockwishlist/pull/42): Search criteria. Thank you [@pablopolyte](https://github.com/pablopolyte)


### Customer reassurance block
* [#49](https://github.com/PrestaShop/blockreassurance/pull/49): Fix conflicts master, by [@Progi1984](https://github.com/Progi1984)
* [#47](https://github.com/PrestaShop/blockreassurance/pull/47): Bump version to 5.0.0 and Fixed .gitignore, by [@Progi1984](https://github.com/Progi1984)


### Dashboard Products
* [#26](https://github.com/PrestaShop/dashproducts/pull/26): Release 2.1.0, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#25](https://github.com/PrestaShop/dashproducts/pull/25): Bump version to 2.1.0, by [@PierreRambaud](https://github.com/PierreRambaud)


### Docker images
* [#225](https://github.com/PrestaShop/docker/pull/225): Release 1767, by [@atomiix](https://github.com/atomiix)


### Shopping cart module
* [#62](https://github.com/PrestaShop/ps_shoppingcart/pull/62): Use preprend-autoloader in composer.json, by [@matks](https://github.com/matks)
* [#59](https://github.com/PrestaShop/ps_shoppingcart/pull/59): Bug Fix change quantity in shopping cart. Thank you [@jeckyl](https://github.com/jeckyl)


### Link list
* [#99](https://github.com/PrestaShop/ps_linklist/pull/99): Update DEV dependencies, by [@matks](https://github.com/matks)
* [#91](https://github.com/PrestaShop/ps_linklist/pull/91): Release 3.2.0, by [@Progi1984](https://github.com/Progi1984)
* [#87](https://github.com/PrestaShop/ps_linklist/pull/87): Use the new feature from 177 for automatic tabs and Symfony route, by [@jolelievre](https://github.com/jolelievre)


### Google Sitemap module
* [#141](https://github.com/PrestaShop/gsitemap/pull/141): Add prepend-autoloader: false in composer.json, by [@matks](https://github.com/matks)


### Prestashop UI Kit
* [#96](https://github.com/PrestaShop/prestashop-ui-kit/pull/96): Add GitHub action for stylelint, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#95](https://github.com/PrestaShop/prestashop-ui-kit/pull/95): Bugfix of select2, error inputs, height of inputs, some adjustments.., by [@NeOMakinG](https://github.com/NeOMakinG)


### Main menu module
* [#35](https://github.com/PrestaShop/ps_mainmenu/pull/35): Release 2.2.0, by [@Progi1984](https://github.com/Progi1984)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@eternoendless](https://github.com/eternoendless), [@LouiseBonnard](https://github.com/LouiseBonnard), [@stijnstroeve](https://github.com/stijnstroeve), [@matks](https://github.com/matks), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@Matt75](https://github.com/Matt75), [@jolelievre](https://github.com/jolelievre), [@matthieu-rolland](https://github.com/matthieu-rolland), [@Progi1984](https://github.com/Progi1984), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@pablopolyte](https://github.com/pablopolyte), [@PierreRambaud](https://github.com/PierreRambaud), [@NeOMakinG](https://github.com/NeOMakinG), [@atomiix](https://github.com/atomiix), [@Xesau](https://github.com/Xesau), [@zalexki](https://github.com/zalexki), [@Daaaaad](https://github.com/Daaaaad), [@JoshHargreaves](https://github.com/JoshHargreaves), [@PululuK](https://github.com/PululuK), [@sowbiba](https://github.com/sowbiba), [@ks129](https://github.com/ks129), [@marekjedrzejewski](https://github.com/marekjedrzejewski), [@zuk3975](https://github.com/zuk3975), [@jeckyl](https://github.com/jeckyl), [@cdcvince](https://github.com/cdcvince), [@idnovate](https://github.com/idnovate), [@luigimassa](https://github.com/luigimassa), [@23b](https://github.com/23b)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

