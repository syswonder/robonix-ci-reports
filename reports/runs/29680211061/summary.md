## Robonix Webots CI

**Result:** `FAIL`
**Scenarios:** `7/15`
**Failures:** `8`

| Status | Suite | Scenario | Rounds | Failures |
| --- | --- | --- | ---: | --- |
| `PASS` | `builtin` | `fault_recovery_builtin` | 3 | - |
| `PASS` | `builtin` | `file_roundtrip` | 1 | - |
| `PASS` | `builtin` | `plan_control_builtins` | 1 | - |
| `PASS` | `builtin` | `run_command` | 1 | - |
| `PASS` | `cap` | `camera_snapshot` | 1 | - |
| `PASS` | `cap` | `explore_smoke` | 2 | - |
| `PASS` | `cap` | `lidar_snapshot` | 1 | - |
| `FAIL` | `cap` | `mapping_save` | 1 | rbnx ask exit=1<br>steps[0] did not match any plan round from 0; expected contracts=['robonix/service/map/save_map']; observed round 0: calls=[('robonix/service/map/save_map', '1:0')]; produced 0 leaf result(s) for 1 call(s); rtdl.children[0]: expected leaf contract='robonix/service/map/save_map' success=True, observed [] |
| `FAIL` | `cap` | `memory_roundtrip` | 0 | rbnx ask exit=1<br>steps[0] did not match any plan round from 0; expected contracts=['robonix/service/memory/save', 'robonix/service/memory/search']; observed no later plan rounds |
| `FAIL` | `cap` | `scene_object_fixture` | 0 | rbnx ask exit=1<br>steps[0] did not match any plan round from 0; expected contracts=['robonix/system/scene/list_objects']; observed no later plan rounds |
| `FAIL` | `cap` | `speech_speak` | 0 | rbnx ask exit=1<br>steps[0] did not match any plan round from 0; expected contracts=['robonix/service/speech/speak']; observed no later plan rounds |
| `FAIL` | `cap` | `voiceprint_list` | 0 | rbnx ask exit=1<br>steps[0] did not match any plan round from 0; expected contracts=['robonix/service/voiceprint/list']; observed no later plan rounds |
| `FAIL` | `flow` | `fault_recovery` | 0 | rbnx ask exit=1<br>steps[0] did not match any plan round from 0; expected contracts=['robonix/service/memory/save']; observed no later plan rounds<br>steps[1] did not match any plan round from 0; expected contracts=['robonix/service/memory/save']; observed no later plan rounds |
| `FAIL` | `flow` | `object_navigation` | 0 | rbnx ask exit=1<br>steps[0] did not match any plan round from 0; expected contracts=['robonix/skill/explore/explore']; observed no later plan rounds<br>steps[1] did not match any plan round from 0; expected contracts=['robonix/system/scene/list_objects']; observed no later plan rounds<br>steps[2] did not match any plan round from 0; expected contracts=['robonix/system/scene/goal_near']; observed no later plan rounds<br>steps[3] did not match any plan round from 0; expected contracts=['robonix/service/navigation/navigate']; observed no later plan rounds |
| `FAIL` | `flow` | `patrol_observe` | 0 | rbnx ask exit=1<br>steps[0] did not match any plan round from 0; expected contracts=['robonix/primitive/camera/snapshot', 'robonix/primitive/lidar/snapshot']; observed no later plan rounds<br>steps[1] did not match any plan round from 0; expected contracts=['robonix/service/memory/save']; observed no later plan rounds<br>steps[2] did not match any plan round from 0; expected contracts=['robonix/service/memory/search']; observed no later plan rounds |

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
