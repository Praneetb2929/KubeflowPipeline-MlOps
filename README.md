# KubeflowPipeline-MlOps
Installation of Kubeflow Pipelines
The best guide to install Kubeflow or any of its components is the official documentation.

https://www.kubeflow.org/docs/started/

In this tutorial, we will learn how to Install, Configure and Use the most popular component of Kubeflow that is KFP (Kubeflow Pipelines).

Step 1: Install Docker Desktop
Follow the below guide and follow the steps according to your OS Distribution.

https://docs.docker.com/desktop/setup/install/mac-install/

Step 2: Install KIND
Easy way to learn Kubeflow Pipelines is to setup a KIND k8s cluster and configure Kubeflow Pipelines on the cluster.

https://kind.sigs.k8s.io/docs/user/quick-start/

Step 3: Install KFP in Kubernertes
Follow the steps to setup KFP.

https://www.kubeflow.org/docs/components/pipelines/operator-guides/installation/

Step 4: Install Python kfp package
Create a folder - mkdir kfp
Create a Python virtual environment - python3 -m venv .kfp
Source the virtual environment - source .kfp/bin/activate
Install the package - pip3 install kfp==2.9.0
