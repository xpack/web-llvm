---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dbgvaluelocentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DbgValueLocEntry` Class

<p>A single location or constant within a variable location description, with either a single entry (with an optional <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a>) used for a DBG_VALUE, or a list of entries used for a DBG_VALUE_LIST. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DbgValueLocEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">CodeGen/AsmPrinter/DebugLocEntry.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EntryType { <a href="#aec56516bd74b34836bf3f0f9ddd213b4">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of entry that this represents. <a href="#aec56516bd74b34836bf3f0f9ddd213b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5158ac15e6015295f8861143288c4ad5">operator==</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two DbgValueLocEntries for equality. <a href="#a5158ac15e6015295f8861143288c4ad5">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f7054122edfc2db9e30692e42ec642c">DbgValueLocEntry</a> (int64_t i)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bc6b2aca9cb3942687e592e31649e98">DbgValueLocEntry</a> (const ConstantFP *CFP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad46bf6993fc7d622f9b42c109623d670">DbgValueLocEntry</a> (const ConstantInt *CIP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6be2ef82ac9b1217d94c7a425450c5c8">DbgValueLocEntry</a> (MachineLocation Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63694d856e119299ad4108742ebae78">DbgValueLocEntry</a> (TargetIndexLocation Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f6f7d65bd25e641c04243271b4aff73">isLocation</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97b46163f5073226d89e3d79d6e6d01a">isIndirectLocation</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbcca8de17c37b780668210be5dc44ae">isTargetIndexLocation</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4994e73b5a7e18715e6eab74b140a827">isInt</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cda313412468a4b7f820229fad30e88">isConstantFP</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7684b012fe30ece9cf61c0bde5374ae8">isConstantInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a508a1ab9fb7d2e3e141485ed524603e3">getInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f8f3fe9089e478dc82393df6ef0e1f6">getConstantFP</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9be550b6beb7b3395d1685e56121a27c">getConstantInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinelocation">MachineLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accea2636d97067c0cf09875b615e698d">getLoc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetindexlocation">TargetIndexLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21ea523fbf4f06ba82abf331fd6cb3b3">getTargetIndexLocation</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab45f19cc70d2f6377ac00b95472d762f">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a629e089e3b0e8835e3fd2098e1f80ce0">Int</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff7e779be50180be32ffa92fbac4ffd2">CFP</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33c74be2884a3875264b4773ff5a4ca9">CIP</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinelocation">MachineLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a241ab45b99f8935bf2419476c9ba4ed2">Loc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Or a location in the machine frame. <a href="#a241ab45b99f8935bf2419476c9ba4ed2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetindexlocation">TargetIndexLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82422008f1f34b14b8cde20c0ce9ac65">TIL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Or a location from target specific location. <a href="#a82422008f1f34b14b8cde20c0ce9ac65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum EntryType</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afee794eb06a0f117926b47ff5c618ae1">EntryKind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/dbgvaluelocentry">llvm::DbgValueLocEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bcbfc785e4232ef661734321523453a">Constant</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Either a constant,. <a href="#a5bcbfc785e4232ef661734321523453a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/dbgvaluelocentry">llvm::DbgValueLocEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a603f1e03ff8af4d86c50de8ff9574ac5"></a></td>
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

<p>A single location or constant within a variable location description, with either a single entry (with an optional <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a>) used for a DBG_VALUE, or a list of entries used for a DBG_VALUE_LIST.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### EntryType {#aec56516bd74b34836bf3f0f9ddd213b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::DbgValueLocEntry::EntryType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of entry that this represents.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">E_Location<a id="aec56516bd74b34836bf3f0f9ddd213b4a139d67a53517d66ac8bc585becdd2711"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">E_Integer<a id="aec56516bd74b34836bf3f0f9ddd213b4a0d363a8bbaac9c5bcf52adc211378af2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">E_ConstantFP<a id="aec56516bd74b34836bf3f0f9ddd213b4a1baf97c03f7a8bccfc204b2ebbc73e59"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">E_ConstantInt<a id="aec56516bd74b34836bf3f0f9ddd213b4a41a5e3ee0693c2261895763271f6f5f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">E_TargetIndexLocation<a id="aec56516bd74b34836bf3f0f9ddd213b4ad98ef3177fcc778b4f406dce2dfbfdc4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### operator== {#a5158ac15e6015295f8861143288c4ad5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvaluelocentry">DbgValueLocEntry</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvaluelocentry">DbgValueLocEntry</a> &amp; B</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compare two DbgValueLocEntries for equality.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a6f7054122edfc2db9e30692e42ec642c">DbgValueLocEntry</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DbgValueLocEntry() {#a6f7054122edfc2db9e30692e42ec642c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgValueLocEntry::DbgValueLocEntry (int64_t i)</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<p>Referenced by <a href="#a5158ac15e6015295f8861143288c4ad5">operator==</a>.</p>

</div>
</div>

### DbgValueLocEntry() {#a1bc6b2aca9cb3942687e592e31649e98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgValueLocEntry::DbgValueLocEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> * CFP)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<p>Reference <a href="#aff7e779be50180be32ffa92fbac4ffd2">CFP</a>.</p>

</div>
</div>

### DbgValueLocEntry() {#ad46bf6993fc7d622f9b42c109623d670}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgValueLocEntry::DbgValueLocEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * CIP)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<p>Reference <a href="#a33c74be2884a3875264b4773ff5a4ca9">CIP</a>.</p>

</div>
</div>

### DbgValueLocEntry() {#a6be2ef82ac9b1217d94c7a425450c5c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgValueLocEntry::DbgValueLocEntry (<a href="/web-llvm/docs/api/classes/llvm/machinelocation">MachineLocation</a> Loc)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<p>Reference <a href="#a241ab45b99f8935bf2419476c9ba4ed2">Loc</a>.</p>

</div>
</div>

### DbgValueLocEntry() {#af63694d856e119299ad4108742ebae78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgValueLocEntry::DbgValueLocEntry (<a href="/web-llvm/docs/api/structs/llvm/targetindexlocation">TargetIndexLocation</a> Loc)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<p>References <a href="#a241ab45b99f8935bf2419476c9ba4ed2">Loc</a> and <a href="#a82422008f1f34b14b8cde20c0ce9ac65">TIL</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#ab45f19cc70d2f6377ac00b95472d762f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void llvm::DbgValueLocEntry::dump ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a5cda313412468a4b7f820229fad30e88">isConstantFP</a>, <a href="#a7684b012fe30ece9cf61c0bde5374ae8">isConstantInt</a>, <a href="#a8f6f7d65bd25e641c04243271b4aff73">isLocation</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a241ab45b99f8935bf2419476c9ba4ed2">Loc</a>.</p>

</div>
</div>

### getConstantFP() {#a4f8f3fe9089e478dc82393df6ef0e1f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantFP * llvm::DbgValueLocEntry::getConstantFP ()</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>

</div>
</div>

### getConstantInt() {#a9be550b6beb7b3395d1685e56121a27c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantInt * llvm::DbgValueLocEntry::getConstantInt ()</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>

</div>
</div>

### getInt() {#a508a1ab9fb7d2e3e141485ed524603e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::DbgValueLocEntry::getInt ()</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>

</div>
</div>

### getLoc() {#accea2636d97067c0cf09875b615e698d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineLocation llvm::DbgValueLocEntry::getLoc ()</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<p>Reference <a href="#a241ab45b99f8935bf2419476c9ba4ed2">Loc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgvalueloc/#aed9e2c87c90de2626b7e97f055a36067">llvm::DbgValueLoc::isEquivalent</a>.</p>

</div>
</div>

### getTargetIndexLocation() {#a21ea523fbf4f06ba82abf331fd6cb3b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetIndexLocation llvm::DbgValueLocEntry::getTargetIndexLocation ()</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<p>Reference <a href="#a82422008f1f34b14b8cde20c0ce9ac65">TIL</a>.</p>

</div>
</div>

### isConstantFP() {#a5cda313412468a4b7f820229fad30e88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgValueLocEntry::isConstantFP ()</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<p>Referenced by <a href="#ab45f19cc70d2f6377ac00b95472d762f">dump</a>.</p>

</div>
</div>

### isConstantInt() {#a7684b012fe30ece9cf61c0bde5374ae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgValueLocEntry::isConstantInt ()</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<p>Referenced by <a href="#ab45f19cc70d2f6377ac00b95472d762f">dump</a>.</p>

</div>
</div>

### isIndirectLocation() {#a97b46163f5073226d89e3d79d6e6d01a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgValueLocEntry::isIndirectLocation ()</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<p>Reference <a href="#a241ab45b99f8935bf2419476c9ba4ed2">Loc</a>.</p>

</div>
</div>

### isInt() {#a4994e73b5a7e18715e6eab74b140a827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgValueLocEntry::isInt ()</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>

</div>
</div>

### isLocation() {#a8f6f7d65bd25e641c04243271b4aff73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgValueLocEntry::isLocation ()</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<p>Referenced by <a href="#ab45f19cc70d2f6377ac00b95472d762f">dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgvalueloc/#aed9e2c87c90de2626b7e97f055a36067">llvm::DbgValueLoc::isEquivalent</a>.</p>

</div>
</div>

### isTargetIndexLocation() {#abbcca8de17c37b780668210be5dc44ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgValueLocEntry::isTargetIndexLocation ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CFP {#aff7e779be50180be32ffa92fbac4ffd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantFP* llvm::DbgValueLocEntry::CFP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<p>Referenced by <a href="#a1bc6b2aca9cb3942687e592e31649e98">DbgValueLocEntry</a>.</p>

</div>
</div>

### CIP {#a33c74be2884a3875264b4773ff5a4ca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantInt* llvm::DbgValueLocEntry::CIP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<p>Referenced by <a href="#ad46bf6993fc7d622f9b42c109623d670">DbgValueLocEntry</a>.</p>

</div>
</div>

### Int {#a629e089e3b0e8835e3fd2098e1f80ce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::DbgValueLocEntry::Int</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>

</div>
</div>

### Loc {#a241ab45b99f8935bf2419476c9ba4ed2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineLocation llvm::DbgValueLocEntry::Loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Or a location in the machine frame.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<p>Referenced by <a href="#a6be2ef82ac9b1217d94c7a425450c5c8">DbgValueLocEntry</a>, <a href="#af63694d856e119299ad4108742ebae78">DbgValueLocEntry</a>, <a href="#ab45f19cc70d2f6377ac00b95472d762f">dump</a>, <a href="#accea2636d97067c0cf09875b615e698d">getLoc</a> and <a href="#a97b46163f5073226d89e3d79d6e6d01a">isIndirectLocation</a>.</p>

</div>
</div>

### TIL {#a82422008f1f34b14b8cde20c0ce9ac65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetIndexLocation llvm::DbgValueLocEntry::TIL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Or a location from target specific location.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>


<p>Referenced by <a href="#af63694d856e119299ad4108742ebae78">DbgValueLocEntry</a> and <a href="#a21ea523fbf4f06ba82abf331fd6cb3b3">getTargetIndexLocation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#a603f1e03ff8af4d86c50de8ff9574ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::DbgValueLocEntry llvm::DbgValueLocEntry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>

</div>
</div>

### Constant {#a5bcbfc785e4232ef661734321523453a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::DbgValueLocEntry llvm::DbgValueLocEntry::Constant</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Either a constant,.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>

</div>
</div>

### EntryKind {#afee794eb06a0f117926b47ff5c618ae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum EntryType llvm::DbgValueLocEntry::EntryKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debuglocentry-h">DebugLocEntry.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
