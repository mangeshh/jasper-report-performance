meaning -

4_cores_150_connections - we are using 4 cores and spring boot connection pool 150
1 user_in 1 second_1 loop_small size - we are sending 1 request( 1 user) in 1 second and not repeating (no loop).

50 users_in 1 second_10 loops_medium size - we are sending 50 requests (50 users) in 1 seconds and repeating for 10 times continuously and all expereiment done with medium size report.


small size report - 20 credit lines
large report - ~190 credit lines
medium - ~40 credit lines.


we did all evaluation on docker environement, with linux, java image and mysql was installed on local box.