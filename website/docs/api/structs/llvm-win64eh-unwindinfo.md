---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/win64eh/unwindinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `UnwindInfo` Struct

<p><a href="/web-llvm/docs/api/structs/llvm/win64eh/unwindinfo">UnwindInfo</a> - An entry in the exception table. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::Win64EH::UnwindInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">llvm/Support/Win64EH.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac691a997cc8c11837d4e8534dd48f992">getVersion</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32bbcdbb8443a7360498aa457ea8fa6d">getFlags</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a221d270d61fda7c2de76077c5e264b12">getFrameRegister</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18b46ba644af2cd55351c2f1b7d121bf">getFrameOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3785361b970b836ca527decee3dcc65">getLanguageSpecificData</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return pointer to language specific data part of <a href="/web-llvm/docs/api/structs/llvm/win64eh/unwindinfo">UnwindInfo</a>. <a href="#ac3785361b970b836ca527decee3dcc65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a383cd99b249e2551a489cb1a97170feb">getLanguageSpecificData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return pointer to language specific data part of <a href="/web-llvm/docs/api/structs/llvm/win64eh/unwindinfo">UnwindInfo</a>. <a href="#a383cd99b249e2551a489cb1a97170feb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3f3c8dd926873fd97006b3fb0f41b63">getLanguageSpecificHandlerOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return image-relative offset of language-specific exception handler. <a href="#ab3f3c8dd926873fd97006b3fb0f41b63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4658491b0f12c7af395d396943a7d542">setLanguageSpecificHandlerOffset</a> (uint32_t offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set image-relative offset of language-specific exception handler. <a href="#a4658491b0f12c7af395d396943a7d542">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0876fe9769944f5c8b8407d8a8b66063">getExceptionData</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return pointer to exception-specific data. <a href="#a0876fe9769944f5c8b8407d8a8b66063">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/win64eh/runtimefunction">RuntimeFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcfb9a8ab2f636ad99390eb86e833ad6">getChainedFunctionEntry</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return pointer to chained unwind info. <a href="#afcfb9a8ab2f636ad99390eb86e833ad6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/win64eh/runtimefunction">RuntimeFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa851e62c3a1711edc7549f33ca937c61">getChainedFunctionEntry</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return pointer to chained unwind info. <a href="#aa851e62c3a1711edc7549f33ca937c61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a485efadb45dde33d030462c548885bf9">VersionAndFlags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d5046f2af7c6eb42afc8cc7045ad2f6">PrologSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7e3e4f5e7b3e85d95fa7374b0a59063">NumCodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a709be2f59e26371e6f8fdfea39ed0142">FrameRegisterAndOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/unions/llvm/win64eh/unwindcode">UnwindCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24ce8b4d3a1e0eeaf0a6413add9d387b">UnwindCodes</a>[1]</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/win64eh/unwindinfo">UnwindInfo</a> - An entry in the exception table.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getChainedFunctionEntry() {#afcfb9a8ab2f636ad99390eb86e833ad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction * llvm::Win64EH::UnwindInfo::getChainedFunctionEntry ()</td>
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

<p>Return pointer to chained unwind info.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>


<p>Reference <a href="#ac3785361b970b836ca527decee3dcc65">getLanguageSpecificData</a>.</p>

</div>
</div>

### getChainedFunctionEntry() {#aa851e62c3a1711edc7549f33ca937c61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RuntimeFunction * llvm::Win64EH::UnwindInfo::getChainedFunctionEntry ()</td>
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

<p>Return pointer to chained unwind info.</p>

<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>


<p>Reference <a href="#ac3785361b970b836ca527decee3dcc65">getLanguageSpecificData</a>.</p>

</div>
</div>

### getExceptionData() {#a0876fe9769944f5c8b8407d8a8b66063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::Win64EH::UnwindInfo::getExceptionData ()</td>
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

<p>Return pointer to exception-specific data.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>


<p>Reference <a href="#ac3785361b970b836ca527decee3dcc65">getLanguageSpecificData</a>.</p>

</div>
</div>

### getFlags() {#a32bbcdbb8443a7360498aa457ea8fa6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::Win64EH::UnwindInfo::getFlags ()</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>


<p>Reference <a href="#a485efadb45dde33d030462c548885bf9">VersionAndFlags</a>.</p>

</div>
</div>

### getFrameOffset() {#a18b46ba644af2cd55351c2f1b7d121bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::Win64EH::UnwindInfo::getFrameOffset ()</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>


<p>Reference <a href="#a709be2f59e26371e6f8fdfea39ed0142">FrameRegisterAndOffset</a>.</p>

</div>
</div>

### getFrameRegister() {#a221d270d61fda7c2de76077c5e264b12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::Win64EH::UnwindInfo::getFrameRegister ()</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>


<p>Reference <a href="#a709be2f59e26371e6f8fdfea39ed0142">FrameRegisterAndOffset</a>.</p>

</div>
</div>

### getLanguageSpecificData() {#ac3785361b970b836ca527decee3dcc65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::Win64EH::UnwindInfo::getLanguageSpecificData ()</td>
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

<p>Return pointer to language specific data part of <a href="/web-llvm/docs/api/structs/llvm/win64eh/unwindinfo">UnwindInfo</a>.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>


<p>References <a href="#af7e3e4f5e7b3e85d95fa7374b0a59063">NumCodes</a> and <a href="#a24ce8b4d3a1e0eeaf0a6413add9d387b">UnwindCodes</a>.</p>


<p>Referenced by <a href="#afcfb9a8ab2f636ad99390eb86e833ad6">getChainedFunctionEntry</a>, <a href="#aa851e62c3a1711edc7549f33ca937c61">getChainedFunctionEntry</a>, <a href="#a0876fe9769944f5c8b8407d8a8b66063">getExceptionData</a>, <a href="#ab3f3c8dd926873fd97006b3fb0f41b63">getLanguageSpecificHandlerOffset</a> and <a href="#a4658491b0f12c7af395d396943a7d542">setLanguageSpecificHandlerOffset</a>.</p>

</div>
</div>

### getLanguageSpecificData() {#a383cd99b249e2551a489cb1a97170feb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const void * llvm::Win64EH::UnwindInfo::getLanguageSpecificData ()</td>
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

<p>Return pointer to language specific data part of <a href="/web-llvm/docs/api/structs/llvm/win64eh/unwindinfo">UnwindInfo</a>.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>


<p>References <a href="#af7e3e4f5e7b3e85d95fa7374b0a59063">NumCodes</a> and <a href="#a24ce8b4d3a1e0eeaf0a6413add9d387b">UnwindCodes</a>.</p>

</div>
</div>

### getLanguageSpecificHandlerOffset() {#ab3f3c8dd926873fd97006b3fb0f41b63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::Win64EH::UnwindInfo::getLanguageSpecificHandlerOffset ()</td>
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

<p>Return image-relative offset of language-specific exception handler.</p>

<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>


<p>Reference <a href="#ac3785361b970b836ca527decee3dcc65">getLanguageSpecificData</a>.</p>

</div>
</div>

### getVersion() {#ac691a997cc8c11837d4e8534dd48f992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::Win64EH::UnwindInfo::getVersion ()</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>


<p>Reference <a href="#a485efadb45dde33d030462c548885bf9">VersionAndFlags</a>.</p>

</div>
</div>

### setLanguageSpecificHandlerOffset() {#a4658491b0f12c7af395d396943a7d542}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Win64EH::UnwindInfo::setLanguageSpecificHandlerOffset (uint32_t offset)</td>
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

<p>Set image-relative offset of language-specific exception handler.</p>

<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>


<p>Reference <a href="#ac3785361b970b836ca527decee3dcc65">getLanguageSpecificData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### FrameRegisterAndOffset {#a709be2f59e26371e6f8fdfea39ed0142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::Win64EH::UnwindInfo::FrameRegisterAndOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>


<p>Referenced by <a href="#a18b46ba644af2cd55351c2f1b7d121bf">getFrameOffset</a> and <a href="#a221d270d61fda7c2de76077c5e264b12">getFrameRegister</a>.</p>

</div>
</div>

### NumCodes {#af7e3e4f5e7b3e85d95fa7374b0a59063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::Win64EH::UnwindInfo::NumCodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>


<p>Referenced by <a href="#ac3785361b970b836ca527decee3dcc65">getLanguageSpecificData</a> and <a href="#a383cd99b249e2551a489cb1a97170feb">getLanguageSpecificData</a>.</p>

</div>
</div>

### PrologSize {#a2d5046f2af7c6eb42afc8cc7045ad2f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::Win64EH::UnwindInfo::PrologSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>

</div>
</div>

### UnwindCodes {#a24ce8b4d3a1e0eeaf0a6413add9d387b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnwindCode llvm::Win64EH::UnwindInfo::UnwindCodes[1]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>


<p>Referenced by <a href="#ac3785361b970b836ca527decee3dcc65">getLanguageSpecificData</a> and <a href="#a383cd99b249e2551a489cb1a97170feb">getLanguageSpecificData</a>.</p>

</div>
</div>

### VersionAndFlags {#a485efadb45dde33d030462c548885bf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::Win64EH::UnwindInfo::VersionAndFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>


<p>Referenced by <a href="#a32bbcdbb8443a7360498aa457ea8fa6d">getFlags</a> and <a href="#ac691a997cc8c11837d4e8534dd48f992">getVersion</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
