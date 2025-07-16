---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/basicsymbolref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BasicSymbolRef` Class Reference

<p>This is a value type class that represents a single symbol in the list of symbols in the object file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::object::BasicSymbolRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">llvm/Object/SymbolicFile.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a value type class that represents a single symbol in the list of symbols in the object file. <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Flags : unsigned { <a href="#a9004a106627deafd45a7c95ee497d431">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8d4ee7c02c28928d25ad12952e8e194">BasicSymbolRef</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52146f20cc758b8230ed868e895f272f">BasicSymbolRef</a> (DataRefImpl SymbolP, const SymbolicFile *Owner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9ffd34ae685ddff696fde4e98d7bb79">operator==</a> (const BasicSymbolRef &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac470b797232a954a8d9f7e8cce6e382e">operator&lt;</a> (const BasicSymbolRef &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add9e37c10e1b7c4c09a2ac44db71ef71">moveNext</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb578f951dd51151734393c1d07284df">printName</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b7c599b5884de1b379b53365685778">getFlags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get symbol flags (bitwise OR of <a href="#a9004a106627deafd45a7c95ee497d431">SymbolRef::Flags</a>) <a href="#a28b7c599b5884de1b379b53365685778">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4edbb76f7d11d8891e10524e40bdaa85">getRawDataRefImpl</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile">SymbolicFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a294f053bad4966edce6b5edb3697cb08">getObject</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f300ff6160a32be594bdeef5b493980">SymbolPimpl</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile">SymbolicFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af027d04c5f8c5173cadabd508ec79d7f">OwningObject</a> = nullptr</td>
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

<p>This is a value type class that represents a single symbol in the list of symbols in the object file.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Flags {#a9004a106627deafd45a7c95ee497d431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::object::BasicSymbolRef::Flags : unsigned</td>
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
<td class="doxyEnumItemName">SF_None<a id="a9004a106627deafd45a7c95ee497d431ad1cfe0c449b3dd82ae0eaeff1da6f766"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_Undefined<a id="a9004a106627deafd45a7c95ee497d431ad1131f10939b205635a0dc81ca3c45d7"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_Global<a id="a9004a106627deafd45a7c95ee497d431a1cc593ee22b60969ba0a3cb1e5e21b34"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_Weak<a id="a9004a106627deafd45a7c95ee497d431ac199a3dc25299a191397723e89fd303e"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_Absolute<a id="a9004a106627deafd45a7c95ee497d431acc6eb3e8d6f0fb38a6f3eb9ddef198af"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_Common<a id="a9004a106627deafd45a7c95ee497d431a917d4e0252fa1d20b2086b2e99e78e57"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_Indirect<a id="a9004a106627deafd45a7c95ee497d431a9660b615b36c70668b966e987719d9d6"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_Exported<a id="a9004a106627deafd45a7c95ee497d431a3936e16c4ba4b109e74006ad9bdc06f8"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_FormatSpecific<a id="a9004a106627deafd45a7c95ee497d431ac0848bf2e216fe6f4664820d93ab7265"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_Thumb<a id="a9004a106627deafd45a7c95ee497d431a586a24e61bc504778e4c89c8bb929e90"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_Hidden<a id="a9004a106627deafd45a7c95ee497d431a204140e5ce85b4dc444bf37cb0d8e402"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_Const<a id="a9004a106627deafd45a7c95ee497d431adb0e2612e20ba28b3b1fe8697f0b095a"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_Executable<a id="a9004a106627deafd45a7c95ee497d431a2d0d252cebc6c9ccac230cb8625d8d59"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 11)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BasicSymbolRef() {#ab8d4ee7c02c28928d25ad12952e8e194}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::BasicSymbolRef::BasicSymbolRef ()</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>


<p>References <a href="#ab8d4ee7c02c28928d25ad12952e8e194">BasicSymbolRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>


<p>Referenced by <a href="#ab8d4ee7c02c28928d25ad12952e8e194">BasicSymbolRef</a>, <a href="#ac470b797232a954a8d9f7e8cce6e382e">operator&lt;</a>, <a href="#aa9ffd34ae685ddff696fde4e98d7bb79">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a3916a0c57c63d466f8f9aee459b5ab8d">llvm::object::SymbolRef::SymbolRef</a> and <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#ad38b7b052df6e4d4d0efc9b3372b9ea6">llvm::object::SymbolRef::SymbolRef</a>.</p>

</div>
</div>

### BasicSymbolRef() {#a52146f20cc758b8230ed868e895f272f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::BasicSymbolRef::BasicSymbolRef (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> SymbolP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile">SymbolicFile</a> * Owner)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#ac470b797232a954a8d9f7e8cce6e382e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::BasicSymbolRef::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref">BasicSymbolRef</a> &amp; Other)</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>


<p>References <a href="#ab8d4ee7c02c28928d25ad12952e8e194">BasicSymbolRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator==() {#aa9ffd34ae685ddff696fde4e98d7bb79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::BasicSymbolRef::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref">BasicSymbolRef</a> &amp; Other)</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>


<p>References <a href="#ab8d4ee7c02c28928d25ad12952e8e194">BasicSymbolRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFlags() {#a28b7c599b5884de1b379b53365685778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint32_t &gt; llvm::object::BasicSymbolRef::getFlags ()</td>
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

<p>Get symbol flags (bitwise OR of <a href="#a9004a106627deafd45a7c95ee497d431">SymbolRef::Flags</a>)</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a903f7954a46ba31474ad9e0c7ccfbed3">isArchiveSymbol</a>.</p>

</div>
</div>

### getObject() {#a294f053bad4966edce6b5edb3697cb08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SymbolicFile * llvm::object::BasicSymbolRef::getObject ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elfsymbolref/#a2285d03995b7c7455fb2ff328c05aaad">llvm::object::ELFSymbolRef::getObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/goffsymbolref/#a94874fd6e295e61d482d922277f70e44">llvm::object::GOFFSymbolRef::getObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#aa08bcfd0fd633889120aa52eb115f3fb">llvm::object::SymbolRef::getObject</a> and <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a3916a0c57c63d466f8f9aee459b5ab8d">llvm::object::SymbolRef::SymbolRef</a>.</p>

</div>
</div>

### getRawDataRefImpl() {#a4edbb76f7d11d8891e10524e40bdaa85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataRefImpl llvm::object::BasicSymbolRef::getRawDataRefImpl ()</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#ac22d03239bd28b53a229486b43a9d3b8">llvm::object::SymbolRef::getAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a964202e1e17cee946ac67303dd34a9a2">llvm::object::SymbolRef::getAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfsymbolref/#a7cc4fe71d834ddfcc6981f15b43ba100">llvm::object::ELFSymbolRef::getBinding</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#afc6576af9f6c428aaeb91be518ef565d">llvm::object::SymbolRef::getCommonSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfsymbolref/#a2d021019938a83613dc66fad533adcfc">llvm::object::ELFSymbolRef::getELFType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#af12e28a6a9862376cd2e440636d6dfac">llvm::object::XCOFFSymbolRef::getEntryAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a6935271c0f6df1209adbb91f2f68d2c1">llvm::object::SymbolRef::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfsymbolref/#a226b51dd73c554ff4c2960696682c0ca">llvm::object::ELFSymbolRef::getOther</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#ab5019ff9e3502f422f3d8668201f5756">llvm::object::ELFObjectFileBase::getPltEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#af8b31890b3cf3677a9c279325661e3af">llvm::object::SymbolRef::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfsymbolref/#a8549874db03a19df5cb846d78eddf383">llvm::object::ELFSymbolRef::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/goffsymbolref/#a8a4e84689782b32f69468f1c05002ea1">llvm::object::GOFFSymbolRef::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a38013df05132b768d4980f709b43b2ee">llvm::object::XCOFFSymbolRef::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a505d506a424234d98ea617f60f69ddb3">llvm::object::XCOFFSymbolRef::getSymbol32</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a421328a37b7de6fbb9712ec550d131a6">llvm::object::XCOFFSymbolRef::getSymbol64</a>, <a href="/web-llvm/docs/api/classes/llvm/object/goffsymbolref/#a6783b2c89a3c8000e5c7f387b0954e36">llvm::object::GOFFSymbolRef::getSymbolGOFFFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/object/goffsymbolref/#a170671a54f2db288bb608b1e18d1478d">llvm::object::GOFFSymbolRef::getSymbolGOFFType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#adeefe77eeb81c0dfee4bb876927e90c8">llvm::object::COFFObjectFile::getSymbolSectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a2f79817cbc7f06dd7a434e20281a0ad5">llvm::object::MachOObjectFile::getSymbolSectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a71d6474e0580f137735002afb39321c4">llvm::object::XCOFFObjectFile::getSymbolSectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a234b2c90b26a44886a6f04c4281b1b65">llvm::object::SymbolRef::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#aefbba218ff811c972e66adacb950989c">llvm::object::SymbolRef::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#aa08b0ee12e4396d3b0b4f50863064f4a">llvm::object::XCOFFSymbolRef::getValue32</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#acb2d20e7ebc4ca9471bad9a00ed0b230">llvm::object::XCOFFSymbolRef::getValue64</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a6b97101d75c9c68d1d2cdcbe733cb80c">llvm::object::WasmObjectFile::getWasmSymbol</a> and <a href="/web-llvm/docs/api/classes/anonymous-runtimedyldelf-cpp-/dyldelfobject/#affb416a373e2586e69aaf93b7b9da3f3">anonymous{RuntimeDyldELF.cpp}::DyldELFObject&lt; ELFT &gt;::updateSymbolAddress</a>.</p>

</div>
</div>

### moveNext() {#add9e37c10e1b7c4c09a2ac44db71ef71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::BasicSymbolRef::moveNext ()</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>

</div>
</div>

### printName() {#abb578f951dd51151734393c1d07284df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::object::BasicSymbolRef::printName (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OwningObject {#af027d04c5f8c5173cadabd508ec79d7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SymbolicFile* llvm::object::BasicSymbolRef::OwningObject = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>

</div>
</div>

### SymbolPimpl {#a4f300ff6160a32be594bdeef5b493980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataRefImpl llvm::object::BasicSymbolRef::SymbolPimpl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
