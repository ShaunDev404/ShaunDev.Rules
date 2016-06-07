# ShaunDev.Rules

ShaunDev.Rules supplies a basic set of Code Analysis rulessets and StyleCop (v 4.7.49) settings.

The purpose of this package is to make developing easy on developers.

Create an extra solution configuration called 'Quick' (besides the existing Debug and Release).
For this Quick configuration, disable Code Analysis, XML documentation, etc.
Using this Quick configuration development is easy, and building is quick.
Switch to Debug configuration sets all CodeAnalysis rules to Warnings.
Switch to Release configuration sets all CodeAnalysis rules Errors.
So before releaseing your code build in Release mode.
