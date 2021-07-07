# This project is Decrypted plzz visit https://github.com/nasir733/OneShopJobs
## Jobs Scrapper && Api

This is a hobby project made to help people jobs from there favourite websites in one place This scrapper will scrape the jobs from revelant website (Indeed.com and stackoverflow) planning to add support for websites soon



## API Reference

#### Get all items

```http
  GET https://jobapiscrapper.herokuapp.com/scrapper/jobs/
```

| Query | Type     | Description                |option|
| :-------- | :------- | :------------------------- |-----|
| `ordering` | `string` |  your ordering field |rating,location ,created_at ,jobCategory |
| `search` | `string` |  your search word |**You can search by**: 'rating','location','title','company_name','created_at', 'job_by','jobCategory' |


## Admin Panel
Can only view things from this demo account 
 ### user = demo
 ### password = ultimatedemo
 [Admin Panel](https://jobapiscrapper.herokuapp.com/admin)
 
# DOCS
 [Documentaion Redoc](https://jobapiscrapper.herokuapp.com/api/schema/redoc/)
 [Documentaion Swagger](https://jobapiscrapper.herokuapp.com/api/schema/swagger-ui/)
