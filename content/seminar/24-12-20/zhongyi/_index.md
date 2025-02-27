---
title: "AnimateDead: Debloating Web Applications Using Concolic Execution"
date: 2024-12-20
---


**Presenter**: {{% mention "Zhongyi Wang" %}}

**Authors**: Babak Amin Azad, Stony Brook University; Rasoul Jahanshahi, Boston University; Chris Tsoukaladelis, Stony Brook University; Manuel Egele, Boston University; Nick Nikiforakis, Stony Brook University

**Abstract**: Year over year, modern web applications evolve to cater to the needs of many users and support various runtime environments. The ever-growing need to appeal to as many users as possible and the reliance on third-party dependencies comes at the price of code-bloat. Previous research has highlighted the benefits of debloating mechanisms which produce smaller applications, customized to the real needs of their users with significant security improvements.

Recognizing the limitations of dynamic and static debloating schemes (including high runtime overhead and lack of accuracy), we propose a hybrid approach based on concolic execution. We developed AnimateDead, a PHP emulator capable of concolic execution and designed a distributed analysis framework around it.

By using the readily available web server logs as application entry points, we perform concolic reachability analysis and extract the code-coverage of target web applications in an abstract environment, which allows our results to generalize for all user inputs and database states. We demonstrate that debloating via concolic execution improves the security of web applications by shrinking the size of their code by an average of 47% and reducing critical API calls by 55%, while removing 35-65% of vulnerabilities for historic CVEs. We show that via concolic execution, we can debloat web applications with comparable security improvements of dynamic debloating schemes without suffering from the runtime overhead, and the need for a training phase. Moreover, AnimateDead-debloated web applications reduce the likelihood of breakage by allowing users to perform all actions reachable from the analyzed entry points.

**URL**: https://www.usenix.org/conference/usenixsecurity23/presentation/azad

