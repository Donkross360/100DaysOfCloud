# Day31 Of My Severles Journey

## Introduction
  Built a fast session store for online applications with Amazon ElastiCache for Redis, as a distributed cache for session management on EC2.


## Use Case
 - Session Store, Session Caching, High Availability, Real-time application.
 
 - There are many ways of managing user sessions in web applications, ranging from cookies-only to distributed key/value databases, including server-local caching. Storing session data in the web server responding to a given request may seem convenient, as accessing the data incurs no network latency.

## Cloud Research
 - The main drawback is that requests have to be routed carefully so that each user interacts with one server and one server only.
 - Another drawback is that once a server goes down, all the session data is gone as well.
 - A distributed, in-memory key/value database can solve both issues by paying the small price of a tiny network latency. Storing all the session data in cookies is good enough most of the time; if you plan to store sensitive data, then using server-side sessions is preferable.

## Products: 
 - Amazon ElastiCache for Redis, AWS Free Tier, Amazon EC2


 [Tweet](https://twitter.com/martynzYoung/status/1305169676780134404)