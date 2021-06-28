# Case Management system
A system to be able to handle requests/issuses from users/customers

# Insperation
- Lime technologies: https://www.lime-technologies.se

# Reqruirements
- Should follow the foundation of ITIL. 
- Should be able to track statics
- Should have a dashboard with goals
- Should have support for checklists
- Should be able to send links to cases to other users
- Users should be able to create theirs own task-lists
- Should have email-integration
- Should be able to import users to the system by AD-integration
- Should support SSO (Single Sign-On)
- Should support username / password
- Should be responsive (Support mobile and desktops)
- Should support, MSSQL / MySQL / PostgreSQL. Mongodb?
- Role-based access control (RBAC)
- Should be easy to update ([db-migrate](https://db-migrate.readthedocs.io/en/latest/))
- Should be able to get a users history of requests
- Should be able to get a assignees latests requests handled
- Should be fast to search (Elastic-Search)
- Should be fast to startup
- Should be able to send invoices
- Should be able to create their own attributes / meta-data
- Backend should be written in C++, with own written JSON parser, HTTP-server, networkcode and thread handler
- Frontend should be written with assistance of the framework Angular or Svelte
- Communication between C++ and frontend shall be done with RestAPI or GraphQL

# Customer Card
- Should contain:
    - Firstname
    - Surname
    - Middle name
    - Title (mr, ms, mrs)
    - Username
    - Password
    - Work title
    - Nickname
    - Address
    - State
    - Zip
    - Country
    - Preferred contact method (Email, phone, sms)
    - Phone number
    - Email
    - Notes about customer
    - Special notes about customer
    - Roles
    - Attachments

# SLA
   - Contract
        - Start date
        - End date
        - Renewal date
        - Reminder email on renewal or x days before renewal date
   - Scope
        - From : time
        - To : time
        - All days.
   - Clocks
        - Response time
            - Total time 
        - Resolve / fix time
            - Total time
        - Escalation
            - Type (Response time Resolve time)
            - Percent 
            - Level (?)
            - Mail to send
   - Attachments
   - Notes

# Services
   - Name
   - Description
   - Image
   - Portfolio status
   - Owner
   - Service category class (?)
   - Sector / Department
   - Limits
        - Customers
        - Case types
        - Support groups
   - Planned publication (date)
   - Real publication (date)
   - Sub services

# Checklists

# Configuration Items
- CI-number
- Name
- Type (Own created)
- Description
- Owner
- Contact
- Used by
- Status
- Installed date
- Class 
- Placed
- Product number
- Manufacture
- Model
- Retailer
- Maintenance manager
- Serial number
- IP
- Attributes
- Attachments
- Related cases

# Organization management
(Should be a bit like customer card)

# Knowledge management

# Case card
- Should contain:
    - Case-number
    - Major-incident
    - Customer/s
    - Case type (Incident, request, change, release, problem)
    - Income from a source (Mail, Phone, Self-service, Integration) (Should be able to create your own sources)
    - Service
    - Specification / Category (Should be able to create own)
    - Description
    - Priority
    - Impact
    - Urgency
    - Assignee
    - Tracker
    - Status
    - Occurred (Date and time)
    - History
        - Public notes
        - Private notes
        - Should contain
            - Created
            - Created By
            - Content
    - Attachments
    - Related to other cases
    - Checklist
    - SLA
    - Solution
