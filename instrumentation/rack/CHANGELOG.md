# Release History: opentelemetry-instrumentation-rack

### v0.14.0 / 2021-02-03

* BREAKING CHANGE: Replace getter and setter callables and remove rack specific propagators 

* ADDED: Replace getter and setter callables and remove rack specific propagators 
* ADDED: Add untraced endpoints config to rack middleware 

### v0.13.0 / 2021-01-29

* FIXED: Only include user agent when present 

### v0.12.0 / 2020-12-24

* (No significant changes)

### v0.11.0 / 2020-12-11

* FIXED: Copyright comments to not reference year 

### v0.10.1 / 2020-12-09

* FIXED: Rack current_span 

### v0.10.0 / 2020-12-03

* (No significant changes)

### v0.9.0 / 2020-11-27

* BREAKING CHANGE: Add timeout for force_flush and shutdown 

* ADDED: Instrument rails 
* ADDED: Add timeout for force_flush and shutdown 

### v0.8.0 / 2020-10-27

* BREAKING CHANGE: Move context/span methods to Trace module 
* BREAKING CHANGE: Remove 'canonical' from status codes 

* FIXED: Move context/span methods to Trace module 
* FIXED: Remove 'canonical' from status codes 

### v0.7.0 / 2020-10-07

* FIXED: Remove superfluous file from Rack gem 
* DOCS: Added README for Rack Instrumentation 
* DOCS: Standardize toplevel docs structure and readme 

### v0.6.0 / 2020-09-10

* (No significant changes)
