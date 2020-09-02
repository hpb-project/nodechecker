# Nodechecker
Reports the status of your HPB node.
It reports if the node is MINING, PEERCOUNT, CURRENT BLOCKNUMBER, IF STARTED, NODE TYPE (HpNode), VERSION.
Using this information, HPB can quickly notify you if there are any issues with your node, and get an overview of the health of the network.

How to set it up:
1. Request a password for your node. Send a message to "nicemans" on Telegram or to xxx on WeChat.

2. Download nodechecker.sh to your node and place it in /opt/ghpb-bin/: curl -o /opt/ghpb-bin/nodechecker.sh https://github.com/...

3. Open nodechecker.sh with an editor and change the following to be correct: NODENAME, PASSWORD, BINARY, PORT (BINARY and PORT are already set to default, so no need to change them if you have not altered the configuration).

4. Run nodechecker.sh: sudo bash /opt/ghpb-bin/nodechecker.sh

5. nodechecker.sh will now report your node's status every 5 minutes.
