# Graylog Inputs Content Pack

## GELF HTTP

```
bind_address: 0.0.0.0
decompress_size_limit: 8388608
enable_cors: true
idle_writer_timeout: 60
max_chunk_size: 65536
number_worker_threads: 4
override_source: <empty>
port: 12202
recv_buffer_size: 1048576
tcp_keepalive: false
tls_cert_file: <empty>
tls_client_auth_cert_file: <empty>
tls_enable: false
tls_key_file: <empty>
tls_key_password: ********
```

## GELF TCP

```
bind_address: 0.0.0.0
decompress_size_limit: 8388608
enable_cors: true
idle_writer_timeout: 60
max_chunk_size: 65536
number_worker_threads: 4
override_source: <empty>
port: 12201
recv_buffer_size: 1048576
tcp_keepalive: false
tls_cert_file: <empty>
tls_client_auth_cert_file: <empty>
tls_enable: false
tls_key_file: <empty>
tls_key_password: ********
```

## GELF UDP

```
bind_address: 0.0.0.0
decompress_size_limit: 8388608
number_worker_threads: 4
override_source: <empty>
port: 12201
recv_buffer_size: 1048576
```

## Syslog TCP

```
allow_override_date: true
bind_address: 0.0.0.0
expand_structured_data: false
force_rdns: false
max_message_size: 2097152
number_worker_threads: 4
override_source: <empty>
port: 10514
recv_buffer_size: 1048576
store_full_message: false
tcp_keepalive: false
tls_cert_file: <empty>
tls_client_auth: disabled
tls_client_auth_cert_file: <empty>
tls_enable: false
tls_key_file: <empty>
tls_key_password: ********
use_null_delimiter: false
```

## Syslog UDP

```
allow_override_date: true
bind_address: 0.0.0.0
expand_structured_data: false
force_rdns: false
number_worker_threads: 4
override_source: <empty>
port: 10514
recv_buffer_size: 262144
store_full_message: false
```
