# Audit Reports

This repo aggregates all audits performed on Sablier smart contracts by third-party security researchers.

> [!WARNING]  
> Audits are not a guarantee of correctness. Some parts of the codebase may have been modified after they were audited.

## Airdrops Protocol

Previously, these contracts were part of `v2-periphery`. You can find audit reports for previous releases under the
[Lockup Protocol](#lockup-protocol) section.

### v1.3.0

[0b83314]: https://github.com/sablier-labs/airdrops/tree/0b83314f77cc1c4f5c8725c9cc121c9e77fcc94e

| Auditors | Types | Commits              | Reports                                              |                                                                                                                                                      |
| :------- | :---- | :------------------- | :--------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Cantina  | Firm  | [`0b83314`][0b83314] | [2025-01-12](./airdrops/v1.0.0/20250112_cantina.pdf) | [![image](https://files.sablier.com/external/badges/cantina-airdrops-1-3-0.svg)](https://cantina.xyz/portfolio/11615402-c0bc-4170-bf3d-595af10f2ce1) |

## Flow Protocol

### v1.1.0

[32ac99c]: https://github.com/sablier-labs/flow/tree/32ac99c89393009166ca05e9a4e75ac34a442139

| Auditors | Types | Commits              | Reports                                          |                                                                                                                                                  |
| :------- | :---- | :------------------- | :----------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Cantina  | Firm  | [`32ac99c`][32ac99c] | [2025-01-12](./flow/v1.1.0/20250112_cantina.pdf) | [![image](https://files.sablier.com/external/badges/cantina-flow-1-1-0.svg)](https://cantina.xyz/portfolio/1daf2e81-62a6-4e53-91d4-135c1a6347b0) |

### v1.0.0

[5dc175c]: https://github.com/sablier-labs/flow/tree/5dc175cca189ba0401b1e877a62e5ca13a85384b
[8348fe5]: https://github.com/sablier-labs/flow/tree/8348fe510fddbe681a1ea055ec65f08c310a0e1c

| Auditors  | Types   | Commits              | Reports                                          |
| :-------- | :------ | :------------------- | :----------------------------------------------- |
| Cantina   | Firm    | [`5dc175c`][5dc175c] | [2024-10-20](./flow/v1.0.0/20241020_cantina.pdf) |
| CodeHawks | Contest | [`8348fe5`][8348fe5] | [2024-11-13](./flow/v1.0.0/20241113_codehawk.md) |

## Lockup Protocol

### v2.0.0

[076eba9]: https://github.com/sablier-labs/lockup/tree/076eba971fea7bb38fe75ee5108f0589c26152c0

| Auditors | Types | Commits              | Reports                                            |                                                                                                                                                    |
| :------- | :---- | :------------------- | :------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Cantina  | Firm  | [`076eba9`][076eba9] | [2025-01-12](./lockup/v2.0.0/20250112_cantina.pdf) | [![image](https://files.sablier.com/external/badges/cantina-lockup-2-0-0.svg)](https://cantina.xyz/portfolio/606ae33c-c3e6-473f-8dee-dcfa0bf9bffe) |

### v1.2.0

[36b49d3]: https://github.com/sablier-labs/lockup/tree/36b49d3bf2a396d19083d28247e8e03d7a3a2ee1
[9d7a15b]: https://github.com/sablier-labs/v2-periphery/tree/9d7a15b0128d549cbac7e33ab2593cfdbf229fc7
[abf7154]: https://github.com/sablier-labs/lockup/tree/abf7154d5371ab957b86fce9a8a4801499573d63
[f9defae]: https://github.com/sablier-labs/v2-periphery/tree/f9defaeb185360d09abba3f7e2f748d993063296
[c85c66a]: https://github.com/sablier-labs/lockup/tree/c85c66ac0a3f3f287ba10a5c267c1ce67d1b6aeb
[eb2983d]: https://github.com/sablier-labs/v2-periphery/tree/eb2983ddddf05d86f5f4483b23541b3e655f32e6
[a86edee]: https://github.com/sablier-labs/lockup/tree/a86edeeecb57a2ba2e6fb5a4a4049e62f0b8f2a6
[73831c7]: https://github.com/sablier-labs/v2-periphery/tree/73831c7dcaa5ec4e2fed6caa0f8040154e53030a

| Auditors      | Types   | Commits                                    | Reports                                            |
| :------------ | :------ | :----------------------------------------- | :------------------------------------------------- |
| Cantina       | Firm    | [`36b49d3`][36b49d3], [`9d7a15b`][9d7a15b] | [2024-07-03](./lockup/v1.2.0/20240703_cantina.pdf) |
| Egis Security | Firm    | [`abf7154`][abf7154], [`f9defae`][f9defae] | [2024-06-28](./lockup/v1.2.0/20240628_egis.pdf)    |
| CodeHawks     | Contest | [`c85c66a`][c85c66a], [`eb2983d`][eb2983d] | [2024-06-15](./lockup/v1.2.0/20240615_codehawk.md) |
| Cantina       | Firm    | [`a86edee`][a86edee], [`73831c7`][73831c7] | [2024-06-13](./lockup/v1.2.0/20240613_cantina.pdf) |

### v1.1.x

[e5a227f]: https://github.com/sablier-labs/lockup/tree/e5a227f77ededaf4d2737b36ed958445ad86eee9
[0004fd2]: https://github.com/sablier-labs/v2-periphery/tree/0004fd2e61e032df3d895045ec414ecb212ddcc8
[07014ac]: https://github.com/sablier-labs/lockup/tree/07014ac
[cc9434f]: https://github.com/sablier-labs/v2-periphery/tree/cc9434f
[79d88ca]: https://github.com/sablier-labs/v2-periphery/tree/79d88ca

| Auditors          | Types | Commits                                    | Reports                                            |
| :---------------- | :---- | :----------------------------------------- | :------------------------------------------------- |
| Cantina           | Firm  | [`e5a227f`][e5a227f], [`0004fd2`][0004fd2] | [2023-12-21](./lockup/v1.1.x/20231221_cantina.pdf) |
| Cantina           | Firm  | [`07014ac`][07014ac], [`cc9434f`][cc9434f] | [2023-12-15](./lockup/v1.1.x/20231215_cantina.pdf) |
| Turing Consulting | Firm  | [`e5a227f`][e5a227f], [`0004fd2`][0004fd2] | [2023-11-30](./lockup/v1.1.x/20231130_turing.pdf)  |
| Cantina           | Firm  | [`79d88ca`][79d88ca]                       | [2023-09-06](./lockup/v1.1.x/20230906_cantina.pdf) |

### v1.0.x

[5997ac0]: https://github.com/sablier-labs/lockup/tree/5997ac05751960259c03aa166158d5db8aea1675
[005df5f]: https://github.com/sablier-labs/v2-periphery/tree/005df5f0452fb2dc4c19a613b9b572982849a35b
[8bd57eb]: https://github.com/sablier-labs/lockup/tree/8bd57ebb31fddf6ef262477e5a378027db8b85d8

| Auditors       | Types | Commits                                    | Reports                                                                                                         |
| :------------- | :---- | :----------------------------------------- | :-------------------------------------------------------------------------------------------------------------- |
| Iaroslav Mazur | Solo  | [`5997ac0`][5997ac0], [`005df5f`][005df5f] | [2023-06-13](./lockup/v1.0.x/20230613_iaro_core.pdf), [2023-07-09](./lockup/v1.0.x/20230709_iaro_periphery.pdf) |
| Cantina        | Firm  | [`8bd57eb`][8bd57eb]                       | [2023-06-08](./lockup/v1.0.x/20230608_cantina.pdf)                                                              |
| Rahul Saxena   | Solo  | [`8bd57eb`][8bd57eb]                       | [2023-04-24](./lockup/v1.0.x/20230424_rahul.pdf)                                                                |
| Iaroslav Mazur | Solo  | [`8bd57eb`][8bd57eb]                       | [2023-04-04](./lockup/v1.0.x/20230404_iaro.pdf)                                                                 |
| HYDN           | Firm  | [`8bd57eb`][8bd57eb]                       | [2023-04-03](./lockup/v1.0.x/20230403_hydn.pdf)                                                                 |
| Hake           | Solo  | [`8bd57eb`][8bd57eb]                       | [2023-03-31](./lockup/v1.0.x/20230331_hake.pdf)                                                                 |

### Legacy

[fc54b02]: https://github.com/sablier-labs/v1-protocol/tree/fc54b0233e186232f6d724fa89d1cf7c1f45c688

| Auditors   | Types | Commits              | Reports                                        |
| :--------- | :---- | :------------------- | :--------------------------------------------- |
| Quantstamp | Firm  | [`fc54b02`][fc54b02] | [2019-11-25](./legacy/20191125_quantstamp.pdf) |

## Code Praise

What the community says about Sablier's code base:

1. Zach Obront on [testing methodology](https://x.com/zachobront/status/1668998130392616966) and on
   [test quality](https://x.com/zachobront/status/1680629892742782977).
1. Georgios Konstantopoulos on [Foundry best practices](https://x.com/gakonst/status/1681792186281521162) employed by
   Sablier.
1. Patrick Collins on the [categorization of tests](https://x.com/PatrickAlphaC/status/1715064363105587309).
1. Pop Punk on [implementation](https://x.com/PopPunkOnChain/status/1681858703463424000).
1. Alan on [code review](https://x.com/ltsCuzzo/status/1681959372698841094).
1. Anton Cheng on [focus on details](https://x.com/antonttc/status/1680046043701088258).
1. r4bbit recommends Solidity devs to [study Sablier](https://x.com/0x_r4bbit/status/1681769698784862208).
1. Shafu on the [use of BTT](https://x.com/shafu0x/status/1683976749309100033).
1. Solidity devs on [code clarity and structure](https://x.com/PaulRBerg/status/1732327663312797700).
