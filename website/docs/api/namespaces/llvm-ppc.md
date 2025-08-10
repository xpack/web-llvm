---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/ppc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `PPC` Namespace

<p>Define some predicates that are used for node matching. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::PPC { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ppc/cpuinfo">CPUInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Fixups { <a href="#aa53de88164b98be6cd073da9543c0450">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Predicate { <a href="#a14028f7fe73a11dabc6583510cc0a355">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/predicate">Predicate</a> - These are "(BI &lt;&lt; 5) | BO" for various predicates. <a href="#a14028f7fe73a11dabc6583510cc0a355">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">BranchHintBit { <a href="#a8144d2e1978b3e3a226233c0b93b92f4">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">MemOpFlags { <a href="#abdd78226dbbe3ffe081cffb3c9e76d80">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">AddrMode { <a href="#a6965a3973aa13b20ebaee31424136dcd">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#afabcc2ff4ea75ff845f97b0807e8de34">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c4695a9cfc9ce20f0c6d8291aca7de">isValidCPU</a> (StringRef CPU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb39db9b40af23175d5d8f3fd556f783">fillValidCPUList</a> (SmallVectorImpl&lt; StringRef &gt; &amp;Values)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6dc8778068867ea9a9597c8ef51a45a">fillValidTuneCPUList</a> (SmallVectorImpl&lt; StringRef &gt; &amp;Values)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f432b141d17384c56f11e55de61aff7">getNormalizedPPCTargetCPU</a> (const Triple &amp;T, StringRef CPUName="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebcdb4ac767d9a75c5c9e79450fb75d3">getNormalizedPPCTuneCPU</a> (const Triple &amp;T, StringRef CPUName="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3c196667a91fdc81783769feab2e89">normalizeCPUName</a> (StringRef CPUName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ddf0f8e0c9ad93a6c3a893df96ef599">stripRegisterPrefix</a> (const char *RegName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>stripRegisterPrefix - This method strips the character prefix from a register name so that only the number is left. <a href="#a2ddf0f8e0c9ad93a6c3a893df96ef599">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad88de25fc56e9402b64e705bc84143b2">getRegNumForOperand</a> (const MCInstrDesc &amp;Desc, unsigned Reg, unsigned OpNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getRegNumForOperand - some operands use different numbering schemes for the same registers. <a href="#ad88de25fc56e9402b64e705bc84143b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc7a469d7d5e4183e2b84d15072786cf">isVFRegister</a> (unsigned Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5436d12d95e36064db97636d22f20988">isVRRegister</a> (unsigned Reg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a14028f7fe73a11dabc6583510cc0a355">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a975319b2f772b89387ffea1b1ba1f049">InvertPredicate</a> (Predicate Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Invert the specified predicate. != -&gt; ==, &lt; -&gt; &gt;=. <a href="#a975319b2f772b89387ffea1b1ba1f049">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a14028f7fe73a11dabc6583510cc0a355">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12c2165ec169065a665bc3a9fcacea89">getSwappedPredicate</a> (Predicate Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assume the condition register is set by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI(a,b)</a>, return the predicate if we modify the instructions such that condition register is set by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI(b,a)</a>. <a href="#a12c2165ec169065a665bc3a9fcacea89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2624042e885fc1d665e8fc01a0ab390b">getPredicateCondition</a> (Predicate Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the condition without hint bits. <a href="#a2624042e885fc1d665e8fc01a0ab390b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f7348f565ebb68dc08979b2808300c5">getPredicateHint</a> (Predicate Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the hint bits of the predicate. <a href="#a5f7348f565ebb68dc08979b2808300c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a14028f7fe73a11dabc6583510cc0a355">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c2294c9ecba721df7f29aaf05157d8">getPredicate</a> (unsigned Condition, unsigned Hint)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return predicate consisting of specified condition and hint bits. <a href="#a40c2294c9ecba721df7f29aaf05157d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2108c96efd9d9e1b89dd25b89a23ed1a">getNonRecordFormOpcode</a> (uint16_t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee91c58b3a130d49788e05c85b12dce4">isVPKUHUMShuffleMask</a> (ShuffleVectorSDNode *N, unsigned ShuffleKind, SelectionDAG &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isVPKUHUMShuffleMask - Return true if this is the shuffle mask for a VPKUHUM instruction. <a href="#aee91c58b3a130d49788e05c85b12dce4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9f806005e684e4cbd25d76849ee1775">isVPKUWUMShuffleMask</a> (ShuffleVectorSDNode *N, unsigned ShuffleKind, SelectionDAG &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isVPKUWUMShuffleMask - Return true if this is the shuffle mask for a VPKUWUM instruction. <a href="#ae9f806005e684e4cbd25d76849ee1775">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43b885afb337e155a5f9e5257081de8b">isVPKUDUMShuffleMask</a> (ShuffleVectorSDNode *N, unsigned ShuffleKind, SelectionDAG &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isVPKUDUMShuffleMask - Return true if this is the shuffle mask for a VPKUDUM instruction. <a href="#a43b885afb337e155a5f9e5257081de8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab27448838ea5635fa836a68c3aa97b29">isVMRGLShuffleMask</a> (ShuffleVectorSDNode *N, unsigned UnitSize, unsigned ShuffleKind, SelectionDAG &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isVMRGLShuffleMask - Return true if this is a shuffle mask suitable for a VRGL* instruction with the specified unit size (1,2 or 4 bytes). <a href="#ab27448838ea5635fa836a68c3aa97b29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f48ceee4d4e7b13efb21c415b8fc330">isVMRGHShuffleMask</a> (ShuffleVectorSDNode *N, unsigned UnitSize, unsigned ShuffleKind, SelectionDAG &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isVMRGHShuffleMask - Return true if this is a shuffle mask suitable for a VRGH* instruction with the specified unit size (1,2 or 4 bytes). <a href="#a3f48ceee4d4e7b13efb21c415b8fc330">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5abe83e8c9d9553cfc708a024c204807">isVMRGEOShuffleMask</a> (ShuffleVectorSDNode *N, bool CheckEven, unsigned ShuffleKind, SelectionDAG &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isVMRGEOShuffleMask - Return true if this is a shuffle mask suitable for a VMRGEW or VMRGOW instruction <a href="#a5abe83e8c9d9553cfc708a024c204807">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96447619c3b90a88e75aed44d332114c">isXXSLDWIShuffleMask</a> (ShuffleVectorSDNode *N, unsigned &amp;ShiftElts, bool &amp;Swap, bool IsLE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isXXSLDWIShuffleMask - Return true if this is a shuffle mask suitable for a XXSLDWI instruction. <a href="#a96447619c3b90a88e75aed44d332114c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bc23d2b734425aad94289c4dc5df21f">isXXBRHShuffleMask</a> (ShuffleVectorSDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isXXBRHShuffleMask - Return true if this is a shuffle mask suitable for a XXBRH instruction. <a href="#a8bc23d2b734425aad94289c4dc5df21f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88c93b88a2a89e226d5312299a4e1790">isXXBRWShuffleMask</a> (ShuffleVectorSDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isXXBRWShuffleMask - Return true if this is a shuffle mask suitable for a XXBRW instruction. <a href="#a88c93b88a2a89e226d5312299a4e1790">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a25cc9341eead72b29eb9646e631244">isXXBRDShuffleMask</a> (ShuffleVectorSDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isXXBRDShuffleMask - Return true if this is a shuffle mask suitable for a XXBRD instruction. <a href="#a2a25cc9341eead72b29eb9646e631244">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e40fdad18c650272628e91ecadce173">isXXBRQShuffleMask</a> (ShuffleVectorSDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isXXBRQShuffleMask - Return true if this is a shuffle mask suitable for a XXBRQ instruction. <a href="#a6e40fdad18c650272628e91ecadce173">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bbd98a4e85245f40c2ef2ea6f14e7c6">isXXPERMDIShuffleMask</a> (ShuffleVectorSDNode *N, unsigned &amp;ShiftElts, bool &amp;Swap, bool IsLE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isXXPERMDIShuffleMask - Return true if this is a shuffle mask suitable for a XXPERMDI instruction. <a href="#a8bbd98a4e85245f40c2ef2ea6f14e7c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa45ea0323da7012ed4e0f58aef3619bb">isVSLDOIShuffleMask</a> (SDNode *N, unsigned ShuffleKind, SelectionDAG &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isVSLDOIShuffleMask - If this is a vsldoi shuffle mask, return the shift amount, otherwise return -1. <a href="#aa45ea0323da7012ed4e0f58aef3619bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf912033ee385662cb4e40bd06206b67">isSplatShuffleMask</a> (ShuffleVectorSDNode *N, unsigned EltSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isSplatShuffleMask - Return true if the specified VECTOR_SHUFFLE operand specifies a splat of a single element that is suitable for input to VSPLTB/VSPLTH/VSPLTW. <a href="#adf912033ee385662cb4e40bd06206b67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb2d86096213925077b7a8b248745e34">isXXINSERTWMask</a> (ShuffleVectorSDNode *N, unsigned &amp;ShiftElts, unsigned &amp;InsertAtByte, bool &amp;Swap, bool IsLE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isXXINSERTWMask - Return true if this VECTOR_SHUFFLE can be handled by the XXINSERTW instruction introduced in ISA 3.0. <a href="#acb2d86096213925077b7a8b248745e34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93d85169d871f169e06ab00673048741">getSplatIdxForPPCMnemonics</a> (SDNode *N, unsigned EltSize, SelectionDAG &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSplatIdxForPPCMnemonics - Return the splat index as a value that is appropriate for <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> mnemonics (which have a big endian bias - namely elements are counted from the left of the vector register). <a href="#a93d85169d871f169e06ab00673048741">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a14301103c8d97e52ed0ca117ea6b65">get_VSPLTI_elt</a> (SDNode *N, unsigned ByteSize, SelectionDAG &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>get_VSPLTI_elt - If this is a build_vector of constants which can be formed by using a vspltis[bhw] instruction of the specified element size, return the constant being splatted. <a href="#a1a14301103c8d97e52ed0ca117ea6b65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cd7fb94f62f409bc4faf2a20e0904eb">createFastISel</a> (FunctionLoweringInfo &amp;FuncInfo, const TargetLibraryInfo *LibInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1545caeeda8de7bd87be034c59b2b9fe">getAltVSXFMAOpcode</a> (uint16_t Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/ppc/cpuinfo">CPUInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb89f3ed94ebc20c424d49c2dfc3e402">getCPUInfoByName</a> (StringRef CPU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/structs/llvm/ppc/cpuinfo">CPUInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dfd53b3d1c77880541a7619dc287f39">PPCCPUInfo</a>[] = ...</td>
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

### anonymous enum  {#afabcc2ff4ea75ff845f97b0807e8de34}

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


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_NONE<a id="afabcc2ff4ea75ff845f97b0807e8de34abf20d995fb8903fac5baf09797e6ed80"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_32<a id="afabcc2ff4ea75ff845f97b0807e8de34aba3e2f71e6bcfa95d8ef5836ba47f02f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_440<a id="afabcc2ff4ea75ff845f97b0807e8de34a7b91cd4044a62473da3166dd0d2b2ddc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_601<a id="afabcc2ff4ea75ff845f97b0807e8de34afdebe93c0e18a5453835f8df1c13e5e4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_602<a id="afabcc2ff4ea75ff845f97b0807e8de34a62ee0718349ae36cd1a8ed500abcd878"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_603<a id="afabcc2ff4ea75ff845f97b0807e8de34a3962994d8e938b9593218caf575ef6bd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_7400<a id="afabcc2ff4ea75ff845f97b0807e8de34a6cdba3048334fa40e8f46956ffeab0c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_750<a id="afabcc2ff4ea75ff845f97b0807e8de34aa77883b2e65039199cd95b624cab29b2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_970<a id="afabcc2ff4ea75ff845f97b0807e8de34a56adb1ba4082b00854c8401847ade1a9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_A2<a id="afabcc2ff4ea75ff845f97b0807e8de34ab81d0aba13bef5a963bb14709390283e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_E500<a id="afabcc2ff4ea75ff845f97b0807e8de34aa3892c789487c6e4d64043ae996717ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_E500mc<a id="afabcc2ff4ea75ff845f97b0807e8de34a00d4f7d7f8d110db90749f417fceff3a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_E5500<a id="afabcc2ff4ea75ff845f97b0807e8de34ac4e6bb06de05f2620850b3fc53a0433e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_PWR3<a id="afabcc2ff4ea75ff845f97b0807e8de34a80679195ad86168a8664a9ee102ce948"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_PWR4<a id="afabcc2ff4ea75ff845f97b0807e8de34a1a9618f9addb07ce52555fa524ccf39d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_PWR5<a id="afabcc2ff4ea75ff845f97b0807e8de34a690b5c342106c270b005123adec2d7e6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_PWR5X<a id="afabcc2ff4ea75ff845f97b0807e8de34a40aa4eed5523516b6f4be5d29307b5cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_PWR6<a id="afabcc2ff4ea75ff845f97b0807e8de34aa2b626cb4809ee8a3b3da9d475eabe05"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_PWR6X<a id="afabcc2ff4ea75ff845f97b0807e8de34a664d0abca2c75f8a6f8ce2dcc21cd676"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_PWR7<a id="afabcc2ff4ea75ff845f97b0807e8de34a0c8a5dd168df904e8c29520a47502a61"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_PWR8<a id="afabcc2ff4ea75ff845f97b0807e8de34aa3de856d909c5b0166919bf6e4bd1a3d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_PWR9<a id="afabcc2ff4ea75ff845f97b0807e8de34a0a03bfd83c00f4d1edab975b7bfe7f36"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_PWR10<a id="afabcc2ff4ea75ff845f97b0807e8de34a1a5dee2be7c154497739282b30ab123c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_PWR11<a id="afabcc2ff4ea75ff845f97b0807e8de34af6a785f2b13ce7870e8e4e6b9653f32f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_PWR_FUTURE<a id="afabcc2ff4ea75ff845f97b0807e8de34ac1fc2f6d654da4e5a6a601e19d423846"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIR_64<a id="afabcc2ff4ea75ff845f97b0807e8de34a00917bbd257bd4ee796f398e9c563a11"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>

</div>
</div>

### AddrMode {#a6965a3973aa13b20ebaee31424136dcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::PPC::AddrMode </td>
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
<td class="doxyEnumItemName">AM_None<a id="a6965a3973aa13b20ebaee31424136dcda319ec6c4a7dda0fbaf3b177aa1dd57a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AM_DForm<a id="a6965a3973aa13b20ebaee31424136dcda14463e6ffd7cc9fd0b93c79fe4856931"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AM_DSForm<a id="a6965a3973aa13b20ebaee31424136dcdafbe45acde65a4870e22102ab63f4643c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AM_DQForm<a id="a6965a3973aa13b20ebaee31424136dcda40a73e5d0d8196bfe33b2866c06d870d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AM_PrefixDForm<a id="a6965a3973aa13b20ebaee31424136dcda5615f105433d37ceb5557243c2ff09cb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AM_XForm<a id="a6965a3973aa13b20ebaee31424136dcdaaac3056a5c906602555ed94a3636077c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AM_PCRel<a id="a6965a3973aa13b20ebaee31424136dcdab748f1b6c866a08f2b1e5a2216e8e73d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 742 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>

</div>
</div>

### BranchHintBit {#a8144d2e1978b3e3a226233c0b93b92f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::PPC::BranchHintBit </td>
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
<td class="doxyEnumItemName">BR_NO_HINT<a id="a8144d2e1978b3e3a226233c0b93b92f4ac7dfdcda0d275c86f35bf9ad77cd8cb0"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BR_NONTAKEN_HINT<a id="a8144d2e1978b3e3a226233c0b93b92f4a23b3b31d33f39cc6e7ed25eb61fe1991"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BR_TAKEN_HINT<a id="a8144d2e1978b3e3a226233c0b93b92f4af4e0cd42db406ff2bf838a277e07dcf7"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BR_HINT_MASK<a id="a8144d2e1978b3e3a226233c0b93b92f4a5df95ff204e7992373cbe6b8ab6b1e79"></a></td>
<td class="doxyEnumItemDescription"> (= 0X3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcpredicates-h">PPCPredicates.h</a>.</p>

</div>
</div>

### Fixups {#aa53de88164b98be6cd073da9543c0450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::PPC::Fixups </td>
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
<td class="doxyEnumItemName">fixup_ppc_br24<a id="aa53de88164b98be6cd073da9543c0450a058440145aa9ecc1725824fc1a47d50d"></a></td>
<td class="doxyEnumItemDescription"> (= FirstTargetFixupKind)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ppc_br24_notoc<a id="aa53de88164b98be6cd073da9543c0450a7529efd48ae862b862618c78039c6876"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ppc_brcond14<a id="aa53de88164b98be6cd073da9543c0450a7c601a9dd02f749390ca0dc194c22e0f"></a></td>
<td class="doxyEnumItemDescription">14-bit PC relative relocation for conditional branches</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ppc_br24abs<a id="aa53de88164b98be6cd073da9543c0450aeb0a8f988a6ad575c39e57767994fae9"></a></td>
<td class="doxyEnumItemDescription">24-bit absolute relocation for direct branches like 'ba' and 'bla'</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ppc_brcond14abs<a id="aa53de88164b98be6cd073da9543c0450a2379567960e1dddd9bde02874a1d9fda"></a></td>
<td class="doxyEnumItemDescription">14-bit absolute relocation for conditional branches</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ppc_half16<a id="aa53de88164b98be6cd073da9543c0450a2cd2bd91cc9938c81599c5e8828addcd"></a></td>
<td class="doxyEnumItemDescription">A 16-bit fixup corresponding to lo16(_foo) or ha16(_foo) for instrs like 'li' or 'addis'</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ppc_half16ds<a id="aa53de88164b98be6cd073da9543c0450aa91622fd93be671ff6340f4a1716fc57"></a></td>
<td class="doxyEnumItemDescription">A 14-bit fixup corresponding to lo16(_foo) with implied 2 zero bits for instrs like 'std'</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ppc_pcrel34<a id="aa53de88164b98be6cd073da9543c0450a1379c8f82d3710fa8ea6c986230cf6b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ppc_imm34<a id="aa53de88164b98be6cd073da9543c0450af5b83e08ebd4d2d64ffaa1cad54eb3ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ppc_nofixup<a id="aa53de88164b98be6cd073da9543c0450ab8c5d5569d95351dc5441109ca5318d2"></a></td>
<td class="doxyEnumItemDescription">Not a true fixup, but ties a symbol to a call to __tls_get_addr for the TLS general and local dynamic models, or inserts the thread-pointer register number</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ppc_half16dq<a id="aa53de88164b98be6cd073da9543c0450aa14de08bc8d45995199ed5b534e91b2a"></a></td>
<td class="doxyEnumItemDescription">A 16-bit fixup corresponding to lo16(_foo) with implied 3 zero bits for instrs like 'lxv'</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastTargetFixupKind<a id="aa53de88164b98be6cd073da9543c0450a5f97639e0fabfe42c2730f1283a90f3e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumTargetFixupKinds<a id="aa53de88164b98be6cd073da9543c0450a5b0265633bc8d4897bf5d6a8339c7b26"></a></td>
<td class="doxyEnumItemDescription"> (= LastTargetFixupKind - FirstTargetFixupKind)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcfixupkinds-h">PPCFixupKinds.h</a>.</p>

</div>
</div>

### MemOpFlags {#abdd78226dbbe3ffe081cffb3c9e76d80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::PPC::MemOpFlags </td>
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
<td class="doxyEnumItemName">MOF_None<a id="abdd78226dbbe3ffe081cffb3c9e76d80a2352da11a2bf61ae32dd447ab28ef2d7"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_SExt<a id="abdd78226dbbe3ffe081cffb3c9e76d80aa0e9765faa99e16f3f77891096e1a4c0"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_ZExt<a id="abdd78226dbbe3ffe081cffb3c9e76d80a34a67c2b0e58a27b547fc3f6edab50fa"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_NoExt<a id="abdd78226dbbe3ffe081cffb3c9e76d80a5888d77039ff78746d9ea8e4e218dfda"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_NotAddNorCst<a id="abdd78226dbbe3ffe081cffb3c9e76d80a39dce6c6e9c3f0bca83f48faf02267a3"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_RPlusSImm16<a id="abdd78226dbbe3ffe081cffb3c9e76d80a3d549266ccdcd583d15c88dfaa9e7e4a"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_RPlusLo<a id="abdd78226dbbe3ffe081cffb3c9e76d80ad559259939478cfc1e6b96bffd48e984"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_RPlusSImm16Mult4<a id="abdd78226dbbe3ffe081cffb3c9e76d80a9da404662425b672e194e163961479a3"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_RPlusSImm16Mult16<a id="abdd78226dbbe3ffe081cffb3c9e76d80a24a8014075c447b950e6ae5b5dec8587"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_RPlusSImm34<a id="abdd78226dbbe3ffe081cffb3c9e76d80a9b668ad2bc8ce251393fad3ee3243948"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_RPlusR<a id="abdd78226dbbe3ffe081cffb3c9e76d80a8ab07220ca2843f4957418b71b270feb"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_PCRel<a id="abdd78226dbbe3ffe081cffb3c9e76d80a85dc8483654345136c685a2ea5e1289c"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_AddrIsSImm32<a id="abdd78226dbbe3ffe081cffb3c9e76d80ad344a01b52e5179abac75ab1b8dd1206"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_SubWordInt<a id="abdd78226dbbe3ffe081cffb3c9e76d80a96449374a0e05655d2d6629086c3987f"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_WordInt<a id="abdd78226dbbe3ffe081cffb3c9e76d80ae2be36186859286206cbd97dc615c8e8"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_DoubleWordInt<a id="abdd78226dbbe3ffe081cffb3c9e76d80a77745d9235db1594c3fc34ccfda3a328"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_ScalarFloat<a id="abdd78226dbbe3ffe081cffb3c9e76d80a211da1f8a39e74696bc1ed77a6e4ae53"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_Vector<a id="abdd78226dbbe3ffe081cffb3c9e76d80a65a49a9801dc3ddde68d360e5ccacc26"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_Vector256<a id="abdd78226dbbe3ffe081cffb3c9e76d80a69d80889b6dd8adc73d19c115248c4bf"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_SubtargetBeforeP9<a id="abdd78226dbbe3ffe081cffb3c9e76d80a7242650bdadf1b93569ad54074062ea1"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_SubtargetP9<a id="abdd78226dbbe3ffe081cffb3c9e76d80ad3634a8cd9f1aea8b0195b90947a03dd"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_SubtargetP10<a id="abdd78226dbbe3ffe081cffb3c9e76d80a0693f1a70645b32307928b28df4ed5c9"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOF_SubtargetSPE<a id="abdd78226dbbe3ffe081cffb3c9e76d80afbbf2421c7a07379ce4e1b2c5d819e28"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 25)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 707 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>

</div>
</div>

### Predicate {#a14028f7fe73a11dabc6583510cc0a355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::PPC::Predicate </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/predicate">Predicate</a> - These are "(BI &lt;&lt; 5) | BO" for various predicates.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_LT<a id="a14028f7fe73a11dabc6583510cc0a355a46cd6e935d7b9cc679d9cb0cf025ae91"></a></td>
<td class="doxyEnumItemDescription"> (= (0 &lt;&lt; 5) | 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_LE<a id="a14028f7fe73a11dabc6583510cc0a355ac89b6a30c033abb18a7e81f48b0e3593"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 5) |  4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_EQ<a id="a14028f7fe73a11dabc6583510cc0a355a34be5288a1bb24e5120358395f7f0dc3"></a></td>
<td class="doxyEnumItemDescription"> (= (2 &lt;&lt; 5) | 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_GE<a id="a14028f7fe73a11dabc6583510cc0a355a44abec85091b571da2189ac4bd139095"></a></td>
<td class="doxyEnumItemDescription"> (= (0 &lt;&lt; 5) |  4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_GT<a id="a14028f7fe73a11dabc6583510cc0a355a8cd4d49277068c1eab8d4d7c4835b817"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 5) | 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_NE<a id="a14028f7fe73a11dabc6583510cc0a355ad9add708b3d9680d64242cf06f448462"></a></td>
<td class="doxyEnumItemDescription"> (= (2 &lt;&lt; 5) |  4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_UN<a id="a14028f7fe73a11dabc6583510cc0a355a89f893823745c8d91bb4d7d83e247cb6"></a></td>
<td class="doxyEnumItemDescription"> (= (3 &lt;&lt; 5) | 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_NU<a id="a14028f7fe73a11dabc6583510cc0a355a94061699653bc6df4c3809c7a4d44ac9"></a></td>
<td class="doxyEnumItemDescription"> (= (3 &lt;&lt; 5) |  4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_LT_MINUS<a id="a14028f7fe73a11dabc6583510cc0a355a33e681071c4ec83f4c4cc4855fc1ed1e"></a></td>
<td class="doxyEnumItemDescription"> (= (0 &lt;&lt; 5) | 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_LE_MINUS<a id="a14028f7fe73a11dabc6583510cc0a355aa55740b85ae5278b5e206d20eeef303a"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 5) |  6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_EQ_MINUS<a id="a14028f7fe73a11dabc6583510cc0a355ada22e0b2b224aa2dc5e2266546424f39"></a></td>
<td class="doxyEnumItemDescription"> (= (2 &lt;&lt; 5) | 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_GE_MINUS<a id="a14028f7fe73a11dabc6583510cc0a355aa0cb1db9aa5842fc89b7590d4a78d22a"></a></td>
<td class="doxyEnumItemDescription"> (= (0 &lt;&lt; 5) |  6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_GT_MINUS<a id="a14028f7fe73a11dabc6583510cc0a355ab4bb503de9d2ddcb886c924fbcdc9042"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 5) | 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_NE_MINUS<a id="a14028f7fe73a11dabc6583510cc0a355aaefab7058909f2616746f6d8244a118e"></a></td>
<td class="doxyEnumItemDescription"> (= (2 &lt;&lt; 5) |  6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_UN_MINUS<a id="a14028f7fe73a11dabc6583510cc0a355a76dfc226a98ea8caf3c545fa54889b19"></a></td>
<td class="doxyEnumItemDescription"> (= (3 &lt;&lt; 5) | 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_NU_MINUS<a id="a14028f7fe73a11dabc6583510cc0a355ac95bcf15367e2c983dc09a5f6dba10f9"></a></td>
<td class="doxyEnumItemDescription"> (= (3 &lt;&lt; 5) |  6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_LT_PLUS<a id="a14028f7fe73a11dabc6583510cc0a355a5f3291fa021498b6f788f19bf4880b39"></a></td>
<td class="doxyEnumItemDescription"> (= (0 &lt;&lt; 5) | 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_LE_PLUS<a id="a14028f7fe73a11dabc6583510cc0a355a46b241a630995742d2839a44af358923"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 5) |  7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_EQ_PLUS<a id="a14028f7fe73a11dabc6583510cc0a355ae9f2ac70e132d4184268f6ae4d0ffcf6"></a></td>
<td class="doxyEnumItemDescription"> (= (2 &lt;&lt; 5) | 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_GE_PLUS<a id="a14028f7fe73a11dabc6583510cc0a355a2b0d1201213c898ccbbc475b86c296aa"></a></td>
<td class="doxyEnumItemDescription"> (= (0 &lt;&lt; 5) |  7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_GT_PLUS<a id="a14028f7fe73a11dabc6583510cc0a355a8a796e02eaa344b39a352e03938f0680"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 5) | 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_NE_PLUS<a id="a14028f7fe73a11dabc6583510cc0a355a7141f86ec6aca10eb4cf8329a20149dc"></a></td>
<td class="doxyEnumItemDescription"> (= (2 &lt;&lt; 5) |  7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_UN_PLUS<a id="a14028f7fe73a11dabc6583510cc0a355a7023259b1bc446d1de0f1565deb639c0"></a></td>
<td class="doxyEnumItemDescription"> (= (3 &lt;&lt; 5) | 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_NU_PLUS<a id="a14028f7fe73a11dabc6583510cc0a355a9867ee23974bb896c049dc26a8b436b2"></a></td>
<td class="doxyEnumItemDescription"> (= (3 &lt;&lt; 5) |  7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_SPE<a id="a14028f7fe73a11dabc6583510cc0a355adb5e703d16f88714345db07c7853a84a"></a></td>
<td class="doxyEnumItemDescription"> (= PRED_GT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_BIT_SET<a id="a14028f7fe73a11dabc6583510cc0a355a3382a0bee0f471ebce5e57f6cbdc91d6"></a></td>
<td class="doxyEnumItemDescription"> (=   1024)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRED_BIT_UNSET<a id="a14028f7fe73a11dabc6583510cc0a355aa3aa5d66d33f7c07c2932141ad4c4b67"></a></td>
<td class="doxyEnumItemDescription"> (= 1025)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcpredicates-h">PPCPredicates.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### createFastISel() {#a2cd7fb94f62f409bc4faf2a20e0904eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastISel * llvm::PPC::createFastISel (<a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; FuncInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * LibInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1504 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2463 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcfastisel-cpp">PPCFastISel.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6622b99b3c00a3938d969957312b1b52">llvm::PPCSubtarget::isPPC64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#afb9a1efd115f87d617c4bd692181df4c">llvm::PPCTargetLowering::createFastISel</a>.</p>

</div>
</div>

### fillValidCPUList() {#afb39db9b40af23175d5d8f3fd556f783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PPC::fillValidCPUList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; Values)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/ppctargetparser-cpp">PPCTargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a> and <a href="#a1dfd53b3d1c77880541a7619dc287f39">PPCCPUInfo</a>.</p>

</div>
</div>

### fillValidTuneCPUList() {#ae6dc8778068867ea9a9597c8ef51a45a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PPC::fillValidTuneCPUList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; Values)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/ppctargetparser-cpp">PPCTargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a> and <a href="#a1dfd53b3d1c77880541a7619dc287f39">PPCCPUInfo</a>.</p>

</div>
</div>

### get\_VSPLTI\_elt() {#a1a14301103c8d97e52ed0ca117ea6b65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::PPC::get_VSPLTI_elt (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned ByteSize, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>get_VSPLTI_elt - If this is a build_vector of constants which can be formed by using a vspltis[bhw] instruction of the specified element size, return the constant being splatted.</p>


<p>The ByteSize field indicates the number of bytes of each element [124] -&gt; [bhw].</p>


<p>Declaration at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2554 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7c6e64fef2ad2ba4052cd8365e97e8d2">llvm::SDNode::getAsZExtVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpudelayedmcexpr-cpp/#a3b9e43a5529fa7d4adb2bad70198c9bd">getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7fc96403de39ca28a30bf2a4a38b113f">llvm::SelectionDAG::getSignedTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af8b512107b41f4ccaf001e31218135c3">llvm::isAllOnesConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a86775f3d85d98a31b2751e1eb348ea">llvm::isNullConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#a6a2164e5aeea9c3e9a02eab3747efd8c">isSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abd6925150e1774fabfaff17efd3f9b9e">llvm::SignExtend32</a>.</p>

</div>
</div>

### getAltVSXFMAOpcode() {#a1545caeeda8de7bd87be034c59b2b9fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::PPC::getAltVSXFMAOpcode (uint16_t Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp">PPCVSXFMAMutate.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#afadf8e95969c146a28e22d91218db770">llvm::PPCInstrInfo::findCommutedOpIndices</a> and <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>.</p>

</div>
</div>

### getCPUInfoByName() {#acb89f3ed94ebc20c424d49c2dfc3e402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CPUInfo * llvm::PPC::getCPUInfoByName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU)</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/ppctargetparser-cpp">PPCTargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a1dfd53b3d1c77880541a7619dc287f39">PPCCPUInfo</a>.</p>


<p>Referenced by <a href="#a40c4695a9cfc9ce20f0c6d8291aca7de">isValidCPU</a>.</p>

</div>
</div>

### getNonRecordFormOpcode() {#a2108c96efd9d9e1b89dd25b89a23ed1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::PPC::getNonRecordFormOpcode (uint16_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>


<p>Reference <a href="#a2108c96efd9d9e1b89dd25b89a23ed1a">getNonRecordFormOpcode</a>.</p>


<p>Referenced by <a href="#a2108c96efd9d9e1b89dd25b89a23ed1a">getNonRecordFormOpcode</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>.</p>

</div>
</div>

### getNormalizedPPCTargetCPU() {#a0f432b141d17384c56f11e55de61aff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::PPC::getNormalizedPPCTargetCPU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPUName="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/ppctargetparser-cpp">PPCTargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a2e8cdc0e591685c9156af3d0d4fdae06">llvm::sys::getHostCPUName</a>, <a href="#a9e3c196667a91fdc81783769feab2e89">normalizeCPUName</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">llvm::Triple::ppc64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">llvm::Triple::ppc64le</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#af5ca20f498adaec1f940475984ad7050">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::doInitialization</a> and <a href="#aebcdb4ac767d9a75c5c9e79450fb75d3">getNormalizedPPCTuneCPU</a>.</p>

</div>
</div>

### getNormalizedPPCTuneCPU() {#aebcdb4ac767d9a75c5c9e79450fb75d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::PPC::getNormalizedPPCTuneCPU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPUName="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/ppctargetparser-cpp">PPCTargetParser.cpp</a>.</p>


<p>References <a href="#a0f432b141d17384c56f11e55de61aff7">getNormalizedPPCTargetCPU</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### getPredicate() {#a40c2294c9ecba721df7f29aaf05157d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::PPC::getPredicate (unsigned Condition, unsigned Hint)</td>
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

<p>Return predicate consisting of specified condition and hint bits.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcpredicates-h">PPCPredicates.h</a>.</p>


<p>Reference <a href="#a8144d2e1978b3e3a226233c0b93b92f4a5df95ff204e7992373cbe6b8ab6b1e79">BR_HINT_MASK</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a584585671a7593c76cc4499d6d75791e">anonymous{PPCMIPeephole.cpp}::getPredicateToDecImm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a47d74d7e9fe3fe56430321c2a238536d">anonymous{PPCMIPeephole.cpp}::getPredicateToIncImm</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>.</p>

</div>
</div>

### getPredicateCondition() {#a2624042e885fc1d665e8fc01a0ab390b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PPC::getPredicateCondition (<a href="#a14028f7fe73a11dabc6583510cc0a355">Predicate</a> Opcode)</td>
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

<p>Return the condition without hint bits.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcpredicates-h">PPCPredicates.h</a>.</p>


<p>Reference <a href="#a8144d2e1978b3e3a226233c0b93b92f4a5df95ff204e7992373cbe6b8ab6b1e79">BR_HINT_MASK</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a584585671a7593c76cc4499d6d75791e">anonymous{PPCMIPeephole.cpp}::getPredicateToDecImm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a47d74d7e9fe3fe56430321c2a238536d">anonymous{PPCMIPeephole.cpp}::getPredicateToIncImm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a360c1f17e2f45595561f8b80c76dbf8e">anonymous{PPCMIPeephole.cpp}::isEqOrNe</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>.</p>

</div>
</div>

### getPredicateHint() {#a5f7348f565ebb68dc08979b2808300c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PPC::getPredicateHint (<a href="#a14028f7fe73a11dabc6583510cc0a355">Predicate</a> Opcode)</td>
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

<p>Return the hint bits of the predicate.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcpredicates-h">PPCPredicates.h</a>.</p>


<p>Reference <a href="#a8144d2e1978b3e3a226233c0b93b92f4a5df95ff204e7992373cbe6b8ab6b1e79">BR_HINT_MASK</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a584585671a7593c76cc4499d6d75791e">anonymous{PPCMIPeephole.cpp}::getPredicateToDecImm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a47d74d7e9fe3fe56430321c2a238536d">anonymous{PPCMIPeephole.cpp}::getPredicateToIncImm</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>.</p>

</div>
</div>

### getRegNumForOperand() {#ad88de25fc56e9402b64e705bc84143b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PPC::getRegNumForOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; Desc, unsigned Reg, unsigned OpNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getRegNumForOperand - some operands use different numbering schemes for the same registers.</p>


<p>For example, a VSX instruction may have any of vs0-vs63 allocated whereas an Altivec instruction could only have vs32-vs63 allocated (numbered as v0-v31). This function returns the actual register number needed for the opcode/operand number combination. The operand number argument will be useful when we need to extend this to instructions that use both Altivec and VSX numbering (for different operands).</p>


<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-h">PPCMCTargetDesc.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp">PPCMCTargetDesc.cpp</a>.</p>


<p>References <a href="#acc7a469d7d5e4183e2b84d15072786cf">isVFRegister</a> and <a href="#a5436d12d95e36064db97636d22f20988">isVRRegister</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#aacaed83c8d18add00c150f20447ae6c8">llvm::PPCMCCodeEmitter::getMachineOpValue</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a5f2fd1af8259132b7f1d061dc1446077">llvm::PPCInstPrinter::printOperand</a>.</p>

</div>
</div>

### getSplatIdxForPPCMnemonics() {#a93d85169d871f169e06ab00673048741}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PPC::getSplatIdxForPPCMnemonics (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned EltSize, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getSplatIdxForPPCMnemonics - Return the splat index as a value that is appropriate for <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> mnemonics (which have a big endian bias - namely elements are counted from the left of the vector register).</p>

<p>Declaration at line 697 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2534 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode/#a449efebfbf16040c8d5c658f4c891f3f">llvm::ShuffleVectorSDNode::getMaskElt</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ac0a534d63ac5c5b87f36acdade953fbe">llvm::SDNode::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a377365b0288a4d06a07e09252d7d583f">llvm::DataLayout::isLittleEndian</a>, <a href="#adf912033ee385662cb4e40bd06206b67">isSplatShuffleMask</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getSwappedPredicate() {#a12c2165ec169065a665bc3a9fcacea89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::PPC::getSwappedPredicate (<a href="#a14028f7fe73a11dabc6583510cc0a355">Predicate</a> Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assume the condition register is set by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI(a,b)</a>, return the predicate if we modify the instructions such that condition register is set by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI(b,a)</a>.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcpredicates-h">PPCPredicates.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>.</p>

</div>
</div>

### InvertPredicate() {#a975319b2f772b89387ffea1b1ba1f049}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::PPC::InvertPredicate (<a href="#a14028f7fe73a11dabc6583510cc0a355">Predicate</a> Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Invert the specified predicate. != -&gt; ==, &lt; -&gt; &gt;=.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcpredicates-h">PPCPredicates.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#a4123a254ab36bc97c087331e6cb38665">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a71d26c25426803c700863bc98bc1d4fd">llvm::PPCInstrInfo::reverseBranchCondition</a> and <a href="/web-llvm/docs/api/structs/anonymous-ppcbranchselector-cpp-/ppcbsel/#a873bcbe8d28d96773cbdf2fd2c9ce07e">anonymous{PPCBranchSelector.cpp}::PPCBSel::runOnMachineFunction</a>.</p>

</div>
</div>

### isSplatShuffleMask() {#adf912033ee385662cb4e40bd06206b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPC::isSplatShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N, unsigned EltSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isSplatShuffleMask - Return true if the specified VECTOR_SHUFFLE operand specifies a splat of a single element that is suitable for input to VSPLTB/VSPLTH/VSPLTW.</p>


<p>isSplatShuffleMask - Return true if the specified VECTOR_SHUFFLE operand specifies a splat of a single element that is suitable for input to one of the splat operations (VSPLTB/VSPLTH/VSPLTW/XXSPLTW/LXVDSX/etc.).</p>


<p>Declaration at line 682 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a93d85169d871f169e06ab00673048741">getSplatIdxForPPCMnemonics</a>.</p>

</div>
</div>

### isValidCPU() {#a40c4695a9cfc9ce20f0c6d8291aca7de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPC::isValidCPU (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/ppctargetparser-cpp">PPCTargetParser.cpp</a>.</p>


<p>References <a href="#acb89f3ed94ebc20c424d49c2dfc3e402">getCPUInfoByName</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>.</p>

</div>
</div>

### isVFRegister() {#acc7a469d7d5e4183e2b84d15072786cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPC::isVFRegister (unsigned Reg)</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-h">PPCMCTargetDesc.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ab8b249a6f01a1f333bc2bfbc6463251c">llvm::PPCInstrInfo::convertToImmediateForm</a>, <a href="#ad88de25fc56e9402b64e705bc84143b2">getRegNumForOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ae1d4c0d71423c8fa3d000f7518a4e8ae">llvm::PPCInstrInfo::isImmInstrEligibleForFolding</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a0bbac805be0153c6ba2c002e08a77388">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::PrintAsmOperand</a>.</p>

</div>
</div>

### isVMRGEOShuffleMask() {#a5abe83e8c9d9553cfc708a024c204807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPC::isVMRGEOShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N, bool CheckEven, unsigned ShuffleKind, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isVMRGEOShuffleMask - Return true if this is a shuffle mask suitable for a VMRGEW or VMRGOW instruction</p>


<p>Determine if the specified shuffle mask is suitable for the vmrgew or vmrgow instructions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] N</td>
<td class="doxyParamItemDescription"><p>The shuffle vector SD <a href="/web-llvm/docs/api/classes/node">Node</a> to analyze</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] CheckEven</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for an even merge (true) or an odd merge (false)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] ShuffleKind</td>
<td class="doxyParamItemDescription"><p>Identify the type of merge:</p>


<ul class="doxyList ">
<li>0 = big-endian merge with two different inputs;</li>
<li>1 = either-endian merge with two identical inputs;</li>
<li>2 = little-endian merge with two different inputs (inputs are swapped for little-endian merges).</li>
</ul></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] DAG</td>
<td class="doxyParamItemDescription"><p>The current <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a></p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true iff this shuffle mask</p></dd>
</dl>


<p>Declaration at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a377365b0288a4d06a07e09252d7d583f">llvm::DataLayout::isLittleEndian</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a941eb33c376cb0192d0d7e52e21c0c11">isVMerge</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isVMRGHShuffleMask() {#a3f48ceee4d4e7b13efb21c415b8fc330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPC::isVMRGHShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N, unsigned UnitSize, unsigned ShuffleKind, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isVMRGHShuffleMask - Return true if this is a shuffle mask suitable for a VRGH* instruction with the specified unit size (1,2 or 4 bytes).</p>


<p>isVMRGHShuffleMask - Return true if this is a shuffle mask suitable for a VMRGH* instruction with the specified unit size (1,2 or 4 bytes).</p>


<p>The ShuffleKind distinguishes between big-endian merges with two different inputs (0), either-endian merges with two identical inputs (1), and little-endian merges with two different inputs (2). For the latter, the input operands are swapped (see PPCInstrAltivec.td).</p>


<p>Declaration at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2069 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a377365b0288a4d06a07e09252d7d583f">llvm::DataLayout::isLittleEndian</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a941eb33c376cb0192d0d7e52e21c0c11">isVMerge</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isVMRGLShuffleMask() {#ab27448838ea5635fa836a68c3aa97b29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPC::isVMRGLShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N, unsigned UnitSize, unsigned ShuffleKind, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isVMRGLShuffleMask - Return true if this is a shuffle mask suitable for a VRGL* instruction with the specified unit size (1,2 or 4 bytes).</p>


<p>isVMRGLShuffleMask - Return true if this is a shuffle mask suitable for a VMRGL* instruction with the specified unit size (1,2 or 4 bytes).</p>


<p>The ShuffleKind distinguishes between big-endian merges with two different inputs (0), either-endian merges with two identical inputs (1), and little-endian merges with two different inputs (2). For the latter, the input operands are swapped (see PPCInstrAltivec.td).</p>


<p>Declaration at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2044 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a377365b0288a4d06a07e09252d7d583f">llvm::DataLayout::isLittleEndian</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a941eb33c376cb0192d0d7e52e21c0c11">isVMerge</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isVPKUDUMShuffleMask() {#a43b885afb337e155a5f9e5257081de8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPC::isVPKUDUMShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N, unsigned ShuffleKind, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isVPKUDUMShuffleMask - Return true if this is the shuffle mask for a VPKUDUM instruction.</p>


<p>isVPKUDUMShuffleMask - Return true if this is the shuffle mask for a VPKUDUM instruction, AND the VPKUDUM instruction exists for the current subtarget.</p>


<p>The ShuffleKind distinguishes between big-endian operations with two different inputs (0), either-endian operations with two identical inputs (1), and little-endian operations with two different inputs (2). For the latter, the input operands are swapped (see PPCInstrAltivec.td).</p>


<p>Declaration at line 631 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 1977 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a150a6b1d332e8d13b77970bd05a235ca">llvm::SelectionDAG::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ab76d3f2c65ed0c127e4d19beb6fc48e3">isConstantOrUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a377365b0288a4d06a07e09252d7d583f">llvm::DataLayout::isLittleEndian</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isVPKUHUMShuffleMask() {#aee91c58b3a130d49788e05c85b12dce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPC::isVPKUHUMShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N, unsigned ShuffleKind, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isVPKUHUMShuffleMask - Return true if this is the shuffle mask for a VPKUHUM instruction.</p>


<p>The ShuffleKind distinguishes between big-endian operations with two different inputs (0), either-endian operations with two identical inputs (1), and little-endian operations with two different inputs (2). For the latter, the input operands are swapped (see PPCInstrAltivec.td).</p>


<p>Declaration at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 1909 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ab76d3f2c65ed0c127e4d19beb6fc48e3">isConstantOrUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a377365b0288a4d06a07e09252d7d583f">llvm::DataLayout::isLittleEndian</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isVPKUWUMShuffleMask() {#ae9f806005e684e4cbd25d76849ee1775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPC::isVPKUWUMShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N, unsigned ShuffleKind, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isVPKUWUMShuffleMask - Return true if this is the shuffle mask for a VPKUWUM instruction.</p>


<p>The ShuffleKind distinguishes between big-endian operations with two different inputs (0), either-endian operations with two identical inputs (1), and little-endian operations with two different inputs (2). For the latter, the input operands are swapped (see PPCInstrAltivec.td).</p>


<p>Declaration at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 1940 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ab76d3f2c65ed0c127e4d19beb6fc48e3">isConstantOrUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a377365b0288a4d06a07e09252d7d583f">llvm::DataLayout::isLittleEndian</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isVRRegister() {#a5436d12d95e36064db97636d22f20988}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPC::isVRRegister (unsigned Reg)</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-h">PPCMCTargetDesc.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#ad88de25fc56e9402b64e705bc84143b2">getRegNumForOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a0bbac805be0153c6ba2c002e08a77388">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::PrintAsmOperand</a>.</p>

</div>
</div>

### isVSLDOIShuffleMask() {#aa45ea0323da7012ed4e0f58aef3619bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::PPC::isVSLDOIShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned ShuffleKind, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isVSLDOIShuffleMask - If this is a vsldoi shuffle mask, return the shift amount, otherwise return -1.</p>


<p>The ShuffleKind distinguishes between big-endian operations with two different inputs (0), either-endian operations with two identical inputs (1), and little-endian operations with two different inputs (2). For the latter, the input operands are swapped (see PPCInstrAltivec.td).</p>


<p>Declaration at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode/#a449efebfbf16040c8d5c658f4c891f3f">llvm::ShuffleVectorSDNode::getMaskElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ab76d3f2c65ed0c127e4d19beb6fc48e3">isConstantOrUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a377365b0288a4d06a07e09252d7d583f">llvm::DataLayout::isLittleEndian</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isXXBRDShuffleMask() {#a2a25cc9341eead72b29eb9646e631244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPC::isXXBRDShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isXXBRDShuffleMask - Return true if this is a shuffle mask suitable for a XXBRD instruction.</p>

<p>Declaration at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2462 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af15ce5608e9ea5ba89ae7deb2e8895c7">isXXBRShuffleMaskHelper</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isXXBRHShuffleMask() {#a8bc23d2b734425aad94289c4dc5df21f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPC::isXXBRHShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isXXBRHShuffleMask - Return true if this is a shuffle mask suitable for a XXBRH instruction.</p>

<p>Declaration at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2454 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af15ce5608e9ea5ba89ae7deb2e8895c7">isXXBRShuffleMaskHelper</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isXXBRQShuffleMask() {#a6e40fdad18c650272628e91ecadce173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPC::isXXBRQShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isXXBRQShuffleMask - Return true if this is a shuffle mask suitable for a XXBRQ instruction.</p>

<p>Declaration at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2466 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af15ce5608e9ea5ba89ae7deb2e8895c7">isXXBRShuffleMaskHelper</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isXXBRWShuffleMask() {#a88c93b88a2a89e226d5312299a4e1790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPC::isXXBRWShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isXXBRWShuffleMask - Return true if this is a shuffle mask suitable for a XXBRW instruction.</p>

<p>Declaration at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2458 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af15ce5608e9ea5ba89ae7deb2e8895c7">isXXBRShuffleMaskHelper</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isXXINSERTWMask() {#acb2d86096213925077b7a8b248745e34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPC::isXXINSERTWMask (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N, unsigned &amp; ShiftElts, unsigned &amp; InsertAtByte, bool &amp; Swap, bool IsLE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isXXINSERTWMask - Return true if this VECTOR_SHUFFLE can be handled by the XXINSERTW instruction introduced in ISA 3.0.</p>


<p>This is essentially any shuffle of v4f32/v4i32 vectors that just inserts one element from one vector into the other. This function will also set a couple of output parameters for how much the source vector needs to be shifted and what byte number needs to be specified for the instruction to put the element in the desired location of the target vector.</p>


<p>Declaration at line 691 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af7dd03e8ef59be43553b3168e2293f33">isNByteElemShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab8aff98d3587ddb15f9e46ed88687f0f">llvm::M0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a58328e0582aabaf012bf9bc6f36c9e04">llvm::M1</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isXXPERMDIShuffleMask() {#a8bbd98a4e85245f40c2ef2ea6f14e7c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPC::isXXPERMDIShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N, unsigned &amp; DM, bool &amp; Swap, bool IsLE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isXXPERMDIShuffleMask - Return true if this is a shuffle mask suitable for a XXPERMDI instruction.</p>


<p>Can node <span class="doxyComputerOutput">N</span> be lowered to an XXPERMDI instruction?</p>


<p>If so, set <span class="doxyComputerOutput">Swap</span> if the inputs to the instruction should be swapped and set <span class="doxyComputerOutput">DM</span> to the value for the immediate. Specifically, set <span class="doxyComputerOutput">Swap</span> to true only if <span class="doxyComputerOutput">N</span> can be lowered to XXPERMDI AND element 0 of the result comes from the first input (LE) or second input (BE). Set <span class="doxyComputerOutput">DM</span> to the calculated result (0-3) only if <span class="doxyComputerOutput">N</span> can be lowered.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true iff the given mask of shuffle node <span class="doxyComputerOutput">N</span> is a XXPERMDI shuffle mask.</p></dd>
</dl>


<p>Declaration at line 671 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2478 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#abbb93ba85eff4d25fd4c3919fddd779c">DM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af7dd03e8ef59be43553b3168e2293f33">isNByteElemShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab8aff98d3587ddb15f9e46ed88687f0f">llvm::M0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a58328e0582aabaf012bf9bc6f36c9e04">llvm::M1</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isXXSLDWIShuffleMask() {#a96447619c3b90a88e75aed44d332114c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPC::isXXSLDWIShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N, unsigned &amp; ShiftElts, bool &amp; Swap, bool IsLE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isXXSLDWIShuffleMask - Return true if this is a shuffle mask suitable for a XXSLDWI instruction.</p>

<p>Declaration at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af7dd03e8ef59be43553b3168e2293f33">isNByteElemShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab8aff98d3587ddb15f9e46ed88687f0f">llvm::M0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a58328e0582aabaf012bf9bc6f36c9e04">llvm::M1</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### normalizeCPUName() {#a9e3c196667a91fdc81783769feab2e89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::PPC::normalizeCPUName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPUName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/ppctargetparser-cpp">PPCTargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a> and <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a2584f7d1fe1c5ab17f8aaba3dafaed66">llvm::XCOFF::getCpuID</a> and <a href="#a0f432b141d17384c56f11e55de61aff7">getNormalizedPPCTargetCPU</a>.</p>

</div>
</div>

### stripRegisterPrefix() {#a2ddf0f8e0c9ad93a6c3a893df96ef599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::PPC::stripRegisterPrefix (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * RegName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>stripRegisterPrefix - This method strips the character prefix from a register name so that only the number is left.</p>


<p>Used by for linux asm.</p>


<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-h">PPCMCTargetDesc.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp">PPCMCTargetDesc.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a0bbac805be0153c6ba2c002e08a77388">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ad00203b7ccef5249a4dda62efbd1be07">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::printOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a5f2fd1af8259132b7f1d061dc1446077">llvm::PPCInstPrinter::printOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### PPCCPUInfo {#a1dfd53b3d1c77880541a7619dc287f39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CPUInfo llvm::PPC::PPCCPUInfo[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
#define <a href="/web-llvm/docs/api/files/lib/lib/targetparser/ppctargetparser-cpp/#a7e6dd2b7c33acb9209e8f33ee4ba1b9d">PPC_CPU</a>(Name, Linux_SUPPORT_METHOD, LinuxID, AIX_SUPPORT_METHOD,       AIXID)                                                         
                                                                               \
}
</div>
</dd>
</dl>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/ppctargetparser-cpp">PPCTargetParser.cpp</a>.</p>


<p>Referenced by <a href="#afb39db9b40af23175d5d8f3fd556f783">fillValidCPUList</a>, <a href="#ae6dc8778068867ea9a9597c8ef51a45a">fillValidTuneCPUList</a> and <a href="#acb89f3ed94ebc20c424d49c2dfc3e402">getCPUInfoByName</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcfixupkinds-h">PPCFixupKinds.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp">PPCMCTargetDesc.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-h">PPCMCTargetDesc.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcpredicates-h">PPCPredicates.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcfastisel-cpp">PPCFastISel.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp">PPCVSXFMAMutate.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/targetparser/ppctargetparser-cpp">PPCTargetParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
