## Specify projects
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td>`--projects <arg>`</td><td>`-pl`</td><td>Comma-delimited list of specified reactor projects to build instead of all projects. A project can be specified by [groupId]:artifactId or by its relative path.</td></tr>
<tr><td>`--resume-from <arg>`</td><td>`-rf`</td><td>Resume reactor from specified project</td></tr>
<tr><td>`--activate-profiles <arg>`</td><td>`-P`</td><td>Comma-delimited list of profiles to activate</td></tr>
<tr><td>`--non-recursive`</td><td>`-N`</td><td>Do not recurse into sub-projects</td></tr>
<tr><td>`--also-make`</td><td>`-am`</td><td>If project list is specified, also build projects required by the list</td></tr>
<tr><td>`--also-make-dependents`</td><td>`-amd`</td><td>If project list is specified, also build projects that depend on projects on the list</td></tr>
</table>

## Main
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td>`--threads <arg>`</td><td>`-T`</td><td>Thread count, for instance 2.0C where C is core multiplied</td></tr>
<tr><td>`--define <arg>`</td><td>`-D`</td><td>Define a system property</td></tr>
<tr><td>`--batch-mode`</td><td>`-B`</td><td>Run in non-interactive (batch) mode</td></tr>
<tr><td>`--builder <arg>`</td><td>`-b`</td><td>The id of the build strategy to use.</td></tr>
</table>

### Output
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td>`--quiet`</td><td>`-q`</td><td>Quiet output - only show errors</td></tr>
<tr><td>`--errors`</td><td>`-e`</td><td>Produce execution error messages</td></tr>
<tr><td>`--debug`</td><td>`-X`</td><td>Produce execution debug output</td></tr>
</table>

## Repo
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td>`--update-snapshots`</td><td>`-U`</td><td>Forces a check for missing releases and updated snapshots on remote repositories</td></tr>
<tr><td>`--offline`</td><td>`-o`</td><td>Work offline</td></tr>
<tr><td>`--no-snapshot-updates`</td><td>`-nsu`</td><td>Suppress SNAPSHOT updates</td></tr>
<tr><td>`--legacy-local-repository`</td><td>`-llr`</td><td>Use Maven 2 Legacy Local Repository behaviour, ie no use of \_remote.repositories. Can also be activated by using -Dmaven.legacyLocalRepo=true</td></tr>
</table>

## Passwords
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td>`--encrypt-master-password <arg>`</td><td>`-emp`</td><td>Encrypt master security password</td></tr>
<tr><td>`--encrypt-password <arg>`</td><td>`-ep`</td><td>Encrypt server password</td></tr>
</table>

## Fail
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td>`--fail-at-end`</td><td>`-fae`</td><td>Only fail the build afterwards; allow all non-impacted builds to continue</td></tr>
<tr><td>`--fail-fast`</td><td>`-ff`</td><td>Stop at first failure in reactorized builds</td></tr>
<tr><td>`--fail-never`</td><td>`-fn`</td><td>NEVER fail the build, regardless of project result</td></tr>
</table>

### Checksum
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td>`--lax-checksums`</td><td>`-c`</td><td>Warn if checksums don't match</td></tr>
<tr><td>`--strict-checksums`</td><td>`-C`</td><td>Fail the build if checksums don't match</td></tr>
</table>

## File locations
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td>`--file <arg>`</td><td>`-f`</td><td>Force the use of an alternate POM file (or directory with pom.xml).</td></tr>
<tr><td>`--settings <arg>`</td><td>`-s`</td><td>Alternate path for the user settings file</td></tr>
<tr><td>`--toolchains <arg>`</td><td>`-t`</td><td>Alternate path for the user toolchains file</td></tr>
<tr><td>`--log-file <arg>`</td><td>`-l`</td><td>Log file to where all build output will go.</td></tr>
<tr><td>`--global-settings <arg>`</td><td>`-gs`</td><td>Alternate path for the global settings file</td></tr>
<tr><td>`--global-toolchains <arg>`</td><td>`-gt`</td><td>Alternate path for the global toolchains file</td></tr>
</table>

## Version/Misc
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td>`--version`</td><td>`-v`</td><td>Display version information</td></tr>
<tr><td>`--show-version`</td><td>`-V`</td><td>Display version information WITHOUT stopping build</td></tr>
<tr><td>`--help`</td><td>`-h`</td><td>Display help information</td></tr>
</table>

## Deprecated options
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td>`--check-plugin-updates`</td><td>`-cpu`</td><td>Ineffective, only kept for backward compatibility</td></tr>
<tr><td>`--update-plugins`</td><td>`-up`</td><td>Ineffective, only kept for backward compatibility</td></tr>
<tr><td>`--no-plugin-registry`</td><td>`-npr`</td><td>Ineffective, only kept for backward compatibility</td></tr>
<tr><td>`--no-plugin-updates`</td><td>`-npu`</td><td>Ineffective, only kept for backward compatibility</td></tr>
</table>
