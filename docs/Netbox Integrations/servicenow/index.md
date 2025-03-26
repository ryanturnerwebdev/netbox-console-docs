# ServiceNow Integration

The ServiceNow Integration supports the following NetBox object types:

- DCIM > Devices
- DCIM > Device Types
- DCIM > Manufacturers
- DCIM > Regions
- DCIM > Sites
- Tenancy > Tenants

## Object Mappings

<div style={{ maxWidth:'600px', width:'100%' }}>
	![service-now-object-map](../../images/integrations/service-now/service-now-object-map.png)
</div>

## Synchronization Options
Data can be synchronized in any of the following directions to accomodate many use cases

- NetBox > ServiceNow
- NetBox < ServiceNow
- NetBox \<\> ServiceNow

#### Bulk Updates
Bulk updates can be run manually or on a schedule to synchronize all data between ServiceNow and NetBox

#### Real-time Updates
Changes in NetBox or ServiceNow can trigger updates in the corresponding system with an automatic real time synchronization
