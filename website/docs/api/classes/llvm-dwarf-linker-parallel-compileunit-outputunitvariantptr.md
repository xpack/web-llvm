---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/compileunit/outputunitvariantptr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `OutputUnitVariantPtr` Class Reference

<p>Output unit selector. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::CompileUnit::OutputUnitVariantPtr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinker/Parallel/DWARFLinkerCompileUnit.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac188afa7fcf9d7d05f2ceca0082b45eb">OutputUnitVariantPtr</a> (CompileUnit *U)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92171cef08a0a7f2da74cd9a0f3c3e43">OutputUnitVariantPtr</a> (TypeUnit *U)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit">DwarfUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a399cf4b87dddd19fbb568833d2799b8a">operator-&gt;</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accessor for common functionality. <a href="#a399cf4b87dddd19fbb568833d2799b8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7ca32dde35b869ef21b9043a6240014">isCompileUnit</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25079b1c4a37b9cb8d893ddfd2819800">isTypeUnit</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9317eea533090c4df7295701b018f688">getAsCompileUnit</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> if applicable. <a href="#a9317eea533090c4df7295701b018f688">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit">TypeUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2165a5fe9160295ec78b9c25a5442ffb">getAsTypeUnit</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit">TypeUnit</a> if applicable. <a href="#a2165a5fe9160295ec78b9c25a5442ffb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> *, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit">TypeUnit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e1ebe889b01bfd9365c798459cf5616">Ptr</a></td>
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

## Description {#details}

<p>Output unit selector.</p>

<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OutputUnitVariantPtr() {#ac188afa7fcf9d7d05f2ceca0082b45eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileUnit::OutputUnitVariantPtr::OutputUnitVariantPtr (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> * U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1799 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#abe722b66707f8b5e4aaa19a24810480f">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a> and <a href="#a7e1ebe889b01bfd9365c798459cf5616">Ptr</a>.</p>

</div>
</div>

### OutputUnitVariantPtr() {#a92171cef08a0a7f2da74cd9a0f3c3e43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileUnit::OutputUnitVariantPtr::OutputUnitVariantPtr (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit">TypeUnit</a> * U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1804 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7e1ebe889b01bfd9365c798459cf5616">Ptr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator-&gt;() {#a399cf4b87dddd19fbb568833d2799b8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfUnit * CompileUnit::OutputUnitVariantPtr::operator-&gt; ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Accessor for common functionality.</p>

<p>Declaration at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1808 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ad367b733292adfe15b6d45c5fc4db8b2">llvm::dwarf_linker::parallel::DwarfUnit::DwarfUnit</a>, <a href="#a9317eea533090c4df7295701b018f688">getAsCompileUnit</a>, <a href="#a2165a5fe9160295ec78b9c25a5442ffb">getAsTypeUnit</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ada33d5221e33153a5557787ab6c9e3bb">llvm::isCompileUnit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAsCompileUnit() {#a9317eea533090c4df7295701b018f688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileUnit * CompileUnit::OutputUnitVariantPtr::getAsCompileUnit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> if applicable.</p>

<p>Declaration at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1823 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#abe722b66707f8b5e4aaa19a24810480f">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a> and <a href="#a7e1ebe889b01bfd9365c798459cf5616">Ptr</a>.</p>


<p>Referenced by <a href="#a399cf4b87dddd19fbb568833d2799b8a">operator-&gt;</a>.</p>

</div>
</div>

### getAsTypeUnit() {#a2165a5fe9160295ec78b9c25a5442ffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeUnit * CompileUnit::OutputUnitVariantPtr::getAsTypeUnit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit">TypeUnit</a> if applicable.</p>

<p>Declaration at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1827 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a7e1ebe889b01bfd9365c798459cf5616">Ptr</a>.</p>


<p>Referenced by <a href="#a399cf4b87dddd19fbb568833d2799b8a">operator-&gt;</a>.</p>

</div>
</div>

### isCompileUnit() {#af7ca32dde35b869ef21b9043a6240014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CompileUnit::OutputUnitVariantPtr::isCompileUnit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1815 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a7e1ebe889b01bfd9365c798459cf5616">Ptr</a>.</p>

</div>
</div>

### isTypeUnit() {#a25079b1c4a37b9cb8d893ddfd2819800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CompileUnit::OutputUnitVariantPtr::isTypeUnit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 590 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1819 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a7e1ebe889b01bfd9365c798459cf5616">Ptr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Ptr {#a7e1ebe889b01bfd9365c798459cf5616}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerUnion&lt;CompileUnit *, TypeUnit *&gt; llvm::dwarf_linker::parallel::CompileUnit::OutputUnitVariantPtr::Ptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Referenced by <a href="#a9317eea533090c4df7295701b018f688">getAsCompileUnit</a>, <a href="#a2165a5fe9160295ec78b9c25a5442ffb">getAsTypeUnit</a>, <a href="#af7ca32dde35b869ef21b9043a6240014">isCompileUnit</a>, <a href="#a25079b1c4a37b9cb8d893ddfd2819800">isTypeUnit</a>, <a href="#ac188afa7fcf9d7d05f2ceca0082b45eb">OutputUnitVariantPtr</a> and <a href="#a92171cef08a0a7f2da74cd9a0f3c3e43">OutputUnitVariantPtr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
