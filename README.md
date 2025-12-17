# AWS-S3-Multi-Region-Access-Point
created an S3 Multi-Region Access Point (MRAP), which allows a single S3 endpoint to distribute traffic to the closest bucket to the user/application.  Multiple buckets are added to the Multi-Region Access Point in different regions, S3 requests (GETs, PUTs, etc) are routed to the closest bucket to the user and also the changes are replicated.
