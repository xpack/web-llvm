---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dbgvariable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DbgVariable` Class Reference

<p>This class is used to track local variable information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DbgVariable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">CodeGen/AsmPrinter/DwarfDebug.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgentity">DbgEntity</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is defined as the common parent of <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/dbglabel">DbgLabel</a> such that it could levarage polymorphism to extract common code for <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/dbglabel">DbgLabel</a>. <a href="/web-llvm/docs/api/classes/llvm/dbgentity/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Loc::Variant</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d3c7ed32eb87d635e9f17a2dd32a29b">DbgVariable</a> (const DILocalVariable *V, const DILocation *IA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a>. <a href="#a5d3c7ed32eb87d635e9f17a2dd32a29b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/loc/#aa1fa35229c3ab492b9ea826366f68350">Loc::Variant</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab98ba710c2a5b5f61bc8dda747a5e38">asVariant</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>To workaround P2162R0 <a href="https://github.com/cplusplus/papers/issues/873">https://github.com/cplusplus/papers/issues/873</a> the base class subobject needs to be passed directly to std::visit, so expose it directly here. <a href="#aab98ba710c2a5b5f61bc8dda747a5e38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/loc/#aa1fa35229c3ab492b9ea826366f68350">Loc::Variant</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14d349b52ea2add2e137a4c494518ee8">asVariant</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af65bc784e6fa32d1ef1d621d2082f082">holds</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Member shorthand for std::holds_alternative. <a href="#af65bc784e6fa32d1ef1d621d2082f082">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7c1c377b74fb349017110f3bc752befb">get</a> () noexcept</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Asserting, noexcept member alternative to std::get. <a href="#a7c1c377b74fb349017110f3bc752befb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> auto &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaa88dad357fd3d66122495f97f4c8088">get</a> () const noexcept</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Asserting, noexcept member alternative to std::get. <a href="#aaa88dad357fd3d66122495f97f4c8088">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f999918279bb2c923b2d35bec6fb01d">getVariable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8efc6ce71f8d82ec684a6de55040c088">getName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d9e9002e64cc718d5bdc179afe2b2a3">getTag</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1605e91e3bead92601f3b9b7e4c47a95">isArtificial</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a> is artificial. <a href="#a1605e91e3bead92601f3b9b7e4c47a95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37e1ead5d36eb33ba9093788422d4d6e">isObjectPointer</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d11876bae08f2f51fe5a8d76eaff58">getType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac479bcdf110bdc37a781338cb1e206b">classof</a> (const DbgEntity *N)</td>
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

<p>This class is used to track local variable information.</p>


<p>Variables that have been optimized out hold the <span class="doxyComputerOutput">monostate</span> alternative. This is not distinguished from the case of a constructed <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a></span> which has not be initialized yet.</p>


<p>Variables can be created from allocas, in which case they're generated from the MMI table. Such variables hold the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/loc/mmi">Loc::MMI</a></span> alternative which can have multiple expressions and frame indices.</p>


<p>Variables can be created from the entry value of registers, in which case they're generated from the MMI table. Such variables hold the <span class="doxyComputerOutput">EntryValueLoc</span> alternative which can either have a single expression or multiple <em>fragment</em> expressions.</p>


<p>Variables can be created from <span class="doxyComputerOutput">DBG_VALUE</span> instructions. Those whose location changes over time hold a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loc/multi">Loc::Multi</a></span> alternative which uses <span class="doxyComputerOutput">DebugLocListIndex</span> and (optionally) <span class="doxyComputerOutput">DebugLocListTagOffset</span>, while those with a single location hold a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loc/single">Loc::Single</a></span> alternative which use <span class="doxyComputerOutput">ValueLoc</span> and (optionally) a single <span class="doxyComputerOutput">Expr</span>.</p>


<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DbgVariable() {#a5d3c7ed32eb87d635e9f17a2dd32a29b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgVariable::DbgVariable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * IA)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a>.</p>


<p>Creates a variable without any DW_AT_location.</p>


<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dbgentity/#adea6ec515624a1a104a8cebee572d416">llvm::DbgEntity::DbgEntity</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgentity/#a843b2111402079a1de79db7ea3942351aae84a3833d80e9b44507b8ca5595a2ed">llvm::DbgEntity::DbgVariableKind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### asVariant() {#aab98ba710c2a5b5f61bc8dda747a5e38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loc::Variant &amp; llvm::DbgVariable::asVariant ()</td>
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

<p>To workaround P2162R0 <a href="https://github.com/cplusplus/papers/issues/873">https://github.com/cplusplus/papers/issues/873</a> the base class subobject needs to be passed directly to std::visit, so expose it directly here.</p>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a90e6b90f1ecca9999a225bac737d2fdc">llvm::DwarfCompileUnit::constructVariableDIE</a>.</p>

</div>
</div>

### asVariant() {#a14d349b52ea2add2e137a4c494518ee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Loc::Variant &amp; llvm::DbgVariable::asVariant ()</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### get() {#a7c1c377b74fb349017110f3bc752befb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto &amp; llvm::DbgVariable::get ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Asserting, noexcept member alternative to std::get.</p>

<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af65bc784e6fa32d1ef1d621d2082f082">holds</a>.</p>

</div>
</div>

### get() {#aaa88dad357fd3d66122495f97f4c8088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const auto &amp; llvm::DbgVariable::get ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Asserting, noexcept member alternative to std::get.</p>

<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> and <a href="#af65bc784e6fa32d1ef1d621d2082f082">holds</a>.</p>

</div>
</div>

### getName() {#a8efc6ce71f8d82ec684a6de55040c088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DbgVariable::getName ()</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/divariable/#af44724cae4bcd562972facee1cf035a5">llvm::DIVariable::getName</a> and <a href="#a3f999918279bb2c923b2d35bec6fb01d">getVariable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7f1c08f4c14daab9f9b9bd3502b0b384">llvm::DwarfCompileUnit::applyCommonDbgVariableAttributes</a>.</p>

</div>
</div>

### getTag() {#a1d9e9002e64cc718d5bdc179afe2b2a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Tag llvm::DbgVariable::getTag ()</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Reference <a href="#a3f999918279bb2c923b2d35bec6fb01d">getVariable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a90e6b90f1ecca9999a225bac737d2fdc">llvm::DwarfCompileUnit::constructVariableDIE</a>.</p>

</div>
</div>

### getType() {#aa6d11876bae08f2f51fe5a8d76eaff58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DIType * DbgVariable::getType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/divariable/#adab9179b79371579b407e31155a32366">llvm::DIVariable::getType</a> and <a href="#a3f999918279bb2c923b2d35bec6fb01d">getVariable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7f1c08f4c14daab9f9b9bd3502b0b384">llvm::DwarfCompileUnit::applyCommonDbgVariableAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp/#a5dcd4fc8ee34f9e83ef4c742f07bd909">dependencies</a>, <a href="#a1605e91e3bead92601f3b9b7e4c47a95">isArtificial</a> and <a href="#a37e1ead5d36eb33ba9093788422d4d6e">isObjectPointer</a>.</p>

</div>
</div>

### getVariable() {#a3f999918279bb2c923b2d35bec6fb01d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DILocalVariable * llvm::DbgVariable::getVariable ()</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgentity/#a87303a6c9dda72c2b68184698f3321d8">llvm::DbgEntity::getEntity</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarffile/#aa5f1a3100af547885ca5a51e5fc9466a">llvm::DwarfFile::addScopeVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7f1c08f4c14daab9f9b9bd3502b0b384">llvm::DwarfCompileUnit::applyCommonDbgVariableAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a90e6b90f1ecca9999a225bac737d2fdc">llvm::DwarfCompileUnit::constructVariableDIE</a>, <a href="#a8efc6ce71f8d82ec684a6de55040c088">getName</a>, <a href="#a1d9e9002e64cc718d5bdc179afe2b2a3">getTag</a>, <a href="#aa6d11876bae08f2f51fe5a8d76eaff58">getType</a>, <a href="#a1605e91e3bead92601f3b9b7e4c47a95">isArtificial</a> and <a href="#a37e1ead5d36eb33ba9093788422d4d6e">isObjectPointer</a>.</p>

</div>
</div>

### holds() {#af65bc784e6fa32d1ef1d621d2082f082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariable::holds ()</td>
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

<p>Member shorthand for std::holds_alternative.</p>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Referenced by <a href="#aaa88dad357fd3d66122495f97f4c8088">get</a> and <a href="#a7c1c377b74fb349017110f3bc752befb">get</a>.</p>

</div>
</div>

### isArtificial() {#a1605e91e3bead92601f3b9b7e4c47a95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariable::isArtificial ()</td>
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

<p>Return true if <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a> is artificial.</p>

<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>References <a href="#aa6d11876bae08f2f51fe5a8d76eaff58">getType</a>, <a href="#a3f999918279bb2c923b2d35bec6fb01d">getVariable</a> and <a href="#a1605e91e3bead92601f3b9b7e4c47a95">isArtificial</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7f1c08f4c14daab9f9b9bd3502b0b384">llvm::DwarfCompileUnit::applyCommonDbgVariableAttributes</a> and <a href="#a1605e91e3bead92601f3b9b7e4c47a95">isArtificial</a>.</p>

</div>
</div>

### isObjectPointer() {#a37e1ead5d36eb33ba9093788422d4d6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariable::isObjectPointer ()</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>References <a href="#aa6d11876bae08f2f51fe5a8d76eaff58">getType</a>, <a href="#a3f999918279bb2c923b2d35bec6fb01d">getVariable</a> and <a href="#a37e1ead5d36eb33ba9093788422d4d6e">isObjectPointer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4a09bbbcfe5fb24876e63ca5b05f45a8">llvm::DwarfCompileUnit::constructVariableDIE</a> and <a href="#a37e1ead5d36eb33ba9093788422d4d6e">isObjectPointer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#aac479bcdf110bdc37a781338cb1e206b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariable::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgentity">DbgEntity</a> * N)</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dbgentity/#adea6ec515624a1a104a8cebee572d416">llvm::DbgEntity::DbgEntity</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgentity/#a843b2111402079a1de79db7ea3942351aae84a3833d80e9b44507b8ca5595a2ed">llvm::DbgEntity::DbgVariableKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
