This branch contains Submodules...
To get the full code, use the following command:
git clone --recursive git://github.com/foo/bar.git

<h1>GCconnex</h1>
GCconnex is a project forked from Elgg by the federal government of Canada.

For more information about Elgg visit http://elgg.org/ or see the original Elgg
README below.


<h1>GCconnex Branches on Github</h1>
<ul>
<li><strong>GCconnex:</strong> Stable version that is used in production environments. This is
likely the branch that you want. Use this for contributing to development, and
for production environments.
<li><strong>Staging:</strong> Pre-release version used by TBS-SCT employees for development (not stable).
<li><strong>1.*</strong> branches that are previous versions of Elgg and don't contain modifications.
<li><strong>devel-*</strong> branches used by TBS-SCT employees to share code with each other.
</ul>


<h1>Elgg README</h1>

Elgg
Copyright (c) 2008-2013 See COPYRIGHT.txt

See CONTRIBUTORS.txt for development credits.

Elgg is managed by the Elgg Foundation, a nonprofit organization that was
founded to govern, protect, and promote the Elgg open source social network
engine.  The Foundation aims to provide a stable, commercially and
individually independent organization that operates in the best interest of Elgg
as an open source project.

The project site can be found at http://elgg.org/

The Elgg project was started in 2004 by:
Ben Werdmuller <ben@benwerd.com, http://benwerd.com> and
Dave Tosh <davidgtosh@gmail.com>

Elgg is released under the GNU General Public License (GPL) Version 2 and the
Massachusetts Institute of Technology (MIT) License. See LICENSE.txt 
in the root of the package you downloaded.

For installation instructions, see INSTALL.txt.

For upgrade instructions, see UPGRADE.txt.
=======
Notification Messages
=====================
Bins all the users to respective department/domain, and "caches" them in a .json file. This is done by checking the user email domains.


Contents
--------
1. Module Dependencies
2. Installation Guide
3. Future Development
4. What's new


1. Module Dependencies
----------------------
- requires a CSV file within the data folder (labelled as /gc_dept)
- requires permission to write inside of /gc_dept


2. Installation Guide
----------------------
- place within the /mod directory and allow permission to create and write to /datafolder/gc_dept

	
3. Future Development
---------------------
- allow visibility rules (public/private/logged in)
- allow exporting tabled data to an excel spreadsheet


4. What's new
-------------
June 03 2015
- revisions and documented code (backend)
- issue with regenerating report is fixed, it does not timeout when it tries to do an update
- can only update via the administrative access
- json files has been reduced to two (it would produce 3 json files)
- Government of Canada departments have been made bilingual, users can now toggle between English and French
>>>>>>> d6aee672ebea0aa8c3719db9a3140704e823b57f
