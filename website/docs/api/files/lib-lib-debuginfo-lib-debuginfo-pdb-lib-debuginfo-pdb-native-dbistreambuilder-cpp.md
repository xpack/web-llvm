---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistreambuilder-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `DbiStreamBuilder.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistreambuilder-h">llvm/DebugInfo/PDB/Native/DbiStreamBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/coff-h">llvm/BinaryFormat/COFF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugframedatasubsection-h">llvm/DebugInfo/CodeView/DebugFrameDataSubsection.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">llvm/DebugInfo/MSF/MSFBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">llvm/DebugInfo/MSF/MappedBlockStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbimoduledescriptorbuilder-h">llvm/DebugInfo/PDB/Native/DbiModuleDescriptorBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/rawerror-h">llvm/DebugInfo/PDB/Native/RawError.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">llvm/Object/COFF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">llvm/Support/BinaryStreamWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/parallel-h">llvm/Support/Parallel.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/timeprofiler-h">llvm/Support/TimeProfiler.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eb9f50c54774f850a82d2e4e5deed58">toSecMapFlags</a> (uint32_t Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### toSecMapFlags() {#a4eb9f50c54774f850a82d2e4e5deed58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t toSecMapFlags (uint32_t Flags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistreambuilder-cpp">DbiStreamBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a39ee700138913a49bc90faf2c1db0b9ba12640bca518ac6f51d59d626f72a51f2">llvm::pdb::AddressIs32Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a39ee700138913a49bc90faf2c1db0b9ba40cd014b7b6251e3a22e6a45a73a64e1">llvm::pdb::Execute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa64a6c00401f530708fa161270b0b8177">llvm::COFF::IMAGE_SCN_MEM_16BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa447cfc2eddd86f9f90a054d3e111c6d9">llvm::COFF::IMAGE_SCN_MEM_EXECUTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa3c5ce7207c84ca0e6a03fd08ab4831ba">llvm::COFF::IMAGE_SCN_MEM_READ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aac1dfcdc9a17df9b148557d4c01759767">llvm::COFF::IMAGE_SCN_MEM_WRITE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a39ee700138913a49bc90faf2c1db0b9bab2865e8fee77da79e0b04f082effd84d">llvm::pdb::IsSelector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a39ee700138913a49bc90faf2c1db0b9ba7a1a5f3e79fdc91edf2f5ead9d66abb4">llvm::pdb::Read</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a39ee700138913a49bc90faf2c1db0b9ba1129c0e4d43f2d121652a7302712cff6">llvm::pdb::Write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistreambuilder/#a0af5d507fc700e7925e19c7e2911be9b">llvm::pdb::DbiStreamBuilder::createSectionMap</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
