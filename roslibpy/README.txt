Steps to build and run:-

1) Install the rosbridge suite using command:-
   sudo apt-get install -y ros-kinetic-rosbridge-server
2) Launch the websocket using command:- roslaunch rosbridge_server rosbridge_websocket.launch
3) Check the connection is established by running:- python ros-hello-world.py
4) To check for Publisher and Subscriber run the below nodes:-
   Talker:- python ros-hello-world-talker.py
   Listener:- python ros-hello-world-listener.py
5) To use a service run the below node
   Server:- python ros-service.py
   Service:- python ros-service-call-set-bool.py
6) Using the action server and client run the below node:-
   Action_Server:- python ros-action-server.py
   Action_Client:- python ros-action-client.py
7) To test a service run the test node :- python test_service.py
