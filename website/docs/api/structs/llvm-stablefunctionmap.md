---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/stablefunctionmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `StableFunctionMap` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::StableFunctionMap { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">llvm/CGData/StableFunctionMap.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80e494265049ae5ce939a82a456b4cb0">HashFuncsMapType</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap/stablefunctionentry">StableFunctionEntry</a> &gt; &gt; &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SizeType { <a href="#af7f46a87841819951deaec079f953594">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae47d1e4bf52d69b600aeafc0e4234271">StableFunctionMapRecord</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a80e494265049ae5ce939a82a456b4cb0">HashFuncsMapType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f7a4800ad974e1eea6f58f1d04c5c8c">getFunctionMap</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the HashToFuncs map for serialization. <a href="#a9f7a4800ad974e1eea6f58f1d04c5c8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f3891770db1cc86ff900295d1a0d01b">getNames</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the NameToId vector for serialization. <a href="#a6f3891770db1cc86ff900295d1a0d01b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adec4c768a37d95c89b361ae6c2e2babd">getIdOrCreateForName</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an existing <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> associated with the given name or create a new <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> if it doesn't exist. <a href="#adec4c768a37d95c89b361ae6c2e2babd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5929b80d72ba7c390d3a83391c376f1">getNameForId</a> (unsigned Id) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name associated with a given <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#ac5929b80d72ba7c390d3a83391c376f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e8659acb3cbdfe3499a5f95696e57a0">insert</a> (const StableFunction &amp;Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/stablefunction">StableFunction</a></span> object into the function map. <a href="#a4e8659acb3cbdfe3499a5f95696e57a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa95f380df2edf513b206d5d47dbce3b6">merge</a> (const StableFunctionMap &amp;OtherMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge a <span class="doxyComputerOutput">OtherMap</span> into this function map. <a href="#aa95f380df2edf513b206d5d47dbce3b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b33abb63149544bcaf0019c9889d7fb">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c43a7970dab09919d38ebc80ac9a0cb">size</a> (SizeType Type=UniqueHashCount) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ca2d718f999a38c14668dffda65cdb9">finalize</a> (bool SkipTrim=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize the stable function map by trimming content. <a href="#a2ca2d718f999a38c14668dffda65cdb9">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4d2586762f7dcfe2dc7bfb0c06902ac">insert</a> (std::unique_ptr&lt; StableFunctionEntry &gt; FuncEntry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap/stablefunctionentry">StableFunctionEntry</a></span> into the function map directly. <a href="#aa4d2586762f7dcfe2dc7bfb0c06902ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a80e494265049ae5ce939a82a456b4cb0">HashFuncsMapType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01725c86da8d550589958ad8ecddd782">HashToFuncs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A map from a <a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a> to a vector of functions with that hash. <a href="#a01725c86da8d550589958ad8ecddd782">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a731694fe2f7d2078fe490358f2ba27f7">IdToName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A vector of strings to hold names. <a href="#a731694fe2f7d2078fe490358f2ba27f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01328bdb92b03fabd41a93cbde280f92">NameToId</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A map from <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> (name) to an <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#a01328bdb92b03fabd41a93cbde280f92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dd6152c36d9a21e30aadfbe5e3f0a4d">Finalized</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the function map is finalized with minimal content. <a href="#a9dd6152c36d9a21e30aadfbe5e3f0a4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### HashFuncsMapType {#a80e494265049ae5ce939a82a456b4cb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StableFunctionMap::HashFuncsMapType = 
      DenseMap&lt;stable_hash, SmallVector&lt;std::unique_ptr&lt;StableFunctionEntry&gt;&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### SizeType {#af7f46a87841819951deaec079f953594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::StableFunctionMap::SizeType </td>
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
<td class="doxyEnumItemName">UniqueHashCount<a id="af7f46a87841819951deaec079f953594ac4b99e236c0602a0561e7117a8ce1a21"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TotalFunctionCount<a id="af7f46a87841819951deaec079f953594ad58321089258f4472260701d4e582164"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MergeableFunctionCount<a id="af7f46a87841819951deaec079f953594abf77634466d9f40413dffc0111c41c77"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### StableFunctionMapRecord {#ae47d1e4bf52d69b600aeafc0e4234271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmaprecord">StableFunctionMapRecord</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<p>Reference <a href="#ae47d1e4bf52d69b600aeafc0e4234271">StableFunctionMapRecord</a>.</p>


<p>Referenced by <a href="#ae47d1e4bf52d69b600aeafc0e4234271">StableFunctionMapRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### empty() {#a4b33abb63149544bcaf0019c9889d7fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StableFunctionMap::empty ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if there is no stable function entry.</p></dd>
</dl>


<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### finalize() {#a2ca2d718f999a38c14668dffda65cdb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StableFunctionMap::finalize (bool SkipTrim=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize the stable function map by trimming content.</p>

<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af59335be18fa802d111a646be658b7d0a68a576ae5bab85b26f5e5a947d3b41e8">llvm::Invalid</a>, <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp/#a1429d1fad1503cf63298bd5441e0e04b">isProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp/#a172ac12ba3705f1f1e519e50c874d406">removeIdenticalIndexPair</a>.</p>

</div>
</div>

### getFunctionMap() {#a9f7a4800ad974e1eea6f58f1d04c5c8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HashFuncsMapType &amp; llvm::StableFunctionMap::getFunctionMap ()</td>
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

<p>Get the HashToFuncs map for serialization.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmaprecord-cpp/#a509ce85b468f4da99d1111c7498e2557">getStableFunctionEntries</a> and <a href="/web-llvm/docs/api/classes/llvm/globalmergefunc/#a31ba90bd367677d2bf4065d6e51eca65">llvm::GlobalMergeFunc::merge</a>.</p>

</div>
</div>

### getIdOrCreateForName() {#adec4c768a37d95c89b361ae6c2e2babd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StableFunctionMap::getIdOrCreateForName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get an existing <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> associated with the given name or create a new <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> if it doesn't exist.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a4e8659acb3cbdfe3499a5f95696e57a0">insert</a> and <a href="#aa95f380df2edf513b206d5d47dbce3b6">merge</a>.</p>

</div>
</div>

### getNameForId() {#ac5929b80d72ba7c390d3a83391c376f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::string &gt; StableFunctionMap::getNameForId (unsigned Id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the name associated with a given <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>

<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>


<p>Referenced by <a href="#aa95f380df2edf513b206d5d47dbce3b6">merge</a>.</p>

</div>
</div>

### getNames() {#a6f3891770db1cc86ff900295d1a0d01b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVector&lt; std::string &gt; llvm::StableFunctionMap::getNames ()</td>
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

<p>Get the NameToId vector for serialization.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>

</div>
</div>

### insert() {#a4e8659acb3cbdfe3499a5f95696e57a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StableFunctionMap::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/stablefunction">StableFunction</a> &amp; Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/stablefunction">StableFunction</a></span> object into the function map.</p>


<p>This method handles the uniquing of string names and create a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap/stablefunctionentry">StableFunctionEntry</a></span> for insertion.</p>


<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adec4c768a37d95c89b361ae6c2e2babd">getIdOrCreateForName</a> and <a href="#a4e8659acb3cbdfe3499a5f95696e57a0">insert</a>.</p>


<p>Referenced by <a href="#a4e8659acb3cbdfe3499a5f95696e57a0">insert</a>.</p>

</div>
</div>

### merge() {#aa95f380df2edf513b206d5d47dbce3b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StableFunctionMap::merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap">StableFunctionMap</a> &amp; OtherMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge a <span class="doxyComputerOutput">OtherMap</span> into this function map.</p>

<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adec4c768a37d95c89b361ae6c2e2babd">getIdOrCreateForName</a> and <a href="#ac5929b80d72ba7c390d3a83391c376f1">getNameForId</a>.</p>

</div>
</div>

### size() {#a3c43a7970dab09919d38ebc80ac9a0cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t StableFunctionMap::size (<a href="#af7f46a87841819951deaec079f953594">SizeType</a> Type=<a href="#af7f46a87841819951deaec079f953594ac4b99e236c0602a0561e7117a8ce1a21">UniqueHashCount</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the size of <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap">StableFunctionMap</a>. <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></span> is the type of size to return.</p></dd>
</dl>


<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#af7f46a87841819951deaec079f953594abf77634466d9f40413dffc0111c41c77">MergeableFunctionCount</a>, <a href="#af7f46a87841819951deaec079f953594ad58321089258f4472260701d4e582164">TotalFunctionCount</a> and <a href="#af7f46a87841819951deaec079f953594ac4b99e236c0602a0561e7117a8ce1a21">UniqueHashCount</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### insert() {#aa4d2586762f7dcfe2dc7bfb0c06902ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::StableFunctionMap::insert (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap/stablefunctionentry">StableFunctionEntry</a> &gt; FuncEntry)</td>
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

<p>Insert a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap/stablefunctionentry">StableFunctionEntry</a></span> into the function map directly.</p>


<p>This method assumes that string names have already been uniqued and the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap/stablefunctionentry">StableFunctionEntry</a></span> is ready for insertion.</p>


<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Finalized {#a9dd6152c36d9a21e30aadfbe5e3f0a4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StableFunctionMap::Finalized = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the function map is finalized with minimal content.</p>

<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>

</div>
</div>

### HashToFuncs {#a01725c86da8d550589958ad8ecddd782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashFuncsMapType llvm::StableFunctionMap::HashToFuncs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A map from a <a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a> to a vector of functions with that hash.</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>

</div>
</div>

### IdToName {#a731694fe2f7d2078fe490358f2ba27f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::string&gt; llvm::StableFunctionMap::IdToName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A vector of strings to hold names.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>

</div>
</div>

### NameToId {#a01328bdb92b03fabd41a93cbde280f92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;unsigned&gt; llvm::StableFunctionMap::NameToId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A map from <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> (name) to an <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
