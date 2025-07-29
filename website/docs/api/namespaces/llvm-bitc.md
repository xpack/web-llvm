---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/bitc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `bitc` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::bitc { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">BlockIDs { <a href="#a802836c61fe369b670441d32741f933d">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">IdentificationCodes { <a href="#a2dde66e038f5a0836d72e760f731a4b4">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identification block contains a string that describes the producer details, and an epoch that defines the auto-upgrade capability. <a href="#a2dde66e038f5a0836d72e760f731a4b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a298addd8bf1eaddaaebcec3640429188">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The epoch that defines the auto-upgrade compatibility for the bitcode. <a href="#a298addd8bf1eaddaaebcec3640429188">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ModuleCodes { <a href="#a9d51b2066d2ce0b9fe4f39f1a80f7c81">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MODULE blocks have a number of optional fields and subblocks. <a href="#a9d51b2066d2ce0b9fe4f39f1a80f7c81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AttributeCodes { <a href="#ac2c80c9b0f575d0333db3cd06da1e51e">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PARAMATTR blocks have code for defining a parameter attribute set. <a href="#ac2c80c9b0f575d0333db3cd06da1e51e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TypeCodes { <a href="#a0bcdd46f107a31184119f65702c0889f">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TYPE blocks have codes for each type primitive they use. <a href="#a0bcdd46f107a31184119f65702c0889f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OperandBundleTagCode { <a href="#abfc8b6b0a946284c6f212eda73571106">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">SyncScopeNameCode { <a href="#ad0a4286c0d9599fd2b3d20f54c883f16">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ValueSymtabCodes { <a href="#a3f554d1f2e074bb07a48d1ae4ecf979c">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ModulePathSymtabCodes { <a href="#af604f4afd5a27f2f0a5c642b26b8a2a4">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">GlobalValueSummarySymtabCodes { <a href="#a2889cf6772f22a2e9c802b6c4cb5001b">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">MetadataCodes { <a href="#a1439ec3246fdaf3a3b4fb4f4e2683c5c">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ConstantsCodes { <a href="#a2f7b2c9070dd196b7bad476149a7ece1">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">CastOpcodes { <a href="#a892950389892c3540c33bb112a4f6078">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a892950389892c3540c33bb112a4f6078">CastOpcodes</a> - These are values used in the bitcode files to encode which cast a CST_CODE_CE_CAST or a XXX refers to. <a href="#a892950389892c3540c33bb112a4f6078">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">UnaryOpcodes { <a href="#a635e5fcb068bb33406c8f4478fec92ac">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a635e5fcb068bb33406c8f4478fec92ac">UnaryOpcodes</a> - These are values used in the bitcode files to encode which unop a CST_CODE_CE_UNOP or a XXX refers to. <a href="#a635e5fcb068bb33406c8f4478fec92ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">BinaryOpcodes { <a href="#afca56ef2a5802dc130b03b7f08833da1">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#afca56ef2a5802dc130b03b7f08833da1">BinaryOpcodes</a> - These are values used in the bitcode files to encode which binop a CST_CODE_CE_BINOP or a XXX refers to. <a href="#afca56ef2a5802dc130b03b7f08833da1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RMWOperations { <a href="#a182436d33a9a893dc643e0c886111a4a">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These are values used in the bitcode files to encode AtomicRMW operations. <a href="#a182436d33a9a893dc643e0c886111a4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OverflowingBinaryOperatorOptionalFlags { <a href="#a5d729bc0f60b0cc1cee0d3d16e8a6954">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a5d729bc0f60b0cc1cee0d3d16e8a6954">OverflowingBinaryOperatorOptionalFlags</a> - Flags for serializing <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator">OverflowingBinaryOperator</a>'s SubclassOptionalData contents. <a href="#a5d729bc0f60b0cc1cee0d3d16e8a6954">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TruncInstOptionalFlags { <a href="#a5e90fa071e4abe5068075a0b4b439a38">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a5e90fa071e4abe5068075a0b4b439a38">TruncInstOptionalFlags</a> - Flags for serializing <a href="#a5e90fa071e4abe5068075a0b4b439a38">TruncInstOptionalFlags</a>'s SubclassOptionalData contents. <a href="#a5e90fa071e4abe5068075a0b4b439a38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FastMathMap { <a href="#abd587fc6c85f5fca5adea50beb5a040a">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FastMath Flags This is a fixed layout derived from the bitcode emitted by LLVM 5.0 intended to decouple the in-memory representation from the serialization. <a href="#abd587fc6c85f5fca5adea50beb5a040a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PossiblyNonNegInstOptionalFlags { <a href="#a28b10e9b2658558a4b547ea0eb025ea4">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flags for serializing <a href="/web-llvm/docs/api/classes/llvm/possiblynonneginst">PossiblyNonNegInst</a>'s SubclassOptionalData contents. <a href="#a28b10e9b2658558a4b547ea0eb025ea4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PossiblyExactOperatorOptionalFlags { <a href="#a49372e72493c55831abbcfcd59a3d49c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a49372e72493c55831abbcfcd59a3d49c">PossiblyExactOperatorOptionalFlags</a> - Flags for serializing <a href="/web-llvm/docs/api/classes/llvm/possiblyexactoperator">PossiblyExactOperator</a>'s SubclassOptionalData contents. <a href="#a49372e72493c55831abbcfcd59a3d49c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PossiblyDisjointInstOptionalFlags { <a href="#abbe7948ad74b8f0387de7e5ac03d6bcc">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#abbe7948ad74b8f0387de7e5ac03d6bcc">PossiblyDisjointInstOptionalFlags</a> - Flags for serializing <a href="/web-llvm/docs/api/classes/llvm/possiblydisjointinst">PossiblyDisjointInst</a>'s SubclassOptionalData contents. <a href="#abbe7948ad74b8f0387de7e5ac03d6bcc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MetadataOperandBundleValueMarker { <a href="#a83900640a877b1deee5e2b561575717a">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark to distinguish metadata from value in an operator bundle. <a href="#a83900640a877b1deee5e2b561575717a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">GetElementPtrOptionalFlags { <a href="#a33a73a3b8d28548e6e3216801bf93207">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a33a73a3b8d28548e6e3216801bf93207">GetElementPtrOptionalFlags</a> - Flags for serializing <a href="/web-llvm/docs/api/classes/llvm/gepoperator">GEPOperator</a>'s SubclassOptionalData contents. <a href="#a33a73a3b8d28548e6e3216801bf93207">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ICmpOptionalFlags { <a href="#ab07949314720a391bf9a4ec0dfb6289a">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#ab07949314720a391bf9a4ec0dfb6289a">ICmpOptionalFlags</a> - Flags for serializing <a href="#ab07949314720a391bf9a4ec0dfb6289a">ICmpOptionalFlags</a>'s SubclassOptionalData contents. <a href="#ab07949314720a391bf9a4ec0dfb6289a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AtomicOrderingCodes { <a href="#aff6d462fc866dfab2fc79bd125310077">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encoded <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> values. <a href="#aff6d462fc866dfab2fc79bd125310077">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CallMarkersFlags { <a href="#a3ecdaacaa7e5214f9f0be1db1b330ff5">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Markers and flags for call instruction. <a href="#a3ecdaacaa7e5214f9f0be1db1b330ff5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FunctionCodes { <a href="#aa0c35b333cf09bfd3e6ff0319f936709">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">UseListCodes { <a href="#a77f340cd374889c5a53b3ab26f47ef95">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">AttributeKindCodes { <a href="#a53da1c4a4f1ae171b53bae755abab1a3">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ComdatSelectionKindCodes { <a href="#a4ebe99a75644fe79a5a1c031c5d0266b">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">StrtabCodes { <a href="#aa5f5b04f18dd0147ec2e2ee1dff56c06">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">SymtabCodes { <a href="#aeb428612b856bd084feccd8f480330de">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">StandardWidths { <a href="#a9bbccfa3e710e59b93cc5a5bf8908cf9">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">FixedAbbrevIDs { <a href="#ab7a76f80792b96a4291e2d1dd1403887">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">StandardBlockIDs { <a href="#a8cd4dd534ba6c31e93a88ca286c4f0e5">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a8cd4dd534ba6c31e93a88ca286c4f0e5">StandardBlockIDs</a> - All bitcode files can optionally include a BLOCKINFO block, which contains metadata about other blocks in the file. <a href="#a8cd4dd534ba6c31e93a88ca286c4f0e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">BlockInfoCodes { <a href="#a6860684558cab9835254eba26b2f7963">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a6860684558cab9835254eba26b2f7963">BlockInfoCodes</a> - The blockinfo block contains metadata about user-defined blocks. <a href="#a6860684558cab9835254eba26b2f7963">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a298addd8bf1eaddaaebcec3640429188}

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

<p>The epoch that defines the auto-upgrade compatibility for the bitcode.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BITCODE_CURRENT_EPOCH<a id="a298addd8bf1eaddaaebcec3640429188a7f66f39da99244fad39ebe115c4053a0"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

</table>
</dd>
</dl>


<p>LLVM guarantees in a major release that a minor release can read bitcode generated by previous minor releases. We translate this by making the reader accepting only bitcode with the same epoch, except for the X.0 release which also accepts N-1.</p>


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### AtomicOrderingCodes {#aff6d462fc866dfab2fc79bd125310077}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::AtomicOrderingCodes </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encoded <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> values.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ORDERING_NOTATOMIC<a id="aff6d462fc866dfab2fc79bd125310077a83f6d5a33251a1af65bfd012765dbec7"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ORDERING_UNORDERED<a id="aff6d462fc866dfab2fc79bd125310077a8768765e8f788907885fbd23ae6a8edb"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ORDERING_MONOTONIC<a id="aff6d462fc866dfab2fc79bd125310077aec3d86ca51de0866abd0fc0d1ec71b9d"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ORDERING_ACQUIRE<a id="aff6d462fc866dfab2fc79bd125310077a0b468dec37bac00c148e2e9a20711bb9"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ORDERING_RELEASE<a id="aff6d462fc866dfab2fc79bd125310077a47017037bf5808b06c2cd2e184c55de2"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ORDERING_ACQREL<a id="aff6d462fc866dfab2fc79bd125310077a133fea251780f2b0a86a520addd9c184"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ORDERING_SEQCST<a id="aff6d462fc866dfab2fc79bd125310077ab5a2748be1fde542bf8baeb43f6f44cb"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### AttributeCodes {#ac2c80c9b0f575d0333db3cd06da1e51e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::AttributeCodes </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PARAMATTR blocks have code for defining a parameter attribute set.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PARAMATTR_CODE_ENTRY_OLD<a id="ac2c80c9b0f575d0333db3cd06da1e51ea24913f2946317d4d3ecf12f900dbd16e"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PARAMATTR_CODE_ENTRY<a id="ac2c80c9b0f575d0333db3cd06da1e51ea7c886568e5c7b7c735e6f3d5ebfb2973"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PARAMATTR_GRP_CODE_ENTRY<a id="ac2c80c9b0f575d0333db3cd06da1e51ea65f8f2ba217d264a39a43fb0b5560a10"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### AttributeKindCodes {#a53da1c4a4f1ae171b53bae755abab1a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::AttributeKindCodes </td>
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
<td class="doxyEnumItemName">ATTR_KIND_ALIGNMENT<a id="a53da1c4a4f1ae171b53bae755abab1a3abadb9d66c19008e4ddb353c55d2c28e2"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_ALWAYS_INLINE<a id="a53da1c4a4f1ae171b53bae755abab1a3ac21e10518d20fe0353e65cca06bd5256"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_BY_VAL<a id="a53da1c4a4f1ae171b53bae755abab1a3aa3b7dab5234bc2c00ecd7e64878b715d"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_INLINE_HINT<a id="a53da1c4a4f1ae171b53bae755abab1a3a554f2b13f875de1d1b91fae8f22f1219"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_IN_REG<a id="a53da1c4a4f1ae171b53bae755abab1a3ab535e133afc06aad0ae2a4cd2a3ba5b2"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_MIN_SIZE<a id="a53da1c4a4f1ae171b53bae755abab1a3a1a3eec7201b20fd0a7be025a2c9c4325"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NAKED<a id="a53da1c4a4f1ae171b53bae755abab1a3a458ace7cc504125aa2a1d7160c41e7d4"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NEST<a id="a53da1c4a4f1ae171b53bae755abab1a3a4e8e90d675a52048aa4b579214515238"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NO_ALIAS<a id="a53da1c4a4f1ae171b53bae755abab1a3ad330adbe19c74c6c37c35f4f5e796bc6"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NO_BUILTIN<a id="a53da1c4a4f1ae171b53bae755abab1a3a2f56428e2de63871e29676305d87de09"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NO_CAPTURE<a id="a53da1c4a4f1ae171b53bae755abab1a3a2107a048bcc160f3ff3266424324ea31"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NO_DUPLICATE<a id="a53da1c4a4f1ae171b53bae755abab1a3a920b3cacbba0ced6115f2566900e127d"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NO_IMPLICIT_FLOAT<a id="a53da1c4a4f1ae171b53bae755abab1a3a2efc67c46821e4185ae5480eb9dd26cd"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NO_INLINE<a id="a53da1c4a4f1ae171b53bae755abab1a3adc9ed5109d2f0dca6fdd2b4bd83c41f7"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NON_LAZY_BIND<a id="a53da1c4a4f1ae171b53bae755abab1a3a93538315516b14f95e92df987821a58a"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NO_RED_ZONE<a id="a53da1c4a4f1ae171b53bae755abab1a3aaa665c4d4c4bc24191c6d60ae71fe62e"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NO_RETURN<a id="a53da1c4a4f1ae171b53bae755abab1a3a59af608118cf63c82feeb91c9d88b6e2"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NO_UNWIND<a id="a53da1c4a4f1ae171b53bae755abab1a3a05dd5faacf5c7eb49825debc35136169"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_OPTIMIZE_FOR_SIZE<a id="a53da1c4a4f1ae171b53bae755abab1a3a10ccf7458de7661ed59552aa375f91e8"></a></td>
<td class="doxyEnumItemDescription"> (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_READ_NONE<a id="a53da1c4a4f1ae171b53bae755abab1a3a974c5448b13d159116dfa73138e2058c"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_READ_ONLY<a id="a53da1c4a4f1ae171b53bae755abab1a3abac7a26689aa32f57183deb05ff4e8b7"></a></td>
<td class="doxyEnumItemDescription"> (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_RETURNED<a id="a53da1c4a4f1ae171b53bae755abab1a3a4d40d2b7ab76139b227d085040438acf"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_RETURNS_TWICE<a id="a53da1c4a4f1ae171b53bae755abab1a3a6321311fb493fcbb0fbf655bda813424"></a></td>
<td class="doxyEnumItemDescription"> (= 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_S_EXT<a id="a53da1c4a4f1ae171b53bae755abab1a3aa08af93fce49bf40ea23e92f7fd99b43"></a></td>
<td class="doxyEnumItemDescription"> (= 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_STACK_ALIGNMENT<a id="a53da1c4a4f1ae171b53bae755abab1a3a4d708f6ef22af69a714124a9e6d27a29"></a></td>
<td class="doxyEnumItemDescription"> (= 25)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_STACK_PROTECT<a id="a53da1c4a4f1ae171b53bae755abab1a3a02985b5b9b00d8fcf0c3456548704f89"></a></td>
<td class="doxyEnumItemDescription"> (= 26)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_STACK_PROTECT_REQ<a id="a53da1c4a4f1ae171b53bae755abab1a3a52eaba8bee5d2693ac99f44de939c95f"></a></td>
<td class="doxyEnumItemDescription"> (= 27)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_STACK_PROTECT_STRONG<a id="a53da1c4a4f1ae171b53bae755abab1a3a05f5e41019f7c20785c7a657d9f8158c"></a></td>
<td class="doxyEnumItemDescription"> (= 28)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_STRUCT_RET<a id="a53da1c4a4f1ae171b53bae755abab1a3a1a17ef11f6af6c1c96c256a885d2bba7"></a></td>
<td class="doxyEnumItemDescription"> (= 29)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_SANITIZE_ADDRESS<a id="a53da1c4a4f1ae171b53bae755abab1a3a2e2b64c82183308aa47d372943092e39"></a></td>
<td class="doxyEnumItemDescription"> (= 30)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_SANITIZE_THREAD<a id="a53da1c4a4f1ae171b53bae755abab1a3af4da5ef4d5aada8b57baf7b42330d168"></a></td>
<td class="doxyEnumItemDescription"> (= 31)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_SANITIZE_MEMORY<a id="a53da1c4a4f1ae171b53bae755abab1a3a063fce6939dfcc85c3d919cbb90cdbe1"></a></td>
<td class="doxyEnumItemDescription"> (= 32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_UW_TABLE<a id="a53da1c4a4f1ae171b53bae755abab1a3aa1ee732e66faee6f738611e8af19ba32"></a></td>
<td class="doxyEnumItemDescription"> (= 33)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_Z_EXT<a id="a53da1c4a4f1ae171b53bae755abab1a3a656d32cce3f0da0c87a066dce0a9ae0f"></a></td>
<td class="doxyEnumItemDescription"> (= 34)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_BUILTIN<a id="a53da1c4a4f1ae171b53bae755abab1a3a86f312d48859fc97a288d8718d4e4e81"></a></td>
<td class="doxyEnumItemDescription"> (= 35)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_COLD<a id="a53da1c4a4f1ae171b53bae755abab1a3a6b5c1960ea5bf27bae724fbe40458671"></a></td>
<td class="doxyEnumItemDescription"> (= 36)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_OPTIMIZE_NONE<a id="a53da1c4a4f1ae171b53bae755abab1a3aa695e2248b1cb68eb1afcdc2c5d62491"></a></td>
<td class="doxyEnumItemDescription"> (= 37)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_IN_ALLOCA<a id="a53da1c4a4f1ae171b53bae755abab1a3ab90bb54c98fe726dfded55b337f3cf71"></a></td>
<td class="doxyEnumItemDescription"> (= 38)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NON_NULL<a id="a53da1c4a4f1ae171b53bae755abab1a3a57d48f7ace267b453bc4d3ad164e58fb"></a></td>
<td class="doxyEnumItemDescription"> (= 39)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_JUMP_TABLE<a id="a53da1c4a4f1ae171b53bae755abab1a3ad87194f39c5d544c6e47d387fad0087d"></a></td>
<td class="doxyEnumItemDescription"> (= 40)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_DEREFERENCEABLE<a id="a53da1c4a4f1ae171b53bae755abab1a3a94f778cea4955c8d871aa0ebc22b4852"></a></td>
<td class="doxyEnumItemDescription"> (= 41)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_DEREFERENCEABLE_OR_NULL<a id="a53da1c4a4f1ae171b53bae755abab1a3aaec534c7d966b2ce46814f56cee8d88a"></a></td>
<td class="doxyEnumItemDescription"> (= 42)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_CONVERGENT<a id="a53da1c4a4f1ae171b53bae755abab1a3a3b0c92f3637b859b97dd9575a33ffec9"></a></td>
<td class="doxyEnumItemDescription"> (= 43)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_SAFESTACK<a id="a53da1c4a4f1ae171b53bae755abab1a3a100c3c2639fc32a8d64953a2c29741a5"></a></td>
<td class="doxyEnumItemDescription"> (= 44)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_ARGMEMONLY<a id="a53da1c4a4f1ae171b53bae755abab1a3a76a225ab7641d99b9cc6b37fadc2f2cf"></a></td>
<td class="doxyEnumItemDescription"> (= 45)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_SWIFT_SELF<a id="a53da1c4a4f1ae171b53bae755abab1a3a4dfd1ab23712750b0c4d712ff9aefdb3"></a></td>
<td class="doxyEnumItemDescription"> (= 46)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_SWIFT_ERROR<a id="a53da1c4a4f1ae171b53bae755abab1a3a12f9c8d3abe9eadfc656fd9a2115c7ec"></a></td>
<td class="doxyEnumItemDescription"> (= 47)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NO_RECURSE<a id="a53da1c4a4f1ae171b53bae755abab1a3a34c5bd95f79732a201f966cfc6421ea5"></a></td>
<td class="doxyEnumItemDescription"> (= 48)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_INACCESSIBLEMEM_ONLY<a id="a53da1c4a4f1ae171b53bae755abab1a3a13ec7512d1a12c9a7593d91ce75e3be1"></a></td>
<td class="doxyEnumItemDescription"> (= 49)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_INACCESSIBLEMEM_OR_ARGMEMONLY<a id="a53da1c4a4f1ae171b53bae755abab1a3a4f31d5615da59be5df769d12d08a3565"></a></td>
<td class="doxyEnumItemDescription"> (= 50)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_ALLOC_SIZE<a id="a53da1c4a4f1ae171b53bae755abab1a3a512cc01a3fa4c51809cb905de3d30b4c"></a></td>
<td class="doxyEnumItemDescription"> (= 51)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_WRITEONLY<a id="a53da1c4a4f1ae171b53bae755abab1a3aa9bcf6b32c733bdfa2e2473fd1f18963"></a></td>
<td class="doxyEnumItemDescription"> (= 52)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_SPECULATABLE<a id="a53da1c4a4f1ae171b53bae755abab1a3adb2076c2e8152af22f43f8fe939b191a"></a></td>
<td class="doxyEnumItemDescription"> (= 53)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_STRICT_FP<a id="a53da1c4a4f1ae171b53bae755abab1a3a9128f6d8bce4c0521966580b79757e13"></a></td>
<td class="doxyEnumItemDescription"> (= 54)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_SANITIZE_HWADDRESS<a id="a53da1c4a4f1ae171b53bae755abab1a3a598116e25b929c808e6bd52e35a2be17"></a></td>
<td class="doxyEnumItemDescription"> (= 55)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NOCF_CHECK<a id="a53da1c4a4f1ae171b53bae755abab1a3aac037ec3f3273e872307022405e95ace"></a></td>
<td class="doxyEnumItemDescription"> (= 56)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_OPT_FOR_FUZZING<a id="a53da1c4a4f1ae171b53bae755abab1a3a6a01a6b667890a3a7fe291b2303729c0"></a></td>
<td class="doxyEnumItemDescription"> (= 57)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_SHADOWCALLSTACK<a id="a53da1c4a4f1ae171b53bae755abab1a3a6943bf6094f5e2e519172af2be91c182"></a></td>
<td class="doxyEnumItemDescription"> (= 58)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_SPECULATIVE_LOAD_HARDENING<a id="a53da1c4a4f1ae171b53bae755abab1a3ac1811dc4c110f8e6a942d6e73da1bcc8"></a></td>
<td class="doxyEnumItemDescription"> (= 59)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_IMMARG<a id="a53da1c4a4f1ae171b53bae755abab1a3a8333f888d39f2fc0d6f18a96a16d902b"></a></td>
<td class="doxyEnumItemDescription"> (= 60)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_WILLRETURN<a id="a53da1c4a4f1ae171b53bae755abab1a3ac847497e79df6980c96592730db17323"></a></td>
<td class="doxyEnumItemDescription"> (= 61)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NOFREE<a id="a53da1c4a4f1ae171b53bae755abab1a3a2b4a84f204f2f012d3df4cb8bc60e860"></a></td>
<td class="doxyEnumItemDescription"> (= 62)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NOSYNC<a id="a53da1c4a4f1ae171b53bae755abab1a3ad0259dc9cd682a7b9bc525e92ab94902"></a></td>
<td class="doxyEnumItemDescription"> (= 63)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_SANITIZE_MEMTAG<a id="a53da1c4a4f1ae171b53bae755abab1a3aeda30207dd431bb2531c9c55972a207d"></a></td>
<td class="doxyEnumItemDescription"> (= 64)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_PREALLOCATED<a id="a53da1c4a4f1ae171b53bae755abab1a3afbba6578048f8900e6a59315caba4eb5"></a></td>
<td class="doxyEnumItemDescription"> (= 65)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NO_MERGE<a id="a53da1c4a4f1ae171b53bae755abab1a3a886acf88e3917643d0bfff579d3d90af"></a></td>
<td class="doxyEnumItemDescription"> (= 66)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NULL_POINTER_IS_VALID<a id="a53da1c4a4f1ae171b53bae755abab1a3a5877603f20796c0153d7ad23b03b2079"></a></td>
<td class="doxyEnumItemDescription"> (= 67)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NOUNDEF<a id="a53da1c4a4f1ae171b53bae755abab1a3a7e86d7e0b4f5f52a3f2205f8b2b07d26"></a></td>
<td class="doxyEnumItemDescription"> (= 68)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_BYREF<a id="a53da1c4a4f1ae171b53bae755abab1a3a13b920c66e426fedc360a03dc19ae6b0"></a></td>
<td class="doxyEnumItemDescription"> (= 69)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_MUSTPROGRESS<a id="a53da1c4a4f1ae171b53bae755abab1a3a5ea40b0bf65fb6dfc7c19695921dfa43"></a></td>
<td class="doxyEnumItemDescription"> (= 70)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NO_CALLBACK<a id="a53da1c4a4f1ae171b53bae755abab1a3a1bbfc846a3dd6eeac891c2696da093e6"></a></td>
<td class="doxyEnumItemDescription"> (= 71)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_HOT<a id="a53da1c4a4f1ae171b53bae755abab1a3ae09a861f046502814ccc8a1805966955"></a></td>
<td class="doxyEnumItemDescription"> (= 72)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NO_PROFILE<a id="a53da1c4a4f1ae171b53bae755abab1a3aaebb0cdb7703aafd9d1a18dad8824b53"></a></td>
<td class="doxyEnumItemDescription"> (= 73)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_VSCALE_RANGE<a id="a53da1c4a4f1ae171b53bae755abab1a3ad34cad71bda2dfd0c79c83a4cfe64523"></a></td>
<td class="doxyEnumItemDescription"> (= 74)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_SWIFT_ASYNC<a id="a53da1c4a4f1ae171b53bae755abab1a3afebba069726cfcfaedb609eb2afc411e"></a></td>
<td class="doxyEnumItemDescription"> (= 75)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NO_SANITIZE_COVERAGE<a id="a53da1c4a4f1ae171b53bae755abab1a3ad8352b9fa6aa94b6457fe509e811b19f"></a></td>
<td class="doxyEnumItemDescription"> (= 76)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_ELEMENTTYPE<a id="a53da1c4a4f1ae171b53bae755abab1a3a84639710ca4a56d99d1ada67fa19c40f"></a></td>
<td class="doxyEnumItemDescription"> (= 77)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_DISABLE_SANITIZER_INSTRUMENTATION<a id="a53da1c4a4f1ae171b53bae755abab1a3a7d923675347db880195935dd2859430b"></a></td>
<td class="doxyEnumItemDescription"> (= 78)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NO_SANITIZE_BOUNDS<a id="a53da1c4a4f1ae171b53bae755abab1a3ae73a1348bfbb82425a20b4f7cc6471f3"></a></td>
<td class="doxyEnumItemDescription"> (= 79)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_ALLOC_ALIGN<a id="a53da1c4a4f1ae171b53bae755abab1a3a929955dc4b9681ed9cec5bc1ff962391"></a></td>
<td class="doxyEnumItemDescription"> (= 80)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_ALLOCATED_POINTER<a id="a53da1c4a4f1ae171b53bae755abab1a3a7a1023f40b7fdf89b8359106f07ce88d"></a></td>
<td class="doxyEnumItemDescription"> (= 81)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_ALLOC_KIND<a id="a53da1c4a4f1ae171b53bae755abab1a3a85f1c987a4cab98ae2d3cf15c46a5533"></a></td>
<td class="doxyEnumItemDescription"> (= 82)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_PRESPLIT_COROUTINE<a id="a53da1c4a4f1ae171b53bae755abab1a3aced00bf2cc41b0b4b1cd9bed3bf70fc6"></a></td>
<td class="doxyEnumItemDescription"> (= 83)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_FNRETTHUNK_EXTERN<a id="a53da1c4a4f1ae171b53bae755abab1a3a289e17c3ab627b09ba25a1fdd4fd4dea"></a></td>
<td class="doxyEnumItemDescription"> (= 84)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_SKIP_PROFILE<a id="a53da1c4a4f1ae171b53bae755abab1a3a7ef1dd025b0567b904f0da8c0624da9b"></a></td>
<td class="doxyEnumItemDescription"> (= 85)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_MEMORY<a id="a53da1c4a4f1ae171b53bae755abab1a3a32b54e18317d6adae4c3570ecb4737d3"></a></td>
<td class="doxyEnumItemDescription"> (= 86)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NOFPCLASS<a id="a53da1c4a4f1ae171b53bae755abab1a3ac4d3e92d2ef62cf51f31676bd04e5105"></a></td>
<td class="doxyEnumItemDescription"> (= 87)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_OPTIMIZE_FOR_DEBUGGING<a id="a53da1c4a4f1ae171b53bae755abab1a3afa58e5a377bd47affa71c9573ff393c4"></a></td>
<td class="doxyEnumItemDescription"> (= 88)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_WRITABLE<a id="a53da1c4a4f1ae171b53bae755abab1a3a6c6b4c48a4db5cb8b4dcd7400dc2a767"></a></td>
<td class="doxyEnumItemDescription"> (= 89)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_CORO_ONLY_DESTROY_WHEN_COMPLETE<a id="a53da1c4a4f1ae171b53bae755abab1a3af37c451700ab8aaad90854ec4b50a980"></a></td>
<td class="doxyEnumItemDescription"> (= 90)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_DEAD_ON_UNWIND<a id="a53da1c4a4f1ae171b53bae755abab1a3a3794a1f268da39dfa1c0815d936ae616"></a></td>
<td class="doxyEnumItemDescription"> (= 91)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_RANGE<a id="a53da1c4a4f1ae171b53bae755abab1a3aca4c5725563d1c044a84ec3d4b818a5f"></a></td>
<td class="doxyEnumItemDescription"> (= 92)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_SANITIZE_NUMERICAL_STABILITY<a id="a53da1c4a4f1ae171b53bae755abab1a3a6d0eb2693e8bacfa8c3265554bb4de39"></a></td>
<td class="doxyEnumItemDescription"> (= 93)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_INITIALIZES<a id="a53da1c4a4f1ae171b53bae755abab1a3a74e8f00480492bc7882bfd1bea39e29a"></a></td>
<td class="doxyEnumItemDescription"> (= 94)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_HYBRID_PATCHABLE<a id="a53da1c4a4f1ae171b53bae755abab1a3aa9f6b695559a1f0368d1942031e4743b"></a></td>
<td class="doxyEnumItemDescription"> (= 95)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_SANITIZE_REALTIME<a id="a53da1c4a4f1ae171b53bae755abab1a3ab2f626bb70e4d6ccec7b48c473d06a29"></a></td>
<td class="doxyEnumItemDescription"> (= 96)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_SANITIZE_REALTIME_BLOCKING<a id="a53da1c4a4f1ae171b53bae755abab1a3ae376cf8d2b2da2e690cea4abf5d52862"></a></td>
<td class="doxyEnumItemDescription"> (= 97)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_CORO_ELIDE_SAFE<a id="a53da1c4a4f1ae171b53bae755abab1a3a85c70a265e696fc216e55f0e6a0d3935"></a></td>
<td class="doxyEnumItemDescription"> (= 98)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NO_EXT<a id="a53da1c4a4f1ae171b53bae755abab1a3aa6f71013a7a1d6d14768c4ab9ec3c228"></a></td>
<td class="doxyEnumItemDescription"> (= 99)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_NO_DIVERGENCE_SOURCE<a id="a53da1c4a4f1ae171b53bae755abab1a3a2d61eb1531fe7e8040651fc3e40f38c2"></a></td>
<td class="doxyEnumItemDescription"> (= 100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_SANITIZE_TYPE<a id="a53da1c4a4f1ae171b53bae755abab1a3acaeef48f6534f29c49dd9068ae704f89"></a></td>
<td class="doxyEnumItemDescription"> (= 101)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_KIND_CAPTURES<a id="a53da1c4a4f1ae171b53bae755abab1a3af3a622a12140d6cfa18c6994cb9b93c5"></a></td>
<td class="doxyEnumItemDescription"> (= 102)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### BinaryOpcodes {#afca56ef2a5802dc130b03b7f08833da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::BinaryOpcodes </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#afca56ef2a5802dc130b03b7f08833da1">BinaryOpcodes</a> - These are values used in the bitcode files to encode which binop a CST_CODE_CE_BINOP or a XXX refers to.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BINOP_ADD<a id="afca56ef2a5802dc130b03b7f08833da1a68d9d8c75aa2cbd98cc3cd6088cd88c3"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BINOP_SUB<a id="afca56ef2a5802dc130b03b7f08833da1af044d7456abdac4e41aef374cbb43e12"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BINOP_MUL<a id="afca56ef2a5802dc130b03b7f08833da1aa4396fd4122548b531cc7177512b139e"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BINOP_UDIV<a id="afca56ef2a5802dc130b03b7f08833da1a6fc7d38cbdd784e6f2573ba865138210"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BINOP_SDIV<a id="afca56ef2a5802dc130b03b7f08833da1aa4e1b66237a655ae124026c28b26d481"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BINOP_UREM<a id="afca56ef2a5802dc130b03b7f08833da1a26868218c32dc434e202a4d694ad3f45"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BINOP_SREM<a id="afca56ef2a5802dc130b03b7f08833da1ac799944d2a5b7b91210b803504e77319"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BINOP_SHL<a id="afca56ef2a5802dc130b03b7f08833da1a01aa051969198a4085e944234de2446e"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BINOP_LSHR<a id="afca56ef2a5802dc130b03b7f08833da1a9ec979797d756b39ae37a5f2e25a0d38"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BINOP_ASHR<a id="afca56ef2a5802dc130b03b7f08833da1a9a30fed92fd54e316fd32e7e745aeb14"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BINOP_AND<a id="afca56ef2a5802dc130b03b7f08833da1acecfe220fcf28ba017208977312a468c"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BINOP_OR<a id="afca56ef2a5802dc130b03b7f08833da1a9b125c378940a11c60ad335b0e60b1a2"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BINOP_XOR<a id="afca56ef2a5802dc130b03b7f08833da1ac6a71c3796edcf421edd6fadb028be68"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

</table>
</dd>
</dl>


<p>The values of these enums have no fixed relation to the LLVM IR enum values. Changing these will break compatibility with old files.</p>


<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### BlockIDs {#a802836c61fe369b670441d32741f933d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::BlockIDs </td>
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
<td class="doxyEnumItemName">MODULE_BLOCK_ID<a id="a802836c61fe369b670441d32741f933da31e5f441b78348934094a9dde0a326e2"></a></td>
<td class="doxyEnumItemDescription"> (= FIRST_APPLICATION_BLOCKID)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PARAMATTR_BLOCK_ID<a id="a802836c61fe369b670441d32741f933da1bd41d0ca31f107397a953d9d266264b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PARAMATTR_GROUP_BLOCK_ID<a id="a802836c61fe369b670441d32741f933da4a716786c51cc39851c8bf53af9c538a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANTS_BLOCK_ID<a id="a802836c61fe369b670441d32741f933da48c634bc116b5df0bf52d60f96862947"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_BLOCK_ID<a id="a802836c61fe369b670441d32741f933da7a137de095b15e7ec696da7678459677"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IDENTIFICATION_BLOCK_ID<a id="a802836c61fe369b670441d32741f933da574b2844e8b4baab9239f12c1b6b0d04"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VALUE_SYMTAB_BLOCK_ID<a id="a802836c61fe369b670441d32741f933dad03d0513adaa3462afbc7be6241b7db2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_BLOCK_ID<a id="a802836c61fe369b670441d32741f933da6d85c95035de79006ae3a5dac19ee4a2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_ATTACHMENT_ID<a id="a802836c61fe369b670441d32741f933da6553316df9fbe50417fd8e4630b90ef4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_BLOCK_ID_NEW<a id="a802836c61fe369b670441d32741f933da1e03bcd25d6c621851c52d1775f15c2a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">USELIST_BLOCK_ID<a id="a802836c61fe369b670441d32741f933daf34210783792fafaf34e0991cda79352"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_STRTAB_BLOCK_ID<a id="a802836c61fe369b670441d32741f933daca3ed786c04791d9c4961711ebf6c294"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLOBALVAL_SUMMARY_BLOCK_ID<a id="a802836c61fe369b670441d32741f933da642102503aff012fc2975f165138b454"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_BUNDLE_TAGS_BLOCK_ID<a id="a802836c61fe369b670441d32741f933daea440f1709f0443e3f8ca718ed2084d9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_KIND_BLOCK_ID<a id="a802836c61fe369b670441d32741f933da5747b302b28e31fd8879df26646da087"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRTAB_BLOCK_ID<a id="a802836c61fe369b670441d32741f933da33a2dbf49ae958238e75eb871a9f0b2e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FULL_LTO_GLOBALVAL_SUMMARY_BLOCK_ID<a id="a802836c61fe369b670441d32741f933daca3afe4e93910906ab7d0c2e3bd2b90e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SYMTAB_BLOCK_ID<a id="a802836c61fe369b670441d32741f933da466acfef0eae5774264a2115c0c1496a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SYNC_SCOPE_NAMES_BLOCK_ID<a id="a802836c61fe369b670441d32741f933da09f9fc047b2465f8d572c23254a64381"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### BlockInfoCodes {#a6860684558cab9835254eba26b2f7963}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::BlockInfoCodes </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a6860684558cab9835254eba26b2f7963">BlockInfoCodes</a> - The blockinfo block contains metadata about user-defined blocks.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BLOCKINFO_CODE_SETBID<a id="a6860684558cab9835254eba26b2f7963acf72b4b5b2c1c5b1310721a6715ab010"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BLOCKINFO_CODE_BLOCKNAME<a id="a6860684558cab9835254eba26b2f7963a3ab749cc5d99cccffd681c29da02fa74"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BLOCKINFO_CODE_SETRECORDNAME<a id="a6860684558cab9835254eba26b2f7963aad1225e67df2c8e94135a067eb3f212e"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitcodeenums-h">BitCodeEnums.h</a>.</p>

</div>
</div>

### CallMarkersFlags {#a3ecdaacaa7e5214f9f0be1db1b330ff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::CallMarkersFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Markers and flags for call instruction.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_TAIL<a id="a3ecdaacaa7e5214f9f0be1db1b330ff5aa5030f997ec7c4661a66cccc1a1a017f"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_CCONV<a id="a3ecdaacaa7e5214f9f0be1db1b330ff5ac522bc68953b6aab8e5975c01fcfc7af"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_MUSTTAIL<a id="a3ecdaacaa7e5214f9f0be1db1b330ff5a6a6a2dd4cd1a868607840aad3f8dda3b"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_EXPLICIT_TYPE<a id="a3ecdaacaa7e5214f9f0be1db1b330ff5a44513f6685b35aade32c4c5c141ceb78"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_NOTAIL<a id="a3ecdaacaa7e5214f9f0be1db1b330ff5af01307b2649f733abd578d07e319e6a7"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_FMF<a id="a3ecdaacaa7e5214f9f0be1db1b330ff5acd0d3e84a607c985c3933ccf7e97c634"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 574 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### CastOpcodes {#a892950389892c3540c33bb112a4f6078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::CastOpcodes </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a892950389892c3540c33bb112a4f6078">CastOpcodes</a> - These are values used in the bitcode files to encode which cast a CST_CODE_CE_CAST or a XXX refers to.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CAST_TRUNC<a id="a892950389892c3540c33bb112a4f6078aa1a60e212be26cd7a84d0218675285c2"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CAST_ZEXT<a id="a892950389892c3540c33bb112a4f6078ab1d860827fec09b9116e81923e3f20aa"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CAST_SEXT<a id="a892950389892c3540c33bb112a4f6078aacc1fb2c439b83d10dd250ff5a2b93f3"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CAST_FPTOUI<a id="a892950389892c3540c33bb112a4f6078a84dd2da5c7f3314061ca10f524e7dcb0"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CAST_FPTOSI<a id="a892950389892c3540c33bb112a4f6078a2d6fc7cca02f499939b68491dff00f58"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CAST_UITOFP<a id="a892950389892c3540c33bb112a4f6078a0aa29b41007b5fbfce2da261d9816978"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CAST_SITOFP<a id="a892950389892c3540c33bb112a4f6078a9eaca2882fcf0ec475854e8e5c2279e8"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CAST_FPTRUNC<a id="a892950389892c3540c33bb112a4f6078ac7c030dde4055cefd0471ef8fb27038d"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CAST_FPEXT<a id="a892950389892c3540c33bb112a4f6078ab585d6900abdafe339c6e9c910035859"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CAST_PTRTOINT<a id="a892950389892c3540c33bb112a4f6078ad441909766521e384654c38484c6f169"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CAST_INTTOPTR<a id="a892950389892c3540c33bb112a4f6078aaa14daa58dc521dbc0ef0a696aa9e6dd"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CAST_BITCAST<a id="a892950389892c3540c33bb112a4f6078a07f83ec620595d592fb799d051ac6e75"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CAST_ADDRSPACECAST<a id="a892950389892c3540c33bb112a4f6078ab8be0ead019884e9180369dcf5ca0470"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

</table>
</dd>
</dl>


<p>The values of these enums have no fixed relation to the LLVM IR enum values. Changing these will break compatibility with old files.</p>


<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### ComdatSelectionKindCodes {#a4ebe99a75644fe79a5a1c031c5d0266b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::ComdatSelectionKindCodes </td>
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
<td class="doxyEnumItemName">COMDAT_SELECTION_KIND_ANY<a id="a4ebe99a75644fe79a5a1c031c5d0266ba228d51974aa5c21ba52010a40302a0fc"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COMDAT_SELECTION_KIND_EXACT_MATCH<a id="a4ebe99a75644fe79a5a1c031c5d0266ba8cfeeb1451c75f879a6876b6beaf6c6d"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COMDAT_SELECTION_KIND_LARGEST<a id="a4ebe99a75644fe79a5a1c031c5d0266ba10c8fffe9e95a186479d54d05cb03507"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COMDAT_SELECTION_KIND_NO_DUPLICATES<a id="a4ebe99a75644fe79a5a1c031c5d0266baa4e0a5bb065b0f0330ec4a9b80b47ca6"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COMDAT_SELECTION_KIND_SAME_SIZE<a id="a4ebe99a75644fe79a5a1c031c5d0266ba78a05db06e72b074e5ff734665534e49"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### ConstantsCodes {#a2f7b2c9070dd196b7bad476149a7ece1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::ConstantsCodes </td>
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
<td class="doxyEnumItemName">CST_CODE_SETTYPE<a id="a2f7b2c9070dd196b7bad476149a7ece1a615b7d9a9b0dd9a38b48a03014c91205"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_NULL<a id="a2f7b2c9070dd196b7bad476149a7ece1a6dd3ec70d9bb6ea798062918c24be3e2"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_UNDEF<a id="a2f7b2c9070dd196b7bad476149a7ece1a638a6258cf684c2497cd615d44403c65"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_INTEGER<a id="a2f7b2c9070dd196b7bad476149a7ece1ae8e99bc177e1fbaa5ab0b14c04674e39"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_WIDE_INTEGER<a id="a2f7b2c9070dd196b7bad476149a7ece1a77c08ad95a17ee3c44e649703986c446"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_FLOAT<a id="a2f7b2c9070dd196b7bad476149a7ece1ade716eb7c08e118453d2b9e8e2003b0e"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_AGGREGATE<a id="a2f7b2c9070dd196b7bad476149a7ece1aa43eb4e99dfc2ea771558d9f41cbc702"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_STRING<a id="a2f7b2c9070dd196b7bad476149a7ece1a5f9eee5ce32e85ce447fcd1a55905850"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_CSTRING<a id="a2f7b2c9070dd196b7bad476149a7ece1accff715dd13050e8889db22ee3e0ac6d"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_CE_BINOP<a id="a2f7b2c9070dd196b7bad476149a7ece1a460c1c80bc1a1d440bff73a0a15e11b1"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_CE_CAST<a id="a2f7b2c9070dd196b7bad476149a7ece1af9c706ecdb4b221f99074e80807d37d3"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_CE_GEP_OLD<a id="a2f7b2c9070dd196b7bad476149a7ece1a3d526f5036b3e2d2f89976e026bbde44"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_CE_SELECT<a id="a2f7b2c9070dd196b7bad476149a7ece1aa87b8dc24ac25fd3f71eb26950afbfd5"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_CE_EXTRACTELT<a id="a2f7b2c9070dd196b7bad476149a7ece1a2e6b4f954f438256da322e1bb755d74c"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_CE_INSERTELT<a id="a2f7b2c9070dd196b7bad476149a7ece1ac13408594bb9f719415ba5c5f3924f63"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_CE_SHUFFLEVEC<a id="a2f7b2c9070dd196b7bad476149a7ece1a58fccbd1073eeb8115dc36a258124b8d"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_CE_CMP<a id="a2f7b2c9070dd196b7bad476149a7ece1a8ffb50b5a5e30d57a4106a22b41496f7"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_INLINEASM_OLD<a id="a2f7b2c9070dd196b7bad476149a7ece1a484390ddb236870542b182545792f2e1"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_CE_SHUFVEC_EX<a id="a2f7b2c9070dd196b7bad476149a7ece1a2810d0bf828889f8abd544ac5a1c2d54"></a></td>
<td class="doxyEnumItemDescription"> (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_CE_INBOUNDS_GEP<a id="a2f7b2c9070dd196b7bad476149a7ece1a0299ea69812d4a1fb87f1f17df9ea34d"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_BLOCKADDRESS<a id="a2f7b2c9070dd196b7bad476149a7ece1a0a3559a40967f759fb2678b53fd6fbfc"></a></td>
<td class="doxyEnumItemDescription"> (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_DATA<a id="a2f7b2c9070dd196b7bad476149a7ece1a159ced9d6dfc127b7672fc59ad43a7fe"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_INLINEASM_OLD2<a id="a2f7b2c9070dd196b7bad476149a7ece1ac244225be847df7b49e39ac895044396"></a></td>
<td class="doxyEnumItemDescription"> (= 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_CE_GEP_WITH_INRANGE_INDEX_OLD<a id="a2f7b2c9070dd196b7bad476149a7ece1a4c50c723fd6927ffab52abaec5133515"></a></td>
<td class="doxyEnumItemDescription"> (= 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_CE_UNOP<a id="a2f7b2c9070dd196b7bad476149a7ece1ac3ddb1f0b4301357b279ac8d517c904f"></a></td>
<td class="doxyEnumItemDescription"> (= 25)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_POISON<a id="a2f7b2c9070dd196b7bad476149a7ece1aee59bbbdf387e5ecefeacfd47dd63b2d"></a></td>
<td class="doxyEnumItemDescription"> (= 26)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_DSO_LOCAL_EQUIVALENT<a id="a2f7b2c9070dd196b7bad476149a7ece1a7f028f12de7ece5425b6d997623000db"></a></td>
<td class="doxyEnumItemDescription"> (= 27)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_INLINEASM_OLD3<a id="a2f7b2c9070dd196b7bad476149a7ece1a06f9cade2de2244cd92f232a6edbf0cc"></a></td>
<td class="doxyEnumItemDescription"> (= 28)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_NO_CFI_VALUE<a id="a2f7b2c9070dd196b7bad476149a7ece1a0aeccbcd15bd58a3aa59ca5fb6fb7042"></a></td>
<td class="doxyEnumItemDescription"> (= 29)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_INLINEASM<a id="a2f7b2c9070dd196b7bad476149a7ece1afa8c4184622cc5f8c37e5ba4fd992cf2"></a></td>
<td class="doxyEnumItemDescription"> (= 30)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_CE_GEP_WITH_INRANGE<a id="a2f7b2c9070dd196b7bad476149a7ece1adebe24358ce2f8706504bdf440f357c1"></a></td>
<td class="doxyEnumItemDescription"> (= 31)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_CE_GEP<a id="a2f7b2c9070dd196b7bad476149a7ece1a7bac8da63ca5744ca7fc806d0977fe5b"></a></td>
<td class="doxyEnumItemDescription"> (= 32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CST_CODE_PTRAUTH<a id="a2f7b2c9070dd196b7bad476149a7ece1a8e5218b44ccf80d689ee54d4ed422f77"></a></td>
<td class="doxyEnumItemDescription"> (= 33)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### FastMathMap {#abd587fc6c85f5fca5adea50beb5a040a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::FastMathMap </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FastMath Flags This is a fixed layout derived from the bitcode emitted by LLVM 5.0 intended to decouple the in-memory representation from the serialization.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnsafeAlgebra<a id="abd587fc6c85f5fca5adea50beb5a040aab9ae7390ca4271aea1cc0fd8ad959ed2"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 0))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoNaNs<a id="abd587fc6c85f5fca5adea50beb5a040aa0b6078f1d27619490c8569776bfaea2f"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 1))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoInfs<a id="abd587fc6c85f5fca5adea50beb5a040aa7615867f60ad3984f710b758a7fa794a"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 2))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoSignedZeros<a id="abd587fc6c85f5fca5adea50beb5a040aa5570d4f40666e6352950e1e45696cbd2"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 3))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowReciprocal<a id="abd587fc6c85f5fca5adea50beb5a040aafa457615c7642f4cb8e1758bc6673c09"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 4))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowContract<a id="abd587fc6c85f5fca5adea50beb5a040aa4601e39685b21855202598fbbbf483c8"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 5))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ApproxFunc<a id="abd587fc6c85f5fca5adea50beb5a040aa3f8ef5ee785e3c0ea9c691175a6de5b0"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 6))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowReassoc<a id="abd587fc6c85f5fca5adea50beb5a040aaf1a502f88e347fddad4ee0750b994975"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 7))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### FixedAbbrevIDs {#ab7a76f80792b96a4291e2d1dd1403887}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::FixedAbbrevIDs </td>
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
<td class="doxyEnumItemName">END_BLOCK<a id="ab7a76f80792b96a4291e2d1dd1403887aee620990aa08180f9ede6fd5c8440620"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ENTER_SUBBLOCK<a id="ab7a76f80792b96a4291e2d1dd1403887a8ade579114e64f6e93e5c2335d9790b3"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DEFINE_ABBREV<a id="ab7a76f80792b96a4291e2d1dd1403887a0353c03d98b211f15e10bad35397bf8d"></a></td>
<td class="doxyEnumItemDescription">DEFINE_ABBREV - Defines an abbrev for the current block (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNABBREV_RECORD<a id="ab7a76f80792b96a4291e2d1dd1403887a5436567dadf1048914764efde6bcc891"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_APPLICATION_ABBREV<a id="ab7a76f80792b96a4291e2d1dd1403887a81e1f263b022b7989aa71fb623b62be8"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitcodeenums-h">BitCodeEnums.h</a>.</p>

</div>
</div>

### FunctionCodes {#aa0c35b333cf09bfd3e6ff0319f936709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::FunctionCodes </td>
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
<td class="doxyEnumItemName">FUNC_CODE_DECLAREBLOCKS<a id="aa0c35b333cf09bfd3e6ff0319f936709a8ec97786f105ca8121a2806de4ec1682"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_BINOP<a id="aa0c35b333cf09bfd3e6ff0319f936709a80cdd435cd736d03e6c58d0666401791"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_CAST<a id="aa0c35b333cf09bfd3e6ff0319f936709adfd8782051a9ba7d35cbeb408bdd41c0"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_GEP_OLD<a id="aa0c35b333cf09bfd3e6ff0319f936709a3bfaac1967f78faf179bea4d3fd7b41f"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_SELECT<a id="aa0c35b333cf09bfd3e6ff0319f936709aaf044edeca1569183fb50db6b58a5b8d"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_EXTRACTELT<a id="aa0c35b333cf09bfd3e6ff0319f936709a8544820faf36e26de560162328332285"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_INSERTELT<a id="aa0c35b333cf09bfd3e6ff0319f936709aa914c0c7f2dd1d33d79e1b7bbebe2bb1"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_SHUFFLEVEC<a id="aa0c35b333cf09bfd3e6ff0319f936709ac55f3a60eb17c44127f080cda8d22cd6"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_CMP<a id="aa0c35b333cf09bfd3e6ff0319f936709aff6314c2931bf11bfa6b4741ae78e369"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_RET<a id="aa0c35b333cf09bfd3e6ff0319f936709a9ebd23d8bb4a995028e7fd7572c88658"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_BR<a id="aa0c35b333cf09bfd3e6ff0319f936709a372a25b3e95b1934c391c28dda7afbb5"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_SWITCH<a id="aa0c35b333cf09bfd3e6ff0319f936709a98a5f24c7ec19951d7eeaf5143f69edc"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_INVOKE<a id="aa0c35b333cf09bfd3e6ff0319f936709a895cae59a4bbe80be66bd28ab38d9f23"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_UNREACHABLE<a id="aa0c35b333cf09bfd3e6ff0319f936709adbdf010c5800d23bee0415c1bab909cd"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_PHI<a id="aa0c35b333cf09bfd3e6ff0319f936709a9e163d0818beeeef65ccae3f844ab399"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_ALLOCA<a id="aa0c35b333cf09bfd3e6ff0319f936709aa7ec8c59479d3e6b56f371cfcfb77ef4"></a></td>
<td class="doxyEnumItemDescription"> (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_LOAD<a id="aa0c35b333cf09bfd3e6ff0319f936709a65611800ff5be3f82a509cd9245365ff"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_VAARG<a id="aa0c35b333cf09bfd3e6ff0319f936709ad38569d0a72dcd786ee8a523806bd0d4"></a></td>
<td class="doxyEnumItemDescription"> (= 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_STORE_OLD<a id="aa0c35b333cf09bfd3e6ff0319f936709acad2211f69d8463b82fc9c246306653a"></a></td>
<td class="doxyEnumItemDescription"> (= 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_EXTRACTVAL<a id="aa0c35b333cf09bfd3e6ff0319f936709a0d433f85ab42c50a5be3af49a7f6a7b1"></a></td>
<td class="doxyEnumItemDescription"> (= 26)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_INSERTVAL<a id="aa0c35b333cf09bfd3e6ff0319f936709a8b6b2cfa5c2e4343d5ae00030b5b1e69"></a></td>
<td class="doxyEnumItemDescription"> (= 27)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_CMP2<a id="aa0c35b333cf09bfd3e6ff0319f936709a23b9ffb88c6b3410c752244f31fa82fe"></a></td>
<td class="doxyEnumItemDescription"> (= 28)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_VSELECT<a id="aa0c35b333cf09bfd3e6ff0319f936709a3b1db1eb7ef5dd992c240db47027a255"></a></td>
<td class="doxyEnumItemDescription"> (= 29)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_INBOUNDS_GEP_OLD<a id="aa0c35b333cf09bfd3e6ff0319f936709a39da947ba8670bf8683cc2efc71612a5"></a></td>
<td class="doxyEnumItemDescription"> (= 30)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_INDIRECTBR<a id="aa0c35b333cf09bfd3e6ff0319f936709a87fea78eff9a3d303fc3587f912c9c61"></a></td>
<td class="doxyEnumItemDescription"> (= 31)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_DEBUG_LOC_AGAIN<a id="aa0c35b333cf09bfd3e6ff0319f936709a82fc66690625c22e5ff66ceb0dd15bd8"></a></td>
<td class="doxyEnumItemDescription"> (= 33)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_CALL<a id="aa0c35b333cf09bfd3e6ff0319f936709aa2c833971b47f8923073ed2e8ddc7ede"></a></td>
<td class="doxyEnumItemDescription"> (= 34)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_DEBUG_LOC<a id="aa0c35b333cf09bfd3e6ff0319f936709ae9b294a6548e1e37574235a995a9e4fb"></a></td>
<td class="doxyEnumItemDescription"> (= 35)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_FENCE<a id="aa0c35b333cf09bfd3e6ff0319f936709a275c95920a145c6599a241fd51c52c4d"></a></td>
<td class="doxyEnumItemDescription"> (= 36)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_CMPXCHG_OLD<a id="aa0c35b333cf09bfd3e6ff0319f936709ae83eb4eb7d8c8ea86b88cbbd170ac87f"></a></td>
<td class="doxyEnumItemDescription"> (= 37)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_ATOMICRMW_OLD<a id="aa0c35b333cf09bfd3e6ff0319f936709a00c7ea10889f542a5e85f8e5576501fc"></a></td>
<td class="doxyEnumItemDescription"> (= 38)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_RESUME<a id="aa0c35b333cf09bfd3e6ff0319f936709a1fe13a7317ace585929d38143776cc53"></a></td>
<td class="doxyEnumItemDescription"> (= 39)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_LANDINGPAD_OLD<a id="aa0c35b333cf09bfd3e6ff0319f936709a4ec4e4326cc36fa835d31578805423c0"></a></td>
<td class="doxyEnumItemDescription">
 (=
      40)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_LOADATOMIC<a id="aa0c35b333cf09bfd3e6ff0319f936709a5d2f3872eea57aea19c31eebc9149ad6"></a></td>
<td class="doxyEnumItemDescription"> (= 41)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_STOREATOMIC_OLD<a id="aa0c35b333cf09bfd3e6ff0319f936709a424a24f4d7afa3b8e1681c89eaf9bbbe"></a></td>
<td class="doxyEnumItemDescription"> (= 42)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_GEP<a id="aa0c35b333cf09bfd3e6ff0319f936709a40eeeeea5d8582fe3c771765db09da7a"></a></td>
<td class="doxyEnumItemDescription"> (= 43)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_STORE<a id="aa0c35b333cf09bfd3e6ff0319f936709a82097d593b57375f64905836e91389bf"></a></td>
<td class="doxyEnumItemDescription"> (= 44)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_STOREATOMIC<a id="aa0c35b333cf09bfd3e6ff0319f936709a6c4d0b70bf0c3ae8fcff5b456898aaf1"></a></td>
<td class="doxyEnumItemDescription"> (= 45)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_CMPXCHG<a id="aa0c35b333cf09bfd3e6ff0319f936709ada2b67ecaa3a7b46f0724674de4633c6"></a></td>
<td class="doxyEnumItemDescription"> (= 46)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_LANDINGPAD<a id="aa0c35b333cf09bfd3e6ff0319f936709a0732dcfe2a0ab6550dd78d9c2c1f649a"></a></td>
<td class="doxyEnumItemDescription"> (= 47)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_CLEANUPRET<a id="aa0c35b333cf09bfd3e6ff0319f936709a4ca5f79d9ab3a432c677a8a33dd233de"></a></td>
<td class="doxyEnumItemDescription"> (= 48)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_CATCHRET<a id="aa0c35b333cf09bfd3e6ff0319f936709a0384dbf1b0606d1351bf871d079f4510"></a></td>
<td class="doxyEnumItemDescription"> (= 49)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_CATCHPAD<a id="aa0c35b333cf09bfd3e6ff0319f936709a1ca8db37585ec3afb5abbddc3c84b7db"></a></td>
<td class="doxyEnumItemDescription"> (= 50)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_CLEANUPPAD<a id="aa0c35b333cf09bfd3e6ff0319f936709ac39726229e7356b0826eda152b19b6b5"></a></td>
<td class="doxyEnumItemDescription"> (= 51)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_CATCHSWITCH<a id="aa0c35b333cf09bfd3e6ff0319f936709a36d5a96cbf2be368ff1a11cafc1bab86"></a></td>
<td class="doxyEnumItemDescription">
 (=
      52)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_OPERAND_BUNDLE<a id="aa0c35b333cf09bfd3e6ff0319f936709aff2a5877ee471d7757a92da4a9b2cfbc"></a></td>
<td class="doxyEnumItemDescription"> (= 55)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_UNOP<a id="aa0c35b333cf09bfd3e6ff0319f936709ac9e67a4dfd9e6bb9f8da5d519be3ef09"></a></td>
<td class="doxyEnumItemDescription"> (= 56)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_CALLBR<a id="aa0c35b333cf09bfd3e6ff0319f936709a27a322a0457f7a70b26a0dac8ea31100"></a></td>
<td class="doxyEnumItemDescription"> (= 57)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_FREEZE<a id="aa0c35b333cf09bfd3e6ff0319f936709ad3aa875041b1654bf46969e17cad4708"></a></td>
<td class="doxyEnumItemDescription"> (= 58)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_INST_ATOMICRMW<a id="aa0c35b333cf09bfd3e6ff0319f936709a76ab7d89dab4a3baefe3a8848591b1dc"></a></td>
<td class="doxyEnumItemDescription"> (= 59)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_BLOCKADDR_USERS<a id="aa0c35b333cf09bfd3e6ff0319f936709ac0f6ff2c7c93422bba8343e4231dbb76"></a></td>
<td class="doxyEnumItemDescription"> (= 60)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_DEBUG_RECORD_VALUE<a id="aa0c35b333cf09bfd3e6ff0319f936709a5210095cb3b666ff6e75b8db71f5d614"></a></td>
<td class="doxyEnumItemDescription">
 (=
      61)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_DEBUG_RECORD_DECLARE<a id="aa0c35b333cf09bfd3e6ff0319f936709af6daa01c2b17212dbfb7e4bff3b8a07a"></a></td>
<td class="doxyEnumItemDescription">
 (=
      62)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_DEBUG_RECORD_ASSIGN<a id="aa0c35b333cf09bfd3e6ff0319f936709a5f980d2c445f4fff5fe7c1ad4620b6c3"></a></td>
<td class="doxyEnumItemDescription">
 (=
      63)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_DEBUG_RECORD_VALUE_SIMPLE<a id="aa0c35b333cf09bfd3e6ff0319f936709a8a98d62c433e16e871f96cb52c2b22b8"></a></td>
<td class="doxyEnumItemDescription">
 (=
      64)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_CODE_DEBUG_RECORD_LABEL<a id="aa0c35b333cf09bfd3e6ff0319f936709a9882a24e599d6b4ef630d38f1d4f5f5f"></a></td>
<td class="doxyEnumItemDescription"> (= 65)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### GetElementPtrOptionalFlags {#a33a73a3b8d28548e6e3216801bf93207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::GetElementPtrOptionalFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a33a73a3b8d28548e6e3216801bf93207">GetElementPtrOptionalFlags</a> - Flags for serializing <a href="/web-llvm/docs/api/classes/llvm/gepoperator">GEPOperator</a>'s SubclassOptionalData contents.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GEP_INBOUNDS<a id="a33a73a3b8d28548e6e3216801bf93207a1d40dfa2a367a9a21810697c5cfc136a"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GEP_NUSW<a id="a33a73a3b8d28548e6e3216801bf93207acd28ff8cbc5d1a5526f142fb27c6c6a3"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GEP_NUW<a id="a33a73a3b8d28548e6e3216801bf93207aa12e0bcbdd56def413c412f7ba95bd37"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### GlobalValueSummarySymtabCodes {#a2889cf6772f22a2e9c802b6c4cb5001b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::GlobalValueSummarySymtabCodes </td>
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
<td class="doxyEnumItemName">FS_PERMODULE<a id="a2889cf6772f22a2e9c802b6c4cb5001ba218fc7065e409670a4db25cbfd87fbb0"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_PERMODULE_PROFILE<a id="a2889cf6772f22a2e9c802b6c4cb5001bac9d1b09e39f4a5cce9548cdecd7d01fc"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_PERMODULE_GLOBALVAR_INIT_REFS<a id="a2889cf6772f22a2e9c802b6c4cb5001ba7eed6dde835daccb38574b36fb17ba32"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_COMBINED<a id="a2889cf6772f22a2e9c802b6c4cb5001ba499eba4e7d704808d5a935ddff46fdb4"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_COMBINED_PROFILE<a id="a2889cf6772f22a2e9c802b6c4cb5001ba5177b0ea0b691b7304e3445f8ecd1002"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_COMBINED_GLOBALVAR_INIT_REFS<a id="a2889cf6772f22a2e9c802b6c4cb5001ba4497ed1a33e7e2ada991426e806ea2db"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_ALIAS<a id="a2889cf6772f22a2e9c802b6c4cb5001ba711d24e5a54cc4b6d0f0f026c6dea25b"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_COMBINED_ALIAS<a id="a2889cf6772f22a2e9c802b6c4cb5001ba8558167549f906ed44231ad2bb14fb08"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_COMBINED_ORIGINAL_NAME<a id="a2889cf6772f22a2e9c802b6c4cb5001ba5aa7b73820241a2bed4f22d5c9909c00"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_VERSION<a id="a2889cf6772f22a2e9c802b6c4cb5001baf03cc9df6c5e873d398960808be1f1db"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_TYPE_TESTS<a id="a2889cf6772f22a2e9c802b6c4cb5001baa2b70896e3139d999510f2727813fc96"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_TYPE_TEST_ASSUME_VCALLS<a id="a2889cf6772f22a2e9c802b6c4cb5001ba88548f8be84646655fdcf04c9d07bb93"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_TYPE_CHECKED_LOAD_VCALLS<a id="a2889cf6772f22a2e9c802b6c4cb5001ba504e48194f2217cbe18f1513474ee0fd"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_TYPE_TEST_ASSUME_CONST_VCALL<a id="a2889cf6772f22a2e9c802b6c4cb5001ba70ca6811ccd6f4269cd2b835bcaa91a6"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_TYPE_CHECKED_LOAD_CONST_VCALL<a id="a2889cf6772f22a2e9c802b6c4cb5001bafbca7a60ed87076dcc60f196385f0f84"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_VALUE_GUID<a id="a2889cf6772f22a2e9c802b6c4cb5001ba3950f7c2a51d13d881e4796aec4fcd4d"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_CFI_FUNCTION_DEFS<a id="a2889cf6772f22a2e9c802b6c4cb5001ba2f14cd6bdc10b8fc739b25be9fc05369"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_CFI_FUNCTION_DECLS<a id="a2889cf6772f22a2e9c802b6c4cb5001ba9a4c09c65abb1174fe3b962be8dad3a6"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_PERMODULE_RELBF<a id="a2889cf6772f22a2e9c802b6c4cb5001ba40d4866bc945500aef3ea87a8c509f06"></a></td>
<td class="doxyEnumItemDescription"> (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_FLAGS<a id="a2889cf6772f22a2e9c802b6c4cb5001bab8c67884cc3a90c02a0a6916d896dd83"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_TYPE_ID<a id="a2889cf6772f22a2e9c802b6c4cb5001ba7a82930dde5c37970562dbf5e7f7b63b"></a></td>
<td class="doxyEnumItemDescription"> (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_TYPE_ID_METADATA<a id="a2889cf6772f22a2e9c802b6c4cb5001ba5d7d125d00b7735770b5376070b7ede6"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_PERMODULE_VTABLE_GLOBALVAR_INIT_REFS<a id="a2889cf6772f22a2e9c802b6c4cb5001ba5d8354b96ed844da9b633e551c4b9bf7"></a></td>
<td class="doxyEnumItemDescription"> (= 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_BLOCK_COUNT<a id="a2889cf6772f22a2e9c802b6c4cb5001ba18ac0246f06475392afb5a095d7cc887"></a></td>
<td class="doxyEnumItemDescription"> (= 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_PARAM_ACCESS<a id="a2889cf6772f22a2e9c802b6c4cb5001ba59c59629c5fe384b7c23381d6bb44b14"></a></td>
<td class="doxyEnumItemDescription"> (= 25)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_PERMODULE_CALLSITE_INFO<a id="a2889cf6772f22a2e9c802b6c4cb5001badeba38c1dfee61f7d2dac12d39046937"></a></td>
<td class="doxyEnumItemDescription"> (= 26)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_PERMODULE_ALLOC_INFO<a id="a2889cf6772f22a2e9c802b6c4cb5001bae00c1b00b0336f5f501530553eb51324"></a></td>
<td class="doxyEnumItemDescription"> (= 27)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_COMBINED_CALLSITE_INFO<a id="a2889cf6772f22a2e9c802b6c4cb5001bab379fe6d08288d8a29cf0d8993b5f05a"></a></td>
<td class="doxyEnumItemDescription"> (= 28)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_COMBINED_ALLOC_INFO<a id="a2889cf6772f22a2e9c802b6c4cb5001babe5d1caab319ca559948c13bbcee0f25"></a></td>
<td class="doxyEnumItemDescription"> (= 29)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_STACK_IDS<a id="a2889cf6772f22a2e9c802b6c4cb5001babeb8f3e136c6d5b652c79eba7d2ac9df"></a></td>
<td class="doxyEnumItemDescription"> (= 30)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_ALLOC_CONTEXT_IDS<a id="a2889cf6772f22a2e9c802b6c4cb5001ba52dd969c2b5e24add5ca2516ed0f200d"></a></td>
<td class="doxyEnumItemDescription"> (= 31)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_CONTEXT_RADIX_TREE_ARRAY<a id="a2889cf6772f22a2e9c802b6c4cb5001ba0b88f487f51959e29f9a30be85640735"></a></td>
<td class="doxyEnumItemDescription"> (= 32)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### ICmpOptionalFlags {#ab07949314720a391bf9a4ec0dfb6289a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::ICmpOptionalFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#ab07949314720a391bf9a4ec0dfb6289a">ICmpOptionalFlags</a> - Flags for serializing <a href="#ab07949314720a391bf9a4ec0dfb6289a">ICmpOptionalFlags</a>'s SubclassOptionalData contents.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICMP_SAME_SIGN<a id="ab07949314720a391bf9a4ec0dfb6289aae42c00bdc25c89dc217009a8669ce7d6"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### IdentificationCodes {#a2dde66e038f5a0836d72e760f731a4b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::IdentificationCodes </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identification block contains a string that describes the producer details, and an epoch that defines the auto-upgrade capability.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IDENTIFICATION_CODE_STRING<a id="a2dde66e038f5a0836d72e760f731a4b4ad0b7a34426fe13ee6793888a32698b4e"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IDENTIFICATION_CODE_EPOCH<a id="a2dde66e038f5a0836d72e760f731a4b4ab33f9d97fa7abd55725a6a62e6250bd1"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### MetadataCodes {#a1439ec3246fdaf3a3b4fb4f4e2683c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::MetadataCodes </td>
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
<td class="doxyEnumItemName">METADATA_STRING_OLD<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca372a73e1273cd4fb80d17f35d3599dec"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_VALUE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca2469cdf3c45af7657f2be883dd766bde"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_NODE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca827f985c260939faf890ac3401bb7967"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_NAME<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca2d740b120f74fcc50412a6518b9cb98e"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_DISTINCT_NODE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5caed90ec4ecfd6c681982c5a0b33ae36a8"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_KIND<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5cacd9207463da1cc7603576917ab4296d8"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_LOCATION<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5cafeae0a17f548db16715e57864553765a"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_OLD_NODE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca84b37b0697960922303a8c239035c2f6"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_OLD_FN_NODE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca8dd410c637aec4f517ebf48286fb779a"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_NAMED_NODE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca732b52c6b54a49a71d6a444c5bae70f5"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_ATTACHMENT<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca6a68c84bdb7ea2c3c9605c493f95f3e4"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_GENERIC_DEBUG<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5caf82e1dbc46c3bbef0e0fd6746445bc16"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_SUBRANGE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca28cd0bea6333cacd82b666aba7be01b6"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_ENUMERATOR<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5caacb02e0ab64961939b3cc56f1e62c02d"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_BASIC_TYPE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5cadecb0c91b1adcb848188803405669200"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_FILE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca2131ac9f9f21b0f3a629d7acd0e2c37f"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_DERIVED_TYPE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5caae742dfb63423efd37ce2ec5bb8d18d9"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_COMPOSITE_TYPE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca8be178af204cf42197404dcb8dd9e30f"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_SUBROUTINE_TYPE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca4e99c99acddacb0e05e5dc01bdc18a02"></a></td>
<td class="doxyEnumItemDescription"> (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_COMPILE_UNIT<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca88b1fb532ad205b229c53ec465bf6a83"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_SUBPROGRAM<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca42578cc539b7ea9ac47fdb3dcd43a0a6"></a></td>
<td class="doxyEnumItemDescription"> (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_LEXICAL_BLOCK<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca3be06296a291d3c55668dc1ea108669c"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_LEXICAL_BLOCK_FILE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca2cbb0e86898a8f744c7a36dc900e6b8d"></a></td>
<td class="doxyEnumItemDescription"> (= 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_NAMESPACE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca130d54871eb8ffb5060c6cfe1dc8b06e"></a></td>
<td class="doxyEnumItemDescription"> (= 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_TEMPLATE_TYPE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5cacfdb927dcd76d9e1bfecf28d4be7ba88"></a></td>
<td class="doxyEnumItemDescription"> (= 25)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_TEMPLATE_VALUE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca2ab955ef080ad8e8f8e049829d9ccc55"></a></td>
<td class="doxyEnumItemDescription"> (= 26)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_GLOBAL_VAR<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca5f84a160180a5cb64d62e73587a5f49a"></a></td>
<td class="doxyEnumItemDescription"> (= 27)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_LOCAL_VAR<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca589678bd10540bc94300b406b2027e77"></a></td>
<td class="doxyEnumItemDescription"> (= 28)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_EXPRESSION<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca614e0a7125b0e180f987863797a9f41a"></a></td>
<td class="doxyEnumItemDescription"> (= 29)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_OBJC_PROPERTY<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca7024402008d28404afeec7d6e5f19600"></a></td>
<td class="doxyEnumItemDescription"> (= 30)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_IMPORTED_ENTITY<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca82869222725e4435d9ed09b0b6bd8508"></a></td>
<td class="doxyEnumItemDescription"> (= 31)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_MODULE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5caf8cb5952d4e57a66d58b7270c65d75fc"></a></td>
<td class="doxyEnumItemDescription"> (= 32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_MACRO<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5caf48b9611039df4625cc52cb11d01fdb4"></a></td>
<td class="doxyEnumItemDescription"> (= 33)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_MACRO_FILE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca1cc51c534fdb1ee7442fac80e3a5cd3a"></a></td>
<td class="doxyEnumItemDescription"> (= 34)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_STRINGS<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca2a61d14a978b399c1b37c016a80a3924"></a></td>
<td class="doxyEnumItemDescription"> (= 35)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_GLOBAL_DECL_ATTACHMENT<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca56f0c251969e37689eb11943a0a2ec75"></a></td>
<td class="doxyEnumItemDescription"> (= 36)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_GLOBAL_VAR_EXPR<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5cadab88c3ced06d1e13772846e4aab32cd"></a></td>
<td class="doxyEnumItemDescription"> (= 37)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_INDEX_OFFSET<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca39ce80fab8b00b665cfcc0effac8cb2b"></a></td>
<td class="doxyEnumItemDescription"> (= 38)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_INDEX<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca380f5b65b785ef2784b256f57b117d54"></a></td>
<td class="doxyEnumItemDescription"> (= 39)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_LABEL<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5caff13508101b196449d79633abe378d86"></a></td>
<td class="doxyEnumItemDescription"> (= 40)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_STRING_TYPE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca1c69f39a27a6e4a428ab6658cbbd2878"></a></td>
<td class="doxyEnumItemDescription"> (= 41)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_COMMON_BLOCK<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca16272aa236980c31363ff798446db035"></a></td>
<td class="doxyEnumItemDescription"> (= 44)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_GENERIC_SUBRANGE<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca87ef5efa088447b4fb7a84f29191ec71"></a></td>
<td class="doxyEnumItemDescription"> (= 45)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_ARG_LIST<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5cadd60a1a4e12983f481ba5a0d658d7305"></a></td>
<td class="doxyEnumItemDescription"> (= 46)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">METADATA_ASSIGN_ID<a id="a1439ec3246fdaf3a3b4fb4f4e2683c5ca882f2234b1d076ded99b49e014fdc5f7"></a></td>
<td class="doxyEnumItemDescription"> (= 47)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### MetadataOperandBundleValueMarker {#a83900640a877b1deee5e2b561575717a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::MetadataOperandBundleValueMarker </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark to distinguish metadata from value in an operator bundle.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OB_METADATA<a id="a83900640a877b1deee5e2b561575717aae15f02b359ebdba764af23bb1054cdd5"></a></td>
<td class="doxyEnumItemDescription"> (= 0x80000000)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### ModuleCodes {#a9d51b2066d2ce0b9fe4f39f1a80f7c81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::ModuleCodes </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MODULE blocks have a number of optional fields and subblocks.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_CODE_VERSION<a id="a9d51b2066d2ce0b9fe4f39f1a80f7c81a163b11eb41c06566dbc6e03e9273cc59"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_CODE_TRIPLE<a id="a9d51b2066d2ce0b9fe4f39f1a80f7c81a61ad593c7421c65ebeb897f01da8b8bf"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_CODE_DATALAYOUT<a id="a9d51b2066d2ce0b9fe4f39f1a80f7c81a6703bf80d33247f566fb686c08ca05a3"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_CODE_ASM<a id="a9d51b2066d2ce0b9fe4f39f1a80f7c81ab85aa993dced273765d89e7ab7948156"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_CODE_SECTIONNAME<a id="a9d51b2066d2ce0b9fe4f39f1a80f7c81a1af915356ab04e24ff6c7bfba7cf2e7e"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_CODE_DEPLIB<a id="a9d51b2066d2ce0b9fe4f39f1a80f7c81a98b51602639f5b8e5b8a4923dc06de6d"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_CODE_GLOBALVAR<a id="a9d51b2066d2ce0b9fe4f39f1a80f7c81a71e354585ad9af847e81899d9e9045cc"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_CODE_FUNCTION<a id="a9d51b2066d2ce0b9fe4f39f1a80f7c81a0f98ccf6b361c7d704a34ae3abb8e9cf"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_CODE_ALIAS_OLD<a id="a9d51b2066d2ce0b9fe4f39f1a80f7c81a79e15cb55e97af4d35cab7a0938e9272"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_CODE_GCNAME<a id="a9d51b2066d2ce0b9fe4f39f1a80f7c81a95aaaa03c6d1b478f1a828e2a6f7c536"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_CODE_COMDAT<a id="a9d51b2066d2ce0b9fe4f39f1a80f7c81ae38955c5ad9326e44fba2871060a0999"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_CODE_VSTOFFSET<a id="a9d51b2066d2ce0b9fe4f39f1a80f7c81a7ecbb9458f443298c9f6e46cdfaa1ff2"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_CODE_ALIAS<a id="a9d51b2066d2ce0b9fe4f39f1a80f7c81a9036417d96ab001e460a784ee529748c"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_CODE_METADATA_VALUES_UNUSED<a id="a9d51b2066d2ce0b9fe4f39f1a80f7c81a3366c027fee58796814d13b48797947b"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_CODE_SOURCE_FILENAME<a id="a9d51b2066d2ce0b9fe4f39f1a80f7c81a19650d5060a76b566188987c86d79f74"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_CODE_HASH<a id="a9d51b2066d2ce0b9fe4f39f1a80f7c81ab91f122af3779bc28dea7291c3c801a7"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODULE_CODE_IFUNC<a id="a9d51b2066d2ce0b9fe4f39f1a80f7c81a7f25b65005508bc23c646a19e446cabc"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### ModulePathSymtabCodes {#af604f4afd5a27f2f0a5c642b26b8a2a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::ModulePathSymtabCodes </td>
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
<td class="doxyEnumItemName">MST_CODE_ENTRY<a id="af604f4afd5a27f2f0a5c642b26b8a2a4aa9424b8bdb4aa189c6db7d740b94897c"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MST_CODE_HASH<a id="af604f4afd5a27f2f0a5c642b26b8a2a4a81b15ee4941b6407d690391c1d5d1be2"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### OperandBundleTagCode {#abfc8b6b0a946284c6f212eda73571106}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::OperandBundleTagCode </td>
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
<td class="doxyEnumItemName">OPERAND_BUNDLE_TAG<a id="abfc8b6b0a946284c6f212eda73571106a03b8f2c0149ad8e7b2333fd069569571"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### OverflowingBinaryOperatorOptionalFlags {#a5d729bc0f60b0cc1cee0d3d16e8a6954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::OverflowingBinaryOperatorOptionalFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a5d729bc0f60b0cc1cee0d3d16e8a6954">OverflowingBinaryOperatorOptionalFlags</a> - Flags for serializing <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator">OverflowingBinaryOperator</a>'s SubclassOptionalData contents.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OBO_NO_UNSIGNED_WRAP<a id="a5d729bc0f60b0cc1cee0d3d16e8a6954a2fc4d70f7ea4e9bb62acf87e73ad6508"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OBO_NO_SIGNED_WRAP<a id="a5d729bc0f60b0cc1cee0d3d16e8a6954a23e6dd46c09ce9c6c771b637a5d3eb69"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### PossiblyDisjointInstOptionalFlags {#abbe7948ad74b8f0387de7e5ac03d6bcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::PossiblyDisjointInstOptionalFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#abbe7948ad74b8f0387de7e5ac03d6bcc">PossiblyDisjointInstOptionalFlags</a> - Flags for serializing <a href="/web-llvm/docs/api/classes/llvm/possiblydisjointinst">PossiblyDisjointInst</a>'s SubclassOptionalData contents.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PDI_DISJOINT<a id="abbe7948ad74b8f0387de7e5ac03d6bcca729f268e07c71da60f9df42ccc9d0e64"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### PossiblyExactOperatorOptionalFlags {#a49372e72493c55831abbcfcd59a3d49c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::PossiblyExactOperatorOptionalFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a49372e72493c55831abbcfcd59a3d49c">PossiblyExactOperatorOptionalFlags</a> - Flags for serializing <a href="/web-llvm/docs/api/classes/llvm/possiblyexactoperator">PossiblyExactOperator</a>'s SubclassOptionalData contents.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PEO_EXACT<a id="a49372e72493c55831abbcfcd59a3d49ca2bb97e5d0b49ccf94e9cae8079c4a4b5"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### PossiblyNonNegInstOptionalFlags {#a28b10e9b2658558a4b547ea0eb025ea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::PossiblyNonNegInstOptionalFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flags for serializing <a href="/web-llvm/docs/api/classes/llvm/possiblynonneginst">PossiblyNonNegInst</a>'s SubclassOptionalData contents.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PNNI_NON_NEG<a id="a28b10e9b2658558a4b547ea0eb025ea4adb47173b64643c09b501e6314972e1ca"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### RMWOperations {#a182436d33a9a893dc643e0c886111a4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::RMWOperations </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>These are values used in the bitcode files to encode AtomicRMW operations.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_XCHG<a id="a182436d33a9a893dc643e0c886111a4aa172fe635673085e6d5efc03db990e68e"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_ADD<a id="a182436d33a9a893dc643e0c886111a4aaf3617c1779061deeeae4a24e1c45d015"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_SUB<a id="a182436d33a9a893dc643e0c886111a4aa7786115a5d20e2d7377870813a8e91fe"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_AND<a id="a182436d33a9a893dc643e0c886111a4aa1fffe440fc04d4931be511a6759fb0bf"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_NAND<a id="a182436d33a9a893dc643e0c886111a4aaf1143967d78add27bf0a34cd120b05b9"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_OR<a id="a182436d33a9a893dc643e0c886111a4aa659ec22852b50f1b2907cb553ccd3003"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_XOR<a id="a182436d33a9a893dc643e0c886111a4aa75792f75bfdfd0639c08b8f4a6d7422e"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_MAX<a id="a182436d33a9a893dc643e0c886111a4aa0f7c09593b49ad69a24976fd79491ca9"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_MIN<a id="a182436d33a9a893dc643e0c886111a4aafef3e0c3498ab6999f170022e942b675"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_UMAX<a id="a182436d33a9a893dc643e0c886111a4aa974e4f980368e5eb72fbc4693ce077bc"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_UMIN<a id="a182436d33a9a893dc643e0c886111a4aa3458453a8e9b396ca571f9c7ee12b9fd"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_FADD<a id="a182436d33a9a893dc643e0c886111a4aa56e0b4e94e457f1abf28de75d156eed2"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_FSUB<a id="a182436d33a9a893dc643e0c886111a4aaae916e663743bef5cdc843ae1fe2bb50"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_FMAX<a id="a182436d33a9a893dc643e0c886111a4aaf6ff61c0bdbe5ab915efd9cdc1ffb3bc"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_FMIN<a id="a182436d33a9a893dc643e0c886111a4aa0f985a5852d333645b18af7dd342b366"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_UINC_WRAP<a id="a182436d33a9a893dc643e0c886111a4aadfffdd7e9faf02738adc9b4515142386"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_UDEC_WRAP<a id="a182436d33a9a893dc643e0c886111a4aa87c17066a291c0b1ce3d143cb4b33afc"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_USUB_COND<a id="a182436d33a9a893dc643e0c886111a4aa051d138a9600eacf2fe449622150a0c8"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMW_USUB_SAT<a id="a182436d33a9a893dc643e0c886111a4aa4d1e7498fe0b00010e93607c187c1c74"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

</table>
</dd>
</dl>


<p>The values of these enums have no fixed relation to the LLVM IR enum values. Changing these will break compatibility with old files.</p>


<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### StandardBlockIDs {#a8cd4dd534ba6c31e93a88ca286c4f0e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::StandardBlockIDs </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a8cd4dd534ba6c31e93a88ca286c4f0e5">StandardBlockIDs</a> - All bitcode files can optionally include a BLOCKINFO block, which contains metadata about other blocks in the file.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BLOCKINFO_BLOCK_ID<a id="a8cd4dd534ba6c31e93a88ca286c4f0e5a9c269366c4dc4af235c9bb24fa46f915"></a></td>
<td class="doxyEnumItemDescription">BLOCKINFO_BLOCK is used to define metadata about blocks, for example, standard abbrevs that should be available to all blocks of a specified <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_APPLICATION_BLOCKID<a id="a8cd4dd534ba6c31e93a88ca286c4f0e5ace7b0ab991cf2f44fb20f2f69cd3fdaa"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitcodeenums-h">BitCodeEnums.h</a>.</p>

</div>
</div>

### StandardWidths {#a9bbccfa3e710e59b93cc5a5bf8908cf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::StandardWidths </td>
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
<td class="doxyEnumItemName">BlockIDWidth<a id="a9bbccfa3e710e59b93cc5a5bf8908cf9a4ae63f558586ca60ba786b672433ed5b"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CodeLenWidth<a id="a9bbccfa3e710e59b93cc5a5bf8908cf9a81e88c5ec4ef96d2e57203df2ca9c7f8"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BlockSizeWidth<a id="a9bbccfa3e710e59b93cc5a5bf8908cf9aa1212eb73e20141e515bcf2f6cba192b"></a></td>
<td class="doxyEnumItemDescription"> (= 32)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitcodeenums-h">BitCodeEnums.h</a>.</p>

</div>
</div>

### StrtabCodes {#aa5f5b04f18dd0147ec2e2ee1dff56c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::StrtabCodes </td>
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
<td class="doxyEnumItemName">STRTAB_BLOB<a id="aa5f5b04f18dd0147ec2e2ee1dff56c06a8a6e8086acc7a4f894b953311c088549"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 802 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### SymtabCodes {#aeb428612b856bd084feccd8f480330de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::SymtabCodes </td>
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
<td class="doxyEnumItemName">SYMTAB_BLOB<a id="aeb428612b856bd084feccd8f480330dea1329b6bf1ed0b214660309e1a7e4e04c"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### SyncScopeNameCode {#ad0a4286c0d9599fd2b3d20f54c883f16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::SyncScopeNameCode </td>
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
<td class="doxyEnumItemName">SYNC_SCOPE_NAME<a id="ad0a4286c0d9599fd2b3d20f54c883f16a23313ec58028c7d305cfea01f0e0a650"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### TruncInstOptionalFlags {#a5e90fa071e4abe5068075a0b4b439a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::TruncInstOptionalFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a5e90fa071e4abe5068075a0b4b439a38">TruncInstOptionalFlags</a> - Flags for serializing <a href="#a5e90fa071e4abe5068075a0b4b439a38">TruncInstOptionalFlags</a>'s SubclassOptionalData contents.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TIO_NO_UNSIGNED_WRAP<a id="a5e90fa071e4abe5068075a0b4b439a38a7193269bf64e9b883163cf75b6aa2166"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TIO_NO_SIGNED_WRAP<a id="a5e90fa071e4abe5068075a0b4b439a38aea126ab6cd8b69e4de1361fe655d981f"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### TypeCodes {#a0bcdd46f107a31184119f65702c0889f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::TypeCodes </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>TYPE blocks have codes for each type primitive they use.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_NUMENTRY<a id="a0bcdd46f107a31184119f65702c0889fad15750f20f7cfbb0cb646da483a684a0"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_VOID<a id="a0bcdd46f107a31184119f65702c0889fa1f5b3dca026d8b0e349657ba5bf0d517"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_FLOAT<a id="a0bcdd46f107a31184119f65702c0889fa900602f2b5f0265f26ac553f5d10e2a7"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_DOUBLE<a id="a0bcdd46f107a31184119f65702c0889fabc5ff06bf0aef888c48eebf02bfd66e2"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_LABEL<a id="a0bcdd46f107a31184119f65702c0889fa18d847861b36874746c22843f0d3bab9"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_OPAQUE<a id="a0bcdd46f107a31184119f65702c0889fa16500f1c14e036b1e442d5b621194751"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_INTEGER<a id="a0bcdd46f107a31184119f65702c0889faa467313477151be600701d8d79452c14"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_POINTER<a id="a0bcdd46f107a31184119f65702c0889fab323e9936937ab8b21f6e7b6cd79880d"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_FUNCTION_OLD<a id="a0bcdd46f107a31184119f65702c0889fadc741bbfcad4733df6d4fdf5495b00de"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_HALF<a id="a0bcdd46f107a31184119f65702c0889fa315d1bf8eb818c5eae8c6936c3f1adb9"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_ARRAY<a id="a0bcdd46f107a31184119f65702c0889fabc4e2642417d9237a7510f3dcd147c3d"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_VECTOR<a id="a0bcdd46f107a31184119f65702c0889fa430b0cbfc0e9ad7a9f13a734587b942e"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_X86_FP80<a id="a0bcdd46f107a31184119f65702c0889fa72ad152f4482c2a829e095d5c7da1da1"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_FP128<a id="a0bcdd46f107a31184119f65702c0889fac298b420050b96d112fbf70bc2b9e4e3"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_PPC_FP128<a id="a0bcdd46f107a31184119f65702c0889fa4e10410f91aef4324d9b03bed3d4758f"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_METADATA<a id="a0bcdd46f107a31184119f65702c0889fa2302891ae626f5f874c98e076d10a061"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_X86_MMX<a id="a0bcdd46f107a31184119f65702c0889fa7f1f1a9a348c8fb79be0e0bfaf0d1f3b"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_STRUCT_ANON<a id="a0bcdd46f107a31184119f65702c0889fa53db2ee4c2c6edcdc8584702594cad50"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_STRUCT_NAME<a id="a0bcdd46f107a31184119f65702c0889fa62750d3b525b51265efe1e4f6e752d3f"></a></td>
<td class="doxyEnumItemDescription"> (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_STRUCT_NAMED<a id="a0bcdd46f107a31184119f65702c0889fae555ee137b8e9d6141129526147e5ac5"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_FUNCTION<a id="a0bcdd46f107a31184119f65702c0889fa99918475e83e7f55791cd5d5b7a60656"></a></td>
<td class="doxyEnumItemDescription"> (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_TOKEN<a id="a0bcdd46f107a31184119f65702c0889faa9a6282554cfa4b3da8149e1f8443771"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_BFLOAT<a id="a0bcdd46f107a31184119f65702c0889fa115c6b8fad2a7474f41db179dcc8f5c8"></a></td>
<td class="doxyEnumItemDescription"> (= 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_X86_AMX<a id="a0bcdd46f107a31184119f65702c0889fab9d457b1241f80024214ae224311feab"></a></td>
<td class="doxyEnumItemDescription"> (= 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_OPAQUE_POINTER<a id="a0bcdd46f107a31184119f65702c0889fa83e0719ed3f4e181136e109089fb6957"></a></td>
<td class="doxyEnumItemDescription"> (= 25)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_CODE_TARGET_TYPE<a id="a0bcdd46f107a31184119f65702c0889fa53cdafb9cc6755a7938dc5ca00e69f4c"></a></td>
<td class="doxyEnumItemDescription"> (= 26)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### UnaryOpcodes {#a635e5fcb068bb33406c8f4478fec92ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::UnaryOpcodes </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a635e5fcb068bb33406c8f4478fec92ac">UnaryOpcodes</a> - These are values used in the bitcode files to encode which unop a CST_CODE_CE_UNOP or a XXX refers to.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNOP_FNEG<a id="a635e5fcb068bb33406c8f4478fec92acaff0bbded1d2517cb24d7d941a40cfd31"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

</table>
</dd>
</dl>


<p>The values of these enums have no fixed relation to the LLVM IR enum values. Changing these will break compatibility with old files.</p>


<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### UseListCodes {#a77f340cd374889c5a53b3ab26f47ef95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::UseListCodes </td>
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
<td class="doxyEnumItemName">USELIST_CODE_DEFAULT<a id="a77f340cd374889c5a53b3ab26f47ef95aa6f510bdef07b7872c929674b3f7b011"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">USELIST_CODE_BB<a id="a77f340cd374889c5a53b3ab26f47ef95a028a27c988ff91790cb09a4cb6969ca2"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

### ValueSymtabCodes {#a3f554d1f2e074bb07a48d1ae4ecf979c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::bitc::ValueSymtabCodes </td>
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
<td class="doxyEnumItemName">VST_CODE_ENTRY<a id="a3f554d1f2e074bb07a48d1ae4ecf979ca6890a6e9486c9bdd0b63f2ed04adf486"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST_CODE_BBENTRY<a id="a3f554d1f2e074bb07a48d1ae4ecf979ca5e227ec096af4bbcd07ebe800633c7f8"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST_CODE_FNENTRY<a id="a3f554d1f2e074bb07a48d1ae4ecf979ca899931d8628dd9e69584296ea0486aab"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST_CODE_COMBINED_ENTRY<a id="a3f554d1f2e074bb07a48d1ae4ecf979caf276160eb6828b3da4e335a84d10cdcf"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">LLVMBitCodes.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitcodeenums-h">BitCodeEnums.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
