# Search Spec (v0.1)

Indexing: exact_error (W4), title (W3), fix_summary (W3), root_cause (W2), repro_steps (W1)

Operators: project:, type:, env:, service:, lang:, framework:"Azure Functions", has:screenshot, has:refs  
Quoted text "..." = exact phrase

Ranking: exact phrase in exact_error > title > fix_summary > root_cause > repro; slight recency boost. 
