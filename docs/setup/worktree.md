# Git worktree: обе копии репозитория

`git worktree list` — показывает основную копию и все рабочие копии
(Agent Manager создаёт их в `.kilo/worktrees/`):

```
/Users/outtathere/Desktop/carmoney-lab-outtathe                                        520cc35 [d1/1.2.1-1.2.3-outtathe]
/Users/outtathere/Desktop/carmoney-lab-outtathe/.kilo/worktrees/outtathe-worktree      df3a5b9 [outtathe-worktree]
/Users/outtathere/Desktop/carmoney-lab-outtathe/.kilo/worktrees/placid-writer          2939f79 [placid-writer]
/Users/outtathere/Desktop/carmoney-lab-outtathe/.kilo/worktrees/tourmaline-quesadilla  df3a5b9 (detached HEAD)
```

Основная копия — `/Users/outtathere/Desktop/carmoney-lab-outtathe` на ветке
`d1/1.2.1-1.2.3-outtathe`; остальные — изолированные worktree-копии
`outtathe-worktree`, `placid-writer` и `tourmaline-quesadilla` (detached HEAD).
