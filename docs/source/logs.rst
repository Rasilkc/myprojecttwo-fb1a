Latest Logs From Latest Build
==============================

Generated On: 2024-12-08 20:44:35 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/Rasilkc/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-08_20:42:42] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-08_20:42:45] STEP 2: Create topics started

  [INFO 2024-12-08_20:42:54] STEP 2: Completed

  [INFO 2024-12-08_20:42:59] STEP 3: producing data started

  [INFO 2024-12-08_20:43:01] MQTT connection established...

  [INFO 2024-12-08_20:43:01] STEP 4: Preprocessing started

  [INFO 2024-12-08_20:43:03] STEP 4: Preprocessing started

  [INFO 2024-12-08_20:43:04] STEP 7: Visualization started

  [INFO 2024-12-08_20:43:10] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-08_20:43:16] STEP 9: Starting privateGPT

  [INFO 2024-12-08_20:43:21] STEP 8: Starting docker push for: rasilkc98/myprojecttwo-fb1a-amd64

  [INFO 2024-12-08_20:43:29] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-12-08_20:43:43] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 06941fb8a158 rasilkc98/myprojecttwo-fb1a-amd64 - message=0

  [INFO 2024-12-08_20:44:26] STEP 8: Successfully ran Docker push: docker push rasilkc98/myprojecttwo-fb1a-amd64 - message=0

  [INFO 2024-12-08_20:44:34] STEP 10: Started to build the documentation

  [INFO 2024-12-08_20:44:35] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


