---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ctx-profile/contextnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ContextNode` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ctx_profile::ContextNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">llvm/ProfileData/CtxInstrContextNode.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a157efc559fb2e3c1c9c7c03330101334">ContextNode</a> (GUID Guid, uint32_t NumCounters, uint32_t NumCallsites, ContextNode *Next=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a581474eba8e0b4ca6ccee5158bc630f1">counters</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1561406835140e308ad77f78511f470">counters_size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab60b840d0134f9e881904678f456aea9">callsites_size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9313b687764f4acba8c52f8cbe9d7157">counters</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ctx-profile/contextnode">ContextNode</a> **</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae421f46a3739f5e541b4f43ce8f4b834">subContexts</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ctx-profile/contextnode">ContextNode</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad13a6770d3b29080908d1d1e7c464720">subContexts</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/ctx-profile/#a6680521b81ea3a4c433750426966360b">GUID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d76c6185d4eb351b63806cabd33d34c">guid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ctx-profile/contextnode">ContextNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeddd2641c29fcacf4b71578863153740">next</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a068b5c183e562872d47a6875917d575b">size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4946f0771a6835bac5a46d077640e7aa">entrycount</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/ctx-profile/#a6680521b81ea3a4c433750426966360b">GUID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cec419a81c69eff7f0f9cc8f3c62669">Guid</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ctx-profile/contextnode">ContextNode</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98339c88abbb91cdda9bbb9d1ac0740a">Next</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a474977a67543e1e99da14e30dfb1a8">NumCounters</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19c35d6032e77be00ac2ff4a990fb19d">NumCallsites</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eec8d154d4aff4bda0f8aef9d5b74b3">getAllocSize</a> (uint32_t NumCounters, uint32_t NumCallsites)</td>
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


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ContextNode() {#a157efc559fb2e3c1c9c7c03330101334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ctx_profile::ContextNode::ContextNode (<a href="/web-llvm/docs/api/namespaces/llvm/ctx-profile/#a6680521b81ea3a4c433750426966360b">GUID</a> Guid, uint32_t NumCounters, uint32_t NumCallsites, <a href="/web-llvm/docs/api/classes/llvm/ctx-profile/contextnode">ContextNode</a> * Next=nullptr)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a>.</p>


<p>Reference <a href="#a157efc559fb2e3c1c9c7c03330101334">ContextNode</a>.</p>


<p>Referenced by <a href="#a157efc559fb2e3c1c9c7c03330101334">ContextNode</a>, <a href="#a581474eba8e0b4ca6ccee5158bc630f1">counters</a>, <a href="#a9313b687764f4acba8c52f8cbe9d7157">counters</a>, <a href="#a9eec8d154d4aff4bda0f8aef9d5b74b3">getAllocSize</a>, <a href="#aeddd2641c29fcacf4b71578863153740">next</a>, <a href="#ae421f46a3739f5e541b4f43ce8f4b834">subContexts</a> and <a href="#ad13a6770d3b29080908d1d1e7c464720">subContexts</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### callsites\_size() {#ab60b840d0134f9e881904678f456aea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ctx_profile::ContextNode::callsites_size ()</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a>.</p>

</div>
</div>

### counters() {#a581474eba8e0b4ca6ccee5158bc630f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t * llvm::ctx_profile::ContextNode::counters ()</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a>.</p>


<p>Reference <a href="#a157efc559fb2e3c1c9c7c03330101334">ContextNode</a>.</p>


<p>Referenced by <a href="#a9313b687764f4acba8c52f8cbe9d7157">counters</a>, <a href="#a4946f0771a6835bac5a46d077640e7aa">entrycount</a> and <a href="#ae421f46a3739f5e541b4f43ce8f4b834">subContexts</a>.</p>

</div>
</div>

### counters() {#a9313b687764f4acba8c52f8cbe9d7157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t * llvm::ctx_profile::ContextNode::counters ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a>.</p>


<p>References <a href="#a157efc559fb2e3c1c9c7c03330101334">ContextNode</a> and <a href="#a581474eba8e0b4ca6ccee5158bc630f1">counters</a>.</p>

</div>
</div>

### counters\_size() {#af1561406835140e308ad77f78511f470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ctx_profile::ContextNode::counters_size ()</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a>.</p>

</div>
</div>

### entrycount() {#a4946f0771a6835bac5a46d077640e7aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ctx_profile::ContextNode::entrycount ()</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a>.</p>


<p>Reference <a href="#a581474eba8e0b4ca6ccee5158bc630f1">counters</a>.</p>

</div>
</div>

### guid() {#a6d76c6185d4eb351b63806cabd33d34c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GUID llvm::ctx_profile::ContextNode::guid ()</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a>.</p>

</div>
</div>

### next() {#aeddd2641c29fcacf4b71578863153740}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextNode * llvm::ctx_profile::ContextNode::next ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a>.</p>


<p>Reference <a href="#a157efc559fb2e3c1c9c7c03330101334">ContextNode</a>.</p>

</div>
</div>

### size() {#a068b5c183e562872d47a6875917d575b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::ctx_profile::ContextNode::size ()</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a>.</p>


<p>Reference <a href="#a9eec8d154d4aff4bda0f8aef9d5b74b3">getAllocSize</a>.</p>

</div>
</div>

### subContexts() {#ae421f46a3739f5e541b4f43ce8f4b834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextNode ** llvm::ctx_profile::ContextNode::subContexts ()</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a>.</p>


<p>References <a href="#a157efc559fb2e3c1c9c7c03330101334">ContextNode</a> and <a href="#a581474eba8e0b4ca6ccee5158bc630f1">counters</a>.</p>


<p>Referenced by <a href="#ad13a6770d3b29080908d1d1e7c464720">subContexts</a>.</p>

</div>
</div>

### subContexts() {#ad13a6770d3b29080908d1d1e7c464720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextNode *const  * llvm::ctx_profile::ContextNode::subContexts ()</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a>.</p>


<p>References <a href="#a157efc559fb2e3c1c9c7c03330101334">ContextNode</a> and <a href="#ae421f46a3739f5e541b4f43ce8f4b834">subContexts</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Guid {#a3cec419a81c69eff7f0f9cc8f3c62669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GUID llvm::ctx_profile::ContextNode::Guid</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a>.</p>

</div>
</div>

### Next {#a98339c88abbb91cdda9bbb9d1ac0740a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextNode* const llvm::ctx_profile::ContextNode::Next</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a>.</p>

</div>
</div>

### NumCallsites {#a19c35d6032e77be00ac2ff4a990fb19d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t llvm::ctx_profile::ContextNode::NumCallsites</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a>.</p>

</div>
</div>

### NumCounters {#a8a474977a67543e1e99da14e30dfb1a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t llvm::ctx_profile::ContextNode::NumCounters</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getAllocSize() {#a9eec8d154d4aff4bda0f8aef9d5b74b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::ctx_profile::ContextNode::getAllocSize (uint32_t NumCounters, uint32_t NumCallsites)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a>.</p>


<p>Reference <a href="#a157efc559fb2e3c1c9c7c03330101334">ContextNode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-pgoctxprofwriter-cpp-/#af1c66a7958c747574e383ef19e15da4f">anonymous{PGOCtxProfWriter.cpp}::createNode</a> and <a href="#a068b5c183e562872d47a6875917d575b">size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/ctxinstrcontextnode-h">CtxInstrContextNode.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
