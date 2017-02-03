# How to install

Download the code
```
git clone git://github.com/PanDAWMS/panda-client.git
cd panda-client
```
and install it
```
python setup.py install --prefix=/path/to/install/dir
```
or create the tar ball
```
echo "%_unpackaged_files_terminate_build 0" >> ~/.rpmmacros
QA_SKIP_BUILD_ROOT=1 python setup.py bdist_rpm
rm ~/.rpmmacros
```

# How to use
```
source /path/to/install/dir/etc/panda/panda_setup.[c]sh
prun -h
pathena -h
```

# Release Notes

See ChangeLog.txt

# CVMFS deployment
1. Leave the tar ball under: /afs/cern.ch/user/a/atlpan/www/panda-client
1. Update the release notes: https://twiki.cern.ch/twiki/bin/view/PanDA/PandaTools
1. Request atlas-adc-tier3sw-install to copy on CVMFS


# Acknowledge
Icons from http://iconka.com