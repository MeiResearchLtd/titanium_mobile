For details, see [ticket #2357](https://app.assembla.com/spaces/pilr-projects/tickets/2357)

# Building

    n 8
    npm install
    cd build
    node scons.js cleanbuild -v 7.5.1.pr10707-MEI ios

# Branching

mei/master are our custom builds.  tibuild.sh will use tagged versions
built on this branch.

1st build will be identical to prj/10707 except with a '-MEI' suffix on the versoin.

