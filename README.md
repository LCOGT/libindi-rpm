# libindi rpm creator
This project contains a spec file that pulls the latest version of libindi from the github repo and builds a set of rpms.

## Pre-requisites

rpmdevtools package must be installed


rpmdev-setuptree
cp libindi.spec ~/rpmbuild/SPECS/
spectool -g -R ~/rpmbuild/SPECS/libindi.spec
rpmbuild -ba ~/rpmbuild/SPECS/libindi.spec 

