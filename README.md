# Real_Estate_Prediction_Model
The Model aims to predict interest that will be shown in a given property on the NoBroker Dataset
Features	Data Type	Unique Values	Description
property_id	alphanumeric		
type	object	[BHK1,BHK2,BHK3,BHK4,BHK4Plus,RK1]	Describes what type of property it is where BHK stands Beddroom Hall and Kitchen and RK stands for Room Kitchen 
activation_date	object	DD-MM-YYYY HH:MM	Describes when the property has been activated on NoBroker website
bathroom	int64	[ 1,  2,  3,  4,  5,  0,  6,  7, 21, 22, 12, 10, 20,  8,  9]	Describes the number fo bathrooms present in the property 
floor	int64	[  3,   4,   0,   1,   2,   6,   5,   8,   7,   9,  10,  14, 17, 11,  19,  12,  13,  15,  16,  18,  25,  27,  20,  21, 123, 26, 24, 22,  28]	Describes the Floor on which the Property is on.
total_floor	float64		Describes the Total number of floors on the property.
furnishing	object	['SEMI_FURNISHED', 'NOT_FURNISHED', 'FULLY_FURNISHED']	Describes whether the property is fully, semi or unfurnished.
gym	int64	[1,0]	Here 1 indicates presence of gym and 0 indicates absence  of gym
latitude	float64		The field stores the Latitude in which the property is located.
longitude	float64		The field stores the Longitude in which the property is located.
lease_type	object	['FAMILY', 'ANYONE', 'BACHELOR', 'COMPANY']	Describes whether the property can be leased to anyone or only bachelor, family or company.
lift	int64	[1,0]	Here 1 indicates presence of lift and 0 indicates absence of lift
locality	object		The field stores the name of the locality in which the property is in.
parking	object	['BOTH', 'FOUR_WHEELER', 'TWO_WHEELER', 'NONE']	Describes whether there is parking space available as part of the property and wether the property has space for two wheeler, four wheeler or both.
property_age	int64		Describes the age of the property in years
property_size	int64		Describes the area of property in square footage
swimming_pool	int64	[1,0]	Here 1 indicates presence of swimming pool and 0 indicates absence  of swimming pool
pin_code	float64		The field stores the Pin Code of the Locality in which the property is situated in.
rent	int64		The Feature states the rent applicable for the property
deposit	int64		The Feature states the deposit applicable for the property
building_type	object	['AP', 'IF', 'IH']	The Feature describes the type of building where AP refers to Apartment, IF refers to Independent Flat and IH refers to as as Independent House 
![Uploading image.png…]()
