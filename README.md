# AirBnB MongoDB Analysis


## Data 
URL LINK: [Athens, Greece]("http://insideairbnb.com/get-the-data)
- Originally in CSV form. 
- [Link to data itself](data/listings.csv)




## Queries

1. Just pulling the top 2 listings.
- Query: `db.listings.find().limit(2)`
- Result: 
```
{ "_id" : ObjectId("624b14fc21f2b8ef609fc805"), "id" : 31155, "listing_url" : "https://www.airbnb.com/rooms/31155", "scrape_id" : NumberLong("20211223003724"), "last_scraped" : "2021-12-23", "name" : "sleep on sailing boat", "description" : "Sleeping on a boat is the ultimate glamping experience.<br />There is a sense of adventure to it.<br />The berth (bed) is very comfortable.<br />You can have breakfast on the boat <br />No evening cooking but you can take out food to enjoy on the boat.<br /><br /><b>The space</b><br />on beautiful island of Aigina, 30 minutes from Athens, live a great adventure to spend the night on a sailing boat.  The boat is a small, 35 feet, canadian flag jeanneau.  Your cabin is the front cabine, you share the bathroom with me, the owner.  Aigina has beautiful beaches, is very picturest, many tavernas.  The cabin has a berth for two persons, I prefer single.  Can give price for more than 3 days.  I have just spent 45 days at sea, I need rest from sailing; this is a great chance for someone who does not really want to sail, but would love the experience of living on boat. I might not be on Aigina, I am not there ALL of the time, sometimes the boat can be on other islands. ALL islands of Greece are ", "neighborhood_overview" : "", "picture_url" : "https://a0.muscache.com/pictures/531153/542d3eb4_original.jpg", "host_id" : 133845, "host_url" : "https://www.airbnb.com/users/show/133845", "host_name" : "Irene", "host_since" : "2010-05-28", "host_location" : "On board Amzerzo.", "host_about" : "I work for one of Greece's major Charter Company.\nI am sailor, love offshore sailing.\nI have been \"a live aboard\" since 10 years.\nI am Canadian, lived in France most of my adult live. \nThe boat is in Greece, moving to different Islands.  \nWhen you will be on board, the boat will not be moving.\nI love cooking, great wine, people, places, stories, all music, opera, walking, swimming, and much more.\nGUYS : Please, I am not looking for romance.", "host_response_time" : "N/A", "host_response_rate" : "N/A", "host_acceptance_rate" : "N/A", "host_is_superhost" : "f", "host_thumbnail_url" : "https://a0.muscache.com/im/pictures/user/bf409287-66f2-4bf9-b309-ef61fd503c2d.jpg?aki_policy=profile_small", "host_picture_url" : "https://a0.muscache.com/im/pictures/user/bf409287-66f2-4bf9-b309-ef61fd503c2d.jpg?aki_policy=profile_x_medium", "host_neighbourhood" : "", "host_listings_count" : 1, "host_total_listings_count" : 1, "host_verifications" : "['email', 'phone', 'reviews', 'jumio', 'offline_government_id', 'government_id', 'work_email']", "host_has_profile_pic" : "t", "host_identity_verified" : "t", "neighbourhood" : "", "neighbourhood_cleansed" : "ΚΕΡΑΜΕΙΚΟΣ", "neighbourhood_group_cleansed" : "", "latitude" : 37.97962, "longitude" : 23.71589, "property_type" : "Private room in rental unit", "room_type" : "Private room", "accommodates" : 1, "bathrooms" : "", "bathrooms_text" : "1 shared bath", "bedrooms" : 1, "beds" : 1, "amenities" : "[\"Long term stays allowed\", \"First aid kit\", \"Essentials\", \"Beach essentials\", \"Extra pillows and blankets\", \"Fire extinguisher\", \"Bed linens\", \"Dishes and silverware\", \"Waterfront\", \"Coffee maker\"]", "price" : "$39.00", "minimum_nights" : 1, "maximum_nights" : 730, "minimum_minimum_nights" : 1, "maximum_minimum_nights" : 1, "minimum_maximum_nights" : 730, "maximum_maximum_nights" : 730, "minimum_nights_avg_ntm" : 1, "maximum_nights_avg_ntm" : 730, "calendar_updated" : "", "has_availability" : "f", "availability_30" : 0, "availability_60" : 0, "availability_90" : 0, "availability_365" : 0, "calendar_last_scraped" : "2021-12-23", "number_of_reviews" : 0, "number_of_reviews_ltm" : 0, "number_of_reviews_l30d" : 0, "first_review" : "", "last_review" : "", "review_scores_rating" : "", "review_scores_accuracy" : "", "review_scores_cleanliness" : "", "review_scores_checkin" : "", "review_scores_communication" : "", "review_scores_location" : "", "review_scores_value" : "", "license" : "", "instant_bookable" : "f", "calculated_host_listings_count" : 1, "calculated_host_listings_count_entire_homes" : 0, "calculated_host_listings_count_private_rooms" : 1, "calculated_host_listings_count_shared_rooms" : 0, "reviews_per_month" : "" }
{ "_id" : ObjectId("624b14fc21f2b8ef609fc7ff"), "id" : 10595, "listing_url" : "https://www.airbnb.com/rooms/10595", "scrape_id" : NumberLong("20211223003724"), "last_scraped" : "2021-12-23", "name" : "96m2, 3BR, 2BA, Metro, WI-FI etc...", "description" : "Athens Furnished Apartment No6 is 3-bedroom apartment with 2-bathrooms<br />-excellent located <br />-close to metro station, <br />-lovely, <br />-very clean <br />with all the facilities that you will need, nice balcony, excellent Wi-Fi, cable tv, fully air conditioned…<br /><br /><b>The space</b><br />Athens Furnished Apartment No6 is an excellent located, close to metro, lovely, very clean 3-bedroom apartment with 2-bathrooms with all the facilities that you will need and balcony. It is on the 2nd floor but do not worry because there is elevator in the building. Fully equipped kitchen with everything you need to prepare your lunch/dinner. Living room to relax and enjoy a movie or a sport event. 2 Clean nice bathrooms. For more than 6 people there is a sofa/bed. <br />Apartment No6 has everything you will need.<br />1st Bedroom – Double bed<br />2nd Bedroom – 2 single beds<br />3rd Bedroom – 2 single beds<br />-Telephone line for incoming calls or to call us if you need something.<b", "neighborhood_overview" : "Ampelokipi district is nice multinational and safe area with excellent transportation system. Staying in Ampelokipi area you have the safety you need when you are in a foreign country. Everything you need for your vacations you can find it next to the apartment: Shops, Supermarkets, Restaurants, Bars, Coffee shops, Bakeries, Groceries, 24 hours kiosk, Pharmacies, Hair Salon, Banks, Travel Agents, Cinemas, summer cinemas and many more... <br />Also every Saturday there is a Farmers market 2-3 minutes away from the apartment.<br /><br />Athens Classical Marathon route pass from the area.<br />In the area you will also find Athens Concert Hall (Megaron Mousikis), National Sculpture Gallery, Badminton Theater (international shows), the biggest urban park in Athens, ministries, universities, embassies, hospitals and more…", "picture_url" : "https://a0.muscache.com/pictures/f7e19a44-5afe-4558-8b5d-2f8186723721.jpg", "host_id" : 37177, "host_url" : "https://www.airbnb.com/users/show/37177", "host_name" : "Emmanouil", "host_since" : "2009-09-08", "host_location" : "Athens, Attica, Greece", "host_about" : "Athens Quality Apartments is a company started back at 2007 and now we have 8 apartments. Our goal is to offer to travelers beautiful apartments with professional service only in good location and with all the necessary amenities.\n", "host_response_time" : "within an hour", "host_response_rate" : "100%", "host_acceptance_rate" : "99%", "host_is_superhost" : "t", "host_thumbnail_url" : "https://a0.muscache.com/im/pictures/user/859c1eda-f858-414e-9984-165bd4575b3f.jpg?aki_policy=profile_small", "host_picture_url" : "https://a0.muscache.com/im/pictures/user/859c1eda-f858-414e-9984-165bd4575b3f.jpg?aki_policy=profile_x_medium", "host_neighbourhood" : "Ambelokipi", "host_listings_count" : 6, "host_total_listings_count" : 6, "host_verifications" : "['email', 'phone', 'reviews', 'jumio', 'government_id']", "host_has_profile_pic" : "t", "host_identity_verified" : "t", "neighbourhood" : "Athens, Attica, Greece", "neighbourhood_cleansed" : "ΑΜΠΕΛΟΚΗΠΟΙ", "neighbourhood_group_cleansed" : "", "latitude" : 37.98863, "longitude" : 23.76527, "property_type" : "Entire rental unit", "room_type" : "Entire home/apt", "accommodates" : 8, "bathrooms" : "", "bathrooms_text" : "2 baths", "bedrooms" : 3, "beds" : 5, "amenities" : "[\"Long term stays allowed\", \"Hot water\", \"Shower gel\", \"Ethernet connection\", \"Iron\", \"Central heating\", \"Oven\", \"Coffee maker\", \"Extra pillows and blankets\", \"Free street parking\", \"Shampoo\", \"Single level home\", \"Air conditioning\", \"Dedicated workspace\", \"Cooking basics\", \"Wifi\", \"Essentials\", \"High chair\", \"Refrigerator\", \"Electric stove\", \"Bed linens\", \"43\\\" HDTV\", \"Patio or balcony\", \"Hangers\", \"Host greets you\", \"Dishwasher\", \"Kitchen\", \"Crib\", \"Microwave\", \"Dishes and silverware\", \"Laundromat nearby\", \"Washer\", \"Hair dryer\"]", "price" : "$70.00", "minimum_nights" : 1, "maximum_nights" : 1125, "minimum_minimum_nights" : 2, "maximum_minimum_nights" : 8, "minimum_maximum_nights" : 1125, "maximum_maximum_nights" : 1125, "minimum_nights_avg_ntm" : 2.3, "maximum_nights_avg_ntm" : 1125, "calendar_updated" : "", "has_availability" : "t", "availability_30" : 21, "availability_60" : 51, "availability_90" : 81, "availability_365" : 114, "calendar_last_scraped" : "2021-12-23", "number_of_reviews" : 32, "number_of_reviews_ltm" : 7, "number_of_reviews_l30d" : 0, "first_review" : "2011-05-20", "last_review" : "2021-09-24", "review_scores_rating" : 4.77, "review_scores_accuracy" : 4.81, "review_scores_cleanliness" : 4.75, "review_scores_checkin" : 4.84, "review_scores_communication" : 4.84, "review_scores_location" : 4.5, "review_scores_value" : 4.66, "license" : 957568, "instant_bookable" : "t", "calculated_host_listings_count" : 6, "calculated_host_listings_count_entire_homes" : 6, "calculated_host_listings_count_private_rooms" : 0, "calculated_host_listings_count_shared_rooms" : 0, "reviews_per_month" : 0.25 }
```

<br>

2. Pulling the top 10 listings, prettified.
- Query: `db.listings.find().pretty().limit(10)`
- Result:
```
{
	"_id" : ObjectId("624b14fc21f2b8ef609fc805"),
	"id" : 31155,
	"listing_url" : "https://www.airbnb.com/rooms/31155",
	"scrape_id" : NumberLong("20211223003724"),
	"last_scraped" : "2021-12-23",
	"name" : "sleep on sailing boat",
	"description" : "Sleeping on a boat is the ultimate glamping experience.<br />There is a sense of adventure to it.<br />The berth (bed) is very comfortable.<br />You can have breakfast on the boat <br />No evening cooking but you can take out food to enjoy on the boat.<br /><br /><b>The space</b><br />on beautiful island of Aigina, 30 minutes from Athens, live a great adventure to spend the night on a sailing boat.  The boat is a small, 35 feet, canadian flag jeanneau.  Your cabin is the front cabine, you share the bathroom with me, the owner.  Aigina has beautiful beaches, is very picturest, many tavernas.  The cabin has a berth for two persons, I prefer single.  Can give price for more than 3 days.  I have just spent 45 days at sea, I need rest from sailing; this is a great chance for someone who does not really want to sail, but would love the experience of living on boat. I might not be on Aigina, I am not there ALL of the time, sometimes the boat can be on other islands. ALL islands of Greece are ",
	"neighborhood_overview" : "",
	"picture_url" : "https://a0.muscache.com/pictures/531153/542d3eb4_original.jpg",
	"host_id" : 133845,
	"host_url" : "https://www.airbnb.com/users/show/133845",
	"host_name" : "Irene",
	"host_since" : "2010-05-28",
	"host_location" : "On board Amzerzo.",
	"host_about" : "I work for one of Greece's major Charter Company.\nI am sailor, love offshore sailing.\nI have been \"a live aboard\" since 10 years.\nI am Canadian, lived in France most of my adult live. \nThe boat is in Greece, moving to different Islands.  \nWhen you will be on board, the boat will not be moving.\nI love cooking, great wine, people, places, stories, all music, opera, walking, swimming, and much more.\nGUYS : Please, I am not looking for romance.",
	"host_response_time" : "N/A",
	"host_response_rate" : "N/A",
	"host_acceptance_rate" : "N/A",
	"host_is_superhost" : "f",
	"host_thumbnail_url" : "https://a0.muscache.com/im/pictures/user/bf409287-66f2-4bf9-b309-ef61fd503c2d.jpg?aki_policy=profile_small",
	"host_picture_url" : "https://a0.muscache.com/im/pictures/user/bf409287-66f2-4bf9-b309-ef61fd503c2d.jpg?aki_policy=profile_x_medium",
	"host_neighbourhood" : "",
	"host_listings_count" : 1,
	"host_total_listings_count" : 1,
	"host_verifications" : "['email', 'phone', 'reviews', 'jumio', 'offline_government_id', 'government_id', 'work_email']",
	"host_has_profile_pic" : "t",
	"host_identity_verified" : "t",
	"neighbourhood" : "",
	"neighbourhood_cleansed" : "ΚΕΡΑΜΕΙΚΟΣ",
	"neighbourhood_group_cleansed" : "",
	"latitude" : 37.97962,
	"longitude" : 23.71589,
	"property_type" : "Private room in rental unit",
	"room_type" : "Private room",
	"accommodates" : 1,
	"bathrooms" : "",
	"bathrooms_text" : "1 shared bath",
	"bedrooms" : 1,
	"beds" : 1,
	"amenities" : "[\"Long term stays allowed\", \"First aid kit\", \"Essentials\", \"Beach essentials\", \"Extra pillows and blankets\", \"Fire extinguisher\", \"Bed linens\", \"Dishes and silverware\", \"Waterfront\", \"Coffee maker\"]",
	"price" : "$39.00",
	"minimum_nights" : 1,
	"maximum_nights" : 730,
	"minimum_minimum_nights" : 1,
	"maximum_minimum_nights" : 1,
	"minimum_maximum_nights" : 730,
	"maximum_maximum_nights" : 730,
	"minimum_nights_avg_ntm" : 1,
	"maximum_nights_avg_ntm" : 730,
	"calendar_updated" : "",
	"has_availability" : "f",
	"availability_30" : 0,
	"availability_60" : 0,
	"availability_90" : 0,
	"availability_365" : 0,
	"calendar_last_scraped" : "2021-12-23",
	"number_of_reviews" : 0,
	"number_of_reviews_ltm" : 0,
	"number_of_reviews_l30d" : 0,
	"first_review" : "",
	"last_review" : "",
	"review_scores_rating" : "",
	"review_scores_accuracy" : "",
	"review_scores_cleanliness" : "",
	"review_scores_checkin" : "",
	"review_scores_communication" : "",
	"review_scores_location" : "",
	"review_scores_value" : "",
	"license" : "",
	"instant_bookable" : "f",
	"calculated_host_listings_count" : 1,
	"calculated_host_listings_count_entire_homes" : 0,
	"calculated_host_listings_count_private_rooms" : 1,
	"calculated_host_listings_count_shared_rooms" : 0,
	"reviews_per_month" : ""
}
{
	"_id" : ObjectId("624b14fc21f2b8ef609fc7ff"),
	"id" : 10595,
	"listing_url" : "https://www.airbnb.com/rooms/10595",
	"scrape_id" : NumberLong("20211223003724"),
	"last_scraped" : "2021-12-23",
	"name" : "96m2, 3BR, 2BA, Metro, WI-FI etc...",
	"description" : "Athens Furnished Apartment No6 is 3-bedroom apartment with 2-bathrooms<br />-excellent located <br />-close to metro station, <br />-lovely, <br />-very clean <br />with all the facilities that you will need, nice balcony, excellent Wi-Fi, cable tv, fully air conditioned…<br /><br /><b>The space</b><br />Athens Furnished Apartment No6 is an excellent located, close to metro, lovely, very clean 3-bedroom apartment with 2-bathrooms with all the facilities that you will need and balcony. It is on the 2nd floor but do not worry because there is elevator in the building. Fully equipped kitchen with everything you need to prepare your lunch/dinner. Living room to relax and enjoy a movie or a sport event. 2 Clean nice bathrooms. For more than 6 people there is a sofa/bed. <br />Apartment No6 has everything you will need.<br />1st Bedroom – Double bed<br />2nd Bedroom – 2 single beds<br />3rd Bedroom – 2 single beds<br />-Telephone line for incoming calls or to call us if you need something.<b",
	"neighborhood_overview" : "Ampelokipi district is nice multinational and safe area with excellent transportation system. Staying in Ampelokipi area you have the safety you need when you are in a foreign country. Everything you need for your vacations you can find it next to the apartment: Shops, Supermarkets, Restaurants, Bars, Coffee shops, Bakeries, Groceries, 24 hours kiosk, Pharmacies, Hair Salon, Banks, Travel Agents, Cinemas, summer cinemas and many more... <br />Also every Saturday there is a Farmers market 2-3 minutes away from the apartment.<br /><br />Athens Classical Marathon route pass from the area.<br />In the area you will also find Athens Concert Hall (Megaron Mousikis), National Sculpture Gallery, Badminton Theater (international shows), the biggest urban park in Athens, ministries, universities, embassies, hospitals and more…",
	"picture_url" : "https://a0.muscache.com/pictures/f7e19a44-5afe-4558-8b5d-2f8186723721.jpg",
	"host_id" : 37177,
	"host_url" : "https://www.airbnb.com/users/show/37177",
	"host_name" : "Emmanouil",
	"host_since" : "2009-09-08",
	"host_location" : "Athens, Attica, Greece",
	"host_about" : "Athens Quality Apartments is a company started back at 2007 and now we have 8 apartments. Our goal is to offer to travelers beautiful apartments with professional service only in good location and with all the necessary amenities.\n",
	"host_response_time" : "within an hour",
	"host_response_rate" : "100%",
	"host_acceptance_rate" : "99%",
	"host_is_superhost" : "t",
	"host_thumbnail_url" : "https://a0.muscache.com/im/pictures/user/859c1eda-f858-414e-9984-165bd4575b3f.jpg?aki_policy=profile_small",
	"host_picture_url" : "https://a0.muscache.com/im/pictures/user/859c1eda-f858-414e-9984-165bd4575b3f.jpg?aki_policy=profile_x_medium",
	"host_neighbourhood" : "Ambelokipi",
	"host_listings_count" : 6,
	"host_total_listings_count" : 6,
	"host_verifications" : "['email', 'phone', 'reviews', 'jumio', 'government_id']",
	"host_has_profile_pic" : "t",
	"host_identity_verified" : "t",
	"neighbourhood" : "Athens, Attica, Greece",
	"neighbourhood_cleansed" : "ΑΜΠΕΛΟΚΗΠΟΙ",
	"neighbourhood_group_cleansed" : "",
	"latitude" : 37.98863,
	"longitude" : 23.76527,
	"property_type" : "Entire rental unit",
	"room_type" : "Entire home/apt",
	"accommodates" : 8,
	"bathrooms" : "",
	"bathrooms_text" : "2 baths",
	"bedrooms" : 3,
	"beds" : 5,
	"amenities" : "[\"Long term stays allowed\", \"Hot water\", \"Shower gel\", \"Ethernet connection\", \"Iron\", \"Central heating\", \"Oven\", \"Coffee maker\", \"Extra pillows and blankets\", \"Free street parking\", \"Shampoo\", \"Single level home\", \"Air conditioning\", \"Dedicated workspace\", \"Cooking basics\", \"Wifi\", \"Essentials\", \"High chair\", \"Refrigerator\", \"Electric stove\", \"Bed linens\", \"43\\\" HDTV\", \"Patio or balcony\", \"Hangers\", \"Host greets you\", \"Dishwasher\", \"Kitchen\", \"Crib\", \"Microwave\", \"Dishes and silverware\", \"Laundromat nearby\", \"Washer\", \"Hair dryer\"]",
	"price" : "$70.00",
	"minimum_nights" : 1,
	"maximum_nights" : 1125,
	"minimum_minimum_nights" : 2,
	"maximum_minimum_nights" : 8,
	"minimum_maximum_nights" : 1125,
	"maximum_maximum_nights" : 1125,
	"minimum_nights_avg_ntm" : 2.3,
	"maximum_nights_avg_ntm" : 1125,
	"calendar_updated" : "",
	"has_availability" : "t",
	"availability_30" : 21,
	"availability_60" : 51,
	"availability_90" : 81,
	"availability_365" : 114,
	"calendar_last_scraped" : "2021-12-23",
	"number_of_reviews" : 32,
	"number_of_reviews_ltm" : 7,
	"number_of_reviews_l30d" : 0,
	"first_review" : "2011-05-20",
	"last_review" : "2021-09-24",
	"review_scores_rating" : 4.77,
	"review_scores_accuracy" : 4.81,
	"review_scores_cleanliness" : 4.75,
	"review_scores_checkin" : 4.84,
	"review_scores_communication" : 4.84,
	"review_scores_location" : 4.5,
	"review_scores_value" : 4.66,
	"license" : 957568,
	"instant_bookable" : "t",
	"calculated_host_listings_count" : 6,
	"calculated_host_listings_count_entire_homes" : 6,
	"calculated_host_listings_count_private_rooms" : 0,
	"calculated_host_listings_count_shared_rooms" : 0,
	"reviews_per_month" : 0.25
}
{
	"_id" : ObjectId("624b14fc21f2b8ef609fc800"),
	"id" : 10990,
	"listing_url" : "https://www.airbnb.com/rooms/10990",
	"scrape_id" : NumberLong("20211223003724"),
	"last_scraped" : "2021-12-23",
	"name" : "Athens Quality Apartments - Deluxe Apartment",
	"description" : "Athens Quality Apartments - Deluxe apartment is 1-bedroom apartment (50 square meters) <br />-excellent located <br />-close to metro station, <br />-lovely, <br />-very clean <br />with all the facilities that you will need, nice balcony, excellent Wi-Fi, cable tv, fully air conditioned…<br /><br /><b>The space</b><br />Athens Furnished Apartment No3 is an excellent located, close to metro, lovely, very clean 1-bedroom apartment (50 square meters) with all the facilities that you will need and a very nice balcony facing the inner garden to enjoy your breakfast in the morning or relax in the evening. Fully equipped kitchen with everything you need to prepare your lunch/dinner. Nice Living room to relax and enjoy a movie or a sport event. Clean nice bathroom. For more than 2 people there is a great double sofa/bed in the living room.<br />Apartment No3 has everything you will need.<br />-Telephone line for incoming calls or to call us if you need something.<br />-Free fast Wi-Fi from th",
	"neighborhood_overview" : "Ampelokipi district is nice multinational and safe area with excellent transportation system. Staying in Ampelokipi area you have the safety you need when you are in a foreign country. Everything you need for your vacations you can find it next to the apartment: Shops, Supermarkets, Restaurants, Bars, Coffee shops, Bakeries, Groceries, 24 hours kiosk, Pharmacies, Hair Salon, Banks, Travel Agents, Cinemas, summer cinemas and many more... <br />Also every Saturday there is a Farmers market 2-3 minutes away from the apartment.<br /><br />Athens Classical Marathon route pass from the area.<br />In the area you will also find Athens Concert Hall (Megaron Mousikis), National Sculpture Gallery, Badminton Theater (international shows), the biggest urban park in Athens, ministries, universities, embassies, hospitals and more…",
	"picture_url" : "https://a0.muscache.com/pictures/8645179/c1728e5b_original.jpg",
	"host_id" : 37177,
	"host_url" : "https://www.airbnb.com/users/show/37177",
	"host_name" : "Emmanouil",
	"host_since" : "2009-09-08",
	"host_location" : "Athens, Attica, Greece",
	"host_about" : "Athens Quality Apartments is a company started back at 2007 and now we have 8 apartments. Our goal is to offer to travelers beautiful apartments with professional service only in good location and with all the necessary amenities.\n",
	"host_response_time" : "within an hour",
	"host_response_rate" : "100%",
	"host_acceptance_rate" : "99%",
	"host_is_superhost" : "t",
	"host_thumbnail_url" : "https://a0.muscache.com/im/pictures/user/859c1eda-f858-414e-9984-165bd4575b3f.jpg?aki_policy=profile_small",
	"host_picture_url" : "https://a0.muscache.com/im/pictures/user/859c1eda-f858-414e-9984-165bd4575b3f.jpg?aki_policy=profile_x_medium",
	"host_neighbourhood" : "Ambelokipi",
	"host_listings_count" : 6,
	"host_total_listings_count" : 6,
	"host_verifications" : "['email', 'phone', 'reviews', 'jumio', 'government_id']",
	"host_has_profile_pic" : "t",
	"host_identity_verified" : "t",
	"neighbourhood" : "Athens, Attica, Greece",
	"neighbourhood_cleansed" : "ΑΜΠΕΛΟΚΗΠΟΙ",
	"neighbourhood_group_cleansed" : "",
	"latitude" : 37.98903,
	"longitude" : 23.76448,
	"property_type" : "Entire rental unit",
	"room_type" : "Entire home/apt",
	"accommodates" : 4,
	"bathrooms" : "",
	"bathrooms_text" : "1 bath",
	"bedrooms" : 1,
	"beds" : 1,
	"amenities" : "[\"Long term stays allowed\", \"Hot water\", \"Shower gel\", \"Ethernet connection\", \"Iron\", \"Central heating\", \"Oven\", \"Coffee maker\", \"Extra pillows and blankets\", \"Stove\", \"Free street parking\", \"Luggage dropoff allowed\", \"Shampoo\", \"Single level home\", \"Air conditioning\", \"TV\", \"Dedicated workspace\", \"Pack \\u2019n play/Travel crib\", \"Cooking basics\", \"Wifi\", \"Essentials\", \"High chair\", \"Refrigerator\", \"Bed linens\", \"Patio or balcony\", \"Hangers\", \"Host greets you\", \"Kitchen\", \"Microwave\", \"Dishes and silverware\", \"Laundromat nearby\", \"Washer\", \"Hair dryer\"]",
	"price" : "$50.00",
	"minimum_nights" : 1,
	"maximum_nights" : 1125,
	"minimum_minimum_nights" : 1,
	"maximum_minimum_nights" : 8,
	"minimum_maximum_nights" : 1125,
	"maximum_maximum_nights" : 1125,
	"minimum_nights_avg_ntm" : 1.6,
	"maximum_nights_avg_ntm" : 1125,
	"calendar_updated" : "",
	"has_availability" : "t",
	"availability_30" : 29,
	"availability_60" : 59,
	"availability_90" : 89,
	"availability_365" : 364,
	"calendar_last_scraped" : "2021-12-23",
	"number_of_reviews" : 54,
	"number_of_reviews_ltm" : 10,
	"number_of_reviews_l30d" : 0,
	"first_review" : "2012-09-06",
	"last_review" : "2021-11-01",
	"review_scores_rating" : 4.83,
	"review_scores_accuracy" : 4.91,
	"review_scores_cleanliness" : 4.85,
	"review_scores_checkin" : 4.91,
	"review_scores_communication" : 4.91,
	"review_scores_location" : 4.81,
	"review_scores_value" : 4.79,
	"license" : 1070920,
	"instant_bookable" : "t",
	"calculated_host_listings_count" : 6,
	"calculated_host_listings_count_entire_homes" : 6,
	"calculated_host_listings_count_private_rooms" : 0,
	"calculated_host_listings_count_shared_rooms" : 0,
	"reviews_per_month" : 0.48
}
...
```

<br>

3. Finding listings of host_id 37177 and 1826598, and checking whether they're superhosts.
- Query: 
`
db.listings.find(
    {
        $or : [
            { host_id: 37177 }, 
            { host_id: 1826598},
        ],
        host_is_superhost:"t"
    }, 
    {_id:0, name:1, price:1, neighbourhood:1, host_name:1, host_is_superhost:1}
);
`
- Results:
```
{ "name" : "96m2, 3BR, 2BA, Metro, WI-FI etc...", "host_name" : "Emmanouil", "host_is_superhost" : "t", "neighbourhood" : "Athens, Attica, Greece", "price" : "$70.00" }
{ "name" : "Athens Quality Apartments - Deluxe Apartment", "host_name" : "Emmanouil", "host_is_superhost" : "t", "neighbourhood" : "Athens, Attica, Greece", "price" : "$50.00" }
{ "name" : "Athens Quality Apartments - Studio", "host_name" : "Emmanouil", "host_is_superhost" : "t", "neighbourhood" : "Athens, Attica, Greece", "price" : "$38.00" }
...
```

<br>

4. Finding all unique host names.
- Query: `db.listings.distinct("host_name")`
- Result: 
```
    "",
	"'Αννα",
	"(Kay)",
	"1915 Team",
	"33 Solonos Suites",
	"A",
	"A&D",
	"A. Tony &",
	"A77",
	"AIKATERINI'S Place, ATHENS",
    ...
```

<br>

5. Finding all places with equal to or greater than 2 beds in "Athens, Attica, Greece" ordered by `review_scores_rating` in descending order.
- Query: 
`
db.listings.find({
    beds: { $gte: 2},  
    neighborhood: "Athens, Attica, Greece",
    }, 
    {name:1, beds:1, review_scores_rating:1, price:1, _id:0}
).sort({review_scores_rating: -1});
`
- Result: 
```
{ "name" : "Design apartment near Syntagma!!", "beds" : 2, "price" : "$170.00", "review_scores_rating" : "" }
{ "name" : "TopFloor Sunny Apartment  Kolonaki", "beds" : 4, "price" : "$120.00", "review_scores_rating" : "" }
{ "name" : "Minimal, Historical Townhouse near Athens centre!", "beds" : 2, "price" : "$80.00", "review_scores_rating" : "" }
{ "name" : "Deluxe Double Room", "beds" : 2, "price" : "$136.00", "review_scores_rating" : "" }
```

<br>

6. Number of listings per host (I used `host_id` to sort to ensure that people with the same name were not mixed up).
- Query: 
`db.listings.aggregate( [
    {$group: {_id:"$host_id", count:{$sum:1}}}
 ]);
`
- Results: 
```
{ "_id" : 436756020, "count" : 1 }
{ "_id" : 436763650, "count" : 1 }
{ "_id" : 436613083, "count" : 1 }
...
```

<br>

7. Average review_scores_rating per neighbourhood, only showing those above 4, sorted in descending order. 
- Query:
`
db.listings.aggregate([ 
    {$group: {_id: "$neighbourhood", 
    "avg_rating": {$avg:"$review_scores_rating"}}},
    {'$match': {avg_rating: {$gte: 4}}},
    {$sort: {"avg_rating": -1}}, 
])
`
- Results: 
```
{ "_id" : "Athens, Attica , Greece", "avg_rating" : 5 }
{ "_id" : "Kypriadou, Greece", "avg_rating" : 5 }
{ "_id" : "Athens, PETRALONA, Greece", "avg_rating" : 5 }
{ "_id" : "Αθηνα, Greece", "avg_rating" : 5 }
{ "_id" : "Athens, Athens, Kolonaki, Greece", "avg_rating" : 5 }
```

