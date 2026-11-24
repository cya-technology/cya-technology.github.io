## Inventory Transfers – Offshore Vendor to In-Transit and Physical Warehouse

### Overview

Designed an inventory movement process in SAP Business One to track goods moving from an offshore supplier location to an in-transit warehouse and ultimately into the company's physical warehouse once received at the facility.

The process uses SAP Business One Inventory Transfer documents to maintain accurate warehouse-level inventory balances, provide visibility into goods in transit, and establish an auditable record of inventory movements throughout the supply chain.

### Business Process

The inventory movement process consists of two sequential warehouse transfers:

**1. Offshore Vendor to In-Transit Warehouse**
- Created an Inventory Transfer document to move inventory from the Offshore Vendor warehouse (OW) to the In-Transit warehouse (IT).
- Recorded the item number, item description, and transferred quantity.
- Updated warehouse inventory balances to reflect goods designated as in transit.
- Maintained visibility of inventory that had shipped but had not yet arrived at the receiving facility.

**2. In-Transit Warehouse to Physical Warehouse**
- Created a second Inventory Transfer document once the shipment arrived at the facility.
- Transferred inventory from the In-Transit warehouse (IT) to the Main Physical Warehouse (WH1).
- Updated on-hand inventory quantities to reflect the physical receipt of goods.
- Made received inventory available for subsequent operational activities, including picking, fulfillment, and distribution.

### SAP Business One Functionality Demonstrated

- **Inventory Transfer Documents:** Used to record and track warehouse-to-warehouse inventory movements.
- **Warehouse Management:** Maintained separate inventory balances across offshore, in-transit, and physical warehouse locations.
- **Inventory Visibility:** Provided visibility into inventory quantities at each stage of the supply chain.
- **Transaction History:** Maintained document-level records of inventory movements for traceability and auditing.
- **Inventory Reconciliation:** Verified that quantities transferred between warehouses were accurately reflected in inventory balances.

### Business Value

- Improved visibility into inventory throughout the international supply chain.
- Established a structured process for tracking goods in transit.
- Reduced the risk of prematurely recognizing shipped inventory as physically available stock.
- Improved inventory accountability through documented warehouse transfers.
- Supported more accurate inventory planning and warehouse operations.

### Technologies & Tools

- SAP Business One
- Inventory Transfer Documents
- Warehouse Management
- Inventory Reporting
- Supply Chain and Inventory Controls
