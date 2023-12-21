#LINUX

Aby uruchmić projekt należy otworzyć katalog "ros2_ws" w terminalu, a następnie wpisać następujące komendy:
- source/opt/ros/humble/setup.bash
- source install/setup.bash
- export TURTLEBOT3_MODEL=burger
- export GAZEBO_MODEL_PATH=$GAZEBO_MODEL_PATH:'ros2 pkg \ prefix turtlebot3_gazebo \ ' /share/turtlebot3_gazebo/models
- ros2 launch turtlebot3_gazebo empty_world.launch.py.

Następnie, należy otworzyć projekt w kolejnym oknie terminalu i wykonać następujące polecenia:
- source/opt/ros/humble/setup.bash
- source install/setup.bash
- ros2 run model_paczka publisher
  
Program powinien wyświetlić puste okno terminala oraz wizuarlizację robota turtlebot, który zacznie poruszać się w górę, lub w dół, w zależności od klikniętej połowy ekranu otwartego okna konsoli. Ekran konsoli podzielony jest na połowy horyzontalnie.
