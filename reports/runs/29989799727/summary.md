## Robonix Webots CI

**Result:** `FAIL`
**Scenarios:** `15/17`
**Failures:** `2`

| Status | Suite | Scenario | Rounds | Failures |
| --- | --- | --- | ---: | --- |
| `PASS` | `builtin` | `fault_recovery_builtin` | 3 | - |
| `PASS` | `builtin` | `file_roundtrip` | 1 | - |
| `PASS` | `builtin` | `plan_control_builtins` | 1 | - |
| `PASS` | `builtin` | `run_command` | 1 | - |
| `PASS` | `cap` | `camera_snapshot` | 1 | - |
| `PASS` | `cap` | `explore_smoke` | 2 | - |
| `PASS` | `cap` | `lidar_snapshot` | 1 | - |
| `PASS` | `cap` | `mapping_save` | 1 | - |
| `FAIL` | `cap` | `memgraph_failure_lesson` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/service/memory/remember', 'robonix/service/memory/remember', 'robonix/service/memory/hybrid_search']; observed no later plan rounds |
| `FAIL` | `cap` | `memgraph_roundtrip` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/service/memory/remember', 'robonix/service/memory/hybrid_search']; observed no later plan rounds<br>steps[1] did not match any plan round from 0; expected contracts=['robonix/service/memory/remember', 'robonix/service/memory/hybrid_search']; observed no later plan rounds<br>steps[2] did not match any plan round from 0; expected contracts=['robonix/service/memory/promote']; observed no later plan rounds |
| `PASS` | `cap` | `memory_roundtrip` | 1 | - |
| `PASS` | `cap` | `scene_object_fixture` | 1 | - |
| `PASS` | `cap` | `speech_speak` | 1 | - |
| `PASS` | `cap` | `voiceprint_list` | 1 | - |
| `PASS` | `flow` | `fault_recovery` | 4 | - |
| `PASS` | `flow` | `object_navigation` | 4 | - |
| `PASS` | `flow` | `patrol_observe` | 3 | - |

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
