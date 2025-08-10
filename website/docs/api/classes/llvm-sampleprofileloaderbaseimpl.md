---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprofileloaderbaseimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SampleProfileLoaderBaseImpl` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename FT&gt;
class llvm::SampleProfileLoaderBaseImpl&lt;FT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">llvm/Transforms/Utils/SampleProfileLoaderBaseImpl.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6333415b6633ad47c07409754088f1b9">NodeRef</a> = typename <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; FT * &gt;::NodeRef</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a78e0cffa6cb464ad39f9a2ce91230a5a">BT</a> = std::remove_pointer_t&lt; <a href="#a6333415b6633ad47c07409754088f1b9">NodeRef</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aabc995a0d85012b77c9232d201d520f2">InstructionT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/afdo-detail/irtraits">afdo_detail::IRTraits</a>&lt; <a href="#a78e0cffa6cb464ad39f9a2ce91230a5a">BT</a> &gt;::InstructionT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a10d31eaba9ec292510535e508e6d52f1">BasicBlockT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/afdo-detail/irtraits">afdo_detail::IRTraits</a>&lt; <a href="#a78e0cffa6cb464ad39f9a2ce91230a5a">BT</a> &gt;::BasicBlockT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abf452b3b35d272a08504ed1d32fe5c6e">BlockFrequencyInfoT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/afdo-detail/irtraits">afdo_detail::IRTraits</a>&lt; <a href="#a78e0cffa6cb464ad39f9a2ce91230a5a">BT</a> &gt;::BlockFrequencyInfoT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af897082b1f09e18ffa991e88464bc089">FunctionT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/afdo-detail/irtraits">afdo_detail::IRTraits</a>&lt; <a href="#a78e0cffa6cb464ad39f9a2ce91230a5a">BT</a> &gt;::FunctionT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a61228be0c808dc34f623712534af1394">LoopT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/afdo-detail/irtraits">afdo_detail::IRTraits</a>&lt; <a href="#a78e0cffa6cb464ad39f9a2ce91230a5a">BT</a> &gt;::LoopT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9d018bb366a750f4ebe333f918cc960e">LoopInfoPtrT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/afdo-detail/irtraits">afdo_detail::IRTraits</a>&lt; <a href="#a78e0cffa6cb464ad39f9a2ce91230a5a">BT</a> &gt;::LoopInfoPtrT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9472f5e59e6a67ce3951989da71dd2be">DominatorTreePtrT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/afdo-detail/irtraits">afdo_detail::IRTraits</a>&lt; <a href="#a78e0cffa6cb464ad39f9a2ce91230a5a">BT</a> &gt;::DominatorTreePtrT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4aa74811b2d87d4f2a61b03a0a37bdb2">PostDominatorTreePtrT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/afdo-detail/irtraits">afdo_detail::IRTraits</a>&lt; <a href="#a78e0cffa6cb464ad39f9a2ce91230a5a">BT</a> &gt;::PostDominatorTreePtrT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acd3af750070884babd65d72b6a4ebf8b">PostDominatorTreeT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/afdo-detail/irtraits">afdo_detail::IRTraits</a>&lt; <a href="#a78e0cffa6cb464ad39f9a2ce91230a5a">BT</a> &gt;::PostDominatorTreeT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae86c8f86169123ccc123cebf307339e0">OptRemarkEmitterT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/afdo-detail/irtraits">afdo_detail::IRTraits</a>&lt; <a href="#a78e0cffa6cb464ad39f9a2ce91230a5a">BT</a> &gt;::OptRemarkEmitterT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8d08cdd6a03d49c140972150eb312a73">OptRemarkAnalysisT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/afdo-detail/irtraits">afdo_detail::IRTraits</a>&lt; <a href="#a78e0cffa6cb464ad39f9a2ce91230a5a">BT</a> &gt;::OptRemarkAnalysisT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad2bc129fc3b5c74d1dd48f220f94c4e8">PredRangeT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/afdo-detail/irtraits">afdo_detail::IRTraits</a>&lt; <a href="#a78e0cffa6cb464ad39f9a2ce91230a5a">BT</a> &gt;::PredRangeT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a184b0dd4e4d9254371efc90ddb56c5e9">SuccRangeT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/afdo-detail/irtraits">afdo_detail::IRTraits</a>&lt; <a href="#a78e0cffa6cb464ad39f9a2ce91230a5a">BT</a> &gt;::SuccRangeT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1e15a2b018aa71534c64276476644063">BlockWeightMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a10d31eaba9ec292510535e508e6d52f1">BasicBlockT</a> *, uint64_t &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#accfc95dbd0fb709357d9e8a97ded0b9c">EquivalenceClassMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a10d31eaba9ec292510535e508e6d52f1">BasicBlockT</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a10d31eaba9ec292510535e508e6d52f1">BasicBlockT</a> * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae0c6798ea9e2df9241569f6b9f6287da">Edge</a> = std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a10d31eaba9ec292510535e508e6d52f1">BasicBlockT</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a10d31eaba9ec292510535e508e6d52f1">BasicBlockT</a> * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8e22e32dc5ee9ac7b1fedd9e5a37aeb4">EdgeWeightMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="#ae0c6798ea9e2df9241569f6b9f6287da">Edge</a>, uint64_t &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a773c15b59a549228a02246704fc09e9d">BlockEdgeMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a10d31eaba9ec292510535e508e6d52f1">BasicBlockT</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a10d31eaba9ec292510535e508e6d52f1">BasicBlockT</a> *, 8 &gt; &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac7b0d41f41bd4959483f76524e705bc7">SampleCoverageTracker</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a8914bae43b683a78d971e5954d781331">SampleProfileLoaderBaseImpl</a> (std::string Name, std::string RemapName, IntrusiveRefCntPtr&lt; vfs::FileSystem &gt; FS)</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a8dec1de56bd6fe391e86b16ffa4f8a78">~SampleProfileLoaderBaseImpl</a> ()=default</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1510e04c6817c687a27c439d5ad36584">dump</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a27bf2b96e5c474b00a78fade0b7a37e9">getFunction</a> (FunctionT &amp;F)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a10d31eaba9ec292510535e508e6d52f1">BasicBlockT</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2b8f887a5dfc3eaa968ede5f79a2fc12">getEntryBB</a> (const FunctionT *F)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ad2bc129fc3b5c74d1dd48f220f94c4e8">PredRangeT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3bf69a5f2b0cc7bba7b071fc67b050b3">getPredecessors</a> (BasicBlockT *BB)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a184b0dd4e4d9254371efc90ddb56c5e9">SuccRangeT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa04ab96e7be5ad3ced9aa3bd35f76eac">getSuccessors</a> (BasicBlockT *BB)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3bb6939c9a307a2d7a2bc20363b5433c">getFunctionLoc</a> (FunctionT &amp;Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the line number for the function header. <a href="#a3bb6939c9a307a2d7a2bc20363b5433c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4242a2c35893bbf85211387709d6a3d1">getInstWeight</a> (const InstructionT &amp;Inst) -&gt; <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; uint64_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the weight for an instruction. <a href="#a4242a2c35893bbf85211387709d6a3d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3fd239026aba79e9aaf5b81578f4198c">getInstWeightImpl</a> (const InstructionT &amp;Inst) -&gt; <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; uint64_t &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acdcff307bede233f8221f618d262b6df">getProbeWeight</a> (const InstructionT &amp;Inst) -&gt; <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; uint64_t &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a366f5bc39f00b9b44f1f39adca8b414c">getBlockWeight</a> (const BasicBlockT *BB) -&gt; <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; uint64_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the weight of a basic block. <a href="#a366f5bc39f00b9b44f1f39adca8b414c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac129a5f56604167d730262a05cb1fd02">findFunctionSamples</a> (const InstructionT &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> for an instruction. <a href="#ac129a5f56604167d730262a05cb1fd02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af80c8905cce458376f69ac1282a07bc3">printEdgeWeight</a> (raw_ostream &amp;OS, Edge E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the weight of edge <span class="doxyComputerOutput">E</span> on stream <span class="doxyComputerOutput">OS</span>. <a href="#af80c8905cce458376f69ac1282a07bc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7222989331e6d8e7845bad3d2d385486">printBlockWeight</a> (raw_ostream &amp;OS, const BasicBlockT *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the weight of block <span class="doxyComputerOutput">BB</span> on stream <span class="doxyComputerOutput">OS</span>. <a href="#a7222989331e6d8e7845bad3d2d385486">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a75839e382274534379a37deb48fb80dc">printBlockEquivalence</a> (raw_ostream &amp;OS, const BasicBlockT *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the equivalence class of block <span class="doxyComputerOutput">BB</span> on stream <span class="doxyComputerOutput">OS</span>. <a href="#a75839e382274534379a37deb48fb80dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abfedd5d05290a01e9b21cde734588620">computeBlockWeights</a> (FunctionT &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute and store the weights of every basic block. <a href="#abfedd5d05290a01e9b21cde734588620">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adad5302e31acac871db7fe5c38940377">findEquivalenceClasses</a> (FunctionT &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find equivalence classes. <a href="#adad5302e31acac871db7fe5c38940377">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aee060f872d48fa04e7ec34df784ce088">findEquivalencesFor</a> (BasicBlockT *BB1, ArrayRef&lt; BasicBlockT * &gt; Descendants, PostDominatorTreeT *DomTree)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find equivalence classes for the given block. <a href="#aee060f872d48fa04e7ec34df784ce088">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afeab810a0b4abc92f2650348428220a2">propagateWeights</a> (FunctionT &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Propagate weights into edges. <a href="#afeab810a0b4abc92f2650348428220a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad3a21cb53662f9cd445fa9d5e384d761">applyProfi</a> (FunctionT &amp;F, BlockEdgeMap &amp;Successors, BlockWeightMap &amp;SampleBlockWeights, BlockWeightMap &amp;BlockWeights, EdgeWeightMap &amp;EdgeWeights)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab32be71f5ab339400be1f2eba700b290">visitEdge</a> (Edge E, unsigned *NumUnknownEdges, Edge *UnknownEdge)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Visit the given edge to decide if it has a valid weight. <a href="#ab32be71f5ab339400be1f2eba700b290">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aedaa834891e933cab48185f1bd32354c">buildEdges</a> (FunctionT &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build in/out edge lists for each basic block in the CFG. <a href="#aedaa834891e933cab48185f1bd32354c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa435e55eb50c7ecc8e69e636eb1fe345">propagateThroughEdges</a> (FunctionT &amp;F, bool UpdateBlockCount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Propagate weights through incoming/outgoing edges. <a href="#aa435e55eb50c7ecc8e69e636eb1fe345">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae9bae46af4ef474d7f244e4f9b67e188">clearFunctionData</a> (bool ResetDT=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear all the per-function data used to load samples and propagate weights. <a href="#ae9bae46af4ef474d7f244e4f9b67e188">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a09b07d241e152c373256e084d21568d2">computeDominanceAndLoopInfo</a> (FunctionT &amp;F)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a040b98a945772423eab83d2ce02f984a">computeAndPropagateWeights</a> (FunctionT &amp;F, const DenseSet&lt; GlobalValue::GUID &gt; &amp;InlinedGUIDs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate branch weight metadata for all branches in <span class="doxyComputerOutput">F</span>. <a href="#a040b98a945772423eab83d2ce02f984a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab399a6466f9c56febc239c000eee5406">initWeightPropagation</a> (FunctionT &amp;F, const DenseSet&lt; GlobalValue::GUID &gt; &amp;InlinedGUIDs)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abdc4c98f065999f51c3871a59e5c1de2">finalizeWeightPropagation</a> (FunctionT &amp;F, const DenseSet&lt; GlobalValue::GUID &gt; &amp;InlinedGUIDs)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9da04aa71aaa9243bb7efe549f1dd758">emitCoverageRemarks</a> (FunctionT &amp;F)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae8a07594791a56f3c10df035214129bc">computeDominanceAndLoopInfo</a> (MachineFunction &amp;F)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a85fc6a15bf46677c3617667d473d479e">computeDominanceAndLoopInfo</a> (Function &amp;F)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeacafab53cd915d0ff8922dcb398fbe1">DILocation2SampleMap</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a1e15a2b018aa71534c64276476644063">BlockWeightMap</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afd962f6862c0fa756bc3d8e2e751a955">BlockWeights</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map basic blocks to their computed weights. <a href="#afd962f6862c0fa756bc3d8e2e751a955">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a8e22e32dc5ee9ac7b1fedd9e5a37aeb4">EdgeWeightMap</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a25b4d69386a27e339e802ac43d47fe33">EdgeWeights</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map edges to their computed weights. <a href="#a25b4d69386a27e339e802ac43d47fe33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a10d31eaba9ec292510535e508e6d52f1">BasicBlockT</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a425760bcf9be77e6a664a5997283a2e1">VisitedBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of visited blocks during propagation. <a href="#a425760bcf9be77e6a664a5997283a2e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="#ae0c6798ea9e2df9241569f6b9f6287da">Edge</a>, 32 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a27d241cbcd8f53b9f09c7c19242cb789">VisitedEdges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of visited edges during propagation. <a href="#a27d241cbcd8f53b9f09c7c19242cb789">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#accfc95dbd0fb709357d9e8a97ded0b9c">EquivalenceClassMap</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4a4a260ea818b3bfe7ae4f0da463dbb9">EquivalenceClass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Equivalence classes for block weights. <a href="#a4a4a260ea818b3bfe7ae4f0da463dbb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9472f5e59e6a67ce3951989da71dd2be">DominatorTreePtrT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a726028c50f8c9cea16a85ffa721a78b4">DT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dominance, post-dominance and loop information. <a href="#a726028c50f8c9cea16a85ffa721a78b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a4aa74811b2d87d4f2a61b03a0a37bdb2">PostDominatorTreePtrT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa48c470371fe9507bec17abd3333fd1f">PDT</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9d018bb366a750f4ebe333f918cc960e">LoopInfoPtrT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae5efdc714ce4789b9a1ffe59bb055cc7">LI</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a773c15b59a549228a02246704fc09e9d">BlockEdgeMap</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab84644c12ae7f1ff1b2db384132d0b4c">Predecessors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Predecessors for each basic block in the CFG. <a href="#ab84644c12ae7f1ff1b2db384132d0b4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a773c15b59a549228a02246704fc09e9d">BlockEdgeMap</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad6a5a5bd663105131550df5f7593ef0f">Successors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Successors for each basic block in the CFG. <a href="#ad6a5a5bd663105131550df5f7593ef0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprofutil/samplecoveragetracker">SampleCoverageTracker</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a52673282884569984ceee1e4f7119a50">CoverageTracker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Profile coverage tracker. <a href="#a52673282884569984ceee1e4f7119a50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader">SampleProfileReader</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6cda1f8872cce456c1ec260c8ef7aa24">Reader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Profile reader object. <a href="#a6cda1f8872cce456c1ec260c8ef7aa24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a28a1e350b54691c575efa482bfc72140">OutlineFunctionSamples</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Synthetic samples created by duplicating the samples of inlined functions from the original profile as if they were top level sample profiles. <a href="#a28a1e350b54691c575efa482bfc72140">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pseudoprobemanager">PseudoProbeManager</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8a061b4f421152b76653f15e18bec185">ProbeManager</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad9ec5be72117476a75c7dd1cc59d03f1">Samples</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Samples collected for the body of this function. <a href="#ad9ec5be72117476a75c7dd1cc59d03f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa25c9c0884c2fc1dc621c881c00485f8">Filename</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Name of the profile file to load. <a href="#aa25c9c0884c2fc1dc621c881c00485f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad0b57e56868a6c60929c62f1494628af">RemappingFilename</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Name of the profile remapping file to load. <a href="#ad0b57e56868a6c60929c62f1494628af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a12022aa707c271f81eae8ec0eebfae29">FS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VirtualFileSystem to load profile files from. <a href="#a12022aa707c271f81eae8ec0eebfae29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae49ac2191e91a12f7ed0b92b2b72ebbe">PSI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Profile Summary Info computed from sample profile. <a href="#ae49ac2191e91a12f7ed0b92b2b72ebbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ae86c8f86169123ccc123cebf307339e0">OptRemarkEmitterT</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a293c85647f9dcb78f29ad5ab31e5a7f9">ORE</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimization Remark Emitter used to emit diagnostic remarks. <a href="#a293c85647f9dcb78f29ad5ab31e5a7f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BasicBlockT {#a10d31eaba9ec292510535e508e6d52f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::BasicBlockT =  typename afdo_detail::IRTraits&lt;BT&gt;::BasicBlockT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### BlockEdgeMap {#a773c15b59a549228a02246704fc09e9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::BlockEdgeMap = 
      DenseMap&lt;const BasicBlockT *, SmallVector&lt;const BasicBlockT *, 8&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### BlockFrequencyInfoT {#abf452b3b35d272a08504ed1d32fe5c6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::BlockFrequencyInfoT = 
      typename afdo_detail::IRTraits&lt;BT&gt;::BlockFrequencyInfoT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### BlockWeightMap {#a1e15a2b018aa71534c64276476644063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::BlockWeightMap =  DenseMap&lt;const BasicBlockT *, uint64_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### BT {#a78e0cffa6cb464ad39f9a2ce91230a5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::BT =  std::remove_pointer_t&lt;NodeRef&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### DominatorTreePtrT {#a9472f5e59e6a67ce3951989da71dd2be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::DominatorTreePtrT = 
      typename afdo_detail::IRTraits&lt;BT&gt;::DominatorTreePtrT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### Edge {#ae0c6798ea9e2df9241569f6b9f6287da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Edge =  std::pair&lt;const BasicBlockT *, const BasicBlockT *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### EdgeWeightMap {#a8e22e32dc5ee9ac7b1fedd9e5a37aeb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::EdgeWeightMap =  DenseMap&lt;Edge, uint64_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### EquivalenceClassMap {#accfc95dbd0fb709357d9e8a97ded0b9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::EquivalenceClassMap = 
      DenseMap&lt;const BasicBlockT *, const BasicBlockT *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### FunctionT {#af897082b1f09e18ffa991e88464bc089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::FunctionT =  typename afdo_detail::IRTraits&lt;BT&gt;::FunctionT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### InstructionT {#aabc995a0d85012b77c9232d201d520f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::InstructionT =  typename afdo_detail::IRTraits&lt;BT&gt;::InstructionT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### LoopInfoPtrT {#a9d018bb366a750f4ebe333f918cc960e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::LoopInfoPtrT =  typename afdo_detail::IRTraits&lt;BT&gt;::LoopInfoPtrT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### LoopT {#a61228be0c808dc34f623712534af1394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::LoopT =  typename afdo_detail::IRTraits&lt;BT&gt;::LoopT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### NodeRef {#a6333415b6633ad47c07409754088f1b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::NodeRef =  typename GraphTraits&lt;FT *&gt;::NodeRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### OptRemarkAnalysisT {#a8d08cdd6a03d49c140972150eb312a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::OptRemarkAnalysisT = 
      typename afdo_detail::IRTraits&lt;BT&gt;::OptRemarkAnalysisT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### OptRemarkEmitterT {#ae86c8f86169123ccc123cebf307339e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::OptRemarkEmitterT = 
      typename afdo_detail::IRTraits&lt;BT&gt;::OptRemarkEmitterT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### PostDominatorTreePtrT {#a4aa74811b2d87d4f2a61b03a0a37bdb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::PostDominatorTreePtrT = 
      typename afdo_detail::IRTraits&lt;BT&gt;::PostDominatorTreePtrT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### PostDominatorTreeT {#acd3af750070884babd65d72b6a4ebf8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::PostDominatorTreeT = 
      typename afdo_detail::IRTraits&lt;BT&gt;::PostDominatorTreeT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### PredRangeT {#ad2bc129fc3b5c74d1dd48f220f94c4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::PredRangeT =  typename afdo_detail::IRTraits&lt;BT&gt;::PredRangeT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### SuccRangeT {#a184b0dd4e4d9254371efc90ddb56c5e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::SuccRangeT =  typename afdo_detail::IRTraits&lt;BT&gt;::SuccRangeT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### SampleCoverageTracker {#ac7b0d41f41bd4959483f76524e705bc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sampleprofutil/samplecoveragetracker">SampleCoverageTracker</a></td>
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


<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Reference <a href="#ac7b0d41f41bd4959483f76524e705bc7">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::SampleCoverageTracker</a>.</p>


<p>Referenced by <a href="#ac7b0d41f41bd4959483f76524e705bc7">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::SampleCoverageTracker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SampleProfileLoaderBaseImpl() {#a8914bae43b683a78d971e5954d781331}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::SampleProfileLoaderBaseImpl (std::string Name, std::string RemapName, <a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &gt; FS)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="#aa25c9c0884c2fc1dc621c881c00485f8">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Filename</a>, <a href="#a12022aa707c271f81eae8ec0eebfae29">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::FS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#ad0b57e56868a6c60929c62f1494628af">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::RemappingFilename</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~SampleProfileLoaderBaseImpl() {#a8dec1de56bd6fe391e86b16ffa4f8a78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::~SampleProfileLoaderBaseImpl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a1510e04c6817c687a27c439d5ad36584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::dump ()</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Reference <a href="#a6cda1f8872cce456c1ec260c8ef7aa24">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Reader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### applyProfi() {#ad3a21cb53662f9cd445fa9d5e384d761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::applyProfi (<a href="#af897082b1f09e18ffa991e88464bc089">FunctionT</a> &amp; F, <a href="#a773c15b59a549228a02246704fc09e9d">BlockEdgeMap</a> &amp; Successors, <a href="#a1e15a2b018aa71534c64276476644063">BlockWeightMap</a> &amp; SampleBlockWeights, <a href="#a1e15a2b018aa71534c64276476644063">BlockWeightMap</a> &amp; BlockWeights, <a href="#a8e22e32dc5ee9ac7b1fedd9e5a37aeb4">EdgeWeightMap</a> &amp; EdgeWeights)</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="#afd962f6862c0fa756bc3d8e2e751a955">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::BlockWeights</a>, <a href="#a25b4d69386a27e339e802ac43d47fe33">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::EdgeWeights</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#ad6a5a5bd663105131550df5f7593ef0f">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Successors</a>.</p>


<p>Referenced by <a href="#afeab810a0b4abc92f2650348428220a2">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateWeights</a>.</p>

</div>
</div>

### buildEdges() {#aedaa834891e933cab48185f1bd32354c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::buildEdges (<a href="#af897082b1f09e18ffa991e88464bc089">FunctionT</a> &amp; F)</td>
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

<p>Build in/out edge lists for each basic block in the CFG.</p>


<p>We are interested in unique edges. If a block B1 has multiple edges to another block B2, we only add a single B1-&gt;B2 edge.</p>


<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a16413f1a88d8baca228d0a1b4cc0bfc6">llvm::SmallPtrSetImplBase::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a3bf69a5f2b0cc7bba7b071fc67b050b3">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getPredecessors</a>, <a href="#aa04ab96e7be5ad3ced9aa3bd35f76eac">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ab84644c12ae7f1ff1b2db384132d0b4c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Predecessors</a> and <a href="#ad6a5a5bd663105131550df5f7593ef0f">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Successors</a>.</p>


<p>Referenced by <a href="#ab399a6466f9c56febc239c000eee5406">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::initWeightPropagation</a>.</p>

</div>
</div>

### clearFunctionData() {#ae9bae46af4ef474d7f244e4f9b67e188}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::clearFunctionData (bool ResetDT=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Clear all the per-function data used to load samples and propagate weights.</p>

<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="#afd962f6862c0fa756bc3d8e2e751a955">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::BlockWeights</a>, <a href="#a52673282884569984ceee1e4f7119a50">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::CoverageTracker</a>, <a href="#a726028c50f8c9cea16a85ffa721a78b4">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::DT</a>, <a href="#a25b4d69386a27e339e802ac43d47fe33">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::EdgeWeights</a>, <a href="#a4a4a260ea818b3bfe7ae4f0da463dbb9">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::EquivalenceClass</a>, <a href="#ae5efdc714ce4789b9a1ffe59bb055cc7">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::LI</a>, <a href="#aa48c470371fe9507bec17abd3333fd1f">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::PDT</a>, <a href="#ab84644c12ae7f1ff1b2db384132d0b4c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Predecessors</a>, <a href="#ad6a5a5bd663105131550df5f7593ef0f">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Successors</a>, <a href="#a425760bcf9be77e6a664a5997283a2e1">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::VisitedBlocks</a> and <a href="#a27d241cbcd8f53b9f09c7c19242cb789">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::VisitedEdges</a>.</p>

</div>
</div>

### computeAndPropagateWeights() {#a040b98a945772423eab83d2ce02f984a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::computeAndPropagateWeights (<a href="#af897082b1f09e18ffa991e88464bc089">FunctionT</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; InlinedGUIDs)</td>
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

<p>Generate branch weight metadata for all branches in <span class="doxyComputerOutput">F</span>.</p>


<p>Branch weights are computed out of instruction samples using a propagation heuristic. Propagation proceeds in 3 phases:</p>


<p>1- Assignment of block weights. All the basic blocks in the function are initial assigned the same weight as their most frequently executed instruction.</p>


<p>2- Creation of equivalence classes. Since samples may be missing from blocks, we can fill in the gaps by setting the weights of all the blocks in the same equivalence class to the same weight. To compute the concept of equivalence, we use dominance and loop information. Two blocks B1 and B2 are in the same equivalence class if B1 dominates B2, B2 post-dominates B1 and both are in the same loop.</p>


<p>3- Propagation of block weights into edges. This uses a simple propagation heuristic. The following rules are applied to every block BB in the CFG:</p>


<ul class="doxyList ">
<li>If BB has a single predecessor/successor, then the weight of that edge is the weight of the block.</li>
<li>If all the edges are known except one, and the weight of the block is already known, the weight of the unknown edge will be the weight of the block minus the sum of all the known edges. If the sum of all the known edges is larger than BB's weight, we set the unknown edge weight to zero.</li>
<li>If there is a self-referential edge, and the weight of the block is known, the weight for that edge is set to the weight of the block minus the weight of the other incoming edges to that block (if known).</li>
</ul>

<p>Since this propagation is not guaranteed to finalize for every CFG, we only allow it to proceed for a limited number of iterations (controlled by -sample-profile-max-propagate-iterations).</p>


<p>FIXME: Try to replace this propagation heuristic with a scheme that is guaranteed to finalize. A work-list approach similar to the standard value propagation algorithm used by SSA-CCP might work here.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">F</td>
<td class="doxyParamItemDescription"><p>The function to query.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">F</span> was modified. Returns false, otherwise.</p></dd>
</dl>


<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="#abfedd5d05290a01e9b21cde734588620">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::computeBlockWeights</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#abdc4c98f065999f51c3871a59e5c1de2">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::finalizeWeightPropagation</a>, <a href="#ab399a6466f9c56febc239c000eee5406">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::initWeightPropagation</a>, <a href="#afeab810a0b4abc92f2650348428220a2">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateWeights</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a9a025cb106832026cd05c2b4648a699f">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::size</a>.</p>

</div>
</div>

### computeBlockWeights() {#abfedd5d05290a01e9b21cde734588620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::computeBlockWeights (<a href="#af897082b1f09e18ffa991e88464bc089">FunctionT</a> &amp; F)</td>
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

<p>Compute and store the weights of every basic block.</p>


<p>This populates the BlockWeights map by computing the weights of every basic block in the CFG.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">F</td>
<td class="doxyParamItemDescription"><p>The function to query.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="#afd962f6862c0fa756bc3d8e2e751a955">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::BlockWeights</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a366f5bc39f00b9b44f1f39adca8b414c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getBlockWeight</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a7222989331e6d8e7845bad3d2d385486">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::printBlockWeight</a> and <a href="#a425760bcf9be77e6a664a5997283a2e1">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::VisitedBlocks</a>.</p>


<p>Referenced by <a href="#a040b98a945772423eab83d2ce02f984a">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::computeAndPropagateWeights</a>.</p>

</div>
</div>

### computeDominanceAndLoopInfo() {#a09b07d241e152c373256e084d21568d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::computeDominanceAndLoopInfo (<a href="#af897082b1f09e18ffa991e88464bc089">FunctionT</a> &amp; F)</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#ab399a6466f9c56febc239c000eee5406">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::initWeightPropagation</a>.</p>

</div>
</div>

### computeDominanceAndLoopInfo() {#ae8a07594791a56f3c10df035214129bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::computeDominanceAndLoopInfo (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; F)</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a>.</p>

</div>
</div>

### computeDominanceAndLoopInfo() {#a85fc6a15bf46677c3617667d473d479e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::computeDominanceAndLoopInfo (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>

</div>
</div>

### emitCoverageRemarks() {#a9da04aa71aaa9243bb7efe549f1dd758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::emitCoverageRemarks (<a href="#af897082b1f09e18ffa991e88464bc089">FunctionT</a> &amp; F)</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="#a52673282884569984ceee1e4f7119a50">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::CoverageTracker</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1cde8c8828756cdaf2a93260e247ae31">llvm::DS_Warning</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp/#a92efb02157b6836e1232c577d34678d6">getFunction</a>, <a href="#a3bb6939c9a307a2d7a2bc20363b5433c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getFunctionLoc</a>, <a href="#ae49ac2191e91a12f7ed0b92b2b72ebbe">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::PSI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f549b38dfc4e0ddd2c4769bb63e03be">llvm::SampleProfileRecordCoverage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4c0c9d54b482a33deaf3c8c2b5a05652">llvm::SampleProfileSampleCoverage</a>, <a href="#ad9ec5be72117476a75c7dd1cc59d03f1">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Samples</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af5ab7a47bc553dfc3ee92daf969d0d7ca96b0141273eabab320119c467cdcaf17">llvm::Total</a>.</p>

</div>
</div>

### finalizeWeightPropagation() {#abdc4c98f065999f51c3871a59e5c1de2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::finalizeWeightPropagation (<a href="#af897082b1f09e18ffa991e88464bc089">FunctionT</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; InlinedGUIDs)</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="#afd962f6862c0fa756bc3d8e2e751a955">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::BlockWeights</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a366f5bc39f00b9b44f1f39adca8b414c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getBlockWeight</a>, <a href="#a2b8f887a5dfc3eaa968ede5f79a2fc12">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getEntryBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp/#a92efb02157b6836e1232c577d34678d6">getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a438d2f246b76817114ade2a005a6bcabac7dbc704eba08842e6acdde9cf6379ba">llvm::Function::PCT_Real</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6074db8acc6aa7a2f810d5918a793e87">llvm::SampleProfileUseProfi</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#aefb3254278b224f10e5b966cea653e01">llvm::Function::setEntryCount</a>.</p>


<p>Referenced by <a href="#a040b98a945772423eab83d2ce02f984a">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::computeAndPropagateWeights</a>.</p>

</div>
</div>

### findEquivalenceClasses() {#adad5302e31acac871db7fe5c38940377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::findEquivalenceClasses (<a href="#af897082b1f09e18ffa991e88464bc089">FunctionT</a> &amp; F)</td>
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

<p>Find equivalence classes.</p>


<p>Since samples may be missing from blocks, we can fill in the gaps by setting the weights of all the blocks in the same equivalence class to the same weight. To compute the concept of equivalence, we use dominance and loop information. Two blocks B1 and B2 are in the same equivalence class if B1 dominates B2, B2 post-dominates B1 and both are in the same loop.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">F</td>
<td class="doxyParamItemDescription"><p>The function to query.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="#afd962f6862c0fa756bc3d8e2e751a955">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::BlockWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a726028c50f8c9cea16a85ffa721a78b4">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::DT</a>, <a href="#a4a4a260ea818b3bfe7ae4f0da463dbb9">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::EquivalenceClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#aee060f872d48fa04e7ec34df784ce088">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findEquivalencesFor</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aa48c470371fe9507bec17abd3333fd1f">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::PDT</a>, <a href="#a75839e382274534379a37deb48fb80dc">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::printBlockEquivalence</a> and <a href="#a7222989331e6d8e7845bad3d2d385486">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::printBlockWeight</a>.</p>


<p>Referenced by <a href="#ab399a6466f9c56febc239c000eee5406">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::initWeightPropagation</a>.</p>

</div>
</div>

### findEquivalencesFor() {#aee060f872d48fa04e7ec34df784ce088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::findEquivalencesFor (<a href="#a10d31eaba9ec292510535e508e6d52f1">BasicBlockT</a> * BB1, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="#a10d31eaba9ec292510535e508e6d52f1">BasicBlockT</a> * &gt; Descendants, <a href="#acd3af750070884babd65d72b6a4ebf8b">PostDominatorTreeT</a> * DomTree)</td>
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

<p>Find equivalence classes for the given block.</p>


<p>This finds all the blocks that are guaranteed to execute the same number of times as <span class="doxyComputerOutput">BB1</span>. To do this, it traverses all the descendants of <span class="doxyComputerOutput">BB1</span> in the dominator or post-dominator tree.</p>


<p>A block BB2 will be in the same equivalence class as <span class="doxyComputerOutput">BB1</span> if the following holds:</p>


<p>1- <span class="doxyComputerOutput">BB1</span> is a descendant of BB2 in the opposite tree. So, if BB2 is a descendant of <span class="doxyComputerOutput">BB1</span> in the dominator tree, then BB2 should dominate BB1 in the post-dominator tree.</p>


<p>2- Both BB2 and <span class="doxyComputerOutput">BB1</span> must be in the same loop.</p>


<p>For every block BB2 that meets those two requirements, we set BB2's equivalence class to <span class="doxyComputerOutput">BB1</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB1</td>
<td class="doxyParamItemDescription"><p>Block to check.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Descendants</td>
<td class="doxyParamItemDescription"><p>Descendants of <span class="doxyComputerOutput">BB1</span> in either the dom or pdom tree.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DomTree</td>
<td class="doxyParamItemDescription"><p>Opposite dominator tree. If <span class="doxyComputerOutput">Descendants</span> is filled with blocks from <span class="doxyComputerOutput">BB1's</span> dominator tree, then this is the post-dominator tree, and vice versa.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="#afd962f6862c0fa756bc3d8e2e751a955">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::BlockWeights</a>, <a href="#a4a4a260ea818b3bfe7ae4f0da463dbb9">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::EquivalenceClass</a>, <a href="#a2b8f887a5dfc3eaa968ede5f79a2fc12">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getEntryBB</a>, <a href="#ae5efdc714ce4789b9a1ffe59bb055cc7">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::LI</a>, <a href="#ad9ec5be72117476a75c7dd1cc59d03f1">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Samples</a> and <a href="#a425760bcf9be77e6a664a5997283a2e1">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::VisitedBlocks</a>.</p>


<p>Referenced by <a href="#adad5302e31acac871db7fe5c38940377">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findEquivalenceClasses</a>.</p>

</div>
</div>

### findFunctionSamples() {#ac129a5f56604167d730262a05cb1fd02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FunctionSamples * llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::findFunctionSamples (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aabc995a0d85012b77c9232d201d520f2">InstructionT</a> &amp; Inst)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> for an instruction.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> of an instruction <span class="doxyComputerOutput">Inst</span> is the inlined instance in which that instruction is coming from. We traverse the inline stack of that instruction, and match it with the tree nodes in the profile.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Inst</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to query.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> pointer to the inlined instance.</p></dd>
</dl>


<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="#aeacafab53cd915d0ff8922dcb398fbe1">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::DILocation2SampleMap</a>, <a href="#a6cda1f8872cce456c1ec260c8ef7aa24">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Reader</a> and <a href="#ad9ec5be72117476a75c7dd1cc59d03f1">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Samples</a>.</p>


<p>Referenced by <a href="#a3fd239026aba79e9aaf5b81578f4198c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getInstWeightImpl</a> and <a href="#acdcff307bede233f8221f618d262b6df">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getProbeWeight</a>.</p>

</div>
</div>

### getBlockWeight() {#a366f5bc39f00b9b44f1f39adca8b414c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; uint64_t &gt; llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::getBlockWeight (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a10d31eaba9ec292510535e508e6d52f1">BasicBlockT</a> * BB)</td>
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

<p>Compute the weight of a basic block.</p>


<p>The weight of basic block <span class="doxyComputerOutput">BB</span> is the maximum weight of all the instructions in BB.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB</td>
<td class="doxyParamItemDescription"><p>The basic block to query.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the weight for <span class="doxyComputerOutput">BB</span>.</p></dd>
</dl>


<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="#a4242a2c35893bbf85211387709d6a3d1">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getInstWeight</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#abfedd5d05290a01e9b21cde734588620">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::computeBlockWeights</a>, <a href="#abdc4c98f065999f51c3871a59e5c1de2">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::finalizeWeightPropagation</a> and <a href="#afeab810a0b4abc92f2650348428220a2">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateWeights</a>.</p>

</div>
</div>

### getEntryBB() {#a2b8f887a5dfc3eaa968ede5f79a2fc12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlockT * llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getEntryBB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#af897082b1f09e18ffa991e88464bc089">FunctionT</a> * F)</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#abdc4c98f065999f51c3871a59e5c1de2">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::finalizeWeightPropagation</a> and <a href="#aee060f872d48fa04e7ec34df784ce088">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findEquivalencesFor</a>.</p>

</div>
</div>

### getFunction() {#a27bf2b96e5c474b00a78fade0b7a37e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function &amp; llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getFunction (<a href="#af897082b1f09e18ffa991e88464bc089">FunctionT</a> &amp; F)</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### getFunctionLoc() {#a3bb6939c9a307a2d7a2bc20363b5433c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::getFunctionLoc (<a href="#af897082b1f09e18ffa991e88464bc089">FunctionT</a> &amp; F)</td>
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

<p>Get the line number for the function header.</p>


<p>This looks up function <span class="doxyComputerOutput">F</span> in the current compilation unit and retrieves the line number where the function is defined. This is line 0 for all the samples read from the profile file. Every line number is relative to this line.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">F</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> object to query.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the line number where <span class="doxyComputerOutput">F</span> is defined. If it returns 0, it means that there is no debug information available for <span class="doxyComputerOutput">F</span>.</p></dd>
</dl>


<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1cde8c8828756cdaf2a93260e247ae31">llvm::DS_Warning</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp/#a92efb02157b6836e1232c577d34678d6">getFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a921b74c15d3400979374dec5abb8ea31">llvm::NoWarnSampleUnused</a>.</p>


<p>Referenced by <a href="#a9da04aa71aaa9243bb7efe549f1dd758">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::emitCoverageRemarks</a>.</p>

</div>
</div>

### getInstWeight() {#a4242a2c35893bbf85211387709d6a3d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; uint64_t &gt; llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::getInstWeight (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aabc995a0d85012b77c9232d201d520f2">InstructionT</a> &amp; Inst)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the weight for an instruction.</p>


<p>The "weight" of an instruction <span class="doxyComputerOutput">Inst</span> is the number of samples collected on that instruction at runtime. To retrieve it, we need to compute the line number of <span class="doxyComputerOutput">Inst</span> relative to the start of its function. We use HeaderLineno to compute the offset. We then look up the samples collected for <span class="doxyComputerOutput">Inst</span> using BodySamples.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Inst</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to query.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the weight of <span class="doxyComputerOutput">Inst</span>.</p></dd>
</dl>


<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="#a3fd239026aba79e9aaf5b81578f4198c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getInstWeightImpl</a>, <a href="#acdcff307bede233f8221f618d262b6df">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getProbeWeight</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa37fe7429ffcf70c306c27a55d714d31">llvm::sampleprof::FunctionSamples::ProfileIsProbeBased</a>.</p>


<p>Referenced by <a href="#a366f5bc39f00b9b44f1f39adca8b414c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getBlockWeight</a>.</p>

</div>
</div>

### getInstWeightImpl() {#a3fd239026aba79e9aaf5b81578f4198c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; uint64_t &gt; llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::getInstWeightImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aabc995a0d85012b77c9232d201d520f2">InstructionT</a> &amp; Inst)</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="#a52673282884569984ceee1e4f7119a50">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::CoverageTracker</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61cf315897c96016607a2b8d5916a64d">llvm::EnableFSDiscriminator</a>, <a href="#ac129a5f56604167d730262a05cb1fd02">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findFunctionSamples</a>, <a href="#a12022aa707c271f81eae8ec0eebfae29">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::FS</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a959d7d5282de6f6f459425591e7482d7">llvm::DILocation::getBaseDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/debugloc/#a427c256af834975c7869ad28fac00563">llvm::DebugLoc::getLine</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ab6f00f222e6f6d30bc6a0fc7bf8396de">llvm::sampleprof::FunctionSamples::getOffset</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a293c85647f9dcb78f29ad5ab31e5a7f9">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::ORE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a91921ada405fd6ba65dff028df047cb6">llvm::Remark</a>.</p>


<p>Referenced by <a href="#a4242a2c35893bbf85211387709d6a3d1">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getInstWeight</a>.</p>

</div>
</div>

### getPredecessors() {#a3bf69a5f2b0cc7bba7b071fc67b050b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredRangeT llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getPredecessors (<a href="#a10d31eaba9ec292510535e508e6d52f1">BasicBlockT</a> * BB)</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#aedaa834891e933cab48185f1bd32354c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::buildEdges</a>.</p>

</div>
</div>

### getProbeWeight() {#acdcff307bede233f8221f618d262b6df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; uint64_t &gt; llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::getProbeWeight (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aabc995a0d85012b77c9232d201d520f2">InstructionT</a> &amp; Inst)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a52673282884569984ceee1e4f7119a50">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::CoverageTracker</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b3e8a01dfede6141c79e012a44ec9e4">llvm::extractProbe</a>, <a href="#ac129a5f56604167d730262a05cb1fd02">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findFunctionSamples</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#a12022aa707c271f81eae8ec0eebfae29">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::FS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a293c85647f9dcb78f29ad5ab31e5a7f9">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::ORE</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa37fe7429ffcf70c306c27a55d714d31">llvm::sampleprof::FunctionSamples::ProfileIsProbeBased</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a91921ada405fd6ba65dff028df047cb6">llvm::Remark</a> and <a href="#ad9ec5be72117476a75c7dd1cc59d03f1">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Samples</a>.</p>


<p>Referenced by <a href="#a4242a2c35893bbf85211387709d6a3d1">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getInstWeight</a>.</p>

</div>
</div>

### getSuccessors() {#aa04ab96e7be5ad3ced9aa3bd35f76eac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SuccRangeT llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getSuccessors (<a href="#a10d31eaba9ec292510535e508e6d52f1">BasicBlockT</a> * BB)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#aedaa834891e933cab48185f1bd32354c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::buildEdges</a>.</p>

</div>
</div>

### initWeightPropagation() {#ab399a6466f9c56febc239c000eee5406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::initWeightPropagation (<a href="#af897082b1f09e18ffa991e88464bc089">FunctionT</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; InlinedGUIDs)</td>
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



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="#aedaa834891e933cab48185f1bd32354c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::buildEdges</a>, <a href="#a09b07d241e152c373256e084d21568d2">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::computeDominanceAndLoopInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#adad5302e31acac871db7fe5c38940377">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findEquivalenceClasses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp/#a92efb02157b6836e1232c577d34678d6">getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a438d2f246b76817114ade2a005a6bcabac7dbc704eba08842e6acdde9cf6379ba">llvm::Function::PCT_Real</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6074db8acc6aa7a2f810d5918a793e87">llvm::SampleProfileUseProfi</a>, <a href="#ad9ec5be72117476a75c7dd1cc59d03f1">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Samples</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#aefb3254278b224f10e5b966cea653e01">llvm::Function::setEntryCount</a>.</p>


<p>Referenced by <a href="#a040b98a945772423eab83d2ce02f984a">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::computeAndPropagateWeights</a>.</p>

</div>
</div>

### printBlockEquivalence() {#a75839e382274534379a37deb48fb80dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::printBlockEquivalence (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a10d31eaba9ec292510535e508e6d52f1">BasicBlockT</a> * BB)</td>
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

<p>Print the equivalence class of block <span class="doxyComputerOutput">BB</span> on stream <span class="doxyComputerOutput">OS</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>Stream to emit the output to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB</td>
<td class="doxyParamItemDescription"><p>Block to print.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Reference <a href="#a4a4a260ea818b3bfe7ae4f0da463dbb9">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::EquivalenceClass</a>.</p>


<p>Referenced by <a href="#adad5302e31acac871db7fe5c38940377">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findEquivalenceClasses</a>.</p>

</div>
</div>

### printBlockWeight() {#a7222989331e6d8e7845bad3d2d385486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::printBlockWeight (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a10d31eaba9ec292510535e508e6d52f1">BasicBlockT</a> * BB)</td>
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

<p>Print the weight of block <span class="doxyComputerOutput">BB</span> on stream <span class="doxyComputerOutput">OS</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>Stream to emit the output to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB</td>
<td class="doxyParamItemDescription"><p>Block to print.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="#afd962f6862c0fa756bc3d8e2e751a955">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::BlockWeights</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#abfedd5d05290a01e9b21cde734588620">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::computeBlockWeights</a>, <a href="#adad5302e31acac871db7fe5c38940377">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findEquivalenceClasses</a> and <a href="#aa435e55eb50c7ecc8e69e636eb1fe345">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateThroughEdges</a>.</p>

</div>
</div>

### printEdgeWeight() {#af80c8905cce458376f69ac1282a07bc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::printEdgeWeight (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="#ae0c6798ea9e2df9241569f6b9f6287da">Edge</a> E)</td>
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

<p>Print the weight of edge <span class="doxyComputerOutput">E</span> on stream <span class="doxyComputerOutput">OS</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>Stream to emit the output to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">E</td>
<td class="doxyParamItemDescription"><p><a href="#ae0c6798ea9e2df9241569f6b9f6287da">Edge</a> to print.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="#a25b4d69386a27e339e802ac43d47fe33">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::EdgeWeights</a>.</p>


<p>Referenced by <a href="#aa435e55eb50c7ecc8e69e636eb1fe345">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateThroughEdges</a>.</p>

</div>
</div>

### propagateThroughEdges() {#aa435e55eb50c7ecc8e69e636eb1fe345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::propagateThroughEdges (<a href="#af897082b1f09e18ffa991e88464bc089">FunctionT</a> &amp; F, bool UpdateBlockCount)</td>
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

<p>Propagate weights through incoming/outgoing edges.</p>


<p>If the weight of a basic block is known, and there is only one edge with an unknown weight, we can calculate the weight of that edge.</p>


<p>Similarly, if all the edges have a known count, we can calculate the count of the basic block, if needed.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">F</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> to process.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UpdateBlockCount</td>
<td class="doxyParamItemDescription"><p>Whether we should update basic block counts that has already been annotated.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if new weights were assigned to edges or blocks.</p></dd>
</dl>


<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="#afd962f6862c0fa756bc3d8e2e751a955">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::BlockWeights</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a25b4d69386a27e339e802ac43d47fe33">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::EdgeWeights</a>, <a href="#a4a4a260ea818b3bfe7ae4f0da463dbb9">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::EquivalenceClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ab84644c12ae7f1ff1b2db384132d0b4c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Predecessors</a>, <a href="#a7222989331e6d8e7845bad3d2d385486">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::printBlockWeight</a>, <a href="#af80c8905cce458376f69ac1282a07bc3">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::printEdgeWeight</a>, <a href="#ad6a5a5bd663105131550df5f7593ef0f">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Successors</a>, <a href="#a425760bcf9be77e6a664a5997283a2e1">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::VisitedBlocks</a>, <a href="#a27d241cbcd8f53b9f09c7c19242cb789">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::VisitedEdges</a> and <a href="#ab32be71f5ab339400be1f2eba700b290">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::visitEdge</a>.</p>


<p>Referenced by <a href="#afeab810a0b4abc92f2650348428220a2">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateWeights</a>.</p>

</div>
</div>

### propagateWeights() {#afeab810a0b4abc92f2650348428220a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::propagateWeights (<a href="#af897082b1f09e18ffa991e88464bc089">FunctionT</a> &amp; F)</td>
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

<p>Propagate weights into edges.</p>


<p>The following rules are applied to every block BB in the CFG:</p>


<ul class="doxyList ">
<li>If BB has a single predecessor/successor, then the weight of that edge is the weight of the block.</li>
<li>If all incoming or outgoing edges are known except one, and the weight of the block is already known, the weight of the unknown edge will be the weight of the block minus the sum of all the known edges. If the sum of all the known edges is larger than BB's weight, we set the unknown edge weight to zero.</li>
<li>If there is a self-referential edge, and the weight of the block is known, the weight for that edge is set to the weight of the block minus the weight of the other incoming edges to that block (if known).</li>
</ul>

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="#ad3a21cb53662f9cd445fa9d5e384d761">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::applyProfi</a>, <a href="#afd962f6862c0fa756bc3d8e2e751a955">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::BlockWeights</a>, <a href="#a25b4d69386a27e339e802ac43d47fe33">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::EdgeWeights</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a366f5bc39f00b9b44f1f39adca8b414c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getBlockWeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ae5efdc714ce4789b9a1ffe59bb055cc7">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::LI</a>, <a href="#aa435e55eb50c7ecc8e69e636eb1fe345">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateThroughEdges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52f8beb60878a03b2ea1f75b6c2e08b9">llvm::SampleProfileMaxPropagateIterations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6074db8acc6aa7a2f810d5918a793e87">llvm::SampleProfileUseProfi</a>, <a href="#ad6a5a5bd663105131550df5f7593ef0f">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Successors</a> and <a href="#a27d241cbcd8f53b9f09c7c19242cb789">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::VisitedEdges</a>.</p>


<p>Referenced by <a href="#a040b98a945772423eab83d2ce02f984a">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::computeAndPropagateWeights</a>.</p>

</div>
</div>

### visitEdge() {#ab32be71f5ab339400be1f2eba700b290}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::SampleProfileLoaderBaseImpl&lt; BT &gt;::visitEdge (<a href="#ae0c6798ea9e2df9241569f6b9f6287da">Edge</a> E, unsigned * NumUnknownEdges, <a href="#ae0c6798ea9e2df9241569f6b9f6287da">Edge</a> * UnknownEdge)</td>
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

<p>Visit the given edge to decide if it has a valid weight.</p>


<p>If <span class="doxyComputerOutput">E</span> has not been visited before, we copy to <span class="doxyComputerOutput">UnknownEdge</span> and increment the count of unknown edges.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">E</td>
<td class="doxyParamItemDescription"><p><a href="#ae0c6798ea9e2df9241569f6b9f6287da">Edge</a> to visit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumUnknownEdges</td>
<td class="doxyParamItemDescription"><p>Current number of unknown edges.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UnknownEdge</td>
<td class="doxyParamItemDescription"><p>Set if E has not been visited before.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>E's weight, if known. Otherwise, return 0.</p></dd>
</dl>


<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a25b4d69386a27e339e802ac43d47fe33">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::EdgeWeights</a> and <a href="#a27d241cbcd8f53b9f09c7c19242cb789">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::VisitedEdges</a>.</p>


<p>Referenced by <a href="#aa435e55eb50c7ecc8e69e636eb1fe345">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateThroughEdges</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### BlockWeights {#afd962f6862c0fa756bc3d8e2e751a955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockWeightMap llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::BlockWeights</td>
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

<p>Map basic blocks to their computed weights.</p>


<p>The weight of a basic block is defined to be the maximum of all the instruction weights in that block.</p>


<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#ad3a21cb53662f9cd445fa9d5e384d761">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::applyProfi</a>, <a href="#ae9bae46af4ef474d7f244e4f9b67e188">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::clearFunctionData</a>, <a href="#abfedd5d05290a01e9b21cde734588620">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::computeBlockWeights</a>, <a href="#abdc4c98f065999f51c3871a59e5c1de2">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::finalizeWeightPropagation</a>, <a href="#adad5302e31acac871db7fe5c38940377">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findEquivalenceClasses</a>, <a href="#aee060f872d48fa04e7ec34df784ce088">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findEquivalencesFor</a>, <a href="#a7222989331e6d8e7845bad3d2d385486">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::printBlockWeight</a>, <a href="#aa435e55eb50c7ecc8e69e636eb1fe345">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateThroughEdges</a> and <a href="#afeab810a0b4abc92f2650348428220a2">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateWeights</a>.</p>

</div>
</div>

### CoverageTracker {#a52673282884569984ceee1e4f7119a50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampleCoverageTracker llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::CoverageTracker</td>
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

<p>Profile coverage tracker.</p>

<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#ae9bae46af4ef474d7f244e4f9b67e188">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::clearFunctionData</a>, <a href="#a9da04aa71aaa9243bb7efe549f1dd758">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::emitCoverageRemarks</a>, <a href="#a3fd239026aba79e9aaf5b81578f4198c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getInstWeightImpl</a> and <a href="#acdcff307bede233f8221f618d262b6df">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getProbeWeight</a>.</p>

</div>
</div>

### DILocation2SampleMap {#aeacafab53cd915d0ff8922dcb398fbe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const DILocation *, const FunctionSamples *&gt; llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::DILocation2SampleMap</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#ac129a5f56604167d730262a05cb1fd02">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findFunctionSamples</a>.</p>

</div>
</div>

### DT {#a726028c50f8c9cea16a85ffa721a78b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTreePtrT llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::DT</td>
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

<p>Dominance, post-dominance and loop information.</p>

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#ae9bae46af4ef474d7f244e4f9b67e188">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::clearFunctionData</a> and <a href="#adad5302e31acac871db7fe5c38940377">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findEquivalenceClasses</a>.</p>

</div>
</div>

### EdgeWeights {#a25b4d69386a27e339e802ac43d47fe33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeWeightMap llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::EdgeWeights</td>
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

<p>Map edges to their computed weights.</p>


<p><a href="#ae0c6798ea9e2df9241569f6b9f6287da">Edge</a> weights are computed by propagating basic block weights in SampleProfile::propagateWeights.</p>


<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#ad3a21cb53662f9cd445fa9d5e384d761">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::applyProfi</a>, <a href="#ae9bae46af4ef474d7f244e4f9b67e188">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::clearFunctionData</a>, <a href="#af80c8905cce458376f69ac1282a07bc3">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::printEdgeWeight</a>, <a href="#aa435e55eb50c7ecc8e69e636eb1fe345">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateThroughEdges</a>, <a href="#afeab810a0b4abc92f2650348428220a2">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateWeights</a> and <a href="#ab32be71f5ab339400be1f2eba700b290">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::visitEdge</a>.</p>

</div>
</div>

### EquivalenceClass {#a4a4a260ea818b3bfe7ae4f0da463dbb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EquivalenceClassMap llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::EquivalenceClass</td>
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

<p>Equivalence classes for block weights.</p>


<p>Two blocks BB1 and BB2 are in the same equivalence class if they dominate and post-dominate each other, and they are in the same loop nest. When this happens, the two blocks are guaranteed to execute the same number of times.</p>


<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#ae9bae46af4ef474d7f244e4f9b67e188">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::clearFunctionData</a>, <a href="#adad5302e31acac871db7fe5c38940377">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findEquivalenceClasses</a>, <a href="#aee060f872d48fa04e7ec34df784ce088">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findEquivalencesFor</a>, <a href="#a75839e382274534379a37deb48fb80dc">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::printBlockEquivalence</a> and <a href="#aa435e55eb50c7ecc8e69e636eb1fe345">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateThroughEdges</a>.</p>

</div>
</div>

### Filename {#aa25c9c0884c2fc1dc621c881c00485f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Filename</td>
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

<p>Name of the profile file to load.</p>

<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#a8914bae43b683a78d971e5954d781331">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::SampleProfileLoaderBaseImpl</a>.</p>

</div>
</div>

### FS {#a12022aa707c271f81eae8ec0eebfae29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrusiveRefCntPtr&lt;vfs::FileSystem&gt; llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::FS</td>
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

<p>VirtualFileSystem to load profile files from.</p>

<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#a3fd239026aba79e9aaf5b81578f4198c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getInstWeightImpl</a>, <a href="#acdcff307bede233f8221f618d262b6df">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getProbeWeight</a> and <a href="#a8914bae43b683a78d971e5954d781331">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::SampleProfileLoaderBaseImpl</a>.</p>

</div>
</div>

### LI {#ae5efdc714ce4789b9a1ffe59bb055cc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfoPtrT llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::LI</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#ae9bae46af4ef474d7f244e4f9b67e188">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::clearFunctionData</a>, <a href="#aee060f872d48fa04e7ec34df784ce088">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findEquivalencesFor</a> and <a href="#afeab810a0b4abc92f2650348428220a2">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateWeights</a>.</p>

</div>
</div>

### ORE {#a293c85647f9dcb78f29ad5ab31e5a7f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptRemarkEmitterT* llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::ORE = nullptr</td>
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

<p>Optimization Remark Emitter used to emit diagnostic remarks.</p>

<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#a3fd239026aba79e9aaf5b81578f4198c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getInstWeightImpl</a> and <a href="#acdcff307bede233f8221f618d262b6df">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getProbeWeight</a>.</p>

</div>
</div>

### OutlineFunctionSamples {#a28a1e350b54691c575efa482bfc72140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;SampleContext, FunctionSamples&gt; llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::OutlineFunctionSamples</td>
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

<p>Synthetic samples created by duplicating the samples of inlined functions from the original profile as if they were top level sample profiles.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> std::map because insertion may happen while its content is referenced.</p>


<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### PDT {#aa48c470371fe9507bec17abd3333fd1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PostDominatorTreePtrT llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::PDT</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#ae9bae46af4ef474d7f244e4f9b67e188">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::clearFunctionData</a> and <a href="#adad5302e31acac871db7fe5c38940377">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findEquivalenceClasses</a>.</p>

</div>
</div>

### Predecessors {#ab84644c12ae7f1ff1b2db384132d0b4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockEdgeMap llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Predecessors</td>
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

<p>Predecessors for each basic block in the CFG.</p>

<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#aedaa834891e933cab48185f1bd32354c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::buildEdges</a>, <a href="#ae9bae46af4ef474d7f244e4f9b67e188">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::clearFunctionData</a> and <a href="#aa435e55eb50c7ecc8e69e636eb1fe345">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateThroughEdges</a>.</p>

</div>
</div>

### ProbeManager {#a8a061b4f421152b76653f15e18bec185}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;PseudoProbeManager&gt; llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::ProbeManager</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>

</div>
</div>

### PSI {#ae49ac2191e91a12f7ed0b92b2b72ebbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummaryInfo* llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::PSI = nullptr</td>
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

<p>Profile Summary Info computed from sample profile.</p>

<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#a9da04aa71aaa9243bb7efe549f1dd758">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::emitCoverageRemarks</a>.</p>

</div>
</div>

### Reader {#a6cda1f8872cce456c1ec260c8ef7aa24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SampleProfileReader&gt; llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Reader</td>
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

<p>Profile reader object.</p>

<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#a1510e04c6817c687a27c439d5ad36584">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::dump</a> and <a href="#ac129a5f56604167d730262a05cb1fd02">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findFunctionSamples</a>.</p>

</div>
</div>

### RemappingFilename {#ad0b57e56868a6c60929c62f1494628af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::RemappingFilename</td>
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

<p>Name of the profile remapping file to load.</p>

<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#a8914bae43b683a78d971e5954d781331">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::SampleProfileLoaderBaseImpl</a>.</p>

</div>
</div>

### Samples {#ad9ec5be72117476a75c7dd1cc59d03f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSamples* llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Samples = nullptr</td>
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

<p>Samples collected for the body of this function.</p>

<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#a9da04aa71aaa9243bb7efe549f1dd758">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::emitCoverageRemarks</a>, <a href="#aee060f872d48fa04e7ec34df784ce088">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findEquivalencesFor</a>, <a href="#ac129a5f56604167d730262a05cb1fd02">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findFunctionSamples</a>, <a href="#acdcff307bede233f8221f618d262b6df">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getProbeWeight</a> and <a href="#ab399a6466f9c56febc239c000eee5406">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::initWeightPropagation</a>.</p>

</div>
</div>

### Successors {#ad6a5a5bd663105131550df5f7593ef0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockEdgeMap llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::Successors</td>
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

<p>Successors for each basic block in the CFG.</p>

<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#ad3a21cb53662f9cd445fa9d5e384d761">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::applyProfi</a>, <a href="#aedaa834891e933cab48185f1bd32354c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::buildEdges</a>, <a href="#ae9bae46af4ef474d7f244e4f9b67e188">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::clearFunctionData</a>, <a href="#aa435e55eb50c7ecc8e69e636eb1fe345">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateThroughEdges</a> and <a href="#afeab810a0b4abc92f2650348428220a2">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateWeights</a>.</p>

</div>
</div>

### VisitedBlocks {#a425760bcf9be77e6a664a5997283a2e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const BasicBlockT *, 32&gt; llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::VisitedBlocks</td>
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

<p>Set of visited blocks during propagation.</p>

<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#ae9bae46af4ef474d7f244e4f9b67e188">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::clearFunctionData</a>, <a href="#abfedd5d05290a01e9b21cde734588620">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::computeBlockWeights</a>, <a href="#aee060f872d48fa04e7ec34df784ce088">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::findEquivalencesFor</a> and <a href="#aa435e55eb50c7ecc8e69e636eb1fe345">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateThroughEdges</a>.</p>

</div>
</div>

### VisitedEdges {#a27d241cbcd8f53b9f09c7c19242cb789}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSet&lt;Edge, 32&gt; llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::VisitedEdges</td>
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

<p>Set of visited edges during propagation.</p>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a>.</p>


<p>Referenced by <a href="#ae9bae46af4ef474d7f244e4f9b67e188">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::clearFunctionData</a>, <a href="#aa435e55eb50c7ecc8e69e636eb1fe345">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateThroughEdges</a>, <a href="#afeab810a0b4abc92f2650348428220a2">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::propagateWeights</a> and <a href="#ab32be71f5ab339400be1f2eba700b290">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::visitEdge</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">SampleProfileLoaderBaseImpl.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
