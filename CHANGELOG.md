#### 1.14.0: Release


#### 1.13.0: Release

 - Pin reusable workflows to v0.1.0 (#123) @ppawlowski
 - Force Resource limits to Strings (#122) @hardillb

#### 1.12.1: Release

 - Run promises in order (#115) @hardillb
 - Expose mem/cpu limits (#119) @hardillb
 - Update ff references in package.json (#117) @knolleary
 - Change repo references in workflows after github org rename (#113) @ppawlowski
 
#### 1.12.0: Release

 - Publish nightly package to npmjs (#112) @ppawlowski
 - Pin reusable workflow to commit SHA (#111) @ppawlowski
 - Disable scheduled package build (#110) @ppawlowski

#### 1.11.0: Release

 - Add flowforge container build dispatch in the node package build pipeline (#108) @ppawlowski
 - Bump kubernetes client (#107) @hardillb
 - Bump word-wrap from 1.2.3 to 1.2.5 (#105) @app/dependabot
 - FIX: Publish package on schedule (#104) @ppawlowski
 - FIX: Allow publish only when changes are pushed to `main` branch (#103) @ppawlowski

#### 1.10.1: Release

 - Fix editor path (#101) @hardillb
 - Introduce package publish pipeline (#99) @ppawlowski
 - Move to CluserIP (#100) @hardillb
 - Remove evreything on suspend (#98) @hardillb

#### 1.10.0: Release

 - Added support for annotation substitutions (#95) @dfulgham
 - Editors: allow optional service account linkage (#92) @elenaviter
 - Chore: Set root flag in eslint (#93) @Pezmc

#### 1.9.0: Release

 - Support for changing the base domain (#88) @hardillb
 - Add package-lock.json (#89) @Pezmc

#### 1.8.0: Release

 - HA: multiple instance replicas (#85) @hardillb
 - Log failures if not restarting susspended project (#86) @hardillb

#### 1.7.0: Release

 - Editor configuration from process environment (#80) @andreikop

#### 1.6.0: Release


#### 1.5.0: Release

 - Add Support for Private Certificate Authorities (#78) @hardillb

#### 1.4.0: Release

 - Fix deployment state (#72) @hardillb
 - Remove ALB annotations (#74) @hardillb
 - Pod to deployment gradual (#71) @hardillb

#### 1.3.0: Release


#### 1.2.0: Release


#### 1.1.0: Release

 - Add getDefaultStackProperies (#63) @hardillb
 - Env Var values must be strings (#64) @hardillb
 - Add flags to inhibit TCP/UDP inbound connections (#60) @Steve-Mcl
 - Only set the nodeSelector if in options (#62) @hardillb

#### 1.0.0: Release

 - Improve project status & detail reporting to frontend (#58) @Steve-Mcl
 - Update eslint rules (#57) @knolleary
 - Force container to run as UID 1000 (#56) @hardillb

#### 0.10.0: Release

 - Prefix service names if they start with a number (#53) @hardillb

#### 0.9.0: Release

 - Make use of project.safename (#51) @hardillb

#### 0.8.0: Release

 - Add licenseType to launcher env (#48) @knolleary
 - Add FORGE_BROKER_* credentials to launcher env (#44) @knolleary
 - add env var FORGE_TEAM_ID (#47) @Steve-Mcl

#### 0.7.0: Release

 - Add startup check for status (#45) @hardillb

#### 0.6.0: Release

 - Map FlowForge logout to nodered auth/revoke (#39) @Steve-Mcl
 - Throw proper errors when actions performed on unknown project (#40) @knolleary
 - Add FORGE_NR_SECRET env if project has credSecret set (#38) @knolleary
 - Add description to stack properties (#36) @hardillb

#### 0.5.0: Release

 - Ensure latest version of contianer is always pulled (#33) @hardillb

#### 0.4.0: Release

 - Fix ingress annotations on AWS (#30) @hardillb
 - Deal with project not in internal cache (#29) @hardillb
 - Update to new driver api and lifecycle (#27) @knolleary
 - Update project automation (#28) @knolleary
 - Fix typo in pod limits (#25) @hardillb
 - Fix CPU % Validator regex (#23) @hardillb
 - Allow Node selectors to be set in flowforge.yml (#22) @hardillb
 - Only add AWS Ingress annotation on AWS (#21) @hardillb

#### 0.3.0: Release

 - Restart missing projects (#12) @hardillb
 - Add stack support (#16) @hardillb
 - Stop driver setting baseURL/forgeURL (#17) @knolleary
 - Automate npm publish on release (#15) @hardillb

#### 0.2.0: Release

 - Bump kube client version to pick up deps (#13) @hardillb
 - add Shutdown hook (#11) @hardillb
 - Add CPU/Memory limits to projects (#10) @hardillb
 - Match url schema to base_url (#9) @hardillb
 - Add project to ALB group (#8) @hardillb
