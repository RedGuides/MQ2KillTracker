---
tags:
  - plugin
resource_link: "https://www.redguides.com/community/resources/mq2killtracker.137/"
support_link: "https://www.redguides.com/community/threads/mq2killtracker.66841/"
repository: "https://github.com/RedGuides/MQ2KillTracker"
config: "Server_Character.ini"
authors: "Sym"
tagline: "Tracks kills over time and can auto report kill counts every X minutes"
---

# MQ2KillTracker

<!--desc-start-->
MQ2KillTracker tracks kills over time and can auto report kill counts every X minutes.
<!--desc-end-->

## Commands

<a href="cmd-killcount/">
{% 
  include-markdown "projects/mq2killtracker/cmd-killcount.md" 
  start="<!--cmd-syntax-start-->" 
  end="<!--cmd-syntax-end-->" 
%}
</a>
:    {% include-markdown "projects/mq2killtracker/cmd-killcount.md" 
        start="<!--cmd-desc-start-->" 
        end="<!--cmd-desc-end-->" 
        trailing-newlines=false 
     %} {{ readMore('projects/mq2killtracker/cmd-killcount.md') }}

<a href="cmd-killtracker/">
{% 
  include-markdown "projects/mq2killtracker/cmd-killtracker.md" 
  start="<!--cmd-syntax-start-->" 
  end="<!--cmd-syntax-end-->" 
%}
</a>
:    {% include-markdown "projects/mq2killtracker/cmd-killtracker.md" 
        start="<!--cmd-desc-start-->" 
        end="<!--cmd-desc-end-->" 
        trailing-newlines=false 
     %} {{ readMore('projects/mq2killtracker/cmd-killtracker.md') }}

## Settings

Example settings from Server_Charname.ini

```ini
[MQ2KillTracker]
Enabled=1
DelayInMinutes=60
```
