---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-dwarfcontext-cpp-/threadsafestate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ThreadSafeState` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{DWARFContext.cpp}::ThreadSafeState { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate">ThreadUnsafeDWARFContextState</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4773c21f1df830fd7ddbea0cfb0e0cf1">ThreadSafeState</a> (DWARFContext &amp;DC, std::string &amp;DWP)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector">DWARFUnitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a98c66372371312392e2e743e210484">getNormalUnits</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector">DWARFUnitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad761a2b6ab159a6e4fb2db4a873cd296">getDWOUnits</a> (bool Lazy) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitindex">DWARFUnitIndex</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac60856f18883bf7af90ef318cf98b76a">getCUIndex</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugabbrev">DWARFDebugAbbrev</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaffc663a86009125fcbafd62ddc2072c">getDebugAbbrevDWO</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitindex">DWARFUnitIndex</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a373675d7af9ec1b2312a6e9a13e02215">getTUIndex</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfgdbindex">DWARFGdbIndex</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd511a6b37c049aa2528979d7af7194d">getGdbIndex</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugabbrev">DWARFDebugAbbrev</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a937cea8ab92f207be8373537f9317b67">getDebugAbbrev</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloc">DWARFDebugLoc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29d7d35d3b873bf10dca52b79844f6ec">getDebugLoc</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugaranges">DWARFDebugAranges</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c69465a34b32fb3f2d8e867b4cd71ca">getDebugAranges</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable">DWARFDebugLine::LineTable</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa2f7e7368f8543ff89c16b88f280603">getLineTableForUnit</a> (DWARFUnit *U, function_ref&lt; void(Error)&gt; RecoverableErrorHandler) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cff273d8f3732631e66f8182a1347e0">clearLineTableForUnit</a> (DWARFUnit *U) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugframe">DWARFDebugFrame</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a270895457422212c73ce2dd71c8b6f6f">getDebugFrame</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugframe">DWARFDebugFrame</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb3c7b81339ceddda135c50fc6f5cf26">getEHFrame</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24582ff542501a5b963de55526c9a9a2">getDebugMacinfo</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8b6b1a03679be0e3f1b492bd26df233">getDebugMacinfoDWO</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cf7b0f880434a07fa31ad5b2edb05c1">getDebugMacro</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af03cf10aa9dad2d0da6e15ddeb56be85">getDebugMacroDWO</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames">DWARFDebugNames</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0be279b1818d10f7cf968a221b77d33c">getDebugNames</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27c941abc93fe2a1b912edca262a6961">getAppleNames</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96aa31f1a1b3aed5d54e2c6741d6d7ed">getAppleTypes</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac23eba14c19e460f03efe600a9061468">getAppleNamespaces</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a5fc38f8e6df2cedfebcfd8fd67bae2">getAppleObjC</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ac644d0d9a801eda9c691229f4b19c5">getDWOContext</a> (StringRef AbsolutePath) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d707ade5b4fba9fdf4857db67063f06">isThreadSafe</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit">DWARFTypeUnit</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39b0b3332ae86991d319265f3e37947d">getTypeUnitMap</a> (bool IsDWO) override</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::recursive_mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0dbcaedaa00debbbfdb3eebc8cc3010">Mutex</a></td>
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


<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ThreadSafeState() {#a4773c21f1df830fd7ddbea0cfb0e0cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DWARFContext.cpp}::ThreadSafeState::ThreadSafeState (<a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp; DC, std::string &amp; DWP)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#aec1a114492047a6d129804286951299f">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::ThreadUnsafeDWARFContextState</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearLineTableForUnit() {#a3cff273d8f3732631e66f8182a1347e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DWARFContext.cpp}::ThreadSafeState::clearLineTableForUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * U)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#ac51a5bd8917ab80869b88b6c7f66edb0">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::clearLineTableForUnit</a>.</p>

</div>
</div>

### getAppleNames() {#a27c941abc93fe2a1b912edca262a6961}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AppleAcceleratorTable &amp; anonymous{DWARFContext.cpp}::ThreadSafeState::getAppleNames ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a44311fbd55fbc785d3bdcfa5b532d296">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getAppleNames</a>.</p>

</div>
</div>

### getAppleNamespaces() {#ac23eba14c19e460f03efe600a9061468}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AppleAcceleratorTable &amp; anonymous{DWARFContext.cpp}::ThreadSafeState::getAppleNamespaces ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a96f19aab275174b4e2968ad2375cf540">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getAppleNamespaces</a>.</p>

</div>
</div>

### getAppleObjC() {#a1a5fc38f8e6df2cedfebcfd8fd67bae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AppleAcceleratorTable &amp; anonymous{DWARFContext.cpp}::ThreadSafeState::getAppleObjC ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a656b58e082a146fe210b1f7c7ae68ffa">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getAppleObjC</a>.</p>

</div>
</div>

### getAppleTypes() {#a96aa31f1a1b3aed5d54e2c6741d6d7ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AppleAcceleratorTable &amp; anonymous{DWARFContext.cpp}::ThreadSafeState::getAppleTypes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#abb6e436a25f8fd3fae8c26d941c6971b">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getAppleTypes</a>.</p>

</div>
</div>

### getCUIndex() {#ac60856f18883bf7af90ef318cf98b76a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFUnitIndex &amp; anonymous{DWARFContext.cpp}::ThreadSafeState::getCUIndex ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#ad032d08aafabfc5c58827536e0b8e3a4">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getCUIndex</a>.</p>

</div>
</div>

### getDebugAbbrev() {#a937cea8ab92f207be8373537f9317b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugAbbrev * anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugAbbrev ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a522f51507f18c0124fd84fd85b06de5a">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugAbbrev</a>.</p>

</div>
</div>

### getDebugAbbrevDWO() {#aaffc663a86009125fcbafd62ddc2072c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugAbbrev * anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugAbbrevDWO ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a04426759b3da000ac6978dfcc0058cd4">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugAbbrevDWO</a>.</p>

</div>
</div>

### getDebugAranges() {#a5c69465a34b32fb3f2d8e867b4cd71ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugAranges * anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugAranges ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 671 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a6fd9cf37b2152d0cab243ae6c4596d9b">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugAranges</a>.</p>

</div>
</div>

### getDebugFrame() {#a270895457422212c73ce2dd71c8b6f6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const DWARFDebugFrame * &gt; anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugFrame ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#afa31bee239029c3abc70cd0b480cbdfd">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugFrame</a>.</p>

</div>
</div>

### getDebugLoc() {#a29d7d35d3b873bf10dca52b79844f6ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugLoc * anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugLoc ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a4451ac5951510e536480746dfc6ab786">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugLoc</a>.</p>

</div>
</div>

### getDebugMacinfo() {#a24582ff542501a5b963de55526c9a9a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugMacro * anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugMacinfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 692 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a8bbcc1d37b98896d500cde4b3f1c6347">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugMacinfo</a>.</p>

</div>
</div>

### getDebugMacinfoDWO() {#af8b6b1a03679be0e3f1b492bd26df233}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugMacro * anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugMacinfoDWO ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#aa45411f4341761736a1ab3429e8574de">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugMacinfoDWO</a>.</p>

</div>
</div>

### getDebugMacro() {#a0cf7b0f880434a07fa31ad5b2edb05c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugMacro * anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugMacro ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a7f2d3dfbdcefba19d666d23c7c3821a9">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugMacro</a>.</p>

</div>
</div>

### getDebugMacroDWO() {#af03cf10aa9dad2d0da6e15ddeb56be85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugMacro * anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugMacroDWO ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#ad95e134993054181567b6ad197eb9180">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugMacroDWO</a>.</p>

</div>
</div>

### getDebugNames() {#a0be279b1818d10f7cf968a221b77d33c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugNames &amp; anonymous{DWARFContext.cpp}::ThreadSafeState::getDebugNames ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a4be087659bb12b2862f4b1975bf021aa">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugNames</a>.</p>

</div>
</div>

### getDWOContext() {#a7ac644d0d9a801eda9c691229f4b19c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt; DWARFContext &gt; anonymous{DWARFContext.cpp}::ThreadSafeState::getDWOContext (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> AbsolutePath)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 729 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a54233894e754c548da87c0d21d69003d">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDWOContext</a>.</p>

</div>
</div>

### getDWOUnits() {#ad761a2b6ab159a6e4fb2db4a873cd296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnitVector &amp; anonymous{DWARFContext.cpp}::ThreadSafeState::getDWOUnits (bool Lazy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a2cf5ad189d1366bf9cc1d4c2d6be644e">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDWOUnits</a>.</p>

</div>
</div>

### getEHFrame() {#aeb3c7b81339ceddda135c50fc6f5cf26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const DWARFDebugFrame * &gt; anonymous{DWARFContext.cpp}::ThreadSafeState::getEHFrame ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a759c4a9026418f467ca84e2b0009a1f0">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getEHFrame</a>.</p>

</div>
</div>

### getGdbIndex() {#acd511a6b37c049aa2528979d7af7194d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFGdbIndex &amp; anonymous{DWARFContext.cpp}::ThreadSafeState::getGdbIndex ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a7d54016517fbbd3c357911beafffa1ea">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getGdbIndex</a>.</p>

</div>
</div>

### getLineTableForUnit() {#afa2f7e7368f8543ff89c16b88f280603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const DWARFDebugLine::LineTable * &gt; anonymous{DWARFContext.cpp}::ThreadSafeState::getLineTableForUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * U, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; RecoverableErrorHandler)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a7f3dd834ea74cf44bbf7c9b9c16f6e56">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getLineTableForUnit</a>.</p>

</div>
</div>

### getNormalUnits() {#a9a98c66372371312392e2e743e210484}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnitVector &amp; anonymous{DWARFContext.cpp}::ThreadSafeState::getNormalUnits ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#ad09d62c07974b0102948172e96282db8">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getNormalUnits</a>.</p>

</div>
</div>

### getTUIndex() {#a373675d7af9ec1b2312a6e9a13e02215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFUnitIndex &amp; anonymous{DWARFContext.cpp}::ThreadSafeState::getTUIndex ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a5b2494f7af81f725a1ca1cd7bb3f2f0d">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getTUIndex</a>.</p>

</div>
</div>

### getTypeUnitMap() {#a39b0b3332ae86991d319265f3e37947d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DenseMap&lt; uint64_t, DWARFTypeUnit * &gt; &amp; anonymous{DWARFContext.cpp}::ThreadSafeState::getTypeUnitMap (bool IsDWO)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 737 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#aea5006d4434f7f94cd614d08034212a8">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getTypeUnitMap</a>.</p>

</div>
</div>

### isThreadSafe() {#a2d707ade5b4fba9fdf4857db67063f06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DWARFContext.cpp}::ThreadSafeState::isThreadSafe ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 734 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Mutex {#ac0dbcaedaa00debbbfdb3eebc8cc3010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::recursive_mutex anonymous{DWARFContext.cpp}::ThreadSafeState::Mutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
