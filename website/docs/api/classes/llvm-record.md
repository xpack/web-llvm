---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/record
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Record` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::Record { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">llvm/TableGen/Record.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RecordKind { <a href="#a114bcc21e64090aed664efd18a36dea7">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98b09e526bfdb38ffb4a256f8cb6629a">Record</a> (const Init *N, ArrayRef&lt; SMLoc &gt; locs, RecordKeeper &amp;records, RecordKind Kind=RK_Def)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9667e38415a2885b9cc555f6e41e1eab">Record</a> (StringRef N, ArrayRef&lt; SMLoc &gt; locs, RecordKeeper &amp;records, RecordKind Kind=RK_Def)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a647a7453aa46d3ca88be0cd677d95af3">Record</a> (const Record &amp;O)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1094c36b2a60bfa42e2344393b944d5b">getID</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9864f9add0da57a2c4f036a6110b313b">getName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d89cc30867b3edb73449f0577ec5b2">getNameInit</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dcfa60a1e7d19ffa3b56bb4fcdb3f75">getNameInitAsString</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a228a28f0c4bc8a85e0281e7079578c">setName</a> (const Init *Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1440b4c6fda0655f260750f386c9d92a">getLoc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6463e475b1a29350bc8e55098af3987b">appendLoc</a> (SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7bf47bfef9b5ba3201e739de4d05408">getForwardDeclarationLocs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb89ae3cf98a778d48e29c2643bf2f6a">appendReferenceLoc</a> (SMRange Loc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a reference to this record value. <a href="#afb89ae3cf98a778d48e29c2643bf2f6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad30eeed65685cc5f0296e127927c113b">getReferenceLocs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the references of this record value. <a href="#ad30eeed65685cc5f0296e127927c113b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad47a1bf1b6f941e37a463d942f573d0c">updateClassLoc</a> (SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recordrecty">RecordRecTy</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06ffb2d31fbf2a377f2156884ac0c0bb">getType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/definit">DefInit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae3f286dc88412e5ffb6b1a488681369">getDefInit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>get the corresponding <a href="/web-llvm/docs/api/classes/llvm/definit">DefInit</a>. <a href="#aae3f286dc88412e5ffb6b1a488681369">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9728bfb7958a78fdcc4e57743bff542b">isClass</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7480b7bdef6b981752b4c50f885513f1">isMultiClass</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d059bdd553c32f0fa98ecf85a2dac11">isAnonymous</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2e19c65a02916c504a1ecc9ca0ef583">getTemplateArgs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/recordval">RecordVal</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaef6f613ea9bdda33119d7f9cb0e9c93">getValues</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/record/assertioninfo">AssertionInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38b24bc8e99fbb4aa410273f20bf772e">getAssertions</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/record/dumpinfo">DumpInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2723632d12388a0d9d809d5a26db21ba">getDumps</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> *, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fb8b12f752de40d45948ad282c6bf84">getSuperClasses</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b6fc6699e686f04ca76a628511741b5">hasDirectSuperClass</a> (const Record *SuperClass) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether this record has the specified direct superclass. <a href="#a8b6fc6699e686f04ca76a628511741b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8f7b3435e5d6a7132e2e0aba6b347e7">getDirectSuperClasses</a> (SmallVectorImpl&lt; const Record * &gt; &amp;Classes) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append the direct superclasses of this record to Classes. <a href="#ae8f7b3435e5d6a7132e2e0aba6b347e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a175c899ffaa6ddfc6c4ce2f823c042">isTemplateArg</a> (const Init *Name) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recordval">RecordVal</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e084b9b417ae456b128ee1f6506b41d">getValue</a> (const Init *Name) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recordval">RecordVal</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7d9a4f8164d6af9b797364cd63702dd">getValue</a> (StringRef Name) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/recordval">RecordVal</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6e5b19799adbbcc20f1b48f094bf621">getValue</a> (const Init *Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/recordval">RecordVal</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8e9cc9756fd959dd1d48921855787a6">getValue</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a615cb9834d2d4b12644f9d534f677e69">addTemplateArg</a> (const Init *Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a4225f6fca11324cfcb7a11535d5dcf">addValue</a> (const RecordVal &amp;RV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad283a32d567fb8d357aec7b38ac8d90f">removeValue</a> (const Init *Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44d44347281bf94a07c74f388d64b346">removeValue</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a862384cb3443f170a9ab592044a57b5c">addAssertion</a> (SMLoc Loc, const Init *Condition, const Init *Message)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14ebe34cb1bb505ed6a0502966fb2ab0">addDump</a> (SMLoc Loc, const Init *Message)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee003d62a938263833fd4d13b083c72a">appendAssertions</a> (const Record *Rec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d65f9f9ef5c489ac6806f565116bfcd">appendDumps</a> (const Record *Rec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af965a776d26783397a4825a49a84bd11">checkRecordAssertions</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f5b2802b4e4073f4ab36dfea4d310f4">emitRecordDumps</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1938bf045c5347c45b2330a204bf32dd">checkUnusedTemplateArgs</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa89c785d5856324faf763817eb091191">isSubClassOf</a> (const Record *R) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b4a7a3640fe5f917ba40dedfaa50e28">isSubClassOf</a> (StringRef Name) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8c64865cb640ca5ba8ba40c3deef870">addSuperClass</a> (const Record *R, SMRange Range)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7a3d6d05ef3aa1203cab2e1d57957cc">resolveReferences</a> (const Init *NewName=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If there are any field references that refer to fields that have been filled in, we can propagate the values now. <a href="#ac7a3d6d05ef3aa1203cab2e1d57957cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14ef30a60513d26f82c93d796deb7494">resolveReferences</a> (Resolver &amp;R, const RecordVal *SkipVal=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the resolver to the name of the record as well as to the initializers of all fields of the record except SkipVal. <a href="#a14ef30a60513d26f82c93d796deb7494">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a507c8dc2db4f450446681404934ce237">getRecords</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47077193efcfcbedd136c518339d8cc9">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5038612e6583bc87b127f637ab19bad">getFieldLoc</a> (StringRef FieldName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the source location for the named field. <a href="#ab5038612e6583bc87b127f637ab19bad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a089bb78f5beac2fe715611c4d02a7e7b">getValueInit</a> (StringRef FieldName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the initializer for a value with the specified name, or throw an exception if the field does not exist. <a href="#a089bb78f5beac2fe715611c4d02a7e7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66ba3203edbbeb2a97f6173e91ebea03">isValueUnset</a> (StringRef FieldName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the named field is unset. <a href="#a66ba3203edbbeb2a97f6173e91ebea03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdb8b506ae2f062a5d33977cb0164ae1">getValueAsString</a> (StringRef FieldName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method looks up the specified field and returns its value as a string, throwing an exception if the field does not exist or if the value is not a string. <a href="#afdb8b506ae2f062a5d33977cb0164ae1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace6e85f8f0adf0c51140965bcd4dfe47">getValueAsOptionalString</a> (StringRef FieldName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method looks up the specified field and returns its value as a string, throwing an exception if the value is not a string and std::nullopt if the field does not exist. <a href="#ace6e85f8f0adf0c51140965bcd4dfe47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitsinit">BitsInit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b428bd00e5250c79391d22968b029d">getValueAsBitsInit</a> (StringRef FieldName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method looks up the specified field and returns its value as a <a href="/web-llvm/docs/api/classes/llvm/bitsinit">BitsInit</a>, throwing an exception if the field does not exist or if the value is not the right type. <a href="#ad7b428bd00e5250c79391d22968b029d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/listinit">ListInit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb5b176fd3d90b85393bc1835dfa92f">getValueAsListInit</a> (StringRef FieldName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method looks up the specified field and returns its value as a <a href="/web-llvm/docs/api/classes/llvm/listinit">ListInit</a>, throwing an exception if the field does not exist or if the value is not the right type. <a href="#a9cb5b176fd3d90b85393bc1835dfa92f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a8bf35316edb5fd57d98f2eda72581b">getValueAsListOfDefs</a> (StringRef FieldName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method looks up the specified field and returns its value as a vector of records, throwing an exception if the field does not exist or if the value is not the right type. <a href="#a2a8bf35316edb5fd57d98f2eda72581b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01c6cc1360f4cc0cfec84038958a2a1e">getValueAsListOfInts</a> (StringRef FieldName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method looks up the specified field and returns its value as a vector of integers, throwing an exception if the field does not exist or if the value is not the right type. <a href="#a01c6cc1360f4cc0cfec84038958a2a1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c14eff6d45e790bba2152e6e8da4d50">getValueAsListOfStrings</a> (StringRef FieldName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method looks up the specified field and returns its value as a vector of strings, throwing an exception if the field does not exist or if the value is not the right type. <a href="#a5c14eff6d45e790bba2152e6e8da4d50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48d62ac5aec02b75a17f28fcd62fe47a">getValueAsDef</a> (StringRef FieldName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method looks up the specified field and returns its value as a <a href="/web-llvm/docs/api/classes/llvm/record">Record</a>, throwing an exception if the field does not exist or if the value is not the right type. <a href="#a48d62ac5aec02b75a17f28fcd62fe47a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a833c8929e04fea46caae8e47a768b19c">getValueAsOptionalDef</a> (StringRef FieldName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method looks up the specified field and returns its value as a <a href="/web-llvm/docs/api/classes/llvm/record">Record</a>, returning null if the field exists but is "uninitialized" (i.e. <a href="#a833c8929e04fea46caae8e47a768b19c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f0900397779045d3d082db84fdefdfb">getValueAsBit</a> (StringRef FieldName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method looks up the specified field and returns its value as a bit, throwing an exception if the field does not exist or if the value is not the right type. <a href="#a0f0900397779045d3d082db84fdefdfb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c84631008c6330d243843e3a2f3088c">getValueAsBitOrUnset</a> (StringRef FieldName, bool &amp;Unset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method looks up the specified field and returns its value as a bit. <a href="#a0c84631008c6330d243843e3a2f3088c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3d85a78d044fdbacc61fb65d9530175">getValueAsInt</a> (StringRef FieldName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method looks up the specified field and returns its value as an int64_t, throwing an exception if the field does not exist or if the value is not the right type. <a href="#af3d85a78d044fdbacc61fb65d9530175">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/daginit">DagInit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a555a8bf98d04f42bf54b2d8dc8e546ce">getValueAsDag</a> (StringRef FieldName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method looks up the specified field and returns its value as an Dag, throwing an exception if the field does not exist or if the value is not the right type. <a href="#a555a8bf98d04f42bf54b2d8dc8e546ce">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43c1dd9623bfc78d0e82ef45bf60742a">checkName</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ef2b33c2fd2813f8f8ae0b9ca496745">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19fc5d63bd1d9f24f04a2be0bc15273e">Locs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ea6b97c46bb9434c7eafcc877c88c05">ForwardDeclarationLocs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a>, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa281cd31b3147d292a68f6407d3fb755">ReferenceLocs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2364707405d7874d0db87b512a4d8870">TemplateArgs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/recordval">RecordVal</a>, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a509d1b5b897b62cf3094d218f7d4efde">Values</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/record/assertioninfo">AssertionInfo</a>, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50a8de9b10d9c268ace456b11545fac0">Assertions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/record/dumpinfo">DumpInfo</a>, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69b7da8bc6b8a4b4adee5a7c424c0142">Dumps</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> *, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> &gt;, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ad8fbd83d2a4869d6c416531df3db61">SuperClasses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acab0626f7a206d88d0c60556934dc217">TrackedRecords</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/definit">DefInit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08366f3dc266374fd7afe9dcf9c3344c">CorrespondingDefInit</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56908536ba77a3df40bfa0030137d8f4">ID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a114bcc21e64090aed664efd18a36dea7">RecordKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae40fd3052f5e2558474d75ecbff30aaa">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135a92f99d0c34b158c54a1f3191dae2">getNewUID</a> (RecordKeeper &amp;RK)</td>
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


<p>Definition at line 1596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### RecordKind {#a114bcc21e64090aed664efd18a36dea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Record::RecordKind </td>
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
<td class="doxyEnumItemName">RK_Def<a id="a114bcc21e64090aed664efd18a36dea7af111c119e0920f583b42c48a404149ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RK_AnonymousDef<a id="a114bcc21e64090aed664efd18a36dea7a86506ee7f447f18252d267dd158b830f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RK_Class<a id="a114bcc21e64090aed664efd18a36dea7a6d12ac1df82d81779e1abe932a8691c4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RK_MultiClass<a id="a114bcc21e64090aed664efd18a36dea7aad5a83addcf4215ddf8139baeef697d7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Record() {#a98b09e526bfdb38ffb4a256f8cb6629a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Record::Record (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * N, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &gt; locs, <a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp; records, <a href="#a114bcc21e64090aed664efd18a36dea7">RecordKind</a> Kind=<a href="#a114bcc21e64090aed664efd18a36dea7af111c119e0920f583b42c48a404149ba">RK_Def</a>)</td>
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



<p>Definition at line 1652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="#a135a92f99d0c34b158c54a1f3191dae2">getNewUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a114bcc21e64090aed664efd18a36dea7af111c119e0920f583b42c48a404149ba">RK_Def</a>.</p>


<p>Referenced by <a href="#af8c64865cb640ca5ba8ba40c3deef870">addSuperClass</a>, <a href="#aee003d62a938263833fd4d13b083c72a">appendAssertions</a>, <a href="#a9d65f9f9ef5c489ac6806f565116bfcd">appendDumps</a>, <a href="#ae8f7b3435e5d6a7132e2e0aba6b347e7">getDirectSuperClasses</a>, <a href="#ad6e5b19799adbbcc20f1b48f094bf621">getValue</a>, <a href="#af8e9cc9756fd959dd1d48921855787a6">getValue</a>, <a href="#a48d62ac5aec02b75a17f28fcd62fe47a">getValueAsDef</a>, <a href="#a833c8929e04fea46caae8e47a768b19c">getValueAsOptionalDef</a>, <a href="#a8b6fc6699e686f04ca76a628511741b5">hasDirectSuperClass</a>, <a href="#aa89c785d5856324faf763817eb091191">isSubClassOf</a>, <a href="#a647a7453aa46d3ca88be0cd677d95af3">Record</a> and <a href="#a9667e38415a2885b9cc555f6e41e1eab">Record</a>.</p>

</div>
</div>

### Record() {#a9667e38415a2885b9cc555f6e41e1eab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Record::Record (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> N, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &gt; locs, <a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp; records, <a href="#a114bcc21e64090aed664efd18a36dea7">RecordKind</a> Kind=<a href="#a114bcc21e64090aed664efd18a36dea7af111c119e0920f583b42c48a404149ba">RK_Def</a>)</td>
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



<p>Definition at line 1659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a98b09e526bfdb38ffb4a256f8cb6629a">Record</a> and <a href="#a114bcc21e64090aed664efd18a36dea7af111c119e0920f583b42c48a404149ba">RK_Def</a>.</p>

</div>
</div>

### Record() {#a647a7453aa46d3ca88be0cd677d95af3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Record::Record (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> &amp; O)</td>
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



<p>Definition at line 1666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="#a135a92f99d0c34b158c54a1f3191dae2">getNewUID</a>, <a href="#a507c8dc2db4f450446681404934ce237">getRecords</a> and <a href="#a98b09e526bfdb38ffb4a256f8cb6629a">Record</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAssertion() {#a862384cb3443f170a9ab592044a57b5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Record::addAssertion (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * Condition, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * Message)</td>
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



<p>Definition at line 1778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### addDump() {#a14ebe34cb1bb505ed6a0502966fb2ab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Record::addDump (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * Message)</td>
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



<p>Definition at line 1782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### addSuperClass() {#af8c64865cb640ca5ba8ba40c3deef870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Record::addSuperClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * R, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Range)</td>
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



<p>Definition at line 1815 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa89c785d5856324faf763817eb091191">isSubClassOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="#a98b09e526bfdb38ffb4a256f8cb6629a">Record</a>.</p>

</div>
</div>

### addTemplateArg() {#a615cb9834d2d4b12644f9d534f677e69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Record::addTemplateArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * Name)</td>
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



<p>Definition at line 1755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a9a175c899ffaa6ddfc6c4ce2f823c042">isTemplateArg</a>.</p>

</div>
</div>

### addValue() {#a7a4225f6fca11324cfcb7a11535d5dcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Record::addValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recordval">RecordVal</a> &amp; RV)</td>
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



<p>Definition at line 1760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/recordval/#aaef4d220def67ee1d6c684950289bf3a">llvm::RecordVal::getNameInit</a> and <a href="#a5e084b9b417ae456b128ee1f6506b41d">getValue</a>.</p>

</div>
</div>

### appendAssertions() {#aee003d62a938263833fd4d13b083c72a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Record::appendAssertions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * Rec)</td>
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



<p>Definition at line 1786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#a98b09e526bfdb38ffb4a256f8cb6629a">Record</a>.</p>

</div>
</div>

### appendDumps() {#a9d65f9f9ef5c489ac6806f565116bfcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Record::appendDumps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * Rec)</td>
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



<p>Definition at line 1790 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#a98b09e526bfdb38ffb4a256f8cb6629a">Record</a>.</p>

</div>
</div>

### appendLoc() {#a6463e475b1a29350bc8e55098af3987b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Record::appendLoc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 1687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### appendReferenceLoc() {#afb89ae3cf98a778d48e29c2643bf2f6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Record::appendReferenceLoc (<a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Loc)</td>
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

<p>Add a reference to this record value.</p>

<p>Definition at line 1694 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### checkRecordAssertions() {#af965a776d26783397a4825a49a84bd11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Record::checkRecordAssertions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1792 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3226 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5990eefbfd827c2954f6c7be3fe5a2d1">llvm::CheckAssert</a>, <a href="#a38b24bc8e99fbb4aa410273f20bf772e">getAssertions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37310d4cb640733ed81281942c314d05">llvm::PrintError</a> and <a href="/web-llvm/docs/api/classes/llvm/init/#a00581957c4bb1587a458c3fbf4326f7a">llvm::Init::resolveReferences</a>.</p>

</div>
</div>

### checkUnusedTemplateArgs() {#a1938bf045c5347c45b2330a204bf32dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Record::checkUnusedTemplateArgs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3256 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/recordval/#a4053da8fe9acab2df4931625674a39a5">llvm::RecordVal::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/recordval/#a56e4dd14f041c61ad7fcdfdd4d4f375c">llvm::RecordVal::getName</a>, <a href="#ad2e19c65a02916c504a1ecc9ca0ef583">getTemplateArgs</a>, <a href="#a5e084b9b417ae456b128ee1f6506b41d">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/recordval/#a4e200529424ce9fc042cb8ada70dee3a">llvm::RecordVal::isUsed</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a642c8e7f7e73fb7e5ab61bff641886f4">llvm::PrintWarning</a>.</p>

</div>
</div>

### dump() {#a47077193efcfcbedd136c518339d8cc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void Record::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1840 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 2991 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

### emitRecordDumps() {#a1f5b2802b4e4073f4ab36dfea4d310f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Record::emitRecordDumps ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3245 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac39bba28adee8aa88e4c64e3bc0e3b4c">llvm::dumpMessage</a> and <a href="#a2723632d12388a0d9d809d5a26db21ba">getDumps</a>.</p>

</div>
</div>

### getAssertions() {#a38b24bc8e99fbb4aa410273f20bf772e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; AssertionInfo &gt; llvm::Record::getAssertions ()</td>
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



<p>Definition at line 1718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="#af965a776d26783397a4825a49a84bd11">checkRecordAssertions</a>.</p>

</div>
</div>

### getDefInit() {#aae3f286dc88412e5ffb6b1a488681369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefInit * Record::getDefInit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>get the corresponding <a href="/web-llvm/docs/api/classes/llvm/definit">DefInit</a>.</p>

<p>Declaration at line 1706 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 2882 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ternopinit/#a40e75ea14a528e6ffb58da993ab983a8">llvm::TernOpInit::Fold</a>.</p>

</div>
</div>

### getDirectSuperClasses() {#ae8f7b3435e5d6a7132e2e0aba6b347e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Record::getDirectSuperClasses (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * &gt; &amp; Classes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Append the direct superclasses of this record to Classes.</p>

<p>Declaration at line 1729 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 2928 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a291ac49156942529f159a9ec003cc25f">llvm::ArrayRef&lt; T &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aa713e2599e000adc01ced998c05502a7">llvm::ArrayRef&lt; T &gt;::drop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="#a0fb8b12f752de40d45948ad282c6bf84">getSuperClasses</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a98b09e526bfdb38ffb4a256f8cb6629a">Record</a>.</p>


<p>Referenced by <a href="#a06ffb2d31fbf2a377f2156884ac0c0bb">getType</a>.</p>

</div>
</div>

### getDumps() {#a2723632d12388a0d9d809d5a26db21ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; DumpInfo &gt; llvm::Record::getDumps ()</td>
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



<p>Definition at line 1719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="#a1f5b2802b4e4073f4ab36dfea4d310f4">emitRecordDumps</a>.</p>

</div>
</div>

### getFieldLoc() {#ab5038612e6583bc87b127f637ab19bad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc Record::getFieldLoc (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the source location for the named field.</p>

<p>Declaration at line 1847 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3030 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="#a1440b4c6fda0655f260750f386c9d92a">getLoc</a>, <a href="#a9864f9add0da57a2c4f036a6110b313b">getName</a>, <a href="#a5e084b9b417ae456b128ee1f6506b41d">getValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>.</p>

</div>
</div>

### getForwardDeclarationLocs() {#ab7bf47bfef9b5ba3201e739de4d05408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; SMLoc &gt; llvm::Record::getForwardDeclarationLocs ()</td>
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



<p>Definition at line 1689 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### getID() {#a1094c36b2a60bfa42e2344393b944d5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Record::getID ()</td>
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



<p>Definition at line 1674 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### getLoc() {#a1440b4c6fda0655f260750f386c9d92a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; SMLoc &gt; llvm::Record::getLoc ()</td>
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



<p>Definition at line 1686 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/binopinit/#adbe242b084763cfdb35c7850bd4098b5">llvm::BinOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/condopinit/#a1f8ad2f0a11458133631759e29f2b54a">llvm::CondOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/fieldinit/#a2c30e04a4f53b4ecbc0897f161ae00de">llvm::FieldInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/ternopinit/#a40e75ea14a528e6ffb58da993ab983a8">llvm::TernOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/unopinit/#af0e0cf8fa25dde613e92575630bb9475">llvm::UnOpInit::Fold</a>, <a href="#ab5038612e6583bc87b127f637ab19bad">getFieldLoc</a>, <a href="#a0f0900397779045d3d082db84fdefdfb">getValueAsBit</a>, <a href="#a0c84631008c6330d243843e3a2f3088c">getValueAsBitOrUnset</a>, <a href="#ad7b428bd00e5250c79391d22968b029d">getValueAsBitsInit</a>, <a href="#a555a8bf98d04f42bf54b2d8dc8e546ce">getValueAsDag</a>, <a href="#a48d62ac5aec02b75a17f28fcd62fe47a">getValueAsDef</a>, <a href="#af3d85a78d044fdbacc61fb65d9530175">getValueAsInt</a>, <a href="#a9cb5b176fd3d90b85393bc1835dfa92f">getValueAsListInit</a>, <a href="#a2a8bf35316edb5fd57d98f2eda72581b">getValueAsListOfDefs</a>, <a href="#a01c6cc1360f4cc0cfec84038958a2a1e">getValueAsListOfInts</a>, <a href="#a5c14eff6d45e790bba2152e6e8da4d50">getValueAsListOfStrings</a>, <a href="#a833c8929e04fea46caae8e47a768b19c">getValueAsOptionalDef</a>, <a href="#ace6e85f8f0adf0c51140965bcd4dfe47">getValueAsOptionalString</a>, <a href="#afdb8b506ae2f062a5d33977cb0164ae1">getValueAsString</a>, <a href="#a089bb78f5beac2fe715611c4d02a7e7b">getValueInit</a>, <a href="/web-llvm/docs/api/classes/anonymous-detailedrecordsbackend-cpp-/detailedrecordsemitter/#a54bc18bca8a7bec4933e2fbfb70d38a1">anonymous{DetailedRecordsBackend.cpp}::DetailedRecordsEmitter::printDefms</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace933d6d43b3e9495210b3ea497b2bd0">llvm::PrintError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a49dd57beeae60b394dc3c257fc49a8bd">llvm::PrintFatalError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a064bbf987337a18c4de98fc302a245cd">llvm::PrintFatalNote</a> and <a href="#a14ef30a60513d26f82c93d796deb7494">resolveReferences</a>.</p>

</div>
</div>

### getName() {#a9864f9add0da57a2c4f036a6110b313b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::Record::getName ()</td>
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



<p>Definition at line 1676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="#ab5038612e6583bc87b127f637ab19bad">getFieldLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a63a780627da7c5b7088ebaf5bd7408aa">llvm::logicalview::getRecordName</a>, <a href="#a0f0900397779045d3d082db84fdefdfb">getValueAsBit</a>, <a href="#a0c84631008c6330d243843e3a2f3088c">getValueAsBitOrUnset</a>, <a href="#ad7b428bd00e5250c79391d22968b029d">getValueAsBitsInit</a>, <a href="#a555a8bf98d04f42bf54b2d8dc8e546ce">getValueAsDag</a>, <a href="#a48d62ac5aec02b75a17f28fcd62fe47a">getValueAsDef</a>, <a href="#af3d85a78d044fdbacc61fb65d9530175">getValueAsInt</a>, <a href="#a9cb5b176fd3d90b85393bc1835dfa92f">getValueAsListInit</a>, <a href="#a2a8bf35316edb5fd57d98f2eda72581b">getValueAsListOfDefs</a>, <a href="#a01c6cc1360f4cc0cfec84038958a2a1e">getValueAsListOfInts</a>, <a href="#a5c14eff6d45e790bba2152e6e8da4d50">getValueAsListOfStrings</a>, <a href="#a833c8929e04fea46caae8e47a768b19c">getValueAsOptionalDef</a>, <a href="#ace6e85f8f0adf0c51140965bcd4dfe47">getValueAsOptionalString</a>, <a href="#afdb8b506ae2f062a5d33977cb0164ae1">getValueAsString</a>, <a href="#a089bb78f5beac2fe715611c4d02a7e7b">getValueInit</a>, <a href="/web-llvm/docs/api/structs/llvm/lessrecord/#a8f202ce2b8d3b6f352f46ea76da83179">llvm::LessRecord::operator()</a> and <a href="/web-llvm/docs/api/structs/llvm/lessrecordregister/#a1a0f91d255d85953130c7fc6c3a416ff">llvm::LessRecordRegister::operator()</a>.</p>

</div>
</div>

### getNameInit() {#af1d89cc30867b3edb73449f0577ec5b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * llvm::Record::getNameInit ()</td>
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



<p>Definition at line 1678 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/existsopinit/#adb91410c35b4cb3b300041319c35608a">llvm::ExistsOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/unopinit/#af0e0cf8fa25dde613e92575630bb9475">llvm::UnOpInit::Fold</a>, <a href="#a3dcfa60a1e7d19ffa3b56bb4fcdb3f75">getNameInitAsString</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp/#a678066d868a6e0abb3151be33bb7232e">QualifyName</a>, <a href="#ad283a32d567fb8d357aec7b38ac8d90f">removeValue</a> and <a href="#a14ef30a60513d26f82c93d796deb7494">resolveReferences</a>.</p>

</div>
</div>

### getNameInitAsString() {#a3dcfa60a1e7d19ffa3b56bb4fcdb3f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::Record::getNameInitAsString ()</td>
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



<p>Definition at line 1680 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/init/#a285d0b93e0c8992d281d0cf4c89e37b7">llvm::Init::getAsUnquotedString</a> and <a href="#af1d89cc30867b3edb73449f0577ec5b2">getNameInit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/condopinit/#a1f8ad2f0a11458133631759e29f2b54a">llvm::CondOpInit::Fold</a>.</p>

</div>
</div>

### getRecords() {#a507c8dc2db4f450446681404934ce237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordKeeper &amp; llvm::Record::getRecords ()</td>
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



<p>Definition at line 1836 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="#ab7d9a4f8164d6af9b797364cd63702dd">getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp/#ab452c4e3205de4b33ebaf7692c0fbc3f">QualifiedNameOfImplicitName</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp/#a678066d868a6e0abb3151be33bb7232e">QualifyName</a>, <a href="#a647a7453aa46d3ca88be0cd677d95af3">Record</a> and <a href="#a44d44347281bf94a07c74f388d64b346">removeValue</a>.</p>

</div>
</div>

### getReferenceLocs() {#ad30eeed65685cc5f0296e127927c113b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; SMRange &gt; llvm::Record::getReferenceLocs ()</td>
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

<p>Return the references of this record value.</p>

<p>Definition at line 1697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### getSuperClasses() {#a0fb8b12f752de40d45948ad282c6bf84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; const Record *, SMRange &gt; &gt; llvm::Record::getSuperClasses ()</td>
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



<p>Definition at line 1721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="#ae8f7b3435e5d6a7132e2e0aba6b347e7">getDirectSuperClasses</a>, <a href="#a8b6fc6699e686f04ca76a628511741b5">hasDirectSuperClass</a> and <a href="/web-llvm/docs/api/classes/anonymous-detailedrecordsbackend-cpp-/detailedrecordsemitter/#aff15dd7156e8ad1d38a077572c0fe4f0">anonymous{DetailedRecordsBackend.cpp}::DetailedRecordsEmitter::printSuperclasses</a>.</p>

</div>
</div>

### getTemplateArgs() {#ad2e19c65a02916c504a1ecc9ca0ef583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; const Init * &gt; llvm::Record::getTemplateArgs ()</td>
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



<p>Definition at line 1714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="#a1938bf045c5347c45b2330a204bf32dd">checkUnusedTemplateArgs</a> and <a href="/web-llvm/docs/api/classes/anonymous-detailedrecordsbackend-cpp-/detailedrecordsemitter/#a37407e1adaf30ca92fcd32b516ce0b07">anonymous{DetailedRecordsBackend.cpp}::DetailedRecordsEmitter::printTemplateArgs</a>.</p>

</div>
</div>

### getType() {#a06ffb2d31fbf2a377f2156884ac0c0bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RecordRecTy * Record::getType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 2876 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/recordrecty/#af99419a971a2b329732cb2a89e6a004b">llvm::RecordRecTy::get</a> and <a href="#ae8f7b3435e5d6a7132e2e0aba6b347e7">getDirectSuperClasses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4c1be5e840f541db6de41d95d4022561">llvm::codeview::computeTypeName</a> and <a href="/web-llvm/docs/api/classes/llvm/existsopinit/#adb91410c35b4cb3b300041319c35608a">llvm::ExistsOpInit::Fold</a>.</p>

</div>
</div>

### getValue() {#a5e084b9b417ae456b128ee1f6506b41d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RecordVal * llvm::Record::getValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * Name)</td>
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



<p>Definition at line 1735 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="#a7a4225f6fca11324cfcb7a11535d5dcf">addValue</a>, <a href="#a1938bf045c5347c45b2330a204bf32dd">checkUnusedTemplateArgs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#ac0d41cae6559f87a6e26f2db6c30f24d">anonymous{PerfSupportPlugin.cpp}::getCodeLoadRecord</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#ac931ae3a09278d920ebb024da87edf2e">anonymous{PerfSupportPlugin.cpp}::getDebugInfoRecord</a>, <a href="#ab5038612e6583bc87b127f637ab19bad">getFieldLoc</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#a68574bf3a1f3cabcb89adaf75a2e51b3">anonymous{PerfSupportPlugin.cpp}::getUnwindingRecord</a>, <a href="#ab7d9a4f8164d6af9b797364cd63702dd">getValue</a>, <a href="#a0f0900397779045d3d082db84fdefdfb">getValueAsBit</a>, <a href="#a0c84631008c6330d243843e3a2f3088c">getValueAsBitOrUnset</a>, <a href="#ad7b428bd00e5250c79391d22968b029d">getValueAsBitsInit</a>, <a href="#a555a8bf98d04f42bf54b2d8dc8e546ce">getValueAsDag</a>, <a href="#a48d62ac5aec02b75a17f28fcd62fe47a">getValueAsDef</a>, <a href="#af3d85a78d044fdbacc61fb65d9530175">getValueAsInt</a>, <a href="#a9cb5b176fd3d90b85393bc1835dfa92f">getValueAsListInit</a>, <a href="#a833c8929e04fea46caae8e47a768b19c">getValueAsOptionalDef</a>, <a href="#ace6e85f8f0adf0c51140965bcd4dfe47">getValueAsOptionalString</a>, <a href="#a089bb78f5beac2fe715611c4d02a7e7b">getValueInit</a>, <a href="/web-llvm/docs/api/classes/llvm/tgvarscope/#ae579c02468ab9307ae959877d8375ada">llvm::TGVarScope::getVar</a> and <a href="/web-llvm/docs/api/classes/anonymous-detailedrecordsbackend-cpp-/detailedrecordsemitter/#a37407e1adaf30ca92fcd32b516ce0b07">anonymous{DetailedRecordsBackend.cpp}::DetailedRecordsEmitter::printTemplateArgs</a>.</p>

</div>
</div>

### getValue() {#ab7d9a4f8164d6af9b797364cd63702dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RecordVal * llvm::Record::getValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 1741 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringinit/#a63edb20ca7b47e34fcb1f8df74d6424f">llvm::StringInit::get</a>, <a href="#a507c8dc2db4f450446681404934ce237">getRecords</a> and <a href="#a5e084b9b417ae456b128ee1f6506b41d">getValue</a>.</p>

</div>
</div>

### getValue() {#ad6e5b19799adbbcc20f1b48f094bf621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordVal * llvm::Record::getValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * Name)</td>
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



<p>Definition at line 1745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#a98b09e526bfdb38ffb4a256f8cb6629a">Record</a>.</p>

</div>
</div>

### getValue() {#af8e9cc9756fd959dd1d48921855787a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordVal * llvm::Record::getValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 1750 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#a98b09e526bfdb38ffb4a256f8cb6629a">Record</a>.</p>

</div>
</div>

### getValueAsBit() {#a0f0900397779045d3d082db84fdefdfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Record::getValueAsBit (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method looks up the specified field and returns its value as a bit, throwing an exception if the field does not exist or if the value is not the right type.</p>

<p>Declaration at line 1907 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3181 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1440b4c6fda0655f260750f386c9d92a">getLoc</a>, <a href="#a9864f9add0da57a2c4f036a6110b313b">getName</a>, <a href="#a5e084b9b417ae456b128ee1f6506b41d">getValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>.</p>

</div>
</div>

### getValueAsBitOrUnset() {#a0c84631008c6330d243843e3a2f3088c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Record::getValueAsBitOrUnset (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName, bool &amp; Unset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method looks up the specified field and returns its value as a bit.</p>


<p>If the field is unset, sets Unset to true and returns false.</p>


<p>Declaration at line 1911 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3193 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1440b4c6fda0655f260750f386c9d92a">getLoc</a>, <a href="#a9864f9add0da57a2c4f036a6110b313b">getName</a>, <a href="#a5e084b9b417ae456b128ee1f6506b41d">getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>.</p>

</div>
</div>

### getValueAsBitsInit() {#ad7b428bd00e5250c79391d22968b029d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BitsInit * Record::getValueAsBitsInit (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method looks up the specified field and returns its value as a <a href="/web-llvm/docs/api/classes/llvm/bitsinit">BitsInit</a>, throwing an exception if the field does not exist or if the value is not the right type.</p>

<p>Declaration at line 1871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3070 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1440b4c6fda0655f260750f386c9d92a">getLoc</a>, <a href="#a9864f9add0da57a2c4f036a6110b313b">getName</a>, <a href="#a5e084b9b417ae456b128ee1f6506b41d">getValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>.</p>

</div>
</div>

### getValueAsDag() {#a555a8bf98d04f42bf54b2d8dc8e546ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DagInit * Record::getValueAsDag (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method looks up the specified field and returns its value as an Dag, throwing an exception if the field does not exist or if the value is not the right type.</p>

<p>Declaration at line 1921 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3210 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1440b4c6fda0655f260750f386c9d92a">getLoc</a>, <a href="#a9864f9add0da57a2c4f036a6110b313b">getName</a>, <a href="#a5e084b9b417ae456b128ee1f6506b41d">getValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>.</p>

</div>
</div>

### getValueAsDef() {#a48d62ac5aec02b75a17f28fcd62fe47a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Record * Record::getValueAsDef (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method looks up the specified field and returns its value as a <a href="/web-llvm/docs/api/classes/llvm/record">Record</a>, throwing an exception if the field does not exist or if the value is not the right type.</p>

<p>Declaration at line 1896 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3155 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1440b4c6fda0655f260750f386c9d92a">getLoc</a>, <a href="#a9864f9add0da57a2c4f036a6110b313b">getName</a>, <a href="#a5e084b9b417ae456b128ee1f6506b41d">getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a> and <a href="#a98b09e526bfdb38ffb4a256f8cb6629a">Record</a>.</p>

</div>
</div>

### getValueAsInt() {#af3d85a78d044fdbacc61fb65d9530175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t Record::getValueAsInt (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method looks up the specified field and returns its value as an int64_t, throwing an exception if the field does not exist or if the value is not the right type.</p>

<p>Declaration at line 1916 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3109 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1440b4c6fda0655f260750f386c9d92a">getLoc</a>, <a href="#a9864f9add0da57a2c4f036a6110b313b">getName</a>, <a href="#a5e084b9b417ae456b128ee1f6506b41d">getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/lessrecordregister/#a1a0f91d255d85953130c7fc6c3a416ff">llvm::LessRecordRegister::operator()</a>.</p>

</div>
</div>

### getValueAsListInit() {#a9cb5b176fd3d90b85393bc1835dfa92f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ListInit * Record::getValueAsListInit (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method looks up the specified field and returns its value as a <a href="/web-llvm/docs/api/classes/llvm/listinit">ListInit</a>, throwing an exception if the field does not exist or if the value is not the right type.</p>

<p>Declaration at line 1876 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3082 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1440b4c6fda0655f260750f386c9d92a">getLoc</a>, <a href="#a9864f9add0da57a2c4f036a6110b313b">getName</a>, <a href="#a5e084b9b417ae456b128ee1f6506b41d">getValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>.</p>


<p>Referenced by <a href="#a2a8bf35316edb5fd57d98f2eda72581b">getValueAsListOfDefs</a>, <a href="#a01c6cc1360f4cc0cfec84038958a2a1e">getValueAsListOfInts</a> and <a href="#a5c14eff6d45e790bba2152e6e8da4d50">getValueAsListOfStrings</a>.</p>

</div>
</div>

### getValueAsListOfDefs() {#a2a8bf35316edb5fd57d98f2eda72581b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; const Record * &gt; Record::getValueAsListOfDefs (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method looks up the specified field and returns its value as a vector of records, throwing an exception if the field does not exist or if the value is not the right type.</p>

<p>Declaration at line 1881 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3095 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1440b4c6fda0655f260750f386c9d92a">getLoc</a>, <a href="#a9864f9add0da57a2c4f036a6110b313b">getName</a>, <a href="#a9cb5b176fd3d90b85393bc1835dfa92f">getValueAsListInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>.</p>

</div>
</div>

### getValueAsListOfInts() {#a01c6cc1360f4cc0cfec84038958a2a1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; int64_t &gt; Record::getValueAsListOfInts (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method looks up the specified field and returns its value as a vector of integers, throwing an exception if the field does not exist or if the value is not the right type.</p>

<p>Declaration at line 1886 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3124 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1440b4c6fda0655f260750f386c9d92a">getLoc</a>, <a href="#a9864f9add0da57a2c4f036a6110b313b">getName</a>, <a href="#a9cb5b176fd3d90b85393bc1835dfa92f">getValueAsListInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>.</p>

</div>
</div>

### getValueAsListOfStrings() {#a5c14eff6d45e790bba2152e6e8da4d50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; StringRef &gt; Record::getValueAsListOfStrings (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method looks up the specified field and returns its value as a vector of strings, throwing an exception if the field does not exist or if the value is not the right type.</p>

<p>Declaration at line 1891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3140 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1440b4c6fda0655f260750f386c9d92a">getLoc</a>, <a href="#a9864f9add0da57a2c4f036a6110b313b">getName</a>, <a href="#a9cb5b176fd3d90b85393bc1835dfa92f">getValueAsListInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>.</p>

</div>
</div>

### getValueAsOptionalDef() {#a833c8929e04fea46caae8e47a768b19c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Record * Record::getValueAsOptionalDef (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method looks up the specified field and returns its value as a <a href="/web-llvm/docs/api/classes/llvm/record">Record</a>, returning null if the field exists but is "uninitialized" (i.e.</p>


<p>set to <span class="doxyComputerOutput">?</span>), and throwing an exception if the field does not exist or if its value is not the right type.</p>


<p>Declaration at line 1902 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3167 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1440b4c6fda0655f260750f386c9d92a">getLoc</a>, <a href="#a9864f9add0da57a2c4f036a6110b313b">getName</a>, <a href="#a5e084b9b417ae456b128ee1f6506b41d">getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a> and <a href="#a98b09e526bfdb38ffb4a256f8cb6629a">Record</a>.</p>

</div>
</div>

### getValueAsOptionalString() {#ace6e85f8f0adf0c51140965bcd4dfe47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; StringRef &gt; Record::getValueAsOptionalString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method looks up the specified field and returns its value as a string, throwing an exception if the value is not a string and std::nullopt if the field does not exist.</p>

<p>Declaration at line 1866 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3055 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1440b4c6fda0655f260750f386c9d92a">getLoc</a>, <a href="#a9864f9add0da57a2c4f036a6110b313b">getName</a>, <a href="#a5e084b9b417ae456b128ee1f6506b41d">getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>.</p>


<p>Referenced by <a href="#afdb8b506ae2f062a5d33977cb0164ae1">getValueAsString</a>.</p>

</div>
</div>

### getValueAsString() {#afdb8b506ae2f062a5d33977cb0164ae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Record::getValueAsString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method looks up the specified field and returns its value as a string, throwing an exception if the field does not exist or if the value is not a string.</p>

<p>Declaration at line 1861 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3046 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="#a1440b4c6fda0655f260750f386c9d92a">getLoc</a>, <a href="#a9864f9add0da57a2c4f036a6110b313b">getName</a>, <a href="#ace6e85f8f0adf0c51140965bcd4dfe47">getValueAsOptionalString</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/lessrecordfieldname/#a8bfc87b0396d770ac3a5f8cb1c5f554d">llvm::LessRecordFieldName::operator()</a>.</p>

</div>
</div>

### getValueInit() {#a089bb78f5beac2fe715611c4d02a7e7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * Record::getValueInit (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the initializer for a value with the specified name, or throw an exception if the field does not exist.</p>

<p>Declaration at line 1851 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 3038 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="#a1440b4c6fda0655f260750f386c9d92a">getLoc</a>, <a href="#a9864f9add0da57a2c4f036a6110b313b">getName</a>, <a href="#a5e084b9b417ae456b128ee1f6506b41d">getValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>.</p>


<p>Referenced by <a href="#a66ba3203edbbeb2a97f6173e91ebea03">isValueUnset</a>.</p>

</div>
</div>

### getValues() {#aaef6f613ea9bdda33119d7f9cb0e9c93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; RecordVal &gt; llvm::Record::getValues ()</td>
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



<p>Definition at line 1716 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-detailedrecordsbackend-cpp-/detailedrecordsemitter/#a3f17021840c979ef6923eea86d0902bf">anonymous{DetailedRecordsBackend.cpp}::DetailedRecordsEmitter::printFields</a>.</p>

</div>
</div>

### hasDirectSuperClass() {#a8b6fc6699e686f04ca76a628511741b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Record::hasDirectSuperClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * SuperClass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether this record has the specified direct superclass.</p>

<p>Declaration at line 1726 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 2915 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="#a0fb8b12f752de40d45948ad282c6bf84">getSuperClasses</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a98b09e526bfdb38ffb4a256f8cb6629a">Record</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-detailedrecordsbackend-cpp-/detailedrecordsemitter/#aff15dd7156e8ad1d38a077572c0fe4f0">anonymous{DetailedRecordsBackend.cpp}::DetailedRecordsEmitter::printSuperclasses</a>.</p>

</div>
</div>

### isAnonymous() {#a2d059bdd553c32f0fa98ecf85a2dac11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Record::isAnonymous ()</td>
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



<p>Definition at line 1712 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#a114bcc21e64090aed664efd18a36dea7a86506ee7f447f18252d267dd158b830f">RK_AnonymousDef</a>.</p>

</div>
</div>

### isClass() {#a9728bfb7958a78fdcc4e57743bff542b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Record::isClass ()</td>
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



<p>Definition at line 1708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#a114bcc21e64090aed664efd18a36dea7a6d12ac1df82d81779e1abe932a8691c4">RK_Class</a>.</p>

</div>
</div>

### isMultiClass() {#a7480b7bdef6b981752b4c50f885513f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Record::isMultiClass ()</td>
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



<p>Definition at line 1710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#a114bcc21e64090aed664efd18a36dea7aad5a83addcf4215ddf8139baeef697d7">RK_MultiClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp/#a678066d868a6e0abb3151be33bb7232e">QualifyName</a>.</p>

</div>
</div>

### isSubClassOf() {#aa89c785d5856324faf763817eb091191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Record::isSubClassOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * R)</td>
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



<p>Definition at line 1796 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a> and <a href="#a98b09e526bfdb38ffb4a256f8cb6629a">Record</a>.</p>


<p>Referenced by <a href="#af8c64865cb640ca5ba8ba40c3deef870">addSuperClass</a> and <a href="/web-llvm/docs/api/classes/llvm/recordrecty/#a0db0c050e6199361f8a6d9f40d2d179c">llvm::RecordRecTy::isSubClassOf</a>.</p>

</div>
</div>

### isSubClassOf() {#a9b4a7a3640fe5f917ba40dedfaa50e28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Record::isSubClassOf (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 1803 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

### isTemplateArg() {#a9a175c899ffaa6ddfc6c4ce2f823c042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Record::isTemplateArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * Name)</td>
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



<p>Definition at line 1731 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>


<p>Referenced by <a href="#a615cb9834d2d4b12644f9d534f677e69">addTemplateArg</a>, <a href="/web-llvm/docs/api/classes/llvm/tgvarscope/#ae579c02468ab9307ae959877d8375ada">llvm::TGVarScope::getVar</a> and <a href="/web-llvm/docs/api/classes/anonymous-detailedrecordsbackend-cpp-/detailedrecordsemitter/#a3f17021840c979ef6923eea86d0902bf">anonymous{DetailedRecordsBackend.cpp}::DetailedRecordsEmitter::printFields</a>.</p>

</div>
</div>

### isValueUnset() {#a66ba3203edbbeb2a97f6173e91ebea03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Record::isValueUnset (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName)</td>
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

<p>Return true if the named field is unset.</p>

<p>Definition at line 1854 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="#a089bb78f5beac2fe715611c4d02a7e7b">getValueInit</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### removeValue() {#ad283a32d567fb8d357aec7b38ac8d90f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Record::removeValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * Name)</td>
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



<p>Definition at line 1765 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="#af1d89cc30867b3edb73449f0577ec5b2">getNameInit</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a44d44347281bf94a07c74f388d64b346">removeValue</a>.</p>

</div>
</div>

### removeValue() {#a44d44347281bf94a07c74f388d64b346}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Record::removeValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 1774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringinit/#a63edb20ca7b47e34fcb1f8df74d6424f">llvm::StringInit::get</a>, <a href="#a507c8dc2db4f450446681404934ce237">getRecords</a> and <a href="#ad283a32d567fb8d357aec7b38ac8d90f">removeValue</a>.</p>

</div>
</div>

### resolveReferences() {#ac7a3d6d05ef3aa1203cab2e1d57957cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Record::resolveReferences (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * NewName=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If there are any field references that refer to fields that have been filled in, we can propagate the values now.</p>


<p>This is a final resolve: any error messages, e.g. due to undefined !cast references, are generated now.</p>


<p>Declaration at line 1827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 2983 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Reference <a href="#ac7a3d6d05ef3aa1203cab2e1d57957cc">resolveReferences</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fieldinit/#ad617a1e50a36876352cc0dc9228636a0">llvm::FieldInit::resolveReferences</a> and <a href="#ac7a3d6d05ef3aa1203cab2e1d57957cc">resolveReferences</a>.</p>

</div>
</div>

### resolveReferences() {#a14ef30a60513d26f82c93d796deb7494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Record::resolveReferences (<a href="/web-llvm/docs/api/classes/llvm/resolver">Resolver</a> &amp; R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recordval">RecordVal</a> * SkipVal=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply the resolver to the name of the record as well as to the initializers of all fields of the record except SkipVal.</p>


<p>The resolver should not resolve any of the fields itself, to avoid recursion / infinite loops.</p>


<p>Declaration at line 1834 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 2939 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/init/#a285d0b93e0c8992d281d0cf4c89e37b7">llvm::Init::getAsUnquotedString</a>, <a href="#a1440b4c6fda0655f260750f386c9d92a">getLoc</a>, <a href="#af1d89cc30867b3edb73449f0577ec5b2">getNameInit</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>, <a href="/web-llvm/docs/api/classes/llvm/init/#a00581957c4bb1587a458c3fbf4326f7a">llvm::Init::resolveReferences</a> and <a href="#a9a228a28f0c4bc8a85e0281e7079578c">setName</a>.</p>

</div>
</div>

### setName() {#a9a228a28f0c4bc8a85e0281e7079578c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Record::setName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1684 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 2894 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#a14ef30a60513d26f82c93d796deb7494">resolveReferences</a>.</p>

</div>
</div>

### updateClassLoc() {#ad47a1bf1b6f941e37a463d942f573d0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Record::updateClassLoc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 2860 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### checkName() {#a43c1dd9623bfc78d0e82ef45bf60742a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Record::checkName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 2868 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Assertions {#a50a8de9b10d9c268ace456b11545fac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AssertionInfo, 0&gt; llvm::Record::Assertions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### CorrespondingDefInit {#a08366f3dc266374fd7afe9dcf9c3344c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefInit* llvm::Record::CorrespondingDefInit = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### Dumps {#a69b7da8bc6b8a4b4adee5a7c424c0142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DumpInfo, 0&gt; llvm::Record::Dumps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1631 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### ForwardDeclarationLocs {#a3ea6b97c46bb9434c7eafcc877c88c05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SMLoc, 0&gt; llvm::Record::ForwardDeclarationLocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### ID {#a56908536ba77a3df40bfa0030137d8f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Record::ID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### Kind {#ae40fd3052f5e2558474d75ecbff30aaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordKind llvm::Record::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### Locs {#a19fc5d63bd1d9f24f04a2be0bc15273e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SMLoc, 4&gt; llvm::Record::Locs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1625 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### Name {#a8ef2b33c2fd2813f8f8ae0b9ca496745}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init* llvm::Record::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1621 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### ReferenceLocs {#aa281cd31b3147d292a68f6407d3fb755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SMRange, 0&gt; llvm::Record::ReferenceLocs</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1627 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### SuperClasses {#a8ad8fbd83d2a4869d6c416531df3db61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;const Record *, SMRange&gt;, 0&gt; llvm::Record::SuperClasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### TemplateArgs {#a2364707405d7874d0db87b512a4d8870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const Init *, 0&gt; llvm::Record::TemplateArgs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### TrackedRecords {#acab0626f7a206d88d0c60556934dc217}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordKeeper&amp; llvm::Record::TrackedRecords</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1638 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### Values {#a509d1b5b897b62cf3094d218f7d4efde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;RecordVal, 0&gt; llvm::Record::Values</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getNewUID() {#a135a92f99d0c34b158c54a1f3191dae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Record::getNewUID (<a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp; RK)</td>
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



<p>Declaration at line 1672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 2890 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/recordkeeper/#a6fba1bfb826082df62c2dcb3062c2055">llvm::RecordKeeper::getImpl</a> and <a href="/web-llvm/docs/api/structs/llvm/detail/recordkeeperimpl/#a3ec9fd69ba3f48d5706ab65078de3103">llvm::detail::RecordKeeperImpl::LastRecordID</a>.</p>


<p>Referenced by <a href="#a98b09e526bfdb38ffb4a256f8cb6629a">Record</a> and <a href="#a647a7453aa46d3ca88be0cd677d95af3">Record</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
