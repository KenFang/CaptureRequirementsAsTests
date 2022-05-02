# Capturing Requirements As Tests
Capturing Requirements As Tests<br />
thread 'subscribe_returns_a_200_for_valid_from_data' panicked at 'assertion failed: `(left == right)`<br />
  left: `200`,<br />
 right: `404`', tests/health_check.rs:59:5<br />
 <br />
 thread 'subscribe_returns_a_400_when_data_is_missing' panicked at 'assertion failed: `(left == right)`<br />
  left: `400`,<br />
 right: `404`: The API did not fail with 400 Bad Request when the payload was missing the email.', tests/health_check.rs:85:9<br />
