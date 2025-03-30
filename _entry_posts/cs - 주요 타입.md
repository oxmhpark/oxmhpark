---
published: true
slug: "cs-주요-타입"
title: "C#: 주요 타입"
date: 2025-03-30 13:19:47 +0900
categories:
  - 개발 노트
tags:
  - 치트시트
---
# 정수

| 타입 이름 | 최소값 | 최대값 | 특징 |
|---|---|---|---|
| `[byte][ref-byte]` | 0 | 0 | |
| `[sbyte][ref-sbyte]` | 0 | 0 | |
| `[short][ref-short]` | 0 | 0 | |
| `[ushort][ref-ushort]` | 0 | 0 | |
| `[int][ref-int]` | 0 | 0 | |
| `[uint][ref-uint]` | 0 | 0 | |
| `[long][ref-long]` | 0 | 0 | |
| `[ulong][ref-ulong]` | 0 | 0 | |
| `[BigInteger][ref-biginteger]` | 0 | 0 | `System.Numerics` 이름공간에 정의됨. |

[ref-byte]: https://learn.microsoft.com/en-us/dotnet/api/system.byte
[ref-sbyte]: https://learn.microsoft.com/en-us/dotnet/api/system.sbyte
[ref-short]: https://learn.microsoft.com/en-us/dotnet/api/system.short
[ref-ushort]: https://learn.microsoft.com/en-us/dotnet/api/system.ushort
[ref-int]: https://learn.microsoft.com/en-us/dotnet/api/system.int
[ref-uint]: https://learn.microsoft.com/en-us/dotnet/api/system.uint
[ref-long]: https://learn.microsoft.com/en-us/dotnet/api/system.long
[ref-ulong]: https://learn.microsoft.com/en-us/dotnet/api/system.ulong
[ref-biginteger]: https://learn.microsoft.com/en-us/dotnet/api/system.numerics.biginteger

# 실수

| 타입 이름 | 최소값 | 최대값 | 특징 |
|---|---|---|---|
| `[float][ref-float]` | 0 | 0 | |
| `[double][ref-double]` | 0 | 0 | |

[ref-float]: https://learn.microsoft.com/en-us/dotnet/api/system.float
[ref-double]: https://learn.microsoft.com/en-us/dotnet/api/system.double

# 플래그

| 타입 이름 | 최소값 | 최대값 | 특징 |
|---|---|---|---|
| `[bool][ref-bool]` | false | true | |
| `[enum][ref-enum]` | 0 | 0 | 구체적인 타입으로 상속받아야 한다. |

[ref-bool]: https://learn.microsoft.com/en-us/dotnet/api/system.bool
[ref-enum]: https://learn.microsoft.com/en-us/dotnet/api/system.enum

# 문자

| 타입 이름 | 값 | 특징 |
|---|---|---|
| `[char][ref-char]` | 문자 | 작은 따옴표로 감싼다. |
| `[string][ref-string]` | 문자열 | 큰 따옴표로 감싼다. |

[ref-char]: https://learn.microsoft.com/en-us/dotnet/api/system.char
[ref-string]: https://learn.microsoft.com/en-us/dotnet/api/system.string

# 날짜와 시간

| 타입 이름 | 특징 |
|---|---|
| `[DateTime][ref-DateTime]` |  |
| `[TimeSpan][ref-TimeSpan]` |  |

[ref-datetime]: https://learn.microsoft.com/en-us/dotnet/api/system.datetime
[ref-timespan]: https://learn.microsoft.com/en-us/dotnet/api/system.timespan
