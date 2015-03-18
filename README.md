# fluentspec

Fork of the little known, but (from what I'm seeing now that I'm playing with) really super simple and elegant unit test framework with bdd flavor. (I forked fluentspec for a quick hack to update to use latest Castle.Core). Had to do this because Raconteur (that I'm investigating updating to VS2013/15) has a dependancy on the old FluentSpec and uses it quite extensively; updating Raconteur meant it was no longer compatible with the old fluentspec, so had to dive in.

Current status of the hack : Migrated fluentspec to use new latest Castle.Core 3.3.3. Also Updated (hacked) assembly version number so that I can simply xcopy the dll for now, instead of having to worry about creating a nuget package. Will speak to Mike at some point soon about pulling these changes into the original.
