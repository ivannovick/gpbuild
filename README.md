# gpbuild
utilities for building Greenplum

# Setup Environment
    export GPORCA_CODE=~/gporca
    export GPOS=~/gpos
    docker build -t gpbuild build
    docker run -v $GPORCA_CODE:/var/src/gporca -v $GPOS_CODE:/var/src/gpos -it gpbuild

# now follow wiki
    https://github.com/greenplum-db/gpos
    https://github.com/greenplum-db/gporca
