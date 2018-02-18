Deep Assist
===========

Create assistive agents to help humans with real-time control tasks.

Usage
-----

Install Python dependencies with the [pip](https://pip.pypa.io/en/stable/installing/) package
manager using

```
pip install -r requirements.txt
```

Install [gym](https://github.com/openai/gym) and replace `gym/envs/box2d/lunar_lander.py` with `deepassist/lunar_lander_for_{bots,humans}.py`.

Install [baselines](https://github.com/openai/baselines) and replace `baselines/baselines/deepq/simple.py` with `deepassist/simple.py`.

Extract [this zip file](https://drive.google.com/file/d/1jeNCyhN7LB4TXmDP8ePnxBeGI3eLyi3m/view?usp=sharing) into `deepassist/`.

For the quadrotor experiments, install [ardrone_autonomy](https://wiki.ros.org/ardrone_autonomy) and [vicon_bridge](https://wiki.ros.org/vicon_bridge).

Questions and comments
----------------------

Please contact the author at `sgr [at] berkeley [dot] edu` if you have questions or find bugs.

Citation
--------
If you find this software useful in your work, we kindly request that you cite the following [paper](https://arxiv.org/abs/1802.01744):

```
@InProceedings{Reddy/etal/18a,
  title={Shared Autonomy via Deep Reinforcement Learning},
  author={Reddy, Siddharth and Levine, Sergey and Dragan, Anca},
  booktitle={Arxiv 1802.01744},
  year={2018},
  url={https://arxiv.org/abs/1802.01744}
}
```
