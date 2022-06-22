---
title: "Variables"
permalink: /variables/
---

# {{ page.title }}

Kl: Grade lists
Bg: Biographies
Ft: Census/population register

Instances: 1 or Multiple

## By individuals

| Variable | Source(s) | Instances | Note |
|---|---|---|---|
| ID | | 1 | Created to link each individual across observations |
| Name | Kl, Bg, Ft | 1 | |
| Maiden name | Kl, Bg, Ft | 1 | (if female) |
| Birth date | Bg, (Kl, Ft) | 1 | |
| Birth place | Bg, (Kl, Ft) | 1 | |
| Birth place | Bg, (Kl, Ft) | 1 | |


## Relation mapping

| Variable | Source(s) | Instances | Note |
|---|---|---|---|
| Student | Kl, Bg, Ft |  | | 
| Father | Bg, Ft, (Kl) | 1 | Birth date, place and occupation |
| Mother | Bg, Ft, (Kl) | 1 | Birth date, place and maiden name |
| Spouse | Bg, Ft | M | Birth date, place and (if female) maiden name |
| Child | Ft, (Bg) | M | Birth date, place -- note: can be more than one! |
