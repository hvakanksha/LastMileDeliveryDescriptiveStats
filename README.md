# LastMileDeliveryDescriptiveStats

An E-Commerce courier company has hired your consulting firm to review and improve its last mile delivery operations. While the firm already uses routing optimization software to find the shortest delivery routes for all their drivers, they re now looking to glean more insights from the data they track on last mile delivery operations. They've generated a few ideas about characteristics of the delivery operation itself and so they' ve sent you a data pull of recent deliveries in the file named, "lastMileDeliveryTimes.csv". In this .csv file, you'll find a dataset that describes a number (N=1000) of home deliveries made by the company. Each row contains the following data about a single home delivery event:

● DeliveryTime: the time between courier departure time from the E-Commerce distribution center on the morning of the delivery and arrival time at the customer location (measured in hours)

●NumberPackagesDelivered: the number of package deliveries that the courier had to make that day on their route (measured as a packages count)
● Temperature: The temperature on that day; this accounts for the weather's possible impact (measured in degrees F)
● DistanceToCityCenterFromDC: The distance from the E-Commerce distribution center to the nearest major city center; assume that this city is where the majority of deliveries are being made (measured in miles)
● DriverExperience: The amount of time that the courier has worked for the organization (measured in years)
● DriverSafetyIncidents: The number of poor decisions made by the driver resulting in unsafe vehicle operation; the time frame is the driver s employment term (measured as an incidents count)
●VehicleType: the engine type of the delivery vehicle; either Electric or Gas. Since the electric delivery vehicles are still relatively new technology, there is a possibility that reliability of the vehicle itself could be a concern.
●FulfillmentChannel: the source of inventory for the home delivery; either SFDCor SFS. Measures proximity of the origin to the destination.
