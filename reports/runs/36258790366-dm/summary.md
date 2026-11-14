## Robonix Webots CI

**Result:** `FAIL`
**Scenarios:** `15/16`
**Failures:** `1`

| Status | Suite | Scenario | Rounds | Failures |
| --- | --- | --- | ---: | --- |
| `FAIL` | `flow` | `object_navigation` | 9 | timeout after 300s<br>before timeout: rbnx ask exit=124<br>before timeout: steps[3] did not match any plan round from 3; expected contracts=['robonix/service/navigation/navigate']; observed round 3: calls=[('robonix/service/navigation/navigate', 'e868-7:0')]; rtdl.children[0]: expected leaf contract='robonix/service/navigation/navigate' success=True, observed [('robonix/service/navigation/navigate', False)] \| round 4: calls=[('robonix/service/navigation/navigate', 'e868-10:0')]; rtdl.children[0]: expected leaf contract='robonix/service/navigation/navigate' success=True, observed [('robonix/service/navigation/navigate', False)] \| round 5: calls=[('robonix/service/navigation/navigate', 'e868-13:0')]; rtdl.children[0]: expected leaf contract='robonix/service/navigation/navigate' success=True, observed [('robonix/service/navigation/navigate', False)]<br>before timeout: unexpected leaf failure robonix/service/navigation/navigate: aborted; distance_remaining=0.000m recoveries=15 last_pose=(-7.619,5.072); nav2=[planner_server-3] [WARN] [1790444636.108386070] [planner_server]: GridBased: fa<br>before timeout: unexpected leaf failure robonix/service/navigation/navigate: aborted; distance_remaining=0.000m recoveries=14 last_pose=(-7.960,5.300); nav2=[planner_server-3] [WARN] [1790444678.298194708] [planner_server]: GridBased: fa<br>before timeout: unexpected leaf failure robonix/service/navigation/navigate: aborted; distance_remaining=0.000m recoveries=15 last_pose=(-7.813,4.995); nav2=[planner_server-3] [WARN] [1790444712.094722323] [planner_server]: GridBased: fa<br>before timeout: unexpected leaf failure robonix/service/navigation/navigate: aborted; distance_remaining=0.000m recoveries=14 last_pose=(-7.832,5.405); nav2=[planner_server-3] [WARN] [1790444755.415442017] [planner_server]: GridBased: fa<br>before timeout: unexpected leaf failure robonix/service/navigation/navigate: aborted; distance_remaining=0.000m recoveries=15 last_pose=(-7.995,5.110); nav2=[planner_server-3] [WARN] [1790444787.987584808] [planner_server]: GridBased: fa |
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

![SLAM occupancy map from this run](https://ci-reports.robonix.ai/reports/runs/36258790366-dm/slam-map.png)

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
