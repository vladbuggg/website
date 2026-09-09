---
title: Blog Template
date: 2026-07-01
tags: tag1, tag2, tag3
summary: A summary about it
---

## Inserting code

```erlang
handle_call({withdraw, Amount}, _From, State)
        when Amount =< State#state.balance ->
    NewState = State#state{balance = State#state.balance - Amount},
    {reply, ok, NewState};
```

