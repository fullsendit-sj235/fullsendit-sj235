<div align="center">
  <img src="../assets/brachify-header.svg" width="100%" alt="brachify: capstone project, in progress" />
</div>

<br />

> [!NOTE]
> **This project is still in progress, and its repository is private.** It's a university capstone built with a team and a clinical client, so the code isn't public yet. You can see the software it builds on below.

### What it is

[brachify](https://github.com/brachify/brachify) is a desktop app that turns a DICOM treatment plan into a 3D-printable cylinder for interstitial gynaecological brachytherapy. It reads the plan's needle channels and structures, builds the applicator around them, and exports a printable mesh and a reference sheet. It was originally developed by Michael Kudla, Ph.D., at BC Cancer.

### What I'm building

For my COSC 499 capstone, my team and I are extending brachify with new features requested by the clinical team, including:

- **Anatomy in the 3D view:** showing organs at risk and the tumour target from the plan's structure set alongside the applicator
- **Needle editing:** adjusting needle channels directly in the app
- **Templates:** reusable applicator templates

**Stack:** Python · PySide6 (Qt) · pythonOCC (OpenCascade) · pydicom

<br />

<p align="center">
  <a href="https://github.com/brachify/brachify"><img src="https://img.shields.io/badge/View_the_original_brachify_software-0E1630?style=for-the-badge&logo=github&logoColor=white" alt="View the original brachify software on GitHub" /></a>
  &nbsp;
  <a href="https://github.com/fullsendit-sj235"><img src="https://img.shields.io/badge/Back_to_profile-1A1235?style=for-the-badge&logoColor=white" alt="Back to profile" /></a>
</p>
