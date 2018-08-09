# raspimouse_gamepad_teach_and_replay

### teaching

The teaching phase starts with a long push of the front button.
The LED at the left side is turned on, and you can control the
robot with a gamepad. When you can stop the teach 
with a push of the front button again. The episode is recored
to a file in ~/.ros/. The name of the file can be
obtained from the ROS parameter `/current\_bag\_file`.

### replay

After the training, the replay can be started with a long push
of the center button. It finishes with one more push of the
center button. After that, you can restart the replay again.

### caution

Bag files are stored in ~/.ros but they are not erased. Please
clean in the directory occasionally. 

## contributers

* Ryo Okazak

codes for gamepad control (original repo: https://github.com/zaki0929/raspimouse_game_controller ）

* Masahiro Kato

codes for teaching (original repo: https://github.com/kato-masahiro/raspimouse_maze_manual ）
