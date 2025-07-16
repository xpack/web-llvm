---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/globalsaaresult/functioninfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FunctionInfo` Class Reference

<p>The mod/ref information collected for a particular function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class GlobalsAAResult::FunctionInfo { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a>, 16 &gt; <a href="#a52f6f3367d250db7c2e62f199c45e29a">GlobalInfoMapType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a663d209e70aa95872d1a553199751674">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The bit that flags that this function may read any global. <a href="#a663d209e70aa95872d1a553199751674">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45c6cc412de79de2f22bf4561911d9e3">FunctionInfo</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks to document the invariants of the bit packing here. <a href="#a45c6cc412de79de2f22bf4561911d9e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae173b2b792c9039e4fce9c0f53b963b4">FunctionInfo</a> (const FunctionInfo &amp;Arg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfb1854001adea3be3a88039c2117005">FunctionInfo</a> (FunctionInfo &amp;&amp;Arg)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c6e699c0d9330913e7e1c3f8187a5a7">~FunctionInfo</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/globalsaaresult/functioninfo">FunctionInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59b9e0575ddae55782ce6d36c68a3396">operator=</a> (const FunctionInfo &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/globalsaaresult/functioninfo">FunctionInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0514c42efe48f54abafb5b7550c9ae17">operator=</a> (FunctionInfo &amp;&amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abda4335ae7608e886cfdf6e81c936b1f">globalClearMayReadAnyGlobal</a> (int I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method clears MayReadAnyGlobal bit added by <a href="/web-llvm/docs/api/classes/llvm/globalsaaresult">GlobalsAAResult</a> to return the corresponding <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a>. <a href="#abda4335ae7608e886cfdf6e81c936b1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fd3dff91e81708c4c2a430e621a7b2f">getModRefInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></span> info for this function. <a href="#a3fd3dff91e81708c4c2a430e621a7b2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bec97a8ab1afce272cd9215abbcfa1e">addModRefInfo</a> (ModRefInfo NewMRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds new <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></span> for this function to its state. <a href="#a1bec97a8ab1afce272cd9215abbcfa1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2fc323f1393bfa9131d122bfe9141e2">mayReadAnyGlobal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether this function may read any global variable, and we don't know which global. <a href="#ac2fc323f1393bfa9131d122bfe9141e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bc827f84df89a03516878d21ff2a330">setMayReadAnyGlobal</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets this function as potentially reading from any global. <a href="#a1bc827f84df89a03516878d21ff2a330">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed4ce4927fbaa9a7569a0e00f7cd5d0c">getModRefInfoForGlobal</a> (const GlobalValue &amp;GV) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></span> info for this function w.r.t. <a href="#aed4ce4927fbaa9a7569a0e00f7cd5d0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a243c7b35c64a8a4df8f2c159f5421139">addFunctionInfo</a> (const FunctionInfo &amp;FI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add mod/ref info from another function into ours, saturating towards ModRef. <a href="#a243c7b35c64a8a4df8f2c159f5421139">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ba9e0ce6cea222950b9800c6c8ff948">addModRefInfoForGlobal</a> (const GlobalValue &amp;GV, ModRefInfo NewMRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16ec45d8f221e08bbcc862c852ed6d68">eraseModRefInfoForGlobal</a> (const GlobalValue &amp;GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear a global's ModRef info. <a href="#a16ec45d8f221e08bbcc862c852ed6d68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; AlignedMap *, 3, unsigned, AlignedMapPointerTraits &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4500d6507d837f7f413d51d2766741f2">Info</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All of the information is encoded into a single pointer, with a three bit integer in the low three bits. <a href="#a4500d6507d837f7f413d51d2766741f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The mod/ref information collected for a particular function.</p>


<p>We collect information about mod/ref behavior of a function here, both in general and as pertains to specific globals. We only have this detailed information when we know <em>something</em> useful about the behavior. If we saturate to fully general mod/ref, we remove the info for the function.</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### GlobalInfoMapType {#a52f6f3367d250db7c2e62f199c45e29a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallDenseMap&lt;const GlobalValue *, ModRefInfo, 16&gt; llvm::GlobalsAAResult::FunctionInfo::GlobalInfoMapType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a663d209e70aa95872d1a553199751674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The bit that flags that this function may read any global.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MayReadAnyGlobal<a id="a663d209e70aa95872d1a553199751674a6b317ffae69da9b553e1656472554509"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

</table>
</dd>
</dl>


<p>This is chosen to mix together with <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> bits. FIXME: This assumes <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> lattice will remain 4 bits! <a href="#a3fd3dff91e81708c4c2a430e621a7b2f">FunctionInfo.getModRefInfo()</a> masks out everything except ModRef so this remains correct.</p>


<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### FunctionInfo() {#a45c6cc412de79de2f22bf4561911d9e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GlobalsAAResult::FunctionInfo::FunctionInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks to document the invariants of the bit packing here.</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>


<p>Referenced by <a href="#a243c7b35c64a8a4df8f2c159f5421139">llvm::GlobalsAAResult::FunctionInfo::addFunctionInfo</a>, <a href="#ae173b2b792c9039e4fce9c0f53b963b4">llvm::GlobalsAAResult::FunctionInfo::FunctionInfo</a>, <a href="#adfb1854001adea3be3a88039c2117005">llvm::GlobalsAAResult::FunctionInfo::FunctionInfo</a>, <a href="#a59b9e0575ddae55782ce6d36c68a3396">llvm::GlobalsAAResult::FunctionInfo::operator=</a> and <a href="#a0514c42efe48f54abafb5b7550c9ae17">llvm::GlobalsAAResult::FunctionInfo::operator=</a>.</p>

</div>
</div>

### FunctionInfo() {#ae173b2b792c9039e4fce9c0f53b963b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GlobalsAAResult::FunctionInfo::FunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/globalsaaresult/functioninfo">FunctionInfo</a> &amp; Arg)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>


<p>References <a href="#a45c6cc412de79de2f22bf4561911d9e3">llvm::GlobalsAAResult::FunctionInfo::FunctionInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/pointerintpair/#ac8b55437ca130fe0c826e94e669e5d99">llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::getPointer</a>.</p>

</div>
</div>

### FunctionInfo() {#adfb1854001adea3be3a88039c2117005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GlobalsAAResult::FunctionInfo::FunctionInfo (<a href="/web-llvm/docs/api/classes/globalsaaresult/functioninfo">FunctionInfo</a> &amp;&amp; Arg)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>


<p>Reference <a href="#a45c6cc412de79de2f22bf4561911d9e3">llvm::GlobalsAAResult::FunctionInfo::FunctionInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~FunctionInfo() {#a2c6e699c0d9330913e7e1c3f8187a5a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GlobalsAAResult::FunctionInfo::~FunctionInfo ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a59b9e0575ddae55782ce6d36c68a3396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionInfo &amp; llvm::GlobalsAAResult::FunctionInfo::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/globalsaaresult/functioninfo">FunctionInfo</a> &amp; RHS)</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>


<p>Reference <a href="#a45c6cc412de79de2f22bf4561911d9e3">llvm::GlobalsAAResult::FunctionInfo::FunctionInfo</a>.</p>

</div>
</div>

### operator=() {#a0514c42efe48f54abafb5b7550c9ae17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionInfo &amp; llvm::GlobalsAAResult::FunctionInfo::operator= (<a href="/web-llvm/docs/api/classes/globalsaaresult/functioninfo">FunctionInfo</a> &amp;&amp; RHS)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>


<p>References <a href="#a45c6cc412de79de2f22bf4561911d9e3">llvm::GlobalsAAResult::FunctionInfo::FunctionInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/pointerintpair/#a6c7149b1ad550ed8ccdec643bc0ef117">llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::setPointerAndInt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFunctionInfo() {#a243c7b35c64a8a4df8f2c159f5421139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalsAAResult::FunctionInfo::addFunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/globalsaaresult/functioninfo">FunctionInfo</a> &amp; FI)</td>
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

<p>Add mod/ref info from another function into ours, saturating towards ModRef.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>


<p>References <a href="#a1bec97a8ab1afce272cd9215abbcfa1e">llvm::GlobalsAAResult::FunctionInfo::addModRefInfo</a>, <a href="#a6ba9e0ce6cea222950b9800c6c8ff948">llvm::GlobalsAAResult::FunctionInfo::addModRefInfoForGlobal</a>, <a href="#a45c6cc412de79de2f22bf4561911d9e3">llvm::GlobalsAAResult::FunctionInfo::FunctionInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a3fd3dff91e81708c4c2a430e621a7b2f">llvm::GlobalsAAResult::FunctionInfo::getModRefInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/pointerintpair/#ac8b55437ca130fe0c826e94e669e5d99">llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::getPointer</a>, <a href="#ac2fc323f1393bfa9131d122bfe9141e2">llvm::GlobalsAAResult::FunctionInfo::mayReadAnyGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a1bc827f84df89a03516878d21ff2a330">llvm::GlobalsAAResult::FunctionInfo::setMayReadAnyGlobal</a>.</p>

</div>
</div>

### addModRefInfo() {#a1bec97a8ab1afce272cd9215abbcfa1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalsAAResult::FunctionInfo::addModRefInfo (<a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> NewMRI)</td>
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

<p>Adds new <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></span> for this function to its state.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>


<p>Referenced by <a href="#a243c7b35c64a8a4df8f2c159f5421139">llvm::GlobalsAAResult::FunctionInfo::addFunctionInfo</a>.</p>

</div>
</div>

### addModRefInfoForGlobal() {#a6ba9e0ce6cea222950b9800c6c8ff948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalsAAResult::FunctionInfo::addModRefInfoForGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> NewMRI)</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a243c7b35c64a8a4df8f2c159f5421139">llvm::GlobalsAAResult::FunctionInfo::addFunctionInfo</a>.</p>

</div>
</div>

### eraseModRefInfoForGlobal() {#a16ec45d8f221e08bbcc862c852ed6d68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalsAAResult::FunctionInfo::eraseModRefInfoForGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
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

<p>Clear a global's ModRef info.</p>


<p>Should be used when a global is being deleted.</p>


<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### getModRefInfo() {#a3fd3dff91e81708c4c2a430e621a7b2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo llvm::GlobalsAAResult::FunctionInfo::getModRefInfo ()</td>
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

<p>Returns the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></span> info for this function.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>


<p>Reference <a href="#abda4335ae7608e886cfdf6e81c936b1f">llvm::GlobalsAAResult::FunctionInfo::globalClearMayReadAnyGlobal</a>.</p>


<p>Referenced by <a href="#a243c7b35c64a8a4df8f2c159f5421139">llvm::GlobalsAAResult::FunctionInfo::addFunctionInfo</a>.</p>

</div>
</div>

### getModRefInfoForGlobal() {#aed4ce4927fbaa9a7569a0e00f7cd5d0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo llvm::GlobalsAAResult::FunctionInfo::getModRefInfoForGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
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

<p>Returns the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></span> info for this function w.r.t.</p>


<p>a particular global, which may be more precise than the general information above.</p>


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac2fc323f1393bfa9131d122bfe9141e2">llvm::GlobalsAAResult::FunctionInfo::mayReadAnyGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ead974636fce6d12e72054e61fb3c1e9a8">llvm::NoModRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### globalClearMayReadAnyGlobal() {#abda4335ae7608e886cfdf6e81c936b1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo llvm::GlobalsAAResult::FunctionInfo::globalClearMayReadAnyGlobal (int I)</td>
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

<p>This method clears MayReadAnyGlobal bit added by <a href="/web-llvm/docs/api/classes/llvm/globalsaaresult">GlobalsAAResult</a> to return the corresponding <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a>.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea6524b183b5cd0850f2cff6d30d581af9">llvm::ModRef</a>.</p>


<p>Referenced by <a href="#a3fd3dff91e81708c4c2a430e621a7b2f">llvm::GlobalsAAResult::FunctionInfo::getModRefInfo</a>.</p>

</div>
</div>

### mayReadAnyGlobal() {#ac2fc323f1393bfa9131d122bfe9141e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalsAAResult::FunctionInfo::mayReadAnyGlobal ()</td>
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

<p>Returns whether this function may read any global variable, and we don't know which global.</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>


<p>Referenced by <a href="#a243c7b35c64a8a4df8f2c159f5421139">llvm::GlobalsAAResult::FunctionInfo::addFunctionInfo</a> and <a href="#aed4ce4927fbaa9a7569a0e00f7cd5d0c">llvm::GlobalsAAResult::FunctionInfo::getModRefInfoForGlobal</a>.</p>

</div>
</div>

### setMayReadAnyGlobal() {#a1bc827f84df89a03516878d21ff2a330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalsAAResult::FunctionInfo::setMayReadAnyGlobal ()</td>
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

<p>Sets this function as potentially reading from any global.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>


<p>Referenced by <a href="#a243c7b35c64a8a4df8f2c159f5421139">llvm::GlobalsAAResult::FunctionInfo::addFunctionInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Info {#a4500d6507d837f7f413d51d2766741f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerIntPair&lt;AlignedMap *, 3, unsigned, AlignedMapPointerTraits&gt; llvm::GlobalsAAResult::FunctionInfo::Info</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All of the information is encoded into a single pointer, with a three bit integer in the low three bits.</p>


<p>The high bit provides a flag for when this function may read any global. The low two bits are the <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a>. And the pointer, when non-null, points to a map from <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> to <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> specific to that <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a>.</p>


<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp">GlobalsModRef.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
