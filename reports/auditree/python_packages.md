# Python Packages Report 2022-02-20

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

## New Packages
These findings are largely informational.  They can be used to debug issues with
the execution environment.

* Deprecated version 1.2.13
* PTable version 0.9.2
* PyGithub version 1.55
* PyNaCl version 1.5.0
* SoftLayer version 5.9.9
* TatSu version 5.6.1
* auditree-central version 0.116.2
* cachetools version 5.0.0
* click version 8.0.3
* cloudant-common version 0.15.0
* future version 0.18.2
* google-auth version 2.6.0
* ibm-cos-sdk version 2.11.0
* ibm-cos-sdk-core version 2.11.0
* ibm-cos-sdk-s3transfer version 2.11.0
* ibmcloud-tools version 2.52.2
* jmespath version 0.10.0
* kubernetes version 17.17.0
* oauthlib version 3.2.0
* prompt-toolkit version 3.0.28
* pyaml version 20.4.0
* pyasn1 version 0.4.8
* pyasn1-modules version 0.2.8
* requests-oauthlib version 1.3.1
* rsa version 4.8
* sdcclient version 0.16.3
* sphinx-rtd-theme version 0.5.2
* utilitarian version 0.57.1
* wcwidth version 0.2.5
* wrapt version 1.13.3

## Package Version Changes
These findings are largely informational.  They can be used to debug issues with
the execution environment.

* PyYAML previous version 6.0, current version 5.3.1
* charset-normalizer previous version 2.0.11, current version 2.0.12
* docutils previous version 0.17.1, current version 0.15.2
* filelock previous version 3.4.2, current version 3.5.0
* identify previous version 2.4.8, current version 2.4.10
* importlib-metadata previous version 4.10.1, current version 4.11.1
* platformdirs previous version 2.4.1, current version 2.5.0
* pytest previous version 7.0.0, current version 7.0.1
* setuptools previous version 60.8.1, current version 60.9.2