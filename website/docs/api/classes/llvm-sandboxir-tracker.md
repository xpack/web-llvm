---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/tracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Tracker` Class Reference

<p>The tracker collects all the change objects and implements the main API for saving / reverting / accepting. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::Tracker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">llvm/SandboxIR/Tracker.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TrackerState { <a href="#a4df022e08f7e3939946ef163a2a44561">...</a> }</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fb3dae8bf227a7b5342d1b31576e3e3">operator&lt;&lt;</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba436f9005948026277c7efc7e3b35bb">Tracker</a> (Context &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ed1e23312cfe7fcfe5f2ac2abd69163">~Tracker</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7e4e8e2c44d4ab0839dac693df7b06c">getContext</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc06dcb45b7b1609a832dcce4b36c227">track</a> (std::unique_ptr&lt; IRChangeBase &gt; &amp;&amp;Change)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> <span class="doxyComputerOutput">Change</span> and take ownership. <a href="#abc06dcb45b7b1609a832dcce4b36c227">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ChangeT, typename... ArgsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae78b97b8ea9885d09219a569caff84b7">emplaceIfTracking</a> (ArgsT... Args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A convenience wrapper for <span class="doxyComputerOutput"><a href="#abc06dcb45b7b1609a832dcce4b36c227">track()</a></span> that constructs and tracks the Change object if tracking is enabled. <a href="#ae78b97b8ea9885d09219a569caff84b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa19c60a204cb57bc2a7e76803aa34396">isTracking</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns true if the tracker is recording changes. <a href="#aa19c60a204cb57bc2a7e76803aa34396">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4df022e08f7e3939946ef163a2a44561">TrackerState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e10b030135657d3579c5597be47d38b">getState</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the current state of the tracker. <a href="#a5e10b030135657d3579c5597be47d38b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba1e7674e521c417d80a5eac6748d87c">save</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turns on IR tracking. <a href="#aba1e7674e521c417d80a5eac6748d87c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2dc80d73e1cda034556ffb7f007374b">accept</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stops tracking and accept changes. <a href="#af2dc80d73e1cda034556ffb7f007374b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e071ba5536194c934854e59bb1c7415">revert</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stops tracking and reverts to saved state. <a href="#a5e071ba5536194c934854e59bb1c7415">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a819361cde3cd4564950f3041bafcfd6f">dump</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af30e21800ff0abcec2638a703c49b5b6">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac550425db21273815494e2b02fed555b">InMiddleOfCreatingChange</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helps catch bugs where we are creating new change objects while in the middle of creating other change objects. <a href="#ac550425db21273815494e2b02fed555b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/irchangebase">IRChangeBase</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b151b33058a97f7f057303147b4c1a1">Changes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of changes that are being tracked. <a href="#a2b151b33058a97f7f057303147b4c1a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4df022e08f7e3939946ef163a2a44561">TrackerState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af593b18b0fc5af0aa45c0719e136177d">State</a> = <a href="#a4df022e08f7e3939946ef163a2a44561ab9f5c797ebbf55adccdd8539a65a0241">TrackerState::Disabled</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current state of the tracker. <a href="#af593b18b0fc5af0aa45c0719e136177d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84cad5b57c519ef05a12649d4a2dd1a5">Ctx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/irsnapshotchecker">IRSnapshotChecker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7874efb23a5a0c017bd7a3b9657137a2">SnapshotChecker</a></td>
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

<p>The tracker collects all the change objects and implements the main API for saving / reverting / accepting.</p>

<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### TrackerState {#a4df022e08f7e3939946ef163a2a44561}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::sandboxir::Tracker::TrackerState </td>
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
<td class="doxyEnumItemName">Disabled<a id="a4df022e08f7e3939946ef163a2a44561ab9f5c797ebbf55adccdd8539a65a0241"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Record<a id="a4df022e08f7e3939946ef163a2a44561a6a0d9eaee314c567fd72fb97ee707a36"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### operator&lt;&lt; {#a7fb3dae8bf227a7b5342d1b31576e3e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/tracker">Tracker</a> &amp; Tracker</td>
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


<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>


<p>Reference <a href="#aba436f9005948026277c7efc7e3b35bb">Tracker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Tracker() {#aba436f9005948026277c7efc7e3b35bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::Tracker::Tracker (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h/#a8de3ed741dadc9c979a4ff17c0a9116e">NDEBUG</a>.</p>


<p>Referenced by <a href="#a7fb3dae8bf227a7b5342d1b31576e3e3">operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Tracker() {#a0ed1e23312cfe7fcfe5f2ac2abd69163}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Tracker::~Tracker ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/tracker-cpp">Tracker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### accept() {#af2dc80d73e1cda034556ffb7f007374b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Tracker::accept ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stops tracking and accept changes.</p>

<p>Declaration at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>, definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/tracker-cpp">Tracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4df022e08f7e3939946ef163a2a44561ab9f5c797ebbf55adccdd8539a65a0241">Disabled</a> and <a href="#a4df022e08f7e3939946ef163a2a44561a6a0d9eaee314c567fd72fb97ee707a36">Record</a>.</p>

</div>
</div>

### dump() {#a819361cde3cd4564950f3041bafcfd6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Tracker::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>, definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/tracker-cpp">Tracker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>.</p>

</div>
</div>

### dump() {#af30e21800ff0abcec2638a703c49b5b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Tracker::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>, definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/tracker-cpp">Tracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#af30e21800ff0abcec2638a703c49b5b6">dump</a>.</p>


<p>Referenced by <a href="#af30e21800ff0abcec2638a703c49b5b6">dump</a>.</p>

</div>
</div>

### emplaceIfTracking() {#ae78b97b8ea9885d09219a569caff84b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ChangeT, typename... ArgsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Tracker::emplaceIfTracking (ArgsT... Args)</td>
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

<p>A convenience wrapper for <span class="doxyComputerOutput"><a href="#abc06dcb45b7b1609a832dcce4b36c227">track()</a></span> that constructs and tracks the Change object if tracking is enabled.</p>


<p>\Returns true if tracking is enabled.</p>


<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>


<p>References <a href="#aa19c60a204cb57bc2a7e76803aa34396">isTracking</a> and <a href="#abc06dcb45b7b1609a832dcce4b36c227">track</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#ae3c21dcbfdf18433a9bb69131cda53e6">llvm::sandboxir::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/#add6c98d077e2f344b4d49266a2692696">llvm::sandboxir::Context::registerValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#a0b2bc62c021fac7a3b7cb98ba3654ff3">llvm::sandboxir::PHINode::removeIncomingValue</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#abd01234117775c7ff32e73f0134b7e34">llvm::sandboxir::PHINode::removeIncomingValue</a>.</p>

</div>
</div>

### getContext() {#ac7e4e8e2c44d4ab0839dac693df7b06c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Context &amp; llvm::sandboxir::Tracker::getContext ()</td>
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



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>

</div>
</div>

### getState() {#a5e10b030135657d3579c5597be47d38b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TrackerState llvm::sandboxir::Tracker::getState ()</td>
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

<p>\Returns the current state of the tracker.</p>

<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>

</div>
</div>

### isTracking() {#aa19c60a204cb57bc2a7e76803aa34396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Tracker::isTracking ()</td>
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

<p>\Returns true if the tracker is recording changes.</p>

<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>


<p>Reference <a href="#a4df022e08f7e3939946ef163a2a44561a6a0d9eaee314c567fd72fb97ee707a36">Record</a>.</p>


<p>Referenced by <a href="#ae78b97b8ea9885d09219a569caff84b7">emplaceIfTracking</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a357dd7c60a0ea6b2e6c7ecdf9c9923d1">llvm::sandboxir::Value::replaceAllUsesWith</a> and <a href="#abc06dcb45b7b1609a832dcce4b36c227">track</a>.</p>

</div>
</div>

### revert() {#a5e071ba5536194c934854e59bb1c7415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Tracker::revert ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stops tracking and reverts to saved state.</p>

<p>Declaration at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>, definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/tracker-cpp">Tracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4df022e08f7e3939946ef163a2a44561ab9f5c797ebbf55adccdd8539a65a0241">Disabled</a>, <a href="#a4df022e08f7e3939946ef163a2a44561a6a0d9eaee314c567fd72fb97ee707a36">Record</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>

</div>
</div>

### save() {#aba1e7674e521c417d80a5eac6748d87c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Tracker::save ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Turns on IR tracking.</p>

<p>Declaration at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/tracker-cpp">Tracker.cpp</a>.</p>


<p>Reference <a href="#a4df022e08f7e3939946ef163a2a44561a6a0d9eaee314c567fd72fb97ee707a36">Record</a>.</p>

</div>
</div>

### track() {#abc06dcb45b7b1609a832dcce4b36c227}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Tracker::track (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/irchangebase">IRChangeBase</a> &gt; &amp;&amp; Change)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> <span class="doxyComputerOutput">Change</span> and take ownership.</p>


<p>This is the main function used to track Sandbox IR changes.</p>


<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac550425db21273815494e2b02fed555b">InMiddleOfCreatingChange</a>, <a href="#aa19c60a204cb57bc2a7e76803aa34396">isTracking</a> and <a href="#a4df022e08f7e3939946ef163a2a44561a6a0d9eaee314c567fd72fb97ee707a36">Record</a>.</p>


<p>Referenced by <a href="#ae78b97b8ea9885d09219a569caff84b7">emplaceIfTracking</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a357dd7c60a0ea6b2e6c7ecdf9c9923d1">llvm::sandboxir::Value::replaceAllUsesWith</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### InMiddleOfCreatingChange {#ac550425db21273815494e2b02fed555b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Tracker::InMiddleOfCreatingChange = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helps catch bugs where we are creating new change objects while in the middle of creating other change objects.</p>

<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>


<p>Referenced by <a href="#abc06dcb45b7b1609a832dcce4b36c227">track</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Changes {#a2b151b33058a97f7f057303147b4c1a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;IRChangeBase&gt; &gt; llvm::sandboxir::Tracker::Changes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The list of changes that are being tracked.</p>

<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>

</div>
</div>

### Ctx {#a84cad5b57c519ef05a12649d4a2dd1a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Context&amp; llvm::sandboxir::Tracker::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>

</div>
</div>

### SnapshotChecker {#a7874efb23a5a0c017bd7a3b9657137a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRSnapshotChecker llvm::sandboxir::Tracker::SnapshotChecker</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>

</div>
</div>

### State {#af593b18b0fc5af0aa45c0719e136177d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TrackerState llvm::sandboxir::Tracker::State = <a href="#a4df022e08f7e3939946ef163a2a44561ab9f5c797ebbf55adccdd8539a65a0241">TrackerState::Disabled</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The current state of the tracker.</p>

<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/tracker-cpp">Tracker.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
