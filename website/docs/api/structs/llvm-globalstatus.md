---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/globalstatus
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `GlobalStatus` Struct

<p>As we analyze each global or thread-local variable, keep track of some information about it. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::GlobalStatus { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/globalstatus-h">llvm/Transforms/Utils/GlobalStatus.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">StoredType { <a href="#abe8cd5e07daf1b2bf532174823523ee7">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of what stores to the global look like. <a href="#abe8cd5e07daf1b2bf532174823523ee7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66343ec7ee95f372f485d76945263189">GlobalStatus</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a878825b35bf0b197646751b36b74a2a1">getStoredOnceValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If only one value (besides the initializer constant) is ever stored to this global return the stored value. <a href="#a878825b35bf0b197646751b36b74a2a1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a793ea7e324427fc88ccdf62294b63fad">IsCompared</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the global's address is used in a comparison. <a href="#a793ea7e324427fc88ccdf62294b63fad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0371d896aba2b285da63fca3b700b169">IsLoaded</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the global is ever loaded. <a href="#a0371d896aba2b285da63fca3b700b169">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a373858349bc2e52452b818cbe2bff5">NumStores</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of stores to the global. <a href="#a3a373858349bc2e52452b818cbe2bff5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="#abe8cd5e07daf1b2bf532174823523ee7">llvm::GlobalStatus::StoredType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8661beacd5ed3a854cd3c98e565ee89e">StoredType</a> = <a href="#abe8cd5e07daf1b2bf532174823523ee7ae2ae8bccbba8e261ad5d71d3a84ce295">NotStored</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68be203655db8e678f567ff41e559500">StoredOnceStore</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If only one value (besides the initializer constant) is ever stored to this global, keep track of what value it is via the store instruction. <a href="#a68be203655db8e678f567ff41e559500">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdf22b304eab8994314a2a89c00103fc">AccessingFunction</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These start out null/false. <a href="#abdf22b304eab8994314a2a89c00103fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31d0dff181f81a41bb701e89600fe324">HasMultipleAccessingFunctions</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b1ce5881588fec97dfaaf3845b04640">Ordering</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">AtomicOrdering::NotAtomic</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set to the strongest atomic ordering requirement. <a href="#a1b1ce5881588fec97dfaaf3845b04640">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae58ea7b3b03443e976cbef09ac25cf00">analyzeGlobal</a> (const Value *V, GlobalStatus &amp;GS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look at all uses of the global and fill in the <a href="/web-llvm/docs/api/structs/llvm/globalstatus">GlobalStatus</a> structure. <a href="#ae58ea7b3b03443e976cbef09ac25cf00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>As we analyze each global or thread-local variable, keep track of some information about it.</p>


<p>If we find out that the address of the global is taken, none of this info will be accurate.</p>


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/globalstatus-h">GlobalStatus.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### StoredType {#abe8cd5e07daf1b2bf532174823523ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::GlobalStatus::StoredType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of what stores to the global look like.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NotStored<a id="abe8cd5e07daf1b2bf532174823523ee7ae2ae8bccbba8e261ad5d71d3a84ce295"></a></td>
<td class="doxyEnumItemDescription">There is no store to this global. It can thus be marked constant</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InitializerStored<a id="abe8cd5e07daf1b2bf532174823523ee7adcbfa969dc654b5812a05827152a42c5"></a></td>
<td class="doxyEnumItemDescription">This global is stored to, but the only thing stored is the constant it was initialized with</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StoredOnce<a id="abe8cd5e07daf1b2bf532174823523ee7aecd55f74522361f4b8056f8b6b745699"></a></td>
<td class="doxyEnumItemDescription">This global is stored to, but only its initializer and one other value is ever stored to it</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Stored<a id="abe8cd5e07daf1b2bf532174823523ee7a3b94935998fa471818fb34bceb4c1357"></a></td>
<td class="doxyEnumItemDescription">This global is stored to by multiple values or something else that we cannot track</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/globalstatus-h">GlobalStatus.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GlobalStatus() {#a66343ec7ee95f372f485d76945263189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalStatus::GlobalStatus ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/globalstatus-h">GlobalStatus.h</a>.</p>


<p>Reference <a href="#a66343ec7ee95f372f485d76945263189">GlobalStatus</a>.</p>


<p>Referenced by <a href="#ae58ea7b3b03443e976cbef09ac25cf00">analyzeGlobal</a> and <a href="#a66343ec7ee95f372f485d76945263189">GlobalStatus</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getStoredOnceValue() {#a878825b35bf0b197646751b36b74a2a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::GlobalStatus::getStoredOnceValue ()</td>
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

<p>If only one value (besides the initializer constant) is ever stored to this global return the stored value.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/globalstatus-h">GlobalStatus.h</a>.</p>


<p>References <a href="#abe8cd5e07daf1b2bf532174823523ee7aecd55f74522361f4b8056f8b6b745699">StoredOnce</a> and <a href="#a68be203655db8e678f567ff41e559500">StoredOnceStore</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AccessingFunction {#abdf22b304eab8994314a2a89c00103fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function* llvm::GlobalStatus::AccessingFunction = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>These start out null/false.</p>


<p>When the first accessing function is noticed, it is recorded. When a second different accessing function is noticed, HasMultipleAccessingFunctions is set to true.</p>


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/globalstatus-h">GlobalStatus.h</a>.</p>

</div>
</div>

### HasMultipleAccessingFunctions {#a31d0dff181f81a41bb701e89600fe324}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalStatus::HasMultipleAccessingFunctions = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/globalstatus-h">GlobalStatus.h</a>.</p>

</div>
</div>

### IsCompared {#a793ea7e324427fc88ccdf62294b63fad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalStatus::IsCompared = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the global's address is used in a comparison.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/globalstatus-h">GlobalStatus.h</a>.</p>

</div>
</div>

### IsLoaded {#a0371d896aba2b285da63fca3b700b169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalStatus::IsLoaded = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the global is ever loaded.</p>


<p>If the global isn't ever loaded it can be deleted.</p>


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/globalstatus-h">GlobalStatus.h</a>.</p>

</div>
</div>

### NumStores {#a3a373858349bc2e52452b818cbe2bff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalStatus::NumStores = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of stores to the global.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/globalstatus-h">GlobalStatus.h</a>.</p>

</div>
</div>

### Ordering {#a1b1ce5881588fec97dfaaf3845b04640}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AtomicOrdering llvm::GlobalStatus::Ordering = <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">AtomicOrdering::NotAtomic</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set to the strongest atomic ordering requirement.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/globalstatus-h">GlobalStatus.h</a>.</p>

</div>
</div>

### StoredOnceStore {#a68be203655db8e678f567ff41e559500}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StoreInst* llvm::GlobalStatus::StoredOnceStore = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If only one value (besides the initializer constant) is ever stored to this global, keep track of what value it is via the store instruction.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/globalstatus-h">GlobalStatus.h</a>.</p>


<p>Referenced by <a href="#a878825b35bf0b197646751b36b74a2a1">getStoredOnceValue</a>.</p>

</div>
</div>

### StoredType {#a8661beacd5ed3a854cd3c98e565ee89e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::GlobalStatus::StoredType llvm::GlobalStatus::StoredType = <a href="#abe8cd5e07daf1b2bf532174823523ee7ae2ae8bccbba8e261ad5d71d3a84ce295">NotStored</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/globalstatus-h">GlobalStatus.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### analyzeGlobal() {#ae58ea7b3b03443e976cbef09ac25cf00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GlobalStatus::analyzeGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/structs/llvm/globalstatus">GlobalStatus</a> &amp; GS)</td>
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

<p>Look at all uses of the global and fill in the <a href="/web-llvm/docs/api/structs/llvm/globalstatus">GlobalStatus</a> structure.</p>


<p>If the global has its address taken, return true to indicate we can't do anything with it.</p>


<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/globalstatus-h">GlobalStatus.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/globalstatus-cpp">GlobalStatus.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/globalstatus-cpp/#a17a474b70329d911e0b4f13e552dc99f">analyzeGlobalAux</a> and <a href="#a66343ec7ee95f372f485d76945263189">GlobalStatus</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5cb8771722bfd8bcbdeb391b17e6cfd6">processGlobal</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/globalstatus-h">GlobalStatus.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/globalstatus-cpp">GlobalStatus.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
