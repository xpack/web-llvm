---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/debuggertuning
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Predicates to tune DWARF for a given debugger Reference

<p>Returns whether we are "tuning" for a given debugger. <a href="#details">More...</a></p>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7967d9d5ff2b6b0344d919d2d27965cb">tuneForGDB</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga98337eccc708fb48a33a9755764014ab">tuneForLLDB</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga12d17eb7e0ee4182377397d9fb39459d">tuneForSCE</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga42e75cae125454aea72ff1c76dabd5b3">tuneForDBX</a> () const</td>
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

<p>Returns whether we are "tuning" for a given debugger.</p>

<div class="doxySectionDef">

## Functions

### tuneForDBX() {#ga42e75cae125454aea72ff1c76dabd5b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::tuneForDBX ()</td>
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



<p>Definition at line 917 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6a5fbfc9a3585a158500a5f9a274c7403a">llvm::DBX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a>.</p>

</div>
</div>

### tuneForGDB() {#ga7967d9d5ff2b6b0344d919d2d27965cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::tuneForGDB ()</td>
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



<p>Definition at line 914 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6abbc0db17ceadc889cc561add9763afc5">llvm::GDB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#afe65683534ca819c702e4eb5f158f387">emitRangeList</a>.</p>

</div>
</div>

### tuneForLLDB() {#ga98337eccc708fb48a33a9755764014ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::tuneForLLDB ()</td>
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



<p>Definition at line 915 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6ac45aa7e8859a50c36c0daa43d65d9fa1">llvm::LLDB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a>.</p>

</div>
</div>

### tuneForSCE() {#ga12d17eb7e0ee4182377397d9fb39459d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::tuneForSCE ()</td>
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



<p>Definition at line 916 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6a4f1fcf80c07532facc35db354783b0b2">llvm::SCE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp/#ac8dcff3941279d4c56ad6f044c1dd54b">AddLinkageNamesToDeclCallOriginsForTuning</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa441f906c99d29f50a64369799d8f737">llvm::DwarfDebug::emitDebugLocValue</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
