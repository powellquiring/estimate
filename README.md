estimate
========

Estimation game 8/10/2014

## development setup
* install git
* download an unzip the jdk
* download unzip grails 2.4.3 - 
* ggts groovy-grails-tool-suite-3.6.0.RELEASE-e4.4-win32-x86_64
* git clone https://github.com/powellquiring/estimate.git
 * use command line git since eclipse ggts import git project does not work
 * do this in HOME/git which will create: estimate/
   * .git
   * estimate/a - yes estimate/estimate/.project is the elcipse project file
* ggts groovy-grails-tool-suite-3.6.0.RELEASE-e4.4-win32-x86_64
 * manually add the grails unzipped above in the windows > preferences > groovy > grails - add and check
 * change browser to default browser - Windows > browser > default browser - I like this better
 * File > Import.. > Git.Projects from git > Existing local repository > locate HOME/git/estimate/.git
  * import existing project HOME/git/estimate/estimate
 * eclipse will complain - run the app to create the missing files
 * grails > run-app - this will fix the eclipse problems

## bluemix setup
* install cloud foundry

