---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/valuehandlebase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ValueHandleBase` Class Reference

<p>This is the common base class of value handles. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ValueHandleBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">llvm/IR/ValueHandle.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callbackvh">CallbackVH</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> handle with callbacks on RAUW and destruction. <a href="/web-llvm/docs/api/classes/llvm/callbackvh/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> handle that is nullable, but tries to track the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/weakvh">WeakVH</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A nullable <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> handle that is nullable. <a href="/web-llvm/docs/api/classes/llvm/weakvh/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">HandleBaseKind { <a href="#ae2f1a12c55f1c06acc38407b8627cb4d">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This indicates what sub class the handle actually is. <a href="#ae2f1a12c55f1c06acc38407b8627cb4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8d2b8564e2beca5243e6ef39a59752f">ValueHandleBase</a> (HandleBaseKind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f768e9f3d874bbac10ab3f98d305507">ValueHandleBase</a> (HandleBaseKind Kind, Value *V)</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd6a51b0b16b598bc41a2b32c6d0030f">ValueHandleBase</a> (const ValueHandleBase &amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af03d30aea88e12f5d794b4c3283f56c2">ValueHandleBase</a> (HandleBaseKind Kind, const ValueHandleBase &amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a756237f2c258476c7f88cf1d86122043">~ValueHandleBase</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a700177b68c18b9e00893b747d3de1453">operator=</a> (Value *RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72628fe43298c0e48a0eaee5475730fc">operator=</a> (const ValueHandleBase &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b43bf5046acb7ccef33fd88485fd3ba">operator-&gt;</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10d9be2466488342a09467f530c2c914">operator*</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d6d2457c839e340266704440f3bb243">getValPtr</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a579078525e0d9c1ea200f908a95aa83a">RemoveFromUseList</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove this ValueHandle from its current use list. <a href="#a579078525e0d9c1ea200f908a95aa83a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9891c6c9a198a9c5c33608be4cd84782">clearValPtr</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the underlying pointer without clearing the use list. <a href="#a9891c6c9a198a9c5c33608be4cd84782">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae86fe94904f074626d0b0ae9e2255e25">setValPtr</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuehandlebase">ValueHandleBase</a> **</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98301d42ee56bc7a1a87b321fb43979f">getPrevPtr</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae2f1a12c55f1c06acc38407b8627cb4d">HandleBaseKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc8107b848252666215ec3f05c636f95">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ffa7f583cfb1c59ba3909eff9904d1e">setPrevPtr</a> (ValueHandleBase **Ptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80e1369ad793d973102200658765e81d">AddToExistingUseList</a> (ValueHandleBase **List)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add this ValueHandle to the use list for V. <a href="#a80e1369ad793d973102200658765e81d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa44c4ffe0363c7b27a4e5c6e7a9605b5">AddToExistingUseListAfter</a> (ValueHandleBase *Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add this ValueHandle to the use list after <a href="/web-llvm/docs/api/classes/node">Node</a>. <a href="#aa44c4ffe0363c7b27a4e5c6e7a9605b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4371858681846dcbf07ce54bb1973309">AddToUseList</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add this ValueHandle to the use list for V. <a href="#a4371858681846dcbf07ce54bb1973309">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase">ValueHandleBase</a> **, 2, <a href="#ae2f1a12c55f1c06acc38407b8627cb4d">HandleBaseKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4d5cb3a84fd8267b023ea4b1afddd3c">PrevPair</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuehandlebase">ValueHandleBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab285f77e2bc21f4f27bcfd021b6858a7">Next</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a243dda0eaa2d0a7c343ce333cad9b4ea">Val</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92d8c2f0a2622bca7ff24f02790c3f31">ValueIsDeleted</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb87e6d5ed7ded2ccd8acac49caf22ab">ValueIsRAUWd</a> (Value *Old, Value *New)</td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a567c4f57a2f3aaeb6daee72ec39fb073">isValid</a> (Value *V)</td>
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

<p>This is the common base class of value handles.</p>


<p>ValueHandle's are smart pointers to <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>'s that have special behavior when the value is deleted or ReplaceAllUsesWith'd. See the specific handles below for details.</p>


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### HandleBaseKind {#ae2f1a12c55f1c06acc38407b8627cb4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ValueHandleBase::HandleBaseKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This indicates what sub class the handle actually is.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Assert<a id="ae2f1a12c55f1c06acc38407b8627cb4da4d4e25f8ba89be14c9c2d60082bb7516"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Callback<a id="ae2f1a12c55f1c06acc38407b8627cb4da670860d51b165a2d146356622a256418"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Weak<a id="ae2f1a12c55f1c06acc38407b8627cb4da3c970eedf4f533d381b99e2b5c73ad77"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WeakTracking<a id="ae2f1a12c55f1c06acc38407b8627cb4dad057ff89faba8a9c0566aabcbf3f8fce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>This is to avoid having a vtable for the light-weight handle pointers. The fully general Callback version does have a vtable.</p>


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### Value {#aeceedf6e1a7d48a588516ce2b1983d6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/value">Value</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>Reference <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmprinter-cpp-/addrlabelmapcallbackptr/#ab40a1ce088eaee128432e229340ed971">anonymous{AsmPrinter.cpp}::AddrLabelMapCallbackPtr::AddrLabelMapCallbackPtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmprinter-cpp-/addrlabelmapcallbackptr/#aaa4817c4af6d9fbb40742edcb6ff0bbc">anonymous{AsmPrinter.cpp}::AddrLabelMapCallbackPtr::allUsesReplacedWith</a>, <a href="/web-llvm/docs/api/structs/anonymous-lazyvalueinfo-cpp-/lvivaluehandle/#a1e2c302e5be1c52548682f51a085b972">anonymous{LazyValueInfo.cpp}::LVIValueHandle::allUsesReplacedWith</a>, <a href="/web-llvm/docs/api/classes/llvm/callbackvh/#a1f633ad5396b6726039d26f5bbac940d">llvm::CallbackVH::allUsesReplacedWith</a>, <a href="/web-llvm/docs/api/structs/llvm/preservedcfgcheckerinstrumentation/bbguard/#aaafe4931c1319404db21c79560795b4b">llvm::PreservedCFGCheckerInstrumentation::BBGuard::allUsesReplacedWith</a>, <a href="/web-llvm/docs/api/classes/llvm/callbackvh/#a3388197aa4f644d4e871c763b59875af">llvm::CallbackVH::CallbackVH</a>, <a href="/web-llvm/docs/api/classes/llvm/callbackvh/#a5ec3602ff26e2f61e14a777a511fbf11">llvm::CallbackVH::CallbackVH</a>, <a href="#a7d6d2457c839e340266704440f3bb243">getValPtr</a>, <a href="#a567c4f57a2f3aaeb6daee72ec39fb073">isValid</a>, <a href="/web-llvm/docs/api/structs/anonymous-lazyvalueinfo-cpp-/lvivaluehandle/#a3b44d2c9f51a87067e4839084626bb06">anonymous{LazyValueInfo.cpp}::LVIValueHandle::LVIValueHandle</a>, <a href="/web-llvm/docs/api/classes/llvm/callbackvh/#a3cc26426e370328a52e00ddb75a0dfbd">llvm::CallbackVH::operator Value *</a>, <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh/#a8002fceeab805b1789ea1feae48cd640">llvm::WeakTrackingVH::operator Value *</a>, <a href="/web-llvm/docs/api/classes/llvm/weakvh/#a3c49cdae7ce889f3126e047b81ad7bee">llvm::WeakVH::operator Value *</a>, <a href="#a10d9be2466488342a09467f530c2c914">operator*</a>, <a href="#a6b43bf5046acb7ccef33fd88485fd3ba">operator-&gt;</a>, <a href="#a72628fe43298c0e48a0eaee5475730fc">operator=</a>, <a href="#a700177b68c18b9e00893b747d3de1453">operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh/#a6a95341d529e6347a7a48294d548ca77">llvm::WeakTrackingVH::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh/#a80b586f93a1a0fd3328324b19db83ab3">llvm::WeakTrackingVH::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/weakvh/#a9ab87f5dbdcfddbcf7f89dd968affcd8">llvm::WeakVH::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/weakvh/#af79a6674a38f02a9a6852e7105654980">llvm::WeakVH::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/callbackvh/#ab3a25e82043f8a99ad6ed61fb9c9483c">llvm::CallbackVH::setValPtr</a>, <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>, <a href="#a1f768e9f3d874bbac10ab3f98d305507">ValueHandleBase</a>, <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh/#a421d63a2896eceee540facd015e92bfa">llvm::WeakTrackingVH::WeakTrackingVH</a> and <a href="/web-llvm/docs/api/classes/llvm/weakvh/#a2121b8e4d72b2a1d68ffc347eb66395c">llvm::WeakVH::WeakVH</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ValueHandleBase() {#ab8d2b8564e2beca5243e6ef39a59752f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueHandleBase::ValueHandleBase (<a href="#ae2f1a12c55f1c06acc38407b8627cb4d">HandleBaseKind</a> Kind)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>

</div>
</div>

### ValueHandleBase() {#a1f768e9f3d874bbac10ab3f98d305507}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueHandleBase::ValueHandleBase (<a href="#ae2f1a12c55f1c06acc38407b8627cb4d">HandleBaseKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="#a7d6d2457c839e340266704440f3bb243">getValPtr</a>, <a href="#a567c4f57a2f3aaeb6daee72ec39fb073">isValid</a> and <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### ValueHandleBase() {#afd6a51b0b16b598bc41a2b32c6d0030f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueHandleBase::ValueHandleBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase">ValueHandleBase</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#afd6a51b0b16b598bc41a2b32c6d0030f">ValueHandleBase</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callbackvh/#a8b64e4dd7471ef330b74ec0d5f112e29">llvm::CallbackVH::CallbackVH</a>, <a href="/web-llvm/docs/api/classes/llvm/callbackvh/#a5ec3602ff26e2f61e14a777a511fbf11">llvm::CallbackVH::CallbackVH</a>, <a href="#a72628fe43298c0e48a0eaee5475730fc">operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh/#a6a95341d529e6347a7a48294d548ca77">llvm::WeakTrackingVH::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/weakvh/#a9ab87f5dbdcfddbcf7f89dd968affcd8">llvm::WeakVH::operator=</a>, <a href="#afd6a51b0b16b598bc41a2b32c6d0030f">ValueHandleBase</a>, <a href="#af03d30aea88e12f5d794b4c3283f56c2">ValueHandleBase</a>, <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh/#a27d4a282d9ddbd93893e1ada30288b53">llvm::WeakTrackingVH::WeakTrackingVH</a>, <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh/#a4f01a47cccf213d6f8cb9589bbb47ca1">llvm::WeakTrackingVH::WeakTrackingVH</a>, <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh/#a421d63a2896eceee540facd015e92bfa">llvm::WeakTrackingVH::WeakTrackingVH</a>, <a href="/web-llvm/docs/api/classes/llvm/weakvh/#a83fa1665a8e540abe92497e0bb8b5ea9">llvm::WeakVH::WeakVH</a>, <a href="/web-llvm/docs/api/classes/llvm/weakvh/#a2ccc76585513b1836598518e5afd0540">llvm::WeakVH::WeakVH</a> and <a href="/web-llvm/docs/api/classes/llvm/weakvh/#a2121b8e4d72b2a1d68ffc347eb66395c">llvm::WeakVH::WeakVH</a>.</p>

</div>
</div>

### ValueHandleBase() {#af03d30aea88e12f5d794b4c3283f56c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueHandleBase::ValueHandleBase (<a href="#ae2f1a12c55f1c06acc38407b8627cb4d">HandleBaseKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase">ValueHandleBase</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="#a7d6d2457c839e340266704440f3bb243">getValPtr</a>, <a href="#a567c4f57a2f3aaeb6daee72ec39fb073">isValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#afd6a51b0b16b598bc41a2b32c6d0030f">ValueHandleBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ValueHandleBase() {#a756237f2c258476c7f88cf1d86122043}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueHandleBase::~ValueHandleBase ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="#a7d6d2457c839e340266704440f3bb243">getValPtr</a>, <a href="#a567c4f57a2f3aaeb6daee72ec39fb073">isValid</a> and <a href="#a579078525e0d9c1ea200f908a95aa83a">RemoveFromUseList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator-&gt;() {#a6b43bf5046acb7ccef33fd88485fd3ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::ValueHandleBase::operator-&gt; ()</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="#a7d6d2457c839e340266704440f3bb243">getValPtr</a> and <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>

</div>
</div>

### operator\*() {#a10d9be2466488342a09467f530c2c914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value &amp; llvm::ValueHandleBase::operator* ()</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7d6d2457c839e340266704440f3bb243">getValPtr</a> and <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>

</div>
</div>

### operator=() {#a700177b68c18b9e00893b747d3de1453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::ValueHandleBase::operator= (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="#a7d6d2457c839e340266704440f3bb243">getValPtr</a>, <a href="#a567c4f57a2f3aaeb6daee72ec39fb073">isValid</a>, <a href="#a579078525e0d9c1ea200f908a95aa83a">RemoveFromUseList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh/#a6a95341d529e6347a7a48294d548ca77">llvm::WeakTrackingVH::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh/#a80b586f93a1a0fd3328324b19db83ab3">llvm::WeakTrackingVH::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/weakvh/#a9ab87f5dbdcfddbcf7f89dd968affcd8">llvm::WeakVH::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/weakvh/#af79a6674a38f02a9a6852e7105654980">llvm::WeakVH::operator=</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmprinter-cpp-/addrlabelmapcallbackptr/#aca27838656388a449b8708915d347bdd">anonymous{AsmPrinter.cpp}::AddrLabelMapCallbackPtr::setPtr</a> and <a href="/web-llvm/docs/api/classes/llvm/callbackvh/#ab3a25e82043f8a99ad6ed61fb9c9483c">llvm::CallbackVH::setValPtr</a>.</p>

</div>
</div>

### operator=() {#a72628fe43298c0e48a0eaee5475730fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::ValueHandleBase::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase">ValueHandleBase</a> &amp; RHS)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="#a7d6d2457c839e340266704440f3bb243">getValPtr</a>, <a href="#a567c4f57a2f3aaeb6daee72ec39fb073">isValid</a>, <a href="#a579078525e0d9c1ea200f908a95aa83a">RemoveFromUseList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a> and <a href="#afd6a51b0b16b598bc41a2b32c6d0030f">ValueHandleBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### clearValPtr() {#a9891c6c9a198a9c5c33608be4cd84782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ValueHandleBase::clearValPtr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear the underlying pointer without clearing the use list.</p>


<p>This should only be used if a derived class has manually removed the handle from the use list.</p>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>

</div>
</div>

### getValPtr() {#a7d6d2457c839e340266704440f3bb243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::ValueHandleBase::getValPtr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>Reference <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmprinter-cpp-/addrlabelmapcallbackptr/#aaa4817c4af6d9fbb40742edcb6ff0bbc">anonymous{AsmPrinter.cpp}::AddrLabelMapCallbackPtr::allUsesReplacedWith</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmprinter-cpp-/addrlabelmapcallbackptr/#af256aa973d5eade6bb3391dea1d4d951">anonymous{AsmPrinter.cpp}::AddrLabelMapCallbackPtr::deleted</a>, <a href="/web-llvm/docs/api/classes/llvm/bfi-detail/bficallbackvh-49ff4c89ffda7f9a22c66676f1ddc8f8/#a399fe6c055fa8053a5302a00cd29f8f1">llvm::bfi_detail::BFICallbackVH&lt; BasicBlock, BFIImplT &gt;::deleted</a>, <a href="/web-llvm/docs/api/classes/llvm/scevunknown/#a94abfc169f1ff22a179d219f781fcc94">llvm::SCEVUnknown::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse/#a1bc04591d1d6420a7fdbc15a4c5f0e31">llvm::IVStrideUse::getUser</a>, <a href="/web-llvm/docs/api/classes/llvm/scevunknown/#a9528d1498a3a1b2f06800cabc45a7f42">llvm::SCEVUnknown::getValue</a>, <a href="/web-llvm/docs/api/structs/llvm/preservedcfgcheckerinstrumentation/bbguard/#a805e72b57540d3677706b90ffef478a5">llvm::PreservedCFGCheckerInstrumentation::BBGuard::isPoisoned</a>, <a href="/web-llvm/docs/api/classes/llvm/callbackvh/#a3cc26426e370328a52e00ddb75a0dfbd">llvm::CallbackVH::operator Value *</a>, <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh/#a8002fceeab805b1789ea1feae48cd640">llvm::WeakTrackingVH::operator Value *</a>, <a href="/web-llvm/docs/api/classes/llvm/weakvh/#a3c49cdae7ce889f3126e047b81ad7bee">llvm::WeakVH::operator Value *</a>, <a href="#a10d9be2466488342a09467f530c2c914">operator*</a>, <a href="#a6b43bf5046acb7ccef33fd88485fd3ba">operator-&gt;</a>, <a href="#a72628fe43298c0e48a0eaee5475730fc">operator=</a>, <a href="#a700177b68c18b9e00893b747d3de1453">operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh/#aed2f94ba7ecd4983f2c811f0d01f1398">llvm::WeakTrackingVH::pointsToAliveValue</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemapcallbackvh/#a1b6c5945f932c835ec27c368ef5e4cc7">llvm::ValueMapCallbackVH&lt; KeyT, ValueT, Config &gt;::Unwrap</a>, <a href="#af03d30aea88e12f5d794b4c3283f56c2">ValueHandleBase</a>, <a href="#a1f768e9f3d874bbac10ab3f98d305507">ValueHandleBase</a> and <a href="#a756237f2c258476c7f88cf1d86122043">~ValueHandleBase</a>.</p>

</div>
</div>

### RemoveFromUseList() {#a579078525e0d9c1ea200f908a95aa83a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueHandleBase::RemoveFromUseList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove this ValueHandle from its current use list.</p>

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>, definition at line 1176 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="#a72628fe43298c0e48a0eaee5475730fc">operator=</a>, <a href="#a700177b68c18b9e00893b747d3de1453">operator=</a> and <a href="#a756237f2c258476c7f88cf1d86122043">~ValueHandleBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AddToExistingUseList() {#a80e1369ad793d973102200658765e81d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueHandleBase::AddToExistingUseList (<a href="/web-llvm/docs/api/classes/llvm/valuehandlebase">ValueHandleBase</a> ** List)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add this ValueHandle to the use list for V.</p>


<p>List is the address of either the head of the list or a Next node within the existing use list.</p>


<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>, definition at line 1110 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### AddToExistingUseListAfter() {#aa44c4ffe0363c7b27a4e5c6e7a9605b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueHandleBase::AddToExistingUseListAfter (<a href="/web-llvm/docs/api/classes/llvm/valuehandlebase">ValueHandleBase</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add this ValueHandle to the use list after <a href="/web-llvm/docs/api/classes/node">Node</a>.</p>

<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>, definition at line 1123 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### AddToUseList() {#a4371858681846dcbf07ce54bb1973309}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueHandleBase::AddToUseList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add this ValueHandle to the use list for V.</p>

<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>, definition at line 1133 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### getKind() {#acc8107b848252666215ec3f05c636f95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HandleBaseKind llvm::ValueHandleBase::getKind ()</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>

</div>
</div>

### getPrevPtr() {#a98301d42ee56bc7a1a87b321fb43979f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueHandleBase ** llvm::ValueHandleBase::getPrevPtr ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>

</div>
</div>

### setPrevPtr() {#a9ffa7f583cfb1c59ba3909eff9904d1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ValueHandleBase::setPrevPtr (<a href="/web-llvm/docs/api/classes/llvm/valuehandlebase">ValueHandleBase</a> ** Ptr)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>

</div>
</div>

### setValPtr() {#ae86fe94904f074626d0b0ae9e2255e25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ValueHandleBase::setValPtr (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Next {#ab285f77e2bc21f4f27bcfd021b6858a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueHandleBase* llvm::ValueHandleBase::Next = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>

</div>
</div>

### PrevPair {#af4d5cb3a84fd8267b023ea4b1afddd3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerIntPair&lt;ValueHandleBase**, 2, HandleBaseKind&gt; llvm::ValueHandleBase::PrevPair</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>

</div>
</div>

### Val {#a243dda0eaa2d0a7c343ce333cad9b4ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::ValueHandleBase::Val = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### ValueIsDeleted() {#a92d8c2f0a2622bca7ff24f02790c3f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueHandleBase::ValueIsDeleted (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>, definition at line 1202 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### ValueIsRAUWd() {#abb87e6d5ed7ded2ccd8acac49caf22ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueHandleBase::ValueIsRAUWd (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * New)</td>
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



<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>, definition at line 1255 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#abcf78af37d56a9b72a49c65428210758">llvm::MemorySSAUpdater::removeMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterbulk/#a60fac14032181eef9fe2f3e790ce9c28">llvm::SSAUpdaterBulk::RewriteAllUses</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyreftypemem2local-cpp-/webassemblyreftypemem2local/#a9ad64c3f2f8f51ff7edc41ed024e022b">anonymous{WebAssemblyRefTypeMem2Local.cpp}::WebAssemblyRefTypeMem2Local::visitAllocaInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### isValid() {#a567c4f57a2f3aaeb6daee72ec39fb073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueHandleBase::isValid (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a1423601a8e4ec304e0756df4e761ebbb">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a9571e26b946751eaf015a9b8dc508be9">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getTombstoneKey</a> and <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>


<p>Referenced by <a href="#a72628fe43298c0e48a0eaee5475730fc">operator=</a>, <a href="#a700177b68c18b9e00893b747d3de1453">operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh/#aed2f94ba7ecd4983f2c811f0d01f1398">llvm::WeakTrackingVH::pointsToAliveValue</a>, <a href="#af03d30aea88e12f5d794b4c3283f56c2">ValueHandleBase</a>, <a href="#a1f768e9f3d874bbac10ab3f98d305507">ValueHandleBase</a> and <a href="#a756237f2c258476c7f88cf1d86122043">~ValueHandleBase</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
