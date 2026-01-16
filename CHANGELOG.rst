============================================
Ansible MCP Builder Collection Release Notes
============================================

.. contents:: Topics

v1.0.2
======

Bugfixes
--------

- Checks for ansible_python_interpreter to determine Python interpreter for uv tool installs.
- Detects the correct architecture for Go builds.
- Verifies npm packages are installed correctly without skipping failures.

v1.0.1
======

Bugfixes
--------

- Added version variables for all MCP servers.
- Skipped AWS Core MCP verification temporarily. See https://github.com/awslabs/mcp/issues/1947

v1.0.0
======

Release Summary
---------------

First stable release of the mcp_builder collection.
This release includes all the features to install and configure MCP servers when building execution environments.
It is designed for use alongside the ansible.mcp collection, providing a comprehensive solution for MCP server management with Ansible.

See the collection's README for detailed usage instructions and examples.

Note: This collection is marked as Technology Preview until further notice.

v0.0.3
======

Release Summary
---------------

Fix broken README link and adjust image tags to the redhat-cop org.

v0.0.2
======

Release Summary
---------------

Cleans up build files and fixes broken links to prepare for 1.0.0 release.

v0.0.1
======

Release Summary
---------------

Pre-release to test releases to Automation Hub and Ansible Galaxy.
