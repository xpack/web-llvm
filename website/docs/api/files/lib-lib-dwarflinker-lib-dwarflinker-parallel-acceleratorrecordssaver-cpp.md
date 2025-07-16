---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AcceleratorRecordsSaver.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-h">AcceleratorRecordsSaver.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/utils-h">llvm/DWARFLinker/Utils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">llvm/DebugInfo/DWARF/DWARFAcceleratorTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/djb-h">llvm/Support/DJB.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9301753b7bb43fbe58a0c9ea05711537">hashFullyQualifiedName</a> (CompileUnit &amp;InputCU, DWARFDie &amp;InputDIE, int ChildRecurseDepth=0)</td>
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

### hashFullyQualifiedName() {#a9301753b7bb43fbe58a0c9ea05711537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t hashFullyQualifiedName (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; InputCU, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; InputDIE, int ChildRecurseDepth=0)</td>
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



<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-cpp">AcceleratorRecordsSaver.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba816fb56fad484d9cd712825dcacaa6">llvm::djbHash</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a031683a2f97f9d8db3b493ada43e2228aecc352ab32050f10e6c1d07d39eca711">llvm::DWARFFormValue::FC_Reference</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a315f90678bfa85d85d71a9dd12d5457a">llvm::DWARFDie::find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a98a8554492a59019e487d750863f96f2">llvm::dwarf_linker::finiteLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a834590fd64e02e844dd117b380ab819b">llvm::DWARFDie::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a2fa3d574c395e0628051860fc9be0463">llvm::DWARFDie::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#ac07a6d11b09b4e2c92e9609b6843e9ea">llvm::DWARFDie::getTag</a>, <a href="#a9301753b7bb43fbe58a0c9ea05711537">hashFullyQualifiedName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#ae970d60ab52d996448bb030b4a0b67bc">llvm::DWARFDie::isValid</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870ad26b007baa81cc3cd38d8d6c93e6df42">llvm::ShortName</a>.</p>


<p>Referenced by <a href="#a9301753b7bb43fbe58a0c9ea05711537">hashFullyQualifiedName</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver/#aca2d3ebfb1896c7f85f76bcb6dea8b81">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::save</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
