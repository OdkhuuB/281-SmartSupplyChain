# 281-SmartSupplyChain

A smart supply chain is an IOT based supply chain management system which is hosted on the cloud. It is designed to manage large-scale on-demand agriculture and 
food supply chains using IOT and cloud services. This supply chain consists of multiple sensor networks which could connect through network and can be installed and deployed in warehouses and trucks.

The sensors used are smart IOT based sensors which have a wireless connectivity. There multiple types of sensors which are installed at multiple places:
Warehouse IOT sensor networks
Smart-edge based IOT sensor networks on the shipping cargo
Smart IOT based wireless sensor networks which manage both warehouse sensor networks and cargo-based sensor networks
Each sensor network can have one or more smart cluster nodes which can communicate and control multiple smart sensor nodes.


The application for multiple tenants, this means that many users with different supply chain requirements can be created. The application allows all users to have different roles and privileges according to the roles assigned. Below are the user and their privileges:

Warehouse Admin User::
This user has complete access to all the warehouse, sensors, dashboards and orders. It can create new dashboard widgets according to their need and may keep it private to the user or share publicly. The warehouse admin can create orders, see past order details, monitor the delivery truck location, have a visual representation of how the warehouse and sensors are associated.

Infrastructure User::
This user is responsible for installing all the sensors in the warehouse and monitoring them. It can add, remove and edit sensors. Editing feature helps in changing status of the sensor, connecting it to simulated values or attach it to real thermostat or changing the units of measurement. It can also create new dashboard widgets according to the need and may keep it private to the user or share publicly. 

Cloud Admin::
This user is responsible for monitoring the health of the system. It can not add, remove or edit the sensors but can only monitor the status and responses and may need to take action in case of failure. It can also create new dashboard widgets according to the need and may keep it private to the user or share publicly.

Truck Driver::
This user is the cargo truck driver and is responsible for delivering the cargo to the customer. The truck user does not have access to the warehouse and sensor details but can only view the order details such as delivery address, date, etc. The dashboard for this user will be created by the warehouse admin.


In Smart Supply Chain cloud system, one of the main challenges is handling an increasing number of sensors in warehouses/trucks and increasing number of trucks and warehouses. 
Our Supply Chain Management System will addresses the scalability and load balancing by adding sensors in bulk from a simulated screen.
