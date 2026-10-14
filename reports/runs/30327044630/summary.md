## Robonix Webots CI

**Result:** `FAIL`
**Scenarios:** `15/18`
**Failures:** `3`

| Status | Suite | Scenario | Rounds | Failures |
| --- | --- | --- | ---: | --- |
| `PASS` | `flow` | `object_navigation` | 4 | - |
| `PASS` | `builtin` | `fault_recovery_builtin` | 3 | - |
| `PASS` | `builtin` | `file_roundtrip` | 1 | - |
| `PASS` | `builtin` | `run_command` | 1 | - |
| `PASS` | `cap` | `camera_snapshot` | 1 | - |
| `PASS` | `cap` | `explore_smoke` | 2 | - |
| `PASS` | `cap` | `lidar_snapshot` | 1 | - |
| `PASS` | `cap` | `mapping_save` | 1 | - |
| `PASS` | `cap` | `memory_roundtrip` | 1 | - |
| `PASS` | `cap` | `scene_label_stability` | 1 | - |
| `FAIL` | `cap` | `scene_object_dropout` | 1 | steps[0] did not match any plan round from 0; expected contracts=['robonix/system/executor/builtin/run_command']; observed round 0: calls=[('robonix/system/executor/builtin/run_command', '34:0')]; rtdl.children[0]: expected leaf 'robonix/system/executor/builtin/run_command' did not satisfy assertions: output JSON did not contain subset {'ok': True, 'reappeared_same_id': True}, got {'ok': False, 'error': 'ROS command failed (1):  Traceback (most recent call last):\n  File "<stdin>", line 13, in <module>\nRuntimeError: /spawn_node_from_string unavailable'} |
| `PASS` | `cap` | `scene_object_fixture` | 1 | - |
| `FAIL` | `cap` | `scene_object_management` | 3 | steps[2] did not match any plan round from 2; expected contracts=['robonix/system/scene/list_objects']; observed round 2: calls=[('robonix/system/scene/update_object_geometry', '40:0'), ('robonix/system/scene/delete_object', '40:1'), ('robonix/system/scene/flush_objects', '40:2')]; planned 3 call(s), expected 1; rtdl.children[0]: expected leaf contract='robonix/system/scene/list_objects' success=True, observed [('robonix/system/scene/flush_objects', False), ('robonix/system/scene/delete_object', False), ('robonix/system/scene/update_object_geometry', False)]<br>steps[3] did not match any plan round from 2; expected contracts=['robonix/system/scene/update_object_label']; observed round 2: calls=[('robonix/system/scene/update_object_geometry', '40:0'), ('robonix/system/scene/delete_object', '40:1'), ('robonix/system/scene/flush_objects', '40:2')]; planned 3 call(s), expected 1; rtdl.children[0]: expected leaf contract='robonix/system/scene/update_object_label' success=True, observed [('robonix/system/scene/flush_objects', False), ('robonix/system/scene/delete_object', False), ('robonix/system/scene/update_object_geometry', False)] |
| `FAIL` | `cap` | `scene_object_quality` | 1 | steps[0] did not match any plan round from 0; expected contracts=['robonix/system/executor/builtin/run_command']; observed round 0: calls=[('robonix/system/executor/builtin/run_command', '46:0')]; rtdl.children[0]: expected leaf 'robonix/system/executor/builtin/run_command' did not satisfy assertions: output JSON did not contain subset {'ok': True, 'off_map_count': 0, 'invalid_bbox_count': 0, 'background_label_count': 0, 'ground_truth_metrics': {'ok': True, 'label_accuracy': 1.0, 'stable_id_count': 1}}, got {'ok': False, 'visible_objects': 7, 'off_map_count': 0, 'invalid_bbox_count': 0, 'background_label_count': 0, 'quality': {'healthy_frames': 386, 'masks_input': 995, 'masks_retained': 992, 'depth_rejected_masks': 3, 'map_bounds_rejected_detections': 0, 'oversized_bbox_rejected_detections': 0, 'accepted_frame_detections': 992, 'require_occupancy_bounds': True, 'frame_dbscan': True, 'depth_range_m': [0.15, 6.0], 'max_bbox_extent_m': 3.0, 'map_bounds_margin_m': 0.25, 'label_provisional_objects': 2, 'label_history_size': 20, 'allow_cross_class_merge': False}, 'off_map_ids': [], 'invalid_bbox_ids': [], 'background_label_ids': [], 'ground_truth_metrics': {'ok': False, 'failures': ['label_accuracy below 1.0'], 'ground_truth': {'label': 'potted_plant', 'center_m': [1.546367, 0.160477, 0.65], 'bbox_size_m': [0.3, 0.3, 1.3], 'yaw_rad': 2.355248}, 'sample_count': 8, 'expected_samples': 8, 'target_recall': 1.0, 'label_accuracy': 0.0, 'stable_id_count': 1, 'median_center_xy_error_m': 0.096529, 'max_center_xy_drift_m': 0.0, 'median_center_z_error_m': 0.244224, 'median_bbox_iou_3d': 0.253018, 'median_point_inlier_fraction': 0.894531, 'median_point_count': 1220.0, 'navigation_grade_fraction': 1.0}} |
| `PASS` | `cap` | `speech_speak` | 1 | - |
| `PASS` | `cap` | `voiceprint_list` | 1 | - |
| `PASS` | `flow` | `fault_recovery` | 2 | - |
| `PASS` | `flow` | `patrol_observe` | 3 | - |

HTML report with embedded log viewer: `testing/report/index.html` in the uploaded artifact.
