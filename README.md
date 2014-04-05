#IBeacon location research
=========================

Links and notes for ibeacon indoor location

##General links
* Bluetooth Indoor Positioning - http://tam.unige.ch/assets/documents/masters/bekkelien/Bekkelien_Master_Thesis.pdf
* Experiment video with comments from J. Krzych from Estimote - http://www.youtube.com/watch?v=dMWEl6GBGqk

##Trilatertion 

* Trilateration math -  http://gis.stackexchange.com/questions/66/trilateration-using-3-latitude-and-longitude-points-and-3-distances
* Trilateration for more than 3 points that do not intersect at one point, nonlinear optimization - http://gis.stackexchange.com/questions/40660/trilateration-algorithm-for-n-amount-of-points
* Trilateration math, precision discussion - http://stackoverflow.com/questions/20332856/triangulate-example-for-ibeacons
* Trilateration math with examples - http://everything2.com/title/Triangulate

##Distance 
* RSSI calculations - http://stackoverflow.com/questions/20416218/understanding-ibeacon-distancing
* Bluetooth LE RSSI for proximity detection iOS - http://stackoverflow.com/questions/15687332/bluetooth-le-rssi-for-proximity-detection-ios/17021642
* How accurate measurements are - http://www.quora.com/Bluetooth-Smart-v4-0-Low-Energy/How-accurate-is-range-measurement-in-bluetooth-Smart

##GPS
* GPS explained, how it deals with errors - http://electronics.howstuffworks.com/gadgets/travel/gps.htm

##Sensor fusion
* How to detect walking with Android accelerometer - http://stackoverflow.com/questions/4993993/how-to-detect-walking-with-android-accelerometer
* WIFI How to improve accuracy of indoor positioning? http://stackoverflow.com/questions/12098122/how-to-improve-accuracy-of-indoor-positioning
* Indoor wireless navigation - http://www.egr.msu.edu/classes/ece480/capstone/spring11/group02/index.html
* Sensor fusion on Android devices - http://www.youtube.com/watch?v=C7JQ7Rpwn2k

##Particle filters
* Particle filter for iBeacon slides - http://blog.andrewcraze.com/2013/12/19/ibeacons-particle-filters-and-cocoaheads/
  * code -  https://bitbucket.org/codeswell/ibeacon-localization/src
  * cocoapod -http://blog.andrewcraze.com/2014/02/27/cdsparticlefilter-available/
* Particle filters vs. simple trilateration - http://forums.udacity.com/questions/1014635/particle-filters-vs-simple-triangulation
* "Continuous location and direction estimation with multiple sensors using particle ﬁltering" - http://elib.dlr.de/44240/1/mfi06-particle-final.pdf
* Online simulation - https://www.cs.utexas.edu/~teammco/misc/particle_filter/
* Pertilce filter for beacons - http://dsp.stackexchange.com/questions/9993/how-to-enhance-pedestrian-dead-reckoning-using-particle-filter
* Difference between Kalaman and Particle filter - http://stats.stackexchange.com/questions/2149/what-is-the-difference-between-a-particle-filter-sequential-monte-carlo-and-a
* A Precise Indoor Localization Approach based on 
Particle Filter and Dynamic Exclusion Techniques - http://www.macrothink.org/journal/index.php/npa/article/viewFile/3717/3396
* Particle filters and their applications - http://web.mit.edu/16.412j/www/html/Advanced%20lectures/Slides/Hsaio_plinval_miller_ParticleFiltersPrint.pdf
* Cursera Artificial Intelligence for Robotics (the course is paid, now  was free in 2012 so maybe it can be still found somwhere)- https://www.udacity.com/course/cs373 

##Math for particle filters
* Generating Normal (Gaussian) Distributed Random Numbers - http://www.protonfish.com/random.shtml
* Probablity density function - https://www.khanacademy.org/math/probability/random-variables-topic/random_variables_prob_dist/v/probability-density-functions
