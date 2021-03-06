0.8.0 - 2017-04-08

 - Auto drop repository after release - [#37](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/37)
 - Rename "promote" operation to "release" - [#50](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/50)
 - Upgrade project dependencies to 2017 - [#43](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/43)
 - Separate functional tests from unit tests - [#48](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/48)
 - Make functional tests work also on Windows - [#39](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/39)

**Deprecation note**. The ~~promoteRepository~~ and ~~closeAndPromoteRepository~~ tasks are marked as deprecated and will be removed
in the one of the future versions. `releaseRepository` and `closeAndReleaseRepository` can be used as drop-in replacements. 

0.7.0 - 2017-03-27

 - Verify that repository has been really closed - [#21](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/21)
 - Re-enable sharing stagingRepositoryId between close and promote - [#46](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/46)
 - Basic functional tests with different Gradle versions - [#41](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/41)
 - Suggest longer timeout if failed on time related operations even without `--info` enabled - [#34](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/34) 
 - Longer default retry period  - [#12](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/12)

0.6.1 - 2017-03-20

 - Reusing `stagingRepositoryId` from close task bypasses retry mechanism and fails - [#44](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/44) - reusing `stagingRepositoryId` is temporary disabled

0.6.0 - 2017-03-19

 - Consider state trying to find just one repository in given state - [#36](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/36) - contribution by [strelok1](https://github.com/strelok1)
 - Better error message in case of HTTP request failure - [#5](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/5) - contribution by [deanhiller](https://github.com/deanhiller)
 - Add EditorConfig configuration to better deal with spaces vs tabs - [#33](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/33)

0.5.3 - 2015-06-13

 - `packageGroup` should be taken from project.group by default - [#11](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/11)

0.5.2 - 2015-06-09

 - Provide single task to close and promote repository - [#9](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/9)
 - `getStagingProfile` task should display output without `--info` switch - [#8](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/8)

0.5.1 - 2015-03-08

 - Credentials should be automatically fetched from configured deployer - [#7](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/7)
 - Credentials should be automatically fetched from Gradle properties (when available) - [#6](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/6)

0.5.0 - 2015-03-02

 - Wait given time period when repositories are not yet available - [#3](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/3)
 - Use configured stagingProfileId when available - [#2](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/2)
 - nexusUrl by default should use Sonatype OSSRH - [#1](https://github.com/Codearte/gradle-nexus-staging-plugin/issues/1)

0.4.0 - 2015-02-27

 - Initial release
