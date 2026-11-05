## Robonix Webots CI

**Result:** `FAIL`
**Scenarios:** `15/16`
**Failures:** `1`

| Status | Suite | Scenario | Rounds | Failures |
| --- | --- | --- | ---: | --- |
| `PASS` | `flow` | `object_navigation` | 4 | - |
| `FAIL` | `builtin` | `fault_recovery_builtin` | 1 | rbnx ask exit=1<br>steps[0] did not match any plan round from 0; expected contracts=['robonix/system/executor/builtin/read_file']; observed round 0: calls=[('robonix/system/executor/builtin/read_file', '02e4-7:0')]; produced 0 leaf result(s) for 1 call(s); rtdl.children[0]: expected leaf contract='robonix/system/executor/builtin/read_file' success=False, observed []<br>steps[1] did not match any plan round from 0; expected contracts=['robonix/system/executor/builtin/write_file']; observed round 0: calls=[('robonix/system/executor/builtin/read_file', '02e4-7:0')]; produced 0 leaf result(s) for 1 call(s); rtdl.children[0]: expected leaf contract='robonix/system/executor/builtin/write_file' success=True, observed []<br>steps[2] did not match any plan round from 0; expected contracts=['robonix/system/executor/builtin/read_file']; observed round 0: calls=[('robonix/system/executor/builtin/read_file', '02e4-7:0')]; produced 0 leaf result(s) for 1 call(s); rtdl.children[0]: expected leaf contract='robonix/system/executor/builtin/read_file' success=True, observed [] |
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
| `PASS` | `flow` | `fault_recovery` | 2 | - |
| `PASS` | `flow` | `patrol_observe` | 3 | - |

### SLAM map

![SLAM occupancy map from this run](https://ci-reports.robonix.ai/reports/runs/41886743804-dm/slam-map.png)

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
