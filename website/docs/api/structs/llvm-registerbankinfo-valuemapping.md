---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/registerbankinfo/valuemapping
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ValueMapping` Struct

<p>Helper struct that represents how a value is mapped through different register banks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::RegisterBankInfo::ValueMapping { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">llvm/CodeGen/RegisterBankInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d25c6b19f2506311abd2ea798250afb">ValueMapping</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The default constructor creates an invalid (<a href="#a788a7905d6f6e954dc6984334bc88d5f">isValid()</a> == false) instance. <a href="#a9d25c6b19f2506311abd2ea798250afb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06976c9ea836c86aa3d237c920609c10">ValueMapping</a> (const PartialMapping *BreakDown, unsigned NumBreakDowns)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize a <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> with the given parameter. <a href="#a06976c9ea836c86aa3d237c920609c10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping">PartialMapping</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0816d52870d885008781168854322987">begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterators through the PartialMappings. <a href="#a0816d52870d885008781168854322987">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping">PartialMapping</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a177c87d358c97d054f1b2016dc95c64b">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f71f2f9b3cb7e0602fcd19e648bdfc">partsAllUniform</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a788a7905d6f6e954dc6984334bc88d5f">isValid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> is valid. <a href="#a788a7905d6f6e954dc6984334bc88d5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6778093ec4b236fadf3c13e2fe1e2ee9">verify</a> (const RegisterBankInfo &amp;RBI, TypeSize MeaningfulBitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that this mapping makes sense for a value of <span class="doxyComputerOutput">MeaningfulBitWidth</span>. <a href="#a6778093ec4b236fadf3c13e2fe1e2ee9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa08a6a3c21b4acf3c92768f1d66d7330">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print this on <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> stream. <a href="#aa08a6a3c21b4acf3c92768f1d66d7330">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33776bd541683ce5ed03b9792d2259f1">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print this on <span class="doxyComputerOutput">OS</span>;. <a href="#a33776bd541683ce5ed03b9792d2259f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping">PartialMapping</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3003e8b89a759af674cb22ed2b67d2e">BreakDown</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>How the value is broken down between the different register banks. <a href="#ae3003e8b89a759af674cb22ed2b67d2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83b9746150eb1c8820d65bca34b8d950">NumBreakDowns</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of partial mapping to break down this value. <a href="#a83b9746150eb1c8820d65bca34b8d950">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper struct that represents how a value is mapped through different register banks.</p>



:::info
<p>: So far we do not have any users of the complex mappings (mappings with more than one partial mapping), but when we do, we would have needed to duplicate partial mappings. The alternative could be to use an array of pointers of partial mapping (i.e., <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping">PartialMapping</a> **BreakDown) and duplicate the pointers instead.</p>
:::


<p>E.g., Let say we have a 32-bit add and a &lt;2 x 32-bit&gt; vadd. We can expand the &lt;2 x 32-bit&gt; add into 2 x 32-bit add.</p>


<p>Currently the TableGen-like file would look like:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   PartialMapping[] = {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightComment">/*32-bit add*/</span><span class="doxyHighlight">      {0, 32, GPR}, </span><span class="doxyHighlightComment">// Scalar entry repeated for first</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightComment">// vec elt.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightComment">/*2x32-bit add*&amp;zwj;/    {0, 32, GPR}, {32, 32, GPR},</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  /*&lt;2x32-bit&gt; vadd*&amp;zwj;/ {0, 64, VPR}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  }; // PartialMapping duplicated.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">* </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  ValueMapping[] {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*    /*plain 32-bit add*&amp;zwj;/       {&amp;PartialMapping[0], 1},</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*    /*expanded vadd on 2xadd*&amp;zwj;/ {&amp;PartialMapping[1], 2},</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*    /*plain &lt;2x32-bit&gt; vadd*&amp;zwj;/  {&amp;PartialMapping[3], 1}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  </span></span></div>

</div>


<p>With the array of pointer, we would have:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   PartialMapping[] = {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightComment">/*32-bit add lower */</span><span class="doxyHighlight"> { 0, 32, GPR},</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightComment">/*32-bit add upper *&amp;zwj;/ {32, 32, GPR},</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  /*&lt;2x32-bit&gt; vadd *&amp;zwj;/  { 0, 64, VPR}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  }; // No more duplication.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">* </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  BreakDowns[] = {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  /*AddBreakDown*&amp;zwj;/   &amp;PartialMapping[0],</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  /*2xAddBreakDown*&amp;zwj;/ &amp;PartialMapping[0], &amp;PartialMapping[1],</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  /*VAddBreakDown*&amp;zwj;/  &amp;PartialMapping[2]</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  }; // Addresses of PartialMapping duplicated (smaller).</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">* </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  ValueMapping[] {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*    /*plain 32-bit add*&amp;zwj;/       {&amp;BreakDowns[0], 1},</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*    /*expanded vadd on 2xadd*&amp;zwj;/ {&amp;BreakDowns[1], 2},</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*    /*plain &lt;2x32-bit&gt; vadd*&amp;zwj;/  {&amp;BreakDowns[3], 1}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  </span></span></div>

</div>


<p>Given that a <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping">PartialMapping</a> is actually small, the code size impact is actually a degradation. Moreover the compile time will be hit by the additional indirection. If <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping">PartialMapping</a> gets bigger we may reconsider.</p>


<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ValueMapping() {#a9d25c6b19f2506311abd2ea798250afb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegisterBankInfo::ValueMapping::ValueMapping ()</td>
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

<p>The default constructor creates an invalid (<a href="#a788a7905d6f6e954dc6984334bc88d5f">isValid()</a> == false) instance.</p>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>Reference <a href="#a9d25c6b19f2506311abd2ea798250afb">ValueMapping</a>.</p>


<p>Referenced by <a href="#a9d25c6b19f2506311abd2ea798250afb">ValueMapping</a>.</p>

</div>
</div>

### ValueMapping() {#a06976c9ea836c86aa3d237c920609c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegisterBankInfo::ValueMapping::ValueMapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping">PartialMapping</a> * BreakDown, unsigned NumBreakDowns)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize a <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> with the given parameter.</p>


<p><span class="doxyComputerOutput">BreakDown</span> needs to have a life time at least as long as this instance.</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>References <a href="#ae3003e8b89a759af674cb22ed2b67d2e">BreakDown</a> and <a href="#a83b9746150eb1c8820d65bca34b8d950">NumBreakDowns</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a0816d52870d885008781168854322987}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PartialMapping * llvm::RegisterBankInfo::ValueMapping::begin ()</td>
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

<p>Iterators through the PartialMappings.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>Reference <a href="#ae3003e8b89a759af674cb22ed2b67d2e">BreakDown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a6817453b853abea76fab37803ade6ef4">llvm::RegisterBankInfo::OperandsMapper::createVRegs</a> and <a href="#a73f71f2f9b3cb7e0602fcd19e648bdfc">partsAllUniform</a>.</p>

</div>
</div>

### dump() {#aa08a6a3c21b4acf3c92768f1d66d7330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void RegisterBankInfo::ValueMapping::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print this on <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> stream.</p>

<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a>.</p>

</div>
</div>

### end() {#a177c87d358c97d054f1b2016dc95c64b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PartialMapping * llvm::RegisterBankInfo::ValueMapping::end ()</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>References <a href="#ae3003e8b89a759af674cb22ed2b67d2e">BreakDown</a> and <a href="#a83b9746150eb1c8820d65bca34b8d950">NumBreakDowns</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a6817453b853abea76fab37803ade6ef4">llvm::RegisterBankInfo::OperandsMapper::createVRegs</a> and <a href="#a73f71f2f9b3cb7e0602fcd19e648bdfc">partsAllUniform</a>.</p>

</div>
</div>

### isValid() {#a788a7905d6f6e954dc6984334bc88d5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegisterBankInfo::ValueMapping::isValid ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> is valid.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>References <a href="#ae3003e8b89a759af674cb22ed2b67d2e">BreakDown</a> and <a href="#a83b9746150eb1c8820d65bca34b8d950">NumBreakDowns</a>.</p>

</div>
</div>

### partsAllUniform() {#a73f71f2f9b3cb7e0602fcd19e648bdfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterBankInfo::ValueMapping::partsAllUniform ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if all partial mappings are the same size and register bank.</p></dd>
</dl>


<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>


<p>References <a href="#a0816d52870d885008781168854322987">begin</a>, <a href="#a177c87d358c97d054f1b2016dc95c64b">end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a> and <a href="#a83b9746150eb1c8820d65bca34b8d950">NumBreakDowns</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac8d8bb4999d968e0efc9555c2b178a83">llvm::RegBankSelect::repairReg</a>.</p>

</div>
</div>

### print() {#a33776bd541683ce5ed03b9792d2259f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterBankInfo::ValueMapping::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print this on <span class="doxyComputerOutput">OS</span>;.</p>

<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>


<p>Reference <a href="#a83b9746150eb1c8820d65bca34b8d950">NumBreakDowns</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5dc8291a0d3249b233ab895fa7051b74">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### verify() {#a6778093ec4b236fadf3c13e2fe1e2ee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterBankInfo::ValueMapping::verify (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> &amp; RBI, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> MeaningfulBitWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify that this mapping makes sense for a value of <span class="doxyComputerOutput">MeaningfulBitWidth</span>.</p>



:::info
<p>This method does not check anything when assertions are disabled.</p>
:::


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True is the check was successful.</p></dd>
</dl>


<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a46ceedee591f92727b85641794a96061">llvm::APInt::getBitsSet</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping/#a6de81ad6fdab369c1e85c901b7f2e8d4">llvm::RegisterBankInfo::PartialMapping::getHighBitIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a423e2c491de1408d54e35f0b47d076be">llvm::APInt::isAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="#a83b9746150eb1c8820d65bca34b8d950">NumBreakDowns</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#aa9467bf23c0dfb8176a54358477962fa">llvm::RegisterBankInfo::RegisterBankInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping/#a0c55804243f2f158a9afa64f0f764c35">llvm::RegisterBankInfo::PartialMapping::StartIdx</a> and <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping/#aaee9b30ca4238627080ab0cb45ac28e6">llvm::RegisterBankInfo::PartialMapping::verify</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#a89e479535d719fb4ec8904104ec1e8ae">llvm::RegisterBankInfo::InstructionMapping::verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BreakDown {#ae3003e8b89a759af674cb22ed2b67d2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PartialMapping* llvm::RegisterBankInfo::ValueMapping::BreakDown</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>How the value is broken down between the different register banks.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#afc5c7be6a4fbeb70b07dde19d8ebc2fd">llvm::RegBankSelect::applyMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a67457fbc2d167a5a1a18124bd446278f">llvm::AMDGPURegisterBankInfo::applyMappingBFE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#afb1a8a9ef7b460687963fb7968fb7626">llvm::AMDGPURegisterBankInfo::applyMappingSBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac00dc73d1e42ba9d0e4f906e8b4edfd8">llvm::RegBankSelect::assignmentMatch</a>, <a href="#a0816d52870d885008781168854322987">begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ab56fd9d622b75f8f20c16af886a1eaae">llvm::ARM::checkValueMapping</a>, <a href="#a177c87d358c97d054f1b2016dc95c64b">end</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#ac390939d904c03a62f806bac6ae2626c">llvm::AMDGPURegisterBankInfo::getBreakDownCost</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac3cfa17f907e7258d898433ddfeb3fbf">llvm::RegBankSelect::getRepairCost</a>, <a href="#a788a7905d6f6e954dc6984334bc88d5f">isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac8d8bb4999d968e0efc9555c2b178a83">llvm::RegBankSelect::repairReg</a> and <a href="#a06976c9ea836c86aa3d237c920609c10">ValueMapping</a>.</p>

</div>
</div>

### NumBreakDowns {#a83b9746150eb1c8820d65bca34b8d950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RegisterBankInfo::ValueMapping::NumBreakDowns</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of partial mapping to break down this value.</p>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#afc5c7be6a4fbeb70b07dde19d8ebc2fd">llvm::RegBankSelect::applyMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac00dc73d1e42ba9d0e4f906e8b4edfd8">llvm::RegBankSelect::assignmentMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ab56fd9d622b75f8f20c16af886a1eaae">llvm::ARM::checkValueMapping</a>, <a href="#a177c87d358c97d054f1b2016dc95c64b">end</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#ac390939d904c03a62f806bac6ae2626c">llvm::AMDGPURegisterBankInfo::getBreakDownCost</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac3cfa17f907e7258d898433ddfeb3fbf">llvm::RegBankSelect::getRepairCost</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#af23faa9ae580c4a451da006e3567b297">llvm::RegisterBankInfo::OperandsMapper::getVRegs</a>, <a href="#a788a7905d6f6e954dc6984334bc88d5f">isValid</a>, <a href="#a73f71f2f9b3cb7e0602fcd19e648bdfc">partsAllUniform</a>, <a href="#a33776bd541683ce5ed03b9792d2259f1">print</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac8d8bb4999d968e0efc9555c2b178a83">llvm::RegBankSelect::repairReg</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a781bc33cca080506ba19a20d66c1c255">llvm::RegBankSelect::tryAvoidingSplit</a>, <a href="#a06976c9ea836c86aa3d237c920609c10">ValueMapping</a> and <a href="#a6778093ec4b236fadf3c13e2fe1e2ee9">verify</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
