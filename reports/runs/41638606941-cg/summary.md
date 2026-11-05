## Robonix Webots CI

**Result:** `FAIL`
**Scenarios:** `15/16`
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
| `PASS` | `cap` | `mapping_save` | 1 | - |
| `PASS` | `cap` | `memgraph_failure_lesson` | 1 | - |
| `PASS` | `cap` | `memgraph_roundtrip` | 3 | - |
| `PASS` | `cap` | `memory_roundtrip` | 1 | - |
| `PASS` | `cap` | `scene_object_fixture` | 1 | - |
| `PASS` | `cap` | `speech_speak` | 1 | - |
| `PASS` | `cap` | `voiceprint_list` | 1 | - |
| `FAIL` | `flow` | `fault_recovery` | 3 | rbnx ask exit=1<br>steps[1] did not match any plan round from 1; expected contracts=['robonix/service/memory/save']; observed round 1: calls=[('robonix/service/memory/save', '0aa2-39:0')]; produced 0 leaf result(s) for 1 call(s); rtdl.children[0]: expected leaf contract='robonix/service/memory/save' success=True, observed [] \| round 2: calls=[]; planned 0 call(s), expected 1; rtdl.children[0]: expected leaf contract='robonix/service/memory/save' success=True, observed [] |
| `PASS` | `flow` | `patrol_observe` | 3 | - |

### SLAM map

![SLAM occupancy map from this run](https://ci-reports.robonix.ai/reports/runs/41638606941-cg/slam-map.png)

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
