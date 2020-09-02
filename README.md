# Nodechecker
Reports the status of your HPB node.
It reports if the node is MINING, PEERCOUNT, CURRENT BLOCKNUMBER, IF STARTED, NODE TYPE (HpNode), VERSION.
Using this information, HPB can quickly notify you if there are any issues with your node, and get an overview of the health of the network.

How to set it up:
1. Request a password for your node. Send a message to "nicemans" on Telegram or to xxx on WeChat.

2. Download nodechecker.sh to your node and place it in /opt/ghpb-bin/:
```sudo curl -o /opt/ghpb-bin/nodechecker.sh https://raw.githubusercontent.com/Nicemanss/nodechecker/master/nodechecker.sh```

3. Open nodechecker.sh with an editor and change the following to be correct: NODENAME, PASSWORD, BINARY, PORT (BINARY and PORT are already set to default, so no need to change them if you have not altered the configuration).

4. Run nodechecker.sh: sudo bash /opt/ghpb-bin/nodechecker.sh

5. nodechecker.sh will now report your node's status every 5 minutes.


Using the name of your node and password obtained in step 1, you can also login to the following URL to watch the status dashboards of the nodes: https://382ac6595ff7400d9466e10bf89853a0.us-central1.gcp.cloud.es.io:9243/app/dashboards#/view/e504b420-e71d-11ea-8880-0d3256919bd5?_g=(filters:!(),refreshInterval:(pause:!t,value:0),time:(from:now-15m,to:now))&_a=(description:'',filters:!(),fullScreenMode:!f,options:(hidePanelTitles:!f,useMargins:!t),query:(language:kuery,query:''),timeRestore:!f,title:Nodes,viewMode:view)
