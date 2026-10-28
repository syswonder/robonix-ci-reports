## Robonix Webots CI

**Result:** `FAIL`
**Scenarios:** `13/16`
**Failures:** `3`

| Status | Suite | Scenario | Rounds | Failures |
| --- | --- | --- | ---: | --- |
| `FAIL` | `flow` | `object_navigation` | 1 | rbnx ask exit=1<br>steps[0] did not match any plan round from 0; expected contracts=['robonix/skill/explore/explore']; observed round 0: calls=[('robonix/skill/explore/explore', '4094-2:0')]; produced 0 leaf result(s) for 1 call(s); rtdl.children[0]: expected leaf contract='robonix/skill/explore/explore' success=False, observed []<br>steps[1] did not match any plan round from 0; expected contracts=['robonix/system/scene/list_objects']; observed round 0: calls=[('robonix/skill/explore/explore', '4094-2:0')]; produced 0 leaf result(s) for 1 call(s); rtdl.children[0]: expected leaf contract='robonix/system/scene/list_objects' success=True, observed []<br>steps[2] did not match any plan round from 0; expected contracts=['robonix/system/scene/goal_near']; observed round 0: calls=[('robonix/skill/explore/explore', '4094-2:0')]; produced 0 leaf result(s) for 1 call(s); rtdl.children[0]: expected leaf contract='robonix/system/scene/goal_near' success=True, observed []<br>steps[3] did not match any plan round from 0; expected contracts=['robonix/service/navigation/navigate']; observed round 0: calls=[('robonix/skill/explore/explore', '4094-2:0')]; produced 0 leaf result(s) for 1 call(s); rtdl.children[0]: expected leaf contract='robonix/service/navigation/navigate' success=True, observed [] |
| `PASS` | `builtin` | `fault_recovery_builtin` | 3 | - |
| `PASS` | `builtin` | `file_roundtrip` | 1 | - |
| `PASS` | `builtin` | `run_command` | 1 | - |
| `PASS` | `cap` | `camera_snapshot` | 1 | - |
| `FAIL` | `cap` | `explore_smoke` | 0 | rbnx ask exit=1<br>steps[0] did not match any plan round from 0; expected contracts=['robonix/skill/explore/explore']; observed no later plan rounds<br>steps[1] did not match any plan round from 0; expected contracts=['robonix/skill/explore/explore/status', 'robonix/skill/explore/explore/cancel']; observed no later plan rounds |
| `PASS` | `cap` | `lidar_snapshot` | 1 | - |
| `PASS` | `cap` | `mapping_save` | 1 | - |
| `PASS` | `cap` | `memgraph_failure_lesson` | 1 | - |
| `PASS` | `cap` | `memgraph_roundtrip` | 3 | - |
| `PASS` | `cap` | `memory_roundtrip` | 1 | - |
| `FAIL` | `cap` | `scene_object_fixture` | 0 | rbnx ask exit=1<br>steps[0] did not match any plan round from 0; expected contracts=['robonix/system/scene/list_objects']; observed no later plan rounds |
| `PASS` | `cap` | `speech_speak` | 1 | - |
| `PASS` | `cap` | `voiceprint_list` | 1 | - |
| `PASS` | `flow` | `fault_recovery` | 2 | - |
| `PASS` | `flow` | `patrol_observe` | 3 | - |

### SLAM map

![SLAM occupancy map from this run](https://ci-reports.robonix.ai/reports/runs/40168991176-cg/slam-map.png)

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
