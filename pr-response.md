# PR Response Doc — CineLog Watchlist Feature

## AI Usage
<!-- Fill in at the end — how you used AI tools during this project -->

## Comment 1 — Rename
**What I did:**
I renamed `save_to_watchlist` to `add_to_watchlist` and changed all instances of it in the code to the new function name.

**How I verified:**
I verified that all instances of `save_to_watchlist` were changed by using my editor's search all file feature. Using this tool, I found all instances of `save_to_watchlist` in my code and changed them to the correct name.

## Comment 2 — Deduplication
**What I did:**
I added Deduplication logic to my `add_to_watchlist` function in the same way `add_to_collection` in `collection_service` does. 

**How I verified:**
I verified the Deduplication logic by running a test when I add the same film twice into the watchlist. This resulted in the second addition of the film throwing the correct error, hence I verified my deduplication logic.

## Comment 3 — Missing test
**What I did:**
**How I verified:**

## Comment 4 — Default visibility
**My position:**
**Reasoning:**
**Tradeoff acknowledged:**

## Comment 5 — Sort order
**My position:**
**Reasoning:**
**Engagement with reviewer's point:**

## Comment 6 — Rebase
**What conflicted:**
**How I resolved it:**
**How I verified no conflict remains:**

## PR Description
<!-- Written at the end — feature overview, design decisions, manual testing steps -->