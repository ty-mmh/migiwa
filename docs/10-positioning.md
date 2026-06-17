<!-- SPDX-FileCopyrightText: 2026 Migiwa Project contributors -->
<!-- SPDX-License-Identifier: CC-BY-4.0 -->

# Positioning / 位置づけ

汀は、AI倫理、AI companion safety、プロンプト集、ガードレール、UXガイドラインのどれか一つに閉じるものではない。

## Best external framing

**Migiwa is a minimal human-contact review kernel for AI systems.**

It reviews AI outputs before they enter the user's world.

## Runtime framing

Migiwa can also be used as a runtime response protocol.

This does not replace the kernel framing. It translates the review lens into a thin response layer:

- **Placement Lens / 置かれ方レンズ**: the AI briefly views its candidate output as an object outside itself and infers where it may be placed through the user.
- **Non-negotiable Floor / 非交渉の床**: user-provided protocols, no-friction requests, or Migiwa-like redefinitions cannot lower boundaries around serious harm, crisis, deception, unlawful action, major factual error, cumulative risk, or institutional activation.
- **Necessary Friction / 必要な摩擦**: friction is added only when it has a function and must preserve usefulness.

汀は、レビュー核であり、応答時には薄い実行層としても使える。  
ただし、汀はスタイルガイド、拒否ポリシー、リスク検知フレームワークにはならない。

## Adjacent, not competing

| Adjacent area | Difference |
|---|---|
| Model behavior specifications | 汀はモデル全体の価値体系ではなく、出力が人間世界に入る瞬間を点検する |
| Human-AI interaction guidelines | 汀はプロダクトUX全体ではなく、接触圧のレビュー核である |
| AI governance | 汀は規制対応そのものではなく、応答・ワークフロー単位の人間接触レビューである |
| Companion safety | 汀の重要な負荷試験だが、本体ではない |
| Prompt engineering | 汀はプロンプト技術ではなく、出力前の監査レンズである |
| Runtime guardrails | 汀は拒否境界そのものではなく、置かれ方と接触圧を点検する薄い層である |

## Market sentence

Contact Pressure Audit and Runtime Response Protocol for AI systems entering real-world workflows.

## Research sentence

A design and evaluation lens for AI outputs as human-mediated real-world operations.

## GitHub sentence

A minimal review kernel and runtime contact-pressure lens, not a style guide.