## 1.1.4 (2017-01-05)

* Expose schedule time of a job

## 1.1.3 (2016-11-09)

* Add an alternative to register a `JobCreator`, if you don't have access to the `Application` class

## 1.1.2 (2016-10-19)

* Remove packaged `R.txt` file

## 1.0.15 (2016-10-19)

* Remove packaged `R.txt` file

## 1.1.1 (2016-10-19)

* Add test option to override minimum interval and flex for testing purposes
* Fix issue that periodic jobs were accidentally canceled

## 1.0.14 (2016-10-19)

* Fix issue that periodic jobs were accidentally canceled

## 1.1.0 (2016-09-23)

* Bump SDK version to 24
* Add option to specify flex parameter for periodic jobs
 * Add support for flex parameter with GCM proxy
 * Add API 24 proxy with support for flex parameter
 * Add a flex support mode for all other APIs
* Add API 19 proxy supporting an execution window
* Add NOT_ROAMING network type
* Adjust minimum interval for periodic jobs
* Add GCM service declaration in library manifest

## 1.0.13 (2016-09-12)

* Fix crash while acquiring wake lock
* Check boot permission only when persisted flag is set to true

## 1.0.12 (2016-08-29)

* Fix IllegalArgumentException with GCM API, see #72

## 1.0.11 (2016-08-09)

* Fix overflow for too large execution windows
* Fix immediately starting jobs with JobScheduler if the execution window is too large

## 1.0.10 (2016-07-25)

* Create the JobManager in all API services

## 1.0.9 (2016-07-18)

* Bug fixes

## 1.0.8 (2016-07-05)

* Make PlatformAlarmReceiver intent explicit, fixes #56
* Delete a job after it has finished, otherwise reschedule if app is crashing while job is running, fixes #55
* Extend Params class with more parameters from the job request, fixes #52
* Cache only 20 finished jobs to free up memory, fixes #57

## 1.0.7 (2016-06-03)

* Weird bug fixes

## 1.0.6 (2016-05-20)

* Clean up orphaned jobs after the database was deleted

## 1.0.5 (2016-05-03)

* Fix "WakeLock under-locked" crash

## 1.0.4 (2016-03-13)

* Add option to update any preexisting jobs 

## 1.0.3 (2016-02-29)

* Bug fixes

## 1.0.2 (2016-01-05)

* Add option to attach multiple job creators 

## 1.0.1 (2015-12-18)

* Catch certain exceptions and runtime crashes

## 1.0.0 (2015-08-20)

* Initial release
