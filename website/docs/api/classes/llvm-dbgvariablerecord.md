---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dbgvariablerecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DbgVariableRecord` Class

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> of a variable value-assignment, aka a non instruction representation of the dbg.value intrinsic. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DbgVariableRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">llvm/IR/DebugProgramInstruction.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for non-instruction debug metadata records that have positions within IR. <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugvalueuser">DebugValueUser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for tracking ValueAsMetadata/DIArgLists with user lookups and Owner callbacks outside of <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata">ValueAsMetadata</a>. <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LocationType : uint8_t { <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4c">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb30cdf49f39c22df90faf961312a2cf">DebugValueUser</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d93b962edf730134f28184361570932">DbgVariableRecord</a> (const DbgVariableIntrinsic *DVI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> representing the intrinsic <span class="doxyComputerOutput">DVI</span>, for example the assignment represented by a dbg.value. <a href="#a0d93b962edf730134f28184361570932">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5a6c4942fc21c7c6c614a78b35747d1">DbgVariableRecord</a> (const DbgVariableRecord &amp;DVR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2254f7f4df1b9770fa98ca4ba39e868d">DbgVariableRecord</a> (Metadata *Location, DILocalVariable *DV, DIExpression *Expr, const DILocation *DI, LocationType Type=LocationType::Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Directly construct a new <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> representing a dbg.value intrinsic assigning <span class="doxyComputerOutput">Location</span> to the DV / Expr / DI variable. <a href="#a2254f7f4df1b9770fa98ca4ba39e868d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a39a6237c5fa48dc0577903cccc592">DbgVariableRecord</a> (Metadata *Value, DILocalVariable *Variable, DIExpression *Expression, DIAssignID *AssignID, Metadata *Address, DIExpression *AddressExpression, const DILocation *DI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fd6d13a11143ba6f61a797e9965dd2b">DbgVariableRecord</a> (LocationType Type, Metadata *Val, MDNode *Variable, MDNode *Expression, MDNode *AssignID, Metadata *Address, MDNode *AddressExpression, MDNode *DI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Private constructor for creating new instances during parsing only. <a href="#a5fd6d13a11143ba6f61a797e9965dd2b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1678dcac1aa0255429f8dcee4ffabd2">isDbgDeclare</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d537737d355256948200ba969a44637">isDbgValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/location-op-iterator">location_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd3574da4a2a86d1540dbdfcef171dd8">location_ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the locations corresponding to the variable referenced by the debug info intrinsic. <a href="#afd3574da4a2a86d1540dbdfcef171dd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99dac64e3a954ffbcbf1fc6726a743a2">getVariableLocationOp</a> (unsigned OpIdx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0ac412244054beacd97e316ded0fed3">replaceVariableLocationOp</a> (Value *OldValue, Value *NewValue, bool AllowEmpty=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61ce6eff43abf1cde49ddc11a5567646">replaceVariableLocationOp</a> (unsigned OpIdx, Value *NewValue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6d5d78fdfb9f1254c0471d2a3be0e65">addVariableLocationOps</a> (ArrayRef&lt; Value * &gt; NewValues, DIExpression *NewExpr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adding a new location operand will always result in this intrinsic using an ArgList, and must always be accompanied by a new expression that uses the new operand. <a href="#ab6d5d78fdfb9f1254c0471d2a3be0e65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd6da9d5bae0cbf845fe0016fcb4c9bb">getNumVariableLocationOps</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9c8103c773f2193dafee38239051d7b">hasArgList</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a340f78403c557e9021cbd9f006d56737">hasValidLocation</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> has no empty MDNodes in its location list. <a href="#a340f78403c557e9021cbd9f006d56737">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a637a15d148a2daafc86b1be17e01bca9">isAddressOfVariable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this describe the address of a local variable. <a href="#a637a15d148a2daafc86b1be17e01bca9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2979450e6f2a5a97c5437d5ba90f04e2">isValueOfVariable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this describes the value of a local variable. <a href="#a2979450e6f2a5a97c5437d5ba90f04e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4c">LocationType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1adb590f8f0ceed777898888ed5db7ac">getType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ec36aa642cfbc3756fab37cc97d0f86">setKillLocation</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49495d1f6880c856ab33832442a9e000">isKillLocation</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b176855918bd3a4e49e48ddb0d3660a">setVariable</a> (DILocalVariable *NewVar)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa774c62045e74bb457b32713c0670696">getVariable</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f421ee6c8aa855c30816913e794a4c7">getRawVariable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e803431f2ec29d9982f5cd7815712ee">setExpression</a> (DIExpression *NewExpr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ec5a479378113fc24b647afa2f06ee5">getExpression</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e0fc51827c21c4dd8f590d7cc4000db">getRawExpression</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9edb568c54e87f08484a5f46e399bee">getRawLocation</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the metadata operand for the first location description. <a href="#ab9edb568c54e87f08484a5f46e399bee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67997ed52b560aac60464dbdcd8cc3f0">getValue</a> (unsigned OpIdx=0) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a826d85216c59be98085f0d03882b9c83">setRawLocation</a> (Metadata *NewLocation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> of this should generally be avoided; instead, replaceVariableLocationOp and addVariableLocationOps should be used where possible to avoid creating invalid state. <a href="#a826d85216c59be98085f0d03882b9c83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/dbgvariablefragmentinfo">DbgVariableFragmentInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae446f360cb65e72ea25e919c540e7388">getFragment</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dbgvariablefragmentinfo">DbgVariableFragmentInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55a1b593c9b1b4f6ed599aae152d99be">getFragmentOrEntireVariable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the FragmentInfo for the variable if it exists, otherwise return a FragmentInfo that covers the entire variable if the variable size is known, otherwise return a zero-sized fragment. <a href="#a55a1b593c9b1b4f6ed599aae152d99be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a647883cb5d19b9519c0caf3b04e824be">getFragmentSizeInBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the size (in bits) of the variable, or fragment of the variable that is described. <a href="#a647883cb5d19b9519c0caf3b04e824be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dde296bd283de2e4e99758a44a2f2a6">isEquivalentTo</a> (const DbgVariableRecord &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae53d93dd6b3f1e5cc24506d2f4119625">isIdenticalToWhenDefined</a> (const DbgVariableRecord &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79a16a0ec88a38e513d42b64923cb8e2">clone</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic">DbgVariableIntrinsic</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad399adefaffab058aa56567aa1b59df9">createDebugIntrinsic</a> (Module *M, Instruction *InsertBefore) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert this <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> back into a dbg.value intrinsic. <a href="#ad399adefaffab058aa56567aa1b59df9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ef1641fd4bbca0fa6b8f3ca4ada2e5b">handleChangedLocation</a> (Metadata *NewLocation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle changes to the location of the <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value(s)</a> that we refer to happening "under our feet". <a href="#a8ef1641fd4bbca0fa6b8f3ca4ada2e5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3172de1fbc8c02b9b2cef0b24e3b558f">print</a> (raw_ostream &amp;O, bool IsForDebug=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad64862991023c01b0515a7d29716e6ad">print</a> (raw_ostream &amp;ROS, ModuleSlotTracker &amp;MST, bool IsForDebug) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4c">LocationType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3412d15543a66c3770500c3f2ba181c3">Type</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Classification of the debug-info record that this <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> represents. <a href="#a3412d15543a66c3770500c3f2ba181c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgrecordparamref">DbgRecordParamRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e369e92b13231538b232197d7b5e541">Variable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgrecordparamref">DbgRecordParamRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c0dfe59dcc53704c7a7191a3dff5689">Expression</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgrecordparamref">DbgRecordParamRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8cc02280e1ae435083375033d5f40bb">AddressExpression</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ff50e2cbdb1f0db4d0b133d03eea6c2">createUnresolvedDbgVariableRecord</a> (LocationType Type, Metadata *Val, MDNode *Variable, MDNode *Expression, MDNode *AssignID, Metadata *Address, MDNode *AddressExpression, MDNode *DI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to create DbgVariableRecords during parsing, where some metadata references may still be unresolved. <a href="#a7ff50e2cbdb1f0db4d0b133d03eea6c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb02462725b8625bd395f4fa53520ed4">createDVRAssign</a> (Value *Val, DILocalVariable *Variable, DIExpression *Expression, DIAssignID *AssignID, Value *Address, DIExpression *AddressExpression, const DILocation *DI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae465cfd07a3ac2e84847e670d92ae8ad">createLinkedDVRAssign</a> (Instruction *LinkedInstr, Value *Val, DILocalVariable *Variable, DIExpression *Expression, Value *Address, DIExpression *AddressExpression, const DILocation *DI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8337b222b982e9caf0f6226efb56039c">createDbgVariableRecord</a> (Value *Location, DILocalVariable *DV, DIExpression *Expr, const DILocation *DI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d7b7b90b3e3aa10243170c25d248f9e">createDbgVariableRecord</a> (Value *Location, DILocalVariable *DV, DIExpression *Expr, const DILocation *DI, DbgVariableRecord &amp;InsertBefore)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8461772cf63d3b043a673a75b6b95e39">createDVRDeclare</a> (Value *Address, DILocalVariable *DV, DIExpression *Expr, const DILocation *DI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06bd71d62590a4779e1645a292c0b58f">createDVRDeclare</a> (Value *Address, DILocalVariable *DV, DIExpression *Expr, const DILocation *DI, DbgVariableRecord &amp;InsertBefore)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6260338c62a9b3b75089e96997428ff">classof</a> (const DbgRecord *E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Support type inquiry through isa, cast, and dyn_cast. <a href="#ab6260338c62a9b3b75089e96997428ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## DbgAssign Methods Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e44c4d5de5d1134497e3ca3b922c535">isDbgAssign</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b5e9ae479c5eea5e6d9179a0c203da1">getAddress</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad76c901f38759f560144bafef2c598be">getRawAddress</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92bf6b19c53c3ebfa6045aaeacf6e24b">getRawAssignID</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4df534a195fe4df5fc7c2eaf2a96bd97">getAssignID</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa6b67c30dd439d0c3a04af3e81252e6">getAddressExpression</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56ed176f3945639483c3ff12214f3ce3">getRawAddressExpression</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a408bd8cb1829e740d4905ddac2a6c251">setAddressExpression</a> (DIExpression *NewExpr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8518bc959468abc1fcd62fadb427f45">setAssignId</a> (DIAssignID *New)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acae02d7d014e32fd2151b92bf57aeb12">setAddress</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b641aa0b6a8f401fff5ba3675467835">setKillAddress</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Kill the address component. <a href="#a9b641aa0b6a8f401fff5ba3675467835">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f1f03934ddcc92c01e8a83acaab39b2">isKillAddress</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this kills the address component. <a href="#a2f1f03934ddcc92c01e8a83acaab39b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> of a variable value-assignment, aka a non instruction representation of the dbg.value intrinsic.</p>


<p>This class inherits from <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser">DebugValueUser</a> to allow LLVM's metadata facilities to update our references to metadata beneath our feet.</p>


<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### LocationType {#ae2c3391c27b9fa4f64f9ed1bdbbdea4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::DbgVariableRecord::LocationType : uint8_t</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Declare<a id="ae2c3391c27b9fa4f64f9ed1bdbbdea4ca2709046ed364cc54b91f908e85e512ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Value<a id="ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Assign<a id="ae2c3391c27b9fa4f64f9ed1bdbbdea4ca185b7133db22230701a857c059360cc2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">End<a id="ae2c3391c27b9fa4f64f9ed1bdbbdea4ca87557f11575c0ad78e4e28abedc13b6e"></a></td>
<td class="doxyEnumItemDescription">Marks the end of the concrete types</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Any<a id="ae2c3391c27b9fa4f64f9ed1bdbbdea4caed36a1ef76a59ee3f15180e0441188ad"></a></td>
<td class="doxyEnumItemDescription">To indicate all LocationTypes in searches</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DebugValueUser {#adb30cdf49f39c22df90faf961312a2cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser">DebugValueUser</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#adb30cdf49f39c22df90faf961312a2cf">DebugValueUser</a>.</p>


<p>Referenced by <a href="#a0d93b962edf730134f28184361570932">DbgVariableRecord</a>, <a href="#ad5a6c4942fc21c7c6c614a78b35747d1">DbgVariableRecord</a>, <a href="#a2254f7f4df1b9770fa98ca4ba39e868d">DbgVariableRecord</a>, <a href="#ab9a39a6237c5fa48dc0577903cccc592">DbgVariableRecord</a> and <a href="#adb30cdf49f39c22df90faf961312a2cf">DebugValueUser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DbgVariableRecord() {#a0d93b962edf730134f28184361570932}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgVariableRecord::DbgVariableRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic">DbgVariableIntrinsic</a> * DVI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> representing the intrinsic <span class="doxyComputerOutput">DVI</span>, for example the assignment represented by a dbg.value.</p>

<p>Declaration at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a269e66beb08d4b146aa23deb49f5f640">llvm::DbgRecord::DbgRecord</a>, <a href="#adb30cdf49f39c22df90faf961312a2cf">DebugValueUser</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a3a0f4e00c3f6345c52c6acd178b3fca3">llvm::DbgRecord::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a753c375d2c90d5f7e04af2ea99648ac3">llvm::DbgVariableIntrinsic::getRawLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a887a873e264b58ebc609ffc62b4372bca75e74fbe10c9a9d133941a96309c178b">llvm::DbgRecord::ValueKind</a>.</p>


<p>Referenced by <a href="#a79a16a0ec88a38e513d42b64923cb8e2">clone</a>, <a href="#a8337b222b982e9caf0f6226efb56039c">createDbgVariableRecord</a>, <a href="#a3d7b7b90b3e3aa10243170c25d248f9e">createDbgVariableRecord</a>, <a href="#acb02462725b8625bd395f4fa53520ed4">createDVRAssign</a>, <a href="#a8461772cf63d3b043a673a75b6b95e39">createDVRDeclare</a>, <a href="#a06bd71d62590a4779e1645a292c0b58f">createDVRDeclare</a>, <a href="#ae465cfd07a3ac2e84847e670d92ae8ad">createLinkedDVRAssign</a>, <a href="#a7ff50e2cbdb1f0db4d0b133d03eea6c2">createUnresolvedDbgVariableRecord</a>, <a href="#ad5a6c4942fc21c7c6c614a78b35747d1">DbgVariableRecord</a>, <a href="#a0dde296bd283de2e4e99758a44a2f2a6">isEquivalentTo</a> and <a href="#ae53d93dd6b3f1e5cc24506d2f4119625">isIdenticalToWhenDefined</a>.</p>

</div>
</div>

### DbgVariableRecord() {#ad5a6c4942fc21c7c6c614a78b35747d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgVariableRecord::DbgVariableRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> &amp; DVR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#af8cc02280e1ae435083375033d5f40bb">AddressExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a269e66beb08d4b146aa23deb49f5f640">llvm::DbgRecord::DbgRecord</a>, <a href="#a0d93b962edf730134f28184361570932">DbgVariableRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser/#ab9d0079a3383c1716114943006e2d0f3">llvm::DebugValueUser::DebugValues</a>, <a href="#adb30cdf49f39c22df90faf961312a2cf">DebugValueUser</a>, <a href="#a1c0dfe59dcc53704c7a7191a3dff5689">Expression</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a3a0f4e00c3f6345c52c6acd178b3fca3">llvm::DbgRecord::getDebugLoc</a>, <a href="#a8ec5a479378113fc24b647afa2f06ee5">getExpression</a>, <a href="#a1adb590f8f0ceed777898888ed5db7ac">getType</a>, <a href="#aa774c62045e74bb457b32713c0670696">getVariable</a>, <a href="#a3412d15543a66c3770500c3f2ba181c3">Type</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a887a873e264b58ebc609ffc62b4372bca75e74fbe10c9a9d133941a96309c178b">llvm::DbgRecord::ValueKind</a> and <a href="#a3e369e92b13231538b232197d7b5e541">Variable</a>.</p>

</div>
</div>

### DbgVariableRecord() {#a2254f7f4df1b9770fa98ca4ba39e868d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgVariableRecord::DbgVariableRecord (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Location, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * DV, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DI, <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4c">LocationType</a> Type=<a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">LocationType::Value</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Directly construct a new <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> representing a dbg.value intrinsic assigning <span class="doxyComputerOutput">Location</span> to the DV / Expr / DI variable.</p>

<p>Declaration at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a269e66beb08d4b146aa23deb49f5f640">llvm::DbgRecord::DbgRecord</a>, <a href="#adb30cdf49f39c22df90faf961312a2cf">DebugValueUser</a>, <a href="#a3412d15543a66c3770500c3f2ba181c3">Type</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a887a873e264b58ebc609ffc62b4372bca75e74fbe10c9a9d133941a96309c178b">llvm::DbgRecord::ValueKind</a>.</p>

</div>
</div>

### DbgVariableRecord() {#ab9a39a6237c5fa48dc0577903cccc592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgVariableRecord::DbgVariableRecord (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Value, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Variable, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expression, <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> * AssignID, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Address, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * AddressExpression, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="#af8cc02280e1ae435083375033d5f40bb">AddressExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a269e66beb08d4b146aa23deb49f5f640">llvm::DbgRecord::DbgRecord</a>, <a href="#adb30cdf49f39c22df90faf961312a2cf">DebugValueUser</a>, <a href="#a1c0dfe59dcc53704c7a7191a3dff5689">Expression</a>, <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a887a873e264b58ebc609ffc62b4372bca75e74fbe10c9a9d133941a96309c178b">llvm::DbgRecord::ValueKind</a> and <a href="#a3e369e92b13231538b232197d7b5e541">Variable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### DbgVariableRecord() {#a5fd6d13a11143ba6f61a797e9965dd2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgVariableRecord::DbgVariableRecord (<a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4c">LocationType</a> Type, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Variable, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Expression, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * AssignID, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Address, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * AddressExpression, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * DI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Private constructor for creating new instances during parsing only.</p>


<p>Only called through <span class="doxyComputerOutput">createUnresolvedDbgVariableRecord</span> below, which makes clear that this is used for parsing only, and will later return a subclass depending on which <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> is passed.</p>


<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addVariableLocationOps() {#ab6d5d78fdfb9f1254c0471d2a3be0e65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableRecord::addVariableLocationOps (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; NewValues, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * NewExpr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adding a new location operand will always result in this intrinsic using an ArgList, and must always be accompanied by a new expression that uses the new operand.</p>

<p>Declaration at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/diarglist/#a51072a9980c37f5cce2a30e9dc4b3057">llvm::DIArgList::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67e80dcdf6a5358a9d3defbe0e8f6c34">llvm::getAsMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#aeeca41a71460985e42575296d3546044">llvm::DbgRecord::getContext</a>, <a href="#acd6da9d5bae0cbf845fe0016fcb4c9bb">getNumVariableLocationOps</a>, <a href="#a99dac64e3a954ffbcbf1fc6726a743a2">getVariableLocationOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="#afd3574da4a2a86d1540dbdfcef171dd8">location_ops</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a8e803431f2ec29d9982f5cd7815712ee">setExpression</a>, <a href="#a826d85216c59be98085f0d03882b9c83">setRawLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### clone() {#a79a16a0ec88a38e513d42b64923cb8e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgVariableRecord * llvm::DbgVariableRecord::clone ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>Reference <a href="#a0d93b962edf730134f28184361570932">DbgVariableRecord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ad19c7559d6302321172436f45c771171">insertDbgVariableRecordsForPHIs</a>.</p>

</div>
</div>

### createDebugIntrinsic() {#ad399adefaffab058aa56567aa1b59df9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgVariableIntrinsic * llvm::DbgVariableRecord::createDebugIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertBefore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert this <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> back into a dbg.value intrinsic.</p>


<p><span class="doxyComputerOutput">InsertBefore</span> Optional position to insert this intrinsic.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A new dbg.value intrinsic representiung this <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a>.</p></dd>
</dl>


<p>Declaration at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4caed36a1ef76a59ee3f15180e0441188ad">Any</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca185b7133db22230701a857c059360cc2">Assign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#aa04721251be00370fbde6d21f47fed1a">llvm::CallInst::Create</a>, <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca2709046ed364cc54b91f908e85e512ed">Declare</a>, <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca87557f11575c0ad78e4e28abedc13b6e">End</a>, <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#a3188a1aa0df768d8f254cd8d8fdeface">llvm::MetadataAsValue::get</a>, <a href="#afa6b67c30dd439d0c3a04af3e81252e6">getAddressExpression</a>, <a href="#a4df534a195fe4df5fc7c2eaf2a96bd97">getAssignID</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a3a0f4e00c3f6345c52c6acd178b3fca3">llvm::DbgRecord::getDebugLoc</a>, <a href="#a8ec5a479378113fc24b647afa2f06ee5">getExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a21075305f0e463b24aafc2fb99514ace">llvm::Function::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="#ad76c901f38759f560144bafef2c598be">getRawAddress</a>, <a href="#ab9edb568c54e87f08484a5f46e399bee">getRawLocation</a>, <a href="#a1adb590f8f0ceed777898888ed5db7ac">getType</a>, <a href="#aa774c62045e74bb457b32713c0670696">getVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>, <a href="#a8e44c4d5de5d1134497e3ca3b922c535">isDbgAssign</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#acff66a4cb0efaafb728848edf097c75f">llvm::CallInst::setTailCall</a> and <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a>.</p>

</div>
</div>

### getExpression() {#a8ec5a479378113fc24b647afa2f06ee5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * llvm::DbgVariableRecord::getExpression ()</td>
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



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#a1c0dfe59dcc53704c7a7191a3dff5689">Expression</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4ad92667dcad9ad33a52a2e1c505a03a">buildOverlapMapAndRecordDeclares</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a07a576318c1a362676e2d4ff00b921bb">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59e94595f29a0adde822a318f82dac61">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82984d4a91e7dc2072dfd8fad2854618">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="#ad399adefaffab058aa56567aa1b59df9">createDebugIntrinsic</a>, <a href="#ad5a6c4942fc21c7c6c614a78b35747d1">DbgVariableRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ac10429a8c82694552d49e1aba0b85491">DbgVariableRecordsRemoveRedundantDbgInstrsUsingBackwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ad4fea0532db5a2d88aadc8ca450eba93">getAddressExpression</a>, <a href="#ae446f360cb65e72ea25e919c540e7388">getFragment</a>, <a href="#a647883cb5d19b9519c0caf3b04e824be">getFragmentSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a52bb01c018d9c9a9bda3d127ab5c7189">llvm::FastISel::handleDbgInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ffbb17abf202aabdbb70f00a84905c9">llvm::InsertDebugValueAtStoreLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#abf39bad779191e6a85e053be5111c399">insertNewDbgInst</a>, <a href="#a49495d1f6880c856ab33832442a9e000">isKillLocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#afa1f83e099867326b23c359030bbb103">llvm::coro::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a05d7d91d31a8121c140a4da8645c6474">valueCoversEntireFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#a943584f0c65b24cfb9cbbca6d86fa75a">llvm::ValueEnumerator::ValueEnumerator</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a196df57d98a1307c0ced654a8e1d202b">llvm::SelectionDAGBuilder::visitDbgInfo</a>.</p>

</div>
</div>

### getFragment() {#ae446f360cb65e72ea25e919c540e7388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DbgVariableFragmentInfo &gt; llvm::DbgVariableRecord::getFragment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#a8ec5a479378113fc24b647afa2f06ee5">getExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a7cc5f1632a4c520497898439c17dc026">llvm::DIExpression::getFragmentInfo</a>.</p>


<p>Referenced by <a href="#a55a1b593c9b1b4f6ed599aae152d99be">getFragmentOrEntireVariable</a>.</p>

</div>
</div>

### getFragmentOrEntireVariable() {#a55a1b593c9b1b4f6ed599aae152d99be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgVariableFragmentInfo llvm::DbgVariableRecord::getFragmentOrEntireVariable ()</td>
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

<p>Get the FragmentInfo for the variable if it exists, otherwise return a FragmentInfo that covers the entire variable if the variable size is known, otherwise return a zero-sized fragment.</p>

<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="#ae446f360cb65e72ea25e919c540e7388">getFragment</a> and <a href="#a647883cb5d19b9519c0caf3b04e824be">getFragmentSizeInBits</a>.</p>

</div>
</div>

### getFragmentSizeInBits() {#a647883cb5d19b9519c0caf3b04e824be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::DbgVariableRecord::getFragmentSizeInBits ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the size (in bits) of the variable, or fragment of the variable that is described.</p>

<p>Declaration at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#a8ec5a479378113fc24b647afa2f06ee5">getExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/divariable/#a6b5977deeb9f99e156685e190de78403">llvm::DIVariable::getSizeInBits</a> and <a href="#aa774c62045e74bb457b32713c0670696">getVariable</a>.</p>


<p>Referenced by <a href="#a55a1b593c9b1b4f6ed599aae152d99be">getFragmentOrEntireVariable</a>.</p>

</div>
</div>

### getNumVariableLocationOps() {#acd6da9d5bae0cbf845fe0016fcb4c9bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DbgVariableRecord::getNumVariableLocationOps ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ab9edb568c54e87f08484a5f46e399bee">getRawLocation</a> and <a href="#af9c8103c773f2193dafee38239051d7b">hasArgList</a>.</p>


<p>Referenced by <a href="#ab6d5d78fdfb9f1254c0471d2a3be0e65">addVariableLocationOps</a>, <a href="#a49495d1f6880c856ab33832442a9e000">isKillLocation</a>, <a href="#a61ce6eff43abf1cde49ddc11a5567646">replaceVariableLocationOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a05d7d91d31a8121c140a4da8645c6474">valueCoversEntireFragment</a>.</p>

</div>
</div>

### getRawExpression() {#a3e0fc51827c21c4dd8f590d7cc4000db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * llvm::DbgVariableRecord::getRawExpression ()</td>
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



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#a1c0dfe59dcc53704c7a7191a3dff5689">Expression</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a7c33f7bfe854f12e21290f2a03a10a18">anonymous{AsmWriter.cpp}::AssemblyWriter::printDbgVariableRecord</a>.</p>

</div>
</div>

### getRawLocation() {#ab9edb568c54e87f08484a5f46e399bee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DbgVariableRecord::getRawLocation ()</td>
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

<p>Returns the metadata operand for the first location description.</p>


<p>i.e., dbg intrinsic dbg.value,declare operand and dbg.assign 1st location operand (the "value componenet"). Note the operand (singular) may be a <a href="/web-llvm/docs/api/classes/llvm/diarglist">DIArgList</a> which is a list of values.</p>


<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser/#ab9d0079a3383c1716114943006e2d0f3">llvm::DebugValueUser::DebugValues</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4ad92667dcad9ad33a52a2e1c505a03a">buildOverlapMapAndRecordDeclares</a>, <a href="#ad399adefaffab058aa56567aa1b59df9">createDebugIntrinsic</a>, <a href="#acd6da9d5bae0cbf845fe0016fcb4c9bb">getNumVariableLocationOps</a>, <a href="#a99dac64e3a954ffbcbf1fc6726a743a2">getVariableLocationOp</a>, <a href="#af9c8103c773f2193dafee38239051d7b">hasArgList</a>, <a href="#a49495d1f6880c856ab33832442a9e000">isKillLocation</a>, <a href="#afd3574da4a2a86d1540dbdfcef171dd8">location_ops</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a7c33f7bfe854f12e21290f2a03a10a18">anonymous{AsmWriter.cpp}::AssemblyWriter::printDbgVariableRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#a943584f0c65b24cfb9cbbca6d86fa75a">llvm::ValueEnumerator::ValueEnumerator</a>.</p>

</div>
</div>

### getRawVariable() {#a9f421ee6c8aa855c30816913e794a4c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * llvm::DbgVariableRecord::getRawVariable ()</td>
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



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#a3e369e92b13231538b232197d7b5e541">Variable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a7c33f7bfe854f12e21290f2a03a10a18">anonymous{AsmWriter.cpp}::AssemblyWriter::printDbgVariableRecord</a>.</p>

</div>
</div>

### getType() {#a1adb590f8f0ceed777898888ed5db7ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationType llvm::DbgVariableRecord::getType ()</td>
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



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#a3412d15543a66c3770500c3f2ba181c3">Type</a>.</p>


<p>Referenced by <a href="#ad399adefaffab058aa56567aa1b59df9">createDebugIntrinsic</a>, <a href="#ad5a6c4942fc21c7c6c614a78b35747d1">DbgVariableRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ac10429a8c82694552d49e1aba0b85491">DbgVariableRecordsRemoveRedundantDbgInstrsUsingBackwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ad4fea0532db5a2d88aadc8ca450eba93">getAddressExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a52bb01c018d9c9a9bda3d127ab5c7189">llvm::FastISel::handleDbgInfo</a>, <a href="#a8e44c4d5de5d1134497e3ca3b922c535">isDbgAssign</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a73ba5a0ae73c1f5de375603aa29818eb">isKillAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a7c33f7bfe854f12e21290f2a03a10a18">anonymous{AsmWriter.cpp}::AssemblyWriter::printDbgVariableRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#afa1f83e099867326b23c359030bbb103">llvm::coro::salvageDebugInfo</a>, <a href="#a9b641aa0b6a8f401fff5ba3675467835">setKillAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a196df57d98a1307c0ced654a8e1d202b">llvm::SelectionDAGBuilder::visitDbgInfo</a>.</p>

</div>
</div>

### getValue() {#a67997ed52b560aac60464dbdcd8cc3f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::DbgVariableRecord::getValue (unsigned OpIdx=0)</td>
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



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="#a99dac64e3a954ffbcbf1fc6726a743a2">getVariableLocationOp</a> and <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#abf39bad779191e6a85e053be5111c399">insertNewDbgInst</a>.</p>

</div>
</div>

### getVariable() {#aa774c62045e74bb457b32713c0670696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocalVariable * llvm::DbgVariableRecord::getVariable ()</td>
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



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#a3e369e92b13231538b232197d7b5e541">Variable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a07a576318c1a362676e2d4ff00b921bb">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59e94595f29a0adde822a318f82dac61">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82984d4a91e7dc2072dfd8fad2854618">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="#ad399adefaffab058aa56567aa1b59df9">createDebugIntrinsic</a>, <a href="#ad5a6c4942fc21c7c6c614a78b35747d1">DbgVariableRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ac10429a8c82694552d49e1aba0b85491">DbgVariableRecordsRemoveRedundantDbgInstrsUsingBackwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a15c139830d442796a30fbd35e8bfa270">findVarsWithStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a91311bfd92d95fb2817580a39aa9a6ad">getAggregateVariable</a>, <a href="#a647883cb5d19b9519c0caf3b04e824be">getFragmentSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a52bb01c018d9c9a9bda3d127ab5c7189">llvm::FastISel::handleDbgInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ffbb17abf202aabdbb70f00a84905c9">llvm::InsertDebugValueAtStoreLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#abf39bad779191e6a85e053be5111c399">insertNewDbgInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a05d7d91d31a8121c140a4da8645c6474">valueCoversEntireFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#a943584f0c65b24cfb9cbbca6d86fa75a">llvm::ValueEnumerator::ValueEnumerator</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a196df57d98a1307c0ced654a8e1d202b">llvm::SelectionDAGBuilder::visitDbgInfo</a>.</p>

</div>
</div>

### getVariableLocationOp() {#a99dac64e3a954ffbcbf1fc6726a743a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::DbgVariableRecord::getVariableLocationOp (unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ab9edb568c54e87f08484a5f46e399bee">getRawLocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a>.</p>


<p>Referenced by <a href="#ab6d5d78fdfb9f1254c0471d2a3be0e65">addVariableLocationOps</a>, <a href="#a67997ed52b560aac60464dbdcd8cc3f0">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a52bb01c018d9c9a9bda3d127ab5c7189">llvm::FastISel::handleDbgInfo</a>, <a href="#a340f78403c557e9021cbd9f006d56737">hasValidLocation</a>, <a href="#a61ce6eff43abf1cde49ddc11a5567646">replaceVariableLocationOp</a>, <a href="#ae0ac412244054beacd97e316ded0fed3">replaceVariableLocationOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#afa1f83e099867326b23c359030bbb103">llvm::coro::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a05d7d91d31a8121c140a4da8645c6474">valueCoversEntireFragment</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a196df57d98a1307c0ced654a8e1d202b">llvm::SelectionDAGBuilder::visitDbgInfo</a>.</p>

</div>
</div>

### handleChangedLocation() {#a8ef1641fd4bbca0fa6b8f3ca4ada2e5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableRecord::handleChangedLocation (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * NewLocation)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle changes to the location of the <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value(s)</a> that we refer to happening "under our feet".</p>

<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>

</div>
</div>

### hasArgList() {#af9c8103c773f2193dafee38239051d7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableRecord::hasArgList ()</td>
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



<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="#ab9edb568c54e87f08484a5f46e399bee">getRawLocation</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#acd6da9d5bae0cbf845fe0016fcb4c9bb">getNumVariableLocationOps</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a52bb01c018d9c9a9bda3d127ab5c7189">llvm::FastISel::handleDbgInfo</a>, <a href="#a49495d1f6880c856ab33832442a9e000">isKillLocation</a>, <a href="#a61ce6eff43abf1cde49ddc11a5567646">replaceVariableLocationOp</a>, <a href="#ae0ac412244054beacd97e316ded0fed3">replaceVariableLocationOp</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a196df57d98a1307c0ced654a8e1d202b">llvm::SelectionDAGBuilder::visitDbgInfo</a>.</p>

</div>
</div>

### hasValidLocation() {#a340f78403c557e9021cbd9f006d56737}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableRecord::hasValidLocation ()</td>
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

<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> has no empty MDNodes in its location list.</p>

<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#a99dac64e3a954ffbcbf1fc6726a743a2">getVariableLocationOp</a>.</p>

</div>
</div>

### isAddressOfVariable() {#a637a15d148a2daafc86b1be17e01bca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableRecord::isAddressOfVariable ()</td>
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

<p>Does this describe the address of a local variable.</p>


<p>True for dbg.addr and dbg.declare, but not dbg.value, which describes its value.</p>


<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca2709046ed364cc54b91f908e85e512ed">Declare</a> and <a href="#a3412d15543a66c3770500c3f2ba181c3">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a82984d4a91e7dc2072dfd8fad2854618">llvm::ConvertDebugDeclareToDebugValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a05d7d91d31a8121c140a4da8645c6474">valueCoversEntireFragment</a>.</p>

</div>
</div>

### isDbgDeclare() {#ac1678dcac1aa0255429f8dcee4ffabd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableRecord::isDbgDeclare ()</td>
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



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca2709046ed364cc54b91f908e85e512ed">Declare</a> and <a href="#a3412d15543a66c3770500c3f2ba181c3">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a28e2e1ff2e4f02b18b4fdfc7d6c83ba5">DynCastToDbgDeclare</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#abf39bad779191e6a85e053be5111c399">insertNewDbgInst</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coro/#afa1f83e099867326b23c359030bbb103">llvm::coro::salvageDebugInfo</a>.</p>

</div>
</div>

### isDbgValue() {#a0d537737d355256948200ba969a44637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableRecord::isDbgValue ()</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="#a3412d15543a66c3770500c3f2ba181c3">Type</a> and <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#abf39bad779191e6a85e053be5111c399">insertNewDbgInst</a>.</p>

</div>
</div>

### isEquivalentTo() {#a0dde296bd283de2e4e99758a44a2f2a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableRecord::isEquivalentTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> &amp; Other)</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a5f326331f824b415d6f35fc0d1478ea1">llvm::DbgRecord::DbgLoc</a>, <a href="#a0d93b962edf730134f28184361570932">DbgVariableRecord</a>, <a href="#ae53d93dd6b3f1e5cc24506d2f4119625">isIdenticalToWhenDefined</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### isIdenticalToWhenDefined() {#ae53d93dd6b3f1e5cc24506d2f4119625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableRecord::isIdenticalToWhenDefined (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> &amp; Other)</td>
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



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="#af8cc02280e1ae435083375033d5f40bb">AddressExpression</a>, <a href="#a0d93b962edf730134f28184361570932">DbgVariableRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser/#ab9d0079a3383c1716114943006e2d0f3">llvm::DebugValueUser::DebugValues</a>, <a href="#a1c0dfe59dcc53704c7a7191a3dff5689">Expression</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a3412d15543a66c3770500c3f2ba181c3">Type</a> and <a href="#a3e369e92b13231538b232197d7b5e541">Variable</a>.</p>


<p>Referenced by <a href="#a0dde296bd283de2e4e99758a44a2f2a6">isEquivalentTo</a>.</p>

</div>
</div>

### isKillLocation() {#a49495d1f6880c856ab33832442a9e000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableRecord::isKillLocation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="#a8ec5a479378113fc24b647afa2f06ee5">getExpression</a>, <a href="#acd6da9d5bae0cbf845fe0016fcb4c9bb">getNumVariableLocationOps</a>, <a href="#ab9edb568c54e87f08484a5f46e399bee">getRawLocation</a>, <a href="#af9c8103c773f2193dafee38239051d7b">hasArgList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a7926734793677673e68d8cff410552ec">llvm::DIExpression::isComplex</a>, <a href="#afd3574da4a2a86d1540dbdfcef171dd8">location_ops</a> and <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a73ba5a0ae73c1f5de375603aa29818eb">isKillAddress</a>.</p>

</div>
</div>

### isValueOfVariable() {#a2979450e6f2a5a97c5437d5ba90f04e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableRecord::isValueOfVariable ()</td>
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

<p>Determine if this describes the value of a local variable.</p>


<p>It is false for dbg.declare, but true for dbg.value, which describes its value.</p>


<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="#a3412d15543a66c3770500c3f2ba181c3">Type</a> and <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a>.</p>

</div>
</div>

### location\_ops() {#afd3574da4a2a86d1540dbdfcef171dd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; DbgVariableRecord::location_op_iterator &gt; llvm::DbgVariableRecord::location_ops ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the locations corresponding to the variable referenced by the debug info intrinsic.</p>


<p>Depending on the intrinsic, this could be the variable's value or its address.</p>


<p>Declaration at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#ab9edb568c54e87f08484a5f46e399bee">getRawLocation</a>.</p>


<p>Referenced by <a href="#ab6d5d78fdfb9f1254c0471d2a3be0e65">addVariableLocationOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ad19c7559d6302321172436f45c771171">insertDbgVariableRecordsForPHIs</a>, <a href="#a49495d1f6880c856ab33832442a9e000">isKillLocation</a>, <a href="#ae0ac412244054beacd97e316ded0fed3">replaceVariableLocationOp</a>, <a href="#a7ec36aa642cfbc3756fab37cc97d0f86">setKillLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a196df57d98a1307c0ced654a8e1d202b">llvm::SelectionDAGBuilder::visitDbgInfo</a>.</p>

</div>
</div>

### print() {#a3172de1fbc8c02b9b2cef0b24e3b558f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DbgVariableRecord::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, bool IsForDebug=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 5001 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a7b98dd2ff18a320795917ace7f8010db">getModuleFromDPI</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>

</div>
</div>

### print() {#ad64862991023c01b0515a7d29716e6ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DbgVariableRecord::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; ROS, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST, bool IsForDebug)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 5028 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#a802b848d702c132a97b3da454c1e68c1">llvm::ModuleSlotTracker::getMachine</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a7b98dd2ff18a320795917ace7f8010db">getModuleFromDPI</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#ace93d877ff9298d25a15e2a32f765653">llvm::ModuleSlotTracker::incorporateFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#ad025b1f45fbe33034c9c94c17684cbef">llvm::DbgRecord::Marker</a>.</p>

</div>
</div>

### replaceVariableLocationOp() {#ae0ac412244054beacd97e316ded0fed3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableRecord::replaceVariableLocationOp (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OldValue, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewValue, bool AllowEmpty=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/classes/llvm/diarglist/#a51072a9980c37f5cce2a30e9dc4b3057">llvm::DIArgList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a>, <a href="#a8b5e9ae479c5eea5e6d9179a0c203da1">getAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67e80dcdf6a5358a9d3defbe0e8f6c34">llvm::getAsMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#aeeca41a71460985e42575296d3546044">llvm::DbgRecord::getContext</a>, <a href="#a99dac64e3a954ffbcbf1fc6726a743a2">getVariableLocationOp</a>, <a href="#af9c8103c773f2193dafee38239051d7b">hasArgList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a8e44c4d5de5d1134497e3ca3b922c535">isDbgAssign</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#afd3574da4a2a86d1540dbdfcef171dd8">location_ops</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#acae02d7d014e32fd2151b92bf57aeb12">setAddress</a>, <a href="#a826d85216c59be98085f0d03882b9c83">setRawLocation</a> and <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ad19c7559d6302321172436f45c771171">insertDbgVariableRecordsForPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab8b1a901ef225bb4a12ca046d13f4b45">rewriteDebugUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#afa1f83e099867326b23c359030bbb103">llvm::coro::salvageDebugInfo</a>, <a href="#a7ec36aa642cfbc3756fab37cc97d0f86">setKillLocation</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#acf65ce696212774397a4c1a3afc44275">updateOneDbgValueForAlloca</a>.</p>

</div>
</div>

### replaceVariableLocationOp() {#a61ce6eff43abf1cde49ddc11a5567646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableRecord::replaceVariableLocationOp (unsigned OpIdx, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/diarglist/#a51072a9980c37f5cce2a30e9dc4b3057">llvm::DIArgList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67e80dcdf6a5358a9d3defbe0e8f6c34">llvm::getAsMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#aeeca41a71460985e42575296d3546044">llvm::DbgRecord::getContext</a>, <a href="#acd6da9d5bae0cbf845fe0016fcb4c9bb">getNumVariableLocationOps</a>, <a href="#a99dac64e3a954ffbcbf1fc6726a743a2">getVariableLocationOp</a>, <a href="#af9c8103c773f2193dafee38239051d7b">hasArgList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a826d85216c59be98085f0d03882b9c83">setRawLocation</a> and <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a>.</p>

</div>
</div>

### setExpression() {#a8e803431f2ec29d9982f5cd7815712ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableRecord::setExpression (<a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * NewExpr)</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#a1c0dfe59dcc53704c7a7191a3dff5689">Expression</a>.</p>


<p>Referenced by <a href="#ab6d5d78fdfb9f1254c0471d2a3be0e65">addVariableLocationOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab8b1a901ef225bb4a12ca046d13f4b45">rewriteDebugUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#afa1f83e099867326b23c359030bbb103">llvm::coro::salvageDebugInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#acf65ce696212774397a4c1a3afc44275">updateOneDbgValueForAlloca</a>.</p>

</div>
</div>

### setKillLocation() {#a7ec36aa642cfbc3756fab37cc97d0f86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableRecord::setKillLocation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#afd3574da4a2a86d1540dbdfcef171dd8">location_ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a434449d5a0f4b334aca9163b13b6286ba02b848adda8d7d33a2b25d87dbef1d75">Poison</a>, <a href="#ae0ac412244054beacd97e316ded0fed3">replaceVariableLocationOp</a> and <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a>.</p>

</div>
</div>

### setRawLocation() {#a826d85216c59be98085f0d03882b9c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableRecord::setRawLocation (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * NewLocation)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> of this should generally be avoided; instead, replaceVariableLocationOp and addVariableLocationOps should be used where possible to avoid creating invalid state.</p>

<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser/#ac437300794c7752e14a5cbca8d436c4c">llvm::DebugValueUser::resetDebugValue</a>.</p>


<p>Referenced by <a href="#ab6d5d78fdfb9f1254c0471d2a3be0e65">addVariableLocationOps</a>, <a href="#a61ce6eff43abf1cde49ddc11a5567646">replaceVariableLocationOp</a> and <a href="#ae0ac412244054beacd97e316ded0fed3">replaceVariableLocationOp</a>.</p>

</div>
</div>

### setVariable() {#a8b176855918bd3a4e49e48ddb0d3660a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableRecord::setVariable (<a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * NewVar)</td>
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



<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#a3e369e92b13231538b232197d7b5e541">Variable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AddressExpression {#af8cc02280e1ae435083375033d5f40bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgRecordParamRef&lt;DIExpression&gt; llvm::DbgVariableRecord::AddressExpression</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Referenced by <a href="#acb02462725b8625bd395f4fa53520ed4">createDVRAssign</a>, <a href="#ae465cfd07a3ac2e84847e670d92ae8ad">createLinkedDVRAssign</a>, <a href="#a7ff50e2cbdb1f0db4d0b133d03eea6c2">createUnresolvedDbgVariableRecord</a>, <a href="#ad5a6c4942fc21c7c6c614a78b35747d1">DbgVariableRecord</a>, <a href="#ab9a39a6237c5fa48dc0577903cccc592">DbgVariableRecord</a>, <a href="#afa6b67c30dd439d0c3a04af3e81252e6">getAddressExpression</a>, <a href="#a56ed176f3945639483c3ff12214f3ce3">getRawAddressExpression</a>, <a href="#ae53d93dd6b3f1e5cc24506d2f4119625">isIdenticalToWhenDefined</a> and <a href="#a408bd8cb1829e740d4905ddac2a6c251">setAddressExpression</a>.</p>

</div>
</div>

### Expression {#a1c0dfe59dcc53704c7a7191a3dff5689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgRecordParamRef&lt;DIExpression&gt; llvm::DbgVariableRecord::Expression</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Referenced by <a href="#acb02462725b8625bd395f4fa53520ed4">createDVRAssign</a>, <a href="#ae465cfd07a3ac2e84847e670d92ae8ad">createLinkedDVRAssign</a>, <a href="#a7ff50e2cbdb1f0db4d0b133d03eea6c2">createUnresolvedDbgVariableRecord</a>, <a href="#ad5a6c4942fc21c7c6c614a78b35747d1">DbgVariableRecord</a>, <a href="#ab9a39a6237c5fa48dc0577903cccc592">DbgVariableRecord</a>, <a href="#a8ec5a479378113fc24b647afa2f06ee5">getExpression</a>, <a href="#a3e0fc51827c21c4dd8f590d7cc4000db">getRawExpression</a>, <a href="#ae53d93dd6b3f1e5cc24506d2f4119625">isIdenticalToWhenDefined</a> and <a href="#a8e803431f2ec29d9982f5cd7815712ee">setExpression</a>.</p>

</div>
</div>

### Type {#a3412d15543a66c3770500c3f2ba181c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationType llvm::DbgVariableRecord::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Classification of the debug-info record that this <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> represents.</p>


<p>Essentially, "does this correspond to a dbg.value,
dbg.declare, or dbg.assign?". FIXME: We could use spare padding bits from <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> for this.</p>


<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Referenced by <a href="#a7ff50e2cbdb1f0db4d0b133d03eea6c2">createUnresolvedDbgVariableRecord</a>, <a href="#ad5a6c4942fc21c7c6c614a78b35747d1">DbgVariableRecord</a>, <a href="#a2254f7f4df1b9770fa98ca4ba39e868d">DbgVariableRecord</a>, <a href="#a1adb590f8f0ceed777898888ed5db7ac">getType</a>, <a href="#a637a15d148a2daafc86b1be17e01bca9">isAddressOfVariable</a>, <a href="#ac1678dcac1aa0255429f8dcee4ffabd2">isDbgDeclare</a>, <a href="#a0d537737d355256948200ba969a44637">isDbgValue</a>, <a href="#ae53d93dd6b3f1e5cc24506d2f4119625">isIdenticalToWhenDefined</a> and <a href="#a2979450e6f2a5a97c5437d5ba90f04e2">isValueOfVariable</a>.</p>

</div>
</div>

### Variable {#a3e369e92b13231538b232197d7b5e541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgRecordParamRef&lt;DILocalVariable&gt; llvm::DbgVariableRecord::Variable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Referenced by <a href="#acb02462725b8625bd395f4fa53520ed4">createDVRAssign</a>, <a href="#ae465cfd07a3ac2e84847e670d92ae8ad">createLinkedDVRAssign</a>, <a href="#a7ff50e2cbdb1f0db4d0b133d03eea6c2">createUnresolvedDbgVariableRecord</a>, <a href="#ad5a6c4942fc21c7c6c614a78b35747d1">DbgVariableRecord</a>, <a href="#ab9a39a6237c5fa48dc0577903cccc592">DbgVariableRecord</a>, <a href="#a9f421ee6c8aa855c30816913e794a4c7">getRawVariable</a>, <a href="#aa774c62045e74bb457b32713c0670696">getVariable</a>, <a href="#ae53d93dd6b3f1e5cc24506d2f4119625">isIdenticalToWhenDefined</a> and <a href="#a8b176855918bd3a4e49e48ddb0d3660a">setVariable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ab6260338c62a9b3b75089e96997428ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableRecord::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> * E)</td>
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

<p>Support type inquiry through isa, cast, and dyn_cast.</p>

<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a269e66beb08d4b146aa23deb49f5f640">llvm::DbgRecord::DbgRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a887a873e264b58ebc609ffc62b4372bca75e74fbe10c9a9d133941a96309c178b">llvm::DbgRecord::ValueKind</a>.</p>

</div>
</div>

### createDbgVariableRecord() {#a8337b222b982e9caf0f6226efb56039c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgVariableRecord * llvm::DbgVariableRecord::createDbgVariableRecord (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Location, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * DV, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DI)</td>
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



<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#a0d93b962edf730134f28184361570932">DbgVariableRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a> and <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a>.</p>


<p>Referenced by <a href="#a3d7b7b90b3e3aa10243170c25d248f9e">createDbgVariableRecord</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-promotememorytoregister-cpp-/#a9d4100416db594644cb6cd161b245636">anonymous{PromoteMemoryToRegister.cpp}::createDebugValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a915a8d23e084b7a40475a3ce2245495b">llvm::DIBuilder::insertDbgValueIntrinsic</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#abf39bad779191e6a85e053be5111c399">insertNewDbgInst</a>.</p>

</div>
</div>

### createDbgVariableRecord() {#a3d7b7b90b3e3aa10243170c25d248f9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgVariableRecord * llvm::DbgVariableRecord::createDbgVariableRecord (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Location, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * DV, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DI, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> &amp; InsertBefore)</td>
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



<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#a8337b222b982e9caf0f6226efb56039c">createDbgVariableRecord</a>, <a href="#a0d93b962edf730134f28184361570932">DbgVariableRecord</a> and <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a>.</p>

</div>
</div>

### createDVRAssign() {#acb02462725b8625bd395f4fa53520ed4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgVariableRecord * llvm::DbgVariableRecord::createDVRAssign (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Variable, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expression, <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> * AssignID, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Address, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * AddressExpression, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DI)</td>
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



<p>Declaration at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="#af8cc02280e1ae435083375033d5f40bb">AddressExpression</a>, <a href="#a0d93b962edf730134f28184361570932">DbgVariableRecord</a>, <a href="#a1c0dfe59dcc53704c7a7191a3dff5689">Expression</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a>, <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a> and <a href="#a3e369e92b13231538b232197d7b5e541">Variable</a>.</p>


<p>Referenced by <a href="#ae465cfd07a3ac2e84847e670d92ae8ad">createLinkedDVRAssign</a> and <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a5a6937fcd639ac78a93b48ab6624e957">llvm::DIBuilder::insertDbgAssign</a>.</p>

</div>
</div>

### createDVRDeclare() {#a8461772cf63d3b043a673a75b6b95e39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgVariableRecord * llvm::DbgVariableRecord::createDVRDeclare (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Address, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * DV, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DI)</td>
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



<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="#a0d93b962edf730134f28184361570932">DbgVariableRecord</a>, <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca2709046ed364cc54b91f908e85e512ed">Declare</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a> and <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a>.</p>


<p>Referenced by <a href="#a06bd71d62590a4779e1645a292c0b58f">createDVRDeclare</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a214637beca449d58d4313a69a9ba32af">llvm::DIBuilder::insertDeclare</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#abf39bad779191e6a85e053be5111c399">insertNewDbgInst</a>.</p>

</div>
</div>

### createDVRDeclare() {#a06bd71d62590a4779e1645a292c0b58f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgVariableRecord * llvm::DbgVariableRecord::createDVRDeclare (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Address, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * DV, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DI, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> &amp; InsertBefore)</td>
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



<p>Declaration at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="#a8461772cf63d3b043a673a75b6b95e39">createDVRDeclare</a>, <a href="#a0d93b962edf730134f28184361570932">DbgVariableRecord</a> and <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a>.</p>

</div>
</div>

### createLinkedDVRAssign() {#ae465cfd07a3ac2e84847e670d92ae8ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgVariableRecord * llvm::DbgVariableRecord::createLinkedDVRAssign (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * LinkedInstr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Variable, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expression, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Address, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * AddressExpression, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DI)</td>
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



<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="#af8cc02280e1ae435083375033d5f40bb">AddressExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#acb02462725b8625bd395f4fa53520ed4">createDVRAssign</a>, <a href="#a0d93b962edf730134f28184361570932">DbgVariableRecord</a>, <a href="#a1c0dfe59dcc53704c7a7191a3dff5689">Expression</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6c09737e146b2d816c911a047ac67ba4">llvm::Instruction::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a> and <a href="#a3e369e92b13231538b232197d7b5e541">Variable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a9b051a25ba281897b4dc62df58312b7e">emitDbgAssign</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#abf39bad779191e6a85e053be5111c399">insertNewDbgInst</a>.</p>

</div>
</div>

### createUnresolvedDbgVariableRecord() {#a7ff50e2cbdb1f0db4d0b133d03eea6c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgVariableRecord * llvm::DbgVariableRecord::createUnresolvedDbgVariableRecord (<a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4c">LocationType</a> Type, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Variable, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Expression, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * AssignID, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Address, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * AddressExpression, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * DI)</td>
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

<p>Used to create DbgVariableRecords during parsing, where some metadata references may still be unresolved.</p>


<p>Although for some fields a generic <span class="doxyComputerOutput">Metadata*</span> argument is accepted for forward type-references, the verifier and accessors will reject incorrect types later on. The function is used for all types of DbgVariableRecords for simplicity while parsing, but asserts if any necessary fields are empty or unused fields are not empty, i.e. if the #dbg_assign fields are used for a non-dbg-assign type.</p>


<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="#af8cc02280e1ae435083375033d5f40bb">AddressExpression</a>, <a href="#a0d93b962edf730134f28184361570932">DbgVariableRecord</a>, <a href="#a1c0dfe59dcc53704c7a7191a3dff5689">Expression</a>, <a href="#a3412d15543a66c3770500c3f2ba181c3">Type</a> and <a href="#a3e369e92b13231538b232197d7b5e541">Variable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## DbgAssign Methods

### getAddress {#a8b5e9ae479c5eea5e6d9179a0c203da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::DbgVariableRecord::getAddress ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#ad76c901f38759f560144bafef2c598be">getRawAddress</a> and <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a6ba7848b8dd7159c151b8c53194cc44d">getAddress</a>, <a href="#a2f1f03934ddcc92c01e8a83acaab39b2">isKillAddress</a>, <a href="#ae0ac412244054beacd97e316ded0fed3">replaceVariableLocationOp</a> and <a href="#a9b641aa0b6a8f401fff5ba3675467835">setKillAddress</a>.</p>

</div>
</div>

### getAddressExpression {#afa6b67c30dd439d0c3a04af3e81252e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * llvm::DbgVariableRecord::getAddressExpression ()</td>
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



<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#af8cc02280e1ae435083375033d5f40bb">AddressExpression</a>.</p>


<p>Referenced by <a href="#ad399adefaffab058aa56567aa1b59df9">createDebugIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ad4fea0532db5a2d88aadc8ca450eba93">getAddressExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#a943584f0c65b24cfb9cbbca6d86fa75a">llvm::ValueEnumerator::ValueEnumerator</a>.</p>

</div>
</div>

### getAssignID {#a4df534a195fe4df5fc7c2eaf2a96bd97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIAssignID * llvm::DbgVariableRecord::getAssignID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser/#ab9d0079a3383c1716114943006e2d0f3">llvm::DebugValueUser::DebugValues</a>.</p>


<p>Referenced by <a href="#ad399adefaffab058aa56567aa1b59df9">createDebugIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#a60ab87620971c02839693ee99009033d">llvm::at::getAssignmentInsts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a9dd6ae445190ac28162bea663717bf1a">getIDFromMarker</a> and <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#a943584f0c65b24cfb9cbbca6d86fa75a">llvm::ValueEnumerator::ValueEnumerator</a>.</p>

</div>
</div>

### getRawAddress {#ad76c901f38759f560144bafef2c598be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DbgVariableRecord::getRawAddress ()</td>
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



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser/#ab9d0079a3383c1716114943006e2d0f3">llvm::DebugValueUser::DebugValues</a> and <a href="#a8e44c4d5de5d1134497e3ca3b922c535">isDbgAssign</a>.</p>


<p>Referenced by <a href="#ad399adefaffab058aa56567aa1b59df9">createDebugIntrinsic</a>, <a href="#a8b5e9ae479c5eea5e6d9179a0c203da1">getAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a7c33f7bfe854f12e21290f2a03a10a18">anonymous{AsmWriter.cpp}::AssemblyWriter::printDbgVariableRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#a943584f0c65b24cfb9cbbca6d86fa75a">llvm::ValueEnumerator::ValueEnumerator</a>.</p>

</div>
</div>

### getRawAddressExpression {#a56ed176f3945639483c3ff12214f3ce3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * llvm::DbgVariableRecord::getRawAddressExpression ()</td>
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



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#af8cc02280e1ae435083375033d5f40bb">AddressExpression</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a7c33f7bfe854f12e21290f2a03a10a18">anonymous{AsmWriter.cpp}::AssemblyWriter::printDbgVariableRecord</a>.</p>

</div>
</div>

### getRawAssignID {#a92bf6b19c53c3ebfa6045aaeacf6e24b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DbgVariableRecord::getRawAssignID ()</td>
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



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser/#ab9d0079a3383c1716114943006e2d0f3">llvm::DebugValueUser::DebugValues</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a7c33f7bfe854f12e21290f2a03a10a18">anonymous{AsmWriter.cpp}::AssemblyWriter::printDbgVariableRecord</a>.</p>

</div>
</div>

### isDbgAssign {#a8e44c4d5de5d1134497e3ca3b922c535}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableRecord::isDbgAssign ()</td>
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



<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca185b7133db22230701a857c059360cc2">Assign</a> and <a href="#a1adb590f8f0ceed777898888ed5db7ac">getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a9c1515a9c974d17a89cbc1443a9b419c">CastToDbgAssign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82984d4a91e7dc2072dfd8fad2854618">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="#ad399adefaffab058aa56567aa1b59df9">createDebugIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ac10429a8c82694552d49e1aba0b85491">DbgVariableRecordsRemoveRedundantDbgInstrsUsingBackwardScan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#ab21716bf3b4914d7319e0316c95baa20">llvm::memtag::DynCastToDbgAssign</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#a60ab87620971c02839693ee99009033d">llvm::at::getAssignmentInsts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a9dd6ae445190ac28162bea663717bf1a">getIDFromMarker</a>, <a href="#ad76c901f38759f560144bafef2c598be">getRawAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#abf39bad779191e6a85e053be5111c399">insertNewDbgInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a7c33f7bfe854f12e21290f2a03a10a18">anonymous{AsmWriter.cpp}::AssemblyWriter::printDbgVariableRecord</a>, <a href="#ae0ac412244054beacd97e316ded0fed3">replaceVariableLocationOp</a> and <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#a943584f0c65b24cfb9cbbca6d86fa75a">llvm::ValueEnumerator::ValueEnumerator</a>.</p>

</div>
</div>

### isKillAddress {#a2f1f03934ddcc92c01e8a83acaab39b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableRecord::isKillAddress ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this kills the address component.</p>


<p>This doesn't take into account the position of the intrinsic, therefore a returned value of false does not guarentee the address is a valid location for the variable at the intrinsic's position in IR.</p>


<p>Declaration at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#a8b5e9ae479c5eea5e6d9179a0c203da1">getAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a73ba5a0ae73c1f5de375603aa29818eb">isKillAddress</a>.</p>

</div>
</div>

### setAddress {#acae02d7d014e32fd2151b92bf57aeb12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableRecord::setAddress (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser/#ac437300794c7752e14a5cbca8d436c4c">llvm::DebugValueUser::resetDebugValue</a> and <a href="#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">Value</a>.</p>


<p>Referenced by <a href="#ae0ac412244054beacd97e316ded0fed3">replaceVariableLocationOp</a>.</p>

</div>
</div>

### setAddressExpression {#a408bd8cb1829e740d4905ddac2a6c251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableRecord::setAddressExpression (<a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * NewExpr)</td>
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



<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#af8cc02280e1ae435083375033d5f40bb">AddressExpression</a>.</p>

</div>
</div>

### setAssignId {#ac8518bc959468abc1fcd62fadb427f45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableRecord::setAssignId (<a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> * New)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser/#ac437300794c7752e14a5cbca8d436c4c">llvm::DebugValueUser::resetDebugValue</a>.</p>

</div>
</div>

### setKillAddress {#a9b641aa0b6a8f401fff5ba3675467835}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableRecord::setKillAddress ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Kill the address component.</p>

<p>Declaration at line 524 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a>, <a href="#a8b5e9ae479c5eea5e6d9179a0c203da1">getAddress</a>, <a href="#a1adb590f8f0ceed777898888ed5db7ac">getType</a> and <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser/#ac437300794c7752e14a5cbca8d436c4c">llvm::DebugValueUser::resetDebugValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#abf39bad779191e6a85e053be5111c399">insertNewDbgInst</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
