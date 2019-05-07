# Club Mahindra DataOlympics
### Food & Beverages Spend Prediction in Club Mahindra Resorts

[competition link](https://datahack.analyticsvidhya.com/contest/club-mahindra-dataolympics/)

__RMSE * 100 : 97.3268376748__

[__Private Leader Board Rank__](https://datahack.analyticsvidhya.com/contest/capillary-machine-learning-hackathon/pvt_lb) : 94/983

[Analysis and data Preparation Notebook](https://nbviewer.jupyter.org/github/NishantBhavsar/Club-Mahindra-DataOlympics/blob/master/code/Analysis.ipynb)

[Final model Notebook](https://nbviewer.jupyter.org/github/NishantBhavsar/Club-Mahindra-DataOlympics/blob/master/code/models.ipynb)

### Problem Statement
Club Mahindra (Club M) makes significant revenue from Food and Beverages (F&B) sales in their resorts. The members of Club M are offered a wide variety of items in either buffet or À la carte form. Following are some benefits that the model to predict the spend by a member in their next visit to a resort will bring:

1. Predicting the F&B spend of a member in a resort would help in improving the pre-sales during resort booking through web and mobile app
2. Targeted campaigns to suit the member taste and preference of F&B
3. Providing members in the resort with a customized experience and offers
4. Help resort kitchen to plan the inventory and food quantity to be prepared in advance

Given the information related to resort, club member, reservation etc. the task is to __predict average spend per room night on food and beverages for the each reservation__ in the test set.


### Data Dictionary

| Variable | Description |
| -------- | ----------- |
| reservation_id | Reservation ID |
| booking_date	| Date of booking |
| checkin_date	| Checkin date recorded at the time of booking | 
| checkout_date	| Checkout date recorded at the time of booking |
| channel_code	| Different channels of booking |
| main_product_code	| Type of product a member has purchased |
| numberofadults	| Number of adults travelling |
| numberofchildren | Number of children travelling |
| persontravellingid	| Type of person travelling |
| resort_region_code	| Resort Region |
| resort_type_code	| Resort Type |
| room_type_booked_code	| Room Type |
| roomnights	| Number of roomnights booked |
| season_holidayed_code	| Season Holidayed |
| state_code_residence	| Residence State of Member |
| state_code_resort	| State in which resort is located |
| total_pax	| Total persons travelling |
| member_age_buckets	| Age bucket of the member |
| booking_type_code	| Type of Booking |
| memberid	| Unique ID of the member |
| cluster_code	| Cluster Code of Resort |
| reservationstatusid_code	| Reservation Status ID |
| resort_id	| Unique Resort ID |
| amount_spent_per_room_night_scaled	| (Target) Resort Spend Per Room Night |


### Evaluation Metric
- RMSE * 100
