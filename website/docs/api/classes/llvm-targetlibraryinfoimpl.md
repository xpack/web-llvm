---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/targetlibraryinfoimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TargetLibraryInfoImpl` Class Reference

<p>Implementation of the target library information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::TargetLibraryInfoImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AvailabilityState { <a href="#a63024b6bdc28b05ace65a47c88f3f32c">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">VectorLibrary { <a href="#abec3cb7868d54c3e24de1dcbc499ffd0">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of known vector-functions libraries. <a href="#abec3cb7868d54c3e24de1dcbc499ffd0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1057141b0b5fe32f5b222b166352c215">TargetLibraryInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a808f8afa53cb0a981fb9e6bec75fb4">TargetLibraryInfoImpl</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2039d7fdda0459345ad2b721b0045e6c">TargetLibraryInfoImpl</a> (const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1436c0342ea2697c5a7fbda33c37d110">TargetLibraryInfoImpl</a> (const TargetLibraryInfoImpl &amp;TLI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada4eb09e8a9ffacd356ab17ec22d614a">TargetLibraryInfoImpl</a> (TargetLibraryInfoImpl &amp;&amp;TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl">TargetLibraryInfoImpl</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89b3a61bc94dd2ca3a0745fb948493ee">operator=</a> (const TargetLibraryInfoImpl &amp;TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl">TargetLibraryInfoImpl</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7959a07d63fb3b89bc260aa0d9d4db4b">operator=</a> (TargetLibraryInfoImpl &amp;&amp;TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f382b34dc924b235282157869cb3771">getLibFunc</a> (StringRef funcName, LibFunc &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Searches for a particular function name. <a href="#a0f382b34dc924b235282157869cb3771">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b91ad1b09dab040d3519c054e473efb">getLibFunc</a> (const Function &amp;FDecl, LibFunc &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Searches for a particular function name, also checking that its type is valid for the library function matching that name. <a href="#a7b91ad1b09dab040d3519c054e473efb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea0b16a2a529ee0ca722019e0fa1223b">getLibFunc</a> (unsigned int Opcode, Type *Ty, LibFunc &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Searches for a function name using an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> <span class="doxyComputerOutput">Opcode</span>. <a href="#aea0b16a2a529ee0ca722019e0fa1223b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6596de0b1e303f7ba18ddc0f779ddbf">setUnavailable</a> (LibFunc F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Forces a function to be marked as unavailable. <a href="#ae6596de0b1e303f7ba18ddc0f779ddbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affe6e31638cfdceea39f7057043c22fc">setAvailable</a> (LibFunc F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Forces a function to be marked as available. <a href="#affe6e31638cfdceea39f7057043c22fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27e3c60feefa1643f8c8dafe485a1e1f">setAvailableWithName</a> (LibFunc F, StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Forces a function to be marked as available and provide an alternate name that must be used. <a href="#a27e3c60feefa1643f8c8dafe485a1e1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a288c0a7ef4bdf0b93570ca74fe9557">disableAllFunctions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disables all builtins. <a href="#a9a288c0a7ef4bdf0b93570ca74fe9557">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48a7797f18b04db2cf63dfb1c2bdbea4">addVectorizableFunctions</a> (ArrayRef&lt; VecDesc &gt; Fns)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a set of scalar -&gt; vector mappings, queryable via getVectorizedFunction and getScalarizedFunction. <a href="#a48a7797f18b04db2cf63dfb1c2bdbea4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32cf61958e13a95aaf8686f4c55aa873">addVectorizableFunctionsFromVecLib</a> (enum VectorLibrary VecLib, const llvm::Triple &amp;TargetTriple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calls addVectorizableFunctions with a known preset of functions for the given vector library. <a href="#a32cf61958e13a95aaf8686f4c55aa873">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dd4a22ee51a1f2aa2cef933db7e2efe">isFunctionVectorizable</a> (StringRef F, const ElementCount &amp;VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the function F has a vector equivalent with vectorization factor VF. <a href="#a1dd4a22ee51a1f2aa2cef933db7e2efe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a798028b6fc917a63c65f97cb29ab6b69">isFunctionVectorizable</a> (StringRef F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the function F has a vector equivalent with any vectorization factor. <a href="#a798028b6fc917a63c65f97cb29ab6b69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af667530bd9aae60938e2714fee3ee6b7">getVectorizedFunction</a> (StringRef F, const ElementCount &amp;VF, bool Masked) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the name of the equivalent of F, vectorized with factor VF. <a href="#af667530bd9aae60938e2714fee3ee6b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c36c8f36fd0fe73e2936da5f1479691">getVectorMappingInfo</a> (StringRef F, const ElementCount &amp;VF, bool Masked) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pointer to a <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a> object holding all info for scalar to vector mappings in TLI for the equivalent of F, vectorized with factor VF. <a href="#a4c36c8f36fd0fe73e2936da5f1479691">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0af42e0d2f497ae6b8a119353cda2045">setShouldExtI32Param</a> (bool Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set to true iff i32 parameters to library functions should have signext or zeroext attributes if they correspond to C-level int or unsigned int, respectively. <a href="#a0af42e0d2f497ae6b8a119353cda2045">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c0279b5745ccf4a95fde99be709cdf9">setShouldExtI32Return</a> (bool Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set to true iff i32 results from library functions should have signext or zeroext attributes if they correspond to C-level int or unsigned int, respectively. <a href="#a0c0279b5745ccf4a95fde99be709cdf9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22e9150ba078ca50c2abde31e5f73a09">setShouldSignExtI32Param</a> (bool Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set to true iff i32 parameters to library functions should have signext attribute if they correspond to C-level int or unsigned int. <a href="#a22e9150ba078ca50c2abde31e5f73a09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a871062b7cfb1949703c308ae3ec0da76">setShouldSignExtI32Return</a> (bool Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set to true iff i32 results from library functions should have signext attribute if they correspond to C-level int or unsigned int. <a href="#a871062b7cfb1949703c308ae3ec0da76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d2522d6b43bee40ae6397cd836599ee">getWCharSize</a> (const Module &amp;M) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size of the wchar_t type in bytes or 0 if the size is unknown. <a href="#a0d2522d6b43bee40ae6397cd836599ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39527ed4234b8b05235a356afbc6e418">getSizeTSize</a> (const Module &amp;M) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size of the size_t type in bits. <a href="#a39527ed4234b8b05235a356afbc6e418">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f303acb3c24624cd7e196de3ba539d5">getIntSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get size of a C-level int or unsigned int, in bits. <a href="#a2f303acb3c24624cd7e196de3ba539d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a364eae125640314f23d8c74bebc87062">setIntSize</a> (unsigned Bits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the C-level size of an integer. <a href="#a364eae125640314f23d8c74bebc87062">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15113486c66611b76318afc2c37352c3">getWidestVF</a> (StringRef ScalarF, ElementCount &amp;FixedVF, ElementCount &amp;Scalable) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the largest vectorization factor used in the list of vector functions. <a href="#a15113486c66611b76318afc2c37352c3">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17740d94aa62168df2d4275b7531fc98">setState</a> (LibFunc F, AvailabilityState State)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">AvailabilityState</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b6e0b189c3dc4744d1ec3d12c836740">getState</a> (LibFunc F) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a739d85807d072388535071f311039850">isValidProtoForLibFunc</a> (const FunctionType &amp;FTy, LibFunc F, const Module &amp;M) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the function type FTy is valid for the library function F, regardless of whether the function is available. <a href="#a739d85807d072388535071f311039850">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac83dea0dea0341ab92e2d3347624cfaf">AvailableArray</a>[(NumLibFuncs+3)/4]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a0534ecc5194a223cffaf01d9e2e1fc">CustomNames</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1bd22ad7fdad74ebd947325725c46c">ShouldExtI32Param</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cf138e500dd6ae08e1198e01a0fb89a">ShouldExtI32Return</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a142ce20c784ef3bf9189c4ce6fb68709">ShouldSignExtI32Param</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f3cf95fb4657745526f030c4a28a9b5">ShouldSignExtI32Return</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6416dbd46c899a3ae94c7cb59f9fe4a1">SizeOfInt</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fd55efcf0ee41a493bfd014abb5a93d">VectorDescs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vectorization descriptors - sorted by ScalarFnName. <a href="#a7fd55efcf0ee41a493bfd014abb5a93d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d28f09e6c01586547a4f9e8a8c62ceb">ScalarDescs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scalarization descriptors - same content as VectorDescs but sorted based on VectorFnName rather than ScalarFnName. <a href="#a9d28f09e6c01586547a4f9e8a8c62ceb">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fe2425902ca5775f3b350cfbe49cc8f">isCallingConvCCompatible</a> (CallBase *CI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if call site / callee has cdecl-compatible calling conventions. <a href="#a6fe2425902ca5775f3b350cfbe49cc8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94f0e652bb2136b88329b8e3d6e98c7d">isCallingConvCCompatible</a> (Function *Callee)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25f18c65ae6cd7186b1fc744904ef1c2">StandardNames</a>[NumLibFuncs] = ...</td>
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

<p>Implementation of the target library information.</p>


<p>This class constructs tables that hold the target library information and make it available. However, it is somewhat expensive to compute and only depends on the triple. So users typically interact with the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a></span> wrapper below.</p>


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### AvailabilityState {#a63024b6bdc28b05ace65a47c88f3f32c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TargetLibraryInfoImpl::AvailabilityState </td>
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
<td class="doxyEnumItemName">StandardName<a id="a63024b6bdc28b05ace65a47c88f3f32cadd32dba198a8df995054b90fdfa61723"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CustomName<a id="a63024b6bdc28b05ace65a47c88f3f32ca69bec6d1bf92976c32a4d70f0dbd6945"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unavailable<a id="a63024b6bdc28b05ace65a47c88f3f32caa911796b643c4158a47a242ce42592b1"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

### VectorLibrary {#abec3cb7868d54c3e24de1dcbc499ffd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TargetLibraryInfoImpl::VectorLibrary </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of known vector-functions libraries.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoLibrary<a id="abec3cb7868d54c3e24de1dcbc499ffd0aaffa58bff1e728e7f4a4362118cfd082"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Accelerate<a id="abec3cb7868d54c3e24de1dcbc499ffd0af076d4474d59ab5a0efc86d94870f2e5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DarwinLibSystemM<a id="abec3cb7868d54c3e24de1dcbc499ffd0a61ca8404d1203f719cd0f48109c529e5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LIBMVEC_X86<a id="abec3cb7868d54c3e24de1dcbc499ffd0ab0e4293663c61c643b1851edb142bbf1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MASSV<a id="abec3cb7868d54c3e24de1dcbc499ffd0a4992d44d29a3636609efced57fd02704"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SVML<a id="abec3cb7868d54c3e24de1dcbc499ffd0a6377df1b30e0cfcaced5ebafa0d2d0ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SLEEFGNUABI<a id="abec3cb7868d54c3e24de1dcbc499ffd0a7d7e07bb2e6138ddac20854c146d4945"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ArmPL<a id="abec3cb7868d54c3e24de1dcbc499ffd0aed2d4462f0f3887fee4fa6d184e0901b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMDLIBM<a id="abec3cb7868d54c3e24de1dcbc499ffd0aaad66d544007471f9a5cc933ac94ecd1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>The vector-functions library defines, which functions are vectorizable and with which factor. The library can be specified by either frontend, or a commandline option, and then used by addVectorizableFunctionsFromVecLib for filling up the tables of vectorizable functions.</p>


<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### TargetLibraryInfo {#a1057141b0b5fe32f5b222b166352c215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154ea389502cf750cbd7c05b635f4c76855ee">llvm::NumLibFuncs</a> and <a href="#a1057141b0b5fe32f5b222b166352c215">TargetLibraryInfo</a>.</p>


<p>Referenced by <a href="#a1057141b0b5fe32f5b222b166352c215">TargetLibraryInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TargetLibraryInfoImpl() {#a0a808f8afa53cb0a981fb9e6bec75fb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfoImpl::TargetLibraryInfoImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 923 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a641b5e25f1fd3d03c418a5a2aefd4b55">initializeBase</a>.</p>


<p>Referenced by <a href="#a89b3a61bc94dd2ca3a0745fb948493ee">operator=</a>, <a href="#a7959a07d63fb3b89bc260aa0d9d4db4b">operator=</a>, <a href="#a1436c0342ea2697c5a7fbda33c37d110">TargetLibraryInfoImpl</a> and <a href="#ada4eb09e8a9ffacd356ab17ec22d614a">TargetLibraryInfoImpl</a>.</p>

</div>
</div>

### TargetLibraryInfoImpl() {#a2039d7fdda0459345ad2b721b0045e6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfoImpl::TargetLibraryInfoImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
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



<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 929 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### TargetLibraryInfoImpl() {#a1436c0342ea2697c5a7fbda33c37d110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfoImpl::TargetLibraryInfoImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl">TargetLibraryInfoImpl</a> &amp; TLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 936 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Reference <a href="#a0a808f8afa53cb0a981fb9e6bec75fb4">TargetLibraryInfoImpl</a>.</p>

</div>
</div>

### TargetLibraryInfoImpl() {#ada4eb09e8a9ffacd356ab17ec22d614a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfoImpl::TargetLibraryInfoImpl (<a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl">TargetLibraryInfoImpl</a> &amp;&amp; TLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 947 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a0a808f8afa53cb0a981fb9e6bec75fb4">TargetLibraryInfoImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a89b3a61bc94dd2ca3a0745fb948493ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfoImpl &amp; TargetLibraryInfoImpl::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl">TargetLibraryInfoImpl</a> &amp; TLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 960 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Reference <a href="#a0a808f8afa53cb0a981fb9e6bec75fb4">TargetLibraryInfoImpl</a>.</p>

</div>
</div>

### operator=() {#a7959a07d63fb3b89bc260aa0d9d4db4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfoImpl &amp; TargetLibraryInfoImpl::operator= (<a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl">TargetLibraryInfoImpl</a> &amp;&amp; TLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 971 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Reference <a href="#a0a808f8afa53cb0a981fb9e6bec75fb4">TargetLibraryInfoImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addVectorizableFunctions() {#a48a7797f18b04db2cf63dfb1c2bdbea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetLibraryInfoImpl::addVectorizableFunctions (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a> &gt; Fns)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a set of scalar -&gt; vector mappings, queryable via getVectorizedFunction and getScalarizedFunction.</p>

<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 1268 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a79b4e70735dd5b20124a6e2deb08554e">compareByScalarFnName</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a86bd45de852039d3b7488453d737364a">compareByVectorFnName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="#a32cf61958e13a95aaf8686f4c55aa873">addVectorizableFunctionsFromVecLib</a>.</p>

</div>
</div>

### addVectorizableFunctionsFromVecLib() {#a32cf61958e13a95aaf8686f4c55aa873}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetLibraryInfoImpl::addVectorizableFunctionsFromVecLib (enum <a href="#abec3cb7868d54c3e24de1dcbc499ffd0">VectorLibrary</a> VecLib, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">llvm::Triple</a> &amp; TargetTriple)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calls addVectorizableFunctions with a known preset of functions for the given vector library.</p>

<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 1352 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">llvm::Triple::aarch64_be</a>, <a href="#abec3cb7868d54c3e24de1dcbc499ffd0af076d4474d59ab5a0efc86d94870f2e5">Accelerate</a>, <a href="#a48a7797f18b04db2cf63dfb1c2bdbea4">addVectorizableFunctions</a>, <a href="#abec3cb7868d54c3e24de1dcbc499ffd0aaad66d544007471f9a5cc933ac94ecd1">AMDLIBM</a>, <a href="#abec3cb7868d54c3e24de1dcbc499ffd0aed2d4462f0f3887fee4fa6d184e0901b">ArmPL</a>, <a href="#abec3cb7868d54c3e24de1dcbc499ffd0a61ca8404d1203f719cd0f48109c529e5">DarwinLibSystemM</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5fc23559f17bbe5ff83ec0fed0a5fdcf">llvm::Triple::getArch</a>, <a href="#abec3cb7868d54c3e24de1dcbc499ffd0ab0e4293663c61c643b1851edb142bbf1">LIBMVEC_X86</a>, <a href="#abec3cb7868d54c3e24de1dcbc499ffd0a4992d44d29a3636609efced57fd02704">MASSV</a>, <a href="#abec3cb7868d54c3e24de1dcbc499ffd0aaffa58bff1e728e7f4a4362118cfd082">NoLibrary</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae4763cb7c05a2a59ce27d51040bf4b08">llvm::Triple::riscv64</a>, <a href="#abec3cb7868d54c3e24de1dcbc499ffd0a7d7e07bb2e6138ddac20854c146d4945">SLEEFGNUABI</a>, <a href="#abec3cb7868d54c3e24de1dcbc499ffd0a6377df1b30e0cfcaced5ebafa0d2d0ac">SVML</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#af17c5f2cd95fecfd78453bb3d6105cfd">VecFuncs_Accelerate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#ab8f604cc3655a0f11ecdd458b39f089a">VecFuncs_AMDLIBM</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a99f444f3a78984f61a904239bcca012b">VecFuncs_ArmPL</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#acad27f01498f4940adaf11039f80f736">VecFuncs_DarwinLibSystemM</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#ac144d58061674e2d303867113dc0f6a2">VecFuncs_LIBMVEC_X86</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a1c23ee38c4d1bd844c40c2629913419c">VecFuncs_MASSV</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a5598458647d40357efc9e50b0394a93a">VecFuncs_SLEEFGNUABI_VF2</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a87860e9e51aaa5d9b98b584128651616">VecFuncs_SLEEFGNUABI_VF4</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#ae80d5658c79a70f7f7798946340a1f29">VecFuncs_SLEEFGNUABI_VFScalable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#af8f742526c2732949ecec896c0137123">VecFuncs_SLEEFGNUABI_VFScalableRISCV</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#adbccc26273cd15a1fa46a10b67064498">VecFuncs_SVML</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/driver/#aeaa83953f1c661c7a3bc7a4af4dc1efe">llvm::driver::createTLII</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a201c313701e8c03b7fd137205154ce37">initializeLibCalls</a>.</p>

</div>
</div>

### disableAllFunctions() {#a9a288c0a7ef4bdf0b93570ca74fe9557}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetLibraryInfoImpl::disableAllFunctions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Disables all builtins.</p>


<p>This can be used for options like -fno-builtin.</p>


<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 1252 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a201c313701e8c03b7fd137205154ce37">initializeLibCalls</a>.</p>

</div>
</div>

### getIntSize() {#a2f303acb3c24624cd7e196de3ba539d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetLibraryInfoImpl::getIntSize ()</td>
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

<p>Get size of a C-level int or unsigned int, in bits.</p>

<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

### getLibFunc() {#a0f382b34dc924b235282157869cb3771}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetLibraryInfoImpl::getLibFunc (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> funcName, <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Searches for a particular function name.</p>


<p>If it is one of the known library functions, return true and set F to the corresponding value.</p>


<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 1004 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#afa528cdb113dc770c1c34b1fa22a43eb">buildIndexMap</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a147437aa3b97e99609ae28aa1ee2eb32">sanitizeFunctionName</a>.</p>


<p>Referenced by <a href="#a7b91ad1b09dab040d3519c054e473efb">getLibFunc</a>.</p>

</div>
</div>

### getLibFunc() {#a7b91ad1b09dab040d3519c054e473efb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetLibraryInfoImpl::getLibFunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; FDecl, <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Searches for a particular function name, also checking that its type is valid for the library function matching that name.</p>


<p>If it is one of the known library functions, return true and set F to the corresponding value.</p>


<p>FDecl is assumed to have a parent <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> when using this function.</p>


<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 1221 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a21075305f0e463b24aafc2fb99514ace">llvm::Function::getFunctionType</a>, <a href="#a0f382b34dc924b235282157869cb3771">getLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a900a32da3983469187b1848189681705">llvm::Function::isIntrinsic</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154ea2552a9aa363fba3520d8e8e1a7eca566">llvm::NotLibFunc</a>.</p>

</div>
</div>

### getLibFunc() {#aea0b16a2a529ee0ca722019e0fa1223b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetLibraryInfoImpl::getLibFunc (unsigned int Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Searches for a function name using an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> <span class="doxyComputerOutput">Opcode</span>.</p>


<p>Currently, only the frem instruction is supported.</p>


<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 1242 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### getSizeTSize() {#a39527ed4234b8b05235a356afbc6e418}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetLibraryInfoImpl::getSizeTSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the size of the size_t type in bits.</p>

<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 1461 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### getVectorizedFunction() {#af667530bd9aae60938e2714fee3ee6b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef TargetLibraryInfoImpl::getVectorizedFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> &amp; VF, bool Masked)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the name of the equivalent of F, vectorized with factor VF.</p>


<p>If no such mapping exists, return the empty string.</p>


<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 1421 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/vecdesc/#add883df844825295deb679e3d6d27c8d">llvm::VecDesc::getVectorFnName</a>, <a href="#a4c36c8f36fd0fe73e2936da5f1479691">getVectorMappingInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a205029ee514828d0fb4988399ef3ece4a6864311f985d160ad4bd46a9fbe4a4d4">llvm::Masked</a>.</p>


<p>Referenced by <a href="#a1dd4a22ee51a1f2aa2cef933db7e2efe">isFunctionVectorizable</a>.</p>

</div>
</div>

### getVectorMappingInfo() {#a4c36c8f36fd0fe73e2936da5f1479691}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VecDesc * TargetLibraryInfoImpl::getVectorMappingInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> &amp; VF, bool Masked)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a pointer to a <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a> object holding all info for scalar to vector mappings in TLI for the equivalent of F, vectorized with factor VF.</p>


<p>If no such mapping exists, return nullpointer.</p>


<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 1431 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aea274b410e29fa114414f15aed1b6126">compareWithScalarFnName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a205029ee514828d0fb4988399ef3ece4a6864311f985d160ad4bd46a9fbe4a4d4">llvm::Masked</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a147437aa3b97e99609ae28aa1ee2eb32">sanitizeFunctionName</a>.</p>


<p>Referenced by <a href="#af667530bd9aae60938e2714fee3ee6b7">getVectorizedFunction</a>.</p>

</div>
</div>

### getWCharSize() {#a0d2522d6b43bee40ae6397cd836599ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetLibraryInfoImpl::getWCharSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the size of the wchar_t type in bytes or 0 if the size is unknown.</p>


<p>This queries the 'wchar_size' metadata.</p>


<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 1454 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>.</p>

</div>
</div>

### getWidestVF() {#a15113486c66611b76318afc2c37352c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetLibraryInfoImpl::getWidestVF (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ScalarF, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> &amp; FixedVF, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> &amp; Scalable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the largest vectorization factor used in the list of vector functions.</p>

<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 1503 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aea274b410e29fa114414f15aed1b6126">compareWithScalarFnName</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a1bddc4949ab247dd1474f79b9bc6e34e">llvm::ElementCount::getScalable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#addaa86bfa4ca26b7f366cbdd868f99bf">llvm::details::FixedOrScalableQuantity&lt; ElementCount, unsigned &gt;::isKnownGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a147437aa3b97e99609ae28aa1ee2eb32">sanitizeFunctionName</a>.</p>

</div>
</div>

### isFunctionVectorizable() {#a1dd4a22ee51a1f2aa2cef933db7e2efe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfoImpl::isFunctionVectorizable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> &amp; VF)</td>
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

<p>Return true if the function F has a vector equivalent with vectorization factor VF.</p>

<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#af667530bd9aae60938e2714fee3ee6b7">getVectorizedFunction</a>.</p>

</div>
</div>

### isFunctionVectorizable() {#a798028b6fc917a63c65f97cb29ab6b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetLibraryInfoImpl::isFunctionVectorizable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the function F has a vector equivalent with any vectorization factor.</p>

<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 1411 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aea274b410e29fa114414f15aed1b6126">compareWithScalarFnName</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a147437aa3b97e99609ae28aa1ee2eb32">sanitizeFunctionName</a>.</p>

</div>
</div>

### setAvailable() {#affe6e31638cfdceea39f7057043c22fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLibraryInfoImpl::setAvailable (<a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> F)</td>
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

<p>Forces a function to be marked as available.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a201c313701e8c03b7fd137205154ce37">initializeLibCalls</a>.</p>

</div>
</div>

### setAvailableWithName() {#a27e3c60feefa1643f8c8dafe485a1e1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLibraryInfoImpl::setAvailableWithName (<a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> F, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Forces a function to be marked as available and provide an alternate name that must be used.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a201c313701e8c03b7fd137205154ce37">initializeLibCalls</a>.</p>

</div>
</div>

### setIntSize() {#a364eae125640314f23d8c74bebc87062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLibraryInfoImpl::setIntSize (unsigned Bits)</td>
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

<p>Initialize the C-level size of an integer.</p>

<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a641b5e25f1fd3d03c418a5a2aefd4b55">initializeBase</a>.</p>

</div>
</div>

### setShouldExtI32Param() {#a0af42e0d2f497ae6b8a119353cda2045}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLibraryInfoImpl::setShouldExtI32Param (bool Val)</td>
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

<p>Set to true iff i32 parameters to library functions should have signext or zeroext attributes if they correspond to C-level int or unsigned int, respectively.</p>

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a641b5e25f1fd3d03c418a5a2aefd4b55">initializeBase</a>.</p>

</div>
</div>

### setShouldExtI32Return() {#a0c0279b5745ccf4a95fde99be709cdf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLibraryInfoImpl::setShouldExtI32Return (bool Val)</td>
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

<p>Set to true iff i32 results from library functions should have signext or zeroext attributes if they correspond to C-level int or unsigned int, respectively.</p>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a641b5e25f1fd3d03c418a5a2aefd4b55">initializeBase</a>.</p>

</div>
</div>

### setShouldSignExtI32Param() {#a22e9150ba078ca50c2abde31e5f73a09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLibraryInfoImpl::setShouldSignExtI32Param (bool Val)</td>
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

<p>Set to true iff i32 parameters to library functions should have signext attribute if they correspond to C-level int or unsigned int.</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a641b5e25f1fd3d03c418a5a2aefd4b55">initializeBase</a>.</p>

</div>
</div>

### setShouldSignExtI32Return() {#a871062b7cfb1949703c308ae3ec0da76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLibraryInfoImpl::setShouldSignExtI32Return (bool Val)</td>
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

<p>Set to true iff i32 results from library functions should have signext attribute if they correspond to C-level int or unsigned int.</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a641b5e25f1fd3d03c418a5a2aefd4b55">initializeBase</a>.</p>

</div>
</div>

### setUnavailable() {#ae6596de0b1e303f7ba18ddc0f779ddbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLibraryInfoImpl::setUnavailable (<a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> F)</td>
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

<p>Forces a function to be marked as unavailable.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a201c313701e8c03b7fd137205154ce37">initializeLibCalls</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getState() {#a7b6e0b189c3dc4744d1ec3d12c836740}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AvailabilityState llvm::TargetLibraryInfoImpl::getState (<a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> F)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

### isValidProtoForLibFunc() {#a739d85807d072388535071f311039850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetLibraryInfoImpl::isValidProtoForLibFunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> &amp; FTy, <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the function type FTy is valid for the library function F, regardless of whether the function is available.</p>

<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 1111 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### setState() {#a17740d94aa62168df2d4275b7531fc98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLibraryInfoImpl::setState (<a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> F, AvailabilityState State)</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AvailableArray {#ac83dea0dea0341ab92e2d3347624cfaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::TargetLibraryInfoImpl::AvailableArray[(NumLibFuncs+3)/4]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

### CustomNames {#a7a0534ecc5194a223cffaf01d9e2e1fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, std::string&gt; llvm::TargetLibraryInfoImpl::CustomNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

### ScalarDescs {#a9d28f09e6c01586547a4f9e8a8c62ceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;VecDesc&gt; llvm::TargetLibraryInfoImpl::ScalarDescs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scalarization descriptors - same content as VectorDescs but sorted based on VectorFnName rather than ScalarFnName.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

### ShouldExtI32Param {#a4a1bd22ad7fdad74ebd947325725c46c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfoImpl::ShouldExtI32Param</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

### ShouldExtI32Return {#a0cf138e500dd6ae08e1198e01a0fb89a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfoImpl::ShouldExtI32Return</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

### ShouldSignExtI32Param {#a142ce20c784ef3bf9189c4ce6fb68709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfoImpl::ShouldSignExtI32Param</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

### ShouldSignExtI32Return {#a7f3cf95fb4657745526f030c4a28a9b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfoImpl::ShouldSignExtI32Return</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

### SizeOfInt {#a6416dbd46c899a3ae94c7cb59f9fe4a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetLibraryInfoImpl::SizeOfInt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

### VectorDescs {#a7fd55efcf0ee41a493bfd014abb5a93d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;VecDesc&gt; llvm::TargetLibraryInfoImpl::VectorDescs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vectorization descriptors - sorted by ScalarFnName.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isCallingConvCCompatible() {#a6fe2425902ca5775f3b350cfbe49cc8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetLibraryInfoImpl::isCallingConvCCompatible (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CI)</td>
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

<p>Returns true if call site / callee has cdecl-compatible calling conventions.</p>

<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#a3ff92cec76009e859cb0c419d6e8ba5f">llvm::CallBase::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac3c35bd078a268a207f607d0f57dadba">llvm::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4ba3a5be6c0e9b9e8a525de055836733">llvm::Instruction::getModule</a> and <a href="/web-llvm/docs/api/classes/llvm/module/#a6b882824580b4666f692474ecbae56ad">llvm::Module::getTargetTriple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fortifiedlibcallsimplifier/#ab5f693b48590402b0109cfdca55ec335">llvm::FortifiedLibCallSimplifier::optimizeCall</a> and <a href="/web-llvm/docs/api/classes/llvm/libcallsimplifier/#a73c4a774eb638f963533b77f7124293b">llvm::LibCallSimplifier::optimizeCall</a>.</p>

</div>
</div>

### isCallingConvCCompatible() {#a94f0e652bb2136b88329b8e3d6e98c7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetLibraryInfoImpl::isCallingConvCCompatible (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Callee)</td>
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



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### StandardNames {#a25f18c65ae6cd7186b1fc744904ef1c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringLiteral const TargetLibraryInfoImpl::StandardNames</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    {
#define <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a970358d390596d6015cd0eae4228a062">TLI_DEFINE_STRING</a>
}
</div>
</dd>
</dl>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
