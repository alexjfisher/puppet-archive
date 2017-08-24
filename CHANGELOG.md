# Change log

All notable changes to this project will be documented in this file.
Each new release typically also includes the latest modulesync defaults.
These should not impact the functionality of the module.

## [v1.4.0](https://github.com/voxpupuli/puppet-archive/tree/v1.4.0) (2017-08-24)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/v1.3.0...v1.4.0)

**Implemented enhancements:**

- Enable allow\_insecure in archive::download [\#295](https://github.com/voxpupuli/puppet-archive/pull/295) ([alexjfisher](https://github.com/alexjfisher))
- Add custom download options [\#279](https://github.com/voxpupuli/puppet-archive/pull/279) ([nanliu](https://github.com/nanliu))
- Add support for downloading puppet URL’s [\#270](https://github.com/voxpupuli/puppet-archive/pull/270) ([hajee](https://github.com/hajee))

**Fixed bugs:**

- wget proxy implementation incorrect [\#256](https://github.com/voxpupuli/puppet-archive/issues/256)

**Closed issues:**

- allow\_insecure is not working [\#294](https://github.com/voxpupuli/puppet-archive/issues/294)
- Error: no parameter named 'contents' [\#288](https://github.com/voxpupuli/puppet-archive/issues/288)
- Upgradable Archives [\#286](https://github.com/voxpupuli/puppet-archive/issues/286)
- Need option to set curl SSL protocol [\#273](https://github.com/voxpupuli/puppet-archive/issues/273)
- Add guide for migrating from puppet-staging [\#266](https://github.com/voxpupuli/puppet-archive/issues/266)
- Rubocop: fix RSpec/MessageSpies [\#260](https://github.com/voxpupuli/puppet-archive/issues/260)
- Server Error: no parameter named 'provider' [\#249](https://github.com/voxpupuli/puppet-archive/issues/249)
- -z for curl option [\#241](https://github.com/voxpupuli/puppet-archive/issues/241)
- RSpec/MessageExpectation violations [\#208](https://github.com/voxpupuli/puppet-archive/issues/208)

**Merged pull requests:**

- Change how ruby proxy is invoked. [\#280](https://github.com/voxpupuli/puppet-archive/pull/280) ([nanliu](https://github.com/nanliu))
- Pass proxy values using the wget -e option [\#272](https://github.com/voxpupuli/puppet-archive/pull/272) ([nanliu](https://github.com/nanliu))
- GH-260 Fix rubocop RSpec/MessageSpies [\#271](https://github.com/voxpupuli/puppet-archive/pull/271) ([nanliu](https://github.com/nanliu))
- Fixing a typo on credentials file and add the config too [\#269](https://github.com/voxpupuli/puppet-archive/pull/269) ([aerostitch](https://github.com/aerostitch))
- Add puppet-staging migration examples [\#268](https://github.com/voxpupuli/puppet-archive/pull/268) ([alexjfisher](https://github.com/alexjfisher))
- Replace validate\_\* functions with Puppet 4 data type validations [\#264](https://github.com/voxpupuli/puppet-archive/pull/264) ([jkroepke](https://github.com/jkroepke))

## [v1.3.0](https://github.com/voxpupuli/puppet-archive/tree/v1.3.0) (2017-02-10)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/v1.2.0...v1.3.0)

**Closed issues:**

- Does this module rerun after each download/extract ? [\#258](https://github.com/voxpupuli/puppet-archive/issues/258)

**Merged pull requests:**

- release 1.3.0 [\#261](https://github.com/voxpupuli/puppet-archive/pull/261) ([bastelfreak](https://github.com/bastelfreak))

## [v1.2.0](https://github.com/voxpupuli/puppet-archive/tree/v1.2.0) (2016-12-25)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/v1.1.2...v1.2.0)

**Closed issues:**

- Syntax Error with Ruby 1.8.7.374 that doesn't happen with Ruby 2.0.0.598 [\#224](https://github.com/voxpupuli/puppet-archive/issues/224)
- Some Gem dependencies require Ruby \> 2.1 [\#221](https://github.com/voxpupuli/puppet-archive/issues/221)

**Merged pull requests:**

- release 1.2.0 [\#253](https://github.com/voxpupuli/puppet-archive/pull/253) ([bastelfreak](https://github.com/bastelfreak))
- modulesync 0.16.6 [\#252](https://github.com/voxpupuli/puppet-archive/pull/252) ([bastelfreak](https://github.com/bastelfreak))
- Bump min version\_requirement for Puppet + dep [\#251](https://github.com/voxpupuli/puppet-archive/pull/251) ([juniorsysadmin](https://github.com/juniorsysadmin))
- modulesync 0.16.4 [\#250](https://github.com/voxpupuli/puppet-archive/pull/250) ([bastelfreak](https://github.com/bastelfreak))
- modulesync 0.16.3 [\#246](https://github.com/voxpupuli/puppet-archive/pull/246) ([bastelfreak](https://github.com/bastelfreak))
- refactor and document archive ruby provider [\#245](https://github.com/voxpupuli/puppet-archive/pull/245) ([igalic](https://github.com/igalic))
- modulesync 0.15.0 [\#240](https://github.com/voxpupuli/puppet-archive/pull/240) ([bastelfreak](https://github.com/bastelfreak))
- added temp\_dir option to override OS temp dir location [\#239](https://github.com/voxpupuli/puppet-archive/pull/239) ([crayfishx](https://github.com/crayfishx))
- Rubocop fixes [\#238](https://github.com/voxpupuli/puppet-archive/pull/238) ([alexjfisher](https://github.com/alexjfisher))
- Include full Apache License text and add badge [\#237](https://github.com/voxpupuli/puppet-archive/pull/237) ([alexjfisher](https://github.com/alexjfisher))
- \[ci skip\] readd camp2camp badge [\#236](https://github.com/voxpupuli/puppet-archive/pull/236) ([bastelfreak](https://github.com/bastelfreak))
- Add missing badges [\#235](https://github.com/voxpupuli/puppet-archive/pull/235) ([dhoppe](https://github.com/dhoppe))
- Add coveralls badge [\#234](https://github.com/voxpupuli/puppet-archive/pull/234) ([alexjfisher](https://github.com/alexjfisher))
- Update based on voxpupuli/modulesync\_config 0.14.1 [\#233](https://github.com/voxpupuli/puppet-archive/pull/233) ([dhoppe](https://github.com/dhoppe))
- Update based on voxpupuli/modulesync\_config 0.13.3 [\#232](https://github.com/voxpupuli/puppet-archive/pull/232) ([dhoppe](https://github.com/dhoppe))
- modulesync 0.13.0 [\#227](https://github.com/voxpupuli/puppet-archive/pull/227) ([bastelfreak](https://github.com/bastelfreak))
- modulesync 0.12.7 [\#218](https://github.com/voxpupuli/puppet-archive/pull/218) ([alexjfisher](https://github.com/alexjfisher))
- Tidy CHANGELOG.md [\#217](https://github.com/voxpupuli/puppet-archive/pull/217) ([alexjfisher](https://github.com/alexjfisher))

## [v1.1.2](https://github.com/voxpupuli/puppet-archive/tree/v1.1.2) (2016-08-31)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/v1.1.1...v1.1.2)

**Closed issues:**

- `allow\_insecure` not working in Windows [\#213](https://github.com/voxpupuli/puppet-archive/issues/213)
- checksum\_url seemingly ignored [\#210](https://github.com/voxpupuli/puppet-archive/issues/210)
- Getting error while running puppet archive. [\#205](https://github.com/voxpupuli/puppet-archive/issues/205)
- archive::nexus ignore changes [\#204](https://github.com/voxpupuli/puppet-archive/issues/204)
- Add support for timeout [\#196](https://github.com/voxpupuli/puppet-archive/issues/196)

**Merged pull requests:**

- Release 1.1.2 [\#216](https://github.com/voxpupuli/puppet-archive/pull/216) ([alexjfisher](https://github.com/alexjfisher))
- Make fact confinement ruby 1.8 compatible [\#215](https://github.com/voxpupuli/puppet-archive/pull/215) ([alexjfisher](https://github.com/alexjfisher))
- Fix `allow\_insecure` for ruby provider [\#214](https://github.com/voxpupuli/puppet-archive/pull/214) ([alexjfisher](https://github.com/alexjfisher))
- Fix GH-205 raise exception on bad source paramters [\#212](https://github.com/voxpupuli/puppet-archive/pull/212) ([nanliu](https://github.com/nanliu))
- Fix GH-204 resolve camptocamp archive regression [\#211](https://github.com/voxpupuli/puppet-archive/pull/211) ([nanliu](https://github.com/nanliu))
- Modulesync 0.12.4 [\#207](https://github.com/voxpupuli/puppet-archive/pull/207) ([alexjfisher](https://github.com/alexjfisher))
- Expose `allow\_insecure` in nexus defined type [\#206](https://github.com/voxpupuli/puppet-archive/pull/206) ([alexjfisher](https://github.com/alexjfisher))

## [v1.1.1](https://github.com/voxpupuli/puppet-archive/tree/v1.1.1) (2016-08-18)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/v1.1.0...v1.1.1)

**Merged pull requests:**

- release 1.1.1 [\#201](https://github.com/voxpupuli/puppet-archive/pull/201) ([bastelfreak](https://github.com/bastelfreak))

## [v1.1.0](https://github.com/voxpupuli/puppet-archive/tree/v1.1.0) (2016-08-18)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/v1.0.0...v1.1.0)

**Closed issues:**

- archive\_windir fact doesn't work on Ruby 1.8.7 [\#199](https://github.com/voxpupuli/puppet-archive/issues/199)
- allow\_insecure not at root level [\#195](https://github.com/voxpupuli/puppet-archive/issues/195)
- AIX - extraction fails [\#194](https://github.com/voxpupuli/puppet-archive/issues/194)
- extract\_flag doesn't work [\#191](https://github.com/voxpupuli/puppet-archive/issues/191)
- Implement `allow\_insecure` in ruby provider [\#187](https://github.com/voxpupuli/puppet-archive/issues/187)
- Windows https source not working [\#185](https://github.com/voxpupuli/puppet-archive/issues/185)
- Release 1.0.0 [\#172](https://github.com/voxpupuli/puppet-archive/issues/172)

**Merged pull requests:**

- Modulesync 0.12.1 & Release 1.1.0 [\#200](https://github.com/voxpupuli/puppet-archive/pull/200) ([bastelfreak](https://github.com/bastelfreak))
- Fix GH-187 make allow\_insecure parameter universal [\#198](https://github.com/voxpupuli/puppet-archive/pull/198) ([nanliu](https://github.com/nanliu))
- Fix GH-194 AIX extraction [\#197](https://github.com/voxpupuli/puppet-archive/pull/197) ([nanliu](https://github.com/nanliu))
- modulesync 0.11.1 [\#193](https://github.com/voxpupuli/puppet-archive/pull/193) ([bastelfreak](https://github.com/bastelfreak))
- Issue \#191 - fixing README [\#192](https://github.com/voxpupuli/puppet-archive/pull/192) ([tibers](https://github.com/tibers))
- modulesync 0.11.0 [\#190](https://github.com/voxpupuli/puppet-archive/pull/190) ([bastelfreak](https://github.com/bastelfreak))
- Move cacert to pluginsync directory. [\#186](https://github.com/voxpupuli/puppet-archive/pull/186) ([nanliu](https://github.com/nanliu))

## [v1.0.0](https://github.com/voxpupuli/puppet-archive/tree/v1.0.0) (2016-07-14)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/v0.5.1...v1.0.0)

**Implemented enhancements:**

- `allow\_insecure` parameter [\#174](https://github.com/voxpupuli/puppet-archive/issues/174)

**Closed issues:**

- Inconsistent cacerts used [\#175](https://github.com/voxpupuli/puppet-archive/issues/175)
- change in puppet 4.5.0 causing archive type to fail when extract\_path not used [\#166](https://github.com/voxpupuli/puppet-archive/issues/166)
- conflicting with camptocamp/archive [\#165](https://github.com/voxpupuli/puppet-archive/issues/165)
- Shellwords dependency [\#161](https://github.com/voxpupuli/puppet-archive/issues/161)
- Should install dependent packages [\#154](https://github.com/voxpupuli/puppet-archive/issues/154)
-  v0.5.1 - not catching 404 errors [\#153](https://github.com/voxpupuli/puppet-archive/issues/153)
- Method HTTP.follow\_redirect works only with Ruby 1.9+ [\#152](https://github.com/voxpupuli/puppet-archive/issues/152)
- 7zip is unable to locate archive on Windows Server2012 [\#150](https://github.com/voxpupuli/puppet-archive/issues/150)
- Possible issues with Windows download after 0.5.0 release [\#145](https://github.com/voxpupuli/puppet-archive/issues/145)
-  autoload puppet/provider/archive/curl [\#105](https://github.com/voxpupuli/puppet-archive/issues/105)

**Merged pull requests:**

- docs: document camptocamp/archive compatibility [\#184](https://github.com/voxpupuli/puppet-archive/pull/184) ([igalic](https://github.com/igalic))
- "Release 1.0.0" [\#183](https://github.com/voxpupuli/puppet-archive/pull/183) ([nibalizer](https://github.com/nibalizer))
- modulesync 0.9.1 [\#182](https://github.com/voxpupuli/puppet-archive/pull/182) ([bastelfreak](https://github.com/bastelfreak))
- Update metadata.json dependencies and requirements [\#181](https://github.com/voxpupuli/puppet-archive/pull/181) ([alexjfisher](https://github.com/alexjfisher))
- Add `allow\_insecure` parameter [\#180](https://github.com/voxpupuli/puppet-archive/pull/180) ([alexjfisher](https://github.com/alexjfisher))
- GH-175 Fix provider checksum content fetch method. [\#179](https://github.com/voxpupuli/puppet-archive/pull/179) ([nanliu](https://github.com/nanliu))
- Modulesync 0.8.1 [\#178](https://github.com/voxpupuli/puppet-archive/pull/178) ([bastelfreak](https://github.com/bastelfreak))
- GH-172 migrate changes from README to CHANGELOG. [\#177](https://github.com/voxpupuli/puppet-archive/pull/177) ([nanliu](https://github.com/nanliu))
- make our type camptocamp/archive compatible [\#176](https://github.com/voxpupuli/puppet-archive/pull/176) ([igalic](https://github.com/igalic))
- modulesync 0.7.0 [\#173](https://github.com/voxpupuli/puppet-archive/pull/173) ([bastelfreak](https://github.com/bastelfreak))
- Fixup for release\(note that this is /not/ a release PR\) [\#171](https://github.com/voxpupuli/puppet-archive/pull/171) ([nibalizer](https://github.com/nibalizer))
- modulesync 0.7.0 [\#170](https://github.com/voxpupuli/puppet-archive/pull/170) ([bastelfreak](https://github.com/bastelfreak))
- Update from voxpupuli modulesync\_config [\#168](https://github.com/voxpupuli/puppet-archive/pull/168) ([jyaworski](https://github.com/jyaworski))
- avoid creating file autorequire with nil variable [\#167](https://github.com/voxpupuli/puppet-archive/pull/167) ([hdeadman](https://github.com/hdeadman))
- Update documentation [\#164](https://github.com/voxpupuli/puppet-archive/pull/164) ([jhg03a](https://github.com/jhg03a))
- Add the shellwords require to resolve jruby problems [\#162](https://github.com/voxpupuli/puppet-archive/pull/162) ([jyaworski](https://github.com/jyaworski))
- GH-150 handle special characters in filepath. [\#160](https://github.com/voxpupuli/puppet-archive/pull/160) ([nanliu](https://github.com/nanliu))
- GH-153 curl should propagate download failures. [\#159](https://github.com/voxpupuli/puppet-archive/pull/159) ([nanliu](https://github.com/nanliu))
- Skip jruby for provider tests. [\#158](https://github.com/voxpupuli/puppet-archive/pull/158) ([nanliu](https://github.com/nanliu))
- modulesync 0.5.1 [\#157](https://github.com/voxpupuli/puppet-archive/pull/157) ([bastelfreak](https://github.com/bastelfreak))
- Problem with URL generated by function assemble\_nexus\_url when version contains a plus sign \("+"\) [\#155](https://github.com/voxpupuli/puppet-archive/pull/155) ([thiagomarinho](https://github.com/thiagomarinho))

## [v0.5.1](https://github.com/voxpupuli/puppet-archive/tree/v0.5.1) (2016-03-18)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/v0.5.0...v0.5.1)

**Implemented enhancements:**

- 0.5.0 Roadmap [\#62](https://github.com/voxpupuli/puppet-archive/issues/62)
- Add support for S3? [\#48](https://github.com/voxpupuli/puppet-archive/issues/48)

**Closed issues:**

- Why the module implements some logic when installing awscli-bundle.zip [\#146](https://github.com/voxpupuli/puppet-archive/issues/146)
- Windows fails to load type [\#144](https://github.com/voxpupuli/puppet-archive/issues/144)
- Cannot download using wget [\#142](https://github.com/voxpupuli/puppet-archive/issues/142)
- $aws\_cli\_install defaults to true for non Amazon instances [\#140](https://github.com/voxpupuli/puppet-archive/issues/140)
- support stripping of directories [\#114](https://github.com/voxpupuli/puppet-archive/issues/114)

**Merged pull requests:**

- Release 0.5.1 [\#149](https://github.com/voxpupuli/puppet-archive/pull/149) ([nanliu](https://github.com/nanliu))
- GH-146 set aws\_cli\_install default to false [\#148](https://github.com/voxpupuli/puppet-archive/pull/148) ([nanliu](https://github.com/nanliu))
- GH-142 Fix wget cookies option [\#147](https://github.com/voxpupuli/puppet-archive/pull/147) ([nanliu](https://github.com/nanliu))
- Fix Cookie header double quotes on wget [\#143](https://github.com/voxpupuli/puppet-archive/pull/143) ([randradas](https://github.com/randradas))
- GH-114 Document extract customization options [\#139](https://github.com/voxpupuli/puppet-archive/pull/139) ([nanliu](https://github.com/nanliu))
- open file in binary mode when writing downloaded content [\#138](https://github.com/voxpupuli/puppet-archive/pull/138) ([damoxc](https://github.com/damoxc))

## [v0.5.0](https://github.com/voxpupuli/puppet-archive/tree/v0.5.0) (2016-03-10)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/v0.4.8...v0.5.0)

**Implemented enhancements:**

- Out of memory while downloading large files [\#55](https://github.com/voxpupuli/puppet-archive/issues/55)

**Closed issues:**

- Forge missing 0.4.6 [\#129](https://github.com/voxpupuli/puppet-archive/issues/129)
- embed gems and install locally [\#118](https://github.com/voxpupuli/puppet-archive/issues/118)
- Extraction fails when user/group set with extract\_path no permissions [\#108](https://github.com/voxpupuli/puppet-archive/issues/108)

**Merged pull requests:**

- Prepare for 0.5.0 release [\#137](https://github.com/voxpupuli/puppet-archive/pull/137) ([robinbowes](https://github.com/robinbowes))
- Surface the "checksum\_verify" parameter in the archive::nexus define [\#136](https://github.com/voxpupuli/puppet-archive/pull/136) ([robinbowes](https://github.com/robinbowes))
- Pin rake to avoid rubocop/rake 11 incompatibility [\#135](https://github.com/voxpupuli/puppet-archive/pull/135) ([roidelapluie](https://github.com/roidelapluie))
- GH-48 S3 bucket support [\#134](https://github.com/voxpupuli/puppet-archive/pull/134) ([nanliu](https://github.com/nanliu))
- Simplify duplicate code in download/content methods [\#133](https://github.com/voxpupuli/puppet-archive/pull/133) ([nanliu](https://github.com/nanliu))
- GH-55 use net::http to stream files [\#124](https://github.com/voxpupuli/puppet-archive/pull/124) ([nanliu](https://github.com/nanliu))

## [v0.4.8](https://github.com/voxpupuli/puppet-archive/tree/v0.4.8) (2016-03-02)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/v0.4.7...v0.4.8)

**Merged pull requests:**

- Release 0.4.8 [\#132](https://github.com/voxpupuli/puppet-archive/pull/132) ([nanliu](https://github.com/nanliu))
- Modulesync update. [\#131](https://github.com/voxpupuli/puppet-archive/pull/131) ([nanliu](https://github.com/nanliu))

## [v0.4.7](https://github.com/voxpupuli/puppet-archive/tree/v0.4.7) (2016-03-01)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/v0.4.6...v0.4.7)

**Closed issues:**

- Extraction failures are supressed [\#107](https://github.com/voxpupuli/puppet-archive/issues/107)
- Could not find parent provider ruby of curl  [\#87](https://github.com/voxpupuli/puppet-archive/issues/87)

**Merged pull requests:**

- Release 0.4.7 [\#130](https://github.com/voxpupuli/puppet-archive/pull/130) ([nanliu](https://github.com/nanliu))
- GH-107 raise exception when error occurs during extraction. [\#125](https://github.com/voxpupuli/puppet-archive/pull/125) ([nanliu](https://github.com/nanliu))

## [v0.4.6](https://github.com/voxpupuli/puppet-archive/tree/v0.4.6) (2016-02-27)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/v0.4.5...v0.4.6)

**Merged pull requests:**

- "Prep 0.4.6 release" [\#128](https://github.com/voxpupuli/puppet-archive/pull/128) ([nibalizer](https://github.com/nibalizer))

## [v0.4.5](https://github.com/voxpupuli/puppet-archive/tree/v0.4.5) (2016-02-26)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/v0.4.4...v0.4.5)

**Merged pull requests:**

- Prep 0.4.5 [\#127](https://github.com/voxpupuli/puppet-archive/pull/127) ([nanliu](https://github.com/nanliu))
- Revert "\[blacksmith\] Bump version to 0.4.5" [\#126](https://github.com/voxpupuli/puppet-archive/pull/126) ([nanliu](https://github.com/nanliu))

## [v0.4.4](https://github.com/voxpupuli/puppet-archive/tree/v0.4.4) (2016-02-25)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/0.4.4...v0.4.4)

**Closed issues:**

- Why force puppetversion fact everywhere in the archive spec? [\#120](https://github.com/voxpupuli/puppet-archive/issues/120)
- params gem provider logic fails with PE puppet 2015.03 [\#109](https://github.com/voxpupuli/puppet-archive/issues/109)
- Unknown variable aio-agent breaks multi version puppet env [\#106](https://github.com/voxpupuli/puppet-archive/issues/106)
- puppet\_gem provider broken on Fedora [\#103](https://github.com/voxpupuli/puppet-archive/issues/103)
- file urls do not work on windows [\#78](https://github.com/voxpupuli/puppet-archive/issues/78)
- allow source to accept absolute file paths [\#77](https://github.com/voxpupuli/puppet-archive/issues/77)
- Release 0.4.x to puppet-community namespace on forge [\#75](https://github.com/voxpupuli/puppet-archive/issues/75)
- checksum\_url not working for me [\#72](https://github.com/voxpupuli/puppet-archive/issues/72)

**Merged pull requests:**

- Fix several issues related to local files [\#123](https://github.com/voxpupuli/puppet-archive/pull/123) ([nanliu](https://github.com/nanliu))
- Fixing the provider name bug introduced in \#117 [\#121](https://github.com/voxpupuli/puppet-archive/pull/121) ([aerostitch](https://github.com/aerostitch))
- Fixing tests failures on non-defined facts [\#117](https://github.com/voxpupuli/puppet-archive/pull/117) ([aerostitch](https://github.com/aerostitch))
- Cosmetic: adding the score and download badges from Puppet Forge [\#116](https://github.com/voxpupuli/puppet-archive/pull/116) ([aerostitch](https://github.com/aerostitch))
- Fixing the travis badge [\#115](https://github.com/voxpupuli/puppet-archive/pull/115) ([aerostitch](https://github.com/aerostitch))
- Add support for .gz [\#113](https://github.com/voxpupuli/puppet-archive/pull/113) ([dhoppe](https://github.com/dhoppe))
- Support xz format [\#112](https://github.com/voxpupuli/puppet-archive/pull/112) ([hfm](https://github.com/hfm))
- Only use the faraday provider when the faraday\_middleware gem is installed [\#111](https://github.com/voxpupuli/puppet-archive/pull/111) ([epienbroek](https://github.com/epienbroek))
- Support a variety of common formats for remote checksums [\#110](https://github.com/voxpupuli/puppet-archive/pull/110) ([glenjamin](https://github.com/glenjamin))
- Do not assume aio-agent if Puppet version \>= 4 [\#104](https://github.com/voxpupuli/puppet-archive/pull/104) ([antoineco](https://github.com/antoineco))
- Restrict continuous-integration/travis-ci/push to only the master branch [\#102](https://github.com/voxpupuli/puppet-archive/pull/102) ([rnelson0](https://github.com/rnelson0))
- Update badge location [\#101](https://github.com/voxpupuli/puppet-archive/pull/101) ([rnelson0](https://github.com/rnelson0))

## [0.4.4](https://github.com/voxpupuli/puppet-archive/tree/0.4.4) (2015-12-02)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/0.4.3...0.4.4)

**Closed issues:**

- ensure directory exists before moving archive [\#74](https://github.com/voxpupuli/puppet-archive/issues/74)
- should staging be a dependency? [\#73](https://github.com/voxpupuli/puppet-archive/issues/73)

**Merged pull requests:**

- Cleanup unused module and Vagrantfile. [\#99](https://github.com/voxpupuli/puppet-archive/pull/99) ([nanliu](https://github.com/nanliu))
- "Prep 0.4.4" [\#98](https://github.com/voxpupuli/puppet-archive/pull/98) ([nibalizer](https://github.com/nibalizer))
- Fix dependency to staging module on Windows platform. [\#97](https://github.com/voxpupuli/puppet-archive/pull/97) ([nanliu](https://github.com/nanliu))
- Update the ignore files to ensure builds work properly. [\#96](https://github.com/voxpupuli/puppet-archive/pull/96) ([rnelson0](https://github.com/rnelson0))
- Make directory before transferring file [\#95](https://github.com/voxpupuli/puppet-archive/pull/95) ([nanliu](https://github.com/nanliu))
- Add authentication parameters to archive::nexus [\#90](https://github.com/voxpupuli/puppet-archive/pull/90) ([kyblik](https://github.com/kyblik))

## [0.4.3](https://github.com/voxpupuli/puppet-archive/tree/0.4.3) (2015-12-02)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/v0.4.1...0.4.3)

**Merged pull requests:**

- "Prep 0.4.3" [\#94](https://github.com/voxpupuli/puppet-archive/pull/94) ([nibalizer](https://github.com/nibalizer))
- Prep 0.4.1 [\#92](https://github.com/voxpupuli/puppet-archive/pull/92) ([igalic](https://github.com/igalic))

## [v0.4.1](https://github.com/voxpupuli/puppet-archive/tree/v0.4.1) (2015-11-25)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/v0.4.0...v0.4.1)

**Merged pull requests:**

- Prep 0.4.0 [\#91](https://github.com/voxpupuli/puppet-archive/pull/91) ([igalic](https://github.com/igalic))

## [v0.4.0](https://github.com/voxpupuli/puppet-archive/tree/v0.4.0) (2015-11-25)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/0.3.0...v0.4.0)

**Implemented enhancements:**

- Sonatype Nexus support \(archive::nexus\) [\#50](https://github.com/voxpupuli/puppet-archive/issues/50)
- add proxy support, add new params to readme documentation [\#83](https://github.com/voxpupuli/puppet-archive/pull/83) ([terrimonster](https://github.com/terrimonster))

**Fixed bugs:**

- Accept 128 char checksum for sha512. [\#85](https://github.com/voxpupuli/puppet-archive/pull/85) ([nanliu](https://github.com/nanliu))

**Closed issues:**

- Feature request: Proxy support [\#88](https://github.com/voxpupuli/puppet-archive/issues/88)
- Checksum for SHA512 out of limits [\#84](https://github.com/voxpupuli/puppet-archive/issues/84)
- No way to set environment vars or a proxy for http [\#80](https://github.com/voxpupuli/puppet-archive/issues/80)
- Unable to obtain file via archive::nexus with Puppet 4 [\#70](https://github.com/voxpupuli/puppet-archive/issues/70)
- Make faraday package install optional [\#68](https://github.com/voxpupuli/puppet-archive/issues/68)
- archive::params class has an invalid expression under puppet 4 [\#67](https://github.com/voxpupuli/puppet-archive/issues/67)
- Follow redirect using curl [\#65](https://github.com/voxpupuli/puppet-archive/issues/65)
- Publish module to Puppet Forge [\#63](https://github.com/voxpupuli/puppet-archive/issues/63)
- Remove the dependency on Faraday [\#60](https://github.com/voxpupuli/puppet-archive/issues/60)
- Query string breaks file:// behavior [\#56](https://github.com/voxpupuli/puppet-archive/issues/56)

**Merged pull requests:**

- Added support for puppet\_gem required by the AIO agent [\#86](https://github.com/voxpupuli/puppet-archive/pull/86) ([dylanratcliffe](https://github.com/dylanratcliffe))
- Modulesync [\#82](https://github.com/voxpupuli/puppet-archive/pull/82) ([jyaworski](https://github.com/jyaworski))
- added gem\_provider as local var. [\#81](https://github.com/voxpupuli/puppet-archive/pull/81) ([mpepping](https://github.com/mpepping))
- fix for $extract\_flags [\#79](https://github.com/voxpupuli/puppet-archive/pull/79) ([eperdeme](https://github.com/eperdeme))
- Add support for bzip [\#76](https://github.com/voxpupuli/puppet-archive/pull/76) ([craigmunro](https://github.com/craigmunro))
- updating to use puppet\_gem provider when puppet 4.x is installed [\#71](https://github.com/voxpupuli/puppet-archive/pull/71) ([smbambling](https://github.com/smbambling))
- Added redirect to  curl provide. Closes \#65 [\#69](https://github.com/voxpupuli/puppet-archive/pull/69) ([hajee](https://github.com/hajee))
- allow setting of mode for artifacts pulled from nexus [\#66](https://github.com/voxpupuli/puppet-archive/pull/66) ([smbambling](https://github.com/smbambling))
- Added wget provider when using unix.  [\#61](https://github.com/voxpupuli/puppet-archive/pull/61) ([hajee](https://github.com/hajee))
- Fix lint error. [\#59](https://github.com/voxpupuli/puppet-archive/pull/59) ([nanliu](https://github.com/nanliu))
- fix params.pp so that it works with strict\_mode [\#58](https://github.com/voxpupuli/puppet-archive/pull/58) ([robbyt](https://github.com/robbyt))
- Fix issue \#56 [\#57](https://github.com/voxpupuli/puppet-archive/pull/57) ([jairojunior](https://github.com/jairojunior))
- Add archive::nexus support [\#54](https://github.com/voxpupuli/puppet-archive/pull/54) ([jairojunior](https://github.com/jairojunior))
- Add note to experimental features. [\#53](https://github.com/voxpupuli/puppet-archive/pull/53) ([nanliu](https://github.com/nanliu))
- Add support for remote checksum url [\#52](https://github.com/voxpupuli/puppet-archive/pull/52) ([nanliu](https://github.com/nanliu))
- Migrate module to puppet-community. [\#51](https://github.com/voxpupuli/puppet-archive/pull/51) ([nanliu](https://github.com/nanliu))

## [0.3.0](https://github.com/voxpupuli/puppet-archive/tree/0.3.0) (2015-04-23)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/0.2.2...0.3.0)

**Fixed bugs:**

- '7zip' variables incompatible with Puppet 4.0 [\#43](https://github.com/voxpupuli/puppet-archive/issues/43)
- Bug: duplicate resource due to aliasing/namevar having filepath stripped off [\#40](https://github.com/voxpupuli/puppet-archive/issues/40)

**Merged pull requests:**

- Release 0.3.0. [\#49](https://github.com/voxpupuli/puppet-archive/pull/49) ([nanliu](https://github.com/nanliu))
- Fix archive so namevar is unique. [\#47](https://github.com/voxpupuli/puppet-archive/pull/47) ([nanliu](https://github.com/nanliu))
- Updates for Puppet 4 [\#46](https://github.com/voxpupuli/puppet-archive/pull/46) ([nanliu](https://github.com/nanliu))
- Release 0.3.0 [\#45](https://github.com/voxpupuli/puppet-archive/pull/45) ([nanliu](https://github.com/nanliu))

## [0.2.2](https://github.com/voxpupuli/puppet-archive/tree/0.2.2) (2015-03-05)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/0.2.1...0.2.2)

**Closed issues:**

- latest version has syntax error [\#31](https://github.com/voxpupuli/puppet-archive/issues/31)

**Merged pull requests:**

- Release 0.2.2 [\#39](https://github.com/voxpupuli/puppet-archive/pull/39) ([nanliu](https://github.com/nanliu))
- Update readme for file/ftp. [\#38](https://github.com/voxpupuli/puppet-archive/pull/38) ([nanliu](https://github.com/nanliu))
- Add ftp support. [\#37](https://github.com/voxpupuli/puppet-archive/pull/37) ([nanliu](https://github.com/nanliu))
- Add support for file:/// source [\#36](https://github.com/voxpupuli/puppet-archive/pull/36) ([nanliu](https://github.com/nanliu))

## [0.2.1](https://github.com/voxpupuli/puppet-archive/tree/0.2.1) (2015-02-26)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/0.2.0...0.2.1)

**Merged pull requests:**

- Release 0.2.1 [\#35](https://github.com/voxpupuli/puppet-archive/pull/35) ([nanliu](https://github.com/nanliu))
- disable travis.ci sudo. [\#34](https://github.com/voxpupuli/puppet-archive/pull/34) ([nanliu](https://github.com/nanliu))
- Fix puppet lint warning. [\#33](https://github.com/voxpupuli/puppet-archive/pull/33) ([nanliu](https://github.com/nanliu))
- Fix Ruby 1.8.7 syntax bug [\#32](https://github.com/voxpupuli/puppet-archive/pull/32) ([nanliu](https://github.com/nanliu))

## [0.2.0](https://github.com/voxpupuli/puppet-archive/tree/0.2.0) (2015-02-23)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/0.1.8...0.2.0)

**Implemented enhancements:**

- Do not overwrite destination while downloading [\#23](https://github.com/voxpupuli/puppet-archive/issues/23)

**Merged pull requests:**

- Update documentation. [\#30](https://github.com/voxpupuli/puppet-archive/pull/30) ([nanliu](https://github.com/nanliu))
- Release 0.2.0 [\#29](https://github.com/voxpupuli/puppet-archive/pull/29) ([nanliu](https://github.com/nanliu))
- Fix tempfile garbage collection race problem. [\#28](https://github.com/voxpupuli/puppet-archive/pull/28) ([nanliu](https://github.com/nanliu))
- Support configuring extract command user/group. [\#27](https://github.com/voxpupuli/puppet-archive/pull/27) ([nanliu](https://github.com/nanliu))
- Download files to temporary directory first. [\#26](https://github.com/voxpupuli/puppet-archive/pull/26) ([nanliu](https://github.com/nanliu))
- Support msi packages as the source for 7zip. [\#25](https://github.com/voxpupuli/puppet-archive/pull/25) ([nanliu](https://github.com/nanliu))
- Add yardoc module for document generation. [\#24](https://github.com/voxpupuli/puppet-archive/pull/24) ([nanliu](https://github.com/nanliu))
- Fix custom flag not behaving correctly. [\#20](https://github.com/voxpupuli/puppet-archive/pull/20) ([nanliu](https://github.com/nanliu))

## [0.1.8](https://github.com/voxpupuli/puppet-archive/tree/0.1.8) (2014-12-09)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/0.1.7...0.1.8)

**Fixed bugs:**

- Invalid package provider 'pe\_gem' [\#13](https://github.com/voxpupuli/puppet-archive/issues/13)

**Closed issues:**

- document why to use this vs alternatives [\#15](https://github.com/voxpupuli/puppet-archive/issues/15)

**Merged pull requests:**

- Release 0.1.8 [\#18](https://github.com/voxpupuli/puppet-archive/pull/18) ([nanliu](https://github.com/nanliu))
- Fix module puppet-lint and metadata.json warnings [\#17](https://github.com/voxpupuli/puppet-archive/pull/17) ([nanliu](https://github.com/nanliu))
- Update README regarding improvements over puppet-staging. [\#16](https://github.com/voxpupuli/puppet-archive/pull/16) ([nanliu](https://github.com/nanliu))

## [0.1.7](https://github.com/voxpupuli/puppet-archive/tree/0.1.7) (2014-11-13)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/0.1.6...0.1.7)

**Fixed bugs:**

- Module fails when puppetlabs-stdlib is also in the modulepath [\#10](https://github.com/voxpupuli/puppet-archive/issues/10)
- Support sha256 which requires 64-char keys [\#8](https://github.com/voxpupuli/puppet-archive/pull/8) ([eshamow](https://github.com/eshamow))

**Merged pull requests:**

- Update release to 0.1.7 [\#14](https://github.com/voxpupuli/puppet-archive/pull/14) ([nanliu](https://github.com/nanliu))
- Add working spec tests. [\#12](https://github.com/voxpupuli/puppet-archive/pull/12) ([nanliu](https://github.com/nanliu))
- Fix PE detection. [\#11](https://github.com/voxpupuli/puppet-archive/pull/11) ([nanliu](https://github.com/nanliu))

## [0.1.6](https://github.com/voxpupuli/puppet-archive/tree/0.1.6) (2014-11-05)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/0.1.5...0.1.6)

**Implemented enhancements:**

- Add windows SSL certificate verification work around. [\#6](https://github.com/voxpupuli/puppet-archive/pull/6) ([nanliu](https://github.com/nanliu))

**Merged pull requests:**

- added some very basic puppet unit tests [\#5](https://github.com/voxpupuli/puppet-archive/pull/5) ([logicminds](https://github.com/logicminds))

## [0.1.5](https://github.com/voxpupuli/puppet-archive/tree/0.1.5) (2014-11-05)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/0.1.4...0.1.5)

**Implemented enhancements:**

- Add cookie support for file download. [\#4](https://github.com/voxpupuli/puppet-archive/pull/4) ([nanliu](https://github.com/nanliu))

## [0.1.4](https://github.com/voxpupuli/puppet-archive/tree/0.1.4) (2014-10-27)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/0.1.3...0.1.4)

**Fixed bugs:**

- Make sure archive re-extract if the file checksum changes. [\#3](https://github.com/voxpupuli/puppet-archive/pull/3) ([nanliu](https://github.com/nanliu))

## [0.1.3](https://github.com/voxpupuli/puppet-archive/tree/0.1.3) (2014-10-10)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/0.1.2...0.1.3)

## [0.1.2](https://github.com/voxpupuli/puppet-archive/tree/0.1.2) (2014-10-02)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/0.1.1...0.1.2)

## [0.1.1](https://github.com/voxpupuli/puppet-archive/tree/0.1.1) (2014-10-01)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/0.1.0...0.1.1)

**Implemented enhancements:**

- Add windows extract support. [\#2](https://github.com/voxpupuli/puppet-archive/pull/2) ([nanliu](https://github.com/nanliu))

## [0.1.0](https://github.com/voxpupuli/puppet-archive/tree/0.1.0) (2014-09-26)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/0.0.2...0.1.0)

**Merged pull requests:**

- Add support files for 0.1.0 release. [\#1](https://github.com/voxpupuli/puppet-archive/pull/1) ([nanliu](https://github.com/nanliu))

## [0.0.2](https://github.com/voxpupuli/puppet-archive/tree/0.0.2) (2014-09-17)
[Full Changelog](https://github.com/voxpupuli/puppet-archive/compare/0.0.1...0.0.2)

## [0.0.1](https://github.com/voxpupuli/puppet-archive/tree/0.0.1) (2014-09-11)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*