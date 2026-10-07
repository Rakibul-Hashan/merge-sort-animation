v0.19 – “Code in stages” panel for approaches 1 and 2: plain actions (EN/বাংলা) → pseudocode → complete runnable C code with a Copy button. For approach 2, “Highlight what changed vs approach 1” marks the key differences. Other approaches show “coming later”.
v0.18 – Bilingual glossary (17 terms: array, index, pointer, buffer, run, rotation, link, stable…) with small examples; Bangla terms use the “বাংলা (English)” style.
v0.17 – “Where do the costs come from?” panel: explains time (levels × n), the reference comparison limit, and the memory cost of the selected approach, using the current example. Also separates Θ growth from real running time.
v0.16 – New approach 8: Advanced in-place merge using block rotations (binary search + rotate, no extra array). Approaches 7 and 8 now sit in an optional “Advanced stage” group in the dropdown so beginners can start with 1–6.
v0.15 – New approach 7: Simple in-place merge using shifts. No auxiliary array; shows each shift step. New “Shifts” counter. Try Reversed input to see the Θ(n²) cost.
v0.14 – New approach 6: Linked-list Merge Sort. Merges by relinking nodes: 0 array writes, 0 allocations, and the leftover list is attached with one link change. New “Link changes” counter (0 for array approaches).
v0.13 – Prediction exercise in the comparison panel: guess which approach does fewer writes (or “Same”) before the table is revealed. Prediction mode can be switched off.
v0.12 – Input pattern buttons: Sorted, Reversed, Random, Duplicates, Nearly sorted (8 numbers). Click one, then watch the animation and the comparison table change.
v0.11 – Same-input comparison: pick any two approaches and see their operation counts side by side for the current input (fewer operations highlighted in green).
v0.10 – New approach 5: Natural Merge Sort. One scan finds existing sorted runs (shown as separate lists), then runs are merged pass by pass. Sorted input needs only n−1 comparisons and 0 writes.
v0.9 – New approach 4: Optimized recursive Merge Sort. Checks arr[mid] ≤ arr[mid+1] before each merge and skips it when already in order (counts as 1 comparison). Try a sorted input to see 0 writes.
v0.8 – New “Splitting view” option for recursive approaches: Concurrent (all groups at a level divide together, then merge level by level) alongside the original Sequential real-recursion order. Counts are identical in both.
v0.7 – New approach 3: Iterative bottom-up Merge Sort. Starts with every number as its own list, then merges pass by pass (1→2→4→8…). No splitting, no recursion (max depth 0), shares one buffer.
v0.6 – Step slider: drag to jump to any step directly (works with Play, ◀ ▶| and arrow keys).
v0.5 – Every list is now drawn as its own box (LEFT LIST / RIGHT LIST / OUTPUT). Each comparison is a separate step with a bracket joining the front of the left list to the front of the right list, then a second step takes the smaller one. Left and right items have different colours. “Why do we split?” text corrected: comparisons happen only between two different lists.
v0.4 – Merge now shows two separate lists (left, right) with i/j pointers on their front values, and a separate output row where chosen values are placed. Added a “Why do we split?” note (EN/বাংলা).
v0.3 – Split animation: the array now divides and drops down level by level (and rises back up when merging) instead of blurring. New sleek dark glass UI.
v0.2 – Approaches: basic recursive (temp arrays) and reusable auxiliary array, with operation counts.
v0.1 – Base: custom/random input, play/pause/prev/next/restart, speed, phase label, step text, English/বাংলা.
