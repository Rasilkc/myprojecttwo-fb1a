Latest Logs From Latest Build
==============================

Generated On: 2024-11-25 19:38:42 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/Rasilkc/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-25_19:37:03] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-25_19:37:05] STEP 2: Create topics started

  [INFO 2024-11-25_19:37:15] STEP 2: Completed

  [INFO 2024-11-25_19:37:20] STEP 3: producing data started

  [INFO 2024-11-25_19:37:23] MQTT connection established...

  [INFO 2024-11-25_19:37:23] STEP 4: Preprocessing started

  [INFO 2024-11-25_19:37:25] STEP 4: Preprocessing started

  [INFO 2024-11-25_19:37:25] STEP 7: Visualization started

  [INFO 2024-11-25_19:37:31] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-25_19:37:35] STEP 9: Starting privateGPT

  [INFO 2024-11-25_19:37:39] STEP 8: Starting docker push for: rasilkc98/myprojecttwo-fb1a-amd64

  [INFO 2024-11-25_19:37:47] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --gpus all --env PORT=8001 --env GPU=1 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-with-gpu-nvidia-amd64

  [INFO 2024-11-25_19:38:01] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 5472e9254be8 rasilkc98/myprojecttwo-fb1a-amd64 - message=0

  [INFO 2024-11-25_19:38:37] STEP 8: Successfully ran Docker push: docker push rasilkc98/myprojecttwo-fb1a-amd64 - message=0

  [INFO 2024-11-25_19:38:42] STEP 10: Started to build the documentation

  [INFO 2024-11-25_19:38:42] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


