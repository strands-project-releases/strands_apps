^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package door_pass
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.12 (2016-04-19)
-------------------
* Merge pull request `#44 <https://github.com/strands-project/strands_apps/issues/44>`_ from bfalacerda/indigo-devel
  adding wait to the door passing action
* counting time properly
* avoid asking to hold the door too many times in a row
* getting door open result corectly
* log waits to mongo
* wait a bit more before trying to go through
* code clean and asking people going through to hold the door
* be less conservative on checking if door is open
* make number of readings to consider door open an argument
* add extra nodes to launch file
* door waiting action
* door wait and pass action
* correct door check node name
* Contributors: Bruno Lacerda, Nick Hawes

0.2.5 (2016-11-02)
------------------
* adding door prediction to install targets (`#63 <https://github.com/strands-project/strands_apps/issues/63>`_)
* add speech to move base door pass
* changes to make all doors work at tsc
* add door_wait_and_move_base
* correct bug
* add closed door readings threshold as param to door actions
* correct doorPassing param names. adding log checks param
* Contributors: Bruno Lacerda, Jaime Pulido Fentanes, Nick Hawes

0.2.4 (2016-06-07)
------------------
* sorting out for release and cleaning up hopefully unnecessary import whicih was messing up other imports
* tested and adjusted door passing
* use robot talk interface for speech
* test commit
* Making sure predictions work when no stats are found
* Less prints managing unknown doors prediction
* Avoid double model creation on start-up
* Making sure models are rebuilt when fremen server is restarted
* add door prediction to launch file
* adding build temporal model action
* adding lock, using only successful passes for time modelling, maximum probability now 0.999999
* show hold the door request on the screen
* randomised speech for door pass
* changing sampling strategy and avoiding 0.0 probability
* adapting door prediction to new message format
* adding service for door prediction
* door prediction skeleton with door extraction
* Contributors: Bruno Lacerda, Jaime Pulido Fentanes, Lars Kunze, Nick Hawes, jailander

0.2.3 (2016-04-29)
------------------
* Merge branch 'indigo-devel' of https://github.com/bfalacerda/strands_apps into indigo-devel
* explicit topic unregistering
* extend door stats to include source and target wps
* Merge branch 'indigo-devel' of https://github.com/strands-project/strands_apps into indigo-devel
* Merge branch 'indigo-devel' of https://github.com/bfalacerda/strands_apps into indigo-devel
* Merge branch 'indigo-devel' of https://github.com/strands-project/strands_apps into indigo-devel
* Contributors: Bruno Lacerda, STRANDS

0.2.2 (2016-04-20)
------------------
* Added missing install target
* Contributors: Nick Hawes

0.2.1 (2016-04-19)
------------------

0.2.0 (2016-04-19)
------------------
* 0.1.12
* updated changelogs
* Merge pull request `#44 <https://github.com/strands-project/strands_apps/issues/44>`_ from bfalacerda/indigo-devel
  adding wait to the door passing action
* counting time properly
* avoid asking to hold the door too many times in a row
* getting door open result corectly
* log waits to mongo
* wait a bit more before trying to go through
* code clean and asking people going through to hold the door
* be less conservative on checking if door is open
* make number of readings to consider door open an argument
* add extra nodes to launch file
* door waiting action
* door wait and pass action
* correct door check node name
* Contributors: Bruno Lacerda, Jenkins, Nick Hawes

0.1.11 (2016-04-14)
-------------------

0.1.9 (2015-04-28)
------------------
* launch file for new door pass and check
* Contributors: Bruno Lacerda

0.1.8 (2015-04-22)
------------------
* Merge pull request `#41 <https://github.com/strands-project/strands_apps/issues/41>`_ from bfalacerda/indigo-devel
  door pass improvements
* add door check script
* update package.xml and CMakeLists
* get topological map name for the logging
* logging door checks to mongo
* getting preemption to work
* door pass tweaks
* use only front langer ranges to calculate trans speed
* * disable/enable recoveries from mon nav when door is closed
  * used selected laser readings for the pass door calculations
  * stop using move base config
  * code clean
* cleaner disable of mon nav recoveries
* disable help from mon nav when door is closed
* Added repeat publishing of stopping commands as they weren't behaving in sim. I think it might be the simulation though.
* Limiting back x and rot value during door pass. This makes things a little slower and less repsonsive, but avoids big dangerous movements
* code clean of door_passing.py
* Contributors: Bruno Lacerda, Nick Hawes, STRANDS

0.1.7 (2015-04-17)
------------------

0.1.6 (2015-04-12)
------------------

0.1.4 (2015-03-19)
------------------

0.1.3 (2015-03-16)
------------------

0.1.2 (2014-11-20)
------------------

0.1.0 (2014-11-19)
------------------

0.0.9 (2014-11-09)
------------------

0.0.8 (2014-11-08)
------------------
* final and tested version of loader
* new machine tags
* Contributors: Jaime Pulido Fentanes

0.0.7 (2014-11-06)
------------------

0.0.6 (2014-11-06)
------------------

0.0.5 (2014-11-04)
------------------

0.0.4 (2014-10-30)
------------------

0.0.3 (2014-10-18)
------------------

0.0.2 (2014-10-13)
------------------

0.0.1 (2014-09-23)
------------------
* Added license files
* [door_pass] preparing cmake and package file for release
* Removed scitos prefix for door_pass and ramp_climb
* Contributors: Christian Dondrup
