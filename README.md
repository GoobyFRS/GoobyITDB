# GoobyITDB

JSON and YAML based CMDB Platform with GoobyDesk Integration.

### Brainstorm

- Python3 Flask App running on port 8001
- JSON, YAML, and CSV data storage
- CRUD entries

**Server Database**

- UUID (SVRDB-a1b2c3d4e5f6)
- Friendly Name (Example Host)
- Hostname/FQDN (host.example.org)
- IP Address (100.68.0.2)
- MAC Address (a1:b2:c3:d4:e5:f6)
- Serial Number
- OS Version
- Type (VM, Physical)
- Location

**Data Circuits Database**

- UUID (CKTDB-a1b2c3d4e5f6)
- Primary Data Circuit ID
- Circuit Type
- Circuit Medium
- Circuit Size
- Last Mile Provider
- Last Mile Circuit ID
- Support Number
- Account Number
- Account Secret
- Account Holder
- Account Billing Address
- Service Address
- Location

**Voice Circuits Database**

- UUID (VCKTDB-a1b2c3d4e56f)
- Carrier
- Service Type
- Assigned Phone Number
- Support Number
- Account Number
- Account Secret
- Account Holder
- Account Billing Address
- Service Address
- Location

**Workstation Database**

- UUID (PCDB-a1b2c3d4e5f6)
- Hostname
- Serial Number
- Device Type
- Brand
- Model
- OS Version
- Purchase Date
- Assigned User
- Location