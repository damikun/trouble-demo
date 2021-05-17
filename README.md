<br />
<p align="center">
  <!-- <a href="https://demo.troubledev.com">
  <img src="images/toast.gif" alt="Trouble-Demo" >
  </a> -->

  <h3 align="center">Trouble</h3>
   <h3 align="center">
    <a href="https://demo.troubledev.com">Online Demo</a>
  </h3>
</p>

**What is it?**

Trouble is system base for factory-oriented projects. It provides various functionality as tracking planning and managing industrial and maintenance-related projects. It helps to collaborate and control your project across the industrial environment.

**What is use cases?**
- Read and collect data from the production plant and process static analytics and anomaly detection. Generate maintenance events (jobs/issues)  based on results.
- Manage production assets, documentation and related files in one place.
- Use cron time period or event schedule to generate maintenance or operational job.
- Manage overview of pending jobs under the various project (plants/rooms/environment)
- Connect 3-part application as event listeners over WebHooks
- Provides multiple project roles to collaborate with external suppliers.

**Application examples:**
- Collecting data (Alarms, QA photos,  measurement values, etc..)
- Order transfer and managment between APP <> PLCs
- Store and send printing job to industrial label printers
- Hold internal EAN or QR Code and provide tracking information for pallet transfer or storage.
- Automatic SW backup module
- Custom data visualization
- New field project integration task management
- Maintenance managment

**API Interface**
Trouble use by default graphql endpoint but also contains some basic REST API, which can be extended by concrete application needs in case graphql is not suitable.

- The system is designed to run on-premise or in the cloud. 
- Compatible with MS SQL, PostgresSQL, and MySQL. The main database can be chosen.
- Data analytics and logs are stored in the elastic database.
- The frontend is built using React, backend use .net Core
- The app contains various services  Frontend, Backend, Elastic, DB, Fileserver, Redis, etc..

Dalibor Kundrat
