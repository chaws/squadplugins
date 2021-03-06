.. image:: https://travis-ci.org/Linaro/squadplugins.svg?branch=master
    :target: https://travis-ci.org/Linaro/squadplugins

SQUAD Plugins
=============

This package contains various plugins for SQUAD

Tradefed
~~~~~~~~

Plugin uses test-attachment test result for retrieving the tarball
which was created during test execution. Tarball contains test_result.xml
file from which all backtraces are extracted and assigned to proper
test results in SQUAD.

LTP
~~~

Plugin uses stdout generated by ltp-pan to retrieve the logs for each
failed test. The logs are assigned based on the test name which is used
as a filtering prefix.

License
-------

Copyright © 2016-2017 Linaro Limited

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
