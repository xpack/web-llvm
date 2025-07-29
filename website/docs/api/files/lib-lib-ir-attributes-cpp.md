---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/ir/attributes-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `Attributes.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">llvm/ADT/FoldingSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">llvm/IR/AttributeMask.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">llvm/IR/ConstantRange.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">llvm/IR/ConstantRangeList.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">llvm/IR/Operator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">llvm/Support/ModRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;limits&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
#include &lt;tuple&gt;
#include &lt;utility&gt;
#include "llvm/IR/Attributes.inc"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/attributecomparator">AttributeComparator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> comparator that only compares attribute keys. <a href="/web-llvm/docs/api/structs/attributecomparator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/enumattr">EnumAttr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/strboolattr">StrBoolAttr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AttributeProperty { <a href="#a50b54203d53a07641d04250d2a7f039d">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84f56e05a576b94b89af30ba313805c4">packAllocSizeArgs</a> (unsigned ElemSizeArg, const std::optional&lt; unsigned &gt; &amp;NumElemsArg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; unsigned, std::optional&lt; unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab67846129bc1b313c0a7606f285f2168">unpackAllocSizeArgs</a> (uint64_t Num)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a8cb941feb6e29b5089568ab1dc2044">packVScaleRangeArgs</a> (unsigned MinValue, std::optional&lt; unsigned &gt; MaxValue)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; unsigned, std::optional&lt; unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44f5f98b926132d88f0211642cc9dcb2">unpackVScaleRangeArgs</a> (uint64_t Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af852b70a5b417dc2dc05caf87caf9457">getModRefStr</a> (ModRefInfo MR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf44a46eb7c1e76ca4614ffae1f4262a">getAttributeProperties</a> (Attribute::AttrKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ac4e7c6dca400b4cbcf176dc94ca0d">hasAttributeProperty</a> (Attribute::AttrKind Kind, AttributeProperty Prop)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c5fbaf034ddf1c9e224c2399990a280">hasIntersectProperty</a> (Attribute::AttrKind Kind, AttributeProperty Prop)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cee1ad5adf2690eb7b15f3f5a71dee5">attrIdxToArrayIdx</a> (unsigned Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> index to the internal array index. <a href="#a9cee1ad5adf2690eb7b15f3f5a71dee5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename K&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a050caf901311dc932e97973d70d17916">addAttributeImpl</a> (SmallVectorImpl&lt; Attribute &gt; &amp;Attrs, K Kind, Attribute Attr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0220f9335f0692044178f634eae8152">denormModeCompatible</a> (DenormalMode CallerMode, DenormalMode CalleeMode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callees with dynamic denormal modes are compatible with any caller mode. <a href="#aa0220f9335f0692044178f634eae8152">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7b23abced1fe9fc0068f73a3cb35c89">checkDenormMode</a> (const Function &amp;Caller, const Function &amp;Callee)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a789e293480556a1764b31e4f9ebd813d">checkStrictFP</a> (const Function &amp;Caller, const Function &amp;Callee)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AttrClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a12f59da641309f7afb7b1d32cb59a7bf">isEqual</a> (const Function &amp;Caller, const Function &amp;Callee)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95e1b2e589c826da6f6bd25ab050e0ad">isEqual</a> (const Function &amp;Caller, const Function &amp;Callee, const StringRef &amp;AttrName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AttrClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a384a442d2146a5a6faab695abbaa6676">setAND</a> (Function &amp;Caller, const Function &amp;Callee)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the logical AND of the attributes of the caller and the callee. <a href="#a384a442d2146a5a6faab695abbaa6676">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AttrClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae83cb1660469243aaf6aff42b7970b25">setOR</a> (Function &amp;Caller, const Function &amp;Callee)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the logical OR of the attributes of the caller and the callee. <a href="#ae83cb1660469243aaf6aff42b7970b25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68a3391f6fe564a33343e43587478592">adjustCallerSSPLevel</a> (Function &amp;Caller, const Function &amp;Callee)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the inlined function had a higher stack protection level than the calling function, then bump up the caller's stack protection level. <a href="#a68a3391f6fe564a33343e43587478592">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f16a0ff0435cf98879eef2066e5a4df">adjustCallerStackProbes</a> (Function &amp;Caller, const Function &amp;Callee)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the inlined function required stack probes, then ensure that the calling function has those too. <a href="#a3f16a0ff0435cf98879eef2066e5a4df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5861f2cf66ad90de99ef9dfe8054f75d">adjustCallerStackProbeSize</a> (Function &amp;Caller, const Function &amp;Callee)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the inlined function defines the size of guard region on the stack, then ensure that the calling function defines a guard region that is no larger. <a href="#a5861f2cf66ad90de99ef9dfe8054f75d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4edf7cbc1ca95769993535d584f66a3f">adjustMinLegalVectorWidth</a> (Function &amp;Caller, const Function &amp;Callee)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the inlined function defines a min legal vector width, then ensure the calling function has the same or larger min legal vector width. <a href="#a4edf7cbc1ca95769993535d584f66a3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa177e0690d977e4dfeafd4fea087f613">adjustNullPointerValidAttr</a> (Function &amp;Caller, const Function &amp;Callee)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the inlined function has null_pointer_is_valid attribute, set this attribute in the caller post inlining. <a href="#aa177e0690d977e4dfeafd4fea087f613">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab120e0d08d1d90a92f27558a82005dcb">AllocSizeNumElemsNotPresent</a> = -1</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba63655d8ee18e876fc5cee12bbaa35e">GET_ATTR_NAMES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac52fd56f4583e0aed1c9b900c3ac98c4">ATTRIBUTE_ENUM</a>(ENUM_NAME, DISPLAY_NAME)&nbsp;&nbsp;&nbsp;  .Case(#DISPLAY_NAME, Attribute::ENUM_NAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a071d47a02c0ca8b57596eea81c5bdee2">GET_ATTR_NAMES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c9483392aa0cf508b9ac300b9e550a4">ATTRIBUTE_ENUM</a>(ENUM_NAME, DISPLAY_NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b41e24f10b13f0f51727234d0c698a7">GET_ATTR_NAMES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a560892ae9e12e82290c046b8e86e7d30">ATTRIBUTE_ALL</a>(ENUM_NAME, DISPLAY_NAME)&nbsp;&nbsp;&nbsp;.Case(#DISPLAY_NAME, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b5e7e3091defeb441ea56e24188e634">GET_ATTR_PROP_TABLE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac21254daccb964b2506c5c068058190e">GET_ATTR_NAMES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9102fc703447e36f0fc9a9c14e52de7">ATTRIBUTE_ENUM</a>(ENUM_NAME, DISPLAY_NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac714438f966ac34421b4ef3cffe04b1b">ATTRIBUTE_STRBOOL</a>(ENUM_NAME, DISPLAY_NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b6abfc8405f6f997d276b4d21b95cec">GET_ATTR_COMPAT_FUNC</a></td>
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

## Enumerations

### AttributeProperty {#a50b54203d53a07641d04250d2a7f039d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum AttributeProperty </td>
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
<td class="doxyEnumItemName">FnAttr<a id="a50b54203d53a07641d04250d2a7f039dadd899aa9755b6823dea0f942ee1ba150"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 0))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ParamAttr<a id="a50b54203d53a07641d04250d2a7f039dad5a6337c700ccb13f576dee2034aa5ea"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 1))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RetAttr<a id="a50b54203d53a07641d04250d2a7f039da19331ed2fb57db290a26f2869bae2f45"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 2))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IntersectPreserve<a id="a50b54203d53a07641d04250d2a7f039da8fed3b85e5feb06ed9845023fd4e6943"></a></td>
<td class="doxyEnumItemDescription"> (= (0 &lt;&lt; 3))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IntersectAnd<a id="a50b54203d53a07641d04250d2a7f039daf650824d160fd62add79797968edd3d9"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 3))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IntersectMin<a id="a50b54203d53a07641d04250d2a7f039daab253a0d03a4a41f574be7a4ed6ed51d"></a></td>
<td class="doxyEnumItemDescription"> (= (2 &lt;&lt; 3))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IntersectCustom<a id="a50b54203d53a07641d04250d2a7f039dacb175e20be6509f68d603623035fab53"></a></td>
<td class="doxyEnumItemDescription"> (= (3 &lt;&lt; 3))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IntersectPropertyMask<a id="a50b54203d53a07641d04250d2a7f039dae6d6f1f1528252e429da2aa5b1d5a996"></a></td>
<td class="doxyEnumItemDescription"> (= (3 &lt;&lt; 3))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 749 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### addAttributeImpl() {#a050caf901311dc932e97973d70d17916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename K&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addAttributeImpl (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> &gt; &amp; Attrs, K Kind, <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Attr)</td>
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



<p>Definition at line 2091 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a7464f6980d299143f57a229f73181c39">llvm::AttrBuilder::addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a59d23ba2e7eac46cbc6cd3086e013b49">llvm::AttrBuilder::addAttribute</a> and <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a1df399b697ebab2755c841d66350778f">llvm::AttrBuilder::addAttribute</a>.</p>

</div>
</div>

### adjustCallerSSPLevel() {#a68a3391f6fe564a33343e43587478592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjustCallerSSPLevel (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee)</td>
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

<p>If the inlined function had a higher stack protection level than the calling function, then bump up the caller's stack protection level.</p>

<p>Definition at line 2505 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/attributemask/#a86730a1a0c270eb9b066301bfaac8581">llvm::AttributeMask::addAttribute</a>.</p>

</div>
</div>

### adjustCallerStackProbes() {#a3f16a0ff0435cf98879eef2066e5a4df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjustCallerStackProbes (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee)</td>
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

<p>If the inlined function required stack probes, then ensure that the calling function has those too.</p>

<p>Definition at line 2535 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### adjustCallerStackProbeSize() {#a5861f2cf66ad90de99ef9dfe8054f75d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjustCallerStackProbeSize (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee)</td>
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

<p>If the inlined function defines the size of guard region on the stack, then ensure that the calling function defines a guard region that is no larger.</p>

<p>Definition at line 2546 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">llvm::StringRef::getAsInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a968930aea9d9efa8d46dd890fce75643">llvm::Attribute::getValueAsString</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>.</p>

</div>
</div>

### adjustMinLegalVectorWidth() {#a4edf7cbc1ca95769993535d584f66a3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjustMinLegalVectorWidth (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee)</td>
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

<p>If the inlined function defines a min legal vector width, then ensure the calling function has the same or larger min legal vector width.</p>


<p>If the caller has the attribute, but the callee doesn't, we need to remove the attribute from the caller since we can't make any guarantees about the caller's requirements. This function is called after the inlining decision has been made so we have to merge the attribute this way. Heuristics that would use min-legal-vector-width to determine inline compatibility would need to be handled as part of inline cost analysis.</p>


<p>Definition at line 2574 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">llvm::StringRef::getAsInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a968930aea9d9efa8d46dd890fce75643">llvm::Attribute::getValueAsString</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>.</p>

</div>
</div>

### adjustNullPointerValidAttr() {#aa177e0690d977e4dfeafd4fea087f613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjustNullPointerValidAttr (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee)</td>
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

<p>If the inlined function has null_pointer_is_valid attribute, set this attribute in the caller post inlining.</p>

<p>Definition at line 2595 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### attrIdxToArrayIdx() {#a9cee1ad5adf2690eb7b15f3f5a71dee5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned attrIdxToArrayIdx (unsigned Index)</td>
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

<p>Map from <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> index to the internal array index.</p>


<p>Adding one happens to work, because -1 wraps around to 0.</p>


<p>Definition at line 1410 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a3f1e8df5d1ec58e81979760331f7808e">llvm::AttributeList::addParamAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelistimpl/#a6f9b9f798d2c70c515f146562de005b1">llvm::AttributeListImpl::AttributeListImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#aa0934a03f7182abfbf5e57fc4e7c7c82">llvm::AttributeList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#acf23368370765012fba0a78c1b42fdf9">llvm::AttributeList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ac8d6f220fcf8f327c6c739813df8c4c9">llvm::AttributeList::getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ad2077a29ae8c3a0a7afe3bd0345f8738">llvm::AttributeList::removeAttributesAtIndex</a>.</p>

</div>
</div>

### checkDenormMode() {#ab7b23abced1fe9fc0068f73a3cb35c89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkDenormMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee)</td>
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



<p>Definition at line 2444 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#aa0220f9335f0692044178f634eae8152">denormModeCompatible</a> and <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a7326cc28954855133bd6efba8aa9724a">llvm::DenormalMode::getInvalid</a>.</p>

</div>
</div>

### checkStrictFP() {#a789e293480556a1764b31e4f9ebd813d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkStrictFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee)</td>
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



<p>Definition at line 2461 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### denormModeCompatible() {#aa0220f9335f0692044178f634eae8152}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool denormModeCompatible (<a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a> CallerMode, <a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a> CalleeMode)</td>
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

<p>Callees with dynamic denormal modes are compatible with any caller mode.</p>

<p>Definition at line 2427 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a29b26e3ae30f3f6ec4106ff181282893ab6083e266013055b6c2ef85b1e47444c">llvm::DenormalMode::Dynamic</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#af51395b84b8db9baa750e7b9210eebb2">llvm::DenormalMode::getDynamic</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a1b79f1995991b0a757a4d04969c3717f">llvm::DenormalMode::Input</a> and <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#aa1be940c9e7d0c7ed20dfdaf5731b082">llvm::DenormalMode::Output</a>.</p>


<p>Referenced by <a href="#ab7b23abced1fe9fc0068f73a3cb35c89">checkDenormMode</a>.</p>

</div>
</div>

### getAttributeProperties() {#abf44a46eb7c1e76ca4614ffae1f4262a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getAttributeProperties (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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



<p>Definition at line 763 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#af6ac4e7c6dca400b4cbcf176dc94ca0d">hasAttributeProperty</a> and <a href="#a9c5fbaf034ddf1c9e224c2399990a280">hasIntersectProperty</a>.</p>

</div>
</div>

### getModRefStr() {#af852b70a5b417dc2dc05caf87caf9457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getModRefStr (<a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> MR)</td>
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



<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea6524b183b5cd0850f2cff6d30d581af9">llvm::ModRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ead974636fce6d12e72054e61fb3c1e9a8">llvm::NoModRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attribute/#a493e72ce53ee16d92489ba67d7ce2bb0">llvm::Attribute::getAsString</a>.</p>

</div>
</div>

### hasAttributeProperty() {#af6ac4e7c6dca400b4cbcf176dc94ca0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasAttributeProperty (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind, <a href="#a50b54203d53a07641d04250d2a7f039d">AttributeProperty</a> Prop)</td>
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



<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="#abf44a46eb7c1e76ca4614ffae1f4262a">getAttributeProperties</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attribute/#aa1d1daaf72feb4d1ecb59df592bdc3d7">llvm::Attribute::canUseAsFnAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#ade0ea4e187f04c1339866dab77cb7181">llvm::Attribute::canUseAsParamAttr</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#a44151f9f498f20ce0aa95010c25fd2d4">llvm::Attribute::canUseAsRetAttr</a>.</p>

</div>
</div>

### hasIntersectProperty() {#a9c5fbaf034ddf1c9e224c2399990a280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasIntersectProperty (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind, <a href="#a50b54203d53a07641d04250d2a7f039d">AttributeProperty</a> Prop)</td>
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



<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abf44a46eb7c1e76ca4614ffae1f4262a">getAttributeProperties</a>, <a href="#a50b54203d53a07641d04250d2a7f039daf650824d160fd62add79797968edd3d9">IntersectAnd</a>, <a href="#a50b54203d53a07641d04250d2a7f039dacb175e20be6509f68d603623035fab53">IntersectCustom</a>, <a href="#a50b54203d53a07641d04250d2a7f039daab253a0d03a4a41f574be7a4ed6ed51d">IntersectMin</a>, <a href="#a50b54203d53a07641d04250d2a7f039da8fed3b85e5feb06ed9845023fd4e6943">IntersectPreserve</a> and <a href="#a50b54203d53a07641d04250d2a7f039dae6d6f1f1528252e429da2aa5b1d5a996">IntersectPropertyMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attribute/#af3b008eee2735671b4bfdabd4df07b35">llvm::Attribute::intersectMustPreserve</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aa586fffdd286955ca876838f11a5f6d3">llvm::Attribute::intersectWithAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a11f48b3f20c58e11564df402e02a1592">llvm::Attribute::intersectWithCustom</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#a3d708ef8b38a269452e88f7c0fcfa5f8">llvm::Attribute::intersectWithMin</a>.</p>

</div>
</div>

### isEqual() {#a12f59da641309f7afb7b1d32cb59a7bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AttrClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isEqual (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee)</td>
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



<p>Definition at line 2469 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab880924a451b73edfe368d53c3d8631c">EliminateDuplicatePHINodesSetBasedImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0af4594038f5cb46e7a4c86713520c95">markAliveBlocks</a>.</p>

</div>
</div>

### isEqual() {#a95e1b2e589c826da6f6bd25ab050e0ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isEqual (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; AttrName)</td>
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



<p>Definition at line 2474 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### packAllocSizeArgs() {#a84f56e05a576b94b89af30ba313805c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t packAllocSizeArgs (unsigned ElemSizeArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; unsigned &gt; &amp; NumElemsArg)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#ab120e0d08d1d90a92f27558a82005dcb">AllocSizeNumElemsNotPresent</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#adea27caeeec5d68cef4a452b8cc25162">llvm::AttrBuilder::addAllocSizeAttr</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#a6f90f8b9a9209911cdd0573c4e25388e">llvm::Attribute::getWithAllocSizeArgs</a>.</p>

</div>
</div>

### packVScaleRangeArgs() {#a9a8cb941feb6e29b5089568ab1dc2044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t packVScaleRangeArgs (unsigned MinValue, std::optional&lt; unsigned &gt; MaxValue)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a4566311f748debbde7053963d802d87e">llvm::AttrBuilder::addVScaleRangeAttr</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#a7b20ebfa9bcf271438ffda63f623d0f5">llvm::Attribute::getWithVScaleRangeArgs</a>.</p>

</div>
</div>

### setAND() {#a384a442d2146a5a6faab695abbaa6676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AttrClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setAND (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee)</td>
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

<p>Compute the logical AND of the attributes of the caller and the callee.</p>


<p>This function sets the caller's attribute to false if the callee's attribute is false.</p>


<p>Definition at line 2485 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### setOR() {#ae83cb1660469243aaf6aff42b7970b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AttrClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setOR (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee)</td>
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

<p>Compute the logical OR of the attributes of the caller and the callee.</p>


<p>This function sets the caller's attribute to true if the callee's attribute is true.</p>


<p>Definition at line 2497 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### unpackAllocSizeArgs() {#ab67846129bc1b313c0a7606f285f2168}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, std::optional&lt; unsigned &gt; &gt; unpackAllocSizeArgs (uint64_t Num)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="#ab120e0d08d1d90a92f27558a82005dcb">AllocSizeNumElemsNotPresent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attribute/#a5bac674280b8fed3e09ea688b91bb1a0">llvm::Attribute::getAllocSizeArgs</a>.</p>

</div>
</div>

### unpackVScaleRangeArgs() {#a44f5f98b926132d88f0211642cc9dcb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, std::optional&lt; unsigned &gt; &gt; unpackVScaleRangeArgs (uint64_t Value)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attribute/#a190a29f5df3964b269383c0d6fba0ea9">llvm::Attribute::getVScaleRangeMax</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#a2340c9d2c47ffa7fc07568ba059b62a2">llvm::Attribute::getVScaleRangeMin</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AllocSizeNumElemsNotPresent {#ab120e0d08d1d90a92f27558a82005dcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned AllocSizeNumElemsNotPresent = -1</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="#a84f56e05a576b94b89af30ba313805c4">packAllocSizeArgs</a> and <a href="#ab67846129bc1b313c0a7606f285f2168">unpackAllocSizeArgs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ATTRIBUTE\_ALL {#a560892ae9e12e82290c046b8e86e7d30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ATTRIBUTE_ALL(ENUM_NAME, DISPLAY_NAME)&nbsp;&nbsp;&nbsp;.Case(#DISPLAY_NAME, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### ATTRIBUTE\_ENUM {#ac52fd56f4583e0aed1c9b900c3ac98c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ATTRIBUTE_ENUM(ENUM_NAME, DISPLAY_NAME)&nbsp;&nbsp;&nbsp;  .Case(#DISPLAY_NAME, Attribute::ENUM_NAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### ATTRIBUTE\_ENUM {#a6c9483392aa0cf508b9ac300b9e550a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ATTRIBUTE_ENUM(ENUM_NAME, DISPLAY_NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case Attribute::ENUM_NAME:                                                   \
    return #DISPLAY_NAME;
</div>
</dd>
</dl>

<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### ATTRIBUTE\_ENUM {#ac9102fc703447e36f0fc9a9c14e52de7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ATTRIBUTE_ENUM(ENUM_NAME, DISPLAY_NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  struct ENUM_NAME##Attr : <a href="/web-llvm/docs/api/structs/enumattr">EnumAttr</a> {                                          \
    static enum <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> getKind() {                                \
      return llvm::Attribute::ENUM_NAME;                                       \
    }                                                                          \
  };
</div>
</dd>
</dl>

<p>Definition at line 2630 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### ATTRIBUTE\_STRBOOL {#ac714438f966ac34421b4ef3cffe04b1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ATTRIBUTE_STRBOOL(ENUM_NAME, DISPLAY_NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  struct ENUM_NAME##Attr : <a href="/web-llvm/docs/api/structs/strboolattr">StrBoolAttr</a> {                                       \
    static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> getKind() { return #DISPLAY_NAME; }                       \
  };
</div>
</dd>
</dl>

<p>Definition at line 2636 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### GET\_ATTR\_COMPAT\_FUNC {#a3b6abfc8405f6f997d276b4d21b95cec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_ATTR_COMPAT_FUNC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2642 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### GET\_ATTR\_NAMES {#aba63655d8ee18e876fc5cee12bbaa35e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_ATTR_NAMES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### GET\_ATTR\_NAMES {#a071d47a02c0ca8b57596eea81c5bdee2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_ATTR_NAMES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### GET\_ATTR\_NAMES {#a1b41e24f10b13f0f51727234d0c698a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_ATTR_NAMES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### GET\_ATTR\_NAMES {#ac21254daccb964b2506c5c068058190e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_ATTR_NAMES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2629 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### GET\_ATTR\_PROP\_TABLE {#a4b5e7e3091defeb441ea56e24188e634}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_ATTR_PROP_TABLE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
