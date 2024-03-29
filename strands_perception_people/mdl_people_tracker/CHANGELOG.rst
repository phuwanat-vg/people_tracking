^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package mdl_people_tracker
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.10.0 (2020-02-12)
-------------------

1.9.0 (2019-12-19)
------------------

1.8.1 (2019-05-21)
------------------

1.8.0 (2018-10-01)
------------------

1.7.0 (2018-09-04)
------------------

1.6.0 (2017-09-01)
------------------
* changelogs
* changed from cdondrup to marc
* Contributors: Marc Hanheide

1.5.5 (2017-07-02)
------------------
* updated changelogs
* Merge pull request `#216 <https://github.com/strands-project/strands_perception_people/issues/216>`_ from sbreuers/indigo-devel
  Adds 2d tracked persons message
* added tracked person 2d messages, published by mdl tracker for further analysis components
* Contributors: Jenkins, Lucas Beyer, sbreuers

1.5.4 (2016-11-03)
------------------
* updated changelogs
* Contributors: Jenkins

1.5.3 (2016-07-04)
------------------
* updated changelogs
* Contributors: Jenkins

1.5.2 (2016-07-02 20:52)
------------------------
* updated changelogs
* Contributors: Jenkins

1.5.1 (2016-07-02 17:54)
------------------------
* updated changelogs
* Merge branch 'indigo-devel' of https://github.com/strands-project/strands_perception_people into people_sitting_feature
* Contributors: Ferdian Jovan, Jenkins

1.5.0 (2016-03-15)
------------------
* updated changelogs
* Contributors: Jenkins

1.4.0 (2016-02-17)
------------------
* updated changelogs
* Contributors: Jenkins

1.3.1 (2016-02-11)
------------------
* updated changelogs
* Merge remote-tracking branch 'upstream/indigo-devel' into indigo-devel
* Contributors: Alexander Hermans, Jenkins

1.3.0 (2016-02-01)
------------------
* updated changelogs
* Contributors: Jenkins

1.2.1 (2016-01-28)
------------------
* updated changelogs
* Contributors: Jenkins

1.2.0 (2015-11-11)
------------------
* updated changelogs
* Contributors: Jenkins

1.1.8 (2015-09-03)
------------------
* updated changelogs
* Contributors: Jenkins

1.1.7 (2015-08-25)
------------------

1.1.6 (2015-06-24)
------------------
* updated changelogs
* Merge branch 'indigo-devel' of https://github.com/strands-project/strands_perception_people into indigo-devel
* 1.1.5
* updated changelogs
* 1.1.4
* updated changelogs
* Merge branch 'indigo-devel' of https://github.com/strands-project/strands_perception_people into indigo-devel
* Contributors: Ferdian Jovan, Jenkins

1.1.5 (2015-05-22)
------------------
* updated changelogs
* Contributors: Jenkins

1.1.4 (2015-05-10)
------------------
* updated changelogs
* Contributors: Jenkins

1.1.3 (2015-04-10)
------------------
* updated changelogs
* Merge branch 'indigo-devel' of http://github.com/strands-project/strands_perception_people into topolog
  Conflicts:
  bayes_people_tracker_logging/launch/logging.launch
* Contributors: Christian Dondrup, Jenkins

1.1.2 (2015-04-07)
------------------
* updated changelogs
* Contributors: Jenkins

1.1.1 (2015-04-03)
------------------
* updated changelogs
* Contributors: Jenkins

1.1.0 (2015-04-02)
------------------
* Merge pull request `#157 <https://github.com/strands-project/strands_perception_people/issues/157>`_ from cdondrup/respawn
  Adding respawn flags
* Adding respawn flags
  Closes `#152 <https://github.com/strands-project/strands_perception_people/issues/152>`_
  Bad workaround for `#156 <https://github.com/strands-project/strands_perception_people/issues/156>`_ and `#76 <https://github.com/strands-project/strands_perception_people/issues/76>`_
* Merge pull request `#148 <https://github.com/strands-project/strands_perception_people/issues/148>`_ from vonovak/rebasing-stuff-forreal
  work towards associating UBD and tracker output
* work towards associating UBD and tracker output
* Contributors: Christian Dondrup, Vojtech Novak

1.0.0 (2015-03-10)
------------------
* Updating changelogs.
* Contributors: Christian Dondrup

0.1.4 (2015-03-06)
------------------
* updated changelogs
* Merge branch 'indigo-devel' of https://github.com/strands-project/strands_perception_people into indigo-devel
* Contributors: Ferdian Jovan, Jenkins

0.1.3 (2015-02-25)
------------------
* updated changelogs
* Merge branch 'indigo-devel' of https://github.com/strands-project/strands_perception_people into indigo-devel
* Contributors: Ferdian Jovan, Jenkins

0.1.2 (2015-02-20)
------------------

0.1.1 (2015-02-18 18:37)
------------------------
* updated changelogs
* Contributors: Jenkins

0.1.0 (2015-02-18 16:59)
------------------------
* Updating changelogs
* Merge pull request `#130 <https://github.com/strands-project/strands_perception_people/issues/130>`_ from cdondrup/fixomatic
  Preparing indigo-devel to be released
* Setting correct version number. The changelogs will be regenerated because the ones from the release branch would not be consistent with the changes made in the devel branch.
* Merged latest version from indigo-devel
* Merge pull request `#128 <https://github.com/strands-project/strands_perception_people/issues/128>`_ from cdondrup/ground_hog
  Removing strands_ground_hog from indigo-devel after it has been moved to attic
* Removed strands_ground_hog
* removing HOG launch files
* Changed launch files to new format.
* Merge pull request `#114 <https://github.com/strands-project/strands_perception_people/issues/114>`_ from cdondrup/hydro-devel
  Changed launch files to new format.
* Changed launch files to new format.
* Merge pull request `#109 <https://github.com/strands-project/strands_perception_people/issues/109>`_ from cdondrup/topics
  Making camera topic reconfigurable
* Making camera topic reconfigurable
  So far only the camera namespace was configurable but that introduced an implicit dependency on the openni_wrapper.
  With these changes the whole topic is reconfigurable via a parameter, e.g.:
  camera_namespace:=/my_cam
  depth_image:=/depth/image
  results in `/my_cam/depth/image` as a topic for the depth image. So `camera_namespace` + `depth_image` = the topic on which to look for the depth image.
* Merge pull request `#105 <https://github.com/strands-project/strands_perception_people/issues/105>`_ from lucasb-eyer/hydro-devel
  Fixing `#101 <https://github.com/strands-project/strands_perception_people/issues/101>`_ (Licenses)
* Added LICENSE files. Fixes `#101 <https://github.com/strands-project/strands_perception_people/issues/101>`_
* Merge pull request `#100 <https://github.com/strands-project/strands_perception_people/issues/100>`_ from cdondrup/hydro-devel
  Renaming mdl-People_tracker launch files
* renaming mdl-People_tracker launch files
  to comply with the rest of the structure and to make releasing easier.
* Merge pull request `#98 <https://github.com/strands-project/strands_perception_people/issues/98>`_ from strands-project/rename
  Renamed strands_pedestrian_tracking to mdl_people_tracker
* Renamed strands_pedestrian_tracking to mdl_people_tracker
  This also includes renaming the messages and most of the parameters.
* Contributors: Christian Dondrup, Lucas Beyer
