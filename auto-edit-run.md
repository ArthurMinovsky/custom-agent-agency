---
mode: primary
description: Auto-accept permisson mode as agent
permission:
  "*": allow
  doom_loop: ask
  external_directory:
    "*": ask
    /Users/aminovsky/.local/share/opencode/tool-output/*: allow
    /Users/aminovsky/Desktop/Work/NECTEC/Depression_analysis/.opencode/skills/lanta-ssh/*: allow
  read:
    "*.env": ask
    "*.env.*": ask
    "*.env.example": allow
---
