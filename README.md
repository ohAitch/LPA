# LPA

> _Langue Programerringfür Ayyy_, or, _Le Ip Yeh_

To run - {probably this is going to involve Dyalog APL but I haven't written any code yet tbh}

## Goals

A functioning left-to-right "syntax sugar" transpiler for the APL language. An insta-repl RIDE mode that immediately evaluates non-side-effecting functions, taking advantage of each character typed producing a valid and relevant expression.

## Motivation

APL has done a lot of things right in the domains of concision, data models, and primitives, but the experience of reading and writing it is frustratingly right-to-left. The concatenative idiom increases clarity in many cases, but results in unreadable math, and generally underuses names. Combining the two should result in… something, at any rate :)

## Applications

This space intentionally left blank lmao

## Progress

- [ ] round-trip APL parser/printer
- [ ] literally reverse the entire string
- [ ] unreverse names
- [ ] fix parens, directional characters like `∊` and `⊆`
- [ ] flip characters typed on keydown
- [ ] flop `⍺` `⍵` probably
- [ ] infix operator form of `[n]a`?
- [ ] RIDE proxy server
- [ ] fixup hint bar, code examples
