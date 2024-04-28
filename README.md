# Intro
Demonstrates an issue trying to reference SelectAllTextBehavior from .NET8 app

# To See the Issue
1. Open SelectAllTextBehaviorTest/SelectAllTextBehaviorTest.sln
1. Uncomment the Entry.Behavior in Project2/MyControl
1. Build the solution for a native runtime, I've been using iOS.
1. The build will fail saying `Error: XLS0414: The type 'toolkit:SelectAllTextBehavior' was not found. Verify that you are not missing an assembly reference and that all referenced assemblies have been built. `
