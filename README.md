APACHE-2.4 CIS
Configure RHEL and Debian based Apache 2.4 servers to be [CIS] (https://www.cisecurity.org/cis-benchmarks/) compliant.

This role will make changes to the system that could break things. This is not an auditing tool but rather a remediation tool to be used after an audit has been conducted.

Based on CIS Apache HTTP Server 2.4 Benchmark .

Requirements
You should carefully read through the tasks to make sure these changes will not break your systems before running this playbook. If you want to do a dry run without changing anything, set the below sections (apache_cis_section1-12) to false.
