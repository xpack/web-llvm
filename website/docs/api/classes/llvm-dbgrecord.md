---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dbgrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DbgRecord` Class

<p>Base class for non-instruction debug metadata records that have positions within IR. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DbgRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">llvm/IR/DebugProgramInstruction.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node&lt;T, Options&gt;</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord">DbgLabelRecord</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Records a position in IR for a source label (<a href="/web-llvm/docs/api/classes/llvm/dilabel">DILabel</a>). <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> of a variable value-assignment, aka a non instruction representation of the dbg.value intrinsic. <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35975cf965c120e55130f30dd377418d">self_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &gt;::iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8168c3d73a92229c9cb438f404fc3830">const_self_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &gt;::const_iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Kind : uint8_t { <a href="#a887a873e264b58ebc609ffc62b4372bc">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subclass discriminator. <a href="#a887a873e264b58ebc609ffc62b4372bc">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a269e66beb08d4b146aa23deb49f5f640">DbgRecord</a> (Kind RecordKind, DebugLoc DL)</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac184fd43f562cc2c736fe63806801b">~DbgRecord</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similarly to <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, we avoid paying the cost of a vtable by protecting the dtor and having deleteRecord dispatch cleanup. <a href="#a5ac184fd43f562cc2c736fe63806801b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d8ddb598af3628af2a22306f38eb12e">deleteRecord</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods that dispatch to subclass implementations. <a href="#a4d8ddb598af3628af2a22306f38eb12e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae02b7e57cfb15d2a58c56b0430712e41">clone</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff23394ed743458599cec2845522c6e">print</a> (raw_ostream &amp;O, bool IsForDebug=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3fd901fba6a8dc3859727e1ff0c3a70">print</a> (raw_ostream &amp;O, ModuleSlotTracker &amp;MST, bool IsForDebug) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2f5ee08968143135ee0b747068fb9f3">isIdenticalToWhenDefined</a> (const DbgRecord &amp;R) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbginfointrinsic">DbgInfoIntrinsic</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e8723b8826ebf40fdf99dabf47e0fe5">createDebugIntrinsic</a> (Module *M, Instruction *InsertBefore) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert this <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> back into an appropriate llvm.dbg. <a href="#a3e8723b8826ebf40fdf99dabf47e0fe5">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17c5361653e142f37d5f1215d6d1591d">isEquivalentTo</a> (const DbgRecord &amp;R) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as isIdenticalToWhenDefined but checks <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> too. <a href="#a17c5361653e142f37d5f1215d6d1591d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a887a873e264b58ebc609ffc62b4372bc">Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab91f1cdac355568aa1252ddf5e0bab79">getRecordKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad412124c6d332b19147cb1cce6cbd3e9">setMarker</a> (DbgMarker *M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1b7611e70113463caabc2bc84bd08bf">getMarker</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc30683eb694b9f95ae3abcd7823d6de">getMarker</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a156a00684afeefad469213a81874265e">getBlock</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6edebc8248d664dc394af8ba5e332d6">getBlock</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c770bec150810f68fb4a4eacceec263">getFunction</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5e73fb863b8910b7841f583487fc077">getFunction</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f3d614408430191567752182cc78bf5">getModule</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0834f7a463c1bfa666cc9af2d8c80d8a">getModule</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeca41a71460985e42575296d3546044">getContext</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebc682702f3ea424f06c4f56fe6c96e6">getContext</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91c403d156acf0bb3132fa6d4abba68b">getInstruction</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdc6ce41b68f4d534a5263fc529ae3d1">getParent</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45e269ebe3c3e967f5d31048378d1193">getParent</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04a8b2dc4d72db72e1f87bdec4074973">removeFromParent</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a796e59eda02637c147d3c0a4f798a96e">eraseFromParent</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70624545858a6591fce72bb8b50975f1">getNextNode</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbc3b96bca499f8cf00af3dac8d1aaf7">getPrevNode</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a569963898bf9957c3f3c944b34cbb7d7">insertBefore</a> (DbgRecord *InsertBefore)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a029e51f0556ca3cf6bb0116298444a0d">insertAfter</a> (DbgRecord *InsertAfter)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b920bc2fa1cd9de994b2dd23786e582">moveBefore</a> (DbgRecord *MoveBefore)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa91a1edec9d49d6782ec46c90538c599">moveAfter</a> (DbgRecord *MoveAfter)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dc563366f005d720e2945990d780388">insertBefore</a> (self_iterator InsertBefore)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca11d07ce28003236a25c5492c041a53">insertAfter</a> (self_iterator InsertAfter)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada1b0e61caec1a352efdde1845c87274">moveBefore</a> (self_iterator MoveBefore)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7de9d4d7629f65ab0d782dc30745b75e">moveAfter</a> (self_iterator MoveAfter)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a0f4e00c3f6345c52c6acd178b3fca3">getDebugLoc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c0c4e84ab4014447f294a22100126db">setDebugLoc</a> (DebugLoc Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cb121a66942e3da75a21e28a09a47e9">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad025b1f45fbe33034c9c94c17684cbef">Marker</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Marker that this <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> is linked into. <a href="#ad025b1f45fbe33034c9c94c17684cbef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f326331f824b415d6f35fc0d1478ea1">DbgLoc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a887a873e264b58ebc609ffc62b4372bc">Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46bdcb5245391fbc40ebf39c0a6e483a">RecordKind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subclass discriminator. <a href="#a46bdcb5245391fbc40ebf39c0a6e483a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Base class for non-instruction debug metadata records that have positions within IR.</p>


<p>Features various methods copied across from the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> class to aid ease-of-use. DbgRecords should always be linked into a <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a>'s StoredDbgRecords list. The marker connects a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> back to its position in the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>.</p>


<p>We need a discriminator for dyn/isa casts. In order to avoid paying for a vtable for "virtual" functions too, subclasses must add a new discriminator value (RecordKind) and cases to a few functions in the base class: deleteRecord clone isIdenticalToWhenDefined both print methods createDebugIntrinsic</p>


<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_self\_iterator {#a8168c3d73a92229c9cb438f404fc3830}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DbgRecord::const_self_iterator =  simple_ilist&lt;DbgRecord&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>

</div>
</div>

### self\_iterator {#a35975cf965c120e55130f30dd377418d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DbgRecord::self_iterator =  simple_ilist&lt;DbgRecord&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### Kind {#a887a873e264b58ebc609ffc62b4372bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::DbgRecord::Kind : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subclass discriminator.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ValueKind<a id="a887a873e264b58ebc609ffc62b4372bca75e74fbe10c9a9d133941a96309c178b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LabelKind<a id="a887a873e264b58ebc609ffc62b4372bca8f3283cf32bfb899b5547245313bd486"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DbgRecord() {#a269e66beb08d4b146aa23deb49f5f640}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgRecord::DbgRecord (<a href="#a887a873e264b58ebc609ffc62b4372bc">Kind</a> RecordKind, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL)</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="#a5f326331f824b415d6f35fc0d1478ea1">DbgLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="#a46bdcb5245391fbc40ebf39c0a6e483a">RecordKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord/#a511d5322f03174c0ee3a84cb13119ae4">llvm::DbgLabelRecord::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ab6260338c62a9b3b75089e96997428ff">llvm::DbgVariableRecord::classof</a>, <a href="#ae02b7e57cfb15d2a58c56b0430712e41">clone</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord/#a608bdf3158d53073f05efa565ca6c14d">llvm::DbgLabelRecord::DbgLabelRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a0d93b962edf730134f28184361570932">llvm::DbgVariableRecord::DbgVariableRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ad5a6c4942fc21c7c6c614a78b35747d1">llvm::DbgVariableRecord::DbgVariableRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a2254f7f4df1b9770fa98ca4ba39e868d">llvm::DbgVariableRecord::DbgVariableRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ab9a39a6237c5fa48dc0577903cccc592">llvm::DbgVariableRecord::DbgVariableRecord</a>, <a href="#a70624545858a6591fce72bb8b50975f1">getNextNode</a>, <a href="#afbc3b96bca499f8cf00af3dac8d1aaf7">getPrevNode</a>, <a href="#a029e51f0556ca3cf6bb0116298444a0d">insertAfter</a>, <a href="#a569963898bf9957c3f3c944b34cbb7d7">insertBefore</a>, <a href="#a17c5361653e142f37d5f1215d6d1591d">isEquivalentTo</a>, <a href="#ab2f5ee08968143135ee0b747068fb9f3">isIdenticalToWhenDefined</a>, <a href="#aa91a1edec9d49d6782ec46c90538c599">moveAfter</a> and <a href="#a7b920bc2fa1cd9de994b2dd23786e582">moveBefore</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~DbgRecord() {#a5ac184fd43f562cc2c736fe63806801b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgRecord::~DbgRecord ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similarly to <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, we avoid paying the cost of a vtable by protecting the dtor and having deleteRecord dispatch cleanup.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> deleteRecord to delete a generic record.</p>


<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### clone() {#ae02b7e57cfb15d2a58c56b0430712e41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgRecord * llvm::DbgRecord::clone ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a269e66beb08d4b146aa23deb49f5f640">DbgRecord</a>, <a href="#a887a873e264b58ebc609ffc62b4372bca8f3283cf32bfb899b5547245313bd486">LabelKind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a46bdcb5245391fbc40ebf39c0a6e483a">RecordKind</a> and <a href="#a887a873e264b58ebc609ffc62b4372bca75e74fbe10c9a9d133941a96309c178b">ValueKind</a>.</p>

</div>
</div>

### createDebugIntrinsic() {#a3e8723b8826ebf40fdf99dabf47e0fe5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgInfoIntrinsic * llvm::DbgRecord::createDebugIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertBefore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert this <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> back into an appropriate llvm.dbg.</p>


<ul class="doxyList ">
<li>intrinsic. <span class="doxyComputerOutput">InsertBefore</span> Optional position to insert this intrinsic.

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A new llvm.dbg.* intrinsic representiung this <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a>.</p></dd>
</dl></li>
</ul>

<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a887a873e264b58ebc609ffc62b4372bca8f3283cf32bfb899b5547245313bd486">LabelKind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a46bdcb5245391fbc40ebf39c0a6e483a">RecordKind</a> and <a href="#a887a873e264b58ebc609ffc62b4372bca75e74fbe10c9a9d133941a96309c178b">ValueKind</a>.</p>

</div>
</div>

### deleteRecord() {#a4d8ddb598af3628af2a22306f38eb12e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgRecord::deleteRecord ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Methods that dispatch to subclass implementations.</p>


<p>These need to be manually updated when a new subclass is added.</p>


<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a887a873e264b58ebc609ffc62b4372bca8f3283cf32bfb899b5547245313bd486">LabelKind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a46bdcb5245391fbc40ebf39c0a6e483a">RecordKind</a> and <a href="#a887a873e264b58ebc609ffc62b4372bca75e74fbe10c9a9d133941a96309c178b">ValueKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#abbecb38d0e9efb34d40d57e80ea9e8bd">llvm::DbgMarker::dropDbgRecords</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#acde68625afdf845a15c3358956e34057">llvm::DbgMarker::dropOneDbgRecord</a> and <a href="#a796e59eda02637c147d3c0a4f798a96e">eraseFromParent</a>.</p>

</div>
</div>

### isIdenticalToWhenDefined() {#ab2f5ee08968143135ee0b747068fb9f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgRecord::isIdenticalToWhenDefined (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &amp; R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a269e66beb08d4b146aa23deb49f5f640">DbgRecord</a>, <a href="#a887a873e264b58ebc609ffc62b4372bca8f3283cf32bfb899b5547245313bd486">LabelKind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a46bdcb5245391fbc40ebf39c0a6e483a">RecordKind</a> and <a href="#a887a873e264b58ebc609ffc62b4372bca75e74fbe10c9a9d133941a96309c178b">ValueKind</a>.</p>


<p>Referenced by <a href="#a17c5361653e142f37d5f1215d6d1591d">isEquivalentTo</a>.</p>

</div>
</div>

### print() {#a0ff23394ed743458599cec2845522c6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgRecord::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, bool IsForDebug=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a887a873e264b58ebc609ffc62b4372bca8f3283cf32bfb899b5547245313bd486">LabelKind</a>, <a href="#a46bdcb5245391fbc40ebf39c0a6e483a">RecordKind</a> and <a href="#a887a873e264b58ebc609ffc62b4372bca75e74fbe10c9a9d133941a96309c178b">ValueKind</a>.</p>

</div>
</div>

### print() {#ae3fd901fba6a8dc3859727e1ff0c3a70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgRecord::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST, bool IsForDebug)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a887a873e264b58ebc609ffc62b4372bca8f3283cf32bfb899b5547245313bd486">LabelKind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a46bdcb5245391fbc40ebf39c0a6e483a">RecordKind</a> and <a href="#a887a873e264b58ebc609ffc62b4372bca75e74fbe10c9a9d133941a96309c178b">ValueKind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a3cb121a66942e3da75a21e28a09a47e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void DbgRecord::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 5315 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>

</div>
</div>

### eraseFromParent() {#a796e59eda02637c147d3c0a4f798a96e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgRecord::eraseFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 679 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#a4d8ddb598af3628af2a22306f38eb12e">deleteRecord</a> and <a href="#a04a8b2dc4d72db72e1f87bdec4074973">removeFromParent</a>.</p>

</div>
</div>

### getBlock() {#a156a00684afeefad469213a81874265e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::DbgRecord::getBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>Reference <a href="#ad025b1f45fbe33034c9c94c17684cbef">Marker</a>.</p>


<p>Referenced by <a href="#aeeca41a71460985e42575296d3546044">getContext</a>, <a href="#aebc682702f3ea424f06c4f56fe6c96e6">getContext</a>, <a href="#a0c770bec150810f68fb4a4eacceec263">getFunction</a> and <a href="#aa5e73fb863b8910b7841f583487fc077">getFunction</a>.</p>

</div>
</div>

### getBlock() {#ae6edebc8248d664dc394af8ba5e332d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock * llvm::DbgRecord::getBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>Reference <a href="#ad025b1f45fbe33034c9c94c17684cbef">Marker</a>.</p>

</div>
</div>

### getContext() {#aeeca41a71460985e42575296d3546044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext &amp; llvm::DbgRecord::getContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#a156a00684afeefad469213a81874265e">getBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aa286a0f7f5d38488d593bb7ef0ba183e">llvm::BasicBlock::getContext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ab6d5d78fdfb9f1254c0471d2a3be0e65">llvm::DbgVariableRecord::addVariableLocationOps</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord/#adc686ba917c4b589803df62f9a0c75d6">llvm::DbgLabelRecord::createDebugIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab03285c2540e2e5af20afb915d26a405">llvm::getDebugValueLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a61ce6eff43abf1cde49ddc11a5567646">llvm::DbgVariableRecord::replaceVariableLocationOp</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae0ac412244054beacd97e316ded0fed3">llvm::DbgVariableRecord::replaceVariableLocationOp</a>.</p>

</div>
</div>

### getContext() {#aebc682702f3ea424f06c4f56fe6c96e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLVMContext &amp; llvm::DbgRecord::getContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#a156a00684afeefad469213a81874265e">getBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aa286a0f7f5d38488d593bb7ef0ba183e">llvm::BasicBlock::getContext</a>.</p>

</div>
</div>

### getDebugLoc() {#a3a0f4e00c3f6345c52c6acd178b3fca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::DbgRecord::getDebugLoc ()</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#a5f326331f824b415d6f35fc0d1478ea1">DbgLoc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4ad92667dcad9ad33a52a2e1c505a03a">buildOverlapMapAndRecordDeclares</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord/#a2e1adab2fe4df7a403f8deb20265d933">llvm::DbgLabelRecord::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord/#adc686ba917c4b589803df62f9a0c75d6">llvm::DbgLabelRecord::createDebugIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ad399adefaffab058aa56567aa1b59df9">llvm::DbgVariableRecord::createDebugIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a0d93b962edf730134f28184361570932">llvm::DbgVariableRecord::DbgVariableRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ad5a6c4942fc21c7c6c614a78b35747d1">llvm::DbgVariableRecord::DbgVariableRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ac10429a8c82694552d49e1aba0b85491">DbgVariableRecordsRemoveRedundantDbgInstrsUsingBackwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a15c139830d442796a30fbd35e8bfa270">findVarsWithStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a91311bfd92d95fb2817580a39aa9a6ad">getAggregateVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab03285c2540e2e5af20afb915d26a405">llvm::getDebugValueLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a52bb01c018d9c9a9bda3d127ab5c7189">llvm::FastISel::handleDbgInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#abf39bad779191e6a85e053be5111c399">insertNewDbgInst</a>, <a href="#a17c5361653e142f37d5f1215d6d1591d">isEquivalentTo</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a7c33f7bfe854f12e21290f2a03a10a18">anonymous{AsmWriter.cpp}::AssemblyWriter::printDbgVariableRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/debuginfofinder/#aed105f22ff3e6ad4f3c80cd96ef7df1f">llvm::DebugInfoFinder::processDbgRecord</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a41b5be766680970f5843b6bbeb8ee3d6">anonymous{ValueMapper.cpp}::Mapper::remapDbgRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#afa1f83e099867326b23c359030bbb103">llvm::coro::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#a943584f0c65b24cfb9cbbca6d86fa75a">llvm::ValueEnumerator::ValueEnumerator</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a196df57d98a1307c0ced654a8e1d202b">llvm::SelectionDAGBuilder::visitDbgInfo</a>.</p>

</div>
</div>

### getFunction() {#a0c770bec150810f68fb4a4eacceec263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::DbgRecord::getFunction ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#a156a00684afeefad469213a81874265e">getBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>.</p>


<p>Referenced by <a href="#a7f3d614408430191567752182cc78bf5">getModule</a>, <a href="#a0834f7a463c1bfa666cc9af2d8c80d8a">getModule</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coro/#afa1f83e099867326b23c359030bbb103">llvm::coro::salvageDebugInfo</a>.</p>

</div>
</div>

### getFunction() {#aa5e73fb863b8910b7841f583487fc077}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function * llvm::DbgRecord::getFunction ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#a156a00684afeefad469213a81874265e">getBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>.</p>

</div>
</div>

### getInstruction() {#a91c403d156acf0bb3132fa6d4abba68b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction * llvm::DbgRecord::getInstruction ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>Reference <a href="#ad025b1f45fbe33034c9c94c17684cbef">Marker</a>.</p>

</div>
</div>

### getMarker() {#aa1b7611e70113463caabc2bc84bd08bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgMarker * llvm::DbgRecord::getMarker ()</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#ad025b1f45fbe33034c9c94c17684cbef">Marker</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#acde68625afdf845a15c3358956e34057">llvm::DbgMarker::dropOneDbgRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a9af15b30bf916411af4026c84ef965ca">getModuleFromDPI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a05eb84c8f630be406f61761013146574">getNextNode</a>, <a href="#a029e51f0556ca3cf6bb0116298444a0d">insertAfter</a>, <a href="#aca11d07ce28003236a25c5492c041a53">insertAfter</a>, <a href="#a569963898bf9957c3f3c944b34cbb7d7">insertBefore</a>, <a href="#a5dc563366f005d720e2945990d780388">insertBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#ad39cef6524b0757f3d47c5e988c20214">llvm::DbgMarker::insertDbgRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#a4e3e46a5043b9376725624d0655d187a">llvm::DbgMarker::insertDbgRecordAfter</a>, <a href="#aa91a1edec9d49d6782ec46c90538c599">moveAfter</a>, <a href="#a7de9d4d7629f65ab0d782dc30745b75e">moveAfter</a>, <a href="#a7b920bc2fa1cd9de994b2dd23786e582">moveBefore</a>, <a href="#ada1b0e61caec1a352efdde1845c87274">moveBefore</a>, <a href="#a04a8b2dc4d72db72e1f87bdec4074973">removeFromParent</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab8b1a901ef225bb4a12ca046d13f4b45">rewriteDebugUsers</a>.</p>

</div>
</div>

### getMarker() {#abc30683eb694b9f95ae3abcd7823d6de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DbgMarker * llvm::DbgRecord::getMarker ()</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#ad025b1f45fbe33034c9c94c17684cbef">Marker</a>.</p>

</div>
</div>

### getModule() {#a7f3d614408430191567752182cc78bf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module * llvm::DbgRecord::getModule ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#a0c770bec150810f68fb4a4eacceec263">getFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a05d7d91d31a8121c140a4da8645c6474">valueCoversEntireFragment</a>.</p>

</div>
</div>

### getModule() {#a0834f7a463c1bfa666cc9af2d8c80d8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module * llvm::DbgRecord::getModule ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#a0c770bec150810f68fb4a4eacceec263">getFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>.</p>

</div>
</div>

### getNextNode() {#a70624545858a6591fce72bb8b50975f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgRecord * llvm::DbgRecord::getNextNode ()</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="#a269e66beb08d4b146aa23deb49f5f640">DbgRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; ilist_detail::compute_node_options&lt; DbgRecord, Options... &gt;::type &gt;::getIterator</a>.</p>

</div>
</div>

### getParent() {#afdc6ce41b68f4d534a5263fc529ae3d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock * llvm::DbgRecord::getParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>Reference <a href="#ad025b1f45fbe33034c9c94c17684cbef">Marker</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a26d6acb7d8248e5d25f190b5d8fecbd3">llvm::JumpThreadingPass::updateSSA</a>.</p>

</div>
</div>

### getParent() {#a45e269ebe3c3e967f5d31048378d1193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::DbgRecord::getParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>Reference <a href="#ad025b1f45fbe33034c9c94c17684cbef">Marker</a>.</p>

</div>
</div>

### getPrevNode() {#afbc3b96bca499f8cf00af3dac8d1aaf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgRecord * llvm::DbgRecord::getPrevNode ()</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="#a269e66beb08d4b146aa23deb49f5f640">DbgRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; ilist_detail::compute_node_options&lt; DbgRecord, Options... &gt;::type &gt;::getIterator</a>.</p>

</div>
</div>

### getRecordKind() {#ab91f1cdac355568aa1252ddf5e0bab79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Kind llvm::DbgRecord::getRecordKind ()</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#a46bdcb5245391fbc40ebf39c0a6e483a">RecordKind</a>.</p>

</div>
</div>

### insertAfter() {#a029e51f0556ca3cf6bb0116298444a0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgRecord::insertAfter (<a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> * InsertAfter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a269e66beb08d4b146aa23deb49f5f640">DbgRecord</a>, <a href="#aa1b7611e70113463caabc2bc84bd08bf">getMarker</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#a4e3e46a5043b9376725624d0655d187a">llvm::DbgMarker::insertDbgRecordAfter</a>.</p>


<p>Referenced by <a href="#aa91a1edec9d49d6782ec46c90538c599">moveAfter</a> and <a href="#a7de9d4d7629f65ab0d782dc30745b75e">moveAfter</a>.</p>

</div>
</div>

### insertAfter() {#aca11d07ce28003236a25c5492c041a53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgRecord::insertAfter (<a href="#a35975cf965c120e55130f30dd377418d">self_iterator</a> InsertAfter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aa1b7611e70113463caabc2bc84bd08bf">getMarker</a>.</p>

</div>
</div>

### insertBefore() {#a569963898bf9957c3f3c944b34cbb7d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgRecord::insertBefore (<a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> * InsertBefore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a269e66beb08d4b146aa23deb49f5f640">DbgRecord</a>, <a href="#aa1b7611e70113463caabc2bc84bd08bf">getMarker</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#ad286983c7ed10a987ff5c2a3391aa9de">llvm::DbgMarker::insertDbgRecord</a>.</p>


<p>Referenced by <a href="#a7b920bc2fa1cd9de994b2dd23786e582">moveBefore</a> and <a href="#ada1b0e61caec1a352efdde1845c87274">moveBefore</a>.</p>

</div>
</div>

### insertBefore() {#a5dc563366f005d720e2945990d780388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgRecord::insertBefore (<a href="#a35975cf965c120e55130f30dd377418d">self_iterator</a> InsertBefore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aa1b7611e70113463caabc2bc84bd08bf">getMarker</a>.</p>

</div>
</div>

### isEquivalentTo() {#a17c5361653e142f37d5f1215d6d1591d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgRecord::isEquivalentTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &amp; R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Same as isIdenticalToWhenDefined but checks <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> too.</p>

<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#a269e66beb08d4b146aa23deb49f5f640">DbgRecord</a>, <a href="#a3a0f4e00c3f6345c52c6acd178b3fca3">getDebugLoc</a> and <a href="#ab2f5ee08968143135ee0b747068fb9f3">isIdenticalToWhenDefined</a>.</p>

</div>
</div>

### moveAfter() {#aa91a1edec9d49d6782ec46c90538c599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgRecord::moveAfter (<a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> * MoveAfter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a269e66beb08d4b146aa23deb49f5f640">DbgRecord</a>, <a href="#aa1b7611e70113463caabc2bc84bd08bf">getMarker</a>, <a href="#a029e51f0556ca3cf6bb0116298444a0d">insertAfter</a> and <a href="#a04a8b2dc4d72db72e1f87bdec4074973">removeFromParent</a>.</p>

</div>
</div>

### moveAfter() {#a7de9d4d7629f65ab0d782dc30745b75e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgRecord::moveAfter (<a href="#a35975cf965c120e55130f30dd377418d">self_iterator</a> MoveAfter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa1b7611e70113463caabc2bc84bd08bf">getMarker</a>, <a href="#a029e51f0556ca3cf6bb0116298444a0d">insertAfter</a> and <a href="#a04a8b2dc4d72db72e1f87bdec4074973">removeFromParent</a>.</p>

</div>
</div>

### moveBefore() {#a7b920bc2fa1cd9de994b2dd23786e582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgRecord::moveBefore (<a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> * MoveBefore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a269e66beb08d4b146aa23deb49f5f640">DbgRecord</a>, <a href="#aa1b7611e70113463caabc2bc84bd08bf">getMarker</a>, <a href="#a569963898bf9957c3f3c944b34cbb7d7">insertBefore</a> and <a href="#a04a8b2dc4d72db72e1f87bdec4074973">removeFromParent</a>.</p>

</div>
</div>

### moveBefore() {#ada1b0e61caec1a352efdde1845c87274}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgRecord::moveBefore (<a href="#a35975cf965c120e55130f30dd377418d">self_iterator</a> MoveBefore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa1b7611e70113463caabc2bc84bd08bf">getMarker</a>, <a href="#a569963898bf9957c3f3c944b34cbb7d7">insertBefore</a> and <a href="#a04a8b2dc4d72db72e1f87bdec4074973">removeFromParent</a>.</p>

</div>
</div>

### removeFromParent() {#a04a8b2dc4d72db72e1f87bdec4074973}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgRecord::removeFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 674 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; ilist_detail::compute_node_options&lt; DbgRecord, Options... &gt;::type &gt;::getIterator</a>, <a href="#aa1b7611e70113463caabc2bc84bd08bf">getMarker</a>, <a href="#ad025b1f45fbe33034c9c94c17684cbef">Marker</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#acf93a5910e8b1adcdca71705495e5d92">llvm::DbgMarker::StoredDbgRecords</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#ac8803aa267830622708ede7b732c7ae2">DbgInserterHelper</a>, <a href="#a796e59eda02637c147d3c0a4f798a96e">eraseFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedc31552ebf0ce116c665da44b4a97a5">hoistLockstepIdenticalDbgVariableRecords</a>, <a href="#aa91a1edec9d49d6782ec46c90538c599">moveAfter</a>, <a href="#a7de9d4d7629f65ab0d782dc30745b75e">moveAfter</a>, <a href="#a7b920bc2fa1cd9de994b2dd23786e582">moveBefore</a>, <a href="#ada1b0e61caec1a352efdde1845c87274">moveBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab8b1a901ef225bb4a12ca046d13f4b45">rewriteDebugUsers</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coro/#afa1f83e099867326b23c359030bbb103">llvm::coro::salvageDebugInfo</a>.</p>

</div>
</div>

### setDebugLoc() {#a8c0c4e84ab4014447f294a22100126db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgRecord::setDebugLoc (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> Loc)</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#a5f326331f824b415d6f35fc0d1478ea1">DbgLoc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a41b5be766680970f5843b6bbeb8ee3d6">anonymous{ValueMapper.cpp}::Mapper::remapDbgRecord</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coro/#afa1f83e099867326b23c359030bbb103">llvm::coro::salvageDebugInfo</a>.</p>

</div>
</div>

### setMarker() {#ad412124c6d332b19147cb1cce6cbd3e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgRecord::setMarker (<a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> * M)</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#ad025b1f45fbe33034c9c94c17684cbef">Marker</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#ab72d53ec1bee5605dfe12b8b594f40f5">llvm::DbgMarker::absorbDebugValues</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Marker {#ad025b1f45fbe33034c9c94c17684cbef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgMarker* llvm::DbgRecord::Marker = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Marker that this <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> is linked into.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Referenced by <a href="#a156a00684afeefad469213a81874265e">getBlock</a>, <a href="#ae6edebc8248d664dc394af8ba5e332d6">getBlock</a>, <a href="#a91c403d156acf0bb3132fa6d4abba68b">getInstruction</a>, <a href="#aa1b7611e70113463caabc2bc84bd08bf">getMarker</a>, <a href="#abc30683eb694b9f95ae3abcd7823d6de">getMarker</a>, <a href="#a45e269ebe3c3e967f5d31048378d1193">getParent</a>, <a href="#afdc6ce41b68f4d534a5263fc529ae3d1">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord/#af01d77795bb3f385853944a0fb4dbc40">llvm::DbgLabelRecord::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ad64862991023c01b0515a7d29716e6ad">llvm::DbgVariableRecord::print</a>, <a href="#a04a8b2dc4d72db72e1f87bdec4074973">removeFromParent</a> and <a href="#ad412124c6d332b19147cb1cce6cbd3e9">setMarker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### DbgLoc {#a5f326331f824b415d6f35fc0d1478ea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::DbgRecord::DbgLoc</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Referenced by <a href="#a269e66beb08d4b146aa23deb49f5f640">DbgRecord</a>, <a href="#a3a0f4e00c3f6345c52c6acd178b3fca3">getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a0dde296bd283de2e4e99758a44a2f2a6">llvm::DbgVariableRecord::isEquivalentTo</a> and <a href="#a8c0c4e84ab4014447f294a22100126db">setDebugLoc</a>.</p>

</div>
</div>

### RecordKind {#a46bdcb5245391fbc40ebf39c0a6e483a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Kind llvm::DbgRecord::RecordKind</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subclass discriminator.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Referenced by <a href="#ae02b7e57cfb15d2a58c56b0430712e41">clone</a>, <a href="#a3e8723b8826ebf40fdf99dabf47e0fe5">createDebugIntrinsic</a>, <a href="#a269e66beb08d4b146aa23deb49f5f640">DbgRecord</a>, <a href="#a4d8ddb598af3628af2a22306f38eb12e">deleteRecord</a>, <a href="#ab91f1cdac355568aa1252ddf5e0bab79">getRecordKind</a>, <a href="#ab2f5ee08968143135ee0b747068fb9f3">isIdenticalToWhenDefined</a>, <a href="#a0ff23394ed743458599cec2845522c6e">print</a> and <a href="#ae3fd901fba6a8dc3859727e1ff0c3a70">print</a>.</p>

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
