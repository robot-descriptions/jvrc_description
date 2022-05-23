# JVRC humanoid robot model

<img src="https://scaron.info/images/jvrc1-model.png" width="250" align="right" />

[![PyPI version](https://img.shields.io/pypi/v/upkie_description)](https://pypi.org/project/upkie_description/)
![Status](https://img.shields.io/pypi/status/upkie_description)

This package contains the robot description for the JVRC-1 model, a virtual humanoid robot released for education and research.

## Python module

This module helps retrieve the JVRC-1 model from a Python program. Import it by:

```python
import jvrc_description
```

It then provides the following paths:

<dl>
    <dt>
        <code>jvrc_description.path</code>
    </dt>
    <dd>
        Path to the <code>jvrc_description</code> folder itself.
    </dd>
    <dt>
        <code>jvrc_description.meshes_path</code>
    </dt>
    <dd>
        Path to the <code>meshes</code> folder.
    </dd>
    <dt>
        <code>jvrc_description.urdf_path</code>
    </dt>
    <dd>
        Path to the <code>jvrc1.urdf</code> URDF file of the model.
    </dd>
</dl>

## Show and tell

Feel free to [open a PR](https://github.com/stephane-caron/jvrc_description/pulls) to share what you have done with this model.

| Date | Topic | Screenshot |
|------|-------|------------|
| 2019 | [Docker image of a walking controller in simulation](https://hub.docker.com/r/stephanecaron/lipm_walking_controller) — Snapshot of a whole-body controller used on the HRP-4 humanoid to walk and climb stairs. This image includes a fully functional build and simulation environment where you can try the controller on the JVRC model.  | <img src="https://user-images.githubusercontent.com/1189580/69481155-04de3500-0e52-11ea-91cc-02d05d504ffa.png" width="250"> |
| 2016 | [Task-based inverse kinematics in Python](https://scaron.info/robot-locomotion/inverse-kinematics.html) — A whole-body inverse kinematics based on the weight-prioritized multi-task framework. Tasks include foot-surface contacts, center of mass or centroidal momentum control. Depends on OpenRAVE. | <img src="https://scaron.info/images/weighted-issue.png" width="250"> |
