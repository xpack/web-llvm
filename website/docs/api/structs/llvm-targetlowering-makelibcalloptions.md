---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/targetlowering/makelibcalloptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MakeLibCallOptions` Struct Reference

<p>This structure is used to pass arguments to makeLibCall function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::TargetLowering::MakeLibCallOptions { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff3cc82d02c80fafcd898a122601ade2">MakeLibCallOptions</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/makelibcalloptions">MakeLibCallOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a610098a9bceabef8349fa1c9c936b305">setIsSigned</a> (bool Value=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/makelibcalloptions">MakeLibCallOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa17c05ed01d1eb0892c731000bf1cdcf">setNoReturn</a> (bool Value=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/makelibcalloptions">MakeLibCallOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30d29fa3a2769f2ef75455683d7af795">setDiscardResult</a> (bool Value=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/makelibcalloptions">MakeLibCallOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18dc59bf0c115284fa1dc5449c6ad2b0">setIsPostTypeLegalization</a> (bool Value=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/makelibcalloptions">MakeLibCallOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82aba70f7fd14f1d0c6d83caa1e5061e">setTypeListBeforeSoften</a> (ArrayRef&lt; EVT &gt; OpsVT, EVT RetVT, bool Value=true)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a364ab3316f12c7e616321c99042976d4">OpsVTBeforeSoften</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eef0efd7cc80c2bda832ce6efbbe773">RetVTBeforeSoften</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34d0fd5ae047db9c073452c64b66db44">IsSigned</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aced439f1cb92715496bc80dd4d2336">DoesNotReturn</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63fca221e2dec9fcba757a30ff8f37a2">IsReturnValueUsed</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a445e4efb3b76e845742b7179c9e1f219">IsPostTypeLegalization</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87460ac8a2a87af4f31aff4205f06d3d">IsSoften</a></td>
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

<p>This structure is used to pass arguments to makeLibCall function.</p>

<p>Definition at line 4714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MakeLibCallOptions() {#aff3cc82d02c80fafcd898a122601ade2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetLowering::MakeLibCallOptions::MakeLibCallOptions ()</td>
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



<p>Definition at line 4725 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#a6aced439f1cb92715496bc80dd4d2336">DoesNotReturn</a>, <a href="#a445e4efb3b76e845742b7179c9e1f219">IsPostTypeLegalization</a>, <a href="#a63fca221e2dec9fcba757a30ff8f37a2">IsReturnValueUsed</a>, <a href="#a34d0fd5ae047db9c073452c64b66db44">IsSigned</a>, <a href="#a87460ac8a2a87af4f31aff4205f06d3d">IsSoften</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="#a30d29fa3a2769f2ef75455683d7af795">setDiscardResult</a>, <a href="#a18dc59bf0c115284fa1dc5449c6ad2b0">setIsPostTypeLegalization</a>, <a href="#a610098a9bceabef8349fa1c9c936b305">setIsSigned</a>, <a href="#aa17c05ed01d1eb0892c731000bf1cdcf">setNoReturn</a> and <a href="#a82aba70f7fd14f1d0c6d83caa1e5061e">setTypeListBeforeSoften</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### setDiscardResult() {#a30d29fa3a2769f2ef75455683d7af795}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MakeLibCallOptions &amp; llvm::TargetLowering::MakeLibCallOptions::setDiscardResult (bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 4739 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#a63fca221e2dec9fcba757a30ff8f37a2">IsReturnValueUsed</a> and <a href="#aff3cc82d02c80fafcd898a122601ade2">MakeLibCallOptions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afff13ac7b2e92fc0ad596603592298bd">llvm::SelectionDAGBuilder::visitSPDescriptorFailure</a>.</p>

</div>
</div>

### setIsPostTypeLegalization() {#a18dc59bf0c115284fa1dc5449c6ad2b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MakeLibCallOptions &amp; llvm::TargetLowering::MakeLibCallOptions::setIsPostTypeLegalization (bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 4744 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#a445e4efb3b76e845742b7179c9e1f219">IsPostTypeLegalization</a> and <a href="#aff3cc82d02c80fafcd898a122601ade2">MakeLibCallOptions</a>.</p>

</div>
</div>

### setIsSigned() {#a610098a9bceabef8349fa1c9c936b305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MakeLibCallOptions &amp; llvm::TargetLowering::MakeLibCallOptions::setIsSigned (bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 4729 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#a34d0fd5ae047db9c073452c64b66db44">IsSigned</a> and <a href="#aff3cc82d02c80fafcd898a122601ade2">MakeLibCallOptions</a>.</p>

</div>
</div>

### setNoReturn() {#aa17c05ed01d1eb0892c731000bf1cdcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MakeLibCallOptions &amp; llvm::TargetLowering::MakeLibCallOptions::setNoReturn (bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 4734 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#a6aced439f1cb92715496bc80dd4d2336">DoesNotReturn</a> and <a href="#aff3cc82d02c80fafcd898a122601ade2">MakeLibCallOptions</a>.</p>

</div>
</div>

### setTypeListBeforeSoften() {#a82aba70f7fd14f1d0c6d83caa1e5061e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MakeLibCallOptions &amp; llvm::TargetLowering::MakeLibCallOptions::setTypeListBeforeSoften (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> &gt; OpsVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> RetVT, bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 4749 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#a87460ac8a2a87af4f31aff4205f06d3d">IsSoften</a>, <a href="#aff3cc82d02c80fafcd898a122601ade2">MakeLibCallOptions</a>, <a href="#a364ab3316f12c7e616321c99042976d4">OpsVTBeforeSoften</a> and <a href="#a9eef0efd7cc80c2bda832ce6efbbe773">RetVTBeforeSoften</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ac83ceb8e67e1ee6ca693e3ff1ffbac0f">llvm::LoongArchTargetLowering::ReplaceNodeResults</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DoesNotReturn {#a6aced439f1cb92715496bc80dd4d2336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::MakeLibCallOptions::DoesNotReturn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#aff3cc82d02c80fafcd898a122601ade2">MakeLibCallOptions</a> and <a href="#aa17c05ed01d1eb0892c731000bf1cdcf">setNoReturn</a>.</p>

</div>
</div>

### IsPostTypeLegalization {#a445e4efb3b76e845742b7179c9e1f219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::MakeLibCallOptions::IsPostTypeLegalization</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4722 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#aff3cc82d02c80fafcd898a122601ade2">MakeLibCallOptions</a> and <a href="#a18dc59bf0c115284fa1dc5449c6ad2b0">setIsPostTypeLegalization</a>.</p>

</div>
</div>

### IsReturnValueUsed {#a63fca221e2dec9fcba757a30ff8f37a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::MakeLibCallOptions::IsReturnValueUsed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#aff3cc82d02c80fafcd898a122601ade2">MakeLibCallOptions</a> and <a href="#a30d29fa3a2769f2ef75455683d7af795">setDiscardResult</a>.</p>

</div>
</div>

### IsSigned {#a34d0fd5ae047db9c073452c64b66db44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::MakeLibCallOptions::IsSigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#aff3cc82d02c80fafcd898a122601ade2">MakeLibCallOptions</a> and <a href="#a610098a9bceabef8349fa1c9c936b305">setIsSigned</a>.</p>

</div>
</div>

### IsSoften {#a87460ac8a2a87af4f31aff4205f06d3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::MakeLibCallOptions::IsSoften</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#aff3cc82d02c80fafcd898a122601ade2">MakeLibCallOptions</a> and <a href="#a82aba70f7fd14f1d0c6d83caa1e5061e">setTypeListBeforeSoften</a>.</p>

</div>
</div>

### OpsVTBeforeSoften {#a364ab3316f12c7e616321c99042976d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;EVT&gt; llvm::TargetLowering::MakeLibCallOptions::OpsVTBeforeSoften</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4717 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#a82aba70f7fd14f1d0c6d83caa1e5061e">setTypeListBeforeSoften</a>.</p>

</div>
</div>

### RetVTBeforeSoften {#a9eef0efd7cc80c2bda832ce6efbbe773}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::TargetLowering::MakeLibCallOptions::RetVTBeforeSoften</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#a82aba70f7fd14f1d0c6d83caa1e5061e">setTypeListBeforeSoften</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
