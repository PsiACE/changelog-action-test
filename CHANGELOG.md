# Changelog

## [v3.0.0-beta.4](https://github.com/casbin/casbin/tree/v3.0.0-beta.4) (2020-09-04)

[Full Changelog](https://github.com/casbin/casbin/compare/v3.0.0-beta.3...v3.0.0-beta.4)

**Merged pull requests:**

- feat: add mutex to model [\#587](https://github.com/casbin/casbin/pull/587) ([dovics](https://github.com/dovics))

## [v3.0.0-beta.3](https://github.com/casbin/casbin/tree/v3.0.0-beta.3) (2020-08-26)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.11.2...v3.0.0-beta.3)

**Merged pull requests:**

- fix: remove unwanted AddMatchingFunc and AddDomainMatchingFunc name argument. [\#509](https://github.com/casbin/casbin/pull/509) ([divy9881](https://github.com/divy9881))

## [v2.11.2](https://github.com/casbin/casbin/tree/v2.11.2) (2020-08-26)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.11.1...v2.11.2)

**Merged pull requests:**

- fix: update enforcer logic when there is no policy found [\#558](https://github.com/casbin/casbin/pull/558) ([lucas-57blocks](https://github.com/lucas-57blocks))

## [v2.11.1](https://github.com/casbin/casbin/tree/v2.11.1) (2020-08-24)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.11.0...v2.11.1)

**Fixed bugs:**

- \[Bug\] Pattern matching in RBAC not working [\#577](https://github.com/casbin/casbin/issues/577)

**Merged pull requests:**

- fix: compatible RBAC in ABAC [\#583](https://github.com/casbin/casbin/pull/583) ([nodece](https://github.com/nodece))

## [v2.11.0](https://github.com/casbin/casbin/tree/v2.11.0) (2020-08-21)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.10.0...v2.11.0)

**Implemented enhancements:**

- suggestion: add a rule of effect "Allow-override" [\#496](https://github.com/casbin/casbin/issues/496)

**Fixed bugs:**

- \[Bug\]RBAC Verification incorrect [\#575](https://github.com/casbin/casbin/issues/575)

**Merged pull requests:**

- feat: add LoadIncrementalFilteredPolicy to append policies [\#582](https://github.com/casbin/casbin/pull/582) ([DarkSorrow](https://github.com/DarkSorrow))

## [v2.10.0](https://github.com/casbin/casbin/tree/v2.10.0) (2020-08-14)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.9.1...v2.10.0)

**Merged pull requests:**

- feat: add a rule of effect "Allow-override" [\#497](https://github.com/casbin/casbin/pull/497) ([ticktap](https://github.com/ticktap))

## [v2.9.1](https://github.com/casbin/casbin/tree/v2.9.1) (2020-08-14)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.9.0...v2.9.1)

**Implemented enhancements:**

- Make a Casbin middleware for "gorilla/mux" web framework [\#551](https://github.com/casbin/casbin/issues/551)

**Closed issues:**

- RoleManager for Mysql [\#559](https://github.com/casbin/casbin/issues/559)

**Merged pull requests:**

- fix: spelling error in comment of management\_api.go [\#565](https://github.com/casbin/casbin/pull/565) ([Xhy-5000](https://github.com/Xhy-5000))

## [v2.9.0](https://github.com/casbin/casbin/tree/v2.9.0) (2020-08-07)

[Full Changelog](https://github.com/casbin/casbin/compare/v3.0.0-beta.2...v2.9.0)

**Merged pull requests:**

- feat: add CasbinJsGetUserPermission [\#557](https://github.com/casbin/casbin/pull/557) ([kingiw](https://github.com/kingiw))

## [v3.0.0-beta.2](https://github.com/casbin/casbin/tree/v3.0.0-beta.2) (2020-08-06)

[Full Changelog](https://github.com/casbin/casbin/compare/v3.0.0-beta.1...v3.0.0-beta.2)

**Merged pull requests:**

- feat: Distributed plugin Dispatcher [\#555](https://github.com/casbin/casbin/pull/555) ([dovics](https://github.com/dovics))

## [v3.0.0-beta.1](https://github.com/casbin/casbin/tree/v3.0.0-beta.1) (2020-08-05)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.8.7...v3.0.0-beta.1)

**Fixed bugs:**

- Multi-threading contention caused by concurrent map writes [\#552](https://github.com/casbin/casbin/issues/552)

**Merged pull requests:**

- feat: Autoloading in cachedenforcer [\#538](https://github.com/casbin/casbin/pull/538) ([GopherJ](https://github.com/GopherJ))
- test: remove print test data [\#536](https://github.com/casbin/casbin/pull/536) ([nodece](https://github.com/nodece))
- feat: make enforcer.ClearPolicy different with Model.ClearPolicy [\#535](https://github.com/casbin/casbin/pull/535) ([GopherJ](https://github.com/GopherJ))
- fix: update module to v3 [\#525](https://github.com/casbin/casbin/pull/525) ([nodece](https://github.com/nodece))
- fix: Quick return. [\#472](https://github.com/casbin/casbin/pull/472) ([divy9881](https://github.com/divy9881))

## [v2.8.7](https://github.com/casbin/casbin/tree/v2.8.7) (2020-07-31)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.8.6...v2.8.7)

**Implemented enhancements:**

- SyncedCachedEnforcer [\#537](https://github.com/casbin/casbin/issues/537)

**Merged pull requests:**

- fix: add checks fieldValues to remove filtered policy [\#549](https://github.com/casbin/casbin/pull/549) ([nodece](https://github.com/nodece))
- chore: add lint and benchmark to GitHub Actions [\#531](https://github.com/casbin/casbin/pull/531) ([nodece](https://github.com/nodece))
- test: fix rbac\_api\_with\_domains\_test lint error [\#530](https://github.com/casbin/casbin/pull/530) ([nodece](https://github.com/nodece))

## [v2.8.6](https://github.com/casbin/casbin/tree/v2.8.6) (2020-07-16)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.8.5...v2.8.6)

**Fixed bugs:**

- Batch operation will be add repeatedly [\#517](https://github.com/casbin/casbin/issues/517)

**Merged pull requests:**

- fix: add cpp in supported languages. [\#529](https://github.com/casbin/casbin/pull/529) ([divy9881](https://github.com/divy9881))
- test: fix golangci-lint error [\#528](https://github.com/casbin/casbin/pull/528) ([nodece](https://github.com/nodece))

## [v2.8.5](https://github.com/casbin/casbin/tree/v2.8.5) (2020-07-15)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.8.4...v2.8.5)

**Merged pull requests:**

- fix: duplicated policies inside rules to add [\#526](https://github.com/casbin/casbin/pull/526) ([GopherJ](https://github.com/GopherJ))

## [v2.8.4](https://github.com/casbin/casbin/tree/v2.8.4) (2020-07-15)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.8.3...v2.8.4)

**Implemented enhancements:**

- Add  DeleteRolesForUserInDomain [\#522](https://github.com/casbin/casbin/issues/522)

**Fixed bugs:**

- allowing the parsing of policy file to deal with commas inside columns [\#518](https://github.com/casbin/casbin/issues/518)

**Merged pull requests:**

- chore: cancel branch restriction [\#524](https://github.com/casbin/casbin/pull/524) ([nodece](https://github.com/nodece))
- fix: Add DeleteRolesForUserInDomain [\#523](https://github.com/casbin/casbin/pull/523) ([dovics](https://github.com/dovics))

## [v2.8.3](https://github.com/casbin/casbin/tree/v2.8.3) (2020-07-15)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.8.2...v2.8.3)

**Merged pull requests:**

- fix: should remove escaped double quotes [\#521](https://github.com/casbin/casbin/pull/521) ([GopherJ](https://github.com/GopherJ))

## [v2.8.2](https://github.com/casbin/casbin/tree/v2.8.2) (2020-07-06)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.8.1...v2.8.2)

**Merged pull requests:**

- fix: wrong locks [\#513](https://github.com/casbin/casbin/pull/513) ([PhilippSeitz](https://github.com/PhilippSeitz))

## [v2.8.1](https://github.com/casbin/casbin/tree/v2.8.1) (2020-07-05)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.8.0...v2.8.1)

**Fixed bugs:**

- \[QUESTION\] what's the difference of `Enforcer` and `SyncedEnforcer` if by default we have locks in every struct with map? [\#504](https://github.com/casbin/casbin/issues/504)

**Merged pull requests:**

- add missing functions to SyncedEnforcer [\#512](https://github.com/casbin/casbin/pull/512) ([PhilippSeitz](https://github.com/PhilippSeitz))

## [v2.8.0](https://github.com/casbin/casbin/tree/v2.8.0) (2020-07-03)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.7.2...v2.8.0)

**Implemented enhancements:**

- performance:  switch to O\(1\) for inserting/removing policy  [\#499](https://github.com/casbin/casbin/issues/499)
- When should i call BuildRoleLinks function [\#455](https://github.com/casbin/casbin/issues/455)
- merge\_effect quick return? [\#439](https://github.com/casbin/casbin/issues/439)

**Merged pull requests:**

- fix: remove unnecessary locks [\#510](https://github.com/casbin/casbin/pull/510) ([GopherJ](https://github.com/GopherJ))

## [v2.7.2](https://github.com/casbin/casbin/tree/v2.7.2) (2020-06-20)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.7.1...v2.7.2)

**Merged pull requests:**

- fix: use map to store policy index [\#500](https://github.com/casbin/casbin/pull/500) ([dovics](https://github.com/dovics))

## [v2.7.1](https://github.com/casbin/casbin/tree/v2.7.1) (2020-06-16)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.7.0...v2.7.1)

**Merged pull requests:**

- Fix: Avoid typecast adapter to BatchAdapter for RemovePolicy [\#495](https://github.com/casbin/casbin/pull/495) ([sanoopsugathan](https://github.com/sanoopsugathan))

## [v2.7.0](https://github.com/casbin/casbin/tree/v2.7.0) (2020-06-15)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.6.12...v2.7.0)

**Merged pull requests:**

- feat: Support pattern function in 3rd args of g [\#475](https://github.com/casbin/casbin/pull/475) ([dovics](https://github.com/dovics))

## [v2.6.12](https://github.com/casbin/casbin/tree/v2.6.12) (2020-06-12)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.6.11...v2.6.12)

**Implemented enhancements:**

- missing role manager bench [\#469](https://github.com/casbin/casbin/issues/469)

**Merged pull requests:**

- fix: Perform adapter persist actions before model changes [\#490](https://github.com/casbin/casbin/pull/490) ([speza](https://github.com/speza))

## [v2.6.11](https://github.com/casbin/casbin/tree/v2.6.11) (2020-06-10)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.6.10...v2.6.11)

**Implemented enhancements:**

- Add ruby to list of supported languages. [\#368](https://github.com/casbin/casbin/issues/368)
- Work in progress: optimizations [\#332](https://github.com/casbin/casbin/issues/332)

**Merged pull requests:**

- fix: \#469 [\#488](https://github.com/casbin/casbin/pull/488) ([RobotHuang](https://github.com/RobotHuang))

## [v2.6.10](https://github.com/casbin/casbin/tree/v2.6.10) (2020-06-07)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.6.9...v2.6.10)

**Implemented enhancements:**

- make g\(r.sub, p.sub, domain\) lazy/cached [\#474](https://github.com/casbin/casbin/issues/474)

**Fixed bugs:**

- an error occurs when run EnforceWithMatcher\(\) [\#484](https://github.com/casbin/casbin/issues/484)
- Panic when I use AutoLoadPolicy, add a policy in DB [\#376](https://github.com/casbin/casbin/issues/376)

**Merged pull requests:**

- fix: Necessary code changes in buildIncrementalRoleLinks. [\#485](https://github.com/casbin/casbin/pull/485) ([divy9881](https://github.com/divy9881))

## [v2.6.9](https://github.com/casbin/casbin/tree/v2.6.9) (2020-06-05)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.6.8...v2.6.9)

## [v2.6.8](https://github.com/casbin/casbin/tree/v2.6.8) (2020-06-04)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.6.7...v2.6.8)

**Merged pull requests:**

- fix: an error occurs when run EnforceWithMatcher\(\) [\#483](https://github.com/casbin/casbin/pull/483) ([techoner](https://github.com/techoner))
- fix: add cache for g function [\#476](https://github.com/casbin/casbin/pull/476) ([nodece](https://github.com/nodece))

## [v2.6.7](https://github.com/casbin/casbin/tree/v2.6.7) (2020-06-04)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.6.6...v2.6.7)

**Merged pull requests:**

- fix: Add Static Check for Enforcer Implementations [\#480](https://github.com/casbin/casbin/pull/480) ([will7200](https://github.com/will7200))

## [v2.6.6](https://github.com/casbin/casbin/tree/v2.6.6) (2020-06-04)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.6.5...v2.6.6)

**Merged pull requests:**

- perf: Use read lock in synced enforcer [\#479](https://github.com/casbin/casbin/pull/479) ([postulha](https://github.com/postulha))

## [v2.6.5](https://github.com/casbin/casbin/tree/v2.6.5) (2020-05-26)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.6.4...v2.6.5)

**Merged pull requests:**

- perf: optimize KeyMatch4\(\) [\#468](https://github.com/casbin/casbin/pull/468) ([techoner](https://github.com/techoner))

## [v2.6.4](https://github.com/casbin/casbin/tree/v2.6.4) (2020-05-25)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.6.3...v2.6.4)

**Implemented enhancements:**

- By default disable logger [\#465](https://github.com/casbin/casbin/issues/465)

**Merged pull requests:**

- fix: support domain for GetRolesForUser and GetUsersForRole [\#467](https://github.com/casbin/casbin/pull/467) ([nodece](https://github.com/nodece))

## [v2.6.3](https://github.com/casbin/casbin/tree/v2.6.3) (2020-05-22)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.6.2...v2.6.3)

**Merged pull requests:**

- fix: Disable logger in benchmark [\#466](https://github.com/casbin/casbin/pull/466) ([dovics](https://github.com/dovics))

## [v2.6.2](https://github.com/casbin/casbin/tree/v2.6.2) (2020-05-19)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.6.1...v2.6.2)

**Merged pull requests:**

- fix: support comment after effect and matcher [\#464](https://github.com/casbin/casbin/pull/464) ([dovics](https://github.com/dovics))

## [v2.6.1](https://github.com/casbin/casbin/tree/v2.6.1) (2020-05-16)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.6.0...v2.6.1)

**Merged pull requests:**

- fix\(synced enforcer\): use casbin logger [\#463](https://github.com/casbin/casbin/pull/463) ([ninedraft](https://github.com/ninedraft))

## [v2.6.0](https://github.com/casbin/casbin/tree/v2.6.0) (2020-05-16)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.5.1...v2.6.0)

**Merged pull requests:**

- feat: add BuildIncrementalRoleLinks [\#459](https://github.com/casbin/casbin/pull/459) ([nodece](https://github.com/nodece))

## [v2.5.1](https://github.com/casbin/casbin/tree/v2.5.1) (2020-05-14)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.5.0...v2.5.1)

**Merged pull requests:**

- fix: adjust policy initialize way in test and bench case [\#461](https://github.com/casbin/casbin/pull/461) ([UnderTreeTech](https://github.com/UnderTreeTech))

## [v2.5.0](https://github.com/casbin/casbin/tree/v2.5.0) (2020-05-14)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.4.1...v2.5.0)

**Implemented enhancements:**

- Explain enforcement by informing matched rules [\#355](https://github.com/casbin/casbin/issues/355)

**Merged pull requests:**

- feat: add AddRolesForUser [\#454](https://github.com/casbin/casbin/pull/454) ([gadelkareem](https://github.com/gadelkareem))

## [v2.4.1](https://github.com/casbin/casbin/tree/v2.4.1) (2020-05-07)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.4.0...v2.4.1)

**Implemented enhancements:**

- Port Casbin for Rust's scaling ABAC rules to Golang [\#440](https://github.com/casbin/casbin/issues/440)
- support pattern function in 3rd args of g [\#337](https://github.com/casbin/casbin/issues/337)

**Fixed bugs:**

- I think we should improve KeyMatch method to avoid endless loop [\#447](https://github.com/casbin/casbin/issues/447)

**Merged pull requests:**

- chore: add semantic.yml [\#451](https://github.com/casbin/casbin/pull/451) ([nodece](https://github.com/nodece))
- fix: improve KeyMatch method to avoid endless loop [\#449](https://github.com/casbin/casbin/pull/449) ([techoner](https://github.com/techoner))
- Explain enforcement in log [\#425](https://github.com/casbin/casbin/pull/425) ([dovics](https://github.com/dovics))

## [v2.4.0](https://github.com/casbin/casbin/tree/v2.4.0) (2020-05-05)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.3.0...v2.4.0)

**Implemented enhancements:**

- Scaling ABAC Rules [\#354](https://github.com/casbin/casbin/issues/354)

**Merged pull requests:**

- Add WatcherEx for change's detail [\#400](https://github.com/casbin/casbin/pull/400) ([dovics](https://github.com/dovics))

## [v2.3.0](https://github.com/casbin/casbin/tree/v2.3.0) (2020-05-05)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.2.3...v2.3.0)

**Implemented enhancements:**

- Suggestion: add automate package releases [\#394](https://github.com/casbin/casbin/issues/394)

**Merged pull requests:**

- Scaling ABAC Rules [\#427](https://github.com/casbin/casbin/pull/427) ([dovics](https://github.com/dovics))

## [v2.2.3](https://github.com/casbin/casbin/tree/v2.2.3) (2020-05-02)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.2.2...v2.2.3)

**Implemented enhancements:**

- problem of running ABAC [\#412](https://github.com/casbin/casbin/issues/412)
- How to add multiple policy ? [\#306](https://github.com/casbin/casbin/issues/306)

**Fixed bugs:**

- GetImplicitUsersForPermission cannot get users in role [\#442](https://github.com/casbin/casbin/issues/442)
- assinging a user to an object role in rbac\_with\_pattern\_policy.csv  [\#435](https://github.com/casbin/casbin/issues/435)
- casbin.SyncedEnforcer does not adhere to casbin.IEnforcer interface [\#405](https://github.com/casbin/casbin/issues/405)

**Closed issues:**

- pre-defined constants|functions [\#430](https://github.com/casbin/casbin/issues/430)
- Correct GoDoc link in README.md [\#420](https://github.com/casbin/casbin/issues/420)

**Merged pull requests:**

- ci: add GitHub actions [\#444](https://github.com/casbin/casbin/pull/444) ([nodece](https://github.com/nodece))
- Fix GetImplicitUsersForPermission [\#443](https://github.com/casbin/casbin/pull/443) ([nodece](https://github.com/nodece))
- Example bug fix. [\#438](https://github.com/casbin/casbin/pull/438) ([divy9881](https://github.com/divy9881))
- casbin-rs is now production-ready [\#426](https://github.com/casbin/casbin/pull/426) ([GopherJ](https://github.com/GopherJ))
- fix \#420 [\#422](https://github.com/casbin/casbin/pull/422) ([dovics](https://github.com/dovics))
- Made changes from normal locking-unlocking to read locking-unlocking for getters. [\#417](https://github.com/casbin/casbin/pull/417) ([divy9881](https://github.com/divy9881))
- Revert "ci: integrated goreleaser" [\#416](https://github.com/casbin/casbin/pull/416) ([nodece](https://github.com/nodece))
- ci: integrated goreleaser [\#414](https://github.com/casbin/casbin/pull/414) ([nodece](https://github.com/nodece))
- Added support for the CONF files having just comma \(no spaces\) separated values. [\#413](https://github.com/casbin/casbin/pull/413) ([divy9881](https://github.com/divy9881))
- Missing member functions added to the interface. [\#409](https://github.com/casbin/casbin/pull/409) ([divy9881](https://github.com/divy9881))
- fix: return panic error when enforce [\#395](https://github.com/casbin/casbin/pull/395) ([jonyhy96](https://github.com/jonyhy96))

## [v2.2.2](https://github.com/casbin/casbin/tree/v2.2.2) (2020-03-25)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.2.1...v2.2.2)

**Implemented enhancements:**

- Add a globMatch\(\) built-in matching function [\#396](https://github.com/casbin/casbin/issues/396)
- Add batch operations: AddPolicies\(\) and RemovePolicies\(\) to Management API [\#386](https://github.com/casbin/casbin/issues/386)
- Separate “Watch.Update” from AutoSave [\#365](https://github.com/casbin/casbin/issues/365)
- Move log.Logger to Enforcer [\#160](https://github.com/casbin/casbin/issues/160)

**Fixed bugs:**

- model.conf has grammatical errors Enforce func return err is nil [\#384](https://github.com/casbin/casbin/issues/384)
- panic: runtime error: index out of range [\#379](https://github.com/casbin/casbin/issues/379)
- Allow empty string policy field [\#316](https://github.com/casbin/casbin/issues/316)

**Closed issues:**

- Matching function does not work in the second argument of g [\#375](https://github.com/casbin/casbin/issues/375)

**Merged pull requests:**

- Use fmt.Errorf\(\) replace errors.New\(fmt.Sprintf\(\)\) [\#403](https://github.com/casbin/casbin/pull/403) ([dovics](https://github.com/dovics))
- Add a globMatch\(\) built-in matching function [\#397](https://github.com/casbin/casbin/pull/397) ([dovics](https://github.com/dovics))
- Return errors in builtin function [\#392](https://github.com/casbin/casbin/pull/392) ([nodece](https://github.com/nodece))
- Added multiple add and remove policies API functions. [\#388](https://github.com/casbin/casbin/pull/388) ([divy9881](https://github.com/divy9881))
- Add synced version of LoadFilteredPolicy. [\#380](https://github.com/casbin/casbin/pull/380) ([VincentK-Titandc](https://github.com/VincentK-Titandc))
- Fix wrong return types for methods in IEnforcer [\#373](https://github.com/casbin/casbin/pull/373) ([dovics](https://github.com/dovics))

## [v2.2.1](https://github.com/casbin/casbin/tree/v2.2.1) (2020-02-24)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.2.0...v2.2.1)

**Implemented enhancements:**

- how to support rbac3? [\#358](https://github.com/casbin/casbin/issues/358)

**Merged pull requests:**

- feat: controls whether to automatically notify Watcher [\#366](https://github.com/casbin/casbin/pull/366) ([nodece](https://github.com/nodece))
- fix\(rbac\_api.go\): DeleteUser should remove Policies + Grouping Policies [\#364](https://github.com/casbin/casbin/pull/364) ([Sefriol](https://github.com/Sefriol))
- Go idomatic stopping goroutine for auto load policy [\#362](https://github.com/casbin/casbin/pull/362) ([Dasio](https://github.com/Dasio))

## [v2.2.0](https://github.com/casbin/casbin/tree/v2.2.0) (2020-02-14)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.1.2...v2.2.0)

**Implemented enhancements:**

- Support ArangoDB persistence adapter [\#339](https://github.com/casbin/casbin/issues/339)
- Could casbin be used for GraphQL?  [\#327](https://github.com/casbin/casbin/issues/327)
- Call Safe functions from panicing ones [\#51](https://github.com/casbin/casbin/issues/51)
- Stack trace in errors [\#50](https://github.com/casbin/casbin/issues/50)

**Fixed bugs:**

- go build error: cannot use functions \(type model.FunctionMap\) as type map\[string\] [\#342](https://github.com/casbin/casbin/issues/342)
- LoadPolicyLine panics [\#333](https://github.com/casbin/casbin/issues/333)

**Merged pull requests:**

- Fix syntax errors on multiline config sentences [\#361](https://github.com/casbin/casbin/pull/361) ([aroldanz](https://github.com/aroldanz))
- Handle panic in enforce [\#351](https://github.com/casbin/casbin/pull/351) ([neelofer-appdirect](https://github.com/neelofer-appdirect))
- Fix link to CONTRIBUTING [\#346](https://github.com/casbin/casbin/pull/346) ([jruizaranguren](https://github.com/jruizaranguren))
- Improve contributing documentation casbin/casbin\#322 [\#343](https://github.com/casbin/casbin/pull/343) ([jruizaranguren](https://github.com/jruizaranguren))
- Update casbin-rs link in README [\#341](https://github.com/casbin/casbin/pull/341) ([kyle-mccarthy](https://github.com/kyle-mccarthy))
- LoadPolicyLine Required Section Check [\#340](https://github.com/casbin/casbin/pull/340) ([mousedownmike](https://github.com/mousedownmike))

## [v2.1.2](https://github.com/casbin/casbin/tree/v2.1.2) (2019-11-23)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.1.1...v2.1.2)

**Closed issues:**

- Problems in role inheritance after calling AddMatchingFunc\(\) [\#329](https://github.com/casbin/casbin/issues/329)

**Merged pull requests:**

- Fix \#329 [\#331](https://github.com/casbin/casbin/pull/331) ([nodece](https://github.com/nodece))

## [v2.1.1](https://github.com/casbin/casbin/tree/v2.1.1) (2019-11-12)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.1.0...v2.1.1)

**Implemented enhancements:**

- Expose `Enforcer` interface [\#318](https://github.com/casbin/casbin/issues/318)
- How do I get data from the user? [\#302](https://github.com/casbin/casbin/issues/302)
- Proposal: migrate from govaluate to expr [\#296](https://github.com/casbin/casbin/issues/296)

**Fixed bugs:**

- Concurrency issues with custom adapter [\#323](https://github.com/casbin/casbin/issues/323)
- Please fix the threading problem of the Enforce method of the SyncedEnforcer [\#309](https://github.com/casbin/casbin/issues/309)
- SyncedEnforcer  DeleteRole\(\) doesn't return error [\#304](https://github.com/casbin/casbin/issues/304)

**Merged pull requests:**

- fix: fix function mapping in concurrent envs and close \#323 [\#325](https://github.com/casbin/casbin/pull/325) ([rolandjitsu](https://github.com/rolandjitsu))
- Added Enforcer Interface to enable testing/mocking on client's end [\#319](https://github.com/casbin/casbin/pull/319) ([7abhishek](https://github.com/7abhishek))
- Improve the performance of NewEnforcer\(\). [\#314](https://github.com/casbin/casbin/pull/314) ([techoner](https://github.com/techoner))
- Add current go version to Travis [\#311](https://github.com/casbin/casbin/pull/311) ([yutita](https://github.com/yutita))
- fix the threading problem of the Enforce method of the SyncedEnforcer [\#310](https://github.com/casbin/casbin/pull/310) ([Orefa](https://github.com/Orefa))
- Properly indent sample code in doc [\#308](https://github.com/casbin/casbin/pull/308) ([shihanng](https://github.com/shihanng))

## [v2.1.0](https://github.com/casbin/casbin/tree/v2.1.0) (2019-10-11)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.0.2...v2.1.0)

**Implemented enhancements:**

- Looking for abac example [\#286](https://github.com/casbin/casbin/issues/286)
- How to match repeated string in keyMatch? [\#281](https://github.com/casbin/casbin/issues/281)
- Implement RBAC API for resource roles [\#226](https://github.com/casbin/casbin/issues/226)

**Fixed bugs:**

- https://casbin.org/docs/en/get-started\#persistence persistence isn't present [\#285](https://github.com/casbin/casbin/issues/285)
- model map is not thread  safe ,and my lock didn't effect [\#191](https://github.com/casbin/casbin/issues/191)

**Merged pull requests:**

- Fix the bug that SyncedEnforcer DeleteRole\(\) doesn't return error [\#305](https://github.com/casbin/casbin/pull/305) ([Nowher2](https://github.com/Nowher2))
- added getter for RoleManager [\#303](https://github.com/casbin/casbin/pull/303) ([asutosh97](https://github.com/asutosh97))
- e.GetAll\<\>\(\) now gets results across all ptypes [\#301](https://github.com/casbin/casbin/pull/301) ([asutosh97](https://github.com/asutosh97))
- replaced explicit for-loop assignment with direct copying. [\#300](https://github.com/casbin/casbin/pull/300) ([asutosh97](https://github.com/asutosh97))
- used model.Function wherever suitable. [\#298](https://github.com/casbin/casbin/pull/298) ([asutosh97](https://github.com/asutosh97))
- Update README.md [\#297](https://github.com/casbin/casbin/pull/297) ([asutosh97](https://github.com/asutosh97))

## [v2.0.2](https://github.com/casbin/casbin/tree/v2.0.2) (2019-09-03)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.0.1...v2.0.2)

**Fixed bugs:**

- Initialize the model from Go code [\#279](https://github.com/casbin/casbin/issues/279)
- panic: interface conversion: \*gormadapter.Adapter is not persist.Adapter: missing method LoadPolicy [\#273](https://github.com/casbin/casbin/issues/273)
- There was a problem when initializing an empty Enforcer. [\#271](https://github.com/casbin/casbin/issues/271)

**Merged pull requests:**

- Add EnforceWithMatcher method [\#283](https://github.com/casbin/casbin/pull/283) ([nodece](https://github.com/nodece))
- add missing methods in management\_api to SyncedEnforcer [\#280](https://github.com/casbin/casbin/pull/280) ([umq](https://github.com/umq))
- Minor change: Guard clauses [\#276](https://github.com/casbin/casbin/pull/276) ([liyiheng](https://github.com/liyiheng))
- Test for a logger and use string.Builder [\#269](https://github.com/casbin/casbin/pull/269) ([ctxnop](https://github.com/ctxnop))

## [v2.0.1](https://github.com/casbin/casbin/tree/v2.0.1) (2019-07-16)

[Full Changelog](https://github.com/casbin/casbin/compare/v2.0.0...v2.0.1)

**Fixed bugs:**

- Casbin v2: something wrong with go.mod? [\#267](https://github.com/casbin/casbin/issues/267)

## [v2.0.0](https://github.com/casbin/casbin/tree/v2.0.0) (2019-07-12)

[Full Changelog](https://github.com/casbin/casbin/compare/v1.9.1...v2.0.0)

**Implemented enhancements:**

- Error handling [\#261](https://github.com/casbin/casbin/issues/261)

**Fixed bugs:**

- After adding a new user, log in with a new account. Sometimes the query will not be queried when the page is refreshed. [\#252](https://github.com/casbin/casbin/issues/252)

## [v1.9.1](https://github.com/casbin/casbin/tree/v1.9.1) (2019-07-04)

[Full Changelog](https://github.com/casbin/casbin/compare/v1.9.0...v1.9.1)

**Fixed bugs:**

- \[question\] lock of SyncedEnforcer [\#257](https://github.com/casbin/casbin/issues/257)
- how to release watcher [\#253](https://github.com/casbin/casbin/issues/253)

**Merged pull requests:**

- Add Close\(\) to SampleWatcher, fix: \#253 [\#258](https://github.com/casbin/casbin/pull/258) ([billcobbler](https://github.com/billcobbler))

## [v1.9.0](https://github.com/casbin/casbin/tree/v1.9.0) (2019-06-30)

[Full Changelog](https://github.com/casbin/casbin/compare/v1.8.3...v1.9.0)

**Implemented enhancements:**

- Add get users with permissions/roles functionality to Management API [\#250](https://github.com/casbin/casbin/issues/250)
- Too much overhead for AddRoleForUserInDomain\(\) when there are 100k rules [\#244](https://github.com/casbin/casbin/issues/244)
- how to implement transcation [\#236](https://github.com/casbin/casbin/issues/236)

**Fixed bugs:**

- When the NewEnforcer is completed, call GetRolesForUserInDomain and report the error invalid memory address or nil pointer dereference [\#247](https://github.com/casbin/casbin/issues/247)
- keyMatch3\("/project/1/member", "/project/1"\) should return false [\#242](https://github.com/casbin/casbin/issues/242)
- e.GetRoles undefined \(type \*casbin.Enforcer has no field or method GetRoles\) [\#239](https://github.com/casbin/casbin/issues/239)

**Closed issues:**

- Init with Model File, Policy File, and Adapter [\#249](https://github.com/casbin/casbin/issues/249)

**Merged pull requests:**

- Performance improvement: avoid copying govaluate parameters unnecessarily [\#248](https://github.com/casbin/casbin/pull/248) ([jszwedko](https://github.com/jszwedko))
- Minor correction for README [\#246](https://github.com/casbin/casbin/pull/246) ([jamieson99](https://github.com/jamieson99))
- Added errors in rbac\_api.go [\#241](https://github.com/casbin/casbin/pull/241) ([L04DB4L4NC3R](https://github.com/L04DB4L4NC3R))
- Activating Open Collective [\#238](https://github.com/casbin/casbin/pull/238) ([monkeywithacupcake](https://github.com/monkeywithacupcake))

## [v1.8.3](https://github.com/casbin/casbin/tree/v1.8.3) (2019-06-15)

[Full Changelog](https://github.com/casbin/casbin/compare/v1.8.2...v1.8.3)

**Implemented enhancements:**

- How to get all related domains for subject [\#215](https://github.com/casbin/casbin/issues/215)
- Effector DSL supports only 4 explicit modes, and tests for them by string exact match [\#211](https://github.com/casbin/casbin/issues/211)

**Fixed bugs:**

- Casbin Editor Broken [\#225](https://github.com/casbin/casbin/issues/225)

**Merged pull requests:**

- make code more elegant and efficient [\#235](https://github.com/casbin/casbin/pull/235) ([Wang-Kai](https://github.com/Wang-Kai))
- Replace `sync.Mutex` with `sync.RWMutex` for CachedEnforcer  [\#221](https://github.com/casbin/casbin/pull/221) ([jszwedko](https://github.com/jszwedko))

## [v1.8.2](https://github.com/casbin/casbin/tree/v1.8.2) (2019-04-25)

[Full Changelog](https://github.com/casbin/casbin/compare/v1.8.1...v1.8.2)

**Merged pull requests:**

- Fix GetImplicitPermissionsForUser [\#220](https://github.com/casbin/casbin/pull/220) ([nodece](https://github.com/nodece))
- Add domain paramter for GetImplicitPermissionsForUser [\#217](https://github.com/casbin/casbin/pull/217) ([nodece](https://github.com/nodece))
- add synced versions for rbac\_api\_with\_domains methods [\#214](https://github.com/casbin/casbin/pull/214) ([stanyx](https://github.com/stanyx))
- reids to redis [\#213](https://github.com/casbin/casbin/pull/213) ([Penglq](https://github.com/Penglq))
- Add more explicit panic log when the defined policy rule is invalid [\#200](https://github.com/casbin/casbin/pull/200) ([pmalhaire](https://github.com/pmalhaire))

## [v1.8.1](https://github.com/casbin/casbin/tree/v1.8.1) (2019-01-29)

[Full Changelog](https://github.com/casbin/casbin/compare/v1.8.0...v1.8.1)

**Implemented enhancements:**

- keyMatch2\("/project/1/member", "/project/1"\) should return false [\#199](https://github.com/casbin/casbin/issues/199)

**Fixed bugs:**

- Breaking change in 1.8.0 where NewEnforcer\(\) panics instead of just returning the enforcer [\#195](https://github.com/casbin/casbin/issues/195)
- \[BUG\] Util EscapeAssertion Function replaces ABAC [\#192](https://github.com/casbin/casbin/issues/192)

**Merged pull requests:**

- fix escapeAssertion bug [\#194](https://github.com/casbin/casbin/pull/194) ([Roman-787](https://github.com/Roman-787))

## [v1.8.0](https://github.com/casbin/casbin/tree/v1.8.0) (2019-01-09)

[Full Changelog](https://github.com/casbin/casbin/compare/v1.7.0...v1.8.0)

**Implemented enhancements:**

- Delphi implementation [\#186](https://github.com/casbin/casbin/issues/186)
- Enable go modules [\#184](https://github.com/casbin/casbin/issues/184)
- Safe functions for policies [\#181](https://github.com/casbin/casbin/issues/181)
- How to use "keyMatch" with "g"? [\#175](https://github.com/casbin/casbin/issues/175)
- panic when add empty policy field [\#171](https://github.com/casbin/casbin/issues/171)
- Would you like to implement new function: GetUsersForRoleInDomain [\#167](https://github.com/casbin/casbin/issues/167)
- LoadPolicy\(\) is called automatically when initializing with filtered adapter [\#96](https://github.com/casbin/casbin/issues/96)
- Changes suggestion on LoadFilteredPolicy [\#93](https://github.com/casbin/casbin/issues/93)
- Support parameterized RBAC [\#10](https://github.com/casbin/casbin/issues/10)
- Cache the decisions to improve the enforcement performance. [\#2](https://github.com/casbin/casbin/issues/2)

**Fixed bugs:**

- Seems it is a bug? [\#183](https://github.com/casbin/casbin/issues/183)
- Enforcer passes silently a non-existent policy file [\#163](https://github.com/casbin/casbin/issues/163)

**Merged pull requests:**

- Add more safe functions and test code. [\#185](https://github.com/casbin/casbin/pull/185) ([techoner](https://github.com/techoner))
- Refactor RBAC pattern [\#182](https://github.com/casbin/casbin/pull/182) ([nodece](https://github.com/nodece))
- Add RESTful Support for g [\#178](https://github.com/casbin/casbin/pull/178) ([nodece](https://github.com/nodece))
- add GetUsersForRoleInDomain and test code [\#170](https://github.com/casbin/casbin/pull/170) ([CHCP](https://github.com/CHCP))
- Added Safe\* methods to the SyncedEnforcer [\#169](https://github.com/casbin/casbin/pull/169) ([e-nikolov](https://github.com/e-nikolov))
- \[enhancement/\#96\] Skip filtered policy init [\#162](https://github.com/casbin/casbin/pull/162) ([faceless-saint](https://github.com/faceless-saint))

## [v1.7.0](https://github.com/casbin/casbin/tree/v1.7.0) (2018-11-07)

[Full Changelog](https://github.com/casbin/casbin/compare/v1.6.0...v1.7.0)

**Implemented enhancements:**

- Structured logging proposal [\#157](https://github.com/casbin/casbin/issues/157)
- Panic in `role\_definition` with g1 [\#155](https://github.com/casbin/casbin/issues/155)
- Can matcher be defined with multiple lines? [\#105](https://github.com/casbin/casbin/issues/105)

**Fixed bugs:**

- ABAC with sub [\#152](https://github.com/casbin/casbin/issues/152)
- Error in TestABACModel [\#150](https://github.com/casbin/casbin/issues/150)

**Closed issues:**

- How to list inherited permissions by father role? [\#137](https://github.com/casbin/casbin/issues/137)
- will support python? [\#125](https://github.com/casbin/casbin/issues/125)

**Merged pull requests:**

- logger interface [\#159](https://github.com/casbin/casbin/pull/159) ([llonchj](https://github.com/llonchj))
- Don't swallow errors [\#151](https://github.com/casbin/casbin/pull/151) ([davisford](https://github.com/davisford))
- Fix test title typo from 'Objeccts' to 'Objects' [\#149](https://github.com/casbin/casbin/pull/149) ([yonasstephen](https://github.com/yonasstephen))
- remove commented-out code [\#133](https://github.com/casbin/casbin/pull/133) ([quasilyte](https://github.com/quasilyte))
- use type switch var binding to reduce the amount of type assertions [\#132](https://github.com/casbin/casbin/pull/132) ([quasilyte](https://github.com/quasilyte))
- remove redundant parenthesis from type conversion exprs [\#131](https://github.com/casbin/casbin/pull/131) ([quasilyte](https://github.com/quasilyte))
- Add test case TestMatcherUsingInOperator & examples/rbac\_model\_matcher & update README.md [\#123](https://github.com/casbin/casbin/pull/123) ([BetaCat0](https://github.com/BetaCat0))

## [v1.6.0](https://github.com/casbin/casbin/tree/v1.6.0) (2018-08-15)

[Full Changelog](https://github.com/casbin/casbin/compare/v1.5.0...v1.6.0)

**Implemented enhancements:**

- 有没有考虑过增加一些缓存 [\#115](https://github.com/casbin/casbin/issues/115)
- RBAC with roles and fixed roles hierarchy across all domains [\#99](https://github.com/casbin/casbin/issues/99)
- The docker image of casbin/casbin doesn't exists [\#76](https://github.com/casbin/casbin/issues/76)
- Interpretation of \[policy\_effect\] and customized role manager [\#71](https://github.com/casbin/casbin/issues/71)

**Closed issues:**

- gorm.DefaultTableNameHandler is not suitable for casbin [\#114](https://github.com/casbin/casbin/issues/114)
- Casbin only takes string parameters\(Note for others\). [\#113](https://github.com/casbin/casbin/issues/113)
- postgres adapter is really slow [\#112](https://github.com/casbin/casbin/issues/112)
- golang csv export error [\#110](https://github.com/casbin/casbin/issues/110)

**Merged pull requests:**

- Update README.md [\#122](https://github.com/casbin/casbin/pull/122) ([BetaCat0](https://github.com/BetaCat0))
- config-enhancement: allow PERM metamodel describe in multi-line [\#120](https://github.com/casbin/casbin/pull/120) ([BetaCat0](https://github.com/BetaCat0))
- fix CachedEnforcer panic [\#118](https://github.com/casbin/casbin/pull/118) ([maplebeats](https://github.com/maplebeats))
- Safe to check variable line after TrimSpace\(\) [\#106](https://github.com/casbin/casbin/pull/106) ([jungju](https://github.com/jungju))
- Task: Resolve lint errors [\#98](https://github.com/casbin/casbin/pull/98) ([kenjones-cisco](https://github.com/kenjones-cisco))

## [v1.5.0](https://github.com/casbin/casbin/tree/v1.5.0) (2018-04-20)

[Full Changelog](https://github.com/casbin/casbin/compare/v1.4.0...v1.5.0)

**Implemented enhancements:**

- remove reflect [\#81](https://github.com/casbin/casbin/issues/81)
- Policies and Model per resource [\#72](https://github.com/casbin/casbin/issues/72)

**Fixed bugs:**

- sync.map error [\#85](https://github.com/casbin/casbin/issues/85)

**Closed issues:**

- Multiple policy definitions [\#77](https://github.com/casbin/casbin/issues/77)

**Merged pull requests:**

- Update typo in comments [\#91](https://github.com/casbin/casbin/pull/91) ([Codier](https://github.com/Codier))
- Remove reflect [\#80](https://github.com/casbin/casbin/pull/80) ([cpg1111](https://github.com/cpg1111))
- \[feature\] Add policy filtering [\#78](https://github.com/casbin/casbin/pull/78) ([faceless-saint](https://github.com/faceless-saint))
- Fix default role manager concurrency [\#74](https://github.com/casbin/casbin/pull/74) ([matevzmihalic](https://github.com/matevzmihalic))

## [v1.4.0](https://github.com/casbin/casbin/tree/v1.4.0) (2018-02-09)

[Full Changelog](https://github.com/casbin/casbin/compare/v1.3.0...v1.4.0)

**Implemented enhancements:**

- \[question\]\[enhancement\]Minio/AWS S3 adapter for casbin [\#69](https://github.com/casbin/casbin/issues/69)
- \[question\] Nats watcher for casbin [\#68](https://github.com/casbin/casbin/issues/68)
- \[question\]data race? [\#67](https://github.com/casbin/casbin/issues/67)
- XACML v3.0 Support and Future Adherence to ABAC Standards [\#64](https://github.com/casbin/casbin/issues/64)
- Model and policy serialization and deserialization [\#61](https://github.com/casbin/casbin/issues/61)
- Performance [\#45](https://github.com/casbin/casbin/issues/45)
- Reloading policies [\#40](https://github.com/casbin/casbin/issues/40)

## [v1.3.0](https://github.com/casbin/casbin/tree/v1.3.0) (2017-12-19)

[Full Changelog](https://github.com/casbin/casbin/compare/v1.2.0...v1.3.0)

**Implemented enhancements:**

- matchers 是什么意思？同时match p p2会怎么样？ [\#53](https://github.com/casbin/casbin/issues/53)

**Fixed bugs:**

- Close files gracefully [\#58](https://github.com/casbin/casbin/issues/58)
- Problem with ABAC? [\#55](https://github.com/casbin/casbin/issues/55)

**Merged pull requests:**

- Tests to demo model/policy getters/setters. [\#60](https://github.com/casbin/casbin/pull/60) ([cdennison](https://github.com/cdennison))
- Close opened files for reading [\#59](https://github.com/casbin/casbin/pull/59) ([bayrinat](https://github.com/bayrinat))
- Improve test coverage from 76% to 99% [\#54](https://github.com/casbin/casbin/pull/54) ([cdennison](https://github.com/cdennison))

## [v1.2.0](https://github.com/casbin/casbin/tree/v1.2.0) (2017-11-02)

[Full Changelog](https://github.com/casbin/casbin/compare/v1.1.0...v1.2.0)

**Implemented enhancements:**

- RBAC sessions [\#43](https://github.com/casbin/casbin/issues/43)
- Hardcoded policy effect of model [\#39](https://github.com/casbin/casbin/issues/39)

**Merged pull requests:**

- Session support for RBAC [\#44](https://github.com/casbin/casbin/pull/44) ([julisch94](https://github.com/julisch94))

## [v1.1.0](https://github.com/casbin/casbin/tree/v1.1.0) (2017-10-24)

[Full Changelog](https://github.com/casbin/casbin/compare/v1.0.0...v1.1.0)

**Implemented enhancements:**

- Thread safety [\#41](https://github.com/casbin/casbin/issues/41)
- RoleManager interface to provide custom implementations [\#36](https://github.com/casbin/casbin/issues/36)

**Fixed bugs:**

- No Go files in redis adapter [\#38](https://github.com/casbin/casbin/issues/38)

**Merged pull requests:**

- \[feature\] Enable multiple policies/roles in API [\#42](https://github.com/casbin/casbin/pull/42) ([faceless-saint](https://github.com/faceless-saint))

## [v1.0.0](https://github.com/casbin/casbin/tree/v1.0.0) (2017-08-30)

[Full Changelog](https://github.com/casbin/casbin/compare/v0.10.0...v1.0.0)

**Implemented enhancements:**

- Graph-based datastore [\#28](https://github.com/casbin/casbin/issues/28)
- Add MongoDB support [\#12](https://github.com/casbin/casbin/issues/12)

**Merged pull requests:**

- Feature: Define RoleManager as interface [\#37](https://github.com/casbin/casbin/pull/37) ([kenjones-cisco](https://github.com/kenjones-cisco))

## [v0.10.0](https://github.com/casbin/casbin/tree/v0.10.0) (2017-07-23)

[Full Changelog](https://github.com/casbin/casbin/compare/v0.9.0...v0.10.0)

**Merged pull requests:**

- Adjust code blocks in Readme [\#31](https://github.com/casbin/casbin/pull/31) ([gmile](https://github.com/gmile))

## [v0.9.0](https://github.com/casbin/casbin/tree/v0.9.0) (2017-07-14)

[Full Changelog](https://github.com/casbin/casbin/compare/v0.8.0...v0.9.0)

## [v0.8.0](https://github.com/casbin/casbin/tree/v0.8.0) (2017-06-28)

[Full Changelog](https://github.com/casbin/casbin/compare/v0.7.0...v0.8.0)

## [v0.7.0](https://github.com/casbin/casbin/tree/v0.7.0) (2017-06-23)

[Full Changelog](https://github.com/casbin/casbin/compare/v0.6.0...v0.7.0)

## [v0.6.0](https://github.com/casbin/casbin/tree/v0.6.0) (2017-06-22)

[Full Changelog](https://github.com/casbin/casbin/compare/v0.5.0...v0.6.0)

**Implemented enhancements:**

- Turn off Log.Print [\#26](https://github.com/casbin/casbin/issues/26)
- How to use casbin.Enforcer as middleware with negroni [\#25](https://github.com/casbin/casbin/issues/25)

**Merged pull requests:**

- Return error from adapters [\#27](https://github.com/casbin/casbin/pull/27) ([ankitm123](https://github.com/ankitm123))

## [v0.5.0](https://github.com/casbin/casbin/tree/v0.5.0) (2017-06-17)

[Full Changelog](https://github.com/casbin/casbin/compare/v0.4.0...v0.5.0)

**Fixed bugs:**

- role inheritance doesn't work for more than 1 level [\#23](https://github.com/casbin/casbin/issues/23)

## [v0.4.0](https://github.com/casbin/casbin/tree/v0.4.0) (2017-06-11)

[Full Changelog](https://github.com/casbin/casbin/compare/v0.3.0...v0.4.0)

**Implemented enhancements:**

- casbin能否支持dotweb？ [\#21](https://github.com/casbin/casbin/issues/21)

## [v0.3.0](https://github.com/casbin/casbin/tree/v0.3.0) (2017-06-03)

[Full Changelog](https://github.com/casbin/casbin/compare/v0.2.0...v0.3.0)

**Implemented enhancements:**

- Provide a way to silence panics [\#19](https://github.com/casbin/casbin/issues/19)

**Closed issues:**

- more documentation on the conf file syntax for casbin [\#16](https://github.com/casbin/casbin/issues/16)

**Merged pull requests:**

- Remove excess line from Model.md [\#18](https://github.com/casbin/casbin/pull/18) ([ibrasho](https://github.com/ibrasho))
- Fix typo and fmt code [\#17](https://github.com/casbin/casbin/pull/17) ([easonlin404](https://github.com/easonlin404))

## [v0.2.0](https://github.com/casbin/casbin/tree/v0.2.0) (2017-05-26)

[Full Changelog](https://github.com/casbin/casbin/compare/v0.1.0...v0.2.0)

## [v0.1.0](https://github.com/casbin/casbin/tree/v0.1.0) (2017-05-22)

[Full Changelog](https://github.com/casbin/casbin/compare/v0.0.6...v0.1.0)

## [v0.0.6](https://github.com/casbin/casbin/tree/v0.0.6) (2017-05-21)

[Full Changelog](https://github.com/casbin/casbin/compare/v0.0.5...v0.0.6)

**Implemented enhancements:**

- authorization middleware for chi framework [\#5](https://github.com/casbin/casbin/issues/5)
- Common DB interface? [\#3](https://github.com/casbin/casbin/issues/3)

**Merged pull requests:**

- Update README.md [\#6](https://github.com/casbin/casbin/pull/6) ([pyprism](https://github.com/pyprism))

## [v0.0.5](https://github.com/casbin/casbin/tree/v0.0.5) (2017-05-05)

[Full Changelog](https://github.com/casbin/casbin/compare/v0.0.4...v0.0.5)

## [v0.0.4](https://github.com/casbin/casbin/tree/v0.0.4) (2017-04-24)

[Full Changelog](https://github.com/casbin/casbin/compare/v0.0.3...v0.0.4)

**Implemented enhancements:**

- Should support CONF to configure the file path, DB [\#1](https://github.com/casbin/casbin/issues/1)

## [v0.0.3](https://github.com/casbin/casbin/tree/v0.0.3) (2017-04-19)

[Full Changelog](https://github.com/casbin/casbin/compare/v0.0.2...v0.0.3)

## [v0.0.2](https://github.com/casbin/casbin/tree/v0.0.2) (2017-04-17)

[Full Changelog](https://github.com/casbin/casbin/compare/v0.0.1...v0.0.2)

## [v0.0.1](https://github.com/casbin/casbin/tree/v0.0.1) (2017-04-13)

[Full Changelog](https://github.com/casbin/casbin/compare/7969b9c2a18f9d51e7bfc96fef6d694f8a72239c...v0.0.1)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
