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
| `FAIL` | `cap` | `scene_object_fixture` | 64 | steps[0] did not match any plan round from 0; expected contracts=['robonix/system/scene/list_objects']; observed round 0: calls=[('robonix/system/scene/list_objects', 'a516-32:0')]; rtdl.children[0]: expected leaf 'robonix/system/scene/list_objects' did not satisfy assertions: checks[1] failed: select='$.objects[]' where={'all': [{'path': '$.label', 'op': 'ne', 'value': 'robot'}, {'path': '$.id', 'op': 'starts_with', 'value': 'scene.object.'}]} assert={'op': 'exists'} values=[] \| round 1: calls=[('robonix/system/scene/list_objects', 'a516-33:0')]; rtdl.children[0]: expected leaf 'robonix/system/scene/list_objects' did not satisfy assertions: checks[1] failed: select='$.objects[]' where={'all': [{'path': '$.label', 'op': 'ne', 'value': 'robot'}, {'path': '$.id', 'op': 'starts_with', 'value': 'scene.object.'}]} assert={'op': 'exists'} values=[] \| round 2: calls=[('robonix/system/scene/list_objects', 'a516-34:0')]; rtdl.children[0]: expected leaf 'robonix/system/scene/list_objects' did not satisfy assertions: checks[1] failed: select='$.objects[]' where={'all': [{'path': '$.label', 'op': 'ne', 'value': 'robot'}, {'path': '$.id', 'op': 'starts_with', 'value': 'scene.object.'}]} assert={'op': 'exists'} values=[] |
| `PASS` | `cap` | `speech_speak` | 1 | - |
| `PASS` | `cap` | `voiceprint_list` | 1 | - |
| `PASS` | `flow` | `fault_recovery` | 2 | - |
| `PASS` | `flow` | `patrol_observe` | 3 | - |

### SLAM map

![SLAM occupancy map from this run](https://ci-reports.robonix.ai/reports/runs/40461178523-cg/slam-map.png)

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
