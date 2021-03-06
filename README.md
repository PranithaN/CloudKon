# CloudKon
Implemented a distributed task execution framework, where EC2 instances programmed in JAVA are used as Scheduler, Worker and Clients.
Programmed the Client instance that sends task to the Scheduler using Socket. 
Designed a Scheduler, which uses SQS services to send Tasks to the Workers. The number of workers changed dynamically with incoming load from clients.
Observed and monitored the remote instances for the completion of task and sending back notifications. 
Amazon SQS and Dynamo DB were employed in conjunction as a lookup table and handle the queue of requests to load balance across multiple workers.
Tested, Analyzed and Evaluated performance of different AWS services using various test cases.
