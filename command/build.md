---
description: Build all targets
agent: build
---

Run the build all command to build everything.

**Build All Command**: `ninja.exe -j36 -C Local/Build/ -f ninja_pc64_vc_dll_release/Tool_Shared_Win64.ninja all`

# Instructions
1. **Build All**: Run the build command
2. **Fix Compile Errors**:
   - Identify the file and line number
   - Show the relevant code snippet
   - Do a fix based on the error message
3. **For linker errors**:
   - Check for missing symbols or duplicate definitions
   - Suggest which library or source file might be missing
4. **If build succeeds**:
   - Confirm completion with a brief summary
   - Report total build time if available
   - Stop, you are done!

# Common Issues to Watch For
- Missing p4 edit on files before modification
- Missing includes

Focus on actionable fixes. If you need to edit files, remember to run p4 edit first.
