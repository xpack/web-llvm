---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/debugloc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DebugLoc` Class

<p>A debug info location. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DebugLoc { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a7eeeeeb14850f63e377665e7d7c8cc39">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37616eb7c1e47f6df05f3fdbdc09552a">DebugLoc</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39a96f6eafefa196693d5ca3ef376934">DebugLoc</a> (const DILocation *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct from an <em><a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a></em>. <a href="#a39a96f6eafefa196693d5ca3ef376934">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a274fed1b1b0bad2f68057a400b5cf738">DebugLoc</a> (const MDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct from an <em><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></em>. <a href="#a274fed1b1b0bad2f68057a400b5cf738">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed2c46114adcf9712ee8de82d9fdf960">operator DILocation *</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ac1684510e43a52a597a7a82fe797b8">operator-&gt;</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1200bd5d7fdbfe5f35b2d1d00d08f8b3">operator*</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3d3e352271b660741f403e60c732b71">operator bool</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for null. <a href="#ad3d3e352271b660741f403e60c732b71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cb50ce12d811af2fa69805ee80107d6">operator==</a> (const DebugLoc &amp;DL) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6959176362102af9a136a5415d74426">operator!=</a> (const DebugLoc &amp;DL) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ff1bb484be62f8dac94fc087f72f524">get</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the underlying <em><a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a></em>. <a href="#a4ff1bb484be62f8dac94fc087f72f524">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fb007484ca0f8415aaa6ef6c1677c5f">hasTrivialDestructor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this has a trivial destructor. <a href="#a6fb007484ca0f8415aaa6ef6c1677c5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a427c256af834975c7869ad28fac00563">getLine</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98eca4d65070b40322af34cf08842d8c">getCol</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51e7213ee467c71c8feec9ff30a580bd">getScope</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada0b6f3c53a53b7274e7aeb23eeab5a8">getInlinedAt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af881dfbb1a3f3e64fc9a8eea04be04bc">getInlinedAtScope</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the fully inlined-at scope for a <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>. <a href="#af881dfbb1a3f3e64fc9a8eea04be04bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bccb0979d1d30e83fe142ac7fb4747b">getFnDebugLoc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the debug info location for the start of the function. <a href="#a4bccb0979d1d30e83fe142ac7fb4747b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a942ba74e5c32ec1b9471e80c2c826b5d">getAsMDNode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return <span class="doxyComputerOutput">this</span> as a bar <em><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></em>. <a href="#a942ba74e5c32ec1b9471e80c2c826b5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadbe78e14e88b07caba251af5db4a042">isImplicitCode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> corresponds to an implicit code. <a href="#aadbe78e14e88b07caba251af5db4a042">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04abc02eae5231190e32453a72d4b2bf">setImplicitCode</a> (bool ImplicitCode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf018edd9aec8ba5434e17d10f64d8cd">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88cd5f78395c5eb2c7b155df2c149bd8">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>prints source location /path/to/file.exe:line:col @[inlined at] <a href="#a88cd5f78395c5eb2c7b155df2c149bd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a0b32d680d9bfed0636f7297d89583e27">TrackingMDNodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3532a77329561b594ff539afb5f9e256">Loc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55acf718f2931a7050c4ed39eb0434e7">appendInlinedAt</a> (const DebugLoc &amp;DL, DILocation *InlinedAt, LLVMContext &amp;Ctx, DenseMap&lt; const MDNode *, MDNode * &gt; &amp;Cache)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rebuild the entire inlined-at chain for this instruction so that the top of the chain now is inlined-at the new call site. <a href="#a55acf718f2931a7050c4ed39eb0434e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac09dfae0aafa3f07db67a5813f454ae">replaceInlinedAtSubprogram</a> (const DebugLoc &amp;DL, DISubprogram &amp;NewSP, LLVMContext &amp;Ctx, DenseMap&lt; const MDNode *, MDNode * &gt; &amp;Cache)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rebuild the entire inline-at chain by replacing the subprogram at the end of the chain with NewSP. <a href="#aac09dfae0aafa3f07db67a5813f454ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A debug info location.</p>


<p>This class is a wrapper around a tracking reference to an <em><a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a></em> pointer.</p>


<p>To avoid extra includes, <em><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></em> doubles the <em><a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a></em> API with a one based on relatively opaque <em><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></em> pointers.</p>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a7eeeeeb14850f63e377665e7d7c8cc39}

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


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ReplaceLastInlinedAt<a id="a7eeeeeb14850f63e377665e7d7c8cc39a2137f764d798f38e1d212649748140e8"></a></td>
<td class="doxyEnumItemDescription"> (= true)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DebugLoc() {#a37616eb7c1e47f6df05f3fdbdc09552a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DebugLoc::DebugLoc ()</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a55acf718f2931a7050c4ed39eb0434e7">appendInlinedAt</a>, <a href="#a4bccb0979d1d30e83fe142ac7fb4747b">getFnDebugLoc</a>, <a href="#ae6959176362102af9a136a5415d74426">operator!=</a>, <a href="#a2cb50ce12d811af2fa69805ee80107d6">operator==</a>, <a href="#a88cd5f78395c5eb2c7b155df2c149bd8">print</a> and <a href="#aac09dfae0aafa3f07db67a5813f454ae">replaceInlinedAtSubprogram</a>.</p>

</div>
</div>

### DebugLoc() {#a39a96f6eafefa196693d5ca3ef376934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc::DebugLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct from an <em><a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a></em>.</p>

<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugloc-cpp">DebugLoc.cpp</a>.</p>

</div>
</div>

### DebugLoc() {#a274fed1b1b0bad2f68057a400b5cf738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc::DebugLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct from an <em><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></em>.</p>


<p>Note: if <span class="doxyComputerOutput">N</span> is not an <em><a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a></em>, a verifier check will fail, and accessors will crash. However, construction from other nodes is supported in order to handle forward references when reading textual IR.</p>


<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugloc-cpp">DebugLoc.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Operators

### operator DILocation \*() {#aed2c46114adcf9712ee8de82d9fdf960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DebugLoc::operator DILocation * ()</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>.</p>


<p>Reference <a href="#a4ff1bb484be62f8dac94fc087f72f524">get</a>.</p>

</div>
</div>

### operator-&gt;() {#a6ac1684510e43a52a597a7a82fe797b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocation * llvm::DebugLoc::operator-&gt; ()</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>.</p>


<p>Reference <a href="#a4ff1bb484be62f8dac94fc087f72f524">get</a>.</p>

</div>
</div>

### operator\*() {#a1200bd5d7fdbfe5f35b2d1d00d08f8b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocation &amp; llvm::DebugLoc::operator* ()</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>.</p>


<p>Reference <a href="#a4ff1bb484be62f8dac94fc087f72f524">get</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#ad3d3e352271b660741f403e60c732b71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DebugLoc::operator bool ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for null.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for null in a way that is safe with broken debug info. Unlike the conversion to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a></span>, this doesn't require that <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span> is of the right type. Important for cases like <em><a href="/web-llvm/docs/api/namespaces/llvm/#a9b2f025559a0b80366b74285cf25c01e">llvm::StripDebugInfo()</a></em> and <em><a href="/web-llvm/docs/api/classes/llvm/instruction/#a565f546ad95bd3a9bbe9a1e5040803f0">Instruction::hasMetadata()</a></em>.</p>


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>.</p>

</div>
</div>

### operator!=() {#ae6959176362102af9a136a5415d74426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DebugLoc::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>.</p>


<p>References <a href="#a37616eb7c1e47f6df05f3fdbdc09552a">DebugLoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

### operator==() {#a2cb50ce12d811af2fa69805ee80107d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DebugLoc::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL)</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>.</p>


<p>References <a href="#a37616eb7c1e47f6df05f3fdbdc09552a">DebugLoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### get() {#a4ff1bb484be62f8dac94fc087f72f524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocation * DebugLoc::get ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the underlying <em><a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a></em>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>!*this or <span class="doxyComputerOutput">isa&lt;DILocation&gt;(getAsMDNode())</span>.</p></dd>
</dl>


<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugloc-cpp">DebugLoc.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad6fb20ec5bd66a3669cc0a4d24ad5f62">llvm::addLocationToRemarks</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#ac04b6d4e5d3715d33fee0cf6c80a15c8">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::addReachesFunctionCallbacksIfEnabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a07a576318c1a362676e2d4ff00b921bb">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82984d4a91e7dc2072dfd8fad2854618">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a2ed4f37fbda15a9c05f333fde59e9fbb">fixupLineNumbers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae591509c81d00090bde300a897e12d82">llvm::formatCallSiteLocation</a>, <a href="#a98eca4d65070b40322af34cf08842d8c">getCol</a>, <a href="#ada0b6f3c53a53b7274e7aeb23eeab5a8">getInlinedAt</a>, <a href="#a427c256af834975c7869ad28fac00563">getLine</a>, <a href="#a51e7213ee467c71c8feec9ff30a580bd">getScope</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ac0da78bd6844fdff5ec2fc0654d00de7">insertDbgValueOrDbgVariableRecord</a>, <a href="#aadbe78e14e88b07caba251af5db4a042">isImplicitCode</a>, <a href="#aed2c46114adcf9712ee8de82d9fdf960">operator DILocation *</a>, <a href="#a1200bd5d7fdbfe5f35b2d1d00d08f8b3">operator*</a>, <a href="#a6ac1684510e43a52a597a7a82fe797b8">operator-&gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/debuginfofinder/#aed105f22ff3e6ad4f3c80cd96ef7df1f">llvm::DebugInfoFinder::processDbgRecord</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a914ea1510476a800508ae70d159bd8c0">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::processStaticAllocas</a> and <a href="#a04abc02eae5231190e32453a72d4b2bf">setImplicitCode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#abf018edd9aec8ba5434e17d10f64d8cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void DebugLoc::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugloc-cpp">DebugLoc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a88cd5f78395c5eb2c7b155df2c149bd8">print</a>.</p>

</div>
</div>

### getAsMDNode() {#a942ba74e5c32ec1b9471e80c2c826b5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * llvm::DebugLoc::getAsMDNode ()</td>
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

<p>Return <span class="doxyComputerOutput">this</span> as a bar <em><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></em>.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a7c33f7bfe854f12e21290f2a03a10a18">anonymous{AsmWriter.cpp}::AssemblyWriter::printDbgVariableRecord</a>.</p>

</div>
</div>

### getCol() {#a98eca4d65070b40322af34cf08842d8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DebugLoc::getCol ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugloc-cpp">DebugLoc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4ff1bb484be62f8dac94fc087f72f524">get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a5217abbfbac8873d22a2dd6cdbb0bcc1">inlineDebugLoc</a>, <a href="#a88cd5f78395c5eb2c7b155df2c149bd8">print</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>.</p>

</div>
</div>

### getFnDebugLoc() {#a4bccb0979d1d30e83fe142ac7fb4747b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc DebugLoc::getFnDebugLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the debug info location for the start of the function.</p>


<p>Walk up the scope chain of given debug loc and find line number info for the function.</p>


<p>FIXME: Remove this. Users should use DILocation/DILocalScope API to find the subprogram, and then <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">DILocation::get()</a>.</p>


<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugloc-cpp">DebugLoc.cpp</a>.</p>


<p>References <a href="#a37616eb7c1e47f6df05f3fdbdc09552a">DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af648a1ecd9b0189801c2c8f8f15ffba3">llvm::getDISubprogram</a> and <a href="#af881dfbb1a3f3e64fc9a8eea04be04bc">getInlinedAtScope</a>.</p>

</div>
</div>

### getInlinedAt() {#ada0b6f3c53a53b7274e7aeb23eeab5a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocation * DebugLoc::getInlinedAt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugloc-cpp">DebugLoc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4ff1bb484be62f8dac94fc087f72f524">get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a15c139830d442796a30fbd35e8bfa270">findVarsWithStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4514f516df040b468e552a28163b3747">getAggregate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a30791b6c651e6313b0aab3f01da9d57b">getAggregateVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a91311bfd92d95fb2817580a39aa9a6ad">getAggregateVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87ef919ea907189c22b74f604a645b40">llvm::getDebugValueLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab03285c2540e2e5af20afb915d26a405">llvm::getDebugValueLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae9748fb2e4d41aaa8ac80d00b2becc52">llvm::SelectionDAGBuilder::handleDebugValue</a>, <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestats/#a2ad1df667a6a13366805e55ea363ee9b">llvm::DroppedVariableStats::populateVarIDSetAndInlinedMap</a> and <a href="#a88cd5f78395c5eb2c7b155df2c149bd8">print</a>.</p>

</div>
</div>

### getInlinedAtScope() {#af881dfbb1a3f3e64fc9a8eea04be04bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * DebugLoc::getInlinedAtScope ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the fully inlined-at scope for a <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>.</p>


<p>Gets the inlined-at scope for a <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>.</p>


<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugloc-cpp">DebugLoc.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="#a4bccb0979d1d30e83fe142ac7fb4747b">getFnDebugLoc</a>.</p>

</div>
</div>

### getLine() {#a427c256af834975c7869ad28fac00563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DebugLoc::getLine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugloc-cpp">DebugLoc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4ff1bb484be62f8dac94fc087f72f524">get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#ac04b6d4e5d3715d33fee0cf6c80a15c8">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::addReachesFunctionCallbacksIfEnabled</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a3fd239026aba79e9aaf5b81578f4198c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getInstWeightImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a5217abbfbac8873d22a2dd6cdbb0bcc1">inlineDebugLoc</a>, <a href="#a88cd5f78395c5eb2c7b155df2c149bd8">print</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>.</p>

</div>
</div>

### getScope() {#a51e7213ee467c71c8feec9ff30a580bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * DebugLoc::getScope ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugloc-cpp">DebugLoc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4ff1bb484be62f8dac94fc087f72f524">get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a87ef919ea907189c22b74f604a645b40">llvm::getDebugValueLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab03285c2540e2e5af20afb915d26a405">llvm::getDebugValueLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a5217abbfbac8873d22a2dd6cdbb0bcc1">inlineDebugLoc</a> and <a href="#a88cd5f78395c5eb2c7b155df2c149bd8">print</a>.</p>

</div>
</div>

### hasTrivialDestructor() {#a6fb007484ca0f8415aaa6ef6c1677c5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DebugLoc::hasTrivialDestructor ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this has a trivial destructor.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>.</p>

</div>
</div>

### isImplicitCode() {#aadbe78e14e88b07caba251af5db4a042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DebugLoc::isImplicitCode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> corresponds to an implicit code.</p>

<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugloc-cpp">DebugLoc.cpp</a>.</p>


<p>Reference <a href="#a4ff1bb484be62f8dac94fc087f72f524">get</a>.</p>

</div>
</div>

### print() {#a88cd5f78395c5eb2c7b155df2c149bd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugLoc::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>prints source location /path/to/file.exe:line:col @[inlined at]</p>

<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugloc-cpp">DebugLoc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a37616eb7c1e47f6df05f3fdbdc09552a">DebugLoc</a>, <a href="#a98eca4d65070b40322af34cf08842d8c">getCol</a>, <a href="#ada0b6f3c53a53b7274e7aeb23eeab5a8">getInlinedAt</a>, <a href="#a427c256af834975c7869ad28fac00563">getLine</a> and <a href="#a51e7213ee467c71c8feec9ff30a580bd">getScope</a>.</p>


<p>Referenced by <a href="#abf018edd9aec8ba5434e17d10f64d8cd">dump</a>.</p>

</div>
</div>

### setImplicitCode() {#a04abc02eae5231190e32453a72d4b2bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugLoc::setImplicitCode (bool ImplicitCode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugloc-cpp">DebugLoc.cpp</a>.</p>


<p>Reference <a href="#a4ff1bb484be62f8dac94fc087f72f524">get</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Loc {#a3532a77329561b594ff539afb5f9e256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TrackingMDNodeRef llvm::DebugLoc::Loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### appendInlinedAt() {#a55acf718f2931a7050c4ed39eb0434e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc DebugLoc::appendInlinedAt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * InlinedAt, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; &amp; Cache)</td>
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

<p>Rebuild the entire inlined-at chain for this instruction so that the top of the chain now is inlined-at the new call site.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">InlinedAt</td>
<td class="doxyParamItemDescription"><p>The new outermost inlined-at in the chain.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugloc-cpp">DebugLoc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a37616eb7c1e47f6df05f3fdbdc09552a">DebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a21a975fd58c287a6ca3f1c89c048e7d3">llvm::MDNode::getDistinct</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a5217abbfbac8873d22a2dd6cdbb0bcc1">inlineDebugLoc</a>.</p>

</div>
</div>

### replaceInlinedAtSubprogram() {#aac09dfae0aafa3f07db67a5813f454ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc DebugLoc::replaceInlinedAtSubprogram (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> &amp; NewSP, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; &amp; Cache)</td>
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

<p>Rebuild the entire inline-at chain by replacing the subprogram at the end of the chain with NewSP.</p>

<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugloc-cpp">DebugLoc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalscope/#ae713d283078fedb08e45a4e893508866">llvm::DILocalScope::cloneScopeForSubprogram</a>, <a href="#a37616eb7c1e47f6df05f3fdbdc09552a">DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">DebugLoc.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/debugloc-cpp">DebugLoc.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
