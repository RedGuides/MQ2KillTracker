---
tags:
  - command
---

# /killtracker

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/killtracker [on|off] | [status] | [report] | [reset] | [delay <#>]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Controls showing killcounts and the delay at which they are auto-reported.
<!--cmd-desc-end-->

## Options

`(no option)`
:   lists command syntax

`on|off`
:   Enables/disables kill tracking

`status`
:   shows current status of the plugin

`report`
:   Shows current tracked kill count

`reset`
:   reset tracked kill count to 0

`delay <#>`
:   Set time in minutes between kill count auto reports. Set to 0 to disable. Default is 60
