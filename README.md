[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=21008000&assignment_repo_type=AssignmentRepo)
# MiniTorch Module 1

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module1/module1/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py tests/test_module.py tests/test_operators.py project/run_manual.py

---

TODO: There seems a dependency error in the repo? I should take time to fix that.

As mentioned in Module 0, I should create a virtual environment with python version >= 3.11

However, in Module 1 here, there exists `numba 0.56`, which requires the python version > 3.7 and < 3.10.

So I change the version of numba to 0.57 here, which meet the requirement.

Let me try if there exits any problem. Then maybe I will make a PR.
