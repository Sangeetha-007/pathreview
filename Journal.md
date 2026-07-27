## Week 7 — Issue selection

**Issue link:** [https://github.com/ascherj/pathreview/issues/153]

**Issue title:** [Faithfulness checker crashes when a context chunk has text: None]

**Tier:** [x] Tier 1  [ ] Tier 2  [ ] Tier 3

**Problem summary:**
[test_faithfulness_checker.py's 4 tests failed, and 18 passed. The exact issue is caused at test_none_context_chunk_text - TypeError: sequence item 0: expected str instance, NoneType found. I will need to figure out a way to return a string. It could be a casting issue.]

**Branch name:** [fix/150-faithfulness_checker]

**Setup confirmation:** [x] App runs locally at localhost:5173

**Cohort ledger:** [x] Issue added to cohort ledger

**Selection notes:** 
[I felt this issue will help me further get comfortable with RAG.]