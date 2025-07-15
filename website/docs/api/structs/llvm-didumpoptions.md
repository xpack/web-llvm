---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/didumpoptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DIDumpOptions` Struct Reference

<p>Container for dump options that control which debug information will be dumped. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::DIDumpOptions { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">llvm/DebugInfo/DIContext.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace64c2107df2ab7fcbf17e0b6017d9dc">noImplicitRecursion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the options with RecurseDepth set to 0 unless explicitly required. <a href="#ace64c2107df2ab7fcbf17e0b6017d9dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7313b0f4c1c5a3307d0947dcbee1777d">DumpType</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#ad61266803a6a149f93740d19b87c0874a0616c268f4b30224000b0e828c45f90f">DIDT_All</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae396b319b15cbecf51ec8dc4ee2719b0">ChildRecurseDepth</a> = -1U</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af55e071b0b0ed1579cc2cf244d7aa92e">ParentRecurseDepth</a> = -1U</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae18a4b1f6943d7355d5f4e504ab1c7a">Version</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af10fbda1b5dff02bb82edba5f45db9b1">AddrSize</a> = 4</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a828913b4a1930e52edc8f9d696d0e560">ShowAddresses</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63c9abd316790e49de7546ac58b9e37b">ShowChildren</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af55119555e8e6db24b4441fdef5ead40">ShowParents</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a0ae33bfdfe31cd538d48aea20ac452">ShowForm</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e2b48707bbce67c70aea64d3b1d1634">SummarizeTypes</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add6a33649e764a95f041d7b8358a019e">Verbose</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af989f60200414119fe05ca13a394ca61">DisplayRawContents</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2673e3b3e2b201c2afe1fdcf192d2df8">IsEH</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98519e1abf24139b0964cc8a33e7993a">DumpNonSkeleton</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ae290f4a1ec55b45fc60c63ca1a9650">ShowAggregateErrors</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95cec23fa81ab2696b64ad2d188ed507">JsonErrSummaryFile</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a>(uint64_t DwarfRegNum, bool <a href="#a2673e3b3e2b201c2afe1fdcf192d2df8">IsEH</a>)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcc02a97a7033bc1db45cd841ed4fc4e">GetNameForDWARFReg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37d04f96a64f8d44fb59b8ca1ab8935b">RecoverableErrorHandler</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14000245b9f0a590dec228e5f073d44f">WarningHandler</a> = <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a0ab9ce7767ba8ad9a3cb17cd35d81a1f">WithColor::defaultWarningHandler</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39edcd45ac2f03df8e7c2b8f32a1d19b">getForSingleDIE</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return default option set for printing a single <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> without children. <a href="#a39edcd45ac2f03df8e7c2b8f32a1d19b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Container for dump options that control which debug information will be dumped.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### noImplicitRecursion() {#ace64c2107df2ab7fcbf17e0b6017d9dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDumpOptions llvm::DIDumpOptions::noImplicitRecursion ()</td>
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

<p>Return the options with RecurseDepth set to 0 unless explicitly required.</p>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>References <a href="#ae396b319b15cbecf51ec8dc4ee2719b0">ChildRecurseDepth</a>, <a href="#af55e071b0b0ed1579cc2cf244d7aa92e">ParentRecurseDepth</a>, <a href="#a63c9abd316790e49de7546ac58b9e37b">ShowChildren</a> and <a href="#af55119555e8e6db24b4441fdef5ead40">ShowParents</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a872194924baf250829ba1b42a0b14105">llvm::DWARFContext::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a901080a7f2755abf0fc90c2d0d9da87f">llvm::dwarf_linker::parallel::DWARFLinkerImpl::verifyInput</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AddrSize {#af10fbda1b5dff02bb82edba5f45db9b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DIDumpOptions::AddrSize = 4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>

</div>
</div>

### ChildRecurseDepth {#ae396b319b15cbecf51ec8dc4ee2719b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DIDumpOptions::ChildRecurseDepth = -1U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#aff52b4e2a5b1e91ab933fbd3ad52bba0">llvm::DWARFDie::dump</a>, <a href="#a39edcd45ac2f03df8e7c2b8f32a1d19b">getForSingleDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#abab9675572d9fe6ef8cf9674b1bab8f7">llvm::dwarf_linker::parallel::DependencyTracker::isLiveSubprogramEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#ac9a57660f0db8e2b356c3ebccd34b063">llvm::dwarf_linker::parallel::DependencyTracker::isLiveVariableEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker/#af6caebcd7dc40dea28562fde4f260414">llvm::dwarf_linker::classic::DWARFLinker::link</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a42302ab883ef8ec7e51b00701d626ce4">llvm::dwarf_linker::parallel::DWARFLinkerImpl::link</a> and <a href="#ace64c2107df2ab7fcbf17e0b6017d9dc">noImplicitRecursion</a>.</p>

</div>
</div>

### DisplayRawContents {#af989f60200414119fe05ca13a394ca61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIDumpOptions::DisplayRawContents = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarfaddressrange/#af81b0ebe03203f548bf8244b75c5a65a">llvm::DWARFAddressRange::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a872194924baf250829ba1b42a0b14105">llvm::DWARFContext::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/rangelistentry/#a9490d0b5d168b24193e600de304103e1">llvm::RangeListEntry::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarflocationtable/#aec9a11e9a2e87414bb67f6aaa342a570">llvm::DWARFLocationTable::dumpLocationList</a>.</p>

</div>
</div>

### DumpNonSkeleton {#a98519e1abf24139b0964cc8a33e7993a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIDumpOptions::DumpNonSkeleton = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad09cae3468f14c61f3ca7af906462dab">llvm::DWARFCompileUnit::dump</a>.</p>

</div>
</div>

### DumpType {#a7313b0f4c1c5a3307d0947dcbee1777d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DIDumpOptions::DumpType = <a href="/web-llvm/docs/api/namespaces/llvm/#ad61266803a6a149f93740d19b87c0874a0616c268f4b30224000b0e828c45f90f">DIDT_All</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a872194924baf250829ba1b42a0b14105">llvm::DWARFContext::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a7ef02a65817764b3fd99c6ee3bb349f4">llvm::DWARFContext::verify</a>.</p>

</div>
</div>

### GetNameForDWARFReg {#abcc02a97a7033bc1db45cd841ed4fc4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;llvm::StringRef(uint64_t DwarfRegNum, bool IsEH)&gt; llvm::DIDumpOptions::GetNameForDWARFReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#a6e3d7579887f71bf2b4cf7def5a3d77b">llvm::logicalview::LVDWARFReader::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aeb9094ce3f495cf3f81c2c7aa6a975f5">llvm::DWARFExpression::prettyPrintRegisterOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp/#a5658f96977b9cb1730425f3ca3cb305c">printRegister</a>.</p>

</div>
</div>

### IsEH {#a2673e3b3e2b201c2afe1fdcf192d2df8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIDumpOptions::IsEH = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf/cie/#ad37449ab3df9cdf881d320defb0a9c20">llvm::dwarf::CIE::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde/#aac5d33bcc6ae2563f3756bd749c2e0d7">llvm::dwarf::FDE::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugframe/#a1e8de60bde8ef9a3008c06086049cc83">llvm::DWARFDebugFrame::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aeb9094ce3f495cf3f81c2c7aa6a975f5">llvm::DWARFExpression::prettyPrintRegisterOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acc23d591518160d5e67b43293906bc8a">llvm::DWARFExpression::print</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp/#a5658f96977b9cb1730425f3ca3cb305c">printRegister</a>.</p>

</div>
</div>

### JsonErrSummaryFile {#a95cec23fa81ab2696b64ad2d188ed507}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DIDumpOptions::JsonErrSummaryFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>

</div>
</div>

### ParentRecurseDepth {#af55e071b0b0ed1579cc2cf244d7aa92e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DIDumpOptions::ParentRecurseDepth = -1U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a50bceafadc9172f69d322e3f2eb1ad3f">dumpParentChain</a>, <a href="#a39edcd45ac2f03df8e7c2b8f32a1d19b">getForSingleDIE</a> and <a href="#ace64c2107df2ab7fcbf17e0b6017d9dc">noImplicitRecursion</a>.</p>

</div>
</div>

### RecoverableErrorHandler {#a37d04f96a64f8d44fb59b8ca1ab8935b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;void(Error)&gt; llvm::DIDumpOptions::RecoverableErrorHandler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      <a href="/web-llvm/docs/api/classes/llvm/withcolor/#aa125c88f5418a9e78bd9f1f20b774b08">WithColor::defaultErrorHandler</a>
</div>
</dd>
</dl>

<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf/cie/#ad37449ab3df9cdf881d320defb0a9c20">llvm::dwarf::CIE::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde/#aac5d33bcc6ae2563f3756bd749c2e0d7">llvm::dwarf::FDE::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a872194924baf250829ba1b42a0b14105">llvm::DWARFContext::dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#aad9651c88d362ae11ea69508451b3ae6">dumpAddrSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarflocationtable/#aec9a11e9a2e87414bb67f6aaa342a570">llvm::DWARFLocationTable::dumpLocationList</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a02e544cd4394600f3a6161460f9ec689">dumpLoclistsSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a76facea967f558412cc173c8224fdd9a">dumpPubTableSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a20d3f5071a5e2993982abaea21820301">dumpRnglistsSection</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#afb874a51b13c3cdfa8011bbf866c3658">dumpStringOffsetsSection</a>.</p>

</div>
</div>

### ShowAddresses {#a828913b4a1930e52edc8f9d696d0e560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIDumpOptions::ShowAddresses = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#aff52b4e2a5b1e91ab933fbd3ad52bba0">llvm::DWARFDie::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#abccb4aa356ed1bf8bae692df185a885a">llvm::DWARFFormValue::dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#ade69f55e99e7ef15fbbb7468ac74b557">dumpRanges</a>.</p>

</div>
</div>

### ShowAggregateErrors {#a9ae290f4a1ec55b45fc60c63ca1a9650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIDumpOptions::ShowAggregateErrors = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>

</div>
</div>

### ShowChildren {#a63c9abd316790e49de7546ac58b9e37b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIDumpOptions::ShowChildren = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#aff52b4e2a5b1e91ab933fbd3ad52bba0">llvm::DWARFDie::dump</a> and <a href="#ace64c2107df2ab7fcbf17e0b6017d9dc">noImplicitRecursion</a>.</p>

</div>
</div>

### ShowForm {#a3a0ae33bfdfe31cd538d48aea20ac452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIDumpOptions::ShowForm = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>.</p>

</div>
</div>

### ShowParents {#af55119555e8e6db24b4441fdef5ead40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIDumpOptions::ShowParents = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#aff52b4e2a5b1e91ab933fbd3ad52bba0">llvm::DWARFDie::dump</a> and <a href="#ace64c2107df2ab7fcbf17e0b6017d9dc">noImplicitRecursion</a>.</p>

</div>
</div>

### SummarizeTypes {#a9e2b48707bbce67c70aea64d3b1d1634}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIDumpOptions::SummarizeTypes = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad09cae3468f14c61f3ca7af906462dab">llvm::DWARFCompileUnit::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a9c2344d084d7463ac5940022292d5775">llvm::DWARFTypeUnit::dump</a>.</p>

</div>
</div>

### Verbose {#add6a33649e764a95f041d7b8358a019e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIDumpOptions::Verbose = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a872194924baf250829ba1b42a0b14105">llvm::DWARFContext::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugaddrtable/#a23d8a27d80ae2aa2502f2dec24d5a420">llvm::DWARFDebugAddrTable::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#aff52b4e2a5b1e91ab933fbd3ad52bba0">llvm::DWARFDie::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#abccb4aa356ed1bf8bae692df185a885a">llvm::DWARFFormValue::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarflisttablebase/#ae7bbad7169bd16810cafb23afee1d472">llvm::DWARFListTableBase&lt; DWARFListType &gt;::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarflisttableheader/#a5878d6c62b444d6d4dc49581e39091e1">llvm::DWARFListTableHeader::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/rangelistentry/#a9490d0b5d168b24193e600de304103e1">llvm::RangeListEntry::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a0bdd3a234a4ad4d695aea54ddb2b92bf">llvm::DWARFFormValue::dumpAddressSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfverifier/#aa555a8e9d0e824277bb9ed7f0b813639">llvm::DWARFVerifier::DWARFVerifier</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#abab9675572d9fe6ef8cf9674b1bab8f7">llvm::dwarf_linker::parallel::DependencyTracker::isLiveSubprogramEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#ac9a57660f0db8e2b356c3ebccd34b063">llvm::dwarf_linker::parallel::DependencyTracker::isLiveVariableEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker/#af6caebcd7dc40dea28562fde4f260414">llvm::dwarf_linker::classic::DWARFLinker::link</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a42302ab883ef8ec7e51b00701d626ce4">llvm::dwarf_linker::parallel::DWARFLinkerImpl::link</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5a44455c55b4b88c16930cd31cf4d20b">llvm::prettyPrintBaseTypeRef</a>.</p>

</div>
</div>

### Version {#aae18a4b1f6943d7355d5f4e504ab1c7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::DIDumpOptions::Version = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>

</div>
</div>

### WarningHandler {#a14000245b9f0a590dec228e5f073d44f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;void(Error)&gt; llvm::DIDumpOptions::WarningHandler = <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a0ab9ce7767ba8ad9a3cb17cd35d81a1f">WithColor::defaultWarningHandler</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a872194924baf250829ba1b42a0b14105">llvm::DWARFContext::dump</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#aad9651c88d362ae11ea69508451b3ae6">dumpAddrSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getForSingleDIE() {#a39edcd45ac2f03df8e7c2b8f32a1d19b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDumpOptions llvm::DIDumpOptions::getForSingleDIE ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return default option set for printing a single <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> without children.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>References <a href="#ae396b319b15cbecf51ec8dc4ee2719b0">ChildRecurseDepth</a> and <a href="#af55e071b0b0ed1579cc2cf244d7aa92e">ParentRecurseDepth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
