---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/remark
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Remark` Struct Reference

<p>A remark type used for both emission and parsing. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::Remark { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">llvm/Remarks/Remark.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac746d9c321346adc9f143c9b98cb9f4e">Remark</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6121801df7ce976e11c2b89a50f4f452">Remark</a> (Remark &amp;&amp;)=default</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73dc8f90db29215856a4d5cbcb631db7">Remark</a> (const Remark &amp;)=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In order to avoid unwanted copies, "delete" the copy constructor. <a href="#a73dc8f90db29215856a4d5cbcb631db7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd514bb9096260febe64c59b7cab97ac">operator=</a> (Remark &amp;&amp;)=default</td>
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

## Private Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a036bd4934013ae30eef74abe89b504">operator=</a> (const Remark &amp;)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b2a0203ac8a36329ff05b5b4d779015">getArgsAsMsg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a message composed from the arguments as a string. <a href="#a9b2a0203ac8a36329ff05b5b4d779015">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a874b998ebd5a2b7ee061e3969c47b2b3">clone</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone this remark to explicitly ask for a copy. <a href="#a874b998ebd5a2b7ee061e3969c47b2b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f22e6d1a356f8354fb13fba1850d831">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement operator&lt;&lt; on <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a>. <a href="#a0f22e6d1a356f8354fb13fba1850d831">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527f">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a241d25fa7a832abc5c8583bc728ec1f1">RemarkType</a> = <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527fa88183b946cc5f0e8c96b2e66e1c74a7e">Type::Unknown</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type of the remark. <a href="#a241d25fa7a832abc5c8583bc728ec1f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35431065aaa52c0d81d719b2468697ed">PassName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Name of the pass that triggers the emission of this remark. <a href="#a35431065aaa52c0d81d719b2468697ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8560e9790fc6522f5ac5ec7e4e3e1f95">RemarkName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Textual identifier for the remark (single-word, camel-case). <a href="#a8560e9790fc6522f5ac5ec7e4e3e1f95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa22dc5b75c24c27c88fda7c86be9e16a">FunctionName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mangled name of the function that triggers the emssion of this remark. <a href="#aa22dc5b75c24c27c88fda7c86be9e16a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/remarklocation">RemarkLocation</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a357123bac089573c87522957e3eb12e3">Loc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The location in the source file of the remark. <a href="#a357123bac089573c87522957e3eb12e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55696a404b259163add62a3fc346de3b">Hotness</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If profile information is available, this is the number of times the corresponding code was executed in a profile instrumentation run. <a href="#a55696a404b259163add62a3fc346de3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/argument">Argument</a>, 5 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad43b86418150167e66360c78b004daae">Args</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Arguments collected via the streaming interface. <a href="#ad43b86418150167e66360c78b004daae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A remark type used for both emission and parsing.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Remark() {#ac746d9c321346adc9f143c9b98cb9f4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::Remark::Remark ()</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<p>Referenced by <a href="#a874b998ebd5a2b7ee061e3969c47b2b3">clone</a>, <a href="#acd514bb9096260febe64c59b7cab97ac">operator=</a> and <a href="#a6121801df7ce976e11c2b89a50f4f452">Remark</a>.</p>

</div>
</div>

### Remark() {#a6121801df7ce976e11c2b89a50f4f452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::Remark::Remark (<a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &amp;&amp;)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<p>Reference <a href="#ac746d9c321346adc9f143c9b98cb9f4e">Remark</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### Remark() {#a73dc8f90db29215856a4d5cbcb631db7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::Remark::Remark (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &amp;)</td>
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

<p>In order to avoid unwanted copies, "delete" the copy constructor.</p>


<p>If a copy is needed, it should be done through <span class="doxyComputerOutput"><a href="#a874b998ebd5a2b7ee061e3969c47b2b3">Remark::clone()</a></span>.</p>


<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#acd514bb9096260febe64c59b7cab97ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Remark &amp; llvm::remarks::Remark::operator= (<a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &amp;&amp;)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<p>Reference <a href="#ac746d9c321346adc9f143c9b98cb9f4e">Remark</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Operators

### operator=() {#a9a036bd4934013ae30eef74abe89b504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Remark &amp; llvm::remarks::Remark::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &amp;)</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#a874b998ebd5a2b7ee061e3969c47b2b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Remark llvm::remarks::Remark::clone ()</td>
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

<p>Clone this remark to explicitly ask for a copy.</p>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<p>Reference <a href="#ac746d9c321346adc9f143c9b98cb9f4e">Remark</a>.</p>

</div>
</div>

### getArgsAsMsg() {#a9b2a0203ac8a36329ff05b5b4d779015}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string Remark::getArgsAsMsg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a message composed from the arguments as a string.</p>

<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>Reference <a href="#ad43b86418150167e66360c78b004daae">Args</a>.</p>

</div>
</div>

### print() {#a0f22e6d1a356f8354fb13fba1850d831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Remark::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implement operator&lt;&lt; on <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a>.</p>

<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>References <a href="#ad43b86418150167e66360c78b004daae">Args</a>, <a href="#aa22dc5b75c24c27c88fda7c86be9e16a">FunctionName</a>, <a href="#a55696a404b259163add62a3fc346de3b">Hotness</a>, <a href="#a357123bac089573c87522957e3eb12e3">Loc</a>, <a href="#a35431065aaa52c0d81d719b2468697ed">PassName</a>, <a href="#a8560e9790fc6522f5ac5ec7e4e3e1f95">RemarkName</a>, <a href="#a241d25fa7a832abc5c8583bc728ec1f1">RemarkType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a333eb5e10055c6bf7e374c99d030149e">llvm::remarks::typeToStr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ac8f8b870c04ce286457d446e4a0a4444">llvm::remarks::operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Args {#ad43b86418150167e66360c78b004daae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Argument, 5&gt; llvm::remarks::Remark::Args</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Arguments collected via the streaming interface.</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#ad385e18cefeea744d80d4ab608dfd09d">llvm::remarks::BitstreamRemarkSerializerHelper::emitRemarkBlock</a>, <a href="#a9b2a0203ac8a36329ff05b5b4d779015">getArgsAsMsg</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#ac4d29f90f81ea8264f49bb0736faf1d0">llvm::remarks::YAMLRemarkParser::parseRemark</a> and <a href="#a0f22e6d1a356f8354fb13fba1850d831">print</a>.</p>

</div>
</div>

### FunctionName {#aa22dc5b75c24c27c88fda7c86be9e16a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::remarks::Remark::FunctionName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mangled name of the function that triggers the emssion of this remark.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#ad385e18cefeea744d80d4ab608dfd09d">llvm::remarks::BitstreamRemarkSerializerHelper::emitRemarkBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#ac4d29f90f81ea8264f49bb0736faf1d0">llvm::remarks::YAMLRemarkParser::parseRemark</a> and <a href="#a0f22e6d1a356f8354fb13fba1850d831">print</a>.</p>

</div>
</div>

### Hotness {#a55696a404b259163add62a3fc346de3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::remarks::Remark::Hotness</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If profile information is available, this is the number of times the corresponding code was executed in a profile instrumentation run.</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#ad385e18cefeea744d80d4ab608dfd09d">llvm::remarks::BitstreamRemarkSerializerHelper::emitRemarkBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#ac4d29f90f81ea8264f49bb0736faf1d0">llvm::remarks::YAMLRemarkParser::parseRemark</a> and <a href="#a0f22e6d1a356f8354fb13fba1850d831">print</a>.</p>

</div>
</div>

### Loc {#a357123bac089573c87522957e3eb12e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;RemarkLocation&gt; llvm::remarks::Remark::Loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The location in the source file of the remark.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#ad385e18cefeea744d80d4ab608dfd09d">llvm::remarks::BitstreamRemarkSerializerHelper::emitRemarkBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#ac4d29f90f81ea8264f49bb0736faf1d0">llvm::remarks::YAMLRemarkParser::parseRemark</a> and <a href="#a0f22e6d1a356f8354fb13fba1850d831">print</a>.</p>

</div>
</div>

### PassName {#a35431065aaa52c0d81d719b2468697ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::remarks::Remark::PassName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Name of the pass that triggers the emission of this remark.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#ad385e18cefeea744d80d4ab608dfd09d">llvm::remarks::BitstreamRemarkSerializerHelper::emitRemarkBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#ac4d29f90f81ea8264f49bb0736faf1d0">llvm::remarks::YAMLRemarkParser::parseRemark</a> and <a href="#a0f22e6d1a356f8354fb13fba1850d831">print</a>.</p>

</div>
</div>

### RemarkName {#a8560e9790fc6522f5ac5ec7e4e3e1f95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::remarks::Remark::RemarkName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Textual identifier for the remark (single-word, camel-case).</p>


<p>Can be used by external tools reading the output file for remarks to identify the remark.</p>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#ad385e18cefeea744d80d4ab608dfd09d">llvm::remarks::BitstreamRemarkSerializerHelper::emitRemarkBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#ac4d29f90f81ea8264f49bb0736faf1d0">llvm::remarks::YAMLRemarkParser::parseRemark</a> and <a href="#a0f22e6d1a356f8354fb13fba1850d831">print</a>.</p>

</div>
</div>

### RemarkType {#a241d25fa7a832abc5c8583bc728ec1f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type llvm::remarks::Remark::RemarkType = <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527fa88183b946cc5f0e8c96b2e66e1c74a7e">Type::Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type of the remark.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#ad385e18cefeea744d80d4ab608dfd09d">llvm::remarks::BitstreamRemarkSerializerHelper::emitRemarkBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#ac4d29f90f81ea8264f49bb0736faf1d0">llvm::remarks::YAMLRemarkParser::parseRemark</a> and <a href="#a0f22e6d1a356f8354fb13fba1850d831">print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
