---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/datalayout
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DataLayout` Class Reference

<p>A parsed version of the target data layout string in and methods for querying it. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DataLayout { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FunctionPtrAlignType { <a href="#a3511bd43936be3600192abe2c7c6d60b">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ManglingModeT { <a href="#a9ae184518d5c712d1bb625e1a44a06f3">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62d0fc1e33fe098cd53b43b42f8ba0a7">DataLayout</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> with default values. <a href="#a62d0fc1e33fe098cd53b43b42f8ba0a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa58e5a33f16b7118e3c90200f6b95ec1">DataLayout</a> (StringRef LayoutString)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> from a specification string. <a href="#aa58e5a33f16b7118e3c90200f6b95ec1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5dc6ab45d8fcc4740ba479489f92258">DataLayout</a> (const DataLayout &amp;DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac13b453a42da1c775de5e0f59013ce13">~DataLayout</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97c0181592cc39a0dc73798d77e5c792">operator=</a> (const DataLayout &amp;Other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea9de7a750555a28e96aea146f50d1b1">operator==</a> (const DataLayout &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad55e43014aa5ae58013f541e36a6d2cd">operator!=</a> (const DataLayout &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a377365b0288a4d06a07e09252d7d583f">isLittleEndian</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Layout endianness... <a href="#a377365b0288a4d06a07e09252d7d583f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84c1d72001dd5f34d9a55b3a7bb8a474">isBigEndian</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed3f806fa9a500c28b0803a98554a15e">getStringRepresentation</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the string representation of the <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a>. <a href="#aed3f806fa9a500c28b0803a98554a15e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37e51b287c7a168b4ee35e4854dcf299">isDefault</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> was constructed from an empty string. <a href="#a37e51b287c7a168b4ee35e4854dcf299">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4865a13a415f04576388b969d04d1541">isLegalInteger</a> (uint64_t Width) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified type is known to be a native integer type supported by the CPU. <a href="#a4865a13a415f04576388b969d04d1541">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81a4738213c5f31e79fd9da78ddbe639">isIllegalInteger</a> (uint64_t Width) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9234a42689bb875b36a3025337edaa8a">getStackAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the natural stack alignment, or MaybeAlign() if one wasn't specified. <a href="#a9234a42689bb875b36a3025337edaa8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9748c769cedc926c41cd95183fd7abd4">getAllocaAddrSpace</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82e740747e70f962da8e6d26a2a86379">getAllocaPtrType</a> (LLVMContext &amp;Ctx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc4eb074a816c840ede3ea3165113d7c">getFunctionPtrAlign</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the alignment of function pointers, which may or may not be related to the alignment of functions. <a href="#acc4eb074a816c840ede3ea3165113d7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3511bd43936be3600192abe2c7c6d60b">FunctionPtrAlignType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b91e7036cfb63d0f699ce8135470b7b">getFunctionPtrAlignType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type of function pointer alignment. <a href="#a4b91e7036cfb63d0f699ce8135470b7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04a2830ac857f68f2bc97f98dfff56dd">getProgramAddressSpace</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a154f698c40d2c0bd67467d4ced1078">getDefaultGlobalsAddressSpace</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe30b15c32f1aff16a43437e75bd0ae9">hasMicrosoftFastStdCallMangling</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56dc8e3d9602fad141bd40813a83677c">doNotMangleLeadingQuestionMark</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if symbols with leading question marks should not receive IR mangling. <a href="#a56dc8e3d9602fad141bd40813a83677c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c2a0ec8ebfcedb3aa960c900457951b">hasLinkerPrivateGlobalPrefix</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fc97424ec0ade058e858f210a6926cc">getLinkerPrivateGlobalPrefix</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae975263a27169538b780c240568e4dfc">getGlobalPrefix</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc048bb502c5a099e2f474d0d8b09698">getPrivateGlobalPrefix</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc91ed2b3f1ffe91542a865a86308b5a">fitsInLegalInteger</a> (unsigned Width) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified type fits in a native integer type supported by the CPU. <a href="#abc91ed2b3f1ffe91542a865a86308b5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af46786371f2d40a54174ac9c9abfd12f">getPointerABIAlignment</a> (unsigned AS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Layout pointer alignment. <a href="#af46786371f2d40a54174ac9c9abfd12f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5a0d7488565e459f1c8422aa5ff9529">getPointerPrefAlignment</a> (unsigned AS=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return target's alignment for stack-based pointers FIXME: The defaults need to be removed once all of the backends/clients are updated. <a href="#ac5a0d7488565e459f1c8422aa5ff9529">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4d8e60ce9a5b62049e6b71f19a24c8b">getPointerSize</a> (unsigned AS=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Layout pointer size in bytes, rounded up to a whole number of bytes. <a href="#ac4d8e60ce9a5b62049e6b71f19a24c8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a592830354856514461dbda7834005d1f">getIndexSize</a> (unsigned AS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>rounded up to a whole number of bytes. <a href="#a592830354856514461dbda7834005d1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd1e9e3a6538d09c27c2984bb63097f9">getNonIntegralAddressSpaces</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the address spaces containing non-integral pointers. <a href="#afd1e9e3a6538d09c27c2984bb63097f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80f295107105ef76efd7022b579cc8e0">isNonIntegralAddressSpace</a> (unsigned AddrSpace) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac51c315bfb66e68f32b03862fe849658">isNonIntegralPointerType</a> (PointerType *PT) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a332bf5be9b33af553358d858e15e2443">isNonIntegralPointerType</a> (Type *Ty) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21ae5af9c62928bb06c66379017bdda1">getPointerSizeInBits</a> (unsigned AS=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Layout pointer size, in bits FIXME: The defaults need to be removed once all of the backends/clients are updated. <a href="#a21ae5af9c62928bb06c66379017bdda1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9e61b1a68b91217d3d10a61a1f0fbb9">getIndexSizeInBits</a> (unsigned AS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size in bits of index used for address calculation in getelementptr. <a href="#ac9e61b1a68b91217d3d10a61a1f0fbb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83f29b41d37a5b66cd48c3b4ec302742">getPointerTypeSizeInBits</a> (Type *) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Layout pointer size, in bits, based on the type. <a href="#a83f29b41d37a5b66cd48c3b4ec302742">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a822fce84743a12eba6f9c83c9c719140">getIndexTypeSizeInBits</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Layout size of the index used in GEP calculation. <a href="#a822fce84743a12eba6f9c83c9c719140">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d97ad8b9dacc077360276f028f6d770">getPointerTypeSize</a> (Type *Ty) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf0b1898efd7f81a078e9288befd9290">getTypeSizeInBits</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size examples: <a href="#acf0b1898efd7f81a078e9288befd9290">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfcd22eb38dbfe1acbf138754297437a">getTypeStoreSize</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the maximum number of bytes that may be overwritten by storing the specified type. <a href="#acfcd22eb38dbfe1acbf138754297437a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b229a84730d00c5e9ed36784521d304">getTypeStoreSizeInBits</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the maximum number of bits that may be overwritten by storing the specified type; always a multiple of 8. <a href="#a3b229a84730d00c5e9ed36784521d304">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04cbf0d1549609eeea73a0c8904b2dbf">typeSizeEqualsStoreSize</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if no extra padding bits are needed when storing the specified type. <a href="#a04cbf0d1549609eeea73a0c8904b2dbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa48b3b7e554b44f4e513d5dd8d9f9343">getTypeAllocSize</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the offset in bytes between successive objects of the specified type, including alignment padding. <a href="#aa48b3b7e554b44f4e513d5dd8d9f9343">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6df5869f0f8df9fd045efe5533e6280">getTypeAllocSizeInBits</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the offset in bits between successive objects of the specified type, including alignment padding; always a multiple of 8. <a href="#ad6df5869f0f8df9fd045efe5533e6280">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a800e74bec9b78d6739665027c3616a55">getABITypeAlign</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the minimum ABI-required alignment for the specified type. <a href="#a800e74bec9b78d6739665027c3616a55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee73eda928cc4fe04f8f68b760d784f4">getValueOrABITypeAlignment</a> (MaybeAlign Alignment, Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to return <span class="doxyComputerOutput">Alignment</span> if it's set or the result of <span class="doxyComputerOutput">getABITypeAlign(Ty)</span>, in any case the result is a valid alignment. <a href="#aee73eda928cc4fe04f8f68b760d784f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ed9cb07b066ca1f510e65f375aca091">getABIIntegerTypeAlignment</a> (unsigned BitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the minimum ABI-required alignment for an integer type of the specified bitwidth. <a href="#a4ed9cb07b066ca1f510e65f375aca091">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9185c7e96873c6d2c13e1f1b6322cf6">getPrefTypeAlign</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the preferred stack/global alignment for the specified type. <a href="#af9185c7e96873c6d2c13e1f1b6322cf6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a2619d0e489a4ba9c19a0d86a041d59">getIntPtrType</a> (LLVMContext &amp;C, unsigned AddressSpace=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an integer type with size at least as big as that of a pointer in the given address space. <a href="#a7a2619d0e489a4ba9c19a0d86a041d59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb1aa8811da861ad795a3125a9e5ce7">getIntPtrType</a> (Type *) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an integer (vector of integer) type with size at least as big as that of a pointer of the given pointer (vector of pointer) type. <a href="#a8bb1aa8811da861ad795a3125a9e5ce7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab478aed986ac4bf6d92e603694af9b2b">getSmallestLegalIntType</a> (LLVMContext &amp;C, unsigned Width=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the smallest integer type with size at least as big as Width bits. <a href="#ab478aed986ac4bf6d92e603694af9b2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbc0ce9726d9e887c396c3d483e09899">getLargestLegalIntType</a> (LLVMContext &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the largest legal integer type, or null if none are set. <a href="#acbc0ce9726d9e887c396c3d483e09899">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4630e3ad6236a8af9c439c364631c15b">getLargestLegalIntTypeSizeInBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size of largest legal integer type size, or 0 if none are set. <a href="#a4630e3ad6236a8af9c439c364631c15b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98477b82eae8654fb3e711d95ea127ec">getIndexType</a> (LLVMContext &amp;C, unsigned AddressSpace) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the type of a GEP index in <a href="/web-llvm/docs/api/namespaces/llvm/nvptxas/#ad7d00b71af84502be65ae2de3f8d91dc">AddressSpace</a>. <a href="#a98477b82eae8654fb3e711d95ea127ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbd9ed911d1d58b73f9571f300cc6a7b">getIndexType</a> (Type *PtrTy) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the type of a GEP index. <a href="#abbd9ed911d1d58b73f9571f300cc6a7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec8bb28502320250bf2d4a55ab99e242">getIndexedOffsetInType</a> (Type *ElemTy, ArrayRef&lt; Value * &gt; Indices) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the offset from the beginning of the type for the specified indices. <a href="#aec8bb28502320250bf2d4a55ab99e242">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36523fbc60bf720df4d9f20cfae7bb7f">getGEPIndicesForOffset</a> (Type *&amp;ElemTy, APInt &amp;Offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get GEP indices to access Offset inside ElemTy. <a href="#a36523fbc60bf720df4d9f20cfae7bb7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3c9ad31690c1a9b440d3ad2d73563af">getGEPIndexForOffset</a> (Type *&amp;ElemTy, APInt &amp;Offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get single GEP index to access Offset inside ElemTy. <a href="#ab3c9ad31690c1a9b440d3ad2d73563af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/structlayout">StructLayout</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61135fb8666f0b7a37b4e1bbcf1db131">getStructLayout</a> (StructType *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a <a href="/web-llvm/docs/api/classes/llvm/structlayout">StructLayout</a> object, indicating the alignment of the struct, its size, and the offsets of its fields. <a href="#a61135fb8666f0b7a37b4e1bbcf1db131">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc7937248226859bf5a5d64a28c8269f">getPreferredAlign</a> (const GlobalVariable *GV) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the preferred alignment of the specified global. <a href="#abc7937248226859bf5a5d64a28c8269f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4432ca31829b03859ff0ca8611e67d0">setPrimitiveSpec</a> (char Specifier, uint32_t BitWidth, Align ABIAlign, Align PrefAlign)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets or updates the specification for the given primitive type. <a href="#ab4432ca31829b03859ff0ca8611e67d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/datalayout/pointerspec">PointerSpec</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5826e4080ea7596df0e03e8201be1d3a">getPointerSpec</a> (uint32_t AddrSpace) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Searches for a pointer specification that matches the given address space. <a href="#a5826e4080ea7596df0e03e8201be1d3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0936401a6a5835ecae5961508e6cdaa9">setPointerSpec</a> (uint32_t AddrSpace, uint32_t BitWidth, Align ABIAlign, Align PrefAlign, uint32_t IndexBitWidth, bool IsNonIntegral)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets or updates the specification for pointer in the given address space. <a href="#a0936401a6a5835ecae5961508e6cdaa9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55d3bf873a1c0f95cbb6c14c032f09a9">getIntegerAlignment</a> (uint32_t BitWidth, bool abi_or_pref) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Internal helper to get alignment for integer of given bitwidth. <a href="#a55d3bf873a1c0f95cbb6c14c032f09a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35da6c4fc6116de265102d411a7679e2">getAlignment</a> (Type *Ty, bool abi_or_pref) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Internal helper method that returns requested alignment for type. <a href="#a35da6c4fc6116de265102d411a7679e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29df5fe749c579a52a890c8161980b9a">parsePrimitiveSpec</a> (StringRef Spec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempts to parse primitive specification ('i', 'f', or 'v'). <a href="#a29df5fe749c579a52a890c8161980b9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b673b9f5344df1a905dcbf06a4cef46">parseAggregateSpec</a> (StringRef Spec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempts to parse aggregate specification ('a'). <a href="#a5b673b9f5344df1a905dcbf06a4cef46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05403b806a28cfc3a2604bc467bb841e">parsePointerSpec</a> (StringRef Spec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempts to parse pointer specification ('p'). <a href="#a05403b806a28cfc3a2604bc467bb841e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86e6a16168d311f571df3dcf328ffab9">parseSpecification</a> (StringRef Spec, SmallVectorImpl&lt; unsigned &gt; &amp;NonIntegralAddressSpaces)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempts to parse a single specification. <a href="#a86e6a16168d311f571df3dcf328ffab9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a474e8b0aadd3e10eeaac6db773ee09fe">parseLayoutString</a> (StringRef LayoutString)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempts to parse a data layout string. <a href="#a474e8b0aadd3e10eeaac6db773ee09fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b05817294495072fc089f68fcbec99f">BigEndian</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b0265b59aaaa3a3b8106f4d3a2b8379">AllocaAddrSpace</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bb5bbb9bd821683020c98e42fec3a16">ProgramAddrSpace</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b9b66e2d95d26b68865176bcbb345bd">DefaultGlobalsAddrSpace</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8711178a0b70f1f5150bf85c45d94d52">StackNaturalAlign</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62c9d25c45a43c88c3ee0095411274d6">FunctionPtrAlign</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3511bd43936be3600192abe2c7c6d60b">FunctionPtrAlignType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ffad0273690ed743ba0f2fab3f57cf1">TheFunctionPtrAlignType</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ManglingModeT</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad909fd9a557bd61bf5daaee3bda67c9a">ManglingMode</a> = MM_None</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned char, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acae649d9ce0277f2eaf4f67f1d15305c">LegalIntWidths</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/datalayout/primitivespec">PrimitiveSpec</a>, 6 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf87bb4143189f3a554c6aaff93889a8">IntSpecs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Primitive type specifications. Sorted and uniqued by type bit width. <a href="#adf87bb4143189f3a554c6aaff93889a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/datalayout/primitivespec">PrimitiveSpec</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83483a68ebfd65981b0f9295cfc47376">FloatSpecs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/datalayout/primitivespec">PrimitiveSpec</a>, 10 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1d3a1274422320ed444799a32209a03">VectorSpecs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/datalayout/pointerspec">PointerSpec</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33e24c4e0f971e033b1ff6b933e4c6be">PointerSpecs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer type specifications. Sorted and uniqued by address space number. <a href="#a33e24c4e0f971e033b1ff6b933e4c6be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb3bbe5f7ec1eb464733625518ab37c3">StringRepresentation</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The string representation used to create this <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a>. <a href="#abb3bbe5f7ec1eb464733625518ab37c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ef151b462f9f6a035224464d521721e">StructABIAlignment</a> = <a href="/web-llvm/docs/api/structs/llvm/align/#ac7699332a966bc646e928f780142c43a">Align::Constant</a>&lt;1&gt;()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Struct type ABI and preferred alignments. The default spec is "a:8:64". <a href="#a7ef151b462f9f6a035224464d521721e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63f075dc21c3df15d3bfd3adaaffedba">StructPrefAlignment</a> = <a href="/web-llvm/docs/api/structs/llvm/align/#ac7699332a966bc646e928f780142c43a">Align::Constant</a>&lt;8&gt;()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3456b2de1e769d7513d42780754b514">LayoutMap</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9e5099e50182fb0c8dcfb57c476bd2c">parse</a> (StringRef LayoutString)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a data layout string and return the layout. <a href="#af9e5099e50182fb0c8dcfb57c476bd2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c5b48c01700ee5c1d1a6df0fec2c72e">getManglingComponent</a> (const Triple &amp;T)</td>
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

<p>A parsed version of the target data layout string in and methods for querying it.</p>


<p>The target data layout string is specified <em>by the target</em> - a frontend generating LLVM IR is required to generate the right target data for the target being codegen'd to.</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### FunctionPtrAlignType {#a3511bd43936be3600192abe2c7c6d60b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::DataLayout::FunctionPtrAlignType </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Independent<a id="a3511bd43936be3600192abe2c7c6d60bae9e003c325eec6946ed1d23c6ac90a21"></a></td>
<td class="doxyEnumItemDescription">The function pointer alignment is independent of the function alignment</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MultipleOfFunctionAlign<a id="a3511bd43936be3600192abe2c7c6d60ba03dba8dbe49f426cf24da0d597e99b70"></a></td>
<td class="doxyEnumItemDescription">The function pointer alignment is a multiple of the function alignment</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### ManglingModeT {#a9ae184518d5c712d1bb625e1a44a06f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::DataLayout::ManglingModeT </td>
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
<td class="doxyEnumItemName">MM_None<a id="a9ae184518d5c712d1bb625e1a44a06f3a5da436798ebd44e0dee4f5191bb5b872"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MM_ELF<a id="a9ae184518d5c712d1bb625e1a44a06f3ad9a8df4b472ebbc2f084b02bfbf42346"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MM_MachO<a id="a9ae184518d5c712d1bb625e1a44a06f3abd26715b55e9859637d26d16b5545b26"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MM_WinCOFF<a id="a9ae184518d5c712d1bb625e1a44a06f3acd42733785edc5d0abca2298625663f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MM_WinCOFFX86<a id="a9ae184518d5c712d1bb625e1a44a06f3ab76bc1498844f329d3b72216b878e8b2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MM_GOFF<a id="a9ae184518d5c712d1bb625e1a44a06f3ab4906e104dbe833b9e44c7c3f4e5a42b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MM_Mips<a id="a9ae184518d5c712d1bb625e1a44a06f3a30d8db68b8318c77e81361377ca400b0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MM_XCOFF<a id="a9ae184518d5c712d1bb625e1a44a06f3a697cfc75b9418bd6c5cff772ee07f6c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DataLayout() {#a62d0fc1e33fe098cd53b43b42f8ba0a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataLayout::DataLayout ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constructs a <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> with default values.</p>

<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp/#a608eb64104e2fd979127cd0311a9a183">DefaultFloatSpecs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp/#ae5b235899641897e1ab41d5e50337020">DefaultIntSpecs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp/#a8e85737a58dc8436d6990110466f5b5f">DefaultPointerSpecs</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp/#a86c777135c0e97b201c0ff7f297661d5">DefaultVectorSpecs</a>.</p>


<p>Referenced by <a href="#ad5dc6ab45d8fcc4740ba479489f92258">DataLayout</a>, <a href="#aa58e5a33f16b7118e3c90200f6b95ec1">DataLayout</a>, <a href="#ad55e43014aa5ae58013f541e36a6d2cd">operator!=</a>, <a href="#a97c0181592cc39a0dc73798d77e5c792">operator=</a>, <a href="#aea9de7a750555a28e96aea146f50d1b1">operator==</a> and <a href="#af9e5099e50182fb0c8dcfb57c476bd2c">parse</a>.</p>

</div>
</div>

### DataLayout() {#aa58e5a33f16b7118e3c90200f6b95ec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataLayout::DataLayout (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LayoutString)</td>
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

<p>Constructs a <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> from a specification string.</p>


<p>WARNING: Aborts execution if the string is malformed. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <a href="#af9e5099e50182fb0c8dcfb57c476bd2c">parse()</a> instead.</p>


<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="#a62d0fc1e33fe098cd53b43b42f8ba0a7">DataLayout</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### DataLayout() {#ad5dc6ab45d8fcc4740ba479489f92258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DataLayout::DataLayout (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>References <a href="#a62d0fc1e33fe098cd53b43b42f8ba0a7">DataLayout</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DataLayout() {#ac13b453a42da1c775de5e0f59013ce13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataLayout::~DataLayout ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 707 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#ad55e43014aa5ae58013f541e36a6d2cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataLayout::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; Other)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>References <a href="#a62d0fc1e33fe098cd53b43b42f8ba0a7">DataLayout</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator=() {#a97c0181592cc39a0dc73798d77e5c792}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataLayout &amp; DataLayout::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="#a62d0fc1e33fe098cd53b43b42f8ba0a7">DataLayout</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator==() {#aea9de7a750555a28e96aea146f50d1b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DataLayout::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="#a62d0fc1e33fe098cd53b43b42f8ba0a7">DataLayout</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### doNotMangleLeadingQuestionMark() {#a56dc8e3d9602fad141bd40813a83677c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataLayout::doNotMangleLeadingQuestionMark ()</td>
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

<p>Returns true if symbols with leading question marks should not receive IR mangling.</p>


<p>True for Windows mangling modes.</p>


<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### fitsInLegalInteger() {#abc91ed2b3f1ffe91542a865a86308b5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataLayout::fitsInLegalInteger (unsigned Width)</td>
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

<p>Returns true if the specified type fits in a native integer type supported by the CPU.</p>


<p>For example, if the CPU only supports i32 as a native integer type, then i27 fits in a legal integer type but i45 does not.</p>


<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### getABIIntegerTypeAlignment() {#a4ed9cb07b066ca1f510e65f375aca091}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::DataLayout::getABIIntegerTypeAlignment (unsigned BitWidth)</td>
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

<p>Returns the minimum ABI-required alignment for an integer type of the specified bitwidth.</p>

<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#ab0097819d1d3f4c8eca96c9d9ac4fa0d">llvm::MachineJumpTableInfo::getEntryAlignment</a>.</p>

</div>
</div>

### getABITypeAlign() {#a800e74bec9b78d6739665027c3616a55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align DataLayout::getABITypeAlign (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the minimum ABI-required alignment for the specified type.</p>

<p>Declaration at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 843 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a8423e53bcc9782e23a4e48e8ef88d150">llvm::analyzeArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a22c327ddfcb98f911f3197180981f41e">llvm::SelectionDAG::getConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a467226658bbb3854ea3e1f625a73a128">llvm::SelectionDAG::getEVTAlign</a>, <a href="#abc7937248226859bf5a5d64a28c8269f">getPreferredAlign</a>, <a href="#aa48b3b7e554b44f4e513d5dd8d9f9343">getTypeAllocSize</a>, <a href="#aee73eda928cc4fe04f8f68b760d784f4">getValueOrABITypeAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a697277613cca131c099969ca5d421041">llvm::SITargetLowering::ReplaceNodeResults</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a>.</p>

</div>
</div>

### getAllocaAddrSpace() {#a9748c769cedc926c41cd95183fd7abd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DataLayout::getAllocaAddrSpace ()</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#aa5f0f4a7de5def1c9d9f6a750a9b1aa1">llvm::MachinePointerInfo::getUnknownStack</a> and <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>.</p>

</div>
</div>

### getAllocaPtrType() {#a82e740747e70f962da8e6d26a2a86379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType * llvm::DataLayout::getAllocaPtrType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx)</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>.</p>

</div>
</div>

### getDefaultGlobalsAddressSpace() {#a4a154f698c40d2c0bd67467d4ced1078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DataLayout::getDefaultGlobalsAddressSpace ()</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### getFunctionPtrAlign() {#acc4eb074a816c840ede3ea3165113d7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign llvm::DataLayout::getFunctionPtrAlign ()</td>
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

<p>Returns the alignment of function pointers, which may or may not be related to the alignment of functions.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a4b91e7036cfb63d0f699ce8135470b7b">getFunctionPtrAlignType</a></p></dd>
</dl>


<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### getFunctionPtrAlignType() {#a4b91e7036cfb63d0f699ce8135470b7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPtrAlignType llvm::DataLayout::getFunctionPtrAlignType ()</td>
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

<p>Return the type of function pointer alignment.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#acc4eb074a816c840ede3ea3165113d7c">getFunctionPtrAlign</a></p></dd>
</dl>


<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### getGEPIndexForOffset() {#ab3c9ad31690c1a9b440d3ad2d73563af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; APInt &gt; DataLayout::getGEPIndexForOffset (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *&amp; ElemTy, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get single GEP index to access Offset inside ElemTy.</p>


<p>Returns std::nullopt if index cannot be computed, e.g. because the type is not an aggregate. ElemTy is updated to be the result element type and Offset to be the residual offset.</p>


<p>Declaration at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 941 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a331caeb70809f50e71528de06fba7b66">llvm::StructLayout::getElementContainingOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp/#a0626211048d3157a84aac054ba7e894a">getElementIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a3932cc53acb297750961bfdaa86425bc">llvm::StructLayout::getElementOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a0b6603d0838e3b40bf5c0a403c0510f2">llvm::StructLayout::getSizeInBytes</a>, <a href="#a61135fb8666f0b7a37b4e1bbcf1db131">getStructLayout</a>, <a href="#aa48b3b7e554b44f4e513d5dd8d9f9343">getTypeAllocSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a36523fbc60bf720df4d9f20cfae7bb7f">getGEPIndicesForOffset</a>.</p>

</div>
</div>

### getGEPIndicesForOffset() {#a36523fbc60bf720df4d9f20cfae7bb7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; APInt &gt; DataLayout::getGEPIndicesForOffset (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *&amp; ElemTy, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get GEP indices to access Offset inside ElemTy.</p>


<p>ElemTy is updated to be the result element type and Offset to be the residual offset.</p>


<p>Declaration at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 971 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp/#a0626211048d3157a84aac054ba7e894a">getElementIndex</a>, <a href="#ab3c9ad31690c1a9b440d3ad2d73563af">getGEPIndexForOffset</a>, <a href="#aa48b3b7e554b44f4e513d5dd8d9f9343">getTypeAllocSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### getGlobalPrefix() {#ae975263a27169538b780c240568e4dfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::DataLayout::getGlobalPrefix ()</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac4b27e8ffe711b0dcbc16b19671d5edc">llvm::emitLinkerFlagsForGlobalCOFF</a>.</p>

</div>
</div>

### getIndexedOffsetInType() {#aec8bb28502320250bf2d4a55ab99e242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t DataLayout::getIndexedOffsetInType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElemTy, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Indices)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the offset from the beginning of the type for the specified indices.</p>


<p>Note that this takes the element type, not the pointer type. This is used to implement getelementptr.</p>


<p>Declaration at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 893 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac828b9b52935f87659a4adf237f820a3">llvm::gep_type_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a43c6ebb4fd35ebd815d66a2df4eed0b9">llvm::gep_type_end</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a3932cc53acb297750961bfdaa86425bc">llvm::StructLayout::getElementOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/generic-gep-type-iterator/#aede343190362b8c6d9e85dcfb5853ba2">llvm::generic_gep_type_iterator&lt; ItTy &gt;::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/generic-gep-type-iterator/#ae3d47d990ab77e9659cc0fc35c9353de">llvm::generic_gep_type_iterator&lt; ItTy &gt;::getSequentialElementStride</a>, <a href="#a61135fb8666f0b7a37b4e1bbcf1db131">getStructLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/generic-gep-type-iterator/#a5a2edfe3b8475d07b1088799fd2df172">llvm::generic_gep_type_iterator&lt; ItTy &gt;::getStructTypeOrNull</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>.</p>

</div>
</div>

### getIndexSize() {#a592830354856514461dbda7834005d1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DataLayout::getIndexSize (unsigned AS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>rounded up to a whole number of bytes.</p>

<p>Declaration at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 750 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>.</p>

</div>
</div>

### getIndexSizeInBits() {#ac9e61b1a68b91217d3d10a61a1f0fbb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DataLayout::getIndexSizeInBits (unsigned AS)</td>
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

<p>Size in bits of index used for address calculation in getelementptr.</p>

<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>Referenced by <a href="#a98477b82eae8654fb3e711d95ea127ec">getIndexType</a>, <a href="#a822fce84743a12eba6f9c83c9c719140">getIndexTypeSizeInBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a>.</p>

</div>
</div>

### getIndexType() {#a98477b82eae8654fb3e711d95ea127ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType * DataLayout::getIndexType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned AddressSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the type of a GEP index in <a href="/web-llvm/docs/api/namespaces/llvm/nvptxas/#ad7d00b71af84502be65ae2de3f8d91dc">AddressSpace</a>.</p>


<p>If it was not specified explicitly, it will be the integer type of the pointer width - IntPtrType.</p>


<p>Declaration at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 878 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a> and <a href="#ac9e61b1a68b91217d3d10a61a1f0fbb9">getIndexSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a6dcfa69ce27cf214caaf50f21bfe1f2f">llvm::ScalarEvolution::getEffectiveSCEVType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a25ea6e038ccdef52ab01b0ee3da9ee52">simplifyAllocaArraySize</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#abfcd971ce6ccafa5489dd3bf313219af">simplifyCastInst</a>.</p>

</div>
</div>

### getIndexType() {#abbd9ed911d1d58b73f9571f300cc6a7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * DataLayout::getIndexType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * PtrTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the type of a GEP index.</p>


<p>If it was not specified explicitly, it will be the integer type of the pointer width - IntPtrType.</p>


<p>Declaration at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 883 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a> and <a href="#a822fce84743a12eba6f9c83c9c719140">getIndexTypeSizeInBits</a>.</p>

</div>
</div>

### getIndexTypeSizeInBits() {#a822fce84743a12eba6f9c83c9c719140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DataLayout::getIndexTypeSizeInBits (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Layout size of the index used in GEP calculation.</p>


<p>The function should be called with pointer or vector of pointers type.</p>


<p>Declaration at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 754 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp/#af6ab6e89a7e272521d7641859805a0ba">getAddressSpace</a> and <a href="#ac9e61b1a68b91217d3d10a61a1f0fbb9">getIndexSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="#abbd9ed911d1d58b73f9571f300cc6a7b">getIndexType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a2c96114e89e8cf2122ebe8bc4d929c7c">llvm::ScalarEvolution::getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a8133ee4dcc7f8903e9b582593c09bf28">isNonEqualPointersWithRecursiveGEP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a99fa28f2d78ae2ce889b621ab275a4ad">llvm::simplifyLoadInst</a>.</p>

</div>
</div>

### getIntPtrType() {#a7a2619d0e489a4ba9c19a0d86a041d59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType * DataLayout::getIntPtrType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned AddressSpace=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an integer type with size at least as big as that of a pointer in the given address space.</p>

<p>Declaration at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 851 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a> and <a href="#a21ae5af9c62928bb06c66379017bdda1">getPointerSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo/#a3ef56098772bca9a4ca38bf149aa872c">llvm::ARMSelectionDAGInfo::EmitSpecializedLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64selectiondaginfo/#a4f4d5344fa41e237eb9a60c7b62975b8">llvm::AArch64SelectionDAGInfo::EmitStreamingCompatibleMemLibCall</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonselectiondaginfo/#a10a0dbb2ae8f208929d1f453d84cb101">llvm::HexagonSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreselectiondaginfo/#af87dbf9e0c8190963043ea6154532c25">llvm::XCoreSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c9c5b337e855fb0ce25e53c0bd3f992">llvm::SelectionDAG::getAtomicMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abe645b6f7de2918e594b110f3c819b07">llvm::SelectionDAG::getAtomicMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c60b6ae234b668266d9f21b0e1b8f89">llvm::SelectionDAG::getAtomicMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a4bab447a6422427e5fc92bbbc0c12fba">llvm::ScalarEvolution::getLosslessPtrToIntExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4590e453df8847d8d5eda7e37ae9dffa">llvm::SelectionDAG::getMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac3f766fb181e521628094d9a9e461606">llvm::SelectionDAG::getMemmove</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#abfcd971ce6ccafa5489dd3bf313219af">simplifyCastInst</a>.</p>

</div>
</div>

### getIntPtrType() {#a8bb1aa8811da861ad795a3125a9e5ce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * DataLayout::getIntPtrType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an integer (vector of integer) type with size at least as big as that of a pointer of the given pointer (vector of pointer) type.</p>

<p>Declaration at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 856 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a> and <a href="#a83f29b41d37a5b66cd48c3b4ec302742">getPointerTypeSizeInBits</a>.</p>

</div>
</div>

### getLargestLegalIntType() {#acbc0ce9726d9e887c396c3d483e09899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::DataLayout::getLargestLegalIntType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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

<p>Returns the largest legal integer type, or null if none are set.</p>

<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a> and <a href="#a4630e3ad6236a8af9c439c364631c15b">getLargestLegalIntTypeSizeInBits</a>.</p>

</div>
</div>

### getLargestLegalIntTypeSizeInBits() {#a4630e3ad6236a8af9c439c364631c15b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DataLayout::getLargestLegalIntTypeSizeInBits ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the size of largest legal integer type size, or 0 if none are set.</p>

<p>Declaration at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 873 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab4e6de707bff0fe8081c4da0711bba07">llvm::max_element</a>.</p>


<p>Referenced by <a href="#acbc0ce9726d9e887c396c3d483e09899">getLargestLegalIntType</a>.</p>

</div>
</div>

### getLinkerPrivateGlobalPrefix() {#a1fc97424ec0ade058e858f210a6926cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DataLayout::getLinkerPrivateGlobalPrefix ()</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### getNonIntegralAddressSpaces() {#afd1e9e3a6538d09c27c2984bb63097f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; unsigned, 8 &gt; llvm::DataLayout::getNonIntegralAddressSpaces ()</td>
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

<p>Return the address spaces containing non-integral pointers.</p>


<p>Pointers in this address space don't have a well-defined bitwise representation.</p>


<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### getPointerABIAlignment() {#af46786371f2d40a54174ac9c9abfd12f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align DataLayout::getPointerABIAlignment (unsigned AS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Layout pointer alignment.</p>

<p>Declaration at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#ab0097819d1d3f4c8eca96c9d9ac4fa0d">llvm::MachineJumpTableInfo::getEntryAlignment</a>.</p>

</div>
</div>

### getPointerPrefAlignment() {#ac5a0d7488565e459f1c8422aa5ff9529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align DataLayout::getPointerPrefAlignment (unsigned AS=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return target's alignment for stack-based pointers FIXME: The defaults need to be removed once all of the backends/clients are updated.</p>

<p>Declaration at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 735 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>

</div>
</div>

### getPointerSize() {#ac4d8e60ce9a5b62049e6b71f19a24c8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DataLayout::getPointerSize (unsigned AS=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Layout pointer size in bytes, rounded up to a whole number of bytes.</p>


<p>FIXME: The defaults need to be removed once all of the backends/clients are updated.</p>


<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a1592f31751bef2ac04349cb6be511d18">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#adde89997aabb6eb4532d8882f311a631">llvm::LoongArchAsmPrinter::emitJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#a4d6ef9167ddc2ae5fdf29a41cbaa5202">llvm::MachineJumpTableInfo::getEntrySize</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp/#a3ad6b5d121ac7d090c7670c699ac3b93">isTargetNullPtr</a> and <a href="/web-llvm/docs/api/classes/anonymous-executionengine-cpp-/argvarray/#a3b5f64c809ca91e2a09b5b97d80e23a7">anonymous{ExecutionEngine.cpp}::ArgvArray::reset</a>.</p>

</div>
</div>

### getPointerSizeInBits() {#a21ae5af9c62928bb06c66379017bdda1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DataLayout::getPointerSizeInBits (unsigned AS=0)</td>
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

<p>Layout pointer size, in bits FIXME: The defaults need to be removed once all of the backends/clients are updated.</p>

<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>Referenced by <a href="#a7a2619d0e489a4ba9c19a0d86a041d59">getIntPtrType</a>, <a href="#a83f29b41d37a5b66cd48c3b4ec302742">getPointerTypeSizeInBits</a>, <a href="#acf0b1898efd7f81a078e9288befd9290">getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a>.</p>

</div>
</div>

### getPointerTypeSize() {#a7d97ad8b9dacc077360276f028f6d770}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DataLayout::getPointerTypeSize (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>Reference <a href="#a83f29b41d37a5b66cd48c3b4ec302742">getPointerTypeSizeInBits</a>.</p>

</div>
</div>

### getPointerTypeSizeInBits() {#a83f29b41d37a5b66cd48c3b4ec302742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DataLayout::getPointerTypeSizeInBits (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Layout pointer size, in bits, based on the type.</p>


<p>If this function is called with a pointer type, then the type size of the pointer is returned. If this function is called with a vector of pointers, then the type size of the pointer is returned. This should only be called with a pointer or vector of pointers.</p>


<p>Declaration at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp/#af6ab6e89a7e272521d7641859805a0ba">getAddressSpace</a> and <a href="#a21ae5af9c62928bb06c66379017bdda1">getPointerSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a903bd19e9d31beff55b22fe86111639e">computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7ee632093c5fc25ca22faa353105aa74">llvm::SelectionDAG::getGlobalAddress</a>, <a href="#a8bb1aa8811da861ad795a3125a9e5ce7">getIntPtrType</a>, <a href="#a7d97ad8b9dacc077360276f028f6d770">getPointerTypeSize</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8d72d0dbb6d5ab8b970a32519122d85c">llvm::SelectionDAG::InferPtrAlign</a>.</p>

</div>
</div>

### getPreferredAlign() {#abc7937248226859bf5a5d64a28c8269f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align DataLayout::getPreferredAlign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the preferred alignment of the specified global.</p>


<p>getPreferredAlign - Return the preferred alignment of the specified global.</p>


<p>This includes an explicitly requested alignment (if the global has one).</p>


<p>Declaration at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 988 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="#a800e74bec9b78d6739665027c3616a55">getABITypeAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a115ac0121663aa8365e095d095d0c633">llvm::GlobalObject::getAlign</a>, <a href="#af9185c7e96873c6d2c13e1f1b6322cf6">getPrefTypeAlign</a>, <a href="#acf0b1898efd7f81a078e9288befd9290">getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a1c66d4eff947253e7610a66379974d63">llvm::GlobalVariable::hasInitializer</a> and <a href="/web-llvm/docs/api/classes/llvm/globalobject/#ade7dc7510e950cd1c1181138b390f965">llvm::GlobalObject::hasSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-executionengine-cpp-/gvmemoryblock/#a2cbb49e0b488e91387da02f0396405f7">anonymous{ExecutionEngine.cpp}::GVMemoryBlock::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#a667ed45ec1fd0b5557d48ac537ddad2d">getAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#ade886f9a8ca0106ed64320647cbc1646">getELFSectionNameForGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac6767d87d6d42330fa8e29e15bb105b1">promoteToConstantPool</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>.</p>

</div>
</div>

### getPrefTypeAlign() {#af9185c7e96873c6d2c13e1f1b6322cf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align DataLayout::getPrefTypeAlign (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the preferred stack/global alignment for the specified type.</p>


<p>This is always at least as good as the ABI alignment.</p>


<p>Declaration at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 847 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a274a99ee4eac8fbc5e112f80cd84c71e">llvm::PPCInstrInfo::finalizeInsInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a22c327ddfcb98f911f3197180981f41e">llvm::SelectionDAG::getConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0c98ec1a456fb81eed1d51d987b156d1">llvm::SelectionDAG::getConstantPool</a>, <a href="#abc7937248226859bf5a5d64a28c8269f">getPreferredAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a531405bfbd93bc7c3464eea0d9144774">getPrefTypeAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a531405bfbd93bc7c3464eea0d9144774">getPrefTypeAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a1d84356309e55a4722a2739dd3c655e4">ReplaceLoadVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a>.</p>

</div>
</div>

### getPrivateGlobalPrefix() {#acc048bb502c5a099e2f474d0d8b09698}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DataLayout::getPrivateGlobalPrefix ()</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a66ebd2ccd2ea699bd04b40dd95c2fee4">llvm::TargetLoweringObjectFileMachO::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a866133bf888d0b8bbce2275845511edb">llvm::TargetLoweringObjectFile::getSymbolWithGlobalValueBase</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ad7367f761921fa5792918525c5082bac">llvm::MipsAsmPrinter::printOperand</a>.</p>

</div>
</div>

### getProgramAddressSpace() {#a04a2830ac857f68f2bc97f98dfff56dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DataLayout::getProgramAddressSpace ()</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### getSmallestLegalIntType() {#ab478aed986ac4bf6d92e603694af9b2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * DataLayout::getSmallestLegalIntType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned Width=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the smallest integer type with size at least as big as Width bits.</p>

<p>Declaration at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 866 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>.</p>

</div>
</div>

### getStackAlignment() {#a9234a42689bb875b36a3025337edaa8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign llvm::DataLayout::getStackAlignment ()</td>
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

<p>Returns the natural stack alignment, or MaybeAlign() if one wasn't specified.</p>

<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### getStringRepresentation() {#aed3f806fa9a500c28b0803a98554a15e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::DataLayout::getStringRepresentation ()</td>
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

<p>Returns the string representation of the <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a>.</p>


<p>This representation is in the same format accepted by the string constructor above. This should not be used to compare two <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> as different string can represent the same layout.</p>


<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### getStructLayout() {#a61135fb8666f0b7a37b4e1bbcf1db131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StructLayout * DataLayout::getStructLayout (<a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a <a href="/web-llvm/docs/api/classes/llvm/structlayout">StructLayout</a> object, indicating the alignment of the struct, its size, and the offsets of its fields.</p>


<p>Note that this information is lazily cached.</p>


<p>Declaration at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8bb931812d78f470d4ca775ac8b88e61">llvm::safe_malloc</a> and <a href="/web-llvm/docs/api/classes/llvm/trailingobjects/#a5b733cf2a7d7206c2d2601cc5b024488">llvm::TrailingObjects&lt; StructLayout, TypeSize &gt;::totalSizeToAlloc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="#ab3c9ad31690c1a9b440d3ad2d73563af">getGEPIndexForOffset</a>, <a href="#aec8bb28502320250bf2d4a55ab99e242">getIndexedOffsetInType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a60be12dda0289837dae43964608cf568">llvm::ScalarEvolution::getOffsetOfExpr</a>, <a href="#acf0b1898efd7f81a078e9288befd9290">getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a38079cd1d3c8bc5f3aef1d3420c3b855">llvm::ExecutionEngine::InitializeMemory</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ab9ee1d3249435d1130a87d064d13857d">isGEPKnownNonNull</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a>.</p>

</div>
</div>

### getTypeAllocSize() {#aa48b3b7e554b44f4e513d5dd8d9f9343}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize llvm::DataLayout::getTypeAllocSize (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Returns the offset in bytes between successive objects of the specified type, including alignment padding.</p>


<p>If Ty is a scalable vector type, the scalable property will be set and the runtime size will be a positive integer multiple of the base size.</p>


<p>This is the amount that alloca reserves for this type. For example, returns 12 or 16 for x86_fp80, depending on alignment.</p>


<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="#a800e74bec9b78d6739665027c3616a55">getABITypeAlign</a> and <a href="#acfcd22eb38dbfe1acbf138754297437a">getTypeStoreSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a8423e53bcc9782e23a4e48e8ef88d150">llvm::analyzeArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-executionengine-cpp-/gvmemoryblock/#a2cbb49e0b488e91387da02f0396405f7">anonymous{ExecutionEngine.cpp}::GVMemoryBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#ab98a836a506bb90245c243f8e4da3162">llvm::ExecutionEngine::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a96970d69b7b91b65fe1dec76d42fcea0">llvm::CSKYAsmPrinter::emitMachineConstantPoolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzasmprinter/#a1580a63379a12004a4da0dfd70744768">llvm::SystemZAsmPrinter::emitMachineConstantPoolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a6fb486939378ca836b98249408abcedf">llvm::ARMAsmPrinter::emitXXStructor</a>, <a href="#ab3c9ad31690c1a9b440d3ad2d73563af">getGEPIndexForOffset</a>, <a href="#a36523fbc60bf720df4d9f20cfae7bb7f">getGEPIndicesForOffset</a>, <a href="#ad6df5869f0f8df9fd045efe5533e6280">getTypeAllocSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a38079cd1d3c8bc5f3aef1d3420c3b855">llvm::ExecutionEngine::InitializeMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#aab3a49dcff02cbc78628deef02c53296">llvm::HexagonTargetObjectFile::isGlobalInSmallSection</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#a2adf1ff4e0a2e37ff5c9ebb3c68ea93e">llvm::RISCVELFTargetObjectFile::isGlobalInSmallSection</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aa7fcaa7855f4688864e1315a38ab3694">llvm::X86TargetLowering::markLibCallAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a40c243011cdda005e97448378d575096">performGlobalAddressCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac6767d87d6d42330fa8e29e15bb105b1">promoteToConstantPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a1ce4069e58167789a23552d4cab66114">llvm::Interpreter::visitAllocaInst</a> and <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a036be8b00358d56b7923f330715301ee">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitReturnInst</a>.</p>

</div>
</div>

### getTypeAllocSizeInBits() {#ad6df5869f0f8df9fd045efe5533e6280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize llvm::DataLayout::getTypeAllocSizeInBits (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Returns the offset in bits between successive objects of the specified type, including alignment padding; always a multiple of 8.</p>


<p>If Ty is a scalable vector type, the scalable property will be set and the runtime size will be a positive integer multiple of the base size.</p>


<p>This is the amount that alloca reserves for this type. For example, returns 96 or 128 for x86_fp80, depending on alignment.</p>


<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>Reference <a href="#aa48b3b7e554b44f4e513d5dd8d9f9343">getTypeAllocSize</a>.</p>


<p>Referenced by <a href="#acf0b1898efd7f81a078e9288befd9290">getTypeSizeInBits</a>.</p>

</div>
</div>

### getTypeSizeInBits() {#acf0b1898efd7f81a078e9288befd9290}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize llvm::DataLayout::getTypeSizeInBits (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Size examples:</p>


<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> SizeInBits StoreSizeInBits AllocSizeInBits[*]</p>


<hr/>


<p>i1 1 8 8 i8 8 8 8 i19 19 24 32 i32 32 32 32 i100 100 104 128 i128 128 128 128 Float 32 32 32 Double 64 64 64 X86_FP80 80 80 96</p>


<p>[*] The alloc size depends on the alignment, and thus on the target. These values are for x86-32 linux. Returns the number of bits necessary to hold the specified type.</p>


<p>If Ty is a scalable vector type, the scalable property will be set and the runtime size will be a positive integer multiple of the base size.</p>


<p>For example, returns 36 for i36 and 80 for x86_fp80. The type passed must have a size (<a href="/web-llvm/docs/api/classes/llvm/type/#a8ad67a33bae235fe3cca1c3e5a91ed2d">Type::isSized()</a> must return true).</p>


<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa2989d3024a84b4dda9d77419b1648554">llvm::Type::ArrayTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaaa889d8e26c8078095629a42d1f930fa7">llvm::Type::BFloatTyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa98aa825426dd4de2d19a3de9983a2d5d">llvm::Type::FixedVectorTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaaf645dbe1647a41fce26595aa8cd8bdfc">llvm::Type::FP128TyID</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a59632c5deb0423a518ad984bdd04d41f">llvm::VectorType::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#aed75da684d36221f1f7b9fbf5aa3aed8">llvm::ArrayType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a1c35bd7a4fa08845607033aecc94423d">llvm::ArrayType::getNumElements</a>, <a href="#a21ae5af9c62928bb06c66379017bdda1">getPointerSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a7ca2273f2f77565f65ba98039c69b3a8">llvm::StructLayout::getSizeInBits</a>, <a href="#a61135fb8666f0b7a37b4e1bbcf1db131">getStructLayout</a>, <a href="#ad6df5869f0f8df9fd045efe5533e6280">getTypeAllocSizeInBits</a>, <a href="#acf0b1898efd7f81a078e9288befd9290">getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa301c3a4cc2bfd399628cfd473f383ff9">llvm::Type::HalfTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa66db5616b8f6b2cfe991861905747783">llvm::Type::LabelTyID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaae68df805bc15b023748c2a78b80563ff">llvm::Type::PointerTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaac1fd0acf788a4de492dc0e3f51088f48">llvm::Type::PPC_FP128TyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6188e4e2fb839d904debf0cbe7fc11f6">llvm::Type::ScalableVectorTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa812a573d23fbb37aacd025e2a0588156">llvm::Type::StructTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa44ac2c71ce3db287c4e73aca9ad04e44">llvm::Type::TargetExtTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa0abcabf751e05ec079d5907fc0733c65">llvm::Type::X86_AMXTyID</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabd37be4e521c37c8b5c07edbab59b8d7">llvm::Type::X86_FP80TyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a903bd19e9d31beff55b22fe86111639e">computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aa730d6c2ddb52a05e3602c501e961629">computeKnownBitsForHorizontalOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="#abc7937248226859bf5a5d64a28c8269f">getPreferredAlign</a>, <a href="#acf0b1898efd7f81a078e9288befd9290">getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a2c96114e89e8cf2122ebe8bc4d929c7c">llvm::ScalarEvolution::getTypeSizeInBits</a>, <a href="#a3b229a84730d00c5e9ed36784521d304">getTypeStoreSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aae1a4eb9b437e719a333c79f74c9a1b2">simplifyAMDGCNMemoryIntrinsicDemanded</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#afc576f8a8ddd42537a82e1cedc179ae1">tocDataChecks</a> and <a href="#a04cbf0d1549609eeea73a0c8904b2dbf">typeSizeEqualsStoreSize</a>.</p>

</div>
</div>

### getTypeStoreSize() {#acfcd22eb38dbfe1acbf138754297437a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize llvm::DataLayout::getTypeStoreSize (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Returns the maximum number of bytes that may be overwritten by storing the specified type.</p>


<p>If Ty is a scalable vector type, the scalable property will be set and the runtime size will be a positive integer multiple of the base size.</p>


<p>For example, returns 5 for i36 and 10 for x86_fp80.</p>


<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a3b229a84730d00c5e9ed36784521d304">getTypeStoreSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a65edce9c8505e3d3b9c0d90794458288">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addAccessedPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a388d5a62753f4e7ff4b72e54c1233fbc">llvm::OpenMPIRBuilder::createAtomicRead</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#af8918ba9c2bab47454cfbe9bb8942871">emitGlobalConstantLargeInt</a>, <a href="#aa48b3b7e554b44f4e513d5dd8d9f9343">getTypeAllocSize</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#adec0e730f80de19f31127faedf39008c">llvm::ExecutionEngine::LoadValueFromMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a08ed33d3b3f8b9e21167918d5de40014">llvm::ExecutionEngine::StoreValueToMemory</a>.</p>

</div>
</div>

### getTypeStoreSizeInBits() {#a3b229a84730d00c5e9ed36784521d304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize llvm::DataLayout::getTypeStoreSizeInBits (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Returns the maximum number of bits that may be overwritten by storing the specified type; always a multiple of 8.</p>


<p>If Ty is a scalable vector type, the scalable property will be set and the runtime size will be a positive integer multiple of the base size.</p>


<p>For example, returns 40 for i36 and 80 for x86_fp80.</p>


<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7f24ae5aca75f26072ec2665cd5f24d3">llvm::alignToPowerOf2</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#acf0b1898efd7f81a078e9288befd9290">getTypeSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>.</p>


<p>Referenced by <a href="#acfcd22eb38dbfe1acbf138754297437a">getTypeStoreSize</a> and <a href="#a04cbf0d1549609eeea73a0c8904b2dbf">typeSizeEqualsStoreSize</a>.</p>

</div>
</div>

### getValueOrABITypeAlignment() {#aee73eda928cc4fe04f8f68b760d784f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::DataLayout::getValueOrABITypeAlignment (<a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> Alignment, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Helper function to return <span class="doxyComputerOutput">Alignment</span> if it's set or the result of <span class="doxyComputerOutput">getABITypeAlign(Ty)</span>, in any case the result is a valid alignment.</p>

<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>Reference <a href="#a800e74bec9b78d6739665027c3616a55">getABITypeAlign</a>.</p>

</div>
</div>

### hasLinkerPrivateGlobalPrefix() {#a1c2a0ec8ebfcedb3aa960c900457951b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataLayout::hasLinkerPrivateGlobalPrefix ()</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### hasMicrosoftFastStdCallMangling() {#abe30b15c32f1aff16a43437e75bd0ae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataLayout::hasMicrosoftFastStdCallMangling ()</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### isBigEndian() {#a84c1d72001dd5f34d9a55b3a7bb8a474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataLayout::isBigEndian ()</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7ed44f2251a99b3c609481e114ae9295">llvm::DwarfExpression::addConstantFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6a1c71b7d20e3cf09cc8ff5a8efdb34f">canCombineShuffleToExtendVectorInreg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6da34b4a62e36f7b3b51720f19d3e753">combineShuffleToAnyExtendVectorInreg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac52d67d57787e5d9c93fadbe593ada02">combineShuffleToZeroExtendVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#af01458f5f68de9153c5392eebedfa0f1">combineTruncationShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aca815d84ffc0bd9719d54ef89a51e8e4">createGPRPairNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a48539398b37da233dca24ff79af3fb9f">createGPRPairNodei64</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a42aed3ce098f4ba8b69e50e87e8146f6">emitGlobalConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a93533d35a661d5dc48a03c624839b8e4">llvm::RISCVInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aa1c33c4fbbe149ca5deb130bca410ef2">foldVecExtTruncToExtElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aee3e98b16f1c8d8d8b30b9a459a6a602">foldVecTruncToExtElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#acb8cf9e50c3979193572ea36f327d0a4">getCopyFromParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a8910923e28ba24c5abedb60c66c86cc5">getCopyToParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aed112aa93992e59dc1fdcbb38700ec14">getPPCf128HiElementSelector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6c49319d93381e455f0138e221896629">isExtendedBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa32a8c1fba431700b7564e94ea5ab4d2">LowerPredicateLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aedabf4c69af716c22c9957d6ca5758e1">LowerPredicateStore</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a070e7ae88917971c8b99b3bb7f3d5942">llvm::CombinerHelper::matchLoadOrCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aa435f2b01aca963d926bd31cd95e7f03">matchPERM</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a528e38dffd58ba9e81a7a05fb7d44c11">narrowExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a8f948dd0c375dfeb4cdf99bc33905e66">optimizeIntegerToVectorInsertions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a75e6b6bf03adf614aaf100a9afdcd612">optimizeVectorResizeWithIntegerBitCasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a51359c8ddfa214a514dbaab1b2ad2d29">PerformBITCASTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aba237afe216b870806584d3e96e575b4">PerformTruncatingStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa98ade29969ff63557a3a9594f95891a">PerformVMOVRRDCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94825933fbeecbda802a1c22c46a524d">llvm::AArch64TargetLowering::ReconstructShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a2c166ebb81953ce2aa531c18213e0011">reduceBuildVecToShuffleWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae416c990e5945aed7ccfb70d4c7a5802">ReplaceATOMIC_LOAD_128Results</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a32739f322e03782811f33bc367f9bc3b">ReplaceCMP_SWAP_128Results</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a9edb7bbdf708d2f51e1cab727a105fdc">ReplaceCMP_SWAP_64Results</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6d8b5e9460092c4517e5e594756fcb82">llvm::LegalizerHelper::scalarizeVectorBooleanStore</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8556cfd59caa7077d224c55f2b1d9767">SkipExtensionForVMULL</a>.</p>

</div>
</div>

### isDefault() {#a37e51b287c7a168b4ee35e4854dcf299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataLayout::isDefault ()</td>
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

<p>Test if the <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> was constructed from an empty string.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a3b63142ca24145028afa3a5bdf3fe7fb">llvm::ExecutionEngine::getMangledName</a>.</p>

</div>
</div>

### isIllegalInteger() {#a81a4738213c5f31e79fd9da78ddbe639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataLayout::isIllegalInteger (uint64_t Width)</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>Reference <a href="#a4865a13a415f04576388b969d04d1541">isLegalInteger</a>.</p>

</div>
</div>

### isLegalInteger() {#a4865a13a415f04576388b969d04d1541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataLayout::isLegalInteger (uint64_t Width)</td>
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

<p>Returns true if the specified type is known to be a native integer type supported by the CPU.</p>


<p>For example, i64 is not native on most 32-bit CPUs and i37 is not native on any known one. This returns false if the integer width is not legal.</p>


<p>The width is specified in bits.</p>


<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>


<p>Referenced by <a href="#a81a4738213c5f31e79fd9da78ddbe639">isIllegalInteger</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a57aff0646c7151c4158d839c386332cc">visitIVCast</a>.</p>

</div>
</div>

### isLittleEndian() {#a377365b0288a4d06a07e09252d7d583f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataLayout::isLittleEndian ()</td>
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

<p>Layout endianness...</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a1a0cd3e4178d08fadb03d4e4e9404dcd">addShuffleForVecExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a2107ac6ce763ed1ad3e60ba0e473139b">llvm::SparcTargetLowering::bitcastConstantFPToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af31a972f3279158ab9801b78f1f92e1f">combineBVOfVecSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a2e8d18b52d32049f8c9ed560d20341b8">getMemsetStringVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a93d85169d871f169e06ab00673048741">llvm::PPC::getSplatIdxForPPCMnemonics</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a5cf58df95b00905950bdfee515cd5e9d">llvm::TargetInstrInfo::getStackSlotRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a5abe83e8c9d9553cfc708a024c204807">llvm::PPC::isVMRGEOShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a3f48ceee4d4e7b13efb21c415b8fc330">llvm::PPC::isVMRGHShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#ab27448838ea5635fa836a68c3aa97b29">llvm::PPC::isVMRGLShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a43b885afb337e155a5f9e5257081de8b">llvm::PPC::isVPKUDUMShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aee91c58b3a130d49788e05c85b12dce4">llvm::PPC::isVPKUHUMShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#ae9f806005e684e4cbd25d76849ee1775">llvm::PPC::isVPKUWUMShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa45ea0323da7012ed4e0f58aef3619bb">llvm::PPC::isVSLDOIShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a92ccbac77b3b6657074fa5d279beb523">LowerF64Op</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#adf6a42cc1a9f660d92f18fdb7004fa1e">LowerFNEGorFABS</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a405578f0decf5610edec9f350a54e81f">llvm::SparcTargetLowering::LowerFormalArguments_32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#adb9776e3c9f8cf35e243fe5585cdafd3">LowerSTORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8bdc70b2f7ce13fccad6913d54322dcf">performUzpCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a347a0b15c11be2a5567e53730e0fb1b2">ShrinkLoadReplaceStoreWithStore</a>.</p>

</div>
</div>

### isNonIntegralAddressSpace() {#a80f295107105ef76efd7022b579cc8e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataLayout::isNonIntegralAddressSpace (unsigned AddrSpace)</td>
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



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>Referenced by <a href="#ac51c315bfb66e68f32b03862fe849658">isNonIntegralPointerType</a>.</p>

</div>
</div>

### isNonIntegralPointerType() {#ac51c315bfb66e68f32b03862fe849658}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataLayout::isNonIntegralPointerType (<a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> * PT)</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8aeced5e71d2589fa3e9791043af5cb">llvm::PointerType::getAddressSpace</a> and <a href="#a80f295107105ef76efd7022b579cc8e0">isNonIntegralAddressSpace</a>.</p>


<p>Referenced by <a href="#a332bf5be9b33af553358d858e15e2443">isNonIntegralPointerType</a>.</p>

</div>
</div>

### isNonIntegralPointerType() {#a332bf5be9b33af553358d858e15e2443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataLayout::isNonIntegralPointerType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#ac51c315bfb66e68f32b03862fe849658">isNonIntegralPointerType</a>.</p>

</div>
</div>

### typeSizeEqualsStoreSize() {#a04cbf0d1549609eeea73a0c8904b2dbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataLayout::typeSizeEqualsStoreSize (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Returns true if no extra padding bits are needed when storing the specified type.</p>


<p>For example, returns false for i19 that has a 24-bit store size.</p>


<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>


<p>References <a href="#acf0b1898efd7f81a078e9288befd9290">getTypeSizeInBits</a> and <a href="#a3b229a84730d00c5e9ed36784521d304">getTypeStoreSizeInBits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getAlignment() {#a35da6c4fc6116de265102d411a7679e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align DataLayout::getAlignment (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, bool abi_or_pref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Internal helper method that returns requested alignment for type.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">abi_or_pref</td>
<td class="doxyParamItemDescription"><p>Flag that determines which alignment is returned. true returns the ABI alignment, false returns the preferred alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>The underlying type for which alignment is determined.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Get the ABI (<em>abi_or_pref</em> == true) or preferred alignment (<em>abi_or_pref</em> == false) for the requested type <em>Ty</em>.</p>


<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 769 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>

</div>
</div>

### getIntegerAlignment() {#a55d3bf873a1c0f95cbb6c14c032f09a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align DataLayout::getIntegerAlignment (uint32_t BitWidth, bool abi_or_pref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Internal helper to get alignment for integer of given bitwidth.</p>

<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>

</div>
</div>

### getPointerSpec() {#a5826e4080ea7596df0e03e8201be1d3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout::PointerSpec &amp; DataLayout::getPointerSpec (uint32_t AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Searches for a pointer specification that matches the given address space.</p>


<p>Returns the default address space specification if not found.</p>


<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>

</div>
</div>

### parseAggregateSpec() {#a5b673b9f5344df1a905dcbf06a4cef46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DataLayout::parseAggregateSpec (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Spec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempts to parse aggregate specification ('a').</p>

<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>

</div>
</div>

### parseLayoutString() {#a474e8b0aadd3e10eeaac6db773ee09fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DataLayout::parseLayoutString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LayoutString)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempts to parse a data layout string.</p>

<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>

</div>
</div>

### parsePointerSpec() {#a05403b806a28cfc3a2604bc467bb841e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DataLayout::parsePointerSpec (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Spec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempts to parse pointer specification ('p').</p>

<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>

</div>
</div>

### parsePrimitiveSpec() {#a29df5fe749c579a52a890c8161980b9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DataLayout::parsePrimitiveSpec (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Spec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempts to parse primitive specification ('i', 'f', or 'v').</p>

<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>

</div>
</div>

### parseSpecification() {#a86e6a16168d311f571df3dcf328ffab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DataLayout::parseSpecification (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Spec, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; NonIntegralAddressSpaces)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempts to parse a single specification.</p>

<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>

</div>
</div>

### setPointerSpec() {#a0936401a6a5835ecae5961508e6cdaa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DataLayout::setPointerSpec (uint32_t AddrSpace, uint32_t BitWidth, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ABIAlign, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> PrefAlign, uint32_t IndexBitWidth, bool IsNonIntegral)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets or updates the specification for pointer in the given address space.</p>

<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>

</div>
</div>

### setPrimitiveSpec() {#ab4432ca31829b03859ff0ca8611e67d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DataLayout::setPrimitiveSpec (char Specifier, uint32_t BitWidth, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ABIAlign, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> PrefAlign)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets or updates the specification for the given primitive type.</p>

<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllocaAddrSpace {#a4b0265b59aaaa3a3b8106f4d3a2b8379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DataLayout::AllocaAddrSpace = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### BigEndian {#a1b05817294495072fc089f68fcbec99f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataLayout::BigEndian = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### DefaultGlobalsAddrSpace {#a3b9b66e2d95d26b68865176bcbb345bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DataLayout::DefaultGlobalsAddrSpace = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### FloatSpecs {#a83483a68ebfd65981b0f9295cfc47376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;PrimitiveSpec, 4&gt; llvm::DataLayout::FloatSpecs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### FunctionPtrAlign {#a62c9d25c45a43c88c3ee0095411274d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign llvm::DataLayout::FunctionPtrAlign</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### IntSpecs {#adf87bb4143189f3a554c6aaff93889a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;PrimitiveSpec, 6&gt; llvm::DataLayout::IntSpecs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Primitive type specifications. Sorted and uniqued by type bit width.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### LayoutMap {#ae3456b2de1e769d7513d42780754b514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::DataLayout::LayoutMap = nullptr</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### LegalIntWidths {#acae649d9ce0277f2eaf4f67f1d15305c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned char, 8&gt; llvm::DataLayout::LegalIntWidths</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### ManglingMode {#ad909fd9a557bd61bf5daaee3bda67c9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ManglingModeT llvm::DataLayout::ManglingMode = MM_None</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### PointerSpecs {#a33e24c4e0f971e033b1ff6b933e4c6be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;PointerSpec, 8&gt; llvm::DataLayout::PointerSpecs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer type specifications. Sorted and uniqued by address space number.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### ProgramAddrSpace {#a2bb5bbb9bd821683020c98e42fec3a16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DataLayout::ProgramAddrSpace = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### StackNaturalAlign {#a8711178a0b70f1f5150bf85c45d94d52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign llvm::DataLayout::StackNaturalAlign</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### StringRepresentation {#abb3bbe5f7ec1eb464733625518ab37c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DataLayout::StringRepresentation</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The string representation used to create this <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a>.</p>

<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### StructABIAlignment {#a7ef151b462f9f6a035224464d521721e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::DataLayout::StructABIAlignment = <a href="/web-llvm/docs/api/structs/llvm/align/#ac7699332a966bc646e928f780142c43a">Align::Constant</a>&lt;1&gt;()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Struct type ABI and preferred alignments. The default spec is "a:8:64".</p>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### StructPrefAlignment {#a63f075dc21c3df15d3bfd3adaaffedba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::DataLayout::StructPrefAlignment = <a href="/web-llvm/docs/api/structs/llvm/align/#ac7699332a966bc646e928f780142c43a">Align::Constant</a>&lt;8&gt;()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### TheFunctionPtrAlignType {#a0ffad0273690ed743ba0f2fab3f57cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPtrAlignType llvm::DataLayout::TheFunctionPtrAlignType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      <a href="#a3511bd43936be3600192abe2c7c6d60bae9e003c325eec6946ed1d23c6ac90a21">FunctionPtrAlignType::Independent</a>
</div>
</dd>
</dl>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

### VectorSpecs {#ab1d3a1274422320ed444799a32209a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;PrimitiveSpec, 10&gt; llvm::DataLayout::VectorSpecs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getManglingComponent() {#a1c5b48c01700ee5c1d1a6df0fec2c72e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * DataLayout::getManglingComponent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
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



<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetmachine-cpp/#aefdbcd6131ef195da070cef7fdaf0532">computeDataLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp/#aefdbcd6131ef195da070cef7fdaf0532">computeDataLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp/#adb29b487708f0dc2a940345b68649270">computeDataLayout</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetmachine-cpp/#aafa20a40f66280a3a22ecddfe821e5c0">getDataLayoutString</a>.</p>

</div>
</div>

### parse() {#af9e5099e50182fb0c8dcfb57c476bd2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DataLayout &gt; DataLayout::parse (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LayoutString)</td>
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

<p>Parse a data layout string and return the layout.</p>


<p>Return an error description on failure.</p>


<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a>, definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>Reference <a href="#a62d0fc1e33fe098cd53b43b42f8ba0a7">DataLayout</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6d9c43797976f73bdbe0c75995f84865">llvm::SPIRVTranslate</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">DataLayout.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
