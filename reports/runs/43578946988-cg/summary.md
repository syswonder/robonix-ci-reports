## Robonix Webots CI

**Result:** `FAIL`
**Scenarios:** `15/16`
**Failures:** `1`

| Status | Suite | Scenario | Rounds | Failures |
| --- | --- | --- | ---: | --- |
| `PASS` | `flow` | `object_navigation` | 4 | - |
| `PASS` | `builtin` | `fault_recovery_builtin` | 3 | - |
| `PASS` | `builtin` | `file_roundtrip` | 1 | - |
| `FAIL` | `builtin` | `run_command` | 1 | steps[0] did not match any plan round from 0; expected contracts=['robonix/system/executor/builtin/run_command']; observed round 0: calls=[('robonix/system/executor/builtin/run_command', '8fe8-13:0')]; rtdl.children[0]: expected leaf 'robonix/system/executor/builtin/run_command' did not satisfy assertions: output text did not match regex '^robonix-ci-marker-bravo\\n?$': 'robonix-ci-marker-bravo\nexit code: 0' |
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

![SLAM occupancy map from this run](https://ci-reports.robonix.ai/reports/runs/43578946988-cg/slam-map.png)

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
