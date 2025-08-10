---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/m68k
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `M68k` Namespace

<p>Define some predicates that are used for node matching. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::M68k { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PartialMappingIdx { <a href="#ad9fcd2b8d1e679cb14ae3d4f08b8d7a6">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ValueMappingIdx { <a href="#ad5c2ec44d6d18d9dc85e3f409c67adfc">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CondCode { <a href="#a3ae7fc35b1e164744d5f085ff1e84039">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a933a536b74f1c683af9f84c569a2e3fc">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enums for memory operand decoding. <a href="#a933a536b74f1c683af9f84c569a2e3fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a1c69b08ffa2f216dff7d46a5a38096c8">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enums for pc-relative memory operand decoding. <a href="#a1c69b08ffa2f216dff7d46a5a38096c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MemAddrModeKind : unsigned { <a href="#ab3a288f2953d8eca3e363959fc2cf38e">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4f0e11a6107b18bffcb5daf2e08772e">addOffset</a> (const MachineInstrBuilder &amp;MIB, int Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad283cfc77268d18405882cb6588c337f">addRegIndirectWithDisp</a> (const MachineInstrBuilder &amp;MIB, Register Reg, bool IsKill, int Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addRegIndirectWithDisp - This function is used to add a memory reference of the form (Offset, Base), i.e., one with no scale or index, but with a displacement. <a href="#ad283cfc77268d18405882cb6588c337f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67931ef18efe0f1710e3f2e39ddfb8f6">addFrameReference</a> (const MachineInstrBuilder &amp;MIB, int FI, int Offset=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addFrameReference - This function is used to add a reference to the base of an abstract object on the stack frame of the current function. <a href="#a67931ef18efe0f1710e3f2e39ddfb8f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40fe21a4879ff8f132c4fb676738c5b1">addMemOperand</a> (const MachineInstrBuilder &amp;MIB, int FI, int Offset=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a3ae7fc35b1e164744d5f085ff1e84039">M68k::CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a876bb5be568d372d0a658d2ea5927b74">GetOppositeBranchCondition</a> (M68k::CondCode CC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53befb9ac81cf6c262c28640cb6c5425">GetCondBranchFromCond</a> (M68k::CondCode CC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a3ae7fc35b1e164744d5f085ff1e84039">M68k::CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af68462432be0df20e086eea034fe3cc0">GetCondFromBranchOpc</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27cf406d028f2c6c883efe8b68b3fe17">IsCMP</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00afcb12e9f6d7c5a926191b6eb31fbf">IsSETCC</a> (unsigned SETCC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c0593d90ef80873966d1556f7a715eb">isCalleePop</a> (CallingConv::ID CallingConv, bool IsVarArg, bool GuaranteeTCO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determines whether the callee is required to pop its own arguments. <a href="#a6c0593d90ef80873966d1556f7a715eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_t&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">value_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa0afd3ff35e9b67d4c567f6ec5ba2a3e">swapWord</a> (value_t Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dcd23cc95df1990a383ced27f964dbe">getMCInstrBeads</a> (unsigned)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping">RegisterBankInfo::PartialMapping</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26fbbdf685b18f9d12aaa5babc259bdf">PartMappings</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">RegisterBankInfo::ValueMapping</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ab41b597a967d9fb5ff98f2fa88ecea">ValueMappings</a>[] = ...</td>
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

<p>Define some predicates that are used for node matching.</p>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a933a536b74f1c683af9f84c569a2e3fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enums for memory operand decoding.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MemDisp<a id="a933a536b74f1c683af9f84c569a2e3fcac4f6de6ded1c2d772d1235a33c9e4c3b"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MemBase<a id="a933a536b74f1c683af9f84c569a2e3fca3e55dd799da63f32bf9732dbd86efc43"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MemIndex<a id="a933a536b74f1c683af9f84c569a2e3fca89e86d272e21382d1d2112c60068ad77"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MemOuter<a id="a933a536b74f1c683af9f84c569a2e3fcaeef8674ed144759b86a1cf39284e7c28"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

</table>
</dd>
</dl>


<p>Supports these forms: (d,An) (d,An,Xn) ([bd,An],Xn,od) ([bd,An,Xn],od) TODO Implement scaling other than 1</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kbaseinfo-h">M68kBaseInfo.h</a>.</p>

</div>
</div>

### anonymous enum  {#a1c69b08ffa2f216dff7d46a5a38096c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enums for pc-relative memory operand decoding.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCRelDisp<a id="a1c69b08ffa2f216dff7d46a5a38096c8ab6d97de57d8c9b7d91a28a7339da4044"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCRelIndex<a id="a1c69b08ffa2f216dff7d46a5a38096c8a803ed9fcd752b973d50b7187b2991149"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCRelOuter<a id="a1c69b08ffa2f216dff7d46a5a38096c8ae21e202d891e60166635bbed263de9bc"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>


<p>Supports these forms: (d,PC) (d,PC,Xn) ([bd,PC],Xn,od) ([bd,PC,Xn],od)</p>


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kbaseinfo-h">M68kBaseInfo.h</a>.</p>

</div>
</div>

### CondCode {#a3ae7fc35b1e164744d5f085ff1e84039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::M68k::CondCode </td>
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
<td class="doxyEnumItemName">COND_T<a id="a3ae7fc35b1e164744d5f085ff1e84039a173d46f3ad7ff4516cc52336b2949f13"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_F<a id="a3ae7fc35b1e164744d5f085ff1e84039a327a900d4ac7d27518a53bc7c1731ee5"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_HI<a id="a3ae7fc35b1e164744d5f085ff1e84039ab92c3630f32ebf09ebfffab9305bbd58"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_LS<a id="a3ae7fc35b1e164744d5f085ff1e84039ae0e66410bd55b220017e4ff5c244ca21"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_CC<a id="a3ae7fc35b1e164744d5f085ff1e84039a7febd5dc3ed75138f38cc36cf0e30fcc"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_CS<a id="a3ae7fc35b1e164744d5f085ff1e84039aa25f8b0ba8ef8c152fcb4d880ee5d387"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_NE<a id="a3ae7fc35b1e164744d5f085ff1e84039aa901317a44b0be9a1ac4067028524bd6"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_EQ<a id="a3ae7fc35b1e164744d5f085ff1e84039ac148f8930d127f0c09a35848ad30419e"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_VC<a id="a3ae7fc35b1e164744d5f085ff1e84039a4e035f352a713e4c58b6b6e306a19a8b"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_VS<a id="a3ae7fc35b1e164744d5f085ff1e84039a8676b3e7eaf6d79f9b2cb242776b831a"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_PL<a id="a3ae7fc35b1e164744d5f085ff1e84039ad7801a76a67f06e7074b6e7e82b63cb9"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_MI<a id="a3ae7fc35b1e164744d5f085ff1e84039a2e5ed258170cfe7b8b2b759e3382fba2"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_GE<a id="a3ae7fc35b1e164744d5f085ff1e84039af0e55f79c4cd6282754ac1bc5417573f"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_LT<a id="a3ae7fc35b1e164744d5f085ff1e84039a99ca08e883ff21904ad2afcf58ac5b36"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_GT<a id="a3ae7fc35b1e164744d5f085ff1e84039a9fa23e50c543dbc8e4199a4b2d86464e"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_LE<a id="a3ae7fc35b1e164744d5f085ff1e84039a251eb0798d4ebad8afda15f84916869a"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_VALID_COND<a id="a3ae7fc35b1e164744d5f085ff1e84039a57bc7f557fe6ce5ca5edc4202e5f438d"></a></td>
<td class="doxyEnumItemDescription"> (= COND_LE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_INVALID<a id="a3ae7fc35b1e164744d5f085ff1e84039a5033e89fe93b7cbea4d857dadb79c110"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrinfo-h">M68kInstrInfo.h</a>.</p>

</div>
</div>

### MemAddrModeKind {#ab3a288f2953d8eca3e363959fc2cf38e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::M68k::MemAddrModeKind : unsigned</td>
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
<td class="doxyEnumItemName">j<a id="ab3a288f2953d8eca3e363959fc2cf38ea363b122c528f54df4a0446b6bab05515"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">o<a id="ab3a288f2953d8eca3e363959fc2cf38ead95679752134a2d9eb61dbd7b91c4bcc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">e<a id="ab3a288f2953d8eca3e363959fc2cf38eae1671797c52e15f763380b45e841ec32"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">p<a id="ab3a288f2953d8eca3e363959fc2cf38ea83878c91171338902e0fe0fb97a8c47a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">f<a id="ab3a288f2953d8eca3e363959fc2cf38ea8fa14cdd754f91cc6554c9e71929cce7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F<a id="ab3a288f2953d8eca3e363959fc2cf38ea800618943025315f869e4e1f09471012"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">g<a id="ab3a288f2953d8eca3e363959fc2cf38eab2f5ff47436671b6e533d8dc3614845d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">G<a id="ab3a288f2953d8eca3e363959fc2cf38eadfcf28d0734569a6a693bc8194de62bf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">u<a id="ab3a288f2953d8eca3e363959fc2cf38ea7b774effe4a349c6dd82ad4f4f21d34c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">U<a id="ab3a288f2953d8eca3e363959fc2cf38ea4c614360da93c0a041b22e537de151eb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v<a id="ab3a288f2953d8eca3e363959fc2cf38ea9e3669d19b675bd57058fd4664205d2a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V<a id="ab3a288f2953d8eca3e363959fc2cf38ea5206560a306a2e085a437fd258eb57ce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">b<a id="ab3a288f2953d8eca3e363959fc2cf38ea92eb5ffee6ae2fec3ad71c777531578f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">B<a id="ab3a288f2953d8eca3e363959fc2cf38ea9d5ed678fe57bcca610140957afab571"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">q<a id="ab3a288f2953d8eca3e363959fc2cf38ea7694f4a66316e53c8cdd9d9954bd611d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k<a id="ab3a288f2953d8eca3e363959fc2cf38ea8ce4b16b22b58894aa86c421e8759df3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">K<a id="ab3a288f2953d8eca3e363959fc2cf38eaa5f3c6a11b03839d46af9fb43c97c188"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">l<a id="ab3a288f2953d8eca3e363959fc2cf38ea2db95e8e1a9267b7a1188556b2013b33"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">L<a id="ab3a288f2953d8eca3e363959fc2cf38ead20caec3b48a1eef164cb4ca81ba2587"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">x<a id="ab3a288f2953d8eca3e363959fc2cf38ea9dd4e461268c8034f5c8564e155c67a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">X<a id="ab3a288f2953d8eca3e363959fc2cf38ea02129bb861061d1a052c592e2dc6b383"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">y<a id="ab3a288f2953d8eca3e363959fc2cf38ea415290769594460e2e485922904f345d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Y<a id="ab3a288f2953d8eca3e363959fc2cf38ea57cec4137b614c87cb4e24a3d003a3e0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kbaseinfo-h">M68kBaseInfo.h</a>.</p>

</div>
</div>

### PartialMappingIdx {#ad9fcd2b8d1e679cb14ae3d4f08b8d7a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::M68k::PartialMappingIdx </td>
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
<td class="doxyEnumItemName">PMI_GPR<a id="ad9fcd2b8d1e679cb14ae3d4f08b8d7a6ae2401fa18c8df5bd4d85315a6a20928a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_Min<a id="ad9fcd2b8d1e679cb14ae3d4f08b8d7a6a960176b21d3ea95d3701060a13828edb"></a></td>
<td class="doxyEnumItemDescription"> (= PMI_GPR)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kregisterbankinfo-cpp">M68kRegisterBankInfo.cpp</a>.</p>

</div>
</div>

### ValueMappingIdx {#ad5c2ec44d6d18d9dc85e3f409c67adfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::M68k::ValueMappingIdx </td>
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
<td class="doxyEnumItemName">InvalidIdx<a id="ad5c2ec44d6d18d9dc85e3f409c67adfca9fb030b714fb8eafb7293cabd3e48849"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GPR3OpsIdx<a id="ad5c2ec44d6d18d9dc85e3f409c67adfca79902e57879f4fca82eaaf5ef0b81890"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kregisterbankinfo-cpp">M68kRegisterBankInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### addFrameReference() {#a67931ef18efe0f1710e3f2e39ddfb8f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::M68k::addFrameReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, int FI, int Offset=0)</td>
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

<p>addFrameReference - This function is used to add a reference to the base of an abstract object on the stack frame of the current function.</p>


<p>This reference has base register as the FrameIndex offset until it is resolved. This allows a constant offset to be specified as well...</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrbuilder-h">M68kInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a86a93dd8ddbce120d8c3101c16bc3cc6">llvm::MachineInstrBuilder::addFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ae565d45627e1678a3e37bd6a016c561c">llvm::MachineInstrBuilder::addMemOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a8320a54de0a273478de910ac3795058b">llvm::MachineFrameInfo::getObjectAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a9284fd53296d2a2f8ae654d000971000">llvm::MachineFrameInfo::getObjectSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6">llvm::MachineMemOperand::MONone</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a239b76db482ddf927605d2df0345f32c">llvm::M68kInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab5fe151eb7f6fa13e78ed30cb5f1ad72">llvm::M68kFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a3bbbc37b2cd9470b51560df8c20e66e2">llvm::M68kFrameLowering::spillCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#acc65122fa06b8871a427abbbd700b22a">llvm::M68kInstrInfo::storeRegToStackSlot</a>.</p>

</div>
</div>

### addMemOperand() {#a40fe21a4879ff8f132c4fb676738c5b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::M68k::addMemOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, int FI, int Offset=0)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrbuilder-h">M68kInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ae565d45627e1678a3e37bd6a016c561c">llvm::MachineInstrBuilder::addMemOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a8320a54de0a273478de910ac3795058b">llvm::MachineFrameInfo::getObjectAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a9284fd53296d2a2f8ae654d000971000">llvm::MachineFrameInfo::getObjectSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6">llvm::MachineMemOperand::MONone</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab5fe151eb7f6fa13e78ed30cb5f1ad72">llvm::M68kFrameLowering::restoreCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a3bbbc37b2cd9470b51560df8c20e66e2">llvm::M68kFrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### addOffset() {#ae4f0e11a6107b18bffcb5daf2e08772e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::M68k::addOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, int Offset)</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrbuilder-h">M68kInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### addRegIndirectWithDisp() {#ad283cfc77268d18405882cb6588c337f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::M68k::addRegIndirectWithDisp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, bool IsKill, int Offset)</td>
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

<p>addRegIndirectWithDisp - This function is used to add a memory reference of the form (Offset, Base), i.e., one with no scale or index, but with a displacement.</p>


<p>An example is: (4,D0).</p>


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrbuilder-h">M68kInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a27812f7473acb8b3398abc5a297ea082">llvm::M68kFrameLowering::emitEpilogue</a> and <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab562d636c0f4809fd64bb0bb674916e8">llvm::M68kFrameLowering::emitPrologue</a>.</p>

</div>
</div>

### GetCondBranchFromCond() {#a53befb9ac81cf6c262c28640cb6c5425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::M68k::GetCondBranchFromCond (<a href="#a3ae7fc35b1e164744d5f085ff1e84039">M68k::CondCode</a> CC)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrinfo-h">M68kInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a7febd5dc3ed75138f38cc36cf0e30fcc">COND_CC</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039aa25f8b0ba8ef8c152fcb4d880ee5d387">COND_CS</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039ac148f8930d127f0c09a35848ad30419e">COND_EQ</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039af0e55f79c4cd6282754ac1bc5417573f">COND_GE</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a9fa23e50c543dbc8e4199a4b2d86464e">COND_GT</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039ab92c3630f32ebf09ebfffab9305bbd58">COND_HI</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a251eb0798d4ebad8afda15f84916869a">COND_LE</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039ae0e66410bd55b220017e4ff5c244ca21">COND_LS</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a99ca08e883ff21904ad2afcf58ac5b36">COND_LT</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a2e5ed258170cfe7b8b2b759e3382fba2">COND_MI</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039aa901317a44b0be9a1ac4067028524bd6">COND_NE</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039ad7801a76a67f06e7074b6e7e82b63cb9">COND_PL</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a4e035f352a713e4c58b6b6e306a19a8b">COND_VC</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a8676b3e7eaf6d79f9b2cb242776b831a">COND_VS</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### GetCondFromBranchOpc() {#af68462432be0df20e086eea034fe3cc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">M68k::CondCode llvm::M68k::GetCondFromBranchOpc (unsigned Opcode)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrinfo-h">M68kInstrInfo.h</a>.</p>


<p>References <a href="#a3ae7fc35b1e164744d5f085ff1e84039a7febd5dc3ed75138f38cc36cf0e30fcc">COND_CC</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039aa25f8b0ba8ef8c152fcb4d880ee5d387">COND_CS</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039ac148f8930d127f0c09a35848ad30419e">COND_EQ</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039af0e55f79c4cd6282754ac1bc5417573f">COND_GE</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a9fa23e50c543dbc8e4199a4b2d86464e">COND_GT</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039ab92c3630f32ebf09ebfffab9305bbd58">COND_HI</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a5033e89fe93b7cbea4d857dadb79c110">COND_INVALID</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a251eb0798d4ebad8afda15f84916869a">COND_LE</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039ae0e66410bd55b220017e4ff5c244ca21">COND_LS</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a99ca08e883ff21904ad2afcf58ac5b36">COND_LT</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a2e5ed258170cfe7b8b2b759e3382fba2">COND_MI</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039aa901317a44b0be9a1ac4067028524bd6">COND_NE</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039ad7801a76a67f06e7074b6e7e82b63cb9">COND_PL</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a4e035f352a713e4c58b6b6e306a19a8b">COND_VC</a> and <a href="#a3ae7fc35b1e164744d5f085ff1e84039a8676b3e7eaf6d79f9b2cb242776b831a">COND_VS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a5fbf08fc2002106c8e39caa9c2c84cd8">llvm::M68kInstrInfo::AnalyzeBranchImpl</a>.</p>

</div>
</div>

### getMCInstrBeads() {#a6dcd23cc95df1990a383ced27f964dbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t * llvm::M68k::getMCInstrBeads (unsigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kmccodeemitter-h">M68kMCCodeEmitter.h</a>.</p>

</div>
</div>

### GetOppositeBranchCondition() {#a876bb5be568d372d0a658d2ea5927b74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">M68k::CondCode llvm::M68k::GetOppositeBranchCondition (<a href="#a3ae7fc35b1e164744d5f085ff1e84039">M68k::CondCode</a> CC)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrinfo-h">M68kInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a7febd5dc3ed75138f38cc36cf0e30fcc">COND_CC</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039aa25f8b0ba8ef8c152fcb4d880ee5d387">COND_CS</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039ac148f8930d127f0c09a35848ad30419e">COND_EQ</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a327a900d4ac7d27518a53bc7c1731ee5">COND_F</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039af0e55f79c4cd6282754ac1bc5417573f">COND_GE</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a9fa23e50c543dbc8e4199a4b2d86464e">COND_GT</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039ab92c3630f32ebf09ebfffab9305bbd58">COND_HI</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a251eb0798d4ebad8afda15f84916869a">COND_LE</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039ae0e66410bd55b220017e4ff5c244ca21">COND_LS</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a99ca08e883ff21904ad2afcf58ac5b36">COND_LT</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a2e5ed258170cfe7b8b2b759e3382fba2">COND_MI</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039aa901317a44b0be9a1ac4067028524bd6">COND_NE</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039ad7801a76a67f06e7074b6e7e82b63cb9">COND_PL</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a173d46f3ad7ff4516cc52336b2949f13">COND_T</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a4e035f352a713e4c58b6b6e306a19a8b">COND_VC</a>, <a href="#a3ae7fc35b1e164744d5f085ff1e84039a8676b3e7eaf6d79f9b2cb242776b831a">COND_VS</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### isCalleePop() {#a6c0593d90ef80873966d1556f7a715eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68k::isCalleePop (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, bool IsVarArg, bool GuaranteeTCO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determines whether the callee is required to pop its own arguments.</p>


<p>Callee pop is necessary to support tail calls.</p>


<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-h">M68kISelLowering.h</a>, definition at line 3046 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp">M68kISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafb7645aeee7db3640bbfdad799b4cfe9">llvm::CallingConv::M68k_RTD</a>.</p>

</div>
</div>

### IsCMP() {#a27cf406d028f2c6c883efe8b68b3fe17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::M68k::IsCMP (unsigned Op)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrinfo-h">M68kInstrInfo.h</a>.</p>

</div>
</div>

### IsSETCC() {#a00afcb12e9f6d7c5a926191b6eb31fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68k::IsSETCC (unsigned SETCC)</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrinfo-h">M68kInstrInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#a20572d2a5543e9ee62228ec92cabc614">isAndOrOfSetCCs</a>.</p>

</div>
</div>

### swapWord() {#aa0afd3ff35e9b67d4c567f6ec5ba2a3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">value_t llvm::M68k::swapWord (value_t Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kbaseinfo-h">M68kBaseInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbad861877da56b8b4ceb35c8cbfdf65bb4">llvm::big</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a108ca68c609b3e8c00918a68d26905fa">llvm::support::endian::byte_swap</a> and <a href="#ab3a288f2953d8eca3e363959fc2cf38ea4c614360da93c0a041b22e537de151eb">U</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/disassembler/m68kdisassembler-cpp/#afa1548b0f3e2e5c945f4e6ffa8a84de8">DecodeImm32</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kmccodeemitter-cpp-/m68kmccodeemitter/#ae9def4fef17a8e66265e30f687158adf">anonymous{M68kMCCodeEmitter.cpp}::M68kMCCodeEmitter::encodePCRelImm</a> and <a href="/web-llvm/docs/api/classes/anonymous-m68kmccodeemitter-cpp-/m68kmccodeemitter/#a642ca54e0f1605190dcf5a216d2b10b6">anonymous{M68kMCCodeEmitter.cpp}::M68kMCCodeEmitter::encodeRelocImm</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### PartMappings {#a26fbbdf685b18f9d12aaa5babc259bdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::PartialMapping llvm::M68k::PartMappings[]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
    {0, 32, GPRRegBank},
}
</div>
</dd>
</dl>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kregisterbankinfo-cpp">M68kRegisterBankInfo.cpp</a>.</p>

</div>
</div>

### ValueMappings {#a3ab41b597a967d9fb5ff98f2fa88ecea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::ValueMapping llvm::M68k::ValueMappings[]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    {nullptr, 0},
    {&amp;<a href="#a26fbbdf685b18f9d12aaa5babc259bdf">PartMappings</a>[<a href="#ad9fcd2b8d1e679cb14ae3d4f08b8d7a6ae2401fa18c8df5bd4d85315a6a20928a">PMI_GPR</a> - <a href="#ad9fcd2b8d1e679cb14ae3d4f08b8d7a6a960176b21d3ea95d3701060a13828edb">PMI_Min</a>], 1},
    {&amp;<a href="#a26fbbdf685b18f9d12aaa5babc259bdf">PartMappings</a>[<a href="#ad9fcd2b8d1e679cb14ae3d4f08b8d7a6ae2401fa18c8df5bd4d85315a6a20928a">PMI_GPR</a> - <a href="#ad9fcd2b8d1e679cb14ae3d4f08b8d7a6a960176b21d3ea95d3701060a13828edb">PMI_Min</a>], 1},
    {&amp;<a href="#a26fbbdf685b18f9d12aaa5babc259bdf">PartMappings</a>[<a href="#ad9fcd2b8d1e679cb14ae3d4f08b8d7a6ae2401fa18c8df5bd4d85315a6a20928a">PMI_GPR</a> - <a href="#ad9fcd2b8d1e679cb14ae3d4f08b8d7a6a960176b21d3ea95d3701060a13828edb">PMI_Min</a>], 1},
}
</div>
</dd>
</dl>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kregisterbankinfo-cpp">M68kRegisterBankInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kregisterbankinfo/#a1c1174fbc250d7fa3773584dfd942728">llvm::M68kRegisterBankInfo::getInstrMapping</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kregisterbankinfo-cpp">M68kRegisterBankInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrbuilder-h">M68kInstrBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrinfo-h">M68kInstrInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp">M68kISelLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-h">M68kISelLowering.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kbaseinfo-h">M68kBaseInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kmccodeemitter-h">M68kMCCodeEmitter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
