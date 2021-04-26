# PrPaPublic

PrPa accomodates requirements for the multiple entity types that will be populating the final DB.
Including,
(Iteration 1)
- CRM Entity Type
  - Client ID ( 🔑 )
  - Client Address
  - Client First Name
  - Client Last Name
  - Client e-mail
  - Client Phone Number
  - Client Preferred calling time (select from morning afternoon evening and then assign hours based off of the results)
  ~ Method Client was acquired by
- Employee Entity Type
  - Employee ID ( 🔑 )
  - Employee First Name
  - Employee Last Name
  - Employee Role
- Project Entity Type
  - Project ID ( 🔑 )
  - Marketer ID ( 🗝️ )
  - Client ID ( 🗝️ )
  - Status (Won, Lost, Pending)
  - Interior Jobs
  - Exterior Jobs
  - Price Rate
  - Total Price
- Job Entity Type
  - Job Name ( 🔑 )
  - Job price calculation type 
  - Length
  - Width / Height ( aliasing is used ) 
  - 
All ID's will be assigned utilizing the GUID system. The different views and user-defined functions will present the data in the most accesible fashion to different users.
