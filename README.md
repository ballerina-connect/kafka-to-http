# Ballerina Connect: Kafka → HTTP
This connector uses Ballerina’s cloud-native capabilities to reliably move messages from Kafka topics to HTTP endpoints. It includes:

Batching: Can send records in batches (arrays of records) to HTTP endpoints
Retries: Automatic retry on failures based on http status code and error codes in the response body. 
Error Handling: Granular error capture and custom recovery.
Logging & Analytics: Built-in observability for throughput and error rates.
Dead-Letter Support: Offload problematic messages for manual inspection.
Perfect for building robust, event-driven microservices that forward Kafka data into HTTP-based systems, APIs, or microservices.
