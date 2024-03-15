
# DE Zoomcamp Module 5  - Homework

### Freanu Peria


## Question 1: Redpanda Version

Answer: 
redpanda@d5c55c0658df:/$ rpk version
v22.3.5 (rev 28b2443)


## Question 2. Creating a topic

Answer:
redpanda@d5c55c0658df:/$ rpk topic create test-topic
TOPIC       STATUS
test-topic  OK
redpanda@d5c55c0658df:/$


## Question 3. Connecting to the Kafka server

Answer:
True



## Question 4. Sending data to the stream

Answer:
the entire cell took 0.5 seconds. it spent most of the time in sending the message.


## Question 5: Sending the Trip Data

all took 34.48 seconds
sending messages took 30.63 seconds
flushing took 3.85 seconds
How much time in seconds did it take? (You can round it to a whole number)
35 Seconds


##  Question 6. Parsing the data

How does the record look after parsing? Copy the output.

Row(lpep_pickup_datetime='2019-10-01 00:26:02', lpep_dropoff_datetime='2019-10-01 00:39:58', PULocationID=112, DOLocationID=196, passenger_count=1.0, trip_distance=5.88, tip_amount=0.0)

without schema:
Row(key=None, value=bytearray(b'{"lpep_pickup_datetime": "2019-10-01 00:26:02", "lpep_dropoff_datetime": "2019-10-01 00:39:58", "PULocationID": 112, "DOLocationID": 196, "passenger_count": 1.0, "trip_distance": 5.88, "tip_amount": 0.0}'), topic='green-trips', partition=0, offset=0, timestamp=datetime.datetime(2024, 3, 15, 20, 55, 39, 930000), timestampType=0)


## Question 7: Most popular destination
- did not answer :(


My code and solutions are in `Homework.ipynb`. Thank you!
