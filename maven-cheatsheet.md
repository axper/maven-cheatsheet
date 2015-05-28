## Specify projects
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td><code>--projects <arg></code></td><td><code>-pl</code></td><td>Comma-delimited list of specified reactor projects to build instead of all projects. A project can be specified by [groupId]:artifactId or by its relative path.</td></tr>
<tr><td><code>--resume-from <arg></code></td><td><code>-rf</code></td><td>Resume reactor from specified project</td></tr>
<tr><td><code>--activate-profiles <arg></code></td><td><code>-P</code></td><td>Comma-delimited list of profiles to activate</td></tr>
<tr><td><code>--non-recursive</code></td><td><code>-N</code></td><td>Do not recurse into sub-projects</td></tr>
<tr><td><code>--also-make</code></td><td><code>-am</code></td><td>If project list is specified, also build projects required by the list</td></tr>
<tr><td><code>--also-make-dependents</code></td><td><code>-amd</code></td><td>If project list is specified, also build projects that depend on projects on the list</td></tr>
</table>

## Main
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td><code>--threads <arg></code></td><td><code>-T</code></td><td>Thread count, for instance 2.0C where C is core multiplied</td></tr>
<tr><td><code>--define <arg></code></td><td><code>-D</code></td><td>Define a system property</td></tr>
<tr><td><code>--batch-mode</code></td><td><code>-B</code></td><td>Run in non-interactive (batch) mode</td></tr>
<tr><td><code>--builder <arg></code></td><td><code>-b</code></td><td>The id of the build strategy to use.</td></tr>
</table>

### Output
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td><code>--quiet</code></td><td><code>-q</code></td><td>Quiet output - only show errors</td></tr>
<tr><td><code>--errors</code></td><td><code>-e</code></td><td>Produce execution error messages</td></tr>
<tr><td><code>--debug</code></td><td><code>-X</code></td><td>Produce execution debug output</td></tr>
</table>

## Repo
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td><code>--update-snapshots</code></td><td><code>-U</code></td><td>Forces a check for missing releases and updated snapshots on remote repositories</td></tr>
<tr><td><code>--offline</code></td><td><code>-o</code></td><td>Work offline</td></tr>
<tr><td><code>--no-snapshot-updates</code></td><td><code>-nsu</code></td><td>Suppress SNAPSHOT updates</td></tr>
<tr><td><code>--legacy-local-repository</code></td><td><code>-llr</code></td><td>Use Maven 2 Legacy Local Repository behaviour, ie no use of \_remote.repositories. Can also be activated by using -Dmaven.legacyLocalRepo=true</td></tr>
</table>

## Passwords
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td><code>--encrypt-master-password <arg></code></td><td><code>-emp</code></td><td>Encrypt master security password</td></tr>
<tr><td><code>--encrypt-password <arg></code></td><td><code>-ep</code></td><td>Encrypt server password</td></tr>
</table>

## Fail
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td><code>--fail-at-end</code></td><td><code>-fae</code></td><td>Only fail the build afterwards; allow all non-impacted builds to continue</td></tr>
<tr><td><code>--fail-fast</code></td><td><code>-ff</code></td><td>Stop at first failure in reactorized builds</td></tr>
<tr><td><code>--fail-never</code></td><td><code>-fn</code></td><td>NEVER fail the build, regardless of project result</td></tr>
</table>

### Checksum
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td><code>--lax-checksums</code></td><td><code>-c</code></td><td>Warn if checksums don't match</td></tr>
<tr><td><code>--strict-checksums</code></td><td><code>-C</code></td><td>Fail the build if checksums don't match</td></tr>
</table>

## File locations
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td><code>--file <arg></code></td><td><code>-f</code></td><td>Force the use of an alternate POM file (or directory with pom.xml).</td></tr>
<tr><td><code>--settings <arg></code></td><td><code>-s</code></td><td>Alternate path for the user settings file</td></tr>
<tr><td><code>--toolchains <arg></code></td><td><code>-t</code></td><td>Alternate path for the user toolchains file</td></tr>
<tr><td><code>--log-file <arg></code></td><td><code>-l</code></td><td>Log file to where all build output will go.</td></tr>
<tr><td><code>--global-settings <arg></code></td><td><code>-gs</code></td><td>Alternate path for the global settings file</td></tr>
<tr><td><code>--global-toolchains <arg></code></td><td><code>-gt</code></td><td>Alternate path for the global toolchains file</td></tr>
</table>

## Version/Misc
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td><code>--version</code></td><td><code>-v</code></td><td>Display version information</td></tr>
<tr><td><code>--show-version</code></td><td><code>-V</code></td><td>Display version information WITHOUT stopping build</td></tr>
<tr><td><code>--help</code></td><td><code>-h</code></td><td>Display help information</td></tr>
</table>

## Deprecated options
<table>
<col style="width:30%">
<col style="width:5%">
<tr><td><code>--check-plugin-updates</code></td><td><code>-cpu</code></td><td>Ineffective, only kept for backward compatibility</td></tr>
<tr><td><code>--update-plugins</code></td><td><code>-up</code></td><td>Ineffective, only kept for backward compatibility</td></tr>
<tr><td><code>--no-plugin-registry</code></td><td><code>-npr</code></td><td>Ineffective, only kept for backward compatibility</td></tr>
<tr><td><code>--no-plugin-updates</code></td><td><code>-npu</code></td><td>Ineffective, only kept for backward compatibility</td></tr>
</table>
