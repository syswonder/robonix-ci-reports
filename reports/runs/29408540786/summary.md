## Robonix Webots CI

**Result:** `FAIL`
**Scenarios:** `13/15`
**Failures:** `2`

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
| `PASS` | `cap` | `scene_object_fixture` | 1 | - |
| `FAIL` | `cap` | `speech_speak` | 64 | steps[0] did not match any plan round from 0; expected contracts=['robonix/service/speech/speak']; observed round 0: calls=[('robonix/service/speech/speak', '1:0')]; rtdl.children[0]: expected leaf contract='robonix/service/speech/speak' success=True, observed [('robonix/service/speech/speak', False)] \| round 1: calls=[('robonix/service/speech/speak', '2:0')]; rtdl.children[0]: expected leaf contract='robonix/service/speech/speak' success=True, observed [('robonix/service/speech/speak', False)] \| round 2: calls=[('robonix/service/speech/speak', '3:0')]; rtdl.children[0]: expected leaf contract='robonix/service/speech/speak' success=True, observed [('robonix/service/speech/speak', False)]<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session<br>unexpected leaf failure robonix/service/speech/speak: mcp tool error: Error executing tool speak: <_InactiveRpcError of RPC that terminated with:
	status = StatusCode.UNAVAILABLE
	details = "no client audio session |
| `PASS` | `cap` | `voiceprint_list` | 1 | - |
| `PASS` | `flow` | `fault_recovery` | 4 | - |
| `FAIL` | `flow` | `object_navigation` | 62 | steps[3] did not match any plan round from 3; expected contracts=['robonix/service/navigation/navigate']; observed round 3: calls=[('robonix/service/navigation/navigate', '4:0')]; rtdl.children[0]: expected leaf contract='robonix/service/navigation/navigate' success=True, observed [('robonix/service/navigation/navigate', False)] \| round 4: calls=[('robonix/service/navigation/navigate', '5:0')]; rtdl.children[0]: expected leaf contract='robonix/service/navigation/navigate' success=True, observed [('robonix/service/navigation/navigate', False)] \| round 5: calls=[('robonix/service/navigation/navigate', '6:0')]; rtdl.children[0]: expected leaf contract='robonix/service/navigation/navigate' success=True, observed [('robonix/service/navigation/navigate', False)]<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected<br>unexpected leaf failure robonix/service/navigation/navigate: goal rejected |
| `PASS` | `flow` | `patrol_observe` | 3 | - |

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
