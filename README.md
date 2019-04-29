# golang-ucp-sim

Only supports the following operations:
* Alert - always returns success
* Submit Short Message - only returns failure when max window size is reached. Current implementation doesn't support delivery receipt yet.
* Session Management - always returns success

# Environment

* UCP_SIM_SILENT - disables logging
* UCP_SIM_CONF_DIR - config directory

# How to run
1. go get github.com/bryan-t/golang-ucp-sim
2. go run github.com/bryan-t/golang-ucp-sim

Note: implemented using Go Modules.