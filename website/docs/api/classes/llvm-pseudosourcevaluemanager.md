---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pseudosourcevaluemanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PseudoSourceValueManager` Class Reference

<p>Manages creation of pseudo source values. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PseudoSourceValueManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">llvm/CodeGen/PseudoSourceValueManager.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea2cc4c9bf64cf77d023c25de40ad870">PseudoSourceValueManager</a> (const TargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b8d7cb4795dfcfae3cbaca1968e66e">getStack</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pseudo source value referencing the area below the stack frame of a function, e.g., the argument space. <a href="#a50b8d7cb4795dfcfae3cbaca1968e66e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a364a4f44b8f382dad30d424633b973f3">getGOT</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pseudo source value referencing the global offset table (or something the like). <a href="#a364a4f44b8f382dad30d424633b973f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a4c66e2326c94e5d10c96b46a09ab63">getConstantPool</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pseudo source value referencing the constant pool. <a href="#a6a4c66e2326c94e5d10c96b46a09ab63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eb9e9d314956cdcfb85f33c863fbe92">getJumpTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pseudo source value referencing a jump table. <a href="#a0eb9e9d314956cdcfb85f33c863fbe92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2909d8f067ac86f7e34f4318f972e447">getFixedStack</a> (int FI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pseudo source value referencing a fixed stack frame entry, e.g., a spill slot. <a href="#a2909d8f067ac86f7e34f4318f972e447">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3932a6cadb29b9d5d4634c48cd7c6d11">getGlobalValueCallEntry</a> (const GlobalValue *GV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a247e545df9715101da536adc144200e4">getExternalSymbolCallEntry</a> (const char *ES)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c9ec9dc876fdfd8a29bf4effeb63569">TM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e8e16cbe07d6bc4bdfc9d76cb6500f2">StackPSV</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acad0e2659acdf066fa753aebdd070b57">GOTPSV</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2ca493c10d13f4bae9c93a2c99d0cd4">JumpTablePSV</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76efab672226c9c60c98f38e0333563d">ConstantPoolPSV</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/fixedstackpseudosourcevalue">FixedStackPseudoSourceValue</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13794b93c47a0065dc167f6433c11909">FSValues</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/externalsymbolpseudosourcevalue">ExternalSymbolPseudoSourceValue</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab28a4eff8bca9fa5f2f978c19378c921">ExternalCallEntries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluepseudosourcevalue">GlobalValuePseudoSourceValue</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8d356c7ae4413f620ee21151da29849">GlobalCallEntries</a></td>
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

<p>Manages creation of pseudo source values.</p>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PseudoSourceValueManager() {#aea2cc4c9bf64cf77d023c25de40ad870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PseudoSourceValueManager::PseudoSourceValueManager (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/pseudosourcevalue-cpp">PseudoSourceValue.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getConstantPool() {#a6a4c66e2326c94e5d10c96b46a09ab63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PseudoSourceValue * PseudoSourceValueManager::getConstantPool ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a pseudo source value referencing the constant pool.</p>


<p>Since constant pools are constant, this doesn't need to identify a specific constant pool entry.</p>


<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/pseudosourcevalue-cpp">PseudoSourceValue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a8b1a64bd0c1be7a99998055c78d1312b">llvm::MachinePointerInfo::getConstantPool</a>.</p>

</div>
</div>

### getExternalSymbolCallEntry() {#a247e545df9715101da536adc144200e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PseudoSourceValue * PseudoSourceValueManager::getExternalSymbolCallEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ES)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/pseudosourcevalue-cpp">PseudoSourceValue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#a41e84c8c57ae0060cabaabcd1493bf9e">llvm::MipsFunctionInfo::callPtrInfo</a>.</p>

</div>
</div>

### getFixedStack() {#a2909d8f067ac86f7e34f4318f972e447}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PseudoSourceValue * PseudoSourceValueManager::getFixedStack (int FI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a pseudo source value referencing a fixed stack frame entry, e.g., a spill slot.</p>

<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/pseudosourcevalue-cpp">PseudoSourceValue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>.</p>

</div>
</div>

### getGlobalValueCallEntry() {#a3932a6cadb29b9d5d4634c48cd7c6d11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PseudoSourceValue * PseudoSourceValueManager::getGlobalValueCallEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/pseudosourcevalue-cpp">PseudoSourceValue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#a44e2bbf88fbae15ddb73760c8123954d">llvm::MipsFunctionInfo::callPtrInfo</a>.</p>

</div>
</div>

### getGOT() {#a364a4f44b8f382dad30d424633b973f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PseudoSourceValue * PseudoSourceValueManager::getGOT ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a pseudo source value referencing the global offset table (or something the like).</p>

<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/pseudosourcevalue-cpp">PseudoSourceValue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#aa70144cee705b3f0db7f53ff3bf004e9">llvm::MachinePointerInfo::getGOT</a>.</p>

</div>
</div>

### getJumpTable() {#a0eb9e9d314956cdcfb85f33c863fbe92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PseudoSourceValue * PseudoSourceValueManager::getJumpTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a pseudo source value referencing a jump table.</p>


<p>Since jump tables are constant, this doesn't need to identify a specific jump table.</p>


<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/pseudosourcevalue-cpp">PseudoSourceValue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a15667eb123c1638704fe9cb7b2ac208b">llvm::MachinePointerInfo::getJumpTable</a>.</p>

</div>
</div>

### getStack() {#a50b8d7cb4795dfcfae3cbaca1968e66e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PseudoSourceValue * PseudoSourceValueManager::getStack ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a pseudo source value referencing the area below the stack frame of a function, e.g., the argument space.</p>

<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/pseudosourcevalue-cpp">PseudoSourceValue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a2f877286c09d06ac6b9c5534736433d9">llvm::MachinePointerInfo::getStack</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ConstantPoolPSV {#a76efab672226c9c60c98f38e0333563d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PseudoSourceValue llvm::PseudoSourceValueManager::ConstantPoolPSV</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a>.</p>

</div>
</div>

### ExternalCallEntries {#ab28a4eff8bca9fa5f2f978c19378c921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::unique_ptr&lt;const ExternalSymbolPseudoSourceValue&gt; &gt; llvm::PseudoSourceValueManager::ExternalCallEntries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a>.</p>

</div>
</div>

### FSValues {#a13794b93c47a0065dc167f6433c11909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;FixedStackPseudoSourceValue&gt; &gt; llvm::PseudoSourceValueManager::FSValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a>.</p>

</div>
</div>

### GlobalCallEntries {#ab8d356c7ae4413f620ee21151da29849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueMap&lt;const GlobalValue *, std::unique_ptr&lt;const GlobalValuePseudoSourceValue&gt; &gt; llvm::PseudoSourceValueManager::GlobalCallEntries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a>.</p>

</div>
</div>

### GOTPSV {#acad0e2659acdf066fa753aebdd070b57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PseudoSourceValue llvm::PseudoSourceValueManager::GOTPSV</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a>.</p>

</div>
</div>

### JumpTablePSV {#aa2ca493c10d13f4bae9c93a2c99d0cd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PseudoSourceValue llvm::PseudoSourceValueManager::JumpTablePSV</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a>.</p>

</div>
</div>

### StackPSV {#a3e8e16cbe07d6bc4bdfc9d76cb6500f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PseudoSourceValue llvm::PseudoSourceValueManager::StackPSV</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a>.</p>

</div>
</div>

### TM {#a6c9ec9dc876fdfd8a29bf4effeb63569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetMachine&amp; llvm::PseudoSourceValueManager::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">PseudoSourceValueManager.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/pseudosourcevalue-cpp">PseudoSourceValue.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
