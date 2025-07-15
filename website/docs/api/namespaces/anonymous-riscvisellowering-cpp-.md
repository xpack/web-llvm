---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-riscvisellowering-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{RISCVISelLowering.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{RISCVISelLowering.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper structure that holds all the necessary information to materialize a combine that does some extension folding. <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class for folding sign/zero extensions. <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ExtKind : uint8_t { <a href="#a0fb45dddfe1615e320ac9ad137d634e7">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adec3c0687a05bd66a2a9937f4a374d34">canFoldToVWWithSameExtensionImpl</a> (SDNode *Root, const NodeExtensionHelper &amp;LHS, const NodeExtensionHelper &amp;RHS, uint8_t AllowExtMask, SelectionDAG &amp;DAG, const RISCVSubtarget &amp;Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if <span class="doxyComputerOutput">Root</span> follows a pattern Root(ext(LHS), ext(RHS)) where <span class="doxyComputerOutput">ext</span> is the same for both LHS and RHS (i.e., both are sext or both are zext) and LHS and RHS can be folded into Root. <a href="#adec3c0687a05bd66a2a9937f4a374d34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a866d5dd0b3838b0751d25c237dd9b8b6">canFoldToVWWithSameExtension</a> (SDNode *Root, const NodeExtensionHelper &amp;LHS, const NodeExtensionHelper &amp;RHS, SelectionDAG &amp;DAG, const RISCVSubtarget &amp;Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if <span class="doxyComputerOutput">Root</span> follows a pattern Root(ext(LHS), ext(RHS)) where <span class="doxyComputerOutput">ext</span> is the same for both LHS and RHS (i.e., both are sext or both are zext) and LHS and RHS can be folded into Root. <a href="#a866d5dd0b3838b0751d25c237dd9b8b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b2154a7e9a794c5b363a5c2c1e489bd">canFoldToVW_W</a> (SDNode *Root, const NodeExtensionHelper &amp;LHS, const NodeExtensionHelper &amp;RHS, SelectionDAG &amp;DAG, const RISCVSubtarget &amp;Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if <span class="doxyComputerOutput">Root</span> follows a pattern Root(LHS, ext(RHS)) <a href="#a8b2154a7e9a794c5b363a5c2c1e489bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c43a9fe0538ec36fd98a4415b58c14a">canFoldToVWWithSEXT</a> (SDNode *Root, const NodeExtensionHelper &amp;LHS, const NodeExtensionHelper &amp;RHS, SelectionDAG &amp;DAG, const RISCVSubtarget &amp;Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if <span class="doxyComputerOutput">Root</span> follows a pattern Root(sext(LHS), sext(RHS)) <a href="#a7c43a9fe0538ec36fd98a4415b58c14a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa60899790b80d7bba8a4f76ca19ea699">canFoldToVWWithZEXT</a> (SDNode *Root, const NodeExtensionHelper &amp;LHS, const NodeExtensionHelper &amp;RHS, SelectionDAG &amp;DAG, const RISCVSubtarget &amp;Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if <span class="doxyComputerOutput">Root</span> follows a pattern Root(zext(LHS), zext(RHS)) <a href="#aa60899790b80d7bba8a4f76ca19ea699">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf060deb455eb2c66d75fb603fa24794">canFoldToVWWithFPEXT</a> (SDNode *Root, const NodeExtensionHelper &amp;LHS, const NodeExtensionHelper &amp;RHS, SelectionDAG &amp;DAG, const RISCVSubtarget &amp;Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if <span class="doxyComputerOutput">Root</span> follows a pattern Root(fpext(LHS), fpext(RHS)) <a href="#abf060deb455eb2c66d75fb603fa24794">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affe8145f52cae856369a22fa52019397">canFoldToVW_SU</a> (SDNode *Root, const NodeExtensionHelper &amp;LHS, const NodeExtensionHelper &amp;RHS, SelectionDAG &amp;DAG, const RISCVSubtarget &amp;Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if <span class="doxyComputerOutput">Root</span> follows a pattern Root(sext(LHS), zext(RHS)) <a href="#affe8145f52cae856369a22fa52019397">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### ExtKind {#a0fb45dddfe1615e320ac9ad137d634e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{RISCVISelLowering.cpp}::ExtKind : uint8_t</td>
</tr>
</table>
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
<td class="doxyEnumItemName">ZExt<a id="a0fb45dddfe1615e320ac9ad137d634e7aa2f0622a02fc4af2ec7bd22803523662"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SExt<a id="a0fb45dddfe1615e320ac9ad137d634e7a6d82f5a74a3f08ddcbb81036603b1f7c"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPExt<a id="a0fb45dddfe1615e320ac9ad137d634e7a2e8f4f487902ef68689d6a02548cf8af"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 14982 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### canFoldToVW\_SU() {#affe8145f52cae856369a22fa52019397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CombineResult &gt; anonymous{RISCVISelLowering.cpp}::canFoldToVW_SU (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; Subtarget)</td>
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

<p>Check if <span class="doxyComputerOutput">Root</span> follows a pattern Root(sext(LHS), zext(RHS))</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>std::nullopt if the pattern doesn't match or a <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a> that can be used to apply the pattern.</p></dd>
</dl>


<p>Definition at line 15694 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="#affe8145f52cae856369a22fa52019397">canFoldToVW_SU</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a> and <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a5a95502e159b8ac43cdfca93752306eb">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getSUOpcode</a>.</p>


<p>Referenced by <a href="#affe8145f52cae856369a22fa52019397">canFoldToVW_SU</a> and <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a776c5a5c2c4c9c913f9b44e5b0437f69">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getSupportedFoldings</a>.</p>

</div>
</div>

### canFoldToVW\_W() {#a8b2154a7e9a794c5b363a5c2c1e489bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CombineResult &gt; anonymous{RISCVISelLowering.cpp}::canFoldToVW_W (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; Subtarget)</td>
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

<p>Check if <span class="doxyComputerOutput">Root</span> follows a pattern Root(LHS, ext(RHS))</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>std::nullopt if the pattern doesn't match or a <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a> that can be used to apply the pattern.</p></dd>
</dl>


<p>Definition at line 15630 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae35e08372bea9134c9fc9e5809af958d">AllowSplatInVW_W</a>, <a href="#a8b2154a7e9a794c5b363a5c2c1e489bd">canFoldToVW_W</a>, <a href="#a0fb45dddfe1615e320ac9ad137d634e7a2e8f4f487902ef68689d6a02548cf8af">FPExt</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a378f0c17215c7767060ad8ac7edc9a12">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getWOpcode</a>, <a href="#a0fb45dddfe1615e320ac9ad137d634e7a6d82f5a74a3f08ddcbb81036603b1f7c">SExt</a> and <a href="#a0fb45dddfe1615e320ac9ad137d634e7aa2f0622a02fc4af2ec7bd22803523662">ZExt</a>.</p>


<p>Referenced by <a href="#a8b2154a7e9a794c5b363a5c2c1e489bd">canFoldToVW_W</a> and <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a776c5a5c2c4c9c913f9b44e5b0437f69">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getSupportedFoldings</a>.</p>

</div>
</div>

### canFoldToVWWithFPEXT() {#abf060deb455eb2c66d75fb603fa24794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CombineResult &gt; anonymous{RISCVISelLowering.cpp}::canFoldToVWWithFPEXT (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; Subtarget)</td>
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

<p>Check if <span class="doxyComputerOutput">Root</span> follows a pattern Root(fpext(LHS), fpext(RHS))</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>std::nullopt if the pattern doesn't match or a <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a> that can be used to apply the pattern.</p></dd>
</dl>


<p>Definition at line 15682 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="#abf060deb455eb2c66d75fb603fa24794">canFoldToVWWithFPEXT</a>, <a href="#adec3c0687a05bd66a2a9937f4a374d34">canFoldToVWWithSameExtensionImpl</a> and <a href="#a0fb45dddfe1615e320ac9ad137d634e7a2e8f4f487902ef68689d6a02548cf8af">FPExt</a>.</p>


<p>Referenced by <a href="#abf060deb455eb2c66d75fb603fa24794">canFoldToVWWithFPEXT</a> and <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a776c5a5c2c4c9c913f9b44e5b0437f69">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getSupportedFoldings</a>.</p>

</div>
</div>

### canFoldToVWWithSameExtension() {#a866d5dd0b3838b0751d25c237dd9b8b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CombineResult &gt; anonymous{RISCVISelLowering.cpp}::canFoldToVWWithSameExtension (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; Subtarget)</td>
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

<p>Check if <span class="doxyComputerOutput">Root</span> follows a pattern Root(ext(LHS), ext(RHS)) where <span class="doxyComputerOutput">ext</span> is the same for both LHS and RHS (i.e., both are sext or both are zext) and LHS and RHS can be folded into Root.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>std::nullopt if the pattern doesn't match or a <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a> that can be used to apply the pattern.</p></dd>
</dl>


<p>Definition at line 15617 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="#a866d5dd0b3838b0751d25c237dd9b8b6">canFoldToVWWithSameExtension</a>, <a href="#adec3c0687a05bd66a2a9937f4a374d34">canFoldToVWWithSameExtensionImpl</a>, <a href="#a0fb45dddfe1615e320ac9ad137d634e7a2e8f4f487902ef68689d6a02548cf8af">FPExt</a>, <a href="#a0fb45dddfe1615e320ac9ad137d634e7a6d82f5a74a3f08ddcbb81036603b1f7c">SExt</a> and <a href="#a0fb45dddfe1615e320ac9ad137d634e7aa2f0622a02fc4af2ec7bd22803523662">ZExt</a>.</p>


<p>Referenced by <a href="#a866d5dd0b3838b0751d25c237dd9b8b6">canFoldToVWWithSameExtension</a> and <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a776c5a5c2c4c9c913f9b44e5b0437f69">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getSupportedFoldings</a>.</p>

</div>
</div>

### canFoldToVWWithSameExtensionImpl() {#adec3c0687a05bd66a2a9937f4a374d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CombineResult &gt; anonymous{RISCVISelLowering.cpp}::canFoldToVWWithSameExtensionImpl (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp; RHS, uint8_t AllowExtMask, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; Subtarget)</td>
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

<p>Check if <span class="doxyComputerOutput">Root</span> follows a pattern Root(ext(LHS), ext(RHS)) where <span class="doxyComputerOutput">ext</span> is the same for both LHS and RHS (i.e., both are sext or both are zext) and LHS and RHS can be folded into Root.</p>


<p>AllowExtMask define which form <span class="doxyComputerOutput">ext</span> can take in this pattern.</p>



:::info
<p>If the pattern can match with both zext and sext, the returned <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a> will feature the zext result.</p>
:::


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>std::nullopt if the pattern doesn't match or a <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a> that can be used to apply the pattern.</p></dd>
</dl>


<p>Definition at line 15591 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="#adec3c0687a05bd66a2a9937f4a374d34">canFoldToVWWithSameExtensionImpl</a>, <a href="#a0fb45dddfe1615e320ac9ad137d634e7a2e8f4f487902ef68689d6a02548cf8af">FPExt</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a43dc5ea17cf1ee5d8069c6d9de119109">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getFPExtOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a4b72126752644e5cfe2680d909b3ff5a">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getSExtOpcode</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a2203a81e4da51a9da50c08965f2bf917">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getZExtOpcode</a>, <a href="#a0fb45dddfe1615e320ac9ad137d634e7a6d82f5a74a3f08ddcbb81036603b1f7c">SExt</a> and <a href="#a0fb45dddfe1615e320ac9ad137d634e7aa2f0622a02fc4af2ec7bd22803523662">ZExt</a>.</p>


<p>Referenced by <a href="#abf060deb455eb2c66d75fb603fa24794">canFoldToVWWithFPEXT</a>, <a href="#a866d5dd0b3838b0751d25c237dd9b8b6">canFoldToVWWithSameExtension</a>, <a href="#adec3c0687a05bd66a2a9937f4a374d34">canFoldToVWWithSameExtensionImpl</a>, <a href="#a7c43a9fe0538ec36fd98a4415b58c14a">canFoldToVWWithSEXT</a> and <a href="#aa60899790b80d7bba8a4f76ca19ea699">canFoldToVWWithZEXT</a>.</p>

</div>
</div>

### canFoldToVWWithSEXT() {#a7c43a9fe0538ec36fd98a4415b58c14a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CombineResult &gt; anonymous{RISCVISelLowering.cpp}::canFoldToVWWithSEXT (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; Subtarget)</td>
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

<p>Check if <span class="doxyComputerOutput">Root</span> follows a pattern Root(sext(LHS), sext(RHS))</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>std::nullopt if the pattern doesn't match or a <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a> that can be used to apply the pattern.</p></dd>
</dl>


<p>Definition at line 15658 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="#adec3c0687a05bd66a2a9937f4a374d34">canFoldToVWWithSameExtensionImpl</a>, <a href="#a7c43a9fe0538ec36fd98a4415b58c14a">canFoldToVWWithSEXT</a> and <a href="#a0fb45dddfe1615e320ac9ad137d634e7a6d82f5a74a3f08ddcbb81036603b1f7c">SExt</a>.</p>


<p>Referenced by <a href="#a7c43a9fe0538ec36fd98a4415b58c14a">canFoldToVWWithSEXT</a> and <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a776c5a5c2c4c9c913f9b44e5b0437f69">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getSupportedFoldings</a>.</p>

</div>
</div>

### canFoldToVWWithZEXT() {#aa60899790b80d7bba8a4f76ca19ea699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CombineResult &gt; anonymous{RISCVISelLowering.cpp}::canFoldToVWWithZEXT (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; Subtarget)</td>
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

<p>Check if <span class="doxyComputerOutput">Root</span> follows a pattern Root(zext(LHS), zext(RHS))</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>std::nullopt if the pattern doesn't match or a <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a> that can be used to apply the pattern.</p></dd>
</dl>


<p>Definition at line 15670 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="#adec3c0687a05bd66a2a9937f4a374d34">canFoldToVWWithSameExtensionImpl</a>, <a href="#aa60899790b80d7bba8a4f76ca19ea699">canFoldToVWWithZEXT</a> and <a href="#a0fb45dddfe1615e320ac9ad137d634e7aa2f0622a02fc4af2ec7bd22803523662">ZExt</a>.</p>


<p>Referenced by <a href="#aa60899790b80d7bba8a4f76ca19ea699">canFoldToVWWithZEXT</a> and <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a776c5a5c2c4c9c913f9b44e5b0437f69">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getSupportedFoldings</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
