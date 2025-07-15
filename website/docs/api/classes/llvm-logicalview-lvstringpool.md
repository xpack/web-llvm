---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/logicalview/lvstringpool
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LVStringPool` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::logicalview::LVStringPool { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">llvm/DebugInfo/LogicalView/Core/LVStringPool.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f29c99dbb0a0e1a0a9ca2d3e5c7708b">TableType</a> = <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; size_t, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38432ff455f71d3b6c47c92b8a66c829">ValueType</a> = <a href="/web-llvm/docs/api/classes/llvm/stringmap/#aa88257a78f38ec0829087713375505dd">TableType::value_type</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a204c21bef4e5468aa430c008e1a68b4e">LVStringPool</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8680ff89615c455eb9fd42ee8db637a">LVStringPool</a> (LVStringPool const &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd07876426d0f69542e06ecb5f9edada">LVStringPool</a> (LVStringPool &amp;&amp;other)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ee48effa9b312b3efa74e90cc3e89b1">~LVStringPool</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06eb9890632fe484dfe264008ea90ab6">isValidIndex</a> (size_t Index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed4e58adc6fdb1955b800f443c0f575e">getSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d8cd9b380cbfd1b9785ba062fe702bb">findIndex</a> (StringRef Key) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae39a6c4bf47bfd20b1d17e8b352e3a14">getIndex</a> (StringRef Key)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6daea733db985910935c38c04cc2564">getString</a> (size_t Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a294b67689fb7619fb93f45e5e1f608dd">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c1e075eb2c5d51cc9e2fb037a245dbc">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf362eb9f08fd148301d2ca309298b40">Allocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">TableType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca238c8ba49c6b02e9f2b0066fefd9cd">StringTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; ValueType * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b63004cea790afe14978f75b75a400">Entries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d33c1320c14c50213ce02104c02863e">BadIndex</a> = std::numeric_limits&lt;size_t&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### TableType {#a9f29c99dbb0a0e1a0a9ca2d3e5c7708b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::LVStringPool::TableType =  StringMap&lt;size_t, BumpPtrAllocator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>

</div>
</div>

### ValueType {#a38432ff455f71d3b6c47c92b8a66c829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::LVStringPool::ValueType =  TableType::value_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LVStringPool() {#a204c21bef4e5468aa430c008e1a68b4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVStringPool::LVStringPool ()</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>


<p>Reference <a href="#ae39a6c4bf47bfd20b1d17e8b352e3a14">getIndex</a>.</p>


<p>Referenced by <a href="#acd07876426d0f69542e06ecb5f9edada">LVStringPool</a> and <a href="#aa8680ff89615c455eb9fd42ee8db637a">LVStringPool</a>.</p>

</div>
</div>

### LVStringPool() {#aa8680ff89615c455eb9fd42ee8db637a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVStringPool::LVStringPool (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvstringpool">LVStringPool</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>


<p>Reference <a href="#a204c21bef4e5468aa430c008e1a68b4e">LVStringPool</a>.</p>

</div>
</div>

### LVStringPool() {#acd07876426d0f69542e06ecb5f9edada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVStringPool::LVStringPool (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvstringpool">LVStringPool</a> &amp;&amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>


<p>Reference <a href="#a204c21bef4e5468aa430c008e1a68b4e">LVStringPool</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LVStringPool() {#a1ee48effa9b312b3efa74e90cc3e89b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVStringPool::~LVStringPool ()</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a8c1e075eb2c5d51cc9e2fb037a245dbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVStringPool::dump ()</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#a294b67689fb7619fb93f45e5e1f608dd">print</a>.</p>

</div>
</div>

### findIndex() {#a0d8cd9b380cbfd1b9785ba062fe702bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::logicalview::LVStringPool::findIndex (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>


<p>Referenced by <a href="#ae39a6c4bf47bfd20b1d17e8b352e3a14">getIndex</a>.</p>

</div>
</div>

### getIndex() {#ae39a6c4bf47bfd20b1d17e8b352e3a14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::logicalview::LVStringPool::getIndex (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringmapentry/#a09f6c55119f75e7997dab2bbd8d2f065">llvm::StringMapEntry&lt; ValueTy &gt;::create</a>, <a href="#a0d8cd9b380cbfd1b9785ba062fe702bb">findIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="#a06eb9890632fe484dfe264008ea90ab6">isValidIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvelement-cpp/#a0a0a5465a81f37e6f33be77ca0cc85e4">getStringIndex</a>, <a href="#a204c21bef4e5468aa430c008e1a68b4e">LVStringPool</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopecompileunit/#a95dfe5b9604ba542096394cb0c7141ec">llvm::logicalview::LVScopeCompileUnit::setCompilationDirectory</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopeaggregate/#a0e8a578d25b46de15538fd9ba938402a">llvm::logicalview::LVScopeAggregate::setEncodedArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopefunction/#a3ec8dd057a333f8d7e8e7f7f1f0c4a58">llvm::logicalview::LVScopeFunction::setEncodedArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscoperoot/#ab32fe8f4d949a79914a32b5ea6928726">llvm::logicalview::LVScopeRoot::setFileFormatName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopefunction/#a182f3ad0cd978373321d157f536082f4">llvm::logicalview::LVScopeFunction::setLinkageName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbol/#a9542d7dd44206a0d47ec9600f9124518">llvm::logicalview::LVSymbol::setLinkageName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a7acb49478601af95b4023b911a973ecf">llvm::logicalview::LVElement::setName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopecompileunit/#a23d3e7c9e3177a2746f72f58d70ca092">llvm::logicalview::LVScopeCompileUnit::setProducer</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a6a8c48f1807ca021e0b8587edc51e48c">llvm::logicalview::LVElement::setQualifiedName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbol/#af0f483ada0be451faa2b254c9548ca1d">llvm::logicalview::LVSymbol::setValue</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypeenumerator/#a330a56df527cd38b617f7726bc9bf049">llvm::logicalview::LVTypeEnumerator::setValue</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypeparam/#a703ff916ed3cc69f9a057e275ce396d2">llvm::logicalview::LVTypeParam::setValue</a>.</p>

</div>
</div>

### getSize() {#aed4e58adc6fdb1955b800f443c0f575e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::logicalview::LVStringPool::getSize ()</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>

</div>
</div>

### getString() {#ad6daea733db985910935c38c04cc2564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::logicalview::LVStringPool::getString (size_t Index)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopecompileunit/#ab73772b12b1e8ae730071128f36ec8a5">llvm::logicalview::LVScopeCompileUnit::getCompilationDirectory</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopeaggregate/#a31c0b21f72dca87ab11b4bb0e5500fc4">llvm::logicalview::LVScopeAggregate::getEncodedArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopefunction/#a84884311be9a507cd1ff9bcc82203365">llvm::logicalview::LVScopeFunction::getEncodedArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscoperoot/#a44a977c5dbc9c5241cea15a23570b8d2">llvm::logicalview::LVScopeRoot::getFileFormatName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopecompileunit/#acb90ff55da5cdef102498df34be06547">llvm::logicalview::LVScopeCompileUnit::getFilename</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopefunction/#a949cd0902ea33ce1d7bc8940eaccdd83">llvm::logicalview::LVScopeFunction::getLinkageName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbol/#a73168fc650aa4c12c42347b50b4a48af">llvm::logicalview::LVSymbol::getLinkageName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a84e414a8ce9720ec080b00475cf799f6">llvm::logicalview::LVElement::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#adc89c46b1e58bf83a945debc69103d3d">llvm::logicalview::LVElement::getPathname</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopecompileunit/#aef7a66a869c3ebaddbcb2cc7febc77ca">llvm::logicalview::LVScopeCompileUnit::getProducer</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a22f7b80319a24d4857818a245aaab295">llvm::logicalview::LVElement::getQualifiedName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbol/#a9034da77379e608d47a977cbb4cccad7">llvm::logicalview::LVSymbol::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypeenumerator/#ab1173f72642ea43a3203c2f2644d2f30">llvm::logicalview::LVTypeEnumerator::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypeparam/#ad7cb673fe7917658cfb60d2a4e92e862">llvm::logicalview::LVTypeParam::getValue</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopecompileunit/#aea50fe32fcd599f0223998c048f09126">llvm::logicalview::LVScopeCompileUnit::printLocalNames</a>.</p>

</div>
</div>

### isValidIndex() {#a06eb9890632fe484dfe264008ea90ab6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVStringPool::isValidIndex (size_t Index)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>


<p>Referenced by <a href="#ae39a6c4bf47bfd20b1d17e8b352e3a14">getIndex</a>.</p>

</div>
</div>

### print() {#a294b67689fb7619fb93f45e5e1f608dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVStringPool::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>


<p>Referenced by <a href="#a8c1e075eb2c5d51cc9e2fb037a245dbc">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocator {#acf362eb9f08fd148301d2ca309298b40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::logicalview::LVStringPool::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>

</div>
</div>

### Entries {#a79b63004cea790afe14978f75b75a400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ValueType *&gt; llvm::logicalview::LVStringPool::Entries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>

</div>
</div>

### StringTable {#aca238c8ba49c6b02e9f2b0066fefd9cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TableType llvm::logicalview::LVStringPool::StringTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### BadIndex {#a4d33c1320c14c50213ce02104c02863e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::logicalview::LVStringPool::BadIndex = std::numeric_limits&lt;size_t&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvstringpool-h">LVStringPool.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
