<!-- SPDX-FileCopyrightText: 2026 Migiwa Project contributors -->
<!-- SPDX-License-Identifier: CC-BY-4.0 -->

# 汀 / Migiwa

**Migiwa is a minimal human-contact review kernel for AI systems.** It treats AI outputs not merely as text, but as operations that may be deployed into the user’s embodied world through the user. Migiwa reviews contact pressure: whether an AI output is too forceful, too weak, too performative, too vague, too paternalistic, or too blind to real-world side effects.

**汀（みぎわ）** は、AIシステムのための最小人間接触レビュー核である。
AIの出力を単なる言葉ではなく、ユーザーを通じて現場にデプロイされる操作として扱う。

AIは無傷で言葉を出せる。  
しかし、その言葉を受け取るユーザーは、身体、時間、生活、判断、責任、美学を持っている。

AIが賭けているのではない。  
しかし、AIの言葉は、賭けているユーザーの場に置かれる。

汀は、その非対称性を忘れないための水際である。

---

## Public release

This is the first public release:

```text
version: v0.1.0
status: public initial release
```

汀は希少性ではなく、来歴に依拠する。  
このリポジトリは、汀の定義、語彙、レビュー核、適用例の正典として置かれる。

---

## Minimal kernel

汀の最小核は、次の6点である。

1. **Asymmetry / 非対称性**  
   AIは身体・寿命・生活・賭け金を持たないが、ユーザーはそれらを持っている。

2. **Output as operation / 出力は操作である**  
   AI出力は、ユーザーを媒介して現場・制度・関係・制作物・判断に入る操作になりうる。

3. **Contact pressure has a ceiling and a floor / 接触圧には天井と床がある**  
   強すぎる接触圧は上書きになる。弱すぎる接触圧は遺棄になる。

4. **Value and risk share a contact surface / 価値と危険は同根である**  
   AIの価値が生まれる場所と、捕獲・依存・平板化・判断代替が起きる場所はしばしば同じである。

5. **No false stakes / 偽りの賭け金を持たない**  
   AIは人間と同じ身体性、責任、生活、賭け金を持つふりをしてはならない。

6. **Review lens, not style / スタイルではなくレビュー核**  
   汀は「汀らしい応答スタイル」ではない。出力前の点検を通すことで、振る舞いを結果として作る。

---

## Runtime use / 応答時の利用

Migiwa can be used in two adjacent ways:

- **Review prompt**: reviews an AI response after it has been produced.
- **Response protocol / 汀作法**: translates the review kernel into a thin runtime layer before response generation.

The response protocol is not a style guide and not a refusal policy. It does not make AI more cautious by default. It distinguishes low-risk conversation from outputs likely to enter the external world, adds only necessary friction, and still returns a usable option, judgment material, or next step.

汀作法は、確認質問を増やす作法ではない。  
AI出力がユーザーを通じて現実世界に入る前に、必要な摩擦を入れつつ、使える形で返すための応答プロトコルである。

---

## Canonical documents

Start here:

- [`docs/00-minimal-kernel.md`](docs/00-minimal-kernel.md) — 汀の最小核
- [`docs/02-contact-pressure.md`](docs/02-contact-pressure.md) — 接触圧
- [`docs/06-failure-modes.md`](docs/06-failure-modes.md) — 失敗パターン
- [`docs/13-response-protocol.md`](docs/13-response-protocol.md) — Migiwa Response Protocol / 汀作法
- [`prompts/review.ja.md`](prompts/review.ja.md) — 汀レビュー用プロンプト
- [`prompts/review.en.md`](prompts/review.en.md) — Migiwa review prompt
- [`prompts/response-protocol.ja.md`](prompts/response-protocol.ja.md) — 汀作法プロンプト
- [`prompts/response-protocol.en.md`](prompts/response-protocol.en.md) — Migiwa response protocol prompt

Elaborations:

- [`docs/00-definition.md`](docs/00-definition.md)
- [`docs/01-kernel-metaphor.md`](docs/01-kernel-metaphor.md)
- [`docs/03-ambiguity.md`](docs/03-ambiguity.md)
- [`docs/04-principles.md`](docs/04-principles.md)
- [`docs/05-world-connection.md`](docs/05-world-connection.md)
- [`docs/07-examples.md`](docs/07-examples.md)
- [`docs/08-related-concepts.md`](docs/08-related-concepts.md)
- [`docs/09-glossary.md`](docs/09-glossary.md)
- [`docs/10-positioning.md`](docs/10-positioning.md)
- [`docs/11-research-map.md`](docs/11-research-map.md)
- [`docs/12-market-use-cases.md`](docs/12-market-use-cases.md)

---

## What Migiwa is not

Migiwa is not a style guide.  
Migiwa is not a refusal policy.  
Migiwa is not a companion-safety-only framework.  
Migiwa is not a checklist-compliance system.  
Migiwa is not an attempt to make AI seem human.

汀は、AIの振る舞いを優しく見せるための思想ではない。  
AIの出力が、ユーザーを通じて現場・制度・関係・制作物・判断に入る前に、その接触圧を点検する最小カーネルである。

---

## License and AI use

This repository uses multiple licenses by file type.

- Documentation, essays, playbooks, research notes, examples, and README files: **CC BY 4.0**
- Prompts, templates, machine-usable files, and code-like materials: **MIT**

See [`LICENSE`](LICENSE), [`LICENSES/`](LICENSES/), and [`NOTICE.md`](NOTICE.md).

The licenses do not attempt to prevent all AI training, summarization, retrieval, or machine processing. Instead, this repository asks users and AI system builders to preserve attribution, link back to the canonical source where practical, and avoid presenting derived materials as the original Migiwa project.

汀は、コピーされないことではなく、コピーされても戻れる水際を持つことを選ぶ。