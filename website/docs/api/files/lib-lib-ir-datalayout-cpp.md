---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/ir/datalayout-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DataLayout.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/getelementptrtypeiterator-h">llvm/IR/GetElementPtrTypeIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memalloc-h">llvm/Support/MemAlloc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">llvm/Support/TypeSize.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;cstdlib&gt;
#include &lt;new&gt;
#include &lt;utility&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-datalayout-cpp-">anonymous{DataLayout.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-datalayout-cpp-/structlayoutmap">StructLayoutMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-datalayout-cpp-/lessprimitivebitwidth">LessPrimitiveBitWidth</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/predicate">Predicate</a> to sort primitive specs by bit width. <a href="/web-llvm/docs/api/structs/anonymous-datalayout-cpp-/lessprimitivebitwidth/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-datalayout-cpp-/lesspointeraddrspace">LessPointerAddrSpace</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/predicate">Predicate</a> to sort pointer specs by address space number. <a href="/web-llvm/docs/api/structs/anonymous-datalayout-cpp-/lesspointeraddrspace/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b24910a0327bc6a8eb631853b022371">createSpecFormatError</a> (Twine Format)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a221bcb219fc93988419350acf03ac23d">parseAddrSpace</a> (StringRef Str, unsigned &amp;AddrSpace)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempts to parse an address space component of a specification. <a href="#a221bcb219fc93988419350acf03ac23d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0106e369078637cf051ef66c829ad540">parseSize</a> (StringRef Str, unsigned &amp;BitWidth, StringRef Name="size")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempts to parse a size component of a specification. <a href="#a0106e369078637cf051ef66c829ad540">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a352f4ca101ae014677dda708b07b98f7">parseAlignment</a> (StringRef Str, Align &amp;Alignment, StringRef Name, bool AllowZero=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempts to parse an alignment component of a specification. <a href="#a352f4ca101ae014677dda708b07b98f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0626211048d3157a84aac054ba7e894a">getElementIndex</a> (TypeSize ElemSize, APInt &amp;Offset)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/structs/llvm/datalayout/primitivespec">DataLayout::PrimitiveSpec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5b235899641897e1ab41d5e50337020">DefaultIntSpecs</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/structs/llvm/datalayout/primitivespec">DataLayout::PrimitiveSpec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a608eb64104e2fd979127cd0311a9a183">DefaultFloatSpecs</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/structs/llvm/datalayout/primitivespec">DataLayout::PrimitiveSpec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86c777135c0e97b201c0ff7f297661d5">DefaultVectorSpecs</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/structs/llvm/datalayout/pointerspec">DataLayout::PointerSpec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e85737a58dc8436d6990110466f5b5f">DefaultPointerSpecs</a>[] = ...</td>
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

### createSpecFormatError() {#a2b24910a0327bc6a8eb631853b022371}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error createSpecFormatError (<a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> Format)</td>
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



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>.</p>

</div>
</div>

### getElementIndex() {#a0626211048d3157a84aac054ba7e894a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt getElementIndex (<a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> ElemSize, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Offset)</td>
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



<p>Definition at line 920 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a995470163b6d76695cba5bc8dfb529">llvm::isUIntN</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#abe6927d96b3815417479246b5afc732e">areTwoInsertFromSameBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a3c995d3af67d9f0024160f8480989563">findBuildAggregate_rec</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#ab3c9ad31690c1a9b440d3ad2d73563af">llvm::DataLayout::getGEPIndexForOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a36523fbc60bf720df4d9f20cfae7bb7f">llvm::DataLayout::getGEPIndicesForOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7800714c330f8f3952e8058b090e001b">llvm::slpvectorizer::BoUpSLP::getTreeCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a405ff61e8571b58fecaa716540af108f">isFirstInsertElement</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>.</p>

</div>
</div>

### parseAddrSpace() {#a221bcb219fc93988419350acf03ac23d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error parseAddrSpace (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, unsigned &amp; AddrSpace)</td>
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

<p>Attempts to parse an address space component of a specification.</p>

<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae03f2b6a02fc9092755ba3a6cf6d2446">llvm::to_integer</a>.</p>

</div>
</div>

### parseAlignment() {#a352f4ca101ae014677dda708b07b98f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error parseAlignment (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp; Alignment, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool AllowZero=false)</td>
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

<p>Attempts to parse an alignment component of a specification.</p>


<p>On success, returns the value converted to byte amount in <span class="doxyComputerOutput">Alignment</span>. If the value is zero and <span class="doxyComputerOutput">AllowZero</span> is true, <span class="doxyComputerOutput">Alignment</span> is set to one.</p>


<p>Return an error in a number of cases:</p>


<ul class="doxyList ">
<li><span class="doxyComputerOutput">Str</span> is empty or contains characters other than decimal digits;</li>
<li>the value is zero and <span class="doxyComputerOutput">AllowZero</span> is false;</li>
<li>the value is too large;</li>
<li>the value is not a multiple of the byte width;</li>
<li>the value converted to byte amount is not not a power of two.</li>
</ul>

<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae03f2b6a02fc9092755ba3a6cf6d2446">llvm::to_integer</a>.</p>

</div>
</div>

### parseSize() {#a0106e369078637cf051ef66c829ad540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error parseSize (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, unsigned &amp; BitWidth, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name="size")</td>
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

<p>Attempts to parse a size component of a specification.</p>

<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae03f2b6a02fc9092755ba3a6cf6d2446">llvm::to_integer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DefaultFloatSpecs {#a608eb64104e2fd979127cd0311a9a183}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataLayout::PrimitiveSpec DefaultFloatSpecs[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    {16, Align::Constant&lt;2&gt;(), Align::Constant&lt;2&gt;()},    
    {32, Align::Constant&lt;4&gt;(), Align::Constant&lt;4&gt;()},    
    {64, Align::Constant&lt;8&gt;(), Align::Constant&lt;8&gt;()},    
    {128, Align::Constant&lt;16&gt;(), Align::Constant&lt;16&gt;()}, 
}
</div>
</dd>
</dl>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a62d0fc1e33fe098cd53b43b42f8ba0a7">llvm::DataLayout::DataLayout</a>.</p>

</div>
</div>

### DefaultIntSpecs {#ae5b235899641897e1ab41d5e50337020}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataLayout::PrimitiveSpec DefaultIntSpecs[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    {1, Align::Constant&lt;1&gt;(), Align::Constant&lt;1&gt;()},  
    {8, Align::Constant&lt;1&gt;(), Align::Constant&lt;1&gt;()},  
    {16, Align::Constant&lt;2&gt;(), Align::Constant&lt;2&gt;()}, 
    {32, Align::Constant&lt;4&gt;(), Align::Constant&lt;4&gt;()}, 
    {64, Align::Constant&lt;4&gt;(), Align::Constant&lt;8&gt;()}, 
}
</div>
</dd>
</dl>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a62d0fc1e33fe098cd53b43b42f8ba0a7">llvm::DataLayout::DataLayout</a>.</p>

</div>
</div>

### DefaultPointerSpecs {#a8e85737a58dc8436d6990110466f5b5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataLayout::PointerSpec DefaultPointerSpecs[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    {0, 64, Align::Constant&lt;8&gt;(), Align::Constant&lt;8&gt;(), 64, false},
}
</div>
</dd>
</dl>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a62d0fc1e33fe098cd53b43b42f8ba0a7">llvm::DataLayout::DataLayout</a>.</p>

</div>
</div>

### DefaultVectorSpecs {#a86c777135c0e97b201c0ff7f297661d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataLayout::PrimitiveSpec DefaultVectorSpecs[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    {64, Align::Constant&lt;8&gt;(), Align::Constant&lt;8&gt;()},    
    {128, Align::Constant&lt;16&gt;(), Align::Constant&lt;16&gt;()}, 
}
</div>
</dd>
</dl>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp">DataLayout.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a62d0fc1e33fe098cd53b43b42f8ba0a7">llvm::DataLayout::DataLayout</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
