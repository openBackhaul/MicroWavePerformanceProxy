# MicroWavePerformanceProxy

### Location
The MicroWavePerformanceProxy belongs to the NetworkApplications.

### Description
The MWPP microservice acts as a proxy between the MicroWaveDeviceInventory and an external tool, e.g. APT (in which the performance data shall be stored).

The performance data is collected on demand when the external application is calling the /v1/provide-performance-data-of-link-endpoint service.  
The data is retrieved from the cache paths at the MicrowaveDeviceInventory and passed on to the external tool.  

The pre-defined set of attributes is provided in a simplified, almost linear structure, but without any translation.

### Relevance
The MicroWavePerformanceProxy fulfils a quality assurance task on the live network.

### Resources
- [Specification](./spec/)
- [TestSuite](./testing/)
- [Implementation](./server/)

### Comments
./.
