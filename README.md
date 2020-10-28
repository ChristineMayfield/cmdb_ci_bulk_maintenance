# cmdb_ci_bulk_maintenance

This is a ServiceNow global scoped application that allows you to create maintenance records from groups of CIs in the CMDB.

TABLES

Data Points

Question

Answer

Drop Down Choice


Maintenance Order

Maintenance Data


Maintenance Template

integrates with Location which integrates with

Service Record


Service Record

Maintenance Teamplate -> Data Point (related list)

Location -> CI (related list)

multiple Maintenance Order -> Maintenance Data (related list) -> Data Point


SWT Template

Planned SWT which generates a 

Site Walk Thru -> SWT Data (related list)

Walk Thru Template (related list) -> Data Point (related list)
