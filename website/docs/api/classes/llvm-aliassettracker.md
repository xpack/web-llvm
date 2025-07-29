---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/aliassettracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AliasSetTracker` Class



## Declaration

<div class="doxyDeclaration">
class llvm::AliasSetTracker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">llvm/Analysis/AliasSetTracker.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00e1f4c5cd973ec788f9a59a6b564e2b">iterator</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a62ea5abc9af8e7ee394912e2617cf30f">ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/aliasset">AliasSet</a> &gt;::iterator</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93a3d4068f6e0427fdfdf88527c7e872">const_iterator</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a62ea5abc9af8e7ee394912e2617cf30f">ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/aliasset">AliasSet</a> &gt;::const_iterator</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3449439a8e72a1fb5627ffcd57073bb">PointerMapType</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &gt;, <a href="/web-llvm/docs/api/classes/llvm/aliasset">AliasSet</a> * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab48ab06126e28c236eee55d10a4f0d74">AliasSet</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a738f215ea1a4af77ea2a9c58d8d1802e">AliasSetTracker</a> (BatchAAResults &amp;AA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an empty collection of AliasSets, and use the specified alias analysis object to disambiguate load and store addresses. <a href="#a738f215ea1a4af77ea2a9c58d8d1802e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeba38d21d3004632f1f0f5f4978b50a9">~AliasSetTracker</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacb988af7b411325fc0f2cf38461d2b1">add</a> (const MemoryLocation &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These methods are used to add different types of instructions to the alias sets. <a href="#aacb988af7b411325fc0f2cf38461d2b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f77b833b9cb8cf108202087d9447001">add</a> (LoadInst *LI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11a67620a6c96cb35ee7807c17ef442c">add</a> (StoreInst *SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af43e1f24119500a34bfc48484749bc3a">add</a> (VAArgInst *VAAI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7183c62524bf8d91b7e41f64f413471a">add</a> (AnyMemSetInst *MSI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8b0110e87b923144a45219d5be8f4e4">add</a> (AnyMemTransferInst *MTI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28c431daa68824e2c7f8721bf495fc25">add</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb03aaafd0fb715515a12108fffbf83e">add</a> (BasicBlock &amp;BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46d699031a20d6ad356a875e20d0ba6d">add</a> (const AliasSetTracker &amp;AST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f720c5ed38312535b0080ccba56a53b">addUnknown</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9578c350fd9a2879f771cedb6d32d13">clear</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a62ea5abc9af8e7ee394912e2617cf30f">ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/aliasset">AliasSet</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a216ac9053e366fde72c44793ecfade1a">getAliasSets</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the alias sets that are active. <a href="#a216ac9053e366fde72c44793ecfade1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aliasset">AliasSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a439aa4acfd3dcd5b1cada30cbecbd189">getAliasSetFor</a> (const MemoryLocation &amp;MemLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the alias set which contains the specified memory location. <a href="#a439aa4acfd3dcd5b1cada30cbecbd189">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a277249512798387d0ea61ab26a79ad48">getAliasAnalysis</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the underlying alias analysis object used by this tracker. <a href="#a277249512798387d0ea61ab26a79ad48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a93a3d4068f6e0427fdfdf88527c7e872">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95113542162d2cb86f32ec712f3f3441">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a93a3d4068f6e0427fdfdf88527c7e872">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc6560f4a6d0d1fa11470f7490f421d">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a00e1f4c5cd973ec788f9a59a6b564e2b">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba7c28694a4aa40870005d566e9645cd">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a00e1f4c5cd973ec788f9a59a6b564e2b">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1ca3b0581291a13b3fc310939ca3015">end</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b1d62bcca06f2c31c35c7f17965b008">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fddd270f1f51237933f224d12b1d26e">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac595b6fbb82e677f0f25a64b8124c2f1">removeAliasSet</a> (AliasSet *AS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af07f901881e518c25b5948571ec73ff2">collapseForwardingIn</a> (AliasSet *&amp;AS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aliasset">AliasSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8b7331818d9dd1900bd0367f914f33c">addMemoryLocation</a> (MemoryLocation Loc, AliasSet::AccessLattice E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aliasset">AliasSet</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f45e0ad9d902841e9b0333eff705bfd">mergeAliasSetsForMemoryLocation</a> (const MemoryLocation &amp;MemLoc, AliasSet *PtrAS, bool &amp;MustAliasAll)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>mergeAliasSetsForMemoryLocation - Given a memory location, merge all alias sets that may alias it. <a href="#a9f45e0ad9d902841e9b0333eff705bfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aliasset">AliasSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9268189bb53c7645a201e1a18d7f8819">mergeAllAliasSets</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge all alias sets into a single set that is considered to alias any memory location or instruction. <a href="#a9268189bb53c7645a201e1a18d7f8819">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aliasset">AliasSet</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3714307656257492f1106873ae7bb070">findAliasSetForUnknownInst</a> (Instruction *Inst)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43d77a19b804763d3869e0929e38579b">AA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a62ea5abc9af8e7ee394912e2617cf30f">ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/aliasset">AliasSet</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a450689dcf478fdd5ab6682ae52fb0dde">AliasSets</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">PointerMapType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d94c484d6e7468f55d063f4d7fc4de9">PointerMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f8071c4713c6c5464be30c718881554">TotalAliasSetSize</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aliasset">AliasSet</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd2ba131082352890fc827e8f4b3652">AliasAnyAS</a> = nullptr</td>
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


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a93a3d4068f6e0427fdfdf88527c7e872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AliasSetTracker::const_iterator =  ilist&lt;AliasSet&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>

</div>
</div>

### iterator {#a00e1f4c5cd973ec788f9a59a6b564e2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AliasSetTracker::iterator =  ilist&lt;AliasSet&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### PointerMapType {#ab3449439a8e72a1fb5627ffcd57073bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AliasSetTracker::PointerMapType =  DenseMap&lt;AssertingVH&lt;const Value&gt;, AliasSet *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### AliasSet {#ab48ab06126e28c236eee55d10a4f0d74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/aliasset">AliasSet</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>


<p>Reference <a href="#ab48ab06126e28c236eee55d10a4f0d74">AliasSet</a>.</p>


<p>Referenced by <a href="#a46d699031a20d6ad356a875e20d0ba6d">add</a>, <a href="#a5f720c5ed38312535b0080ccba56a53b">addUnknown</a>, <a href="#ab48ab06126e28c236eee55d10a4f0d74">AliasSet</a>, <a href="#a439aa4acfd3dcd5b1cada30cbecbd189">getAliasSetFor</a> and <a href="#a9b1d62bcca06f2c31c35c7f17965b008">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AliasSetTracker() {#a738f215ea1a4af77ea2a9c58d8d1802e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AliasSetTracker::AliasSetTracker (<a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; AA)</td>
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

<p>Create an empty collection of AliasSets, and use the specified alias analysis object to disambiguate load and store addresses.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>


<p>Referenced by <a href="#a46d699031a20d6ad356a875e20d0ba6d">add</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AliasSetTracker() {#aeba38d21d3004632f1f0f5f4978b50a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AliasSetTracker::~AliasSetTracker ()</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>


<p>Reference <a href="#ac9578c350fd9a2879f771cedb6d32d13">clear</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#aacb988af7b411325fc0f2cf38461d2b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AliasSetTracker::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>These methods are used to add different types of instructions to the alias sets.</p>


<p>Adding a new instruction can result in one of three actions happening:</p>


<ol class="doxyList" type="1">
<li>If the instruction doesn't alias any other sets, create a new set.</li>
<li>If the instruction aliases exactly one set, add it to the set</li>
<li>If the instruction aliases multiple sets, merge the sets, and add the instruction to the result.</li>
</ol>

<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>


<p>Referenced by <a href="#afb03aaafd0fb715515a12108fffbf83e">add</a>, <a href="#a46d699031a20d6ad356a875e20d0ba6d">add</a>, <a href="#a28c431daa68824e2c7f8721bf495fc25">add</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a37ddbdd8cb4efa5072282498fdc1ac65">collectPromotionCandidates</a> and <a href="/web-llvm/docs/api/classes/llvm/aliassetsprinterpass/#a3a8a27458f2832e65ace0c61bb035be7">llvm::AliasSetsPrinterPass::run</a>.</p>

</div>
</div>

### add() {#a7f77b833b9cb8cf108202087d9447001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AliasSetTracker::add (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>


<p>References <a href="#a5f720c5ed38312535b0080ccba56a53b">addUnknown</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a18e5a3f1d71ba10a624f2a8e5121cf1f">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a93603fe0d4168b92a901f06015ecb2e7">llvm::LoadInst::getOrdering</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a230fb4d924829b7649a5fb112dcbe9f8">llvm::isStrongerThanMonotonic</a>.</p>

</div>
</div>

### add() {#a11a67620a6c96cb35ee7807c17ef442c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AliasSetTracker::add (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>


<p>References <a href="#a5f720c5ed38312535b0080ccba56a53b">addUnknown</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a18e5a3f1d71ba10a624f2a8e5121cf1f">llvm::MemoryLocation::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a230fb4d924829b7649a5fb112dcbe9f8">llvm::isStrongerThanMonotonic</a>.</p>

</div>
</div>

### add() {#af43e1f24119500a34bfc48484749bc3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AliasSetTracker::add (<a href="/web-llvm/docs/api/classes/llvm/vaarginst">VAArgInst</a> * VAAI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a18e5a3f1d71ba10a624f2a8e5121cf1f">llvm::MemoryLocation::get</a>.</p>

</div>
</div>

### add() {#a7183c62524bf8d91b7e41f64f413471a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AliasSetTracker::add (<a href="/web-llvm/docs/api/classes/llvm/anymemsetinst">AnyMemSetInst</a> * MSI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#ac8f8983c6b76d0e30f22fff86b281f16">llvm::MemoryLocation::getForDest</a>.</p>

</div>
</div>

### add() {#ad8b0110e87b923144a45219d5be8f4e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AliasSetTracker::add (<a href="/web-llvm/docs/api/classes/llvm/anymemtransferinst">AnyMemTransferInst</a> * MTI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#ac8f8983c6b76d0e30f22fff86b281f16">llvm::MemoryLocation::getForDest</a> and <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a207e239d68b66b0d5ccad5997a5ef027">llvm::MemoryLocation::getForSource</a>.</p>

</div>
</div>

### add() {#a28c431daa68824e2c7f8721bf495fc25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AliasSetTracker::add (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>


<p>References <a href="#aacb988af7b411325fc0f2cf38461d2b1">add</a>, <a href="#a5f720c5ed38312535b0080ccba56a53b">addUnknown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#afc51de08aefeeaabc77fefacc869dbd4">llvm::MemoryLocation::getForArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a728f79528ca8659e15d00c1e6818b316">llvm::isModSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae96dbd1485a431400525ca17896ec48e">llvm::isNoModRef</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7787f6b577cd7a63f043b87301b8e81">llvm::isRefSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### add() {#afb03aaafd0fb715515a12108fffbf83e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AliasSetTracker::add (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>


<p>References <a href="#aacb988af7b411325fc0f2cf38461d2b1">add</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### add() {#a46d699031a20d6ad356a875e20d0ba6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AliasSetTracker::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aliassettracker">AliasSetTracker</a> &amp; AST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>


<p>References <a href="#aacb988af7b411325fc0f2cf38461d2b1">add</a>, <a href="#ab48ab06126e28c236eee55d10a4f0d74">AliasSet</a>, <a href="#a738f215ea1a4af77ea2a9c58d8d1802e">AliasSetTracker</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### addUnknown() {#a5f720c5ed38312535b0080ccba56a53b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AliasSetTracker::addUnknown (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>


<p>References <a href="#ab48ab06126e28c236eee55d10a4f0d74">AliasSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a2d77b9d450543e86acb394ff6dda6b53">llvm::Instruction::mayReadOrWriteMemory</a>.</p>


<p>Referenced by <a href="#a28c431daa68824e2c7f8721bf495fc25">add</a>, <a href="#a7f77b833b9cb8cf108202087d9447001">add</a> and <a href="#a11a67620a6c96cb35ee7807c17ef442c">add</a>.</p>

</div>
</div>

### begin() {#a95113542162d2cb86f32ec712f3f3441}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::AliasSetTracker::begin ()</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>

</div>
</div>

### begin() {#aba7c28694a4aa40870005d566e9645cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::AliasSetTracker::begin ()</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>

</div>
</div>

### clear() {#ac9578c350fd9a2879f771cedb6d32d13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AliasSetTracker::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>.</p>


<p>Referenced by <a href="#aeba38d21d3004632f1f0f5f4978b50a9">~AliasSetTracker</a>.</p>

</div>
</div>

### dump() {#a1fddd270f1f51237933f224d12b1d26e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void AliasSetTracker::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a9b1d62bcca06f2c31c35c7f17965b008">print</a>.</p>

</div>
</div>

### end() {#a7cc6560f4a6d0d1fa11470f7490f421d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::AliasSetTracker::end ()</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>

</div>
</div>

### end() {#aa1ca3b0581291a13b3fc310939ca3015}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::AliasSetTracker::end ()</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>

</div>
</div>

### getAliasAnalysis() {#a277249512798387d0ea61ab26a79ad48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BatchAAResults &amp; llvm::AliasSetTracker::getAliasAnalysis ()</td>
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

<p>Return the underlying alias analysis object used by this tracker.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>

</div>
</div>

### getAliasSetFor() {#a439aa4acfd3dcd5b1cada30cbecbd189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasSet &amp; AliasSetTracker::getAliasSetFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; MemLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the alias set which contains the specified memory location.</p>


<p>If the memory location aliases two or more existing alias sets, will have the effect of merging those alias sets before the single resulting alias set is returned.</p>


<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>


<p>References <a href="#ab48ab06126e28c236eee55d10a4f0d74">AliasSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a9550ce4a179e46db37f653ce28feca7a">llvm::MemoryLocation::Ptr</a>.</p>

</div>
</div>

### getAliasSets() {#a216ac9053e366fde72c44793ecfade1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ilist&lt; AliasSet &gt; &amp; llvm::AliasSetTracker::getAliasSets ()</td>
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

<p>Return the alias sets that are active.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>

</div>
</div>

### print() {#a9b1d62bcca06f2c31c35c7f17965b008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AliasSetTracker::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>


<p>References <a href="#ab48ab06126e28c236eee55d10a4f0d74">AliasSet</a> and <a href="/web-llvm/docs/api/classes/llvm/aliasset/#a402ffc8c32cbcbcf858f1188ce7a4c87">llvm::AliasSet::print</a>.</p>


<p>Referenced by <a href="#a1fddd270f1f51237933f224d12b1d26e">dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5289ffe81af5752eec554b5c9eabb5b8">llvm::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/classes/llvm/aliassetsprinterpass/#a3a8a27458f2832e65ace0c61bb035be7">llvm::AliasSetsPrinterPass::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addMemoryLocation() {#ab8b7331818d9dd1900bd0367f914f33c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasSet &amp; AliasSetTracker::addMemoryLocation (<a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> Loc, AliasSet::AccessLattice E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>

</div>
</div>

### collapseForwardingIn() {#af07f901881e518c25b5948571ec73ff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AliasSetTracker::collapseForwardingIn (<a href="/web-llvm/docs/api/classes/llvm/aliasset">AliasSet</a> *&amp; AS)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>

</div>
</div>

### findAliasSetForUnknownInst() {#a3714307656257492f1106873ae7bb070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasSet * AliasSetTracker::findAliasSetForUnknownInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>

</div>
</div>

### mergeAliasSetsForMemoryLocation() {#a9f45e0ad9d902841e9b0333eff705bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasSet * AliasSetTracker::mergeAliasSetsForMemoryLocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; MemLoc, <a href="/web-llvm/docs/api/classes/llvm/aliasset">AliasSet</a> * PtrAS, bool &amp; MustAliasAll)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>mergeAliasSetsForMemoryLocation - Given a memory location, merge all alias sets that may alias it.</p>


<p>Return the unified set, or nullptr if no aliasing set was found. A known existing alias set for the pointer value of the memory location can be passed in (or nullptr if not available). MustAliasAll is updated to true/false if the memory location is found to MustAlias all the sets it merged.</p>


<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>

</div>
</div>

### mergeAllAliasSets() {#a9268189bb53c7645a201e1a18d7f8819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasSet &amp; AliasSetTracker::mergeAllAliasSets ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge all alias sets into a single set that is considered to alias any memory location or instruction.</p>

<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>

</div>
</div>

### removeAliasSet() {#ac595b6fbb82e677f0f25a64b8124c2f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AliasSetTracker::removeAliasSet (<a href="/web-llvm/docs/api/classes/llvm/aliasset">AliasSet</a> * AS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a43d77a19b804763d3869e0929e38579b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BatchAAResults&amp; llvm::AliasSetTracker::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>

</div>
</div>

### AliasAnyAS {#a9fd2ba131082352890fc827e8f4b3652}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasSet* llvm::AliasSetTracker::AliasAnyAS = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>

</div>
</div>

### AliasSets {#a450689dcf478fdd5ab6682ae52fb0dde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ilist&lt;AliasSet&gt; llvm::AliasSetTracker::AliasSets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>

</div>
</div>

### PointerMap {#a7d94c484d6e7468f55d063f4d7fc4de9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerMapType llvm::AliasSetTracker::PointerMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>

</div>
</div>

### TotalAliasSetSize {#a6f8071c4713c6c5464be30c718881554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AliasSetTracker::TotalAliasSetSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliassettracker-h">AliasSetTracker.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/aliassettracker-cpp">AliasSetTracker.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
