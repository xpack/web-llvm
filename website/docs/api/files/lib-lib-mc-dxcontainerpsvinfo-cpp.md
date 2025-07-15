---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/mc/dxcontainerpsvinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DXContainerPSVInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">llvm/MC/DXContainerPSVInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">llvm/BinaryFormat/DXContainer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">llvm/MC/StringTableBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">llvm/Support/EndianStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2cb91b4a276a9864c39790b06f72678">FindSequence</a> (ArrayRef&lt; uint32_t &gt; Buffer, ArrayRef&lt; uint32_t &gt; Sequence)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6c7bb71f11814fe88bf73f5c589a9e0">ProcessElementList</a> (StringTableBuilder &amp;StrTabBuilder, SmallVectorImpl&lt; uint32_t &gt; &amp;IndexBuffer, SmallVectorImpl&lt; v0::SignatureElement &gt; &amp;FinalElements, SmallVectorImpl&lt; StringRef &gt; &amp;SemanticNames, ArrayRef&lt; PSVSignatureElement &gt; Elements)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a454ce2c1ee39625b7053a5cef9a6da6e">npos</a> = StringRef::npos</td>
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


<div class="doxySectionDef">

## Functions

### FindSequence() {#af2cb91b4a276a9864c39790b06f72678}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t FindSequence (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt; Buffer, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt; Sequence)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/dxcontainerpsvinfo-cpp">DXContainerPSVInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp/#affd23ab4a2fbb796128b383986b7286f">memcmp</a>, <a href="#a454ce2c1ee39625b7053a5cef9a6da6e">npos</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#ad6c7bb71f11814fe88bf73f5c589a9e0">ProcessElementList</a>.</p>

</div>
</div>

### ProcessElementList() {#ad6c7bb71f11814fe88bf73f5c589a9e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ProcessElementList (<a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a> &amp; StrTabBuilder, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint32_t &gt; &amp; IndexBuffer, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v0/signatureelement">v0::SignatureElement</a> &gt; &amp; FinalElements, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; SemanticNames, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mcdxbc/psvsignatureelement">PSVSignatureElement</a> &gt; Elements)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/dxcontainerpsvinfo-cpp">DXContainerPSVInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#ae6ba484ec18769c20a3c576c02f0b2a7">llvm::StringTableBuilder::add</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v0/signatureelement/#ad5cac55510cc81d2fa397eb409fb612d">llvm::dxbc::PSV::v0::SignatureElement::Allocated</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v0/signatureelement/#aed0fdadf3a8b0031d7adde43d23999d2">llvm::dxbc::PSV::v0::SignatureElement::Cols</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v0/signatureelement/#a7e937261ce680c88998610451ea7526a">llvm::dxbc::PSV::v0::SignatureElement::DynamicMask</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#af2cb91b4a276a9864c39790b06f72678">FindSequence</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v0/signatureelement/#a902112dca130ef99aaff5c9991646300">llvm::dxbc::PSV::v0::SignatureElement::IndicesOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a94d23373106467003722f7d6c17b1528">llvm::SmallVectorImpl&lt; T &gt;::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v0/signatureelement/#a1ae0d1bc81a066d3d3fbe24ab7bdb61b">llvm::dxbc::PSV::v0::SignatureElement::Kind</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v0/signatureelement/#a80c0612357de65a68cfc26f77a70a968">llvm::dxbc::PSV::v0::SignatureElement::Mode</a>, <a href="#a454ce2c1ee39625b7053a5cef9a6da6e">npos</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v0/signatureelement/#a8bbc59b596b2ca812c2aedbabfdef840">llvm::dxbc::PSV::v0::SignatureElement::Rows</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v0/signatureelement/#affd715a9865731fc4f86f8ad8debccd8">llvm::dxbc::PSV::v0::SignatureElement::StartCol</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v0/signatureelement/#aecca65a0ee2fef7ae6137b9cb4107d8e">llvm::dxbc::PSV::v0::SignatureElement::StartRow</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v0/signatureelement/#ab2d84d73d59d634207bc228f5fbc53cd">llvm::dxbc::PSV::v0::SignatureElement::Stream</a> and <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v0/signatureelement/#a89ea993b39896cdc43708fac35b5e11b">llvm::dxbc::PSV::v0::SignatureElement::Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcdxbc/psvruntimeinfo/#a3afcf265b28cf1aae8dab4af4c89201c">llvm::mcdxbc::PSVRuntimeInfo::finalize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### npos {#a454ce2c1ee39625b7053a5cef9a6da6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t npos = StringRef::npos</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/dxcontainerpsvinfo-cpp">DXContainerPSVInfo.cpp</a>.</p>


<p>Referenced by <a href="#af2cb91b4a276a9864c39790b06f72678">FindSequence</a> and <a href="#ad6c7bb71f11814fe88bf73f5c589a9e0">ProcessElementList</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
