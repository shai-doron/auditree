# Python Packages Report 2022-02-23

This report displays differences in the compliance automation execution Python
package environment since the previous execution.

<details>
<summary>More details...</summary>

Any **package version changes**
are largely informational.  They _can_ be used to debug why things worked
previously but aren't working today.  The compliance automation framework execution
environment depends on other of Python libraries.  These libraries can have new
releases and it's not outside the realm of possibility that a new release of a
dependency could cause a problem.  This report provides information that helps to
guard against that.  This report also checks whether the versions of the
[auditree-central](https://github.ibm.com/auditree/auditree-central),
[auditree-arboretum](https://github.com/ComplianceAsCode/auditree-arboretum),
the [auditree-framework](https://github.com/ComplianceAsCode/auditree-framework)
and the [auditree-harvest](https://github.com/ComplianceAsCode/auditree-harvest)
packages are the most recent versions available, as is the expected behavior.
</details>

<details>
<summary>Remediation...</summary>

Package version change warnings are informational but can be used in part
to debug why things worked previously but currently don't.  However, if the
`auditree-central`, `auditree-arboretum`, `auditree-framework`, or the
`auditree-harvest` packages are flagged as a **latest version violation** then
that needs to be explained.  It is expected that the most recent versions of
each of those packages are used during fetcher, check and report execution.
</details>



## Latest Version Violation
Checks that ensure that the `auditree-central`, `auditree-arboretum`,
`auditree-framework` and `auditree-harvest` packages are up to date have
uncovered issues.  These warnings should be investigated because the expectation
is that these packages should be current and up to date.

* auditree-central latest version 0.116.3, version used 0.116.2