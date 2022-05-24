# JVRC humanoid robot model

<img src="https://scaron.info/images/jvrc1-model.png" width="250" align="right" />

[![PyPI version](https://img.shields.io/pypi/v/jvrc_description)](https://pypi.org/project/jvrc_description/)

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
