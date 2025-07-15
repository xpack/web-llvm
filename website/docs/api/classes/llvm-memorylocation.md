---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memorylocation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MemoryLocation` Class Reference

<p>Representation for a specific memory location. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MemoryLocation { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">llvm/Analysis/MemoryLocation.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint64_t { <a href="#a031e3abd6e1a18f9462f7cee212ba004">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>UnknownSize - This is a special value which can be used with the size arguments in alias queries to indicate that the caller does not know the sizes of the potential memory references. <a href="#a031e3abd6e1a18f9462f7cee212ba004">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6df048912d249abd35e7b75dda080af">MemoryLocation</a> (const Value *Ptr, LocationSize Size, const AAMDNodes &amp;AATags=AAMDNodes())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb476100bd92dff58e8d94e4feddac0d">operator==</a> (const MemoryLocation &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a219a6b067df507c97053410136be7d7a">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81f225396ee3b9587327c8009f9dce40">getWithNewPtr</a> (const Value *NewPtr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a078f7dbb4fe93a1a5921d82a91f04875">getWithNewSize</a> (LocationSize NewSize) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b970d738243dcc4f94c0834ca26b09f">getWithoutAATags</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9550ce4a179e46db37f653ce28feca7a">Ptr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The address of the start of the location. <a href="#a9550ce4a179e46db37f653ce28feca7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f7ff959874bf38f3e14aa0b2622da0">Size</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum size of the location, in address-units, or UnknownSize if the size is not known. <a href="#a39f7ff959874bf38f3e14aa0b2622da0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a926099ca5ca5db6ba2de398c2487b725">AATags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The metadata nodes which describes the aliasing of the location (each member is null if that kind of information is unavailable). <a href="#a926099ca5ca5db6ba2de398c2487b725">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18e5a3f1d71ba10a624f2a8e5121cf1f">get</a> (const LoadInst *LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a location with information about the memory reference by the given instruction. <a href="#a18e5a3f1d71ba10a624f2a8e5121cf1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4037bfe373761aedbe48f3010dbadfed">get</a> (const StoreInst *SI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a7fb118760760e7530c5d6f5be6ce64">get</a> (const VAArgInst *VI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c1bd5fd8ec3eeb7320cd9d457b0f164">get</a> (const AtomicCmpXchgInst *CXI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46d61c561714322cb42bd3db9f1609fa">get</a> (const AtomicRMWInst *RMWI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61dc6d1a1e9c3cb0adb4c791b329ff31">get</a> (const Instruction *Inst)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af61b31a99c1e58b1760492d2a7a1ba9c">getOrNone</a> (const Instruction *Inst)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a207e239d68b66b0d5ccad5997a5ef027">getForSource</a> (const MemTransferInst *MTI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a location representing the source of a memory transfer. <a href="#a207e239d68b66b0d5ccad5997a5ef027">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affa4eee9971fefed07074382af167a70">getForSource</a> (const AtomicMemTransferInst *MTI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af438c8da3109f9d2b1530aed2771b88e">getForSource</a> (const AnyMemTransferInst *MTI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8f8983c6b76d0e30f22fff86b281f16">getForDest</a> (const MemIntrinsic *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a location representing the destination of a memory set or transfer. <a href="#ac8f8983c6b76d0e30f22fff86b281f16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95f08c3f32d60b2a352d73be8a055cfe">getForDest</a> (const AtomicMemIntrinsic *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb295e94a75b98f5c8840312a87e7a0d">getForDest</a> (const AnyMemIntrinsic *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4904e476c0d296b50491f629f7de59c3">getForDest</a> (const CallBase *CI, const TargetLibraryInfo &amp;TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc51de08aefeeaabc77fefacc869dbd4">getForArgument</a> (const CallBase *Call, unsigned ArgIdx, const TargetLibraryInfo *TLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a location representing a particular argument of a call. <a href="#afc51de08aefeeaabc77fefacc869dbd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a3ac788aac52795d1127f22f98aa747">getForArgument</a> (const CallBase *Call, unsigned ArgIdx, const TargetLibraryInfo &amp;TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49f776e0940cc5d63d17d85ff6dac257">getAfter</a> (const Value *Ptr, const AAMDNodes &amp;AATags=AAMDNodes())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a location that may access any location after Ptr, while remaining within the underlying object. <a href="#a49f776e0940cc5d63d17d85ff6dac257">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46815b7f69bb96eddd2e1e01bec6120c">getBeforeOrAfter</a> (const Value *Ptr, const AAMDNodes &amp;AATags=AAMDNodes())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a location that may access any location before or after Ptr, while remaining within the underlying object. <a href="#a46815b7f69bb96eddd2e1e01bec6120c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Representation for a specific memory location.</p>


<p>This abstraction can be used to represent a specific location in memory. The goal of the location is to represent enough information to describe abstract aliasing, modification, and reference behaviors of whatever value(s) are stored in memory at the particular location.</p>


<p>The primary user of this interface is LLVM's Alias Analysis, but other memory analyses such as MemoryDependence can use it as well.</p>


<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a031e3abd6e1a18f9462f7cee212ba004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint64_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>UnknownSize - This is a special value which can be used with the size arguments in alias queries to indicate that the caller does not know the sizes of the potential memory references.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnknownSize<a id="a031e3abd6e1a18f9462f7cee212ba004a33f7f25590a5334874e8a114e6f5e55f"></a></td>
<td class="doxyEnumItemDescription"> (= ~UINT64_C(0))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MemoryLocation() {#aa17d3cf450fd3c75aaf0233578d73341}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemoryLocation::MemoryLocation ()</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>References <a href="#a9550ce4a179e46db37f653ce28feca7a">Ptr</a> and <a href="#a39f7ff959874bf38f3e14aa0b2622da0">Size</a>.</p>


<p>Referenced by <a href="#a6c1bd5fd8ec3eeb7320cd9d457b0f164">get</a>, <a href="#a46d61c561714322cb42bd3db9f1609fa">get</a>, <a href="#a61dc6d1a1e9c3cb0adb4c791b329ff31">get</a>, <a href="#a18e5a3f1d71ba10a624f2a8e5121cf1f">get</a>, <a href="#a4037bfe373761aedbe48f3010dbadfed">get</a>, <a href="#a7a7fb118760760e7530c5d6f5be6ce64">get</a>, <a href="#a49f776e0940cc5d63d17d85ff6dac257">getAfter</a>, <a href="#a46815b7f69bb96eddd2e1e01bec6120c">getBeforeOrAfter</a>, <a href="#a1a3ac788aac52795d1127f22f98aa747">getForArgument</a>, <a href="#afc51de08aefeeaabc77fefacc869dbd4">getForArgument</a>, <a href="#acb295e94a75b98f5c8840312a87e7a0d">getForDest</a>, <a href="#a95f08c3f32d60b2a352d73be8a055cfe">getForDest</a>, <a href="#ac8f8983c6b76d0e30f22fff86b281f16">getForDest</a>, <a href="#af438c8da3109f9d2b1530aed2771b88e">getForSource</a>, <a href="#affa4eee9971fefed07074382af167a70">getForSource</a>, <a href="#a207e239d68b66b0d5ccad5997a5ef027">getForSource</a>, <a href="#a81f225396ee3b9587327c8009f9dce40">getWithNewPtr</a>, <a href="#a078f7dbb4fe93a1a5921d82a91f04875">getWithNewSize</a>, <a href="#a0b970d738243dcc4f94c0834ca26b09f">getWithoutAATags</a> and <a href="#acb476100bd92dff58e8d94e4feddac0d">operator==</a>.</p>

</div>
</div>

### MemoryLocation() {#aa6df048912d249abd35e7b75dda080af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemoryLocation::MemoryLocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a> Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> &amp; AATags=<a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a>())</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>References <a href="#a926099ca5ca5db6ba2de398c2487b725">AATags</a>, <a href="#a9550ce4a179e46db37f653ce28feca7a">Ptr</a> and <a href="#a39f7ff959874bf38f3e14aa0b2622da0">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#acb476100bd92dff58e8d94e4feddac0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemoryLocation::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Other)</td>
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



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>References <a href="#a926099ca5ca5db6ba2de398c2487b725">AATags</a>, <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a9550ce4a179e46db37f653ce28feca7a">Ptr</a> and <a href="#a39f7ff959874bf38f3e14aa0b2622da0">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getWithNewPtr() {#a81f225396ee3b9587327c8009f9dce40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation llvm::MemoryLocation::getWithNewPtr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewPtr)</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Reference <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a7b4a95aa47d151f0db62f60bafa792d8">memoryIsNotModifiedBetween</a>.</p>

</div>
</div>

### getWithNewSize() {#a078f7dbb4fe93a1a5921d82a91f04875}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation llvm::MemoryLocation::getWithNewSize (<a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a> NewSize)</td>
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



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Reference <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a>.</p>

</div>
</div>

### getWithoutAATags() {#a0b970d738243dcc4f94c0834ca26b09f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation llvm::MemoryLocation::getWithoutAATags ()</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Reference <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a>.</p>

</div>
</div>

### print() {#a219a6b067df507c97053410136be7d7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MemoryLocation::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>References <a href="#a9550ce4a179e46db37f653ce28feca7a">Ptr</a> and <a href="#a39f7ff959874bf38f3e14aa0b2622da0">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AATags {#a926099ca5ca5db6ba2de398c2487b725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAMDNodes llvm::MemoryLocation::AATags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The metadata nodes which describes the aliasing of the location (each member is null if that kind of information is unavailable).</p>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcarc/objcarcaaresult/#acfba8e1035be99ff311c1af58e624878">llvm::objcarc::ObjCARCAAResult::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaaresult/#a688068ae24921ce2ed14ca5ff0b732e2">llvm::SCEVAAResult::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/scopednoaliasaaresult/#ab972fe828052b5cbeeeb3e9b8cfe0764">llvm::ScopedNoAliasAAResult::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/typebasedaaresult/#ac92480fed6d1bffab7843f41e0a51c20">llvm::TypeBasedAAResult::alias</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/typesanitizer-cpp/#a8fe9c2e5d8a275393677c1c46c5f0596">collectMemAccessInfo</a>, <a href="#a49f776e0940cc5d63d17d85ff6dac257">getAfter</a>, <a href="#a46815b7f69bb96eddd2e1e01bec6120c">getBeforeOrAfter</a>, <a href="#afc51de08aefeeaabc77fefacc869dbd4">getForArgument</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-4f2a5bd91682bf5740574941f9d3c82c/#af947d8fcd9b31cabaaecff33b00611e7">llvm::DenseMapInfo&lt; MemoryLocation &gt;::getHashValue</a>, <a href="#aa6df048912d249abd35e7b75dda080af">MemoryLocation</a>, <a href="#acb476100bd92dff58e8d94e4feddac0d">operator==</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a5737072fd3031fc204134cf904dc36bb">underlyingObjectsAlias</a>.</p>

</div>
</div>

### Ptr {#a9550ce4a179e46db37f653ce28feca7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value* llvm::MemoryLocation::Ptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The address of the start of the location.</p>

<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aaresults/#a12e37baab16d8f80dd44998ea6df7b8d">llvm::AAResults::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuaaresult/#a268b9527fc2ecbb486822e53d18f90ca">llvm::AMDGPUAAResult::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/basicaaresult/#aedf3cfa2d4fc19037cb678766d31d738">llvm::BasicAAResult::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/globalsaaresult/#ad1af2012f83ff1c94df346bbc8ac3b6a">llvm::GlobalsAAResult::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxaaresult/#a3c6e127da93ba9d67d0f1d42a0e9827b">llvm::NVPTXAAResult::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/objcarcaaresult/#acfba8e1035be99ff311c1af58e624878">llvm::objcarc::ObjCARCAAResult::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaaresult/#a688068ae24921ce2ed14ca5ff0b732e2">llvm::SCEVAAResult::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ac27531b926069efa107ab0d977ebbe23">llvm::AAResults::callCapturesBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/typesanitizer-cpp/#a8fe9c2e5d8a275393677c1c46c5f0596">collectMemAccessInfo</a>, <a href="#a49f776e0940cc5d63d17d85ff6dac257">getAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/aliassettracker/#a439aa4acfd3dcd5b1cada30cbecbd189">llvm::AliasSetTracker::getAliasSetFor</a>, <a href="#a46815b7f69bb96eddd2e1e01bec6120c">getBeforeOrAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa5c238ef927795521aeb232b467a6cd1">llvm::MemoryDependenceResults::getDependency</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a0b9027fe8e7ff91d9d6ee565fbdb3db4">anonymous{DeadStoreElimination.cpp}::DSEState::getDomMemoryDef</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-4f2a5bd91682bf5740574941f9d3c82c/#af947d8fcd9b31cabaaecff33b00611e7">llvm::DenseMapInfo&lt; MemoryLocation &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7d8410ca3fc6fb227416067d3c2535d2">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getNonAliasingPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasset/#af36ab8b8b78e18290f43d172c45d24c9">llvm::AliasSet::getPointers</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a870a4918277d840461917023a42f1d57">anonymous{DeadStoreElimination.cpp}::DSEState::isGuaranteedLoopIndependent</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ad2005ee17b5b6cb575257dc12793a077">anonymous{DeadStoreElimination.cpp}::DSEState::isOverwrite</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a5eb76849763054986dcdd4f2f41d369e">anonymous{DeadStoreElimination.cpp}::DSEState::isWriteAtEndOfFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7ae0da674977e2cd46d8df703e7dbab1">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMatrixMultiplyFused</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a7b4a95aa47d151f0db62f60bafa792d8">memoryIsNotModifiedBetween</a>, <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a>, <a href="#aa6df048912d249abd35e7b75dda080af">MemoryLocation</a>, <a href="#acb476100bd92dff58e8d94e4feddac0d">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasset/#a402ffc8c32cbcbcf858f1188ce7a4c87">llvm::AliasSet::print</a>, <a href="#a219a6b067df507c97053410136be7d7a">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a5737072fd3031fc204134cf904dc36bb">underlyingObjectsAlias</a>.</p>

</div>
</div>

### Size {#a39f7ff959874bf38f3e14aa0b2622da0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationSize llvm::MemoryLocation::Size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum size of the location, in address-units, or UnknownSize if the size is not known.</p>


<p>Note that an unknown size does not mean the pointer aliases the entire virtual address space, because there are restrictions on stepping out of one object and into another. See <a href="http://llvm.org/docs/LangRef.html#pointeraliasing">http://llvm.org/docs/LangRef.html#pointeraliasing</a></p>


<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aaresults/#a12e37baab16d8f80dd44998ea6df7b8d">llvm::AAResults::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/basicaaresult/#aedf3cfa2d4fc19037cb678766d31d738">llvm::BasicAAResult::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/objcarcaaresult/#acfba8e1035be99ff311c1af58e624878">llvm::objcarc::ObjCARCAAResult::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaaresult/#a688068ae24921ce2ed14ca5ff0b732e2">llvm::SCEVAAResult::alias</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#ac33670a87c023e6ae45daf3df0a4cd1e">canSkipClobberingStore</a>, <a href="#afc51de08aefeeaabc77fefacc869dbd4">getForArgument</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-4f2a5bd91682bf5740574941f9d3c82c/#af947d8fcd9b31cabaaecff33b00611e7">llvm::DenseMapInfo&lt; MemoryLocation &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7d8410ca3fc6fb227416067d3c2535d2">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getNonAliasingPointer</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ad2005ee17b5b6cb575257dc12793a077">anonymous{DeadStoreElimination.cpp}::DSEState::isOverwrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#aa46849ad227581d0105b7c41b4f9377f">isPartialOverwrite</a>, <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a>, <a href="#aa6df048912d249abd35e7b75dda080af">MemoryLocation</a>, <a href="#acb476100bd92dff58e8d94e4feddac0d">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasset/#a402ffc8c32cbcbcf858f1188ce7a4c87">llvm::AliasSet::print</a> and <a href="#a219a6b067df507c97053410136be7d7a">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#a18e5a3f1d71ba10a624f2a8e5121cf1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation MemoryLocation::get (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI)</td>
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

<p>Return a location with information about the memory reference by the given instruction.</p>

<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorylocation-cpp">MemoryLocation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#aade703948f2fdabdc65868bdf42d3141">llvm::Instruction::getAAMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af65afd02332c4f21c2fab7d217d6600f">llvm::Instruction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2d1ff28d6923802e165905b8d1766e76">llvm::LoadInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a131715ceeb92fb803a329d6b76d14e0d">llvm::LocationSize::precise</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aliassettracker/#a7f77b833b9cb8cf108202087d9447001">llvm::AliasSetTracker::add</a>, <a href="/web-llvm/docs/api/classes/llvm/aliassettracker/#a11a67620a6c96cb35ee7807c17ef442c">llvm::AliasSetTracker::add</a>, <a href="/web-llvm/docs/api/classes/llvm/aliassettracker/#af43e1f24119500a34bfc48484749bc3a">llvm::AliasSetTracker::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/tailrecursionelimination-cpp/#a60fb2a009661b4da106f7ae49f8df93a">canMoveAboveCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-mergeicmps-cpp-/bcecmpblock/#a851916c7b9610597c4339a0d74f8e449">anonymous{MergeICmps.cpp}::BCECmpBlock::canSinkBCECmpInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a158e2caed73e4b5d2ad70c1b2a0e0cc8">llvm::canSinkOrHoistInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#ac33670a87c023e6ae45daf3df0a4cd1e">canSkipClobberingStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/typesanitizer-cpp/#a8fe9c2e5d8a275393677c1c46c5f0596">collectMemAccessInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a49197b24cced248bed2d2c89c641a6dd">llvm::DependenceInfo::depends</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a2295fc872f9e737d27abeffbc9016fbe">findArgParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a459b627931605e520bf7d14e074af7c1">llvm::FindAvailableLoadedValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5ccb7187d4b25577a595e8bd49d2eb2c">llvm::FindAvailableLoadedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp/#a088f7a420ed4bf2ec2e1119af23ad6b4">findSafeStoreForStoreStrongContraction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a8f64e8576d57bb362e730214c7e6fae9">foldLoadsRecursive</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#a3fd364675c871bdf0a532d46bab77e3d">GetLocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#aae9f536130472bd3fbdd23c3d4486b3b">getLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#a251ca8ed878a4ce566cf9a59dee54a0d">llvm::AAResults::getModRefInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ae1b052f14fb4b833786d84bef32008a8">llvm::AAResults::getModRefInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ad0a575d131b12639efc6aa4668268bf7">llvm::AAResults::getModRefInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#a66075ea2329efd415e768265fd6869e3">llvm::AAResults::getModRefInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#a48361e2f65993ca12c655ce466499839">llvm::AAResults::getModRefInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ad81b0803f4f7a698d53aca1637ca8475">llvm::AAResults::getModRefInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7d8410ca3fc6fb227416067d3c2535d2">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getNonAliasingPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#ab46fb372d99dc0562d09cfdcd041d5ab">llvm::MemoryDependenceResults::getNonLocalPointerDependency</a>, <a href="#af61b31a99c1e58b1760492d2a7a1ba9c">getOrNone</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a110f1f473cbb5a42bf9c82973ac9101c">llvm::DependenceInfo::getSplitIteration</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae78f734e49b5ad94836bf32dda101ec6">llvm::hasPartialIVCondition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af55cf9792d5f9186df02c58b337a1511">llvm::AMDGPU::isClobberedInFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loadstorevectorizer-cpp-/vectorizer/#af0c2e6c32b60d80acb3a91698e4981eb">anonymous{LoadStoreVectorizer.cpp}::Vectorizer::isSafeToMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#a5e126bad06b6fa7c75f524f304deb7b0">isSafeToMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#aa7bf9007b34e2a7a16275b1a7d7e3d63">isUseTriviallyOptimizableToLiveOnEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7ae0da674977e2cd46d8df703e7dbab1">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMatrixMultiplyFused</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a7b4a95aa47d151f0db62f60bafa792d8">memoryIsNotModifiedBetween</a>, <a href="/web-llvm/docs/api/classes/anonymous-memoryssa-cpp-/memorylocorcall/#a39c2f0fc42421509baac673f4561e66d">anonymous{MemorySSA.cpp}::MemoryLocOrCall::MemoryLocOrCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-memoryssa-cpp-/upwardsmemoryquery/#aea0cf8bd5bfb12b0fe0a58ee3df0f183">anonymous{MemorySSA.cpp}::UpwardsMemoryQuery::UpwardsMemoryQuery</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moveautoinit-cpp/#ac1a256d1832d143abe2dd5859bff0a82">writeToAlloca</a>.</p>

</div>
</div>

### get() {#a4037bfe373761aedbe48f3010dbadfed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation MemoryLocation::get (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI)</td>
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



<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorylocation-cpp">MemoryLocation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a131715ceeb92fb803a329d6b76d14e0d">llvm::LocationSize::precise</a>.</p>

</div>
</div>

### get() {#a7a7fb118760760e7530c5d6f5be6ce64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation MemoryLocation::get (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vaarginst">VAArgInst</a> * VI)</td>
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



<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorylocation-cpp">MemoryLocation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/locationsize/#ac01c1aa625e97bf21d27474544c463e5">llvm::LocationSize::afterPointer</a> and <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a>.</p>

</div>
</div>

### get() {#a6c1bd5fd8ec3eeb7320cd9d457b0f164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation MemoryLocation::get (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst">AtomicCmpXchgInst</a> * CXI)</td>
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



<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorylocation-cpp">MemoryLocation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#aade703948f2fdabdc65868bdf42d3141">llvm::Instruction::getAAMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a39126826c171851bae4062b25b48e74e">llvm::AtomicCmpXchgInst::getCompareOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af65afd02332c4f21c2fab7d217d6600f">llvm::Instruction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a6c4b659279dd2c617f262bfd36a5eee3">llvm::AtomicCmpXchgInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a131715ceeb92fb803a329d6b76d14e0d">llvm::LocationSize::precise</a>.</p>

</div>
</div>

### get() {#a46d61c561714322cb42bd3db9f1609fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation MemoryLocation::get (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> * RMWI)</td>
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



<p>Declaration at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorylocation-cpp">MemoryLocation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#aade703948f2fdabdc65868bdf42d3141">llvm::Instruction::getAAMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af65afd02332c4f21c2fab7d217d6600f">llvm::Instruction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a506260aecca4d92e8633628f8d4b83ae">llvm::AtomicRMWInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#ae55438e0a802a1a20d6dcabf71b552ad">llvm::AtomicRMWInst::getValOperand</a>, <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a131715ceeb92fb803a329d6b76d14e0d">llvm::LocationSize::precise</a>.</p>

</div>
</div>

### get() {#a61dc6d1a1e9c3cb0adb4c791b329ff31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation llvm::MemoryLocation::get (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>References <a href="#af61b31a99c1e58b1760492d2a7a1ba9c">getOrNone</a> and <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a>.</p>

</div>
</div>

### getAfter() {#a49f776e0940cc5d63d17d85ff6dac257}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation llvm::MemoryLocation::getAfter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> &amp; AATags=<a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a>())</td>
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

<p>Return a location that may access any location after Ptr, while remaining within the underlying object.</p>

<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>References <a href="#a926099ca5ca5db6ba2de398c2487b725">AATags</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#ac01c1aa625e97bf21d27474544c463e5">llvm::LocationSize::afterPointer</a>, <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a> and <a href="#a9550ce4a179e46db37f653ce28feca7a">Ptr</a>.</p>


<p>Referenced by <a href="#afc51de08aefeeaabc77fefacc869dbd4">getForArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#a3fd364675c871bdf0a532d46bab77e3d">GetLocation</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ad1a51eb63abe756612f5b8765cfe4e2a">anonymous{DeadStoreElimination.cpp}::DSEState::getLocForTerminator</a> and <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>.</p>

</div>
</div>

### getBeforeOrAfter() {#a46815b7f69bb96eddd2e1e01bec6120c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation llvm::MemoryLocation::getBeforeOrAfter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> &amp; AATags=<a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a>())</td>
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

<p>Return a location that may access any location before or after Ptr, while remaining within the underlying object.</p>

<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>References <a href="#a926099ca5ca5db6ba2de398c2487b725">AATags</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a837cf7f4d88580c0adb92afc6a3b08b0">llvm::LocationSize::beforeOrAfterPointer</a>, <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a> and <a href="#a9550ce4a179e46db37f653ce28feca7a">Ptr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a3c51f913ac7ff81eb9d5891e5f77a347">addArgLocs</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#a400e5c12433d0a31f12a3bc19df0cc01">llvm::AAResults::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/objcarcaaresult/#acfba8e1035be99ff311c1af58e624878">llvm::objcarc::ObjCARCAAResult::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ac27531b926069efa107ab0d977ebbe23">llvm::AAResults::callCapturesBefore</a>, <a href="#afc51de08aefeeaabc77fefacc869dbd4">getForArgument</a>, <a href="#a4904e476c0d296b50491f629f7de59c3">getForDest</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae58d526e759487737de52702abf2b7c5">anonymous{DeadStoreElimination.cpp}::DSEState::getInitializesArgMemLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/basicaaresult/#a43a53dbe445a968ef8851f1a257d4d7c">llvm::BasicAAResult::getModRefInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#aaefc6bd2c4e163d9742af701e1af4ba3">llvm::AAResults::getModRefInfoMask</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/objcarcaaresult/#a846e0f39264857f2a44cbab95183b2a6">llvm::objcarc::ObjCARCAAResult::getModRefInfoMask</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#a77cea246c314acc1023a00c449301b49">llvm::AAResults::isNoAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#a0a943c5f98373e76a212ba6b617edd66">llvm::AAResults::pointsToConstantMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults/#ae1cf15d168b6004e6bd3fe53edfc4c48">llvm::BatchAAResults::pointsToConstantMemory</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a5737072fd3031fc204134cf904dc36bb">underlyingObjectsAlias</a>.</p>

</div>
</div>

### getForArgument() {#afc51de08aefeeaabc77fefacc869dbd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation MemoryLocation::getForArgument (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call, unsigned ArgIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI)</td>
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

<p>Return a location representing a particular argument of a call.</p>

<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorylocation-cpp">MemoryLocation.cpp</a>.</p>


<p>References <a href="#a926099ca5ca5db6ba2de398c2487b725">AATags</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#ac01c1aa625e97bf21d27474544c463e5">llvm::LocationSize::afterPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a49f776e0940cc5d63d17d85ff6dac257">getAfter</a>, <a href="#a46815b7f69bb96eddd2e1e01bec6120c">getBeforeOrAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a97cfbbed8869e3582142012a071a9052">llvm::TargetLibraryInfo::getLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a54699e3f128acda6003afc11d3027f6c">llvm::TargetLibraryInfo::has</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a131715ceeb92fb803a329d6b76d14e0d">llvm::LocationSize::precise</a>, <a href="#a39f7ff959874bf38f3e14aa0b2622da0">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/locationsize/#ad7198c4852982f1005eb076b6ab126de">llvm::LocationSize::upperBound</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aliassettracker/#a28c431daa68824e2c7f8721bf495fc25">llvm::AliasSetTracker::add</a>, <a href="#a1a3ac788aac52795d1127f22f98aa747">getForArgument</a>, <a href="#acb295e94a75b98f5c8840312a87e7a0d">getForDest</a>, <a href="#a4904e476c0d296b50491f629f7de59c3">getForDest</a>, <a href="#af438c8da3109f9d2b1530aed2771b88e">getForSource</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#a3fd364675c871bdf0a532d46bab77e3d">GetLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ab55d9da87838f5736581bfcd5b54afa1">llvm::AAResults::getModRefInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ae94615351738e4ace274b61029700da9">llvm::AAResults::getModRefInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a899698594c66589eab9bdca89c843798">isArgUnmodifiedByAllCalls</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a77893cb733d0e730a7ce005b53259e09">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::isSafeToMoveBeforeInBB</a> and <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7ae0da674977e2cd46d8df703e7dbab1">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMatrixMultiplyFused</a>.</p>

</div>
</div>

### getForArgument() {#a1a3ac788aac52795d1127f22f98aa747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation llvm::MemoryLocation::getForArgument (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call, unsigned ArgIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI)</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="#afc51de08aefeeaabc77fefacc869dbd4">getForArgument</a> and <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a>.</p>

</div>
</div>

### getForDest() {#ac8f8983c6b76d0e30f22fff86b281f16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation MemoryLocation::getForDest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memintrinsic">MemIntrinsic</a> * MI)</td>
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

<p>Return a location representing the destination of a memory set or transfer.</p>

<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorylocation-cpp">MemoryLocation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ac8f8983c6b76d0e30f22fff86b281f16">getForDest</a>, <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aliassettracker/#a7183c62524bf8d91b7e41f64f413471a">llvm::AliasSetTracker::add</a>, <a href="/web-llvm/docs/api/classes/llvm/aliassettracker/#ad8b0110e87b923144a45219d5be8f4e4">llvm::AliasSetTracker::add</a>, <a href="#a95f08c3f32d60b2a352d73be8a055cfe">getForDest</a>, <a href="#ac8f8983c6b76d0e30f22fff86b281f16">getForDest</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a7876ddf180b2706ffa008155e3f20c80">anonymous{DeadStoreElimination.cpp}::DSEState::getLocForWrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a9b9d4b530f90e36eede3c575ad1948ee">llvm::AA::isPotentiallyAffectedByBarrier</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#abbd47852a13b73290f4625f20c9018d8">isRemovableWrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a7b4a95aa47d151f0db62f60bafa792d8">memoryIsNotModifiedBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#aca7c31a6dcc095ed3c2831f6876c6dc0">SoleWriteToDeadLocal</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moveautoinit-cpp/#ac1a256d1832d143abe2dd5859bff0a82">writeToAlloca</a>.</p>

</div>
</div>

### getForDest() {#a95f08c3f32d60b2a352d73be8a055cfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation MemoryLocation::getForDest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/atomicmemintrinsic">AtomicMemIntrinsic</a> * MI)</td>
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



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorylocation-cpp">MemoryLocation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ac8f8983c6b76d0e30f22fff86b281f16">getForDest</a>, <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getForDest() {#acb295e94a75b98f5c8840312a87e7a0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation MemoryLocation::getForDest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/anymemintrinsic">AnyMemIntrinsic</a> * MI)</td>
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



<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorylocation-cpp">MemoryLocation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afc51de08aefeeaabc77fefacc869dbd4">getForArgument</a>, <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getForDest() {#a4904e476c0d296b50491f629f7de59c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; MemoryLocation &gt; MemoryLocation::getForDest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI)</td>
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



<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorylocation-cpp">MemoryLocation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#adde2ea00dd2613ee41bfe91908e4e68e">llvm::CallBase::arg_size</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#aade703948f2fdabdc65868bdf42d3141">llvm::Instruction::getAAMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="#a46815b7f69bb96eddd2e1e01bec6120c">getBeforeOrAfter</a>, <a href="#afc51de08aefeeaabc77fefacc869dbd4">getForArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aecc0c27ae96638bc9d8fa4caffa92c31">llvm::CallBase::hasOperandBundles</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#adc6331fb2f51f3f964b8f9494ab6620e">llvm::CallBase::onlyAccessesArgMemory</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a857a8c38e4856efec047cc914c25b692">llvm::CallBase::onlyReadsMemory</a>.</p>

</div>
</div>

### getForSource() {#a207e239d68b66b0d5ccad5997a5ef027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation MemoryLocation::getForSource (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memtransferinst">MemTransferInst</a> * MTI)</td>
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

<p>Return a location representing the source of a memory transfer.</p>

<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorylocation-cpp">MemoryLocation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a207e239d68b66b0d5ccad5997a5ef027">getForSource</a> and <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aliassettracker/#ad8b0110e87b923144a45219d5be8f4e4">llvm::AliasSetTracker::add</a>, <a href="#affa4eee9971fefed07074382af167a70">getForSource</a>, <a href="#a207e239d68b66b0d5ccad5997a5ef027">getForSource</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a9b9d4b530f90e36eede3c575ad1948ee">llvm::AA::isPotentiallyAffectedByBarrier</a>.</p>

</div>
</div>

### getForSource() {#affa4eee9971fefed07074382af167a70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation MemoryLocation::getForSource (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/atomicmemtransferinst">AtomicMemTransferInst</a> * MTI)</td>
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



<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorylocation-cpp">MemoryLocation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a207e239d68b66b0d5ccad5997a5ef027">getForSource</a> and <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a>.</p>

</div>
</div>

### getForSource() {#af438c8da3109f9d2b1530aed2771b88e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation MemoryLocation::getForSource (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/anymemtransferinst">AnyMemTransferInst</a> * MTI)</td>
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



<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorylocation-cpp">MemoryLocation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="#afc51de08aefeeaabc77fefacc869dbd4">getForArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/memtransferbase/#aa3c771310b66362b6a032071f63776bb">llvm::MemTransferBase&lt; BaseCL &gt;::getRawSource</a> and <a href="#aa17d3cf450fd3c75aaf0233578d73341">MemoryLocation</a>.</p>

</div>
</div>

### getOrNone() {#af61b31a99c1e58b1760492d2a7a1ba9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; MemoryLocation &gt; MemoryLocation::getOrNone (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
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



<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorylocation-cpp">MemoryLocation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a18e5a3f1d71ba10a624f2a8e5121cf1f">get</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceableimpl/#a032ee1ab74cd70ec3ff4801ec8a49f0f">anonymous{AttributorAttributes.cpp}::AADereferenceableImpl::addAccessedBytesForUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a8b8a65f41fa956162c7877cb20bc53b9">checkFunctionMemoryAccess</a>, <a href="#a61dc6d1a1e9c3cb0adb4c791b329ff31">get</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a7159508155406ad5c350cc429980e09d">anonymous{AttributorAttributes.cpp}::getKnownNonNullAndDerefBytesForUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a7876ddf180b2706ffa008155e3f20c80">anonymous{DeadStoreElimination.cpp}::DSEState::getLocForWrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#a0ea8063abb874faff99f39c4e849f8de">HasAddressTaken</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a9b9d4b530f90e36eede3c575ad1948ee">llvm::AA::isPotentiallyAffectedByBarrier</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a77893cb733d0e730a7ce005b53259e09">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::isSafeToMoveBeforeInBB</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/utils/#a9f715b1ea015a15c8efb07a459c0156f">llvm::sandboxir::Utils::memoryLocationGetOrNone</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/memorylocation-cpp">MemoryLocation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
