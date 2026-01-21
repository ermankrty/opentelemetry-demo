
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
Fixed missing trace attributes on retry
Simplified metric export error handling
Fixed missing service metadata on exported traces
Reduced repeated span attribute lookups
Improved handling when the metrics exporter disconnects
Fixed trace propagation when context is partially missing
Improved span naming for background operations
Fixed metric tags when requests are retried
Removed an unnecessary trace context copy
Handled exporter shutdown without leaving pending spans
Fixed exporter retry timing after a temporary connection failure
Fixed missing resource attributes on exported spans
Reduced duplicate exporter calls during retries
Improved cleanup when an export batch is interrupted
Fixed missing span links during chained requests
Simplified metric aggregation for repeated events
Fixed missing trace attributes on downstream failures
Improved batching behavior for metric exports
Removed duplicate span status updates
Handled missing instrumentation scope values
Cleaned up exporter state after a shutdown failure
Fixed a case where trace attributes were dropped after retry
Improved cleanup when metric export is interrupted
Fixed a case where span status was not updated after exporter failure
Improved handling when a trace ends before all child spans complete
Fixed missing service attributes on retried exports
Simplified span event filtering before export
Improved cleanup when the trace exporter shuts down early
Fixed missing parent context when spans are retried
Improved cleanup after a failed metric flush
Fixed a case where metric labels were not cleared after exporter reset
Fixed trace sampling when parent context is unavailable
Reduced duplicate resource attribute processing
Improved span cleanup after an exporter timeout
Handled invalid metric points before export
Fixed propagation of baggage values across async operations
Reduced unnecessary span processing before export
Fixed trace context loss during async callbacks
Improved metric export handling for partial batches
Removed duplicate resource attributes before export
Improved shutdown behavior for pending telemetry
Fixed missing span attributes after context propagation
Improved metric batching when export volume spikes
Cleaned up retry state after exporter recovery
Fixed an issue where exporter state was not reset after a failed retry
Fixed an issue where exporter state was not reset after a failed retry
Fixed span status propagation after downstream errors
Improved metric export behavior when batches are partially full
Removed duplicate trace attribute assignment
Cleaned up exporter state after a cancelled flush
Fixed missing trace metadata after retry
Improved exporter handling for partial failures
Reduced duplicate span processing before flush
Fixed span linking when parent context is restored late
