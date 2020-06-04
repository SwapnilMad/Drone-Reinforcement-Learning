# Autonomous Face Tracking Drone
<p>Reinforcement Learning applied on a Tello Drone to follow human faces using keras-rl. For this project DJI Tello Edu drone was used.</p>
<p>Agent is trained on a continuous state simulator to adjust velocity depending upon the position of the target using Deep Deterministic Policy Gradient (DDPG)</p>

## Getting Started
Clone or download the project to your system

<h4>Prequisites</h4>

<p>Python</p><pre>Install Python 3 or Anaconda</pre>

<h4>Installing</h4>

<p>Install Dependencies</p><pre>pip install -r requirements.txt</pre>

<h4>Running</h4>
<p>Train the agent on a simulator and save weights</p>
<pre>python train.py</pre>

<p>Load the saved weights and test it on the drone</p>
<pre>python drone_test.py</pre>
