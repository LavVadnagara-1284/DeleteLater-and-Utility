PS D:\ADIT Codes> cd .\Eyefinity-sync-api\

PS D:\ADIT Codes\Eyefinity-sync-api> git stash push -u -m "Saving all changes before switching"
Saved working directory and index state On v2plasma_yash_beta: Saving all changes before switching

PS D:\ADIT Codes\Eyefinity-sync-api> git checkout develop
branch 'develop' set up to track 'origin/develop'.
Switched to a new branch 'develop'

PS D:\ADIT Codes\Eyefinity-sync-api> git pull origin develop
From https://arsenal.aditadv.xyz/adit/be/Eyefinity-sync-api
 * branch            develop    -> FETCH_HEAD
Already up to date.

PS D:\ADIT Codes\Eyefinity-sync-api> git checkout -b lav_develop
Switched to a new branch 'lav_develop'

PS D:\ADIT Codes\Eyefinity-sync-api> git stash apply
CONFLICT (modify/delete): .gitignore deleted in Updated upstream and modified in Stashed changes.  Version Stashed changes of .gitignore left in tree.
CONFLICT (modify/delete): package-lock.json deleted in Updated upstream and modified in Stashed changes.  Version Stashed changes of package-lock.json left in tree.
CONFLICT (modify/delete): package.json deleted in Updated upstream and modified in Stashed changes.  Version Stashed changes of package.json left in tree.
CONFLICT (modify/delete): src/provider/dto/create-provider.dto.ts deleted in Updated upstream and modified in Stashed changes.  Version Stashed changes of src/provider/dto/create-provider.dto.ts left in tree.
CONFLICT (modify/delete): src/provider/provider.controller.ts deleted in Updated upstream and modified in Stashed changes.  Version Stashed changes of src/provider/provider.controller.ts left in tree.
CONFLICT (modify/delete): src/provider/provider.service.ts deleted in Updated upstream and modified in Stashed changes.  Version Stashed changes of src/provider/provider.service.ts left in tree.    
CONFLICT (modify/delete): tsconfig.json deleted in Updated upstream and modified in Stashed changes.  Version Stashed changes of tsconfig.json left in tree.
On branch lav_develop
Unmerged paths:
  (use "git restore --staged <file>..." to unstage)
  (use "git add/rm <file>..." as appropriate to mark resolution)
        deleted by us:   .gitignore
        deleted by us:   package-lock.json
        deleted by us:   package.json
        deleted by us:   src/provider/dto/create-provider.dto.ts
        deleted by us:   src/provider/provider.controller.ts
        deleted by us:   src/provider/provider.service.ts
        deleted by us:   tsconfig.json

no changes added to commit (use "git add" and/or "git commit -a")

PS D:\ADIT Codes\Eyefinity-sync-api> git add .                  

PS D:\ADIT Codes\Eyefinity-sync-api> git commit -m "first commit - createProvider api work"   
[lav_develop 2587d9a] first commit - createProvider api work
 7 files changed, 20346 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 package-lock.json
 create mode 100644 package.json
 create mode 100644 src/provider/dto/create-provider.dto.ts
 create mode 100644 src/provider/provider.controller.ts
 create mode 100644 src/provider/provider.service.ts
 create mode 100644 tsconfig.json

PS D:\ADIT Codes\Eyefinity-sync-api> npm i

added 13 packages, and audited 1646 packages in 2m

232 packages are looking for funding
  run `npm fund` for details

51 vulnerabilities (7 low, 6 moderate, 38 high)

232 packages are looking for funding
  run `npm fund` for details

51 vulnerabilities (7 low, 6 moderate, 38 high)

To address issues that do not require attention, run:
  npm audit fix
232 packages are looking for funding
  run `npm fund` for details

51 vulnerabilities (7 low, 6 moderate, 38 high)

To address issues that do not require attention, run:
232 packages are looking for funding
  run `npm fund` for details

51 vulnerabilities (7 low, 6 moderate, 38 high)

  run `npm fund` for details

51 vulnerabilities (7 low, 6 moderate, 38 high)

To address issues that do not require attention, run:
  npm audit fix
51 vulnerabilities (7 low, 6 moderate, 38 high)

To address issues that do not require attention, run:
  npm audit fix

To address all issues possible (including breaking changes), run:

To address issues that do not require attention, run:
  npm audit fix

To address all issues possible (including breaking changes), run:
To address issues that do not require attention, run:
  npm audit fix

To address all issues possible (including breaking changes), run:
  npm audit fix --force


To address all issues possible (including breaking changes), run:
  npm audit fix --force

  npm audit fix --force

Some issues need review, and may require choosing
a different dependency.

Run `npm audit` for details.

PS D:\ADIT Codes\Eyefinity-sync-api>

PS D:\ADIT Codes> cd .\Eyefinity-sync-api\

PS D:\ADIT Codes\Eyefinity-sync-api> git pull origin v2plasma_yash_beta
From https://arsenal.aditadv.xyz/adit/be/Eyefinity-sync-api
 * branch            v2plasma_yash_beta -> FETCH_HEAD
error: Your local changes to the following files would be overwritten by merge:
        package-lock.json
Please commit your changes or stash them before you merge.
Aborting
Merge with strategy ort failed.

PS D:\ADIT Codes\Eyefinity-sync-api> git pull origin v2plasma_yash_beta
From https://arsenal.aditadv.xyz/adit/be/Eyefinity-sync-api
 * branch            v2plasma_yash_beta -> FETCH_HEAD
Auto-merging .gitignore
CONFLICT (add/add): Merge conflict in .gitignore
Merge with strategy ort failed.

PS D:\ADIT Codes\Eyefinity-sync-api> git pull origin v2plasma_yash_beta
From https://arsenal.aditadv.xyz/adit/be/Eyefinity-sync-api
 * branch            v2plasma_yash_beta -> FETCH_HEAD
Auto-merging .gitignore
CONFLICT (add/add): Merge conflict in .gitignore
Auto-merging package-lock.json
CONFLICT (add/add): Merge conflict in package-lock.json
Auto-merging package.json
CONFLICT (add/add): Merge conflict in package.json
Auto-merging src/provider/dto/create-provider.dto.ts
CONFLICT (add/add): Merge conflict in src/provider/dto/create-provider.dto.ts
Auto-merging src/provider/provider.controller.ts
CONFLICT (add/add): Merge conflict in src/provider/provider.controller.ts
Auto-merging src/provider/provider.service.ts
CONFLICT (add/add): Merge conflict in src/provider/provider.service.ts
Auto-merging tsconfig.json
CONFLICT (add/add): Merge conflict in tsconfig.json
Merge with strategy ort failed.

PS D:\ADIT Codes\Eyefinity-sync-api> git pull origin v2plasma_yash_beta
From https://arsenal.aditadv.xyz/adit/be/Eyefinity-sync-api
 * branch            v2plasma_yash_beta -> FETCH_HEAD
Auto-merging .gitignore
CONFLICT (add/add): Merge conflict in .gitignore
Auto-merging package-lock.json
CONFLICT (add/add): Merge conflict in package-lock.json
Auto-merging package.json
CONFLICT (add/add): Merge conflict in package.json
Auto-merging src/provider/dto/create-provider.dto.ts
CONFLICT (add/add): Merge conflict in src/provider/dto/create-provider.dto.ts
Auto-merging src/provider/provider.controller.ts
CONFLICT (add/add): Merge conflict in src/provider/provider.controller.ts
Auto-merging src/provider/provider.service.ts
CONFLICT (add/add): Merge conflict in src/provider/provider.service.ts
Auto-merging tsconfig.json
CONFLICT (add/add): Merge conflict in tsconfig.json
Merge with strategy ort failed.

PS D:\ADIT Codes\Eyefinity-sync-api> git pull origin v2plasma_yash_beta
From https://arsenal.aditadv.xyz/adit/be/Eyefinity-sync-api
 * branch            v2plasma_yash_beta -> FETCH_HEAD
Auto-merging .gitignore
CONFLICT (add/add): Merge conflict in .gitignore
Auto-merging package-lock.json
CONFLICT (add/add): Merge conflict in package-lock.json
Auto-merging package.json
CONFLICT (add/add): Merge conflict in package.json
Auto-merging src/provider/dto/create-provider.dto.ts
CONFLICT (add/add): Merge conflict in src/provider/dto/create-provider.dto.ts
Auto-merging src/provider/provider.controller.ts
CONFLICT (add/add): Merge conflict in src/provider/provider.controller.ts
Auto-merging src/provider/provider.service.ts
Merge with strategy ort failed.

PS D:\ADIT Codes\Eyefinity-sync-api> git pull origin v2plasma_yash_beta
From https://arsenal.aditadv.xyz/adit/be/Eyefinity-sync-api
 * branch            v2plasma_yash_beta -> FETCH_HEAD
Auto-merging .gitignore
CONFLICT (add/add): Merge conflict in .gitignore
Auto-merging package-lock.json
CONFLICT (add/add): Merge conflict in package-lock.json
Auto-merging package.json
CONFLICT (add/add): Merge conflict in package.json
Auto-merging src/provider/dto/create-provider.dto.ts
CONFLICT (add/add): Merge conflict in src/provider/dto/create-provider.dto.ts
Auto-merging src/provider/provider.controller.ts
Merge with strategy ort failed.

PS D:\ADIT Codes\Eyefinity-sync-api> git pull origin v2plasma_yash_beta
From https://arsenal.aditadv.xyz/adit/be/Eyefinity-sync-api
 * branch            v2plasma_yash_beta -> FETCH_HEAD
Auto-merging .gitignore
CONFLICT (add/add): Merge conflict in .gitignore
Auto-merging package-lock.json
CONFLICT (add/add): Merge conflict in package-lock.json
Auto-merging package.json
CONFLICT (add/add): Merge conflict in package.json
Merge with strategy ort failed.

PS D:\ADIT Codes\Eyefinity-sync-api> git pull origin v2plasma_yash_beta
From https://arsenal.aditadv.xyz/adit/be/Eyefinity-sync-api
 * branch            v2plasma_yash_beta -> FETCH_HEAD
Auto-merging .gitignore
CONFLICT (add/add): Merge conflict in .gitignore
Auto-merging package-lock.json
CONFLICT (add/add): Merge conflict in package-lock.json
Auto-merging package.json
Merge with strategy ort failed.

PS D:\ADIT Codes\Eyefinity-sync-api> git pull origin v2plasma_yash_beta
From https://arsenal.aditadv.xyz/adit/be/Eyefinity-sync-api
 * branch            v2plasma_yash_beta -> FETCH_HEAD
Auto-merging .gitignore
CONFLICT (add/add): Merge conflict in .gitignore
Auto-merging package-lock.json
CONFLICT (add/add): Merge conflict in package-lock.json
Merge with strategy ort failed.

PS D:\ADIT Codes\Eyefinity-sync-api> git pull origin v2plasma_yash_beta
From https://arsenal.aditadv.xyz/adit/be/Eyefinity-sync-api
 * branch            v2plasma_yash_beta -> FETCH_HEAD
Auto-merging .gitignore
CONFLICT (add/add): Merge conflict in .gitignore
Auto-merging package-lock.json
CONFLICT (add/add): Merge conflict in package-lock.json
Auto-merging package.json
Auto-merging .gitignore
CONFLICT (add/add): Merge conflict in .gitignore
Auto-merging package-lock.json
CONFLICT (add/add): Merge conflict in package-lock.json
Auto-merging package.json
CONFLICT (add/add): Merge conflict in package.json
Auto-merging package-lock.json
CONFLICT (add/add): Merge conflict in package-lock.json
Auto-merging package.json
CONFLICT (add/add): Merge conflict in package.json
Auto-merging src/provider/dto/create-provider.dto.ts
CONFLICT (add/add): Merge conflict in package-lock.json
Auto-merging package.json
CONFLICT (add/add): Merge conflict in package.json
Auto-merging src/provider/dto/create-provider.dto.ts
CONFLICT (add/add): Merge conflict in package.json
Auto-merging src/provider/dto/create-provider.dto.ts
CONFLICT (add/add): Merge conflict in src/provider/dto/create-provider.dto.ts
Auto-merging src/provider/provider.controller.ts
Auto-merging src/provider/dto/create-provider.dto.ts
CONFLICT (add/add): Merge conflict in src/provider/dto/create-provider.dto.ts
Auto-merging src/provider/provider.controller.ts
CONFLICT (add/add): Merge conflict in src/provider/provider.controller.ts
CONFLICT (add/add): Merge conflict in src/provider/dto/create-provider.dto.ts
Auto-merging src/provider/provider.controller.ts
CONFLICT (add/add): Merge conflict in src/provider/provider.controller.ts
Auto-merging src/provider/provider.controller.ts
CONFLICT (add/add): Merge conflict in src/provider/provider.controller.ts
Auto-merging src/provider/provider.service.ts
CONFLICT (add/add): Merge conflict in src/provider/provider.service.ts
Auto-merging tsconfig.json
CONFLICT (add/add): Merge conflict in src/provider/provider.controller.ts
Auto-merging src/provider/provider.service.ts
CONFLICT (add/add): Merge conflict in src/provider/provider.service.ts
Auto-merging tsconfig.json
CONFLICT (add/add): Merge conflict in tsconfig.json
Auto-merging src/provider/provider.service.ts
CONFLICT (add/add): Merge conflict in src/provider/provider.service.ts
Auto-merging tsconfig.json
CONFLICT (add/add): Merge conflict in tsconfig.json
Auto-merging tsconfig.json
CONFLICT (add/add): Merge conflict in tsconfig.json
CONFLICT (add/add): Merge conflict in tsconfig.json
Automatic merge failed; fix conflicts and then commit the result.

PS D:\ADIT Codes\Eyefinity-sync-api> git reset --hard
HEAD is now at 2587d9a first commit - createProvider api work

PS D:\ADIT Codes\Eyefinity-sync-api>
Automatic merge failed; fix conflicts and then commit the result.

PS D:\ADIT Codes\Eyefinity-sync-api> git reset --hard
HEAD is now at 2587d9a first commit - createProvider api work

PS D:\ADIT Codes\Eyefinity-sync-api> git checkout v2plasma_yash_beta
Switched to branch 'v2plasma_yash_beta'
Your branch is up to date with 'origin/v2plasma_yash_beta'.

PS D:\ADIT Codes\Eyefinity-sync-api> git checkout v2plasma_beta_develop
Switched to branch 'v2plasma_beta_develop'
Your branch is up to date with 'origin/v2plasma_beta_develop'.

PS D:\ADIT Codes\Eyefinity-sync-api> git pull
remote: Enumerating objects: 53, done.
remote: Counting objects: 100% (43/43), done.
remote: Compressing objects: 100% (37/37), done.
remote: Total 53 (delta 16), reused 5 (delta 5), pack-reused 10 (from 1)
Unpacking objects: 100% (53/53), 57.65 KiB | 66.00 KiB/s, done.
From https://arsenal.aditadv.xyz/adit/be/Eyefinity-sync-api
   067b47d..cdad613  v2plasma_beta_develop   -> origin/v2plasma_beta_develop
   73ee934..e8573d3  beta                    -> origin/beta
   f8d9c06..1f5c679  poc_sagar_realtime_sync -> origin/poc_sagar_realtime_sync
   4ddfa8a..dde8920  v2plasma_prateek        -> origin/v2plasma_prateek
Updating 067b47d..cdad613
Fast-forward
 .../appointment-location.controller.ts             |   6 +-
   73ee934..e8573d3  beta                    -> origin/beta
   f8d9c06..1f5c679  poc_sagar_realtime_sync -> origin/poc_sagar_realtime_sync
   4ddfa8a..dde8920  v2plasma_prateek        -> origin/v2plasma_prateek
Updating 067b47d..cdad613
Fast-forward
 .../appointment-location.controller.ts             |   6 +-
 .../appointment-location.module.ts                 |   3 +-
   f8d9c06..1f5c679  poc_sagar_realtime_sync -> origin/poc_sagar_realtime_sync
   4ddfa8a..dde8920  v2plasma_prateek        -> origin/v2plasma_prateek
Updating 067b47d..cdad613
Fast-forward
 .../appointment-location.controller.ts             |   6 +-
 .../appointment-location.module.ts                 |   3 +-
Updating 067b47d..cdad613
Fast-forward
 .../appointment-location.controller.ts             |   6 +-
 .../appointment-location.module.ts                 |   3 +-
Fast-forward
 .../appointment-location.controller.ts             |   6 +-
 .../appointment-location.module.ts                 |   3 +-
 .../appointment-location.controller.ts             |   6 +-
 .../appointment-location.module.ts                 |   3 +-
 .../appointment-location.module.ts                 |   3 +-
 .../appointment-location.service.ts                |  17 +-
 src/appointment/appointment.controller.ts          |  11 ++
 .../appointment-location.service.ts                |  17 +-
 src/appointment/appointment.controller.ts          |  11 ++
 src/appointment/appointment.service.ts             | 177 ++++++++++++++++++---
 src/appointment/queries.service.ts                 |   3 +
 src/appointment/appointment.controller.ts          |  11 ++
 src/appointment/appointment.service.ts             | 177 ++++++++++++++++++---
 src/appointment/queries.service.ts                 |   3 +
 src/appointment/appointment.service.ts             | 177 ++++++++++++++++++---
 src/appointment/queries.service.ts                 |   3 +
 src/appointment/queries.service.ts                 |   3 +
 .../block-appointment.controller.ts                |  16 +-
 src/block-appointment/block-appointment.service.ts | 137 ++++++++++++----
 src/block-appointment/block-appointment.service.ts | 137 ++++++++++++----
 .../dto/create-block-appointment.dto.ts            | 105 ++++++++++++
 src/block-appointment/queries.service.ts           |   2 +-
 src/patient/patient.service.ts                     |  69 ++++++--
 src/shared/services/shared/shared.service.ts       |  22 +++
 12 files changed, 488 insertions(+), 80 deletions(-)

PS D:\ADIT Codes\Eyefinity-sync-api> git checkout -b lav_beta
Switched to a new branch 'lav_beta'
 src/block-appointment/block-appointment.service.ts | 137 ++++++++++++----
 .../dto/create-block-appointment.dto.ts            | 105 ++++++++++++
 src/block-appointment/queries.service.ts           |   2 +-
 src/patient/patient.service.ts                     |  69 ++++++--
 src/shared/services/shared/shared.service.ts       |  22 +++
 12 files changed, 488 insertions(+), 80 deletions(-)

PS D:\ADIT Codes\Eyefinity-sync-api> git checkout -b lav_beta
 src/block-appointment/block-appointment.service.ts | 137 ++++++++++++----
 .../dto/create-block-appointment.dto.ts            | 105 ++++++++++++
 src/block-appointment/queries.service.ts           |   2 +-
 src/patient/patient.service.ts                     |  69 ++++++--
 src/block-appointment/block-appointment.service.ts | 137 ++++++++++++----
 .../dto/create-block-appointment.dto.ts            | 105 ++++++++++++
 src/block-appointment/queries.service.ts           |   2 +-
 src/block-appointment/block-appointment.service.ts | 137 ++++++++++++----
 .../dto/create-block-appointment.dto.ts            | 105 ++++++++++++
 src/block-appointment/block-appointment.service.ts | 137 ++++++++++++----
 .../dto/create-block-appointment.dto.ts            | 105 ++++++++++++
 src/block-appointment/queries.service.ts           |   2 +-
 src/patient/patient.service.ts                     |  69 ++++++--
 src/shared/services/shared/shared.service.ts       |  22 +++
 12 files changed, 488 insertions(+), 80 deletions(-)

PS D:\ADIT Codes\Eyefinity-sync-api> git checkout -b lav_beta
Switched to a new branch 'lav_beta'

PS D:\ADIT Codes\Eyefinity-sync-api>