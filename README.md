
Fixed a case where telemetry state was not cleared after a failed refresh
Simplified how disabled controls are restored after loading
Fixed trace cleanup when a request is cancelled
Improved span handling when downstream calls fail
Removed duplicate attribute assignment from tracing logic
Added a fallback when trace context is missing
Simplified metric label construction
Fixed metric updates when a service returns no data
Fixed span status when an upstream request is rejected
Reduced repeated metric label construction
Improved cleanup for orphaned trace context
Fixed missing attributes on retried spans
Simplified exporter error handling
Fixed missing parent context when creating nested spans
Reduced duplicate metric updates during retries
Added a guard for invalid exporter responses
Simplified cleanup after a cancelled trace
Fixed an issue where failed exports left stale trace state
Improved span cleanup when a downstream call times out
