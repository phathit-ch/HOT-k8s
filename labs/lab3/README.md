# Setting up your Kubernetes Overview Page

As per the official instructions [here](https://www.dynatrace.com/support/help/technology-support/cloud-platforms/kubernetes/installation-and-operation/further-integrations/connect-your-kubernetes-clusters-to-dynatrace/) for the Kubernetes integration, you will need to setup an Environment Activegate first.

### 1. Create infrastructure and install Activegate

``` bash
./setup-activegate.sh
```

Automation has been build around these [official steps](https://www.dynatrace.com/support/help/setup-and-configuration/activegate/installation/install-an-environment-activegate/#expand-103if-youre-on-an-ubuntu-server) with the above command

Once completed, you should see Activegate under Deployment Status.

![Activegate-connected](https://github.com/Nodnarboen/HOT-k8s/blob/master/assets/Picture9.1.png)

### 2. Setup the K8S Overview Dashboard

``` bash
./setup-k8s-ui.sh
```

With the values provided from the screen, copy and paste them into the Kubernetes integration page

Go to <b>Settings</b> -> <b>Cloud and Virtualization</b> -> <b>Kubernetes</b>

Follow the steps from our offical [documentation page](https://www.dynatrace.com/support/help/technology-support/cloud-platforms/kubernetes/installation-and-operation/further-integrations/connect-your-kubernetes-clusters-to-dynatrace/) to setup the K8S integration

:arrow_up: [Back to TOC](/README.md) :arrow_left: [Prev](../lab2/README.md)   :arrow_right: [Next](../lab4/README.md)  
