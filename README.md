ROLLINGUPDATE:
In rooling update it create a new pod then terminate the old one (for small application) downtime: no , used in Production env: yes
BLUE_GREEN:
In green-blue deployment strategy "blue' is used for current version that user use ,now i want to update the version. 
i will create a clone of this version then test it is "green" deployment iof it is ok  then just chhange the  app label on blue deployment
change the service app label to green downtime :no ,used in production : yessss
ADDITIONAL_HELP:
dont forget to clear the port forward cache as we are not in eks "pkill -f "kubectl port-forward"
