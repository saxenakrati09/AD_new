# AD_new

Inside the folder,
run
"make"
to build the executable "./arcsim" in bin folder.

To check if it is working,
run
"./bin/arcsim simulate conf/sphere.json"

Also, please change the file path in src/main.cpp (if required)
here
"
dart::simulation::WorldPtr myWorld
      = dart::utils::SkelParser::readWorld("AD_new/data/skel/MyManipulator2.skel");
  assert(myWorld != nullptr);
"

  to the /data/skel/filename path
  
