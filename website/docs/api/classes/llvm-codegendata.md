---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codegendata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CodeGenData` Class



## Declaration

<div class="doxyDeclaration">
class llvm::CodeGenData { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">llvm/CGData/CodeGenData.h</a>"
</div>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4abbcc1c3904b0c438b4cac811776a4">CodeGenData</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a9b6539320e312559d38149f9cc3e19">~CodeGenData</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a743f557723374e2edf31ae04673b653a">hasOutlinedHashTree</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we have a valid outlined hash tree. <a href="#a743f557723374e2edf31ae04673b653a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0074654a63d2717448e3ca65fb166b38">hasStableFunctionMap</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e5f32b1f85714a5fb918833048c04d8">getOutlinedHashTree</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the outlined hash tree. <a href="#a8e5f32b1f85714a5fb918833048c04d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap">StableFunctionMap</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ca8e548ef9d5c9ea700ef5ca967affd">getStableFunctionMap</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c2334570aeb5f51fc75d0ed0bba7768">emitCGData</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we should write codegen data. <a href="#a1c2334570aeb5f51fc75d0ed0bba7768">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a565722c191eaf11d0247efe5104c4db8">publishOutlinedHashTree</a> (std::unique_ptr&lt; OutlinedHashTree &gt; HashTree)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Publish the (globally) merged or read outlined hash tree. <a href="#a565722c191eaf11d0247efe5104c4db8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1cd6547aef00b0dcd2f15e3e7fb954b">publishStableFunctionMap</a> (std::unique_ptr&lt; StableFunctionMap &gt; FunctionMap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa10e68673eb85633ae54eea55841497f">PublishedHashTree</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global outlined hash tree that has oulined hash sequences across modules. <a href="#aa10e68673eb85633ae54eea55841497f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap">StableFunctionMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc525de317c1cc65f79dbfa9d189d58">PublishedStableFunctionMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global stable function map that has stable function info across modules. <a href="#a7cc525de317c1cc65f79dbfa9d189d58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1de6bb5642d04f0900ff0d30804f1aeb">EmitCGData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This flag is set when -fcodegen-data-generate is passed. <a href="#a1de6bb5642d04f0900ff0d30804f1aeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/codegendata">CodeGenData</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af860defbaa2aa3a19cd8e5ef4edb5aed">getInstance</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/codegendata">CodeGenData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4d3547aeda52b43e324c73db4de4408">Instance</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a singleton instance which is thread-safe. <a href="#ae4d3547aeda52b43e324c73db4de4408">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::once_flag</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fdd80928c30f380b9be40cf601af7f6">OnceFlag</a></td>
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


<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### CodeGenData() {#ab4abbcc1c3904b0c438b4cac811776a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CodeGenData::CodeGenData ()</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CodeGenData() {#a9a9b6539320e312559d38149f9cc3e19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CodeGenData::~CodeGenData ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitCGData() {#a1c2334570aeb5f51fc75d0ed0bba7768}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeGenData::emitCGData ()</td>
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

<p>Returns true if we should write codegen data.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#ad1a6f1d892a1ed8390de8835209b023b">llvm::cgdata::emitCGData</a>.</p>

</div>
</div>

### getOutlinedHashTree() {#a8e5f32b1f85714a5fb918833048c04d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const OutlinedHashTree * llvm::CodeGenData::getOutlinedHashTree ()</td>
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

<p>Returns the outlined hash tree.</p>


<p>This can be globally used in a read-only manner.</p>


<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a5f779cac580e35591c444da3941d46f3">llvm::cgdata::getOutlinedHashTree</a>.</p>

</div>
</div>

### getStableFunctionMap() {#a0ca8e548ef9d5c9ea700ef5ca967affd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StableFunctionMap * llvm::CodeGenData::getStableFunctionMap ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#ae5dbda3760db631f85dcce8129a067c5">llvm::cgdata::getStableFunctionMap</a>.</p>

</div>
</div>

### hasOutlinedHashTree() {#a743f557723374e2edf31ae04673b653a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeGenData::hasOutlinedHashTree ()</td>
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

<p>Returns true if we have a valid outlined hash tree.</p>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a429cd542137f6930d904d70bc864c451">llvm::cgdata::hasOutlinedHashTree</a>.</p>

</div>
</div>

### hasStableFunctionMap() {#a0074654a63d2717448e3ca65fb166b38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeGenData::hasStableFunctionMap ()</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a566a3c31a37bef40996854be6a8d68e3">llvm::cgdata::hasStableFunctionMap</a>.</p>

</div>
</div>

### publishOutlinedHashTree() {#a565722c191eaf11d0247efe5104c4db8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenData::publishOutlinedHashTree (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a> &gt; HashTree)</td>
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

<p>Publish the (globally) merged or read outlined hash tree.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a2868ab61a4ce104901a8f12be4dbbf40">llvm::cgdata::publishOutlinedHashTree</a>.</p>

</div>
</div>

### publishStableFunctionMap() {#af1cd6547aef00b0dcd2f15e3e7fb954b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenData::publishStableFunctionMap (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap">StableFunctionMap</a> &gt; FunctionMap)</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a816930fb508497c770b4fe53b5757541">llvm::cgdata::publishStableFunctionMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EmitCGData {#a1de6bb5642d04f0900ff0d30804f1aeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeGenData::EmitCGData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This flag is set when -fcodegen-data-generate is passed.</p>


<p>Or, it can be mutated with -fcodegen-data-thinlto-two-rounds.</p>


<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>

</div>
</div>

### PublishedHashTree {#aa10e68673eb85633ae54eea55841497f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;OutlinedHashTree&gt; llvm::CodeGenData::PublishedHashTree</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Global outlined hash tree that has oulined hash sequences across modules.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>

</div>
</div>

### PublishedStableFunctionMap {#a7cc525de317c1cc65f79dbfa9d189d58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;StableFunctionMap&gt; llvm::CodeGenData::PublishedStableFunctionMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Global stable function map that has stable function info across modules.</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getInstance() {#af860defbaa2aa3a19cd8e5ef4edb5aed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeGenData &amp; llvm::CodeGenData::getInstance ()</td>
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



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp">CodeGenData.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp/#a7cb94a17c6e0104702ff3c8fd9fab8f2">CodeGenDataGenerate</a>, <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp/#a477832f90e9c98e1d9c574aa7a599d62">CodeGenDataThinLTOTwoRounds</a>, <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp/#a6a7851e11614b6c08d4326e58b2ec744">CodeGenDataUsePath</a>, <a href="/web-llvm/docs/api/classes/llvm/codegendatareader/#a4a44372ad9be897766236ba844f560e5">llvm::CodeGenDataReader::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfs/#a9878c6a5a53d24e17c7c1002be31364c">llvm::vfs::getRealFileSystem</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a594febf895e59fe42257c1d2918c4f65">llvm::cgdata::warn</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#ad1a6f1d892a1ed8390de8835209b023b">llvm::cgdata::emitCGData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a5f779cac580e35591c444da3941d46f3">llvm::cgdata::getOutlinedHashTree</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#ae5dbda3760db631f85dcce8129a067c5">llvm::cgdata::getStableFunctionMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a429cd542137f6930d904d70bc864c451">llvm::cgdata::hasOutlinedHashTree</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a566a3c31a37bef40996854be6a8d68e3">llvm::cgdata::hasStableFunctionMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a2868ab61a4ce104901a8f12be4dbbf40">llvm::cgdata::publishOutlinedHashTree</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a816930fb508497c770b4fe53b5757541">llvm::cgdata::publishStableFunctionMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### Instance {#ae4d3547aeda52b43e324c73db4de4408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; CodeGenData &gt; llvm::CodeGenData::Instance = nullptr</td>
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

<p>This is a singleton instance which is thread-safe.</p>


<p>Unlike profile data which is largely function-based, codegen data describes the whole module. Therefore, this can be initialized once, and can be used across modules instead of constructing the same one for each codegen backend.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>

</div>
</div>

### OnceFlag {#a4fdd80928c30f380b9be40cf601af7f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::once_flag llvm::CodeGenData::OnceFlag</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp">CodeGenData.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
