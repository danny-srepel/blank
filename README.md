# blank

3 stages

Stage 1: Build
--------------

  * create working directory
  * create environment file
  * run build script
  * create bundle.tgz
  * update symlinks: rename current -> previous, build -> current

Stage 2: Update Repository
--------------------------

  * create working directory
  * copy bundle.tgz from build machine
  * update symlinks: ...

Stage 3: Deployment
-------------------

  * create working directory
  * copy bundle.tgz from repository
  * untar
  * source environment file
  * run deploy script
  * 

build


work env build links
