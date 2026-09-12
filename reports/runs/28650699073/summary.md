## Robonix Webots CI

**Result:** `FAIL`
**Scenarios:** `13/14`
**Failures:** `1`

| Status | Suite | Scenario | Rounds | Failures |
| --- | --- | --- | ---: | --- |
| `PASS` | `builtin` | `fault_recovery_builtin` | 3 | - |
| `PASS` | `builtin` | `file_roundtrip` | 1 | - |
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
| `FAIL` | `flow` | `object_navigation` | 2 | steps[1] did not match any plan round from 1; expected contracts=['robonix/system/scene/list_objects']; observed round 1: calls=[('robonix/system/scene/list_objects', '2:0')]; rtdl.children[0]: expected leaf 'robonix/system/scene/list_objects' did not satisfy assertions: output text did not match regex '"label":\\s*"(?!robot)[^"]+"': '{\n  "objects": [\n    {\n      "id": "scene.object.robot_001",\n      "label": "robot",\n      "x": 0.8213417386159421,\n      "y": 0.05591520487328666,\n      "z": 0.0,\n      "yaw": 0.029677648161309522,\n      "last_seen_unix": 1783071293.6984234\n    }\n  ],\n  "stamp_unix": 1783071293.8984308\n}'<br>steps[2] did not match any plan round from 1; expected contracts=['robonix/system/scene/goal_near']; observed round 1: calls=[('robonix/system/scene/list_objects', '2:0')]; rtdl.children[0]: expected leaf contract='robonix/system/scene/goal_near' success=True, observed [('robonix/system/scene/list_objects', True)]<br>steps[3] did not match any plan round from 1; expected contracts=['robonix/service/navigation/navigate']; observed round 1: calls=[('robonix/system/scene/list_objects', '2:0')]; rtdl.children[0]: expected leaf contract='robonix/service/navigation/navigate' success=True, observed [('robonix/system/scene/list_objects', True)] |
| `PASS` | `flow` | `patrol_observe` | 3 | - |

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
