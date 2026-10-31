# Corevanta Logix Modernizer

Corevanta Logix Modernizer is a focused Windows desktop application for updating Studio 5000 L5X logic without manually chasing references through every routine. It replaces Corevanta AB Legacy Tag Updater as the current release and adds generalized tag and direct I/O remapping for existing Logix projects.

## Designed for a short learning curve

The guided workflow follows familiar Studio 5000 concepts:

1. Export the affected routines or Programs as L5X.
2. Select the reference categories to scan.
3. Analyze and review the mappings and reference locations.
4. Enter changes in the application or Excel.
5. Validate and generate new L5X files for import.

No scripting language, database, or code-generation framework is required. Original L5X files are never overwritten.

## Capabilities

- Direct module-defined I/O remapping
- BOOL and integer-bit mappings
- SINT, INT, DINT, LINT, and unsigned integer mappings
- REAL, TIMER, COUNTER, STRING, and structured/UDT mappings
- Converted PLC-5 I, O, B, T, C, N, and F workflows
- Whole-object TIMER and COUNTER replacement
- Multi-routine and Program-level L5X analysis
- Excel mapping import and export
- Controller-tag conflict and data-type checks
- Existing tag description and TIMER/COUNTER preset preservation
- Saved projects and compatibility with legacy `.abltproject` files

## Download

Download the latest signed Windows installer from the [Releases](https://github.com/CorevantaLLC/corevanta-logix-modernizer/releases/latest) page.

The application includes a 14-day free trial with no credit card required. Analysis, mapping review, project files, and controller-tag safety checks remain available without an active license; Excel mapping import/export and updated L5X generation require a trial or commercial license.

Existing AB Legacy Tag Updater licenses remain valid for Logix Modernizer 2.0.0.

## Product information

- Website: https://corevantaautomation.com/
- Commercial license: https://buy.stripe.com/dRm9AT95jbGibin6Ozfbq05
- Support: customerservice@corevantallc.com

This repository distributes official release packages and release notes. It does not contain the proprietary application source code. The v1.0.0 AB Legacy Tag Updater release remains archived for rollback and reference.

## Trademarks

Studio 5000, Logix Designer, ControlLogix, CompactLogix, Allen-Bradley, and PLC-5 are trademarks of Rockwell Automation, Inc. Corevanta Logix Modernizer is an independent product and is not affiliated with or endorsed by Rockwell Automation.
