XMPP Lift Module
==================

This module provides support for XMLL (eXtensible Messaging and Presence Protocol, a.k.a Jabber)

To include this module in your Lift project, update your `libraryDependencies` in `build.sbt` to include:

*Lift 2.6.x* for Scala 2.9 and 2.10:

    "net.liftmodules" %% "xmpp_2.6" % "1.2"

*Lift 2.5.x* for Scala 2.9 and 2.10:

    "net.liftmodules" %% "xmpp_2.5" % "1.2"

*Lift 3.0.x* for Scala 2.10:

    "net.liftmodules" %% "xmpp_3.0" % "1.2-SNAPSHOT"


Documentation
=============

See _Exploring Lift_ [chapter 13.5](http://exploring.liftweb.net/master/index-13.html) for example of using this module.

**Note:** The module package changed from `net.liftweb.xmpp` to `net.liftmodules.xmpp` in May 2012.  Please consider this when referencing documentation written before that date.


Notes for module developers
===========================

* The [Jenkins build](https://liftmodules.ci.cloudbees.com/job/xmpp/) is triggered on a push to master.



