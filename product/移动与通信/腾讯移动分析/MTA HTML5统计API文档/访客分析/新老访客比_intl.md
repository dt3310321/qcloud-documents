### Feature Description
Query the number of new and old visitors of the day on a daily basis.

**API URL:** `http://mta.qq.com/h5/api/ctr_user_compare`;
**HTTP request method:** GET.

### Parameters

| Parameter Name | Type | Meaning | Note |
|---------|---------|---------|---------|
| app_id | Integer | App ID | The ID generated during application registration |
| start_date | String | Start time | Start time (Y-m-d) |
| end_date | String | End time | End time (Y-m-d) |
| sign | String | Verification string | See the example of generation process |
