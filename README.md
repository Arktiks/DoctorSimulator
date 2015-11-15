# DoctorSimulator
Game made for 2015 November [#UE4JAM](https://forums.unrealengine.com/showthread.php?90285-November-UE4JAM-November-12-15th-Theme-to-be-announced!).

#### Level Clear Conditions
* At least one non-infected cell must remain.
* Destroy all infected cells.
* Timer doesn't run out.

You can destroy objects by **left-clicking** them. If two infected cells collide they will destroy each other. If non-infected cell collides with an infected cell they will stick together.

#### Known Problems
* Physics simulation may be inconsistent between retries.
* If three or more cells cluster together clicking one of them will destroy only two by random. Intended feature was to destroy the whole cluster.
