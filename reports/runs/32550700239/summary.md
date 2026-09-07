## Robonix Webots CI

**Result:** `FAIL`
**Scenarios:** `16/17`
**Failures:** `1`

| Status | Suite | Scenario | Rounds | Failures |
| --- | --- | --- | ---: | --- |
| `PASS` | `flow` | `object_navigation` | 4 | - |
| `PASS` | `builtin` | `fault_recovery_builtin` | 3 | - |
| `PASS` | `builtin` | `file_roundtrip` | 1 | - |
| `PASS` | `builtin` | `run_command` | 1 | - |
| `PASS` | `cap` | `camera_snapshot` | 1 | - |
| `PASS` | `cap` | `explore_smoke` | 2 | - |
| `PASS` | `cap` | `lidar_snapshot` | 1 | - |
| `FAIL` | `cap` | `map_quality` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/primitive/chassis/move', 'robonix/primitive/chassis/move', 'robonix/primitive/chassis/move', 'robonix/primitive/chassis/move', 'robonix/primitive/chassis/move', 'robonix/primitive/chassis/move', 'robonix/primitive/chassis/move', 'robonix/primitive/chassis/move']; observed no later plan rounds |
| `PASS` | `cap` | `mapping_save` | 1 | - |
| `PASS` | `cap` | `memgraph_failure_lesson` | 1 | - |
| `PASS` | `cap` | `memgraph_roundtrip` | 3 | - |
| `PASS` | `cap` | `memory_roundtrip` | 1 | - |
| `PASS` | `cap` | `scene_object_fixture` | 1 | - |
| `PASS` | `cap` | `speech_speak` | 1 | - |
| `PASS` | `cap` | `voiceprint_list` | 1 | - |
| `PASS` | `flow` | `fault_recovery` | 2 | - |
| `PASS` | `flow` | `patrol_observe` | 3 | - |

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
