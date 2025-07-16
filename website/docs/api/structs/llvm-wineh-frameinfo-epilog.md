---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/wineh/frameinfo/epilog
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Epilog` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::WinEH::FrameInfo::Epilog { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">llvm/MC/MCWinEH.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">Instruction</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a346001a30654d6b6d77457965833723f">Instructions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cea8eb6141764d39a0b4475191d5b3c">Condition</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adafdf60d887b6f42e55152ae27d0b51b">End</a></td>
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


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Condition {#a5cea8eb6141764d39a0b4475191d5b3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::WinEH::FrameInfo::Epilog::Condition</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a73622e67d89cdc5f662981287e16879f">checkARMPackedEpilog</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a982dd5c343c1b1e191b5cc1d00fefaf6">tryARMPackedUnwind</a>.</p>

</div>
</div>

### End {#adafdf60d887b6f42e55152ae27d0b51b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::WinEH::FrameInfo::Epilog::End</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>

</div>
</div>

### Instructions {#a346001a30654d6b6d77457965833723f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Instruction&gt; llvm::WinEH::FrameInfo::Epilog::Instructions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a73622e67d89cdc5f662981287e16879f">checkARMPackedEpilog</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a982dd5c343c1b1e191b5cc1d00fefaf6">tryARMPackedUnwind</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">MCWinEH.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
