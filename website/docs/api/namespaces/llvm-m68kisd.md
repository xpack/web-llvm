---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/m68kisd
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `M68kISD` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::M68kISD { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeType { <a href="#a5d785b7c28047e4e75d1fed254de7a5e">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/m68k">M68k</a> Specific DAG nodes. <a href="#a5d785b7c28047e4e75d1fed254de7a5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### NodeType {#a5d785b7c28047e4e75d1fed254de7a5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::M68kISD::NodeType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/m68k">M68k</a> Specific DAG nodes.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_NUMBER<a id="a5d785b7c28047e4e75d1fed254de7a5ea5e36cb9cb8aedef936d5a48f0d97a774"></a></td>
<td class="doxyEnumItemDescription">Start the numbering from where <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a> <a href="#a5d785b7c28047e4e75d1fed254de7a5e">NodeType</a> finishes (= ISD::BUILTIN_OP_END)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL<a id="a5d785b7c28047e4e75d1fed254de7a5ea1db213bd07ce5797d4c6c3e562633136"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RET<a id="a5d785b7c28047e4e75d1fed254de7a5ead7fa9da10b119eb169b7ae6e431c3321"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TAIL_CALL<a id="a5d785b7c28047e4e75d1fed254de7a5ea0b774ceea90d005ee910880a2e770741"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TC_RETURN<a id="a5d785b7c28047e4e75d1fed254de7a5ea829a1972c7442908f3935a785a9b3db6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMP<a id="a5d785b7c28047e4e75d1fed254de7a5ea8cd87958bea756c6a27ff00b667d10e0"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/m68k">M68k</a> compare and logical compare instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BTST<a id="a5d785b7c28047e4e75d1fed254de7a5ea87f0b18bdb27dba8e523209a37f8d8f4"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/m68k">M68k</a> bit-test instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SELECT<a id="a5d785b7c28047e4e75d1fed254de7a5ea9dfbb88925ed7d9c06cde456b295708c"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/m68k">M68k</a> Select</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETCC<a id="a5d785b7c28047e4e75d1fed254de7a5ea033ef30df6deed20a9acd5926e3cfc93"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/m68k">M68k</a> SetCC</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETCC_CARRY<a id="a5d785b7c28047e4e75d1fed254de7a5eaed343786427d2174402ccc304a81d970"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMOV<a id="a5d785b7c28047e4e75d1fed254de7a5ea875e4b0821b79e23c773e7c705cf843a"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/m68k">M68k</a> conditional moves</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRCOND<a id="a5d785b7c28047e4e75d1fed254de7a5ea35a9ba2758babaf9c667261acff12ffd"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/m68k">M68k</a> conditional branches</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADD<a id="a5d785b7c28047e4e75d1fed254de7a5eaf8b75b447c76089aba1761b873b3462c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUB<a id="a5d785b7c28047e4e75d1fed254de7a5ea620f48dc3793e755e23c4a52570a5fe8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDX<a id="a5d785b7c28047e4e75d1fed254de7a5ea6483d80f9b2ff70477d2fd61b8d08807"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUBX<a id="a5d785b7c28047e4e75d1fed254de7a5eadbdde4bf9f22db5a9e564351a5437fc4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMUL<a id="a5d785b7c28047e4e75d1fed254de7a5ea99b6d187f1021ef66370caed88095539"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMUL<a id="a5d785b7c28047e4e75d1fed254de7a5ea8a765bf18d667f80f45c7e7b4eee58c4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OR<a id="a5d785b7c28047e4e75d1fed254de7a5eac466515b1e5dbfb481f72f2371699621"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XOR<a id="a5d785b7c28047e4e75d1fed254de7a5ea4f670d05d6a5596bcd962fd02daf268a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AND<a id="a5d785b7c28047e4e75d1fed254de7a5eaf4c94f423b53b11430662946883231d2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLOBAL_BASE_REG<a id="a5d785b7c28047e4e75d1fed254de7a5eaf4ce8c5d66fc94f7573b82c3ace0491b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Wrapper<a id="a5d785b7c28047e4e75d1fed254de7a5eaf0a730a8c230a66750922a4708e16963"></a></td>
<td class="doxyEnumItemDescription">A wrapper node for TargetConstantPool, TargetExternalSymbol, and TargetGlobalAddress</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WrapperPC<a id="a5d785b7c28047e4e75d1fed254de7a5eae5220eb9816fbc61516f67a9d7fbbaeb"></a></td>
<td class="doxyEnumItemDescription">Special wrapper used under <a href="/web-llvm/docs/api/namespaces/llvm/m68k">M68k</a> PIC mode for PC relative displacements</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SEG_ALLOCA<a id="a5d785b7c28047e4e75d1fed254de7a5ea19046ca67fbf7a4aa0ee960c86d82afe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-h">M68kISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-h">M68kISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
