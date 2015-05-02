The following project is a working guitar tuner app.
"Working" is a little bit of over statement as it could work much (_much_) better, but it compiles and runs and do some sound analyzing using FFT over JND.

#### Some project quick start notes ####

  * For those of you who are using IntelliJ with the android plug-in,setting up a project should be quite easy:
    1. After checking out the code go to File -> New Project -> Create Java project from existing sources and point to your local trunk folder.
    1. Once project is created go to Run -> Edit Configurations -> Add New (+) and select the android facet.
    1. On the Run/Debug Configurations screen:  point Activity to Main class in project-home/src/../activities/Main and set "Before launch" to "Run Ant target" and point to the build.xml file in the project.
    1. You might want to consider replacing the android\_rules.xml with the one enclosed in the project if you encounter any weird build/sign errors.

  * I Don't know about eclipse but I guess it should be fairly easy as well

  * On the subject of how to build the NDK lib - on another wiki...