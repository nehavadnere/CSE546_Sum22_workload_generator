# CSE546_2021S_workload_generator

This repository contains code examples for you to use our workload generator.
We setup both php and node.js server backends

The following command sends three requests to a php backend.
```
python3 workload_generator.py \
 --num_request 3 \
 --url 'http://your_host_ip/php_server.php' \
 --image_folder "your_local_image_folder"
```

The following command sends three requests to a node.js backend.
```
python3 workload_generator.py \
 --num_request 3 \
 --url 'http://your_host_ip:3000' \
 --image_folder "your_local_image_folder"
```

To send requests using multiple threads, you can use multithread_workload_generator.py. 

Sample output:
```
test_93.JPEG uploaded!
Classification result: church

test_85.JPEG uploaded!
Classification result: carton

test_11.JPEG uploaded!
Classification result: custard apple
```
