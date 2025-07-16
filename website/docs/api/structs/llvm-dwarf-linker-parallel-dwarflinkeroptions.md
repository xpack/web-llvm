---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarf-linker/parallel/dwarflinkeroptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DWARFLinkerOptions` Struct Reference

<p>linking options <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::dwarf_linker::parallel::DWARFLinkerOptions { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinker/Parallel/DWARFLinkerGlobalData.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44548ea51a7a3a4ba06a921d43b874be">TargetDWARFVersion</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DWARF version for the output. <a href="#a44548ea51a7a3a4ba06a921d43b874be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b508ddf784702f18079fa995522858b">Verbose</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate processing log to the standard output. <a href="#a2b508ddf784702f18079fa995522858b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada6d21af43986bd389dd2b165454cb5e">Statistics</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print statistics. <a href="#ada6d21af43986bd389dd2b165454cb5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7af2635dbf7eabcfb1fea5e933065e1e">VerifyInputDWARF</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the input DWARF. <a href="#a7af2635dbf7eabcfb1fea5e933065e1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cad01ae18054f3a918286b97f32ee3c">NoODR</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do not unique types according to ODR. <a href="#a4cad01ae18054f3a918286b97f32ee3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0fde97dc4343f593eb4a01436cd05b9">UpdateIndexTablesOnly</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update index tables. <a href="#ad0fde97dc4343f593eb4a01436cd05b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0304dfc63cdd99efba5f330f2f39fbe7">KeepFunctionForStatic</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether we want a static variable to force us to keep its enclosing function. <a href="#a0304dfc63cdd99efba5f330f2f39fbe7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cf7eaa1914002989dd579f683907a58">AllowNonDeterministicOutput</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow to generate valid, but non deterministic output. <a href="#a4cf7eaa1914002989dd579f683907a58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae68d3cab00cbc12c2f7af38c6d74a674">Threads</a> = 1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of threads. <a href="#ae68d3cab00cbc12c2f7af38c6d74a674">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a78ca7920cd1aaf69f7da553285c55308">DWARFLinkerBase::AccelTableKind</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f4e5c8bada3ae219059fce1f12529ae">AccelTables</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The accelerator table kinds. <a href="#a3f4e5c8bada3ae219059fce1f12529ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b4d1969e9d1a09e808debff611e46ea">PrependPath</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepend path for the clang modules. <a href="#a6b4d1969e9d1a09e808debff611e46ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#ac482b3b01bd8e00cd02ecfba94e88694">DWARFLinkerBase::InputVerificationHandlerTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af525e29f46c247419bfe277b66fd6dcb">InputVerificationHandler</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>input verification handler(it might be called asynchronously). <a href="#af525e29f46c247419bfe277b66fd6dcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#ab7230244084c9a0c89b2113444331260">DWARFLinkerBase::SwiftInterfacesMapTy</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30fbbcfa4b40cbf2bad3b75c6f24dc74">ParseableSwiftInterfaces</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of all .swiftinterface files referenced by the debug info, mapping <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> name to path on disk. <a href="#a30fbbcfa4b40cbf2bad3b75c6f24dc74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a0b10e00e608ed9bcead9c3c7bcd62b4c">DWARFLinkerBase::ObjectPrefixMapTy</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030e371ebba14e496848104fd2e157f9">ObjectPrefixMap</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of remappings to apply to file paths. <a href="#a030e371ebba14e496848104fd2e157f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>linking options</p>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### AccelTables {#a3f4e5c8bada3ae219059fce1f12529ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DWARFLinkerBase::AccelTableKind, 1&gt; llvm::dwarf_linker::parallel::DWARFLinkerOptions::AccelTables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The accelerator table kinds.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>

</div>
</div>

### AllowNonDeterministicOutput {#a4cf7eaa1914002989dd579f683907a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::DWARFLinkerOptions::AllowNonDeterministicOutput = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow to generate valid, but non deterministic output.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>

</div>
</div>

### InputVerificationHandler {#af525e29f46c247419bfe277b66fd6dcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFLinkerBase::InputVerificationHandlerTy llvm::dwarf_linker::parallel::DWARFLinkerOptions::InputVerificationHandler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>input verification handler(it might be called asynchronously).</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      nullptr
</div>
</dd>
</dl>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>

</div>
</div>

### KeepFunctionForStatic {#a0304dfc63cdd99efba5f330f2f39fbe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::DWARFLinkerOptions::KeepFunctionForStatic = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether we want a static variable to force us to keep its enclosing function.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>

</div>
</div>

### NoODR {#a4cad01ae18054f3a918286b97f32ee3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::DWARFLinkerOptions::NoODR = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do not unique types according to ODR.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>

</div>
</div>

### ObjectPrefixMap {#a030e371ebba14e496848104fd2e157f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFLinkerBase::ObjectPrefixMapTy* llvm::dwarf_linker::parallel::DWARFLinkerOptions::ObjectPrefixMap = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A list of remappings to apply to file paths.</p>


<p>(it might be called asynchronously).</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>

</div>
</div>

### ParseableSwiftInterfaces {#a30fbbcfa4b40cbf2bad3b75c6f24dc74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFLinkerBase::SwiftInterfacesMapTy* llvm::dwarf_linker::parallel::DWARFLinkerOptions::ParseableSwiftInterfaces = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A list of all .swiftinterface files referenced by the debug info, mapping <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> name to path on disk.</p>


<p>The entries need to be uniqued and sorted and there are only few entries expected per compile unit, which is why this is a std::map. this is dsymutil specific fag.</p>


<p>(it might be called asynchronously).</p>


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>

</div>
</div>

### PrependPath {#a6b4d1969e9d1a09e808debff611e46ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::dwarf_linker::parallel::DWARFLinkerOptions::PrependPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prepend path for the clang modules.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>

</div>
</div>

### Statistics {#ada6d21af43986bd389dd2b165454cb5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::DWARFLinkerOptions::Statistics = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print statistics.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>

</div>
</div>

### TargetDWARFVersion {#a44548ea51a7a3a4ba06a921d43b874be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::dwarf_linker::parallel::DWARFLinkerOptions::TargetDWARFVersion = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DWARF version for the output.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>

</div>
</div>

### Threads {#ae68d3cab00cbc12c2f7af38c6d74a674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dwarf_linker::parallel::DWARFLinkerOptions::Threads = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of threads.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>

</div>
</div>

### UpdateIndexTablesOnly {#ad0fde97dc4343f593eb4a01436cd05b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::DWARFLinkerOptions::UpdateIndexTablesOnly = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update index tables.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>

</div>
</div>

### Verbose {#a2b508ddf784702f18079fa995522858b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::DWARFLinkerOptions::Verbose = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate processing log to the standard output.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>

</div>
</div>

### VerifyInputDWARF {#a7af2635dbf7eabcfb1fea5e933065e1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::DWARFLinkerOptions::VerifyInputDWARF = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the input DWARF.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
