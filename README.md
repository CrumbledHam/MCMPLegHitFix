# MCMPLegHitFix

A fix for not being able to hit the legs of mobs if the mobs eyes are covered.

The only modification this jarmod has is removing the `canEntityBeSeen()` check from `if(entity3 != null && this.playerEntity.canEntityBeSeen(entity3) && this.playerEntity.getDistanceSqToEntity(entity3) < 36.0D)`.

## Installation

Pick a zip for your version and drag the files from the zip into the server jar file.


