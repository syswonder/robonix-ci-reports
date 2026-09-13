## Robonix Webots CI

**Result:** `FAIL`
**Scenarios:** `16/17`
**Failures:** `1`

| Status | Suite | Scenario | Rounds | Failures |
| --- | --- | --- | ---: | --- |
| `FAIL` | `flow` | `object_navigation` | 11 | timeout after 300s<br>before timeout: rbnx ask exit=124<br>before timeout: steps[0] did not match any plan round from 0; expected contracts=['robonix/skill/explore/explore']; observed round 0: calls=[('robonix/skill/explore/explore', '2:0')]; rtdl.children[0]: expected leaf 'robonix/skill/explore/explore' did not satisfy assertions: error text did not match regex 'hit 8\\.0s ceiling': 'Driver(CMD_ACTIVATE) failed: skill explore is REGISTERED; automatic activation is only valid from INACTIVE. The executor will not repeat CMD_ACTIVATE after an activation error; recover or restart the provider lifecycle first' \| round 1: calls=[('robonix/system/scene/list_objects', '3:0')]; rtdl.children[0]: expected leaf contract='robonix/skill/explore/explore' success=False, observed [('robonix/system/scene/list_objects', True)] \| round 2: calls=[('robonix/system/scene/goal_near', '6:0')]; rtdl.children[0]: expected leaf contract='robonix/skill/explore/explore' success=False, observed [('robonix/system/scene/goal_near', True)]<br>before timeout: steps[3] did not match any plan round from 3; expected contracts=['robonix/service/navigation/navigate']; observed round 3: calls=[('robonix/service/navigation/navigate', '7:0')]; rtdl.children[0]: expected leaf contract='robonix/service/navigation/navigate' success=True, observed [('robonix/service/navigation/navigate', False)] \| round 4: calls=[('robonix/service/navigation/navigate', '10:0')]; rtdl.children[0]: expected leaf contract='robonix/service/navigation/navigate' success=True, observed [('robonix/service/navigation/navigate', False)] \| round 5: calls=[('robonix/service/navigation/navigate', '13:0')]; rtdl.children[0]: expected leaf contract='robonix/service/navigation/navigate' success=True, observed [('robonix/service/navigation/navigate', False)]<br>before timeout: unexpected leaf failure robonix/skill/explore/explore: Driver(CMD_ACTIVATE) failed: skill explore is REGISTERED; automatic activation is only valid from INACTIVE. The executor will not repeat CMD_ACTIVATE after an a<br>before timeout: unexpected leaf failure robonix/service/navigation/navigate: aborted; distance_remaining=0.000m recoveries=15 last_pose=(-0.199,0.418); nav2=[planner_server-3] [WARN] [1787361391.088864556] [planner_server]: GridBased: fa<br>before timeout: unexpected leaf failure robonix/service/navigation/navigate: aborted; distance_remaining=0.000m recoveries=14 last_pose=(-0.550,0.203); nav2=[planner_server-3] [WARN] [1787361424.393526345] [planner_server]: GridBased: fa<br>before timeout: unexpected leaf failure robonix/service/navigation/navigate: aborted; distance_remaining=0.000m recoveries=15 last_pose=(-2.932,-1.752); nav2=[planner_server-3] [WARN] [1787361463.101479178] [planner_server]: GridBased: f<br>before timeout: unexpected leaf failure robonix/service/navigation/navigate: aborted; distance_remaining=0.000m recoveries=15 last_pose=(-9.154,-2.474); nav2=[planner_server-3] [WARN] [1787361530.703127246] [planner_server]: GridBased: f<br>before timeout: unexpected leaf failure robonix/service/navigation/navigate: aborted; distance_remaining=0.000m recoveries=15 last_pose=(-8.918,-2.242); nav2=[planner_server-3] [WARN] [1787361555.118688025] [planner_server]: GridBased: f<br>before timeout: unexpected leaf failure robonix/service/navigation/navigate: aborted; distance_remaining=0.000m recoveries=14 last_pose=(-9.324,-2.345); nav2=[planner_server-3] [WARN] [1787361587.424937284] [planner_server]: GridBased: f<br>before timeout: unexpected leaf failure robonix/service/navigation/navigate: aborted; distance_remaining=0.000m recoveries=15 last_pose=(-8.988,-2.463); nav2=[planner_server-3] [WARN] [1787361612.110353932] [planner_server]: GridBased: f |
| `PASS` | `builtin` | `fault_recovery_builtin` | 3 | - |
| `PASS` | `builtin` | `file_roundtrip` | 1 | - |
| `PASS` | `builtin` | `run_command` | 1 | - |
| `PASS` | `cap` | `camera_snapshot` | 1 | - |
| `PASS` | `cap` | `explore_smoke` | 2 | - |
| `PASS` | `cap` | `lidar_snapshot` | 1 | - |
| `PASS` | `cap` | `map_quality` | 1 | - |
| `PASS` | `cap` | `mapping_save` | 1 | - |
| `PASS` | `cap` | `memgraph_failure_lesson` | 1 | - |
| `PASS` | `cap` | `memgraph_roundtrip` | 3 | - |
| `PASS` | `cap` | `memory_roundtrip` | 1 | - |
| `PASS` | `cap` | `scene_object_fixture` | 1 | - |
| `PASS` | `cap` | `speech_speak` | 1 | - |
| `PASS` | `cap` | `voiceprint_list` | 1 | - |
| `PASS` | `flow` | `fault_recovery` | 2 | - |
| `PASS` | `flow` | `patrol_observe` | 3 | - |

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
