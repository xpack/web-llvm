---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/jitlink/aarch32/fixupinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FixupInfo` Struct Template Reference

<p>Collection of named constants per fixup kind. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;EdgeKind_aarch32 Kind&gt;
struct llvm::jitlink::aarch32::FixupInfo&lt;Kind&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch32-h">llvm/ExecutionEngine/JITLink/aarch32.h</a>"
</div>

## Description {#details}

<p>Collection of named constants per fixup kind.</p>


<p>Mandatory entries: Opcode - Values of the op-code bits in the instruction, with unaffected bits nulled OpcodeMask - Mask with all bits set that encode the op-code</p>


<p>Other common entries: ImmMask - Mask with all bits set that encode the immediate value RegMask - Mask with all bits set that encode the register</p>


<p>Specializations can add further custom fields without restrictions.</p>


<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch32-h">aarch32.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
