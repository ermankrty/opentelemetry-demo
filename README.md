
Fixed a case where telemetry state was not cleared after a failed refresh
Simplified how disabled controls are restored after loading
Fixed trace cleanup when a request is cancelled
Improved span handling when downstream calls fail
Removed duplicate attribute assignment from tracing logic
Added a fallback when trace context is missing
Simplified metric label construction
Fixed metric updates when a service returns no data
