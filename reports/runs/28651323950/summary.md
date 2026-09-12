## Robonix Webots CI

**Result:** `FAIL`
**Scenarios:** `14/15`
**Failures:** `1`

| Status | Suite | Scenario | Rounds | Failures |
| --- | --- | --- | ---: | --- |
| `PASS` | `builtin` | `fault_recovery_builtin` | 3 | - |
| `PASS` | `builtin` | `file_roundtrip` | 1 | - |
| `FAIL` | `builtin` | `plan_control_builtins` | 1 | steps[0] did not match any plan round from 0; expected contracts=['robonix/system/executor/builtin/get_all_plans', 'robonix/system/executor/builtin/get_plan_status', 'robonix/system/executor/builtin/stop_plan_at']; observed round 0: calls=[('robonix/system/executor/builtin/get_all_plans', '1:0'), ('robonix/system/executor/builtin/get_plan_status', '1:1'), ('robonix/system/executor/builtin/stop_plan_at', '1:2')]; rtdl.children[1]: expected leaf 'robonix/system/executor/builtin/get_plan_status' did not satisfy assertions: jsonpath '$.ops[].op_id' missing exact value '1': ['16', '17', '18', '19'] |
| `PASS` | `builtin` | `run_command` | 1 | - |
| `PASS` | `cap` | `camera_snapshot` | 1 | - |
| `PASS` | `cap` | `explore_smoke` | 2 | - |
| `PASS` | `cap` | `lidar_snapshot` | 1 | - |
| `PASS` | `cap` | `mapping_save` | 1 | - |
| `PASS` | `cap` | `memory_roundtrip` | 1 | - |
| `PASS` | `cap` | `scene_object_fixture` | 1 | - |
| `PASS` | `cap` | `speech_speak` | 1 | - |
| `PASS` | `cap` | `voiceprint_list` | 1 | - |
| `PASS` | `flow` | `fault_recovery` | 2 | - |
| `PASS` | `flow` | `object_navigation` | 4 | - |
| `PASS` | `flow` | `patrol_observe` | 3 | - |

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
