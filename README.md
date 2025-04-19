##METRICS DATA USING PROMETHEUS:
http://localhost:9464/metrics

# HELP target_info Target metadata
# TYPE target_info gauge
target_info{host_name="LAPTOP-2DLL14AN",host_arch="amd64",process_pid="10208",process_executable_name=" ",process_executable_path="C:\\Program Files\\nodejs\\node.exe",process_command_args="[\"C:\\\\Program Files\\\\nodejs\\\\node.exe\",\"--require\",\"./instrumentation.js\",\"D:\\\\BTECH_CSEcore\\\\Internship\\\\CDAC\\\\app.js\"]",process_runtime_version="22.12.0",process_runtime_name="nodejs",process_runtime_description="Node.js",process_command="D:\\BTECH_CSEcore\\Internship\\CDAC\\app.js",process_owner="Sushindh A",service_name="unknown_service:C:/Program Files/nodejs/node.exe",telemetry_sdk_language="nodejs",telemetry_sdk_name="opentelemetry",telemetry_sdk_version="2.0.0"} 1
# HELP nodejs_eventloop_utilization Event loop utilization
# UNIT nodejs_eventloop_utilization 1
# TYPE nodejs_eventloop_utilization gauge
nodejs_eventloop_utilization 0.007937881753201396
# HELP nodejs_eventloop_time_total Cumulative duration of time the event loop has been in each state.
# UNIT nodejs_eventloop_time_total s
# TYPE nodejs_eventloop_time_total counter
nodejs_eventloop_time_total{nodejs_eventloop_state="active"} 0.03662290000014036
nodejs_eventloop_time_total{nodejs_eventloop_state="idle"} 4.551655800000001
# HELP nodejs_eventloop_delay_min Event loop minimum delay.
# UNIT nodejs_eventloop_delay_min s
# TYPE nodejs_eventloop_delay_min gauge
nodejs_eventloop_delay_min 0.010125312
# HELP nodejs_eventloop_delay_max Event loop maximum delay.
# UNIT nodejs_eventloop_delay_max s
# TYPE nodejs_eventloop_delay_max gauge
nodejs_eventloop_delay_max 0.025559039
# HELP nodejs_eventloop_delay_mean Event loop mean delay.
# UNIT nodejs_eventloop_delay_mean s
# TYPE nodejs_eventloop_delay_mean gauge
nodejs_eventloop_delay_mean 0.0163974037562724
# HELP nodejs_eventloop_delay_stddev Event loop standard deviation delay.
# UNIT nodejs_eventloop_delay_stddev s
# TYPE nodejs_eventloop_delay_stddev gauge
nodejs_eventloop_delay_stddev 0.0024891139470417734
# HELP nodejs_eventloop_delay_p50 Event loop 50 percentile delay.
# UNIT nodejs_eventloop_delay_p50 s
# TYPE nodejs_eventloop_delay_p50 gauge
nodejs_eventloop_delay_p50 0.016072703
# HELP nodejs_eventloop_delay_p90 Event loop 90 percentile delay.
# UNIT nodejs_eventloop_delay_p90 s
# TYPE nodejs_eventloop_delay_p90 gauge
nodejs_eventloop_delay_p90 0.017973247
# HELP nodejs_eventloop_delay_p99 Event loop 99 percentile delay.
# UNIT nodejs_eventloop_delay_p99 s
# TYPE nodejs_eventloop_delay_p99 gauge
nodejs_eventloop_delay_p99 0.024608767
# HELP v8js_gc_duration Garbage collection duration by kind, one of major, minor, incremental or weakcb.
# UNIT v8js_gc_duration s
# TYPE v8js_gc_duration histogram
v8js_gc_duration_count{v8js_gc_type="minor"} 1
v8js_gc_duration_sum{v8js_gc_type="minor"} 0.0030388000002130864
v8js_gc_duration_bucket{v8js_gc_type="minor",le="0.01"} 1
v8js_gc_duration_bucket{v8js_gc_type="minor",le="0.1"} 1
v8js_gc_duration_bucket{v8js_gc_type="minor",le="1"} 1
v8js_gc_duration_bucket{v8js_gc_type="minor",le="10"} 1
v8js_gc_duration_bucket{v8js_gc_type="minor",le="+Inf"} 1
# HELP v8js_memory_heap_limit Total heap memory size pre-allocated.
# UNIT v8js_memory_heap_limit By
# TYPE v8js_memory_heap_limit gauge
v8js_memory_heap_limit{v8js_heap_space_name="read_only_space"} 0
v8js_memory_heap_limit{v8js_heap_space_name="new_space"} 16777216
v8js_memory_heap_limit{v8js_heap_space_name="old_space"} 14929920
v8js_memory_heap_limit{v8js_heap_space_name="code_space"} 786432
v8js_memory_heap_limit{v8js_heap_space_name="shared_space"} 0
v8js_memory_heap_limit{v8js_heap_space_name="trusted_space"} 2097152
v8js_memory_heap_limit{v8js_heap_space_name="new_large_object_space"} 0
v8js_memory_heap_limit{v8js_heap_space_name="large_object_space"} 1261568
v8js_memory_heap_limit{v8js_heap_space_name="code_large_object_space"} 0
v8js_memory_heap_limit{v8js_heap_space_name="shared_large_object_space"} 0
v8js_memory_heap_limit{v8js_heap_space_name="trusted_large_object_space"} 0
# HELP v8js_memory_heap_used Heap Memory size allocated.
# UNIT v8js_memory_heap_used By
# TYPE v8js_memory_heap_used gauge
v8js_memory_heap_used{v8js_heap_space_name="read_only_space"} 0
v8js_memory_heap_used{v8js_heap_space_name="new_space"} 2786480
v8js_memory_heap_used{v8js_heap_space_name="old_space"} 14388744
v8js_memory_heap_used{v8js_heap_space_name="code_space"} 568704
v8js_memory_heap_used{v8js_heap_space_name="shared_space"} 0
v8js_memory_heap_used{v8js_heap_space_name="trusted_space"} 1906184
v8js_memory_heap_used{v8js_heap_space_name="new_large_object_space"} 0
v8js_memory_heap_used{v8js_heap_space_name="large_object_space"} 1240176
v8js_memory_heap_used{v8js_heap_space_name="code_large_object_space"} 0
v8js_memory_heap_used{v8js_heap_space_name="shared_large_object_space"} 0
v8js_memory_heap_used{v8js_heap_space_name="trusted_large_object_space"} 0
# HELP v8js_memory_heap_space_available_size Heap space available size.
# UNIT v8js_memory_heap_space_available_size By
# TYPE v8js_memory_heap_space_available_size gauge
v8js_memory_heap_space_available_size{v8js_heap_space_name="read_only_space"} 0
v8js_memory_heap_space_available_size{v8js_heap_space_name="new_space"} 5460816
v8js_memory_heap_space_available_size{v8js_heap_space_name="old_space"} 232656
v8js_memory_heap_space_available_size{v8js_heap_space_name="code_space"} 168480
v8js_memory_heap_space_available_size{v8js_heap_space_name="shared_space"} 0
v8js_memory_heap_space_available_size{v8js_heap_space_name="trusted_space"} 155584
v8js_memory_heap_space_available_size{v8js_heap_space_name="new_large_object_space"} 8388608
v8js_memory_heap_space_available_size{v8js_heap_space_name="large_object_space"} 0
v8js_memory_heap_space_available_size{v8js_heap_space_name="code_large_object_space"} 0
v8js_memory_heap_space_available_size{v8js_heap_space_name="shared_large_object_space"} 0
v8js_memory_heap_space_available_size{v8js_heap_space_name="trusted_large_object_space"} 0
# HELP v8js_memory_heap_space_physical_size Committed size of a heap space.
# UNIT v8js_memory_heap_space_physical_size By
# TYPE v8js_memory_heap_space_physical_size gauge
v8js_memory_heap_space_physical_size{v8js_heap_space_name="read_only_space"} 0
v8js_memory_heap_space_physical_size{v8js_heap_space_name="new_space"} 16777216
v8js_memory_heap_space_physical_size{v8js_heap_space_name="old_space"} 14929920
v8js_memory_heap_space_physical_size{v8js_heap_space_name="code_space"} 786432
v8js_memory_heap_space_physical_size{v8js_heap_space_name="shared_space"} 0
v8js_memory_heap_space_physical_size{v8js_heap_space_name="trusted_space"} 2097152
v8js_memory_heap_space_physical_size{v8js_heap_space_name="new_large_object_space"} 0
v8js_memory_heap_space_physical_size{v8js_heap_space_name="large_object_space"} 1261568
v8js_memory_heap_space_physical_size{v8js_heap_space_name="code_large_object_space"} 0
v8js_memory_heap_space_physical_size{v8js_heap_space_name="shared_large_object_space"} 0
v8js_memory_heap_space_physical_size{v8js_heap_space_name="trusted_large_object_space"} 0
