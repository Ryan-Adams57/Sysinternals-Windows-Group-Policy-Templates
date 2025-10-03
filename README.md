Sysinternals‑Windows‑Group‑Policy‑Templates — README (short & organized)

Project: Group Policy Administrative Templates (ADM/ADMX) for Microsoft Windows Sysinternals

Purpose: Provide ADMX/ADM files to centrally configure and manage Sysinternals utilities via Group Policy.

Key points

What it does: Supplies Administrative Templates to control Sysinternals tools across Windows environments.

Scope: Templates for 68 Sysinternals tools (partial list below).

Version: 0.1 — includes a license-agreement approval policy.

Visual: Screenshot/asset included in repo.

Partial list of tools (examples)

AccessChk · AccessEnum · AutoRuns · BGInfo · Coreinfo · DebugView · Desktops · Disk2Vhd · Handle · Insight for Active Directory · Process Explorer · Process Monitor · PsExec · PsService · RamMap · RootkitRevealer · SDelete · Sigcheck · TCPView · VMMap · Winobj · ZoomIt

(full list available in repository)

Usage

Import the ADMX/ADML files into your Group Policy Central Store or local policy editor.

Configure per-machine or per-user settings via Group Policy Management.

Recommendations / Next steps

Add per-tool configuration examples and default values.

Expand tests across Windows versions and document supported OS builds.

Provide automated CI to validate ADMX syntax and sample GPO exports.

Contributing

Open a PR with: ADMX/ADML files, a short changelog, and any test results for supported Windows builds.

![ADMX Microsoft Windows Sysinternals](https://github.com/user-attachments/assets/cb894d9b-8c0c-4874-b068-2ada0e3d13a9)
