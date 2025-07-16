---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/armcp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `ARMCP` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::ARMCP { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ARMCPKind { <a href="#ad7299e03746a8bdbbff1d3aaf03eaaab">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ARMCPModifier { <a href="#ad792b254bbbd9b9f3e5ea93d54a54d85">...</a> }</td>
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


<div class="doxySectionDef">

## Enumerations

### ARMCPKind {#ad7299e03746a8bdbbff1d3aaf03eaaab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMCP::ARMCPKind </td>
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
<td class="doxyEnumItemName">CPValue<a id="ad7299e03746a8bdbbff1d3aaf03eaaabad4206f41cccb7d5c78d6d642b4b35e1f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPExtSymbol<a id="ad7299e03746a8bdbbff1d3aaf03eaaabab8ec2c2ae69c4040c312cf22f10c6819"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPBlockAddress<a id="ad7299e03746a8bdbbff1d3aaf03eaaabac6721b50294fd164c5861cb82e938e10"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPLSDA<a id="ad7299e03746a8bdbbff1d3aaf03eaaaba7266a79b029f9dc90109a374fe43c64f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPMachineBasicBlock<a id="ad7299e03746a8bdbbff1d3aaf03eaaaba69027420555aea47cb71a920edb9efcc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPPromotedGlobal<a id="ad7299e03746a8bdbbff1d3aaf03eaaaba842db4432c41709c02038126b8d57e27"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>

</div>
</div>

### ARMCPModifier {#ad792b254bbbd9b9f3e5ea93d54a54d85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMCP::ARMCPModifier </td>
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
<td class="doxyEnumItemName">no_modifier<a id="ad792b254bbbd9b9f3e5ea93d54a54d85ae9103902078db9ff4f9a7f5477b04c76"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TLSGD<a id="ad792b254bbbd9b9f3e5ea93d54a54d85a62fc1799424549066b0c6b91919152d7"></a></td>
<td class="doxyEnumItemDescription">None</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GOT_PREL<a id="ad792b254bbbd9b9f3e5ea93d54a54d85a3d74db86256dfd469bc89a14b1d76fab"></a></td>
<td class="doxyEnumItemDescription">Thread Local Storage (General Dynamic Mode)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GOTTPOFF<a id="ad792b254bbbd9b9f3e5ea93d54a54d85acddd18dc22e67498fcf0a79b16155fcf"></a></td>
<td class="doxyEnumItemDescription">Global Offset Table, PC Relative</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TPOFF<a id="ad792b254bbbd9b9f3e5ea93d54a54d85ae08d827e55e1fbc94f0156f25aea52e2"></a></td>
<td class="doxyEnumItemDescription">Global Offset Table, Thread Pointer Offset</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SECREL<a id="ad792b254bbbd9b9f3e5ea93d54a54d85a007149d5920d57032dba20c97c18e7e6"></a></td>
<td class="doxyEnumItemDescription">Thread Pointer Offset</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SBREL<a id="ad792b254bbbd9b9f3e5ea93d54a54d85a44297a25f1c31b29e03e9631855cfef9"></a></td>
<td class="doxyEnumItemDescription">Section Relative (Windows TLS)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
