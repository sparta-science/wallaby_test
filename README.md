### performance of `time mix test`

| step | time |
| ---- | ---- |
| brand new phoenix project | 0.0557s |
| add wallaby 0.19.2 to deps | 0.647s |
| add `{:ok, _} = Application.ensure_all_started(:wallaby)` to `test_helper.exs` | 14.418s |
| go back to `a6f232c` | 0.972s |
| go to `29aed59a` (head) | 12.482s |
| go to 0.19.1 | 0.925s |

