---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeview/debugstringtablesubsectionref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DebugStringTableSubsectionRef` Class

<p>Represents a read-only view of a CodeView string table. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::codeview::DebugStringTableSubsectionRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugstringtablesubsection-h">llvm/DebugInfo/CodeView/DebugStringTableSubsection.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionref">DebugSubsectionRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac905d56c88d6c108d0aa45384740e76e">DebugStringTableSubsectionRef</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af981a356161e3b59a1f8a5bcaffaa2a4">initialize</a> (BinaryStreamRef Contents)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5029e1e658cdad46cadff17a42cc3545">initialize</a> (BinaryStreamReader &amp;Reader)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89f91fb97bacfa2e66d5f5b912a85304">getString</a> (uint32_t Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a202afaec75ecb8f7fb9ef645eda2d67d">valid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62b7aea34b28e2f818e6984ebdd735d5">getBuffer</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9059041187c9d19582453637fe6e1f0d">Stream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86642e21e28cc709e635f081ae9f9da3">classof</a> (const DebugSubsectionRef *S)</td>
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

<p>Represents a read-only view of a CodeView string table.</p>


<p>This is a very simple flat buffer consisting of null-terminated strings, where strings are retrieved by their offset in the buffer. <a href="/web-llvm/docs/api/classes/llvm/codeview/debugstringtablesubsectionref">DebugStringTableSubsectionRef</a> does not own the underlying storage for the buffer.</p>


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugstringtablesubsection-h">DebugStringTableSubsection.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DebugStringTableSubsectionRef() {#ac905d56c88d6c108d0aa45384740e76e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugStringTableSubsectionRef::DebugStringTableSubsectionRef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugstringtablesubsection-h">DebugStringTableSubsection.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debugstringtablesubsection-cpp">DebugStringTableSubsection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionref/#acca35ccd89314881b9924f28968ac872">llvm::codeview::DebugSubsectionRef::DebugSubsectionRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afafee465e31ac15d7b21d8ca9d6f5ac685">llvm::codeview::StringTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBuffer() {#a62b7aea34b28e2f818e6984ebdd735d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamRef llvm::codeview::DebugStringTableSubsectionRef::getBuffer ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugstringtablesubsection-h">DebugStringTableSubsection.h</a>.</p>

</div>
</div>

### getString() {#a89f91fb97bacfa2e66d5f5b912a85304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; DebugStringTableSubsectionRef::getString (uint32_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugstringtablesubsection-h">DebugStringTableSubsection.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debugstringtablesubsection-cpp">DebugStringTableSubsection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a1cbc5251f13ad42510760ed61c71e874">llvm::BinaryStreamReader::readCString</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#ab56b001a0bd245c9e73972be0ac5d593">llvm::BinaryStreamReader::setOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp/#a7dccd1a95b77bf5792bba098da658c60">convertOneChecksum</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlcrossmoduleimportssubsection/#ab42895970e4ba1faf321f15498ec80e3">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLCrossModuleImportsSubsection::fromCodeViewSubsection</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlframedatasubsection/#adbb271a35aa3f6d4d6209ed00bf1620b">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLFrameDataSubsection::fromCodeViewSubsection</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp/#a7a04a5d6f4e7be81af7a33aa3ba25a5e">getFileName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a6c8767d62827feb3a07578e10a648c8f">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#ab6dce4234dfed467146522a0c820df35">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>.</p>

</div>
</div>

### initialize() {#af981a356161e3b59a1f8a5bcaffaa2a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DebugStringTableSubsectionRef::initialize (<a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> Contents)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugstringtablesubsection-h">DebugStringTableSubsection.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debugstringtablesubsection-cpp">DebugStringTableSubsection.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### initialize() {#a5029e1e658cdad46cadff17a42cc3545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DebugStringTableSubsectionRef::initialize (<a href="/web-llvm/docs/api/classes/llvm/binarystreamreader">BinaryStreamReader</a> &amp; Reader)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugstringtablesubsection-h">DebugStringTableSubsection.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debugstringtablesubsection-cpp">DebugStringTableSubsection.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a03bf40efbeb72552b33026fa1608280b">llvm::BinaryStreamReader::readStreamRef</a>.</p>

</div>
</div>

### valid() {#a202afaec75ecb8f7fb9ef645eda2d67d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codeview::DebugStringTableSubsectionRef::valid ()</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugstringtablesubsection-h">DebugStringTableSubsection.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Stream {#a9059041187c9d19582453637fe6e1f0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamRef llvm::codeview::DebugStringTableSubsectionRef::Stream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugstringtablesubsection-h">DebugStringTableSubsection.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a86642e21e28cc709e635f081ae9f9da3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codeview::DebugStringTableSubsectionRef::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionref">DebugSubsectionRef</a> * S)</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugstringtablesubsection-h">DebugStringTableSubsection.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionref/#acca35ccd89314881b9924f28968ac872">llvm::codeview::DebugSubsectionRef::DebugSubsectionRef</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionref/#a83bd49c4af0b650932ba2b257c67f94c">llvm::codeview::DebugSubsectionRef::kind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afafee465e31ac15d7b21d8ca9d6f5ac685">llvm::codeview::StringTable</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugstringtablesubsection-h">DebugStringTableSubsection.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debugstringtablesubsection-cpp">DebugStringTableSubsection.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
