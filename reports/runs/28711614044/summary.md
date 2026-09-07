## Robonix Webots CI

**Result:** `FAIL`
**Scenarios:** `14/15`
**Failures:** `1`

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
| `PASS` | `cap` | `memory_roundtrip` | 1 | - |
| `FAIL` | `cap` | `scene_object_fixture` | 45 | steps[0] did not match any plan round from 0; expected contracts=['robonix/system/scene/list_objects']; observed round 0: calls=[('robonix/system/scene/list_objects', '1:0')]; rtdl.children[0]: expected leaf 'robonix/system/scene/list_objects' did not satisfy assertions: output text did not match regex '"label":\\s*"(?!robot)[^"]+"': '{\n  "objects": [\n    {\n      "id": "scene.object.robot_001",\n      "label": "robot",\n      "x": 0.8195212974605665,\n      "y": 0.056699247480400575,\n      "z": 0.0,\n      "yaw": 0.009482281834625397,\n      "last_seen_unix": 1783182216.4893417\n    }\n  ],\n  "stamp_unix": 1783182216.530669\n}' \| round 1: calls=[('robonix/system/scene/list_objects', '2:0')]; rtdl.children[0]: expected leaf 'robonix/system/scene/list_objects' did not satisfy assertions: output text did not match regex '"label":\\s*"(?!robot)[^"]+"': '{\n  "objects": [\n    {\n      "id": "scene.object.robot_001",\n      "label": "robot",\n      "x": 0.8195212243474964,\n      "y": 0.05669925796297208,\n      "z": 0.0,\n      "yaw": 0.009482278894063825,\n      "last_seen_unix": 1783182219.5198205\n    }\n  ],\n  "stamp_unix": 1783182219.6512773\n}' \| round 2: calls=[('robonix/system/scene/list_objects', '3:0')]; rtdl.children[0]: expected leaf 'robonix/system/scene/list_objects' did not satisfy assertions: output text did not match regex '"label":\\s*"(?!robot)[^"]+"': '{\n  "objects": [\n    {\n      "id": "scene.object.robot_001",\n      "label": "robot",\n      "x": 0.8195211487762591,\n      "y": 0.05669925724636318,\n      "z": 0.0,\n      "yaw": 0.009482275716495398,\n      "last_seen_unix": 1783182222.746691\n    }\n  ],\n  "stamp_unix": 1783182222.7606604\n}' |
| `PASS` | `cap` | `speech_speak` | 1 | - |
| `PASS` | `cap` | `voiceprint_list` | 1 | - |
| `PASS` | `flow` | `fault_recovery` | 4 | - |
| `PASS` | `flow` | `object_navigation` | 4 | - |
| `PASS` | `flow` | `patrol_observe` | 3 | - |

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
