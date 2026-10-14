## Robonix Webots CI

**Result:** `FAIL`
**Scenarios:** `15/16`
**Failures:** `1`

| Status | Suite | Scenario | Rounds | Failures |
| --- | --- | --- | ---: | --- |
| `FAIL` | `flow` | `object_navigation` | 9 | timeout after 300s<br>before timeout: rbnx ask exit=124<br>before timeout: steps[3] did not match any plan round from 3; expected contracts=['robonix/service/navigation/navigate']; observed round 3: calls=[('robonix/service/navigation/navigate', '32c2-7:0')]; rtdl.children[0]: expected leaf contract='robonix/service/navigation/navigate' success=True, observed [('robonix/service/navigation/navigate', False)] \| round 4: calls=[('robonix/service/navigation/navigate', '32c2-10:0')]; rtdl.children[0]: expected leaf contract='robonix/service/navigation/navigate' success=True, observed [('robonix/service/navigation/navigate', False)] \| round 5: calls=[('robonix/service/navigation/navigate', '32c2-13:0')]; rtdl.children[0]: expected leaf contract='robonix/service/navigation/navigate' success=True, observed [('robonix/service/navigation/navigate', False)]<br>before timeout: unexpected leaf failure robonix/service/navigation/navigate: aborted; distance_remaining=0.000m recoveries=22 last_pose=(1.715,-0.542); nav2=[planner_server-3] [WARN] [1791112329.423627185] [planner_server]: GridBased: fa<br>before timeout: unexpected leaf failure robonix/service/navigation/navigate: aborted; distance_remaining=0.000m recoveries=22 last_pose=(1.723,-0.547); nav2=[planner_server-3] [WARN] [1791112363.448170541] [planner_server]: GridBased: fa<br>before timeout: unexpected leaf failure robonix/service/navigation/navigate: aborted; distance_remaining=0.000m recoveries=22 last_pose=(1.728,-0.548); nav2=[planner_server-3] [WARN] [1791112399.321220551] [planner_server]: GridBased: fa<br>before timeout: unexpected leaf failure robonix/service/navigation/navigate: aborted; distance_remaining=0.000m recoveries=22 last_pose=(1.755,-0.549); nav2=[planner_server-3] [WARN] [1791112434.462352493] [planner_server]: GridBased: fa<br>before timeout: unexpected leaf failure robonix/service/navigation/navigate: aborted; distance_remaining=0.000m recoveries=22 last_pose=(1.783,-0.546); nav2=[planner_server-3] [WARN] [1791112469.456525015] [planner_server]: GridBased: fa |
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

![SLAM occupancy map from this run](https://ci-reports.robonix.ai/reports/runs/37197515154-cg/slam-map.png)

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
