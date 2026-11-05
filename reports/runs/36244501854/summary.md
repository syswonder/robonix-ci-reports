## Robonix Webots CI

**Result:** `FAIL`
**Scenarios:** `0/16`
**Failures:** `16`

| Status | Suite | Scenario | Rounds | Failures |
| --- | --- | --- | ---: | --- |
| `FAIL` | `flow` | `object_navigation` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/skill/explore/explore']; observed no later plan rounds<br>steps[1] did not match any plan round from 0; expected contracts=['robonix/system/scene/list_objects']; observed no later plan rounds<br>steps[2] did not match any plan round from 0; expected contracts=['robonix/system/scene/goal_near']; observed no later plan rounds<br>steps[3] did not match any plan round from 0; expected contracts=['robonix/service/navigation/navigate']; observed no later plan rounds |
| `FAIL` | `builtin` | `fault_recovery_builtin` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/system/executor/builtin/read_file']; observed no later plan rounds<br>steps[1] did not match any plan round from 0; expected contracts=['robonix/system/executor/builtin/write_file']; observed no later plan rounds<br>steps[2] did not match any plan round from 0; expected contracts=['robonix/system/executor/builtin/read_file']; observed no later plan rounds |
| `FAIL` | `builtin` | `file_roundtrip` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/system/executor/builtin/write_file', 'robonix/system/executor/builtin/read_file', 'robonix/system/executor/builtin/list_dir']; observed no later plan rounds |
| `FAIL` | `builtin` | `run_command` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/system/executor/builtin/run_command']; observed no later plan rounds |
| `FAIL` | `cap` | `camera_snapshot` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/primitive/camera/snapshot']; observed no later plan rounds |
| `FAIL` | `cap` | `explore_smoke` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/skill/explore/explore']; observed no later plan rounds<br>steps[1] did not match any plan round from 0; expected contracts=['robonix/skill/explore/explore/status', 'robonix/skill/explore/explore/cancel']; observed no later plan rounds |
| `FAIL` | `cap` | `lidar_snapshot` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/primitive/lidar/snapshot']; observed no later plan rounds |
| `FAIL` | `cap` | `mapping_save` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/service/map/save_map']; observed no later plan rounds |
| `FAIL` | `cap` | `memgraph_failure_lesson` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/service/memory/remember', 'robonix/service/memory/remember', 'robonix/service/memory/hybrid_search']; observed no later plan rounds |
| `FAIL` | `cap` | `memgraph_roundtrip` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/service/memory/remember', 'robonix/service/memory/hybrid_search']; observed no later plan rounds<br>steps[1] did not match any plan round from 0; expected contracts=['robonix/service/memory/remember', 'robonix/service/memory/hybrid_search']; observed no later plan rounds<br>steps[2] did not match any plan round from 0; expected contracts=['robonix/service/memory/promote']; observed no later plan rounds |
| `FAIL` | `cap` | `memory_roundtrip` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/service/memory/save', 'robonix/service/memory/search']; observed no later plan rounds |
| `FAIL` | `cap` | `scene_object_fixture` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/system/scene/list_objects']; observed no later plan rounds |
| `FAIL` | `cap` | `speech_speak` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/service/speech/speak']; observed no later plan rounds |
| `FAIL` | `cap` | `voiceprint_list` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/service/voiceprint/list']; observed no later plan rounds |
| `FAIL` | `flow` | `fault_recovery` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/service/memory/save']; observed no later plan rounds<br>steps[1] did not match any plan round from 0; expected contracts=['robonix/service/memory/save']; observed no later plan rounds |
| `FAIL` | `flow` | `patrol_observe` | 0 | steps[0] did not match any plan round from 0; expected contracts=['robonix/primitive/camera/snapshot', 'robonix/primitive/lidar/snapshot']; observed no later plan rounds<br>steps[1] did not match any plan round from 0; expected contracts=['robonix/service/memory/save']; observed no later plan rounds<br>steps[2] did not match any plan round from 0; expected contracts=['robonix/service/memory/search']; observed no later plan rounds |

### SLAM map

![SLAM occupancy map from this run](https://ci-reports.robonix.ai/reports/runs/36244501854/slam-map.png)

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
