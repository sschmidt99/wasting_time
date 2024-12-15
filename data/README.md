# Data Dictionary
 [Fabricate with Mockaroo](https://fabricate.mockaroo.com/databases/67910a04-65f5-4e1e-b0d8-138c48cfeee6?).

## Data Descriptions
## social_media_usage

# actor_data table
- profile_id - str
- first_name - str
- last_name - str
- email - str
- gender - str
- age - int
- location_id - str
- profession - str


# media_usage table
- usage_id - str
- profile_id - int
- date - DD/MM/YYYY
- time_spent_minutes - int

# social_media_platform table
- platform_id - int
- platform_name - str

# social_media_profile table
- profile_id - str
- platform_id - str
- user_name - str
- personal_profile -boolean
- gender - str