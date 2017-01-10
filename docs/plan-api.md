# CarFreeAtoZ Trip Planning API

The CarFreeAtoZ API is located at [http://www.carfreeatoz.com/api](http://www.carfreeatoz.com/api). Available endpoints include the following:


### **/plan** (GET)

#### Query Parameters

| Parameter | Type | Notes | Example |
| -- | -- | -- | -- |
| accessModes | Comma-separated list | The allowable modes for accessing a transit trip | WALK,BICYCLE,BICYCLE_RENT,CAR_PARK |
| bikeSpeed | Number | The user's biking speed in m/s | 3.5763 |
| date | Date | The date of travel in YYYY-MM-DD format | 2017-01-01 |
| directModes | Comma-separated list | The allowable modes for a direct trip connecting the start and end locations | WALK,BICYCLE,BICYCLE_RENT,CAR |
| egressModes | Comma-separated list | The allowable modes for egressing a transit trip | WALK,BICYCLE_RENT |
| endTime | Time | The beginning of search range | 9:00 |
| from | Lat/Lon | The destination of the trip | 38.914319,-77.021102 |
| maxBikeTime | Number | The maximum time for a bike-access leg in minutes | 20 |
| maxWalkTime | Number | The maximum time for a walk-access leg in minutes | 30 |
| maxCarTime | Number | The maximum time for a car-access leg in minutes | 45 |
| startTime | Time | The beginning of search range |7:00 |
| to | Lat/Lon | The destination of the trip |  38.889637,-77.086272 |
| limit | Number | The maximum number of transit options to return | 2 |
| transitModes | Comma-separated list | The allowable modes for the transit leg of a trip | BUS,TRAIN |
| walkSpeed | Number | The user's walking speed | 1.34112 |
