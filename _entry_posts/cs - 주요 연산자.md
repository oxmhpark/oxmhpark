---
published: true
slug: "cs-주요-연산자"
title: "C#: 주요 연산자"
date: 2025-03-30 20:19:47 +0900
years:
  - 2025
categories:
  - 개발 노트
tags:
  - CSharp
  - 치트시트
excerpt: And | Or | Xor | Not | Shift
---

# 논리 연산[^1]

||| B5 | B4 | B3 | B2 | B1 | B0 | D |
|---|---|---|---|---|---|---|---|---|
|| `x` | 0 | 0 | 0 | 1 | 1 | 0 | 6 |
|| `y` | 0 | 0 | 1 | 1 | 0 | 0 | 12 |
| And | `x & y` | 0 | 0 | 0 | 1 | 0 | 0 | 4 |
| Or | `x | y` | 0 | 0 | 1 | 1 | 1 | 0 | 14 |
| Xor | `x ^ y` | 0 | 0 | 1 | 0 | 1 | 0 | 10 |

[^1]: <https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/operators/boolean-logical-operators>

# 비트 및 시프트 연산[^2]

||| B5 | B4 | B3 | B2 | B1 | B0 | D |
|---|---|---|---|---|---|---|---|---|
|| `x` | 0 | 0 | 0 | 1 | 1 | 0 | 6 |
| Not | `~x` | 1 | 1 | 1 | 0 | 0 | 1 | 9 |
| Shift (L) | `x << 1` | 0 | 0 | 1 | 1 | 0 | 0 | 12 |
| Shift (L) | `x << 2` | 0 | 1 | 1 | 0 | 0 | 0 | 24 |
| Shift (R) | `x >> 1` | 0 | 0 | 0 | 0 | 1 | 1 | 3 |
| Shift (R) | `x >> 2` | 0 | 0 | 0 | 0 | 0 | 1 | 1 |

[^2]: <https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/operators/bitwise-and-shift-operators>
