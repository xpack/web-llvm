---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/targetlibraryinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TargetLibraryInfo` Class Reference

<p>Provides information about what library functions are available for the current target. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::TargetLibraryInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebe96ee83ba64d58e8af6adb3c255bc6">TargetLibraryAnalysis</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9a409afc7f917489e6a8047bfb35b9d">TargetLibraryInfoWrapperPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9088608ebb8bafd853e87b7e7b4676b9">TargetLibraryInfo</a> (const TargetLibraryInfoImpl &amp;Impl, std::optional&lt; const Function * &gt; F=std::nullopt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72e15e0a0b87c3d3af56b39ca970a19e">TargetLibraryInfo</a> (const TargetLibraryInfo &amp;TLI)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adea9261bf534eaee448dc5f2f20e782d">TargetLibraryInfo</a> (TargetLibraryInfo &amp;&amp;TLI)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f563e571ecea362ba07e5e53ac18f7f">operator=</a> (const TargetLibraryInfo &amp;TLI)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad29a00bf2e9e46ae4551db26ee51c921">operator=</a> (TargetLibraryInfo &amp;&amp;TLI)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12588063ab5d62069b25e2a2d075f7fc">areInlineCompatible</a> (const TargetLibraryInfo &amp;CalleeTLI, bool AllowCallerSuperset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether a callee with the given TLI can be inlined into caller with this TLI, based on 'nobuiltin' attributes. <a href="#a12588063ab5d62069b25e2a2d075f7fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25b8b3cd7b0a1ee616b00ca9abcf0a0f">isValidProtoForLibFunc</a> (const FunctionType &amp;FTy, LibFunc F, const Module &amp;M) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the function type FTy is valid for the library function F, regardless of whether the function is available. <a href="#a25b8b3cd7b0a1ee616b00ca9abcf0a0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97cfbbed8869e3582142012a071a9052">getLibFunc</a> (StringRef funcName, LibFunc &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Searches for a particular function name. <a href="#a97cfbbed8869e3582142012a071a9052">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9672c6412ce53a4bc4ade8e99a7f4df1">getLibFunc</a> (const Function &amp;FDecl, LibFunc &amp;F) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a130c04c64f1ad6c7bea33c1aff8160be">getLibFunc</a> (const CallBase &amp;CB, LibFunc &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a callbase does not have the 'nobuiltin' attribute, return if the called function is a known library function and set F to that function. <a href="#a130c04c64f1ad6c7bea33c1aff8160be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0c44937de7747acc7756269f3d5641d">getLibFunc</a> (unsigned int Opcode, Type *Ty, LibFunc &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Searches for a function name using an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> <span class="doxyComputerOutput">Opcode</span>. <a href="#ac0c44937de7747acc7756269f3d5641d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71749cadcb51437084eb14c3f3bfea8a">disableAllFunctions</a> () LLVM_ATTRIBUTE_UNUSED</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disables all builtins. <a href="#a71749cadcb51437084eb14c3f3bfea8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a858bc32432a78550f43728ac033fa4ae">setUnavailable</a> (LibFunc F) LLVM_ATTRIBUTE_UNUSED</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Forces a function to be marked as unavailable. <a href="#a858bc32432a78550f43728ac033fa4ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">TargetLibraryInfoImpl::AvailabilityState</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6242b52990676d512b20a9611c760000">getState</a> (LibFunc F) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54699e3f128acda6003afc11d3027f6c">has</a> (LibFunc F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether a library function is available. <a href="#a54699e3f128acda6003afc11d3027f6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2dc370c0f0b837f18b006c2d4b8b7cc">isFunctionVectorizable</a> (StringRef F, const ElementCount &amp;VF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5412f8840a4b4e4a9644fd3674f21506">isFunctionVectorizable</a> (StringRef F) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac839c0e63d91f848aaf1290585e1fc25">getVectorizedFunction</a> (StringRef F, const ElementCount &amp;VF, bool Masked=false) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf95582fbff31ea4c597858e1112a6e8">getVectorMappingInfo</a> (StringRef F, const ElementCount &amp;VF, bool Masked) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38377afcf58b163cbb11662bdc2841a9">hasOptimizedCodeGen</a> (LibFunc F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if the function is both available and a candidate for optimized code generation. <a href="#a38377afcf58b163cbb11662bdc2841a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acee3b789f998e244c05ff9d65096178b">getName</a> (LibFunc F) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af091deb7d771e1462ad4f69354d45d0a">getExtAttrForI32Param</a> (bool Signed=true) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b33d10b93531c1862dc3fe207079ede">getExtAttrForI32Return</a> (bool Signed=true) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08ab82ef887ca585ab51c676c55b7a66">getAttrList</a> (LLVMContext *C, ArrayRef&lt; unsigned &gt; ArgNos, bool Signed, bool Ret=false, AttributeList AL=AttributeList()) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc986f86ae11ca39e3f87fd2d2affe1">getWCharSize</a> (const Module &amp;M) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size of the wchar_t type in bytes or 0 if the size is unknown. <a href="#a2cc986f86ae11ca39e3f87fd2d2affe1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b8cd043d27c642730b103a0eb241bd7">getSizeTSize</a> (const Module &amp;M) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size of the size_t type in bits. <a href="#a5b8cd043d27c642730b103a0eb241bd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae3e672e918b61abf32a5bb8a1aa7a08">getSizeTType</a> (const Module &amp;M) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> corresponding to size_t. <a href="#aae3e672e918b61abf32a5bb8a1aa7a08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2de4710e7d8c87b170aac3aaebc50bfb">getAsSizeT</a> (uint64_t V, const Module &amp;M) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a constant materialized as a size_t type. <a href="#a2de4710e7d8c87b170aac3aaebc50bfb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6cdbfae97e9631aae2c2e90a8023f99">getIntSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get size of a C-level int or unsigned int, in bits. <a href="#ad6cdbfae97e9631aae2c2e90a8023f99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17342406ff4ab4fee327f102208bfd98">invalidate</a> (Module &amp;, const PreservedAnalyses &amp;, ModuleAnalysisManager::Invalidator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle invalidation from the pass manager. <a href="#a17342406ff4ab4fee327f102208bfd98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4af46c3c528375fb14a38c8ac91472e6">invalidate</a> (Function &amp;, const PreservedAnalyses &amp;, FunctionAnalysisManager::Invalidator &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a842341c6f70ff53fbb7f69badbe7d876">getWidestVF</a> (StringRef ScalarF, ElementCount &amp;FixedVF, ElementCount &amp;ScalableVF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the largest vectorization factor used in the list of vector functions. <a href="#a842341c6f70ff53fbb7f69badbe7d876">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a509a54a541f436c80708c727d0b4d1b3">isKnownVectorFunctionInLibrary</a> (StringRef F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the function "F" is listed in a library known to LLVM. <a href="#a509a54a541f436c80708c727d0b4d1b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl">TargetLibraryInfoImpl</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a549346dd94dd26390a1eb20c9feeccd8">Impl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The global (module level) TLI info. <a href="#a549346dd94dd26390a1eb20c9feeccd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::bitset&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154ea389502cf750cbd7c05b635f4c76855ee">NumLibFuncs</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8850dbdbf4441ec01bcbf003215d0b5e">OverrideAsUnavailable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Support for -fno-builtin* options as function attributes, overrides information in global <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl">TargetLibraryInfoImpl</a>. <a href="#a8850dbdbf4441ec01bcbf003215d0b5e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbec53ddcfefcaaecad3227ecf1335e9">initExtensionsForTriple</a> (bool &amp;ShouldExtI32Param, bool &amp;ShouldExtI32Return, bool &amp;ShouldSignExtI32Param, bool &amp;ShouldSignExtI32Return, const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f08cb479d7f462525c9c9782c4e3aee">getExtAttrForI32Param</a> (const Triple &amp;T, bool Signed=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92a600f27aa38fb499232e09fb6704d9">getExtAttrForI32Return</a> (const Triple &amp;T, bool Signed=true)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1318ad3b8c7d131c224d3ecfb5042a6">getExtAttrForI32Param</a> (bool ShouldExtI32Param_, bool ShouldSignExtI32Param_, bool Signed=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns extension attribute kind to be used for i32 parameters corresponding to C-level int or unsigned int. <a href="#ac1318ad3b8c7d131c224d3ecfb5042a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe2b9efefca833d6d4fafb22ee353fc4">getExtAttrForI32Return</a> (bool ShouldExtI32Return_, bool ShouldSignExtI32Return_, bool Signed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns extension attribute kind to be used for i32 return values corresponding to C-level int or unsigned int. <a href="#afe2b9efefca833d6d4fafb22ee353fc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Provides information about what library functions are available for the current target.</p>


<p>This both allows optimizations to handle them specially and frontends to disable such optimizations through -fno-builtin etc.</p>


<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<div class="doxySectionDef">

## Friends

### TargetLibraryAnalysis {#aebe96ee83ba64d58e8af6adb3c255bc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/targetlibraryanalysis">TargetLibraryAnalysis</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="#aebe96ee83ba64d58e8af6adb3c255bc6">TargetLibraryAnalysis</a>.</p>


<p>Referenced by <a href="#aebe96ee83ba64d58e8af6adb3c255bc6">TargetLibraryAnalysis</a>.</p>

</div>
</div>

### TargetLibraryInfoWrapperPass {#ad9a409afc7f917489e6a8047bfb35b9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfowrapperpass">TargetLibraryInfoWrapperPass</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="#ad9a409afc7f917489e6a8047bfb35b9d">TargetLibraryInfoWrapperPass</a>.</p>


<p>Referenced by <a href="#ad9a409afc7f917489e6a8047bfb35b9d">TargetLibraryInfoWrapperPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TargetLibraryInfo() {#a9088608ebb8bafd853e87b7e7b4676b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetLibraryInfo::TargetLibraryInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl">TargetLibraryInfoImpl</a> &amp; Impl, std::optional&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; F=std::nullopt)</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="#a71749cadcb51437084eb14c3f3bfea8a">disableAllFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a97cfbbed8869e3582142012a071a9052">getLibFunc</a> and <a href="#a858bc32432a78550f43728ac033fa4ae">setUnavailable</a>.</p>


<p>Referenced by <a href="#a12588063ab5d62069b25e2a2d075f7fc">areInlineCompatible</a>, <a href="#a6f563e571ecea362ba07e5e53ac18f7f">operator=</a>, <a href="#ad29a00bf2e9e46ae4551db26ee51c921">operator=</a>, <a href="#a72e15e0a0b87c3d3af56b39ca970a19e">TargetLibraryInfo</a> and <a href="#adea9261bf534eaee448dc5f2f20e782d">TargetLibraryInfo</a>.</p>

</div>
</div>

### TargetLibraryInfo() {#a72e15e0a0b87c3d3af56b39ca970a19e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetLibraryInfo::TargetLibraryInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI)</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="#a9088608ebb8bafd853e87b7e7b4676b9">TargetLibraryInfo</a>.</p>

</div>
</div>

### TargetLibraryInfo() {#adea9261bf534eaee448dc5f2f20e782d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetLibraryInfo::TargetLibraryInfo (<a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;&amp; TLI)</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="#a9088608ebb8bafd853e87b7e7b4676b9">TargetLibraryInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a6f563e571ecea362ba07e5e53ac18f7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfo &amp; llvm::TargetLibraryInfo::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI)</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="#a9088608ebb8bafd853e87b7e7b4676b9">TargetLibraryInfo</a>.</p>

</div>
</div>

### operator=() {#ad29a00bf2e9e46ae4551db26ee51c921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfo &amp; llvm::TargetLibraryInfo::operator= (<a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;&amp; TLI)</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="#a9088608ebb8bafd853e87b7e7b4676b9">TargetLibraryInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### areInlineCompatible() {#a12588063ab5d62069b25e2a2d075f7fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfo::areInlineCompatible (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; CalleeTLI, bool AllowCallerSuperset)</td>
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

<p>Determine whether a callee with the given TLI can be inlined into caller with this TLI, based on 'nobuiltin' attributes.</p>


<p>When requested, allow inlining into a caller with a superset of the callee's nobuiltin attributes, which is conservatively correct.</p>


<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="#a9088608ebb8bafd853e87b7e7b4676b9">TargetLibraryInfo</a>.</p>

</div>
</div>

### disableAllFunctions() {#a71749cadcb51437084eb14c3f3bfea8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLibraryInfo::disableAllFunctions ()</td>
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

<p>Disables all builtins.</p>


<p>This can be used for options like -fno-builtin.</p>


<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#acc1c483f4b4ee2f17bb6643a3b353609">LLVM_ATTRIBUTE_UNUSED</a>.</p>


<p>Referenced by <a href="#a9088608ebb8bafd853e87b7e7b4676b9">TargetLibraryInfo</a>.</p>

</div>
</div>

### getAsSizeT() {#a2de4710e7d8c87b170aac3aaebc50bfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantInt * llvm::TargetLibraryInfo::getAsSizeT (uint64_t V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Returns a constant materialized as a size_t type.</p>

<p>Definition at line 576 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="#aae3e672e918b61abf32a5bb8a1aa7a08">getSizeTType</a>.</p>

</div>
</div>

### getAttrList() {#a08ab82ef887ca585ab51c676c55b7a66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::TargetLibraryInfo::getAttrList (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> * C, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; ArgNos, bool Signed, bool Ret=false, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> AL=<a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a>())</td>
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



<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>.</p>

</div>
</div>

### getExtAttrForI32Param() {#af091deb7d771e1462ad4f69354d45d0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute::AttrKind llvm::TargetLibraryInfo::getExtAttrForI32Param (bool Signed=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>.</p>

</div>
</div>

### getExtAttrForI32Return() {#a3b33d10b93531c1862dc3fe207079ede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute::AttrKind llvm::TargetLibraryInfo::getExtAttrForI32Return (bool Signed=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>.</p>

</div>
</div>

### getIntSize() {#ad6cdbfae97e9631aae2c2e90a8023f99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetLibraryInfo::getIntSize ()</td>
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

<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#ac03bc20ffe7747dad3d3d4bbbd4a3ca3">getIntTy</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5289777e58accae64ebded1a95e4c8b0">anonymous{MergeICmps.cpp}::mergeComparisons</a>.</p>

</div>
</div>

### getLibFunc() {#a97cfbbed8869e3582142012a071a9052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfo::getLibFunc (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> funcName, <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> &amp; F)</td>
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

<p>Searches for a particular function name.</p>


<p>If it is one of the known library functions, return true and set F to the corresponding value.</p>


<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af75ecbb2ce891821d146a047f17d4dd1">llvm::callsGCLeafFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4e3a3843bf5e85d3d55c2a252ec235bd">llvm::ConstantFoldCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#af8730ce5a51609308adda5bc1de4a859">anonymous{ConstantFolding.cpp}::ConstantFoldLibCall2</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a656b9d85656ae6dd73f482f6d5639b97">llvm::emitBinaryFloatFnCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08d868189c5335a01b6415e379a0c68c">llvm::emitUnaryFloatFnCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#af1da24e35a7154a7043bc87d971982a6">foldLibCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#a3c3ae5109d96640fa77e6942513269d6">getAllocationDataForFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a291c4451c91c4aaee65308741793626a">llvm::getAllocationFamily</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a713bb53f77454635f44dd95c53fc8684">llvm::TargetTransformInfo::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#afc51de08aefeeaabc77fefacc869dbd4">llvm::MemoryLocation::getForArgument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9cb77a3069c227792d6bade6faff422">llvm::getFreedOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db7e1f11fa5a274a0cffb6fc5e524be">llvm::getIntrinsicForCallSite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a754e6c242f055fb911359dd7ed568638">getIntrinsicFromLibfunc</a>, <a href="#a130c04c64f1ad6c7bea33c1aff8160be">getLibFunc</a>, <a href="/web-llvm/docs/api/structs/anonymous-pgomemopsizeopt-cpp-/memop/#abccd022ea8583eb828326120c036643f">anonymous{PGOMemOPSizeOpt.cpp}::MemOp::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a24da6451c0e494831c85fa96cb572c9a">insertSinCosCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a38c8e31049a8ae175aaac38c00f83279">isAllocationWithHotColdVariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a5d94ee8aaee00c42c11954aaa6022894">isAllocSiteRemovable</a>, <a href="/web-llvm/docs/api/structs/anonymous-pgomemopsizeopt-cpp-/memop/#ab8a4bb85b0732df6c45f43d726c63011">anonymous{PGOMemOPSizeOpt.cpp}::MemOp::isBcmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a87548c69480b23599d643d518412895c">isIntrinsicOrLFToBeTailCalled</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#af481ee3f81ad12db32ea0df13ec4b0d0">isKnownLibFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/moduleinliner-cpp/#af481ee3f81ad12db32ea0df13ec4b0d0">isKnownLibFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd66d9154d0d16a2c0f099505c8fa839">llvm::isLibFuncEmittable</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a7f1d4c503f57491de3cad8ff6d1512c4">anonymous{InlineCost.cpp}::CallAnalyzer::isLoweredToCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f579c2fbf1fda44d35d059d9799eddc">llvm::isMathLibCallNoop</a>, <a href="/web-llvm/docs/api/structs/anonymous-pgomemopsizeopt-cpp-/memop/#a8c8bd1558d1b481693131d443c5669e2">anonymous{PGOMemOPSizeOpt.cpp}::MemOp::isMemcmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae63427c4d8f3c1ce48401b38ed9198f1">llvm::maybeMarkSanitizerLibraryCallNoBuiltin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymemintrinsicresults-cpp/#a64e13a8c3c0d483c21941a99f473f8c2">optimizeCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-expandmemcmp-cpp-/#ab8309872ede007a47eebce4974ab341c">anonymous{ExpandMemCmp.cpp}::runOnBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/partiallyinlinelibcalls-cpp/#a0e177ca37bd9b11680cecf99d1115c35">runPartiallyInlineLibCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a463056de56ab82cc6e2c50e5ccf17626">shouldCheckArgs</a> and <a href="#a9088608ebb8bafd853e87b7e7b4676b9">TargetLibraryInfo</a>.</p>

</div>
</div>

### getLibFunc() {#a9672c6412ce53a4bc4ade8e99a7f4df1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfo::getLibFunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; FDecl, <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> &amp; F)</td>
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



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### getLibFunc() {#a130c04c64f1ad6c7bea33c1aff8160be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfo::getLibFunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> &amp; F)</td>
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

<p>If a callbase does not have the 'nobuiltin' attribute, return if the called function is a known library function and set F to that function.</p>

<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="#a97cfbbed8869e3582142012a071a9052">getLibFunc</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a1fb374eb65dcf7cd3d1671efb2616f76">llvm::CallBase::isNoBuiltin</a>.</p>

</div>
</div>

### getLibFunc() {#ac0c44937de7747acc7756269f3d5641d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfo::getLibFunc (unsigned int Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> &amp; F)</td>
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

<p>Searches for a function name using an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> <span class="doxyComputerOutput">Opcode</span>.</p>


<p>Currently, only the frem instruction is supported.</p>


<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### getName() {#acee3b789f998e244c05ff9d65096178b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::TargetLibraryInfo::getName (<a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> F)</td>
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



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a6242b52990676d512b20a9611c760000">getState</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a8dbd4c4f3aebf9f810f0590d49ba1003">llvm::emitCalloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8a6b92032e49dc6da4a5c4a05771878f">llvm::emitFPutC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689dd439a7989cc49b73cd6eb52d90dc">llvm::emitFPutS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a2a45b5fd2f1698d6fd10a06a0a38f2">llvm::emitFWrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad8bec6d053e2c93fee21eebfffae31d0">llvm::emitHotColdNew</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb10d4f78442972e711932060882cd79">llvm::emitHotColdNewAligned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1ee7adc14967589134b654d321b3561d">llvm::emitHotColdNewAlignedNoThrow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6cfbf3bb83193d8447d8f7c392915cb">llvm::emitHotColdNewNoThrow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad721b230836c9430afd9a392db0c7c5a">llvm::emitHotColdSizeReturningNew</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf8c11d60a5385f70c3a140c03f136e4">llvm::emitHotColdSizeReturningNewAligned</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#a62d6c0a5c9dd42949245eb28ab9c37c8">emitLibCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76c99e44c5f3570a3666c9234caf222">llvm::emitMalloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11b84a626ef34d3ced2e131937e58ddd">llvm::emitPutChar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8cc4358373eeb5363cd620bbdaeab">llvm::emitPutS</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a713bb53f77454635f44dd95c53fc8684">llvm::TargetTransformInfo::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85cffb0596b8391caaebf06fbd786b1b">llvm::getFloatFn</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a754e6c242f055fb911359dd7ed568638">getIntrinsicFromLibfunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87cba3c4c88ab5df01a7f7dece1e0266">llvm::getOrInsertLibFunc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a57d0e3799b16937e1f8df20ca1f1f3df">llvm::isLibFuncEmittable</a>.</p>

</div>
</div>

### getSizeTSize() {#a5b8cd043d27c642730b103a0eb241bd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetLibraryInfo::getSizeTSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Returns the size of the size_t type in bits.</p>

<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#a527943330d141bf468c70741d40375cc">getSizeTTy</a>, <a href="#aae3e672e918b61abf32a5bb8a1aa7a08">getSizeTType</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5289777e58accae64ebded1a95e4c8b0">anonymous{MergeICmps.cpp}::mergeComparisons</a>.</p>

</div>
</div>

### getSizeTType() {#aae3e672e918b61abf32a5bb8a1aa7a08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType * llvm::TargetLibraryInfo::getSizeTType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Returns an <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> corresponding to size_t.</p>

<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a> and <a href="#a5b8cd043d27c642730b103a0eb241bd7">getSizeTSize</a>.</p>


<p>Referenced by <a href="#a2de4710e7d8c87b170aac3aaebc50bfb">getAsSizeT</a>.</p>

</div>
</div>

### getState() {#a6242b52990676d512b20a9611c760000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfoImpl::AvailabilityState llvm::TargetLibraryInfo::getState (<a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> F)</td>
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



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#acee3b789f998e244c05ff9d65096178b">getName</a>, <a href="#a54699e3f128acda6003afc11d3027f6c">has</a> and <a href="#a38377afcf58b163cbb11662bdc2841a9">hasOptimizedCodeGen</a>.</p>

</div>
</div>

### getVectorizedFunction() {#ac839c0e63d91f848aaf1290585e1fc25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::TargetLibraryInfo::getVectorizedFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> &amp; VF, bool Masked=false)</td>
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



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a205029ee514828d0fb4988399ef3ece4a6864311f985d160ad4bd46a9fbe4a4d4">llvm::Masked</a>.</p>

</div>
</div>

### getVectorMappingInfo() {#acf95582fbff31ea4c597858e1112a6e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VecDesc * llvm::TargetLibraryInfo::getVectorMappingInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> &amp; VF, bool Masked)</td>
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



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a205029ee514828d0fb4988399ef3ece4a6864311f985d160ad4bd46a9fbe4a4d4">llvm::Masked</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#a8bde7bea5a6d6a50fd5b6d03d746e05b">addMappingsFromTLI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a27cad9bebff39ed9ba603074dda1335e">replaceWithCallToVeclib</a>.</p>

</div>
</div>

### getWCharSize() {#a2cc986f86ae11ca39e3f87fd2d2affe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetLibraryInfo::getWCharSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Returns the size of the wchar_t type in bytes or 0 if the size is unknown.</p>


<p>This queries the 'wchar_size' metadata.</p>


<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

### getWidestVF() {#a842341c6f70ff53fbb7f69badbe7d876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLibraryInfo::getWidestVF (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ScalarF, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> &amp; FixedVF, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> &amp; ScalableVF)</td>
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

<p>Returns the largest vectorization factor used in the list of vector functions.</p>

<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#a8bde7bea5a6d6a50fd5b6d03d746e05b">addMappingsFromTLI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae641260d79a9242ccf378d9a7949fdc3">llvm::isTLIScalarize</a>.</p>

</div>
</div>

### has() {#a54699e3f128acda6003afc11d3027f6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfo::has (<a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> F)</td>
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

<p>Tests whether a library function is available.</p>

<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a6242b52990676d512b20a9611c760000">getState</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af75ecbb2ce891821d146a047f17d4dd1">llvm::callsGCLeafFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#af8730ce5a51609308adda5bc1de4a859">anonymous{ConstantFolding.cpp}::ConstantFoldLibCall2</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#a3c3ae5109d96640fa77e6942513269d6">getAllocationDataForFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a291c4451c91c4aaee65308741793626a">llvm::getAllocationFamily</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#afc51de08aefeeaabc77fefacc869dbd4">llvm::MemoryLocation::getForArgument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9cb77a3069c227792d6bade6faff422">llvm::getFreedOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87cba3c4c88ab5df01a7f7dece1e0266">llvm::getOrInsertLibFunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a5d94ee8aaee00c42c11954aaa6022894">isAllocSiteRemovable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d0e3799b16937e1f8df20ca1f1f3df">llvm::isLibFuncEmittable</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a7f1d4c503f57491de3cad8ff6d1512c4">anonymous{InlineCost.cpp}::CallAnalyzer::isLoweredToCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#acdae591a7f9f5246ef32c3cc992a6b36">anonymous{MergeICmps.cpp}::runImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/partiallyinlinelibcalls-cpp/#a0e177ca37bd9b11680cecf99d1115c35">runPartiallyInlineLibCalls</a>.</p>

</div>
</div>

### hasOptimizedCodeGen() {#a38377afcf58b163cbb11662bdc2841a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfo::hasOptimizedCodeGen (<a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> F)</td>
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

<p>Tests if the function is both available and a candidate for optimized code generation.</p>

<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a6242b52990676d512b20a9611c760000">getState</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae63427c4d8f3c1ce48401b38ed9198f1">llvm::maybeMarkSanitizerLibraryCallNoBuiltin</a>.</p>

</div>
</div>

### invalidate() {#a17342406ff4ab4fee327f102208bfd98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfo::invalidate (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp;, ModuleAnalysisManager::Invalidator &amp;)</td>
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

<p>Handle invalidation from the pass manager.</p>


<p>If we try to invalidate this info, just return false. It cannot become invalid even if the module or function changes.</p>


<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

### invalidate() {#a4af46c3c528375fb14a38c8ac91472e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfo::invalidate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp;, FunctionAnalysisManager::Invalidator &amp;)</td>
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



<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

### isFunctionVectorizable() {#af2dc370c0f0b837f18b006c2d4b8b7cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfo::isFunctionVectorizable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> &amp; VF)</td>
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



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#a8bde7bea5a6d6a50fd5b6d03d746e05b">addMappingsFromTLI</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a713bb53f77454635f44dd95c53fc8684">llvm::TargetTransformInfo::getArithmeticInstrCost</a>, <a href="#a509a54a541f436c80708c727d0b4d1b3">isKnownVectorFunctionInLibrary</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae641260d79a9242ccf378d9a7949fdc3">llvm::isTLIScalarize</a>.</p>

</div>
</div>

### isFunctionVectorizable() {#a5412f8840a4b4e4a9644fd3674f21506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfo::isFunctionVectorizable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> F)</td>
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



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### isKnownVectorFunctionInLibrary() {#a509a54a541f436c80708c727d0b4d1b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfo::isKnownVectorFunctionInLibrary (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> F)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the function "F" is listed in a library known to LLVM.</p>

<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#af2dc370c0f0b837f18b006c2d4b8b7cc">isFunctionVectorizable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#af481ee3f81ad12db32ea0df13ec4b0d0">isKnownLibFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/moduleinliner-cpp/#af481ee3f81ad12db32ea0df13ec4b0d0">isKnownLibFunction</a>.</p>

</div>
</div>

### isValidProtoForLibFunc() {#a25b8b3cd7b0a1ee616b00ca9abcf0a0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLibraryInfo::isValidProtoForLibFunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> &amp; FTy, <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Return true if the function type FTy is valid for the library function F, regardless of whether the function is available.</p>

<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a57d0e3799b16937e1f8df20ca1f1f3df">llvm::isLibFuncEmittable</a>.</p>

</div>
</div>

### setUnavailable() {#a858bc32432a78550f43728ac033fa4ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLibraryInfo::setUnavailable (<a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> F)</td>
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

<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#acc1c483f4b4ee2f17bb6643a3b353609">LLVM_ATTRIBUTE_UNUSED</a>.</p>


<p>Referenced by <a href="#a9088608ebb8bafd853e87b7e7b4676b9">TargetLibraryInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Impl {#a549346dd94dd26390a1eb20c9feeccd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfoImpl* llvm::TargetLibraryInfo::Impl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The global (module level) TLI info.</p>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

### OverrideAsUnavailable {#a8850dbdbf4441ec01bcbf003215d0b5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::bitset&lt;NumLibFuncs&gt; llvm::TargetLibraryInfo::OverrideAsUnavailable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Support for -fno-builtin* options as function attributes, overrides information in global <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl">TargetLibraryInfoImpl</a>.</p>

<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getExtAttrForI32Param() {#a0f08cb479d7f462525c9c9782c4e3aee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute::AttrKind llvm::TargetLibraryInfo::getExtAttrForI32Param (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, bool Signed=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="#abbec53ddcfefcaaecad3227ecf1335e9">initExtensionsForTriple</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### getExtAttrForI32Return() {#a92a600f27aa38fb499232e09fb6704d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute::AttrKind llvm::TargetLibraryInfo::getExtAttrForI32Return (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, bool Signed=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="#abbec53ddcfefcaaecad3227ecf1335e9">initExtensionsForTriple</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### initExtensionsForTriple() {#abbec53ddcfefcaaecad3227ecf1335e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLibraryInfo::initExtensionsForTriple (bool &amp; ShouldExtI32Param, bool &amp; ShouldExtI32Return, bool &amp; ShouldSignExtI32Param, bool &amp; ShouldSignExtI32Return, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
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



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a34e8fe940082d534b3957f06616c8227">llvm::Triple::sparcv9</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f">llvm::Triple::systemz</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a0f08cb479d7f462525c9c9782c4e3aee">getExtAttrForI32Param</a>, <a href="#a92a600f27aa38fb499232e09fb6704d9">getExtAttrForI32Return</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a641b5e25f1fd3d03c418a5a2aefd4b55">initializeBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getExtAttrForI32Param() {#ac1318ad3b8c7d131c224d3ecfb5042a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute::AttrKind llvm::TargetLibraryInfo::getExtAttrForI32Param (bool ShouldExtI32Param_, bool ShouldSignExtI32Param_, bool Signed=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Returns extension attribute kind to be used for i32 parameters corresponding to C-level int or unsigned int.</p>


<p>May be zeroext, signext, or none.</p>


<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

### getExtAttrForI32Return() {#afe2b9efefca833d6d4fafb22ee353fc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute::AttrKind llvm::TargetLibraryInfo::getExtAttrForI32Return (bool ShouldExtI32Return_, bool ShouldSignExtI32Return_, bool Signed)</td>
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

<p>Returns extension attribute kind to be used for i32 return values corresponding to C-level int or unsigned int.</p>


<p>May be zeroext, signext, or none.</p>


<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">TargetLibraryInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
