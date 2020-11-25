# OrlogExploration
Finding an optimal policy for Orlog.

## Setup - Windows

20201125: Must be locked to numpy version 1.19.3 on Windows builds due to a known incompatibility between the latest Windows 10 update and the latest numpy builds: https://developercommunity.visualstudio.com/content/problem/1207405/fmod-after-an-update-to-windows-2004-is-causing-a.html

```
$ virtualenv -p python37.exe env
$ env\Scripts\activate
(env) $ pip install numpy==1.19.3 pandas seaborn matplotlib jupyter
(env) $ pip install torch===1.7.0+cu110 -f https://download.pytorch.org/whl/torch_stable.html
(env) $ jupyter notebook
```

## Setup - Linux / UNIX

```
$ virtualenv -p python37 env
$ source env/bin/activate
(env) $ pip install numpy pandas seaborn matplotlib jupyter
(env) $ pip install torch==1.7.0+cu110 -f https://download.pytorch.org/whl/torch_stable.html
(env) $ jupyter notebook
```