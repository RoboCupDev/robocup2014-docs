Introduction
============
The system called “tournamenter” was made specificly for the RoboCup 2014,
with the intention of working locally, and serving as a helper for storing
and sharing real-time information about scores, rounds, soccer matches and
most of what spectators and teams need to know.

One of the objectives was to allow others (even a small competition), to
easily use it. The second objective was to make it useful for most of the
tournament types, currently in RoboCup (Rescue, Soccer, Dance, @Home…), and
also outside RoboCup (FLL, Sumo…).

For every tournament one system is required. We didn’t want to mix things
up. During RoboCup, about 20 systems like this will be running
simultaneously to provide access to Chairs for each league.

This document provides an easy introduction into how to effectively use the
system and make use of its features to simplify the organizational
processes that are a necessary part of any RoboCup.


Basic terms
-----------

Before we start talking about the system there are a few names that are
good to know. Here is a collection of helper names with their meaning:

- **View**: Something that will be shown to spectators. It has a group of
  Pages. Like a (Power Point) presentation.
- **Page**: A single slide on a View. Imagine it as a slide of a presentation.
- **Page type**: There are many page-types, such as: Table View, CSV View,
  Message View, Group View...
- **Group**: A group is composed of soccer matches. A group also generates a
  scoring table in soccer style.
- **Table**: A table representing Teams in it’s row, and scores in its
  columns.
- **Score**: A single entry of points for a team.
- **Final Score:** Computed with all its Scores. You can define a custom
  function to compute it.
- **Module**: A part of the system.


