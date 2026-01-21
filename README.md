Sysinternals Windows Group Policy Templates

Group Policy Administrative Templates (ADM/ADMX) for Microsoft Windows Sysinternals

Purpose:

Provide ADMX/ADM files to centrally configure and manage Sysinternals utilities through Group Policy.

Key Points

Functionality: Supplies Administrative Templates to control Sysinternals tools across Windows environments.

Scope: Templates cover 68 Sysinternals tools (partial list below).

Version: 0.1 — includes a license-agreement approval policy.

Visual: Screenshot or asset included in the repository.

Partial List of Tools (examples)

AccessChk · AccessEnum · AutoRuns · BGInfo · Coreinfo · DebugView · Desktops · Disk2Vhd · Handle · Insight for Active Directory · Process Explorer · Process Monitor · PsExec · PsService · RamMap · RootkitRevealer · SDelete · Sigcheck · TCPView · VMMap · Winobj · ZoomIt

Full list available in the repository.

Usage

Import the ADMX/ADML files into your Group Policy Central Store or local policy editor.

Configure per-machine or per-user settings using Group Policy Management.

Recommendations/Next Steps

Add per-tool configuration examples and default values.

Expand testing across different Windows versions and document supported OS builds.

Implement automated CI to validate ADMX syntax and sample GPO exports.

Contributing

To contribute:

Open a pull request including ADMX/ADML files.

Include a short changelog and any test results for supported Windows builds.
