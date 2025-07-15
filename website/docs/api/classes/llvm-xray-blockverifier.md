---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/xray/blockverifier
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BlockVerifier` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::xray::BlockVerifier { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">llvm/XRay/BlockVerifier.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/xray/recordvisitor">RecordVisitor</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">State : std::size_t { <a href="#a59694dabdf15b05a6ed96e3d6395921a">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0363cbb2ea3574b210ed0511901ba550">visit</a> (BufferExtents &amp;) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5150f8980b37faa50e10714637643a7">visit</a> (WallclockRecord &amp;) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac927d14a65a4257ee852b29412c6326d">visit</a> (NewCPUIDRecord &amp;) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e93c0c6eca3d7b8d9ec4a3cfa7cc7b8">visit</a> (TSCWrapRecord &amp;) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc53f6d9482f5fe2fa57c938071ee172">visit</a> (CustomEventRecord &amp;) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2c0014e8932ea8c1552f2adf10535e4">visit</a> (CallArgRecord &amp;) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746d79144717a5289a72a8fd7377b34a">visit</a> (PIDRecord &amp;) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa65d33473539f0f4b04235581a7b0c7e">visit</a> (NewBufferRecord &amp;) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01202d1f61e22bd9ab1e6fd70938f07b">visit</a> (EndBufferRecord &amp;) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa2074d3d4345a4e170f94980299301c">visit</a> (FunctionRecord &amp;) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0466a89ecf2d430b651264e562f22057">visit</a> (CustomEventRecordV5 &amp;) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1d0957ab5ee78c3b17b8ede0ccca66c">visit</a> (TypedEventRecord &amp;) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a358157e2ac5a3e8e85ed759cec5e1798">verify</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af37ef7cf3fcd3b633b938865641a8925">reset</a> ()</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad32b26d167d98bd2c9d3e5881e0e093f">transition</a> (State To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a59694dabdf15b05a6ed96e3d6395921a">State</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d50ad09b365f7510886fd6db5736f12">CurrentRecord</a> = <a href="#a59694dabdf15b05a6ed96e3d6395921aa88183b946cc5f0e8c96b2e66e1c74a7e">State::Unknown</a></td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### State {#a59694dabdf15b05a6ed96e3d6395921a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::xray::BlockVerifier::State : std::size_t</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unknown<a id="a59694dabdf15b05a6ed96e3d6395921aa88183b946cc5f0e8c96b2e66e1c74a7e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BufferExtents<a id="a59694dabdf15b05a6ed96e3d6395921aad40f124c04e0f7053a59091324c057bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NewBuffer<a id="a59694dabdf15b05a6ed96e3d6395921aa9640a8ab0717de99a9cba910898a29e1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WallClockTime<a id="a59694dabdf15b05a6ed96e3d6395921aa0e35c3a890a74eac23be4290fbb514b9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PIDEntry<a id="a59694dabdf15b05a6ed96e3d6395921aabf3fd8939cdbbe2ffa4241c50b79aa2a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NewCPUId<a id="a59694dabdf15b05a6ed96e3d6395921aa4d5e3885bd7d52c169962c2f3fe53802"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TSCWrap<a id="a59694dabdf15b05a6ed96e3d6395921aa859cbd93cb41d14122da3077763072ce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CustomEvent<a id="a59694dabdf15b05a6ed96e3d6395921aac8b0247e97b3b6334312cddb4de4182e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TypedEvent<a id="a59694dabdf15b05a6ed96e3d6395921aa583dedceb162e94531b777a3b8902743"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Function<a id="a59694dabdf15b05a6ed96e3d6395921aa86408593c34af77fdd90df932f8b5261"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CallArg<a id="a59694dabdf15b05a6ed96e3d6395921aa2255a845dfaa556c825c2e5696cd9e78"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EndOfBuffer<a id="a59694dabdf15b05a6ed96e3d6395921aae5da385dbefcea25180d295762b0b38f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StateMax<a id="a59694dabdf15b05a6ed96e3d6395921aa98dc330541bd24c811d0a8c4646e6cc6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### reset() {#af37ef7cf3fcd3b633b938865641a8925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::xray::BlockVerifier::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/blockverifier-cpp">BlockVerifier.cpp</a>.</p>


<p>Reference <a href="#a59694dabdf15b05a6ed96e3d6395921aa88183b946cc5f0e8c96b2e66e1c74a7e">Unknown</a>.</p>

</div>
</div>

### verify() {#a358157e2ac5a3e8e85ed759cec5e1798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::xray::BlockVerifier::verify ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>, definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/blockverifier-cpp">BlockVerifier.cpp</a>.</p>


<p>References <a href="#a59694dabdf15b05a6ed96e3d6395921aa2255a845dfaa556c825c2e5696cd9e78">CallArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#a59694dabdf15b05a6ed96e3d6395921aac8b0247e97b3b6334312cddb4de4182e">CustomEvent</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="#a59694dabdf15b05a6ed96e3d6395921aae5da385dbefcea25180d295762b0b38f">EndOfBuffer</a>, <a href="#a59694dabdf15b05a6ed96e3d6395921aa86408593c34af77fdd90df932f8b5261">Function</a>, <a href="#a59694dabdf15b05a6ed96e3d6395921aa4d5e3885bd7d52c169962c2f3fe53802">NewCPUId</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#a59694dabdf15b05a6ed96e3d6395921aa859cbd93cb41d14122da3077763072ce">TSCWrap</a> and <a href="#a59694dabdf15b05a6ed96e3d6395921aa583dedceb162e94531b777a3b8902743">TypedEvent</a>.</p>

</div>
</div>

### visit() {#a0363cbb2ea3574b210ed0511901ba550}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::xray::BlockVerifier::visit (<a href="/web-llvm/docs/api/classes/llvm/xray/bufferextents">BufferExtents</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/blockverifier-cpp">BlockVerifier.cpp</a>.</p>


<p>Reference <a href="#a59694dabdf15b05a6ed96e3d6395921aad40f124c04e0f7053a59091324c057bb">BufferExtents</a>.</p>

</div>
</div>

### visit() {#ac5150f8980b37faa50e10714637643a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::xray::BlockVerifier::visit (<a href="/web-llvm/docs/api/classes/llvm/xray/wallclockrecord">WallclockRecord</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/blockverifier-cpp">BlockVerifier.cpp</a>.</p>


<p>Reference <a href="#a59694dabdf15b05a6ed96e3d6395921aa0e35c3a890a74eac23be4290fbb514b9">WallClockTime</a>.</p>

</div>
</div>

### visit() {#ac927d14a65a4257ee852b29412c6326d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::xray::BlockVerifier::visit (<a href="/web-llvm/docs/api/classes/llvm/xray/newcpuidrecord">NewCPUIDRecord</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/blockverifier-cpp">BlockVerifier.cpp</a>.</p>


<p>Reference <a href="#a59694dabdf15b05a6ed96e3d6395921aa4d5e3885bd7d52c169962c2f3fe53802">NewCPUId</a>.</p>

</div>
</div>

### visit() {#a2e93c0c6eca3d7b8d9ec4a3cfa7cc7b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::xray::BlockVerifier::visit (<a href="/web-llvm/docs/api/classes/llvm/xray/tscwraprecord">TSCWrapRecord</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>, definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/blockverifier-cpp">BlockVerifier.cpp</a>.</p>


<p>Reference <a href="#a59694dabdf15b05a6ed96e3d6395921aa859cbd93cb41d14122da3077763072ce">TSCWrap</a>.</p>

</div>
</div>

### visit() {#acc53f6d9482f5fe2fa57c938071ee172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::xray::BlockVerifier::visit (<a href="/web-llvm/docs/api/classes/llvm/xray/customeventrecord">CustomEventRecord</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/blockverifier-cpp">BlockVerifier.cpp</a>.</p>


<p>Reference <a href="#a59694dabdf15b05a6ed96e3d6395921aac8b0247e97b3b6334312cddb4de4182e">CustomEvent</a>.</p>

</div>
</div>

### visit() {#ab2c0014e8932ea8c1552f2adf10535e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::xray::BlockVerifier::visit (<a href="/web-llvm/docs/api/classes/llvm/xray/callargrecord">CallArgRecord</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>, definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/blockverifier-cpp">BlockVerifier.cpp</a>.</p>


<p>Reference <a href="#a59694dabdf15b05a6ed96e3d6395921aa2255a845dfaa556c825c2e5696cd9e78">CallArg</a>.</p>

</div>
</div>

### visit() {#a746d79144717a5289a72a8fd7377b34a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::xray::BlockVerifier::visit (<a href="/web-llvm/docs/api/classes/llvm/xray/pidrecord">PIDRecord</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/blockverifier-cpp">BlockVerifier.cpp</a>.</p>


<p>Reference <a href="#a59694dabdf15b05a6ed96e3d6395921aabf3fd8939cdbbe2ffa4241c50b79aa2a">PIDEntry</a>.</p>

</div>
</div>

### visit() {#aa65d33473539f0f4b04235581a7b0c7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::xray::BlockVerifier::visit (<a href="/web-llvm/docs/api/classes/llvm/xray/newbufferrecord">NewBufferRecord</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/blockverifier-cpp">BlockVerifier.cpp</a>.</p>


<p>Reference <a href="#a59694dabdf15b05a6ed96e3d6395921aa9640a8ab0717de99a9cba910898a29e1">NewBuffer</a>.</p>

</div>
</div>

### visit() {#a01202d1f61e22bd9ab1e6fd70938f07b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::xray::BlockVerifier::visit (<a href="/web-llvm/docs/api/classes/llvm/xray/endbufferrecord">EndBufferRecord</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/blockverifier-cpp">BlockVerifier.cpp</a>.</p>


<p>Reference <a href="#a59694dabdf15b05a6ed96e3d6395921aae5da385dbefcea25180d295762b0b38f">EndOfBuffer</a>.</p>

</div>
</div>

### visit() {#afa2074d3d4345a4e170f94980299301c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::xray::BlockVerifier::visit (<a href="/web-llvm/docs/api/classes/llvm/xray/functionrecord">FunctionRecord</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>, definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/blockverifier-cpp">BlockVerifier.cpp</a>.</p>


<p>Reference <a href="#a59694dabdf15b05a6ed96e3d6395921aa86408593c34af77fdd90df932f8b5261">Function</a>.</p>

</div>
</div>

### visit() {#a0466a89ecf2d430b651264e562f22057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::xray::BlockVerifier::visit (<a href="/web-llvm/docs/api/classes/llvm/xray/customeventrecordv5">CustomEventRecordV5</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/blockverifier-cpp">BlockVerifier.cpp</a>.</p>


<p>Reference <a href="#a59694dabdf15b05a6ed96e3d6395921aac8b0247e97b3b6334312cddb4de4182e">CustomEvent</a>.</p>

</div>
</div>

### visit() {#aa1d0957ab5ee78c3b17b8ede0ccca66c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::xray::BlockVerifier::visit (<a href="/web-llvm/docs/api/classes/llvm/xray/typedeventrecord">TypedEventRecord</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>, definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/blockverifier-cpp">BlockVerifier.cpp</a>.</p>


<p>Reference <a href="#a59694dabdf15b05a6ed96e3d6395921aa583dedceb162e94531b777a3b8902743">TypedEvent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### transition() {#ad32b26d167d98bd2c9d3e5881e0e093f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::xray::BlockVerifier::transition (<a href="#a59694dabdf15b05a6ed96e3d6395921a">State</a> To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/blockverifier-cpp">BlockVerifier.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurrentRecord {#a0d50ad09b365f7510886fd6db5736f12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">State llvm::xray::BlockVerifier::CurrentRecord = <a href="#a59694dabdf15b05a6ed96e3d6395921aa88183b946cc5f0e8c96b2e66e1c74a7e">State::Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/blockverifier-h">BlockVerifier.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/xray/blockverifier-cpp">BlockVerifier.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
