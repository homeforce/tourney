1.2.1 / 2015-12-20
==================
  * Fixed a bug where `score` could return an unexpected truthy integer rather than a bool

1.2.0 / 2015-12-15
==================
  * Bump tournament for configurable `log` handlers.

1.1.0 / 2014-10-11
==================
  * Add `::state` and `.restore` to mimic Tournament API

1.0.0 / 2014-10-10
==================
  * **Complete rewrite of tourney** with full documentation
  * Parallel support removed
  * API now mimics Tournament and proxies onto instances where present
  * Added coverage

0.2.2 / 2014-03-23
==================
  * Fixed `.stageComplete()` never being set to true for rounds > 2

0.2.1 / 2014-03-09
==================
  * Lock down scoring of revealed old stage tournaments (inconsistency bug #5)

0.2.0 / 2013-12-23
==================
  * tournaments now exposed, and scoring done via events on new version of tournament

0.1.0 / 2013-12-04
==================
  * first release
