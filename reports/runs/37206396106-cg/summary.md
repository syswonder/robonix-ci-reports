## Robonix Webots CI

**Result:** `FAIL`
**Scenarios:** `15/16`
**Failures:** `1`

| Status | Suite | Scenario | Rounds | Failures |
| --- | --- | --- | ---: | --- |
| `FAIL` | `flow` | `object_navigation` | 4 | steps[0] did not match any plan round from 0; expected contracts=['robonix/skill/explore/explore']; observed round 0: calls=[('robonix/skill/explore/explore', '0e06-2:0')]; rtdl.children[0]: expected leaf 'robonix/skill/explore/explore' did not satisfy assertions: error text did not match regex 'hit 8\\.0s ceiling': 'Driver(CMD_ACTIVATE) failed: skill explore is REGISTERED; automatic activation is only valid from INACTIVE. The executor will not repeat CMD_ACTIVATE after an activation error; recover or restart the provider lifecycle first' \| round 1: calls=[('robonix/system/scene/list_objects', '0e06-3:0')]; rtdl.children[0]: expected leaf contract='robonix/skill/explore/explore' success=False, observed [('robonix/system/scene/list_objects', True)] \| round 2: calls=[('robonix/system/scene/goal_near', '0e06-6:0')]; rtdl.children[0]: expected leaf contract='robonix/skill/explore/explore' success=False, observed [('robonix/system/scene/goal_near', True)] |
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
| `PASS` | `flow` | `fault_recovery` | 2 | - |
| `PASS` | `flow` | `patrol_observe` | 3 | - |

### SLAM map

![SLAM occupancy map from this run](https://ci-reports.robonix.ai/reports/runs/37206396106-cg/slam-map.png)

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
