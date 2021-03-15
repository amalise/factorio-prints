# Sandbox

This book contains two sets of blueprints which make it easy to deploy a build testing environment in a new Sandbox map. Usage is simple:

* Create a new map with Sandbox settings. Ideally turn off biters, pollution, and terrain features. Optionally turn off resources.
* Place one instance of the Border blueprint appropriate for whether you have Bob's entities or not. This blueprint snaps to a grid, making it easier to place the support blueprints if you have started with one of these.
* Place a Supply blueprint just above or below the placed Border. Make sure the power lines connect.
* Place a Launch blueprint next to the Supply blueprint. Make sure the power lines connect.
* Use automatic item generation from Sandbox mode to place the entities in the Launch blueprint. These form the minimum amount of automation necessary for the bots to build everything.
* Place a Trash blueprint somewhere within Roboport coverage, so the bots have some place to store anything which is deconstructed.
* Deploy additional Border blueprints as necessary to expand roboport coverage for your testing procedure.
* Place radars within the border as necessary to reveal map.
* Deploy additional Supply and Trash blueprints as necessary to keep Bot travel time to an appropriate level for your project.

## Sub-Books

* Vanilla (all entities for a Vanilla build)
* Bob's (all entities for a Bob's build)
* Science (blueprint; performs additional science research in case it is needed.)

## Upgrade Planners

None.

## Mod Support

* Bob's
* Loader Redux
* Ama's Storage
* Dectorio

Adding additional mod support would simply require adding additional infinity and passive provider chests in the same manner as exist in the Supply blueprint.