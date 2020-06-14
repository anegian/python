# python

Instruction on How to activate conda in command prompt

1) C:\Users\anest>conda create -n myenv python=3.7
Collecting package metadata (current_repodata.json): done
Solving environment: done

==> WARNING: A newer version of conda exists. <==
  current version: 4.8.2
  latest version: 4.8.3

Please update conda by running

    $ conda update -n base -c defaults conda

## Package Plan ##

  environment location: C:\Users\anest\anaconda3\envs\myenv

  added / updated specs:
    - python=3.7

The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    certifi-2020.4.5.1         |           py37_0         156 KB
    openssl-1.1.1g             |       he774522_0         4.8 MB
    pip-20.0.2                 |           py37_3         1.7 MB
    python-3.7.7               |       h81c818b_4        14.3 MB
    setuptools-47.1.1          |           py37_0         538 KB
    sqlite-3.31.1              |       h2a8f88b_1         804 KB
    vs2015_runtime-14.16.27012 |       hf0eaf9b_2         1.2 MB
    zlib-1.2.11                |       h62dcd97_4         113 KB
    ------------------------------------------------------------
                                           Total:        23.6 MB
The following NEW packages will be INSTALLED:

  ca-certificates    pkgs/main/win-64::ca-certificates-2020.1.1-0
  certifi            pkgs/main/win-64::certifi-2020.4.5.1-py37_0
  openssl            pkgs/main/win-64::openssl-1.1.1g-he774522_0
  pip                pkgs/main/win-64::pip-20.0.2-py37_3
  python             pkgs/main/win-64::python-3.7.7-h81c818b_4
  setuptools         pkgs/main/win-64::setuptools-47.1.1-py37_0
  sqlite             pkgs/main/win-64::sqlite-3.31.1-h2a8f88b_1
  vc                 pkgs/main/win-64::vc-14.1-h0510ff6_4
  vs2015_runtime     pkgs/main/win-64::vs2015_runtime-14.16.27012-hf0eaf9b_2
  wheel              pkgs/main/win-64::wheel-0.34.2-py37_0
  wincertstore       pkgs/main/win-64::wincertstore-0.2-py37_0
  zlib               pkgs/main/win-64::zlib-1.2.11-h62dcd97_4


2) Proceed ([y]/n)? y

Downloading and Extracting Packages
vs2015_runtime-14.16 | 1.2 MB    | ############################################################################ | 100%
pip-20.0.2           | 1.7 MB    | ############################################################################ | 100%
python-3.7.7         | 14.3 MB   | ############################################################################ | 100%
zlib-1.2.11          | 113 KB    | ############################################################################ | 100%
sqlite-3.31.1        | 804 KB    | ############################################################################ | 100%
openssl-1.1.1g       | 4.8 MB    | ############################################################################ | 100%
certifi-2020.4.5.1   | 156 KB    | ############################################################################ | 100%
setuptools-47.1.1    | 538 KB    | ############################################################################ | 100%
Preparing transaction: done
Verifying transaction: done
Executing transaction: done
#
# To activate this environment, use
#
#     $ conda activate myenv
#
# To deactivate an active environment, use
#
#     $ conda deactivate

3) C:\Users\anest>conda activate myenv

(myenv) C:\Users\anest>python
Python 3.7.7 (default, May  6 2020, 11:45:54) [MSC v.1916 64 bit (AMD64)] :: Anaconda, Inc. on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>

SUCCESS
