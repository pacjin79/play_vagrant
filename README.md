# Vagrant box for play framework

## Note in order for hot reload to work, add the following line to your build.sbt file
`PlayKeys.fileWatchService := play.runsupport.FileWatchService.sbt(2000)`