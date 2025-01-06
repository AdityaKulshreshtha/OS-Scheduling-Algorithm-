# OS-Scheduling-Algorithm-
This is a resource based scheduling algorithm in which each process tells
beforehand about the max need of resources. The processes also has their burst
time and arrival time associated with them.
The algorithm schedules the processes (i.e. pid's of the processes) in such a way
that the processes which utilize more no. of resources are executed after completing
the processes utilizing lesser no. of resources.This helps in better initial responses
since the task of OS is somewhat lesser in the beginning.But later the bulkier
processes come into execution which drops the productivity of the process's
execution to some extent . When there are two or more processes having same need
of resources the the burst time is taken into consideration and the process having
less burst time is executed first.And still if there are two or more processes having
same need of resources and same burst time then their time of arrival is used as a
tiebreaker and the one which arrived early is executed first . This code ensures the
less resource requiring processes are executed on a faster basis and their result may
be used by the high resource demanding processes.
The algorithm works for the non-preemptive processes and arranges them in order to
provide a significantly better initial execution results.
