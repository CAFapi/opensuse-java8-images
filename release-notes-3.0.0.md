!not-ready-for-release!

#### Version Number
${version-number}

#### New Features
- **SCMOD-8516**: Extend the TLS/SSL cipher hardening of the Java base images to disallow TLSv1.1

#### Known Issues


#### Breaking Changes
- **SCMOD-8516**: Extend the TLS/SSL cipher hardening of the Java base images to disallow TLSv1.1
Weaker TLS algorithms are no longer supported by default.  See [here](src/main/docker/disableWeakTlsAlgorithms.patch) to view the list of algorithms which have been disabled.
