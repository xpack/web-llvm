---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `BuildLibCalls.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/buildlibcalls-h">llvm/Transforms/Utils/BuildLibCalls.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">llvm/Analysis/MemoryBuiltins.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">llvm/IR/Argument.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/callingconv-h">llvm/IR/CallingConv.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">llvm/Support/TypeSize.h</a>"
#include &lt;optional&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc0bf3299bbe99f7051fc6ee07de1b80">STATISTIC</a> (NumReadNone, "Number of functions inferred as readnone")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77df356de97b56a4f70a4cba4328101a">STATISTIC</a> (NumInaccessibleMemOnly, "Number of functions inferred as inaccessiblememonly")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa896d9d77f5b3b1113287cdcd64f269a">STATISTIC</a> (NumReadOnly, "Number of functions inferred as readonly")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cad7d0f561ed1ea8cc020409a71be61">STATISTIC</a> (NumWriteOnly, "Number of functions inferred as writeonly")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0bcff48afd267418cd6bc29d8178bbb">STATISTIC</a> (NumArgMemOnly, "Number of functions inferred as argmemonly")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef73dc95826feb0c162dc4ea3318f5b7">STATISTIC</a> (NumInaccessibleMemOrArgMemOnly, "Number of functions inferred as inaccessiblemem_or_argmemonly")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b0569d285b6595a313399b4abbc4246">STATISTIC</a> (NumNoUnwind, "Number of functions inferred as nounwind")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7862f0daf73c7c742bcaad917bdfbd5a">STATISTIC</a> (NumNoCapture, "Number of arguments inferred as nocapture")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3116d2c3c5ecef8986f6851f24ecf14c">STATISTIC</a> (NumWriteOnlyArg, "Number of arguments inferred as writeonly")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a050de76ab9c9abf0206f324c416c8a92">STATISTIC</a> (NumReadOnlyArg, "Number of arguments inferred as readonly")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2244c1d2fbbc8e31aa05d6348436191">STATISTIC</a> (NumNoAlias, "Number of function returns inferred as noalias")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a3c510ccc8d8cd9614b06ff168a31bc">STATISTIC</a> (NumNoUndef, "Number of function returns inferred as noundef returns")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69ef613babd921647e49367ee30f923c">STATISTIC</a> (NumReturnedArg, "Number of arguments inferred as returned")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5c4d7256cacaeff14c8c5b9b1b06201">STATISTIC</a> (NumWillReturn, "Number of functions inferred as willreturn")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab053105853c35775062e9de4ab6db50d">STATISTIC</a> (NumCold, "Number of functions inferred as cold")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5a2e27a970c60ac9f6359f5952fd04b">STATISTIC</a> (NumNoReturn, "Number of functions inferred as no return")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29c659191a94f501d0fcbed1ec038fc6">setDoesNotAccessMemory</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a705d7baf1886e2c563acd72d0fa247eb">setIsCold</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab870e135bab0b964d551c9f8f85a6920">setNoReturn</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab963052e3e1c2670f3ba921278e8b2af">setOnlyAccessesInaccessibleMemory</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af563230bf3a3655fcd2e8fcbc46d7527">setOnlyReadsMemory</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeaadd34fcdce514cc4a395489a1c8a7">setOnlyWritesMemory</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5e33f9ec8db4547538a0470c2e1b842">setOnlyAccessesArgMemory</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d94f692bd9cced8dc9224980871d04c">setOnlyAccessesInaccessibleMemOrArgMem</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaad1694d34412656ad48fc67421e3262">setDoesNotThrow</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a954b387569997de88e7f515b56943ea9">setRetDoesNotAlias</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8d8d94c0332f6cd0a50e4ea8d76fe2d">setDoesNotCapture</a> (Function &amp;F, unsigned ArgNo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25dbed61f2588d9a6e04d7b24cc82eb4">setDoesNotAlias</a> (Function &amp;F, unsigned ArgNo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12f48e9416202b9d2610424cc5fdfc3a">setOnlyReadsMemory</a> (Function &amp;F, unsigned ArgNo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae66c81544378cca8108c8fef8b637e31">setOnlyWritesMemory</a> (Function &amp;F, unsigned ArgNo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02f36d43109b86d1ecfb0c1161e16d56">setRetNoUndef</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b463eea6993bd20bdc439dda8ea9ea6">setArgsNoUndef</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0d38e371ed4acd5d20cddfee3aa7453">setArgNoUndef</a> (Function &amp;F, unsigned ArgNo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84b37eea05a40afe51600e28fe4960e1">setRetAndArgsNoUndef</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa50217a23e5677da9384f32deaba60d6">setReturnedArg</a> (Function &amp;F, unsigned ArgNo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d3aac6350d77104c41caca1e4bd63cf">setNonLazyBind</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdd8715c27373f115d01fd95f8d76d3d">setDoesNotFreeMemory</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad6696445cc0ed9ff37af963d4cf41b1">setWillReturn</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80ea36f7233c0104e8059b64e17de44f">setAlignedAllocParam</a> (Function &amp;F, unsigned ArgNo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c57fabbbbdee320af861f4c6fc80919">setAllocatedPointerParam</a> (Function &amp;F, unsigned ArgNo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e5e759cb3f6cf4f3f67df086825189e">setAllocSize</a> (Function &amp;F, unsigned ElemSizeArg, std::optional&lt; unsigned &gt; NumElemsArg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0a6b229ccb3d943c2d6e88839ae6141">setAllocFamily</a> (Function &amp;F, StringRef Family)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5784e92545941ed78762b81c4e2189b">setAllocKind</a> (Function &amp;F, AllocFnKind K)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2b97c63c3fb8a13876d9afcbfc57fff">setArgExtAttr</a> (Function &amp;F, unsigned ArgNo, const TargetLibraryInfo &amp;TLI, bool Signed=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a608eb7ae967bfbd15f1c78ab03110d16">setRetExtAttr</a> (Function &amp;F, const TargetLibraryInfo &amp;TLI, bool Signed=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac03bc20ffe7747dad3d3d4bbbd4a3ca3">getIntTy</a> (IRBuilderBase &amp;B, const TargetLibraryInfo *TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a527943330d141bf468c70741d40375cc">getSizeTTy</a> (IRBuilderBase &amp;B, const TargetLibraryInfo *TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62d6c0a5c9dd42949245eb28ab9c37c8">emitLibCall</a> (LibFunc TheLibFunc, Type *ReturnType, ArrayRef&lt; Type * &gt; ParamTypes, ArrayRef&lt; Value * &gt; Operands, IRBuilderBase &amp;B, const TargetLibraryInfo *TLI, bool IsVaArgs=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1010fa59aa3c24fac816fbff04e96a89">appendTypeSuffix</a> (Value *Op, StringRef &amp;Name, SmallString&lt; 20 &gt; &amp;NameBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append a suffix to the function name according to the type of '<a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>'. <a href="#a1010fa59aa3c24fac816fbff04e96a89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a560b77762851df60ac51ca48db42058b">emitUnaryFloatFnCallHelper</a> (Value *Op, LibFunc TheLibFunc, StringRef Name, IRBuilderBase &amp;B, const AttributeList &amp;Attrs, const TargetLibraryInfo *TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa71b78b68e5077a0c0201ceb8b5cbe85">emitBinaryFloatFnCallHelper</a> (Value *Op1, Value *Op2, LibFunc TheLibFunc, StringRef Name, IRBuilderBase &amp;B, const AttributeList &amp;Attrs, const TargetLibraryInfo *TLI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"build-libcalls"</td>
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

## Functions

### appendTypeSuffix() {#a1010fa59aa3c24fac816fbff04e96a89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void appendTypeSuffix (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 20 &gt; &amp; NameBuffer)</td>
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

<p>Append a suffix to the function name according to the type of '<a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>'.</p>

<p>Definition at line 1770 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a656b9d85656ae6dd73f482f6d5639b97">llvm::emitBinaryFloatFnCall</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a08d868189c5335a01b6415e379a0c68c">llvm::emitUnaryFloatFnCall</a>.</p>

</div>
</div>

### emitBinaryFloatFnCallHelper() {#aa71b78b68e5077a0c0201ceb8b5cbe85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * emitBinaryFloatFnCallHelper (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op2, <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> TheLibFunc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> &amp; Attrs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI)</td>
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



<p>Definition at line 1832 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87cba3c4c88ab5df01a7f7dece1e0266">llvm::getOrInsertLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4a57dcd94b6daa3eacdbe8471955f4b1">llvm::inferNonMandatoryLibFuncAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a9da3b29e8e71b9be4645874e1721207a">llvm::CallBase::setAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0851b4de29686e9c3918449b054cfada">llvm::CallBase::setCallingConv</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5730c4888cfeb0d60f0afc368e179d61">llvm::emitBinaryFloatFnCall</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a656b9d85656ae6dd73f482f6d5639b97">llvm::emitBinaryFloatFnCall</a>.</p>

</div>
</div>

### emitLibCall() {#a62d6c0a5c9dd42949245eb28ab9c37c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * emitLibCall (<a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> TheLibFunc, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ReturnType, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; ParamTypes, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Operands, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, bool IsVaArgs=false)</td>
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



<p>Definition at line 1526 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#acee3b789f998e244c05ff9d65096178b">llvm::TargetLibraryInfo::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87cba3c4c88ab5df01a7f7dece1e0266">llvm::getOrInsertLibFunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4a57dcd94b6daa3eacdbe8471955f4b1">llvm::inferNonMandatoryLibFuncAttrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d0e3799b16937e1f8df20ca1f1f3df">llvm::isLibFuncEmittable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0851b4de29686e9c3918449b054cfada">llvm::CallBase::setCallingConv</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7e2b6aee30057f25f3a9537ff74775a8">llvm::emitBCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad286c87289a5549b40e06096076e2974">llvm::emitMemCCpy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acaee7c149092d8a3f5c9b626030c6fa9">llvm::emitMemChr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a64f1b4176cc7b8012657e7e04a687e66">llvm::emitMemCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae76b9bfb5e62fe86e9133d4a5b5bd275">llvm::emitMemPCpy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38b79d4f932b987c3ff538cacebb106f">llvm::emitMemRChr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b45cdd248363e4cae6c330d167f93f0">llvm::emitSNPrintf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35f8c517a70dfe8d3d066407c441894f">llvm::emitSPrintf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa2219174d1d70af115609449fea112b1">llvm::emitStpCpy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c2ffb91a5485fa7becad0e00d7e1815">llvm::emitStpNCpy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8da8a33e55b9283587506d8ba68c0ab2">llvm::emitStrCat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba6a71235e219f0d87ab9f7c43476a9">llvm::emitStrChr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1777b151b5f4127a3af26fa2f841a99">llvm::emitStrCpy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a70223109f2fd6a814865c58a738b4925">llvm::emitStrDup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a392fe07b95bac44c375179b4f16df1ec">llvm::emitStrLCat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adee6ec38d5e042d13294bf047abc3245">llvm::emitStrLCpy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a89b0cdc1642ef7f90fcbf492429d1ad8">llvm::emitStrLen</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a572e1b920d8a5f2a338570c82bbeb446">llvm::emitStrNCat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6235f3b5af61e1da8ecb017f6f909f1f">llvm::emitStrNCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a14a05ffce8dd7f9e6fe4a0b96dc313e6">llvm::emitStrNCpy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d61091498dd892d586e250c8d29fe3a">llvm::emitVSNPrintf</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9310a89abda7116ac06bf226544daadd">llvm::emitVSPrintf</a>.</p>

</div>
</div>

### emitUnaryFloatFnCallHelper() {#a560b77762851df60ac51ca48db42058b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * emitUnaryFloatFnCallHelper (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> TheLibFunc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> &amp; Attrs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI)</td>
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



<p>Definition at line 1784 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87cba3c4c88ab5df01a7f7dece1e0266">llvm::getOrInsertLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a9da3b29e8e71b9be4645874e1721207a">llvm::CallBase::setAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0851b4de29686e9c3918449b054cfada">llvm::CallBase::setCallingConv</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa6c86e6bdfc79d09b48a72903685b6e9">llvm::emitUnaryFloatFnCall</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a08d868189c5335a01b6415e379a0c68c">llvm::emitUnaryFloatFnCall</a>.</p>

</div>
</div>

### getIntTy() {#ac03bc20ffe7747dad3d3d4bbbd4a3ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType * getIntTy (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI)</td>
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



<p>Definition at line 1517 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#ad6cdbfae97e9631aae2c2e90a8023f99">llvm::TargetLibraryInfo::getIntSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7e2b6aee30057f25f3a9537ff74775a8">llvm::emitBCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8a6b92032e49dc6da4a5c4a05771878f">llvm::emitFPutC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689dd439a7989cc49b73cd6eb52d90dc">llvm::emitFPutS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad286c87289a5549b40e06096076e2974">llvm::emitMemCCpy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acaee7c149092d8a3f5c9b626030c6fa9">llvm::emitMemChr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a64f1b4176cc7b8012657e7e04a687e66">llvm::emitMemCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38b79d4f932b987c3ff538cacebb106f">llvm::emitMemRChr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11b84a626ef34d3ced2e131937e58ddd">llvm::emitPutChar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8cc4358373eeb5363cd620bbdaeab">llvm::emitPutS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b45cdd248363e4cae6c330d167f93f0">llvm::emitSNPrintf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35f8c517a70dfe8d3d066407c441894f">llvm::emitSPrintf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba6a71235e219f0d87ab9f7c43476a9">llvm::emitStrChr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6235f3b5af61e1da8ecb017f6f909f1f">llvm::emitStrNCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d61091498dd892d586e250c8d29fe3a">llvm::emitVSNPrintf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9310a89abda7116ac06bf226544daadd">llvm::emitVSPrintf</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a4bfdcc832771570bdc4bc5cbedfc2d00">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::getConstInt</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a6a12fa96c1212a99f965fcce98aa550a">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::joinVectorElements</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a97c8c57e973ff87b44455c5d47d41770">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::rescale</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a40bdb7ed86f1fdb139eb9fd73b05405a">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::splitVectorElements</a>.</p>

</div>
</div>

### getSizeTTy() {#a527943330d141bf468c70741d40375cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType * getSizeTTy (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI)</td>
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



<p>Definition at line 1521 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a5b8cd043d27c642730b103a0eb241bd7">llvm::TargetLibraryInfo::getSizeTSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7e2b6aee30057f25f3a9537ff74775a8">llvm::emitBCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8dbd4c4f3aebf9f810f0590d49ba1003">llvm::emitCalloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a2a45b5fd2f1698d6fd10a06a0a38f2">llvm::emitFWrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76c99e44c5f3570a3666c9234caf222">llvm::emitMalloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad286c87289a5549b40e06096076e2974">llvm::emitMemCCpy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acaee7c149092d8a3f5c9b626030c6fa9">llvm::emitMemChr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a64f1b4176cc7b8012657e7e04a687e66">llvm::emitMemCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1484bdcb6b4c84ceb447270f8acca352">llvm::emitMemCpyChk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae76b9bfb5e62fe86e9133d4a5b5bd275">llvm::emitMemPCpy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38b79d4f932b987c3ff538cacebb106f">llvm::emitMemRChr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b45cdd248363e4cae6c330d167f93f0">llvm::emitSNPrintf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c2ffb91a5485fa7becad0e00d7e1815">llvm::emitStpNCpy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a392fe07b95bac44c375179b4f16df1ec">llvm::emitStrLCat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adee6ec38d5e042d13294bf047abc3245">llvm::emitStrLCpy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a89b0cdc1642ef7f90fcbf492429d1ad8">llvm::emitStrLen</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a572e1b920d8a5f2a338570c82bbeb446">llvm::emitStrNCat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6235f3b5af61e1da8ecb017f6f909f1f">llvm::emitStrNCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a14a05ffce8dd7f9e6fe4a0b96dc313e6">llvm::emitStrNCpy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5d61091498dd892d586e250c8d29fe3a">llvm::emitVSNPrintf</a>.</p>

</div>
</div>

### setAlignedAllocParam() {#a80ea36f7233c0104e8059b64e17de44f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setAlignedAllocParam (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, unsigned ArgNo)</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setAllocatedPointerParam() {#a5c57fabbbbdee320af861f4c6fc80919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setAllocatedPointerParam (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, unsigned ArgNo)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setAllocFamily() {#ad0a6b229ccb3d943c2d6e88839ae6141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setAllocFamily (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Family)</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setAllocKind() {#ab5784e92545941ed78762b81c4e2189b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setAllocKind (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1">AllocFnKind</a> K)</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setAllocSize() {#a7e5e759cb3f6cf4f3f67df086825189e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setAllocSize (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, unsigned ElemSizeArg, std::optional&lt; unsigned &gt; NumElemsArg)</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#a6f90f8b9a9209911cdd0573c4e25388e">llvm::Attribute::getWithAllocSizeArgs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setArgExtAttr() {#ae2b97c63c3fb8a13876d9afcbfc57fff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setArgExtAttr (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, unsigned ArgNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI, bool Signed=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 1329 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">llvm::Attribute::None</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a87cba3c4c88ab5df01a7f7dece1e0266">llvm::getOrInsertLibFunc</a>.</p>

</div>
</div>

### setArgNoUndef() {#ad0d38e371ed4acd5d20cddfee3aa7453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setArgNoUndef (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, unsigned ArgNo)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setArgsNoUndef() {#a4b463eea6993bd20bdc439dda8ea9ea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setArgsNoUndef (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a> and <a href="#a84b37eea05a40afe51600e28fe4960e1">setRetAndArgsNoUndef</a>.</p>

</div>
</div>

### setDoesNotAccessMemory() {#a29c659191a94f501d0fcbed1ec038fc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setDoesNotAccessMemory (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setDoesNotAlias() {#a25dbed61f2588d9a6e04d7b24cc82eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setDoesNotAlias (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, unsigned ArgNo)</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setDoesNotCapture() {#aa8d8d94c0332f6cd0a50e4ea8d76fe2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setDoesNotCapture (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, unsigned ArgNo)</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setDoesNotFreeMemory() {#afdd8715c27373f115d01fd95f8d76d3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setDoesNotFreeMemory (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setDoesNotThrow() {#aaad1694d34412656ad48fc67421e3262}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setDoesNotThrow (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setIsCold() {#a705d7baf1886e2c563acd72d0fa247eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setIsCold (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setNonLazyBind() {#a6d3aac6350d77104c41caca1e4bd63cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setNonLazyBind (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp/#aa5369c9d1c15e1c2fe5106461ae89334">lowerObjCCall</a>.</p>

</div>
</div>

### setNoReturn() {#ab870e135bab0b964d551c9f8f85a6920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setNoReturn (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setOnlyAccessesArgMemory() {#ae5e33f9ec8db4547538a0470c2e1b842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setOnlyAccessesArgMemory (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setOnlyAccessesInaccessibleMemOrArgMem() {#a7d94f692bd9cced8dc9224980871d04c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setOnlyAccessesInaccessibleMemOrArgMem (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setOnlyAccessesInaccessibleMemory() {#ab963052e3e1c2670f3ba921278e8b2af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setOnlyAccessesInaccessibleMemory (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setOnlyReadsMemory() {#af563230bf3a3655fcd2e8fcbc46d7527}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setOnlyReadsMemory (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setOnlyReadsMemory() {#a12f48e9416202b9d2610424cc5fdfc3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setOnlyReadsMemory (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, unsigned ArgNo)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### setOnlyWritesMemory() {#aeeaadd34fcdce514cc4a395489a1c8a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setOnlyWritesMemory (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setOnlyWritesMemory() {#ae66c81544378cca8108c8fef8b637e31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setOnlyWritesMemory (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, unsigned ArgNo)</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### setRetAndArgsNoUndef() {#a84b37eea05a40afe51600e28fe4960e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setRetAndArgsNoUndef (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a4b463eea6993bd20bdc439dda8ea9ea6">setArgsNoUndef</a> and <a href="#a02f36d43109b86d1ecfb0c1161e16d56">setRetNoUndef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setRetDoesNotAlias() {#a954b387569997de88e7f515b56943ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setRetDoesNotAlias (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setRetExtAttr() {#a608eb7ae967bfbd15f1c78ab03110d16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setRetExtAttr (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI, bool Signed=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 1336 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">llvm::Attribute::None</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a87cba3c4c88ab5df01a7f7dece1e0266">llvm::getOrInsertLibFunc</a>.</p>

</div>
</div>

### setRetNoUndef() {#a02f36d43109b86d1ecfb0c1161e16d56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setRetNoUndef (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a> and <a href="#a84b37eea05a40afe51600e28fe4960e1">setRetAndArgsNoUndef</a>.</p>

</div>
</div>

### setReturnedArg() {#aa50217a23e5677da9384f32deaba60d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setReturnedArg (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, unsigned ArgNo)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### setWillReturn() {#aad6696445cc0ed9ff37af963d4cf41b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setWillReturn (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1cf88c4b4d9016af2a02ae6faa63cdf1">llvm::inferNonMandatoryLibFuncAttrs</a>.</p>

</div>
</div>

### STATISTIC() {#afc0bf3299bbe99f7051fc6ee07de1b80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumReadNone, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> inferred as readnone")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a77df356de97b56a4f70a4cba4328101a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumInaccessibleMemOnly, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> inferred as inaccessiblememonly")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aa896d9d77f5b3b1113287cdcd64f269a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumReadOnly, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> inferred as readonly")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a5cad7d0f561ed1ea8cc020409a71be61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumWriteOnly, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> inferred as writeonly")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#af0bcff48afd267418cd6bc29d8178bbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumArgMemOnly, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> inferred as argmemonly")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aef73dc95826feb0c162dc4ea3318f5b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumInaccessibleMemOrArgMemOnly, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> inferred as inaccessiblemem_or_argmemonly")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a6b0569d285b6595a313399b4abbc4246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumNoUnwind, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> inferred as nounwind")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a7862f0daf73c7c742bcaad917bdfbd5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumNoCapture, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a27a0ca182c45d386e77d15f3399d7cde">arguments</a> inferred as nocapture")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a3116d2c3c5ecef8986f6851f24ecf14c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumWriteOnlyArg, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a27a0ca182c45d386e77d15f3399d7cde">arguments</a> inferred as writeonly")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a050de76ab9c9abf0206f324c416c8a92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumReadOnlyArg, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a27a0ca182c45d386e77d15f3399d7cde">arguments</a> inferred as readonly")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ab2244c1d2fbbc8e31aa05d6348436191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumNoAlias, "Number of <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> returns inferred as noalias")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a9a3c510ccc8d8cd9614b06ff168a31bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumNoUndef, "Number of <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> returns inferred as noundef returns")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a69ef613babd921647e49367ee30f923c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumReturnedArg, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a27a0ca182c45d386e77d15f3399d7cde">arguments</a> inferred as returned")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ae5c4d7256cacaeff14c8c5b9b1b06201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumWillReturn, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> inferred as willreturn")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ab053105853c35775062e9de4ab6db50d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumCold, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> inferred as cold")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ac5a2e27a970c60ac9f6359f5952fd04b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumNoReturn, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> inferred as no return")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"build-libcalls"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp">BuildLibCalls.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
