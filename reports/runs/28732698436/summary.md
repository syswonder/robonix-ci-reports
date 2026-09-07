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
| `FAIL` | `cap` | `scene_object_fixture` | 45 | steps[0] did not match any plan round from 0; expected contracts=['robonix/system/scene/list_objects']; observed round 0: calls=[('robonix/system/scene/list_objects', '1:0')]; rtdl.children[0]: expected leaf 'robonix/system/scene/list_objects' did not satisfy assertions: output text did not match regex '"label":\\s*"(?!robot)[^"]+"': '{\n  "objects": [\n    {\n      "id": "scene.object.robot_001",\n      "label": "robot",\n      "x": 0.8348730142339194,\n      "y": 0.06017307948532505,\n      "z": 0.0,\n      "yaw": 0.028103474504646838,\n      "last_seen_unix": 1783235652.8944702\n    }\n  ],\n  "stamp_unix": 1783235652.9372187\n}' \| round 1: calls=[('robonix/system/scene/list_objects', '2:0')]; rtdl.children[0]: expected leaf 'robonix/system/scene/list_objects' did not satisfy assertions: output text did not match regex '"label":\\s*"(?!robot)[^"]+"': '{\n  "objects": [\n    {\n      "id": "scene.object.robot_001",\n      "label": "robot",\n      "x": 0.8348729425601746,\n      "y": 0.06017308072573091,\n      "z": 0.0,\n      "yaw": 0.02810347255964002,\n      "last_seen_unix": 1783235655.9599469\n    }\n  ],\n  "stamp_unix": 1783235656.0720274\n}' \| round 2: calls=[('robonix/system/scene/list_objects', '3:0')]; rtdl.children[0]: expected leaf 'robonix/system/scene/list_objects' did not satisfy assertions: output text did not match regex '"label":\\s*"(?!robot)[^"]+"': '{\n  "objects": [\n    {\n      "id": "scene.object.robot_001",\n      "label": "robot",\n      "x": 0.8348728670953223,\n      "y": 0.0601730741073673,\n      "z": 0.0,\n      "yaw": 0.028103468457959246,\n      "last_seen_unix": 1783235659.1963782\n    }\n  ],\n  "stamp_unix": 1783235659.2010076\n}' |
| `PASS` | `cap` | `speech_speak` | 1 | - |
| `PASS` | `cap` | `voiceprint_list` | 1 | - |
| `PASS` | `flow` | `fault_recovery` | 4 | - |
| `PASS` | `flow` | `object_navigation` | 4 | - |
| `PASS` | `flow` | `patrol_observe` | 3 | - |

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
