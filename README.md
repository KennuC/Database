# Database

## Objective

The objectives for this activity are to gain proficiency in managing both MySQL and MongoDB databases through hands-on tasks, including creating databases and tables/collections, inserting records/documents, and retrieving data.

### Skills Learned

- Database creation and management.
- Data insertion and retrieval.
- Use of SQL and NoSQL databases.

### Tools Used

- **MySQL**: For relational database management and querying.
- **MongoDB**: For NoSQL database management and querying.

## Steps

### MySQL

Show current database

![image](https://github.com/KennuC/MySQL/assets/131323586/c0ccfb0d-b9d1-47d3-a99e-0c04ca13c95e)

Creating a database.

![image](https://github.com/KennuC/MySQL/assets/131323586/dceb41cf-b509-40c9-bf7c-f35b2d0f9f13)

Creating a table of records that will contain vulnerability information from The Open Worldwide Application Security Project (OWASP) Top 10 for 2021 [OWASP Top 10](https://owasp.org/www-project-top-ten/).

![image](https://github.com/KennuC/MySQL/assets/131323586/850560b7-5c8c-48fc-b9d4-544772e6bbaf)

Describing the fields and attributes of the table.

![image](https://github.com/KennuC/MySQL/assets/131323586/bd35b276-875e-480f-90bb-489eb829c102)

Inserting first values into the table. 

![image](https://github.com/KennuC/MySQL/assets/131323586/c20d575e-7743-4bfe-8865-46c0bd53c993)

![image](https://github.com/KennuC/MySQL/assets/131323586/ab0f9678-caee-433f-bc5d-49252f3d294d)

Repeating for the following security risks.

![image](https://github.com/KennuC/MySQL/assets/131323586/be9611f6-789f-4459-80b1-3fdf38698f36)

Displaying database based on condition.

![image](https://github.com/KennuC/MySQL/assets/131323586/4fce8ba6-69b3-4774-8bff-5a2cfeb03f38)

![image](https://github.com/KennuC/MySQL/assets/131323586/4c3b4048-7a59-43f6-9653-be48e08c51e3)

### MongoDB

Show current database with `show dbs`.

![image](https://github.com/KennuC/Database/assets/131323586/d42e612d-e663-47df-8586-242549a8528b)

Creating now database with `use <DatabaseName`.

![image](https://github.com/KennuC/Database/assets/131323586/4c1fd8d7-2c6f-40d3-92fb-0f9eb634b96b)

Create a new collection under the database.

![image](https://github.com/KennuC/Database/assets/131323586/b3c0891e-3a69-4e6a-b07a-6e508a9412b0)

Again using the document OWASP Top 10-2021, create the database.

![image](https://github.com/KennuC/Database/assets/131323586/93094923-f839-44f6-8084-58ad4d6e399b)


This time will use `insertMany` to insert the rest of the data all at once.

![image](https://github.com/KennuC/Database/assets/131323586/60afd20b-dc1e-4f84-b97a-100fff4e5ba8)


Using `db.<collectionName>.find().pretty()` to show data from the database.

![image](https://github.com/KennuC/Database/assets/131323586/702b0c0d-f5f3-46c6-90a0-64147187cb77)

In the find field, specify a document to retrieve using `db.<collectionName>.find({"<field>":"<value>"}).pretty()`

![image](https://github.com/KennuC/Database/assets/131323586/a4e1239f-7f11-4503-a146-2cd3b8bef94a)

Retrieve all documents that match condition.

![image](https://github.com/KennuC/Database/assets/131323586/2e492db3-3c02-4296-8166-76ff2b9bef5e)


