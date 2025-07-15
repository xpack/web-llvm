---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LowerTypeTestsModule` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41245c88cdf19ddbfe8a2dffba0a500d">LowerTypeTestsModule</a> (Module &amp;M, ModuleAnalysisManager &amp;AM, ModuleSummaryIndex *ExportSummary, const ModuleSummaryIndex *ImportSummary, DropTestKind DropTypeTests)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower all type tests in this module. <a href="#a41245c88cdf19ddbfe8a2dffba0a500d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c206887f3f0887f2c6ac58910c09c41">lower</a> ()</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a624f16ec9a3e60fc7fb15571ae0b076e">shouldExportConstantsAsAbsoluteSymbols</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1de20375a8b144f6575927a84de8a797">exportTypeId</a> (StringRef TypeId, const TypeIdLowering &amp;TIL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Export the given type identifier so that ThinLTO backends may import it. <a href="#a1de20375a8b144f6575927a84de8a797">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">TypeIdLowering</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65461b6bab8b4fff734cd4235b381d0b">importTypeId</a> (StringRef TypeId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e3ff751d7678ed59f9f5acca59deff3">importTypeTest</a> (CallInst *CI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6478298c1f13d2b70830f2a53df82cd9">importFunction</a> (Function *F, bool isJumpTableCanonical, std::vector&lt; GlobalAlias * &gt; &amp;AliasesToErase)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lowertypetests/bitsetinfo">BitSetInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a221dda8ab4a0bb084a701257a07428c7">buildBitSet</a> (Metadata *TypeId, const DenseMap&lt; GlobalTypeMember *, uint64_t &gt; &amp;GlobalLayout)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a bit set for TypeId using the object layouts in GlobalLayout. <a href="#a221dda8ab4a0bb084a701257a07428c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-lowertypetests-cpp-/bytearrayinfo">ByteArrayInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e6b194b0dac3ea1ff1ea51716d9ed6a">createByteArray</a> (BitSetInfo &amp;BSI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22fdda5c9c80aad8223539f7f0d5062a">allocateByteArrays</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96d852aa0330460be287d711a802c192">createBitSetTest</a> (IRBuilder&lt;&gt; &amp;B, const TypeIdLowering &amp;TIL, Value *BitOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a test that bit BitOffset is set in the type identifier that was lowered to TIL, which must be either an Inline or a ByteArray. <a href="#a96d852aa0330460be287d711a802c192">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf363e473e0f8f93eb380007c5f3ab11">lowerTypeTestCalls</a> (ArrayRef&lt; Metadata * &gt; TypeIds, Constant *CombinedGlobalAddr, const DenseMap&lt; GlobalTypeMember *, uint64_t &gt; &amp;GlobalLayout)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a365ae5a92dab048d15851e11a76196c3">lowerTypeTestCall</a> (Metadata *TypeId, CallInst *CI, const TypeIdLowering &amp;TIL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower a llvm.type.test call to its implementation. <a href="#a365ae5a92dab048d15851e11a76196c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17691199c7cdd4ccbf0248fa92531d67">buildBitSetsFromGlobalVariables</a> (ArrayRef&lt; Metadata * &gt; TypeIds, ArrayRef&lt; GlobalTypeMember * &gt; Globals)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a disjoint set of type identifiers and globals, lay out the globals, build the bit sets and lower the llvm.type.test calls. <a href="#a17691199c7cdd4ccbf0248fa92531d67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154">Triple::ArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad270ec8a52eea297248e45fcdb713e00">selectJumpTableArmEncoding</a> (ArrayRef&lt; GlobalTypeMember * &gt; Functions)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2b826b640d4a5b558193fd5076f231d">hasBranchTargetEnforcement</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a714a1341783d6cde03fd8ddd89a0d246">getJumpTableEntrySize</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad800ac9e601328a17ffbc5a8e606542e">getJumpTableEntryType</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28dd5783c6807ab61f9efe69a8509745">createJumpTableEntry</a> (raw_ostream &amp;AsmOS, raw_ostream &amp;ConstraintOS, Triple::ArchType JumpTableArch, SmallVectorImpl&lt; Value * &gt; &amp;AsmArgs, Function *Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c8199b4908da567065bb3382820b7e7">verifyTypeMDNode</a> (GlobalObject *GO, MDNode *Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e2c347426e422c469ee0cb010edeb0">buildBitSetsFromFunctions</a> (ArrayRef&lt; Metadata * &gt; TypeIds, ArrayRef&lt; GlobalTypeMember * &gt; Functions)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a disjoint set of type identifiers and functions, build the bit sets and lower the llvm.type.test calls, architecture dependently. <a href="#a92e2c347426e422c469ee0cb010edeb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8549418fa0a783eb1f0fca4a8771cc8">buildBitSetsFromFunctionsNative</a> (ArrayRef&lt; Metadata * &gt; TypeIds, ArrayRef&lt; GlobalTypeMember * &gt; Functions)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a disjoint set of type identifiers and functions, build a jump table for the functions, build the bit sets and lower the llvm.type.test calls. <a href="#ab8549418fa0a783eb1f0fca4a8771cc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99d2617756f5892c363ed2af3e616560">buildBitSetsFromFunctionsWASM</a> (ArrayRef&lt; Metadata * &gt; TypeIds, ArrayRef&lt; GlobalTypeMember * &gt; Functions)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign a dummy layout using an incrementing counter, tag each function with its index represented as metadata, and lower each type test to an integer range comparison. <a href="#a99d2617756f5892c363ed2af3e616560">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08ad046e76851fc124c6ac07c419849f">buildBitSetsFromDisjointSet</a> (ArrayRef&lt; Metadata * &gt; TypeIds, ArrayRef&lt; GlobalTypeMember * &gt; Globals, ArrayRef&lt; ICallBranchFunnel * &gt; ICallBranchFunnels)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f2e98c910db3c49e8c9b35369597cbe">replaceWeakDeclarationWithJumpTablePtr</a> (Function *F, Constant *JT, bool IsJumpTableCanonical)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac188b4e969634b038b06ddc017a84a3f">moveInitializerToModuleConstructor</a> (GlobalVariable *GV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2bbf858b0779d51c8a6518c77c37d69">findGlobalVariableUsersOf</a> (Constant *C, SmallSetVector&lt; GlobalVariable *, 8 &gt; &amp;Out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaeaca0d27e6723c4ed90620c6d47c56">createJumpTable</a> (Function *F, ArrayRef&lt; GlobalTypeMember * &gt; Functions)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ad2c240bfbf9ffb2ea67902f3b49260">replaceCfiUses</a> (Function *Old, Value *New, bool IsJumpTableCanonical)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>replaceCfiUses - Go through the uses list for this definition and make each use point to "V" instead of "this" when the use is outside the block. <a href="#a8ad2c240bfbf9ffb2ea67902f3b49260">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b2b49dc024d7287d3b987178f294ec1">replaceDirectCalls</a> (Value *Old, Value *New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>replaceDirectCalls - Go through the uses list for this definition and replace each use, which is a direct function call. <a href="#a2b2b49dc024d7287d3b987178f294ec1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a607c72673949a1623b0474c02940bfa0">isFunctionAnnotation</a> (Value *V) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad14721f622d19e2d964df7ec6a8a282a">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a598456848bde937abc9a5cdb206cae60">ExportSummary</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafdac9d332655f457997fc210c965528">ImportSummary</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lowertypetests/#a28baf2df0f23eab12b60755416e83ada">DropTestKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf4a90d97532aa8f00d29a39c6e4a5da">DropTypeTests</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154">Triple::ArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeebc9897ba59126e64a6b9c2ab927e56">Arch</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cd">Triple::OSType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a69eb5e40c0d5e3fe712c81bd2c7b65">OS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201">Triple::ObjectFormatType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c842abb6fd87693c9fdefc90213b0e7">ObjectFormat</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20b35d990964f7e557a29a8f11adff16">CanUseArmJumpTable</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bf41b435d381dc0046c93250be38d4b">CanUseThumbBWJumpTable</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2004b5e8af3151913e78688407080b7">HasBranchTargetEnforcement</a> = -1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154">Triple::ArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62050974d264c832320de36b23491325">JumpTableArch</a> = Triple::UnknownArch</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea28ba6edce52f7af0c98bf2121e4a93">Int1Ty</a> = Type::getInt1Ty(M.getContext())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fe54d4940e3fe982765580c4e293ec0">Int8Ty</a> = Type::getInt8Ty(M.getContext())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9538bde2c64e9f0a309a547c813d2e76">Int8PtrTy</a> = PointerType::getUnqual(M.getContext())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arraytype">ArrayType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd4c8f35e086003fc934b87d81fb800b">Int8Arr0Ty</a> = ArrayType::get(Type::getInt8Ty(M.getContext()), 0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7876d811fcc983dd36170d15b5fb2523">Int32Ty</a> = Type::getInt32Ty(M.getContext())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2246bee82a0242ae43cead0f15d286f3">Int32PtrTy</a> = PointerType::getUnqual(M.getContext())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace43619a6eb3255e3ac3afb22ee1b15a">Int64Ty</a> = Type::getInt64Ty(M.getContext())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00b6e30397804dd372b5ae5e627d56ab">IntPtrTy</a> = M.getDataLayout().getIntPtrType(M.getContext(), 0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5755ede96b98dfe8431da9edaeb5e57">IndirectIndex</a> = 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *, TypeIdUserInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6412b5f6bc2cb0664e9d3871ceaf2841">TypeIdUsers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-lowertypetests-cpp-/bytearrayinfo">ByteArrayInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa1bcd2522a52bd015a6864c21a8956f">ByteArrayInfos</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb722413d5c17a796db06f3f2036c429">WeakInitializerFn</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52ce1e1d921897f0bb4bbc19727f5543">GlobalAnnotation</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a813af3a43b691ecbdb820d57945883c4">FunctionAnnotations</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fee796681f58a9d96414dcaac5bb642">runForTesting</a> (Module &amp;M, ModuleAnalysisManager &amp;AM)</td>
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


<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LowerTypeTestsModule() {#a41245c88cdf19ddbfe8a2dffba0a500d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LowerTypeTestsModule::LowerTypeTestsModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * ExportSummary, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * ImportSummary, <a href="/web-llvm/docs/api/namespaces/llvm/lowertypetests/#a28baf2df0f23eab12b60755416e83ada">DropTestKind</a> DropTypeTests)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower all type tests in this module.</p>

<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">llvm::Triple::arm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#adbfaa049c7170233bc56b3d6cd9e5702">ClDropTypeTests</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5fc23559f17bbe5ff83ec0fed0a5fdcf">llvm::Triple::getArch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a2e265a0d332c3e2db0acf0c7afd4175d">llvm::Triple::getObjectFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5a777de4cd152c5b22b9d28439326d50">llvm::Triple::getOS</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#aaab1fad63e4f3b8679469720a873fedd">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getResult</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a0b931781aa589c6ebe64a76c1447e5b2">llvm::User::operands</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">llvm::Triple::thumb</a>.</p>


<p>Referenced by <a href="#a2fee796681f58a9d96414dcaac5bb642">runForTesting</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### lower() {#a7c206887f3f0887f2c6ac58910c09c41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LowerTypeTestsModule::lower ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lowertypetests/#a28baf2df0f23eab12b60755416e83adaab1c94ca2fbc3e78fc30069c8d0f01680">llvm::lowertypetests::All</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#adde2ea00dd2613ee41bfe91908e4e68e">llvm::CallBase::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8f67fbc50a05486efacc898909c8fa6a3fedbac88865b0c78cef42848ade7db1">llvm::CFL_Definition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8f67fbc50a05486efacc898909c8fa6a2c774a7021d843a45dccfa54a21fa83b">llvm::CFL_WeakDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a041e60c6f5f9841f3dc74921ea87bec2">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/globaltypemember/#a7d998bbf42b3e7b41db5f23ca7b37ba2">anonymous{LowerTypeTests.cpp}::GlobalTypeMember::create</a>, <a href="/web-llvm/docs/api/structs/anonymous-lowertypetests-cpp-/icallbranchfunnel/#acb948e4663bb2cccc693ebccc240113a">anonymous{LowerTypeTests.cpp}::ICallBranchFunnel::create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a8a638534b520f72ab7f2c886da739a6c">llvm::GlobalAlias::create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3e999e4bb7297d284f931638721840e5">llvm::GlobalValue::dropLLVMManglingEscape</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#a52f9ebe90c5295cbd67350376bd57eb3">dropTypeTests</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a09b07d472515f1d307c0e8229f6856fb">llvm::GlobalAlias::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a9d88e21e9caa53945e903fd8c8700b4f">llvm::GlobalObject::eraseMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa81fc8db28ac4af45766fbab2e79d466">llvm::GlobalValue::ExternalWeakLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdoperand/#ac5d52549f5e52702a331fbc4bd7eb512">llvm::MDOperand::get</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aa1731508126b77035ab3ba9d71d5374b">llvm::Intrinsic::getDeclarationIfExists</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a71ee7e63264e4997a3340a781d44832e">llvm::GlobalValue::getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#aef569d822dbf572ae71954d6831ce8a9">llvm::GlobalObject::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3ac5d9eb48038aa973017317279eadf5">llvm::GetPointerBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#abb6ea6cbdf19ab64bf0c8f65b2e6e8ce">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6b66f492cbea5f4b4f434d7178477116">llvm::GlobalValue::isDeclarationForLinker</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lowertypetests/#ab6535371eaec8620c84bbb0689535dbb">llvm::lowertypetests::isJumpTableCanonical</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a308b65a044b4f53e31a2026a81c991d2">llvm::GlobalValue::isLocalLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a58328e0582aabaf012bf9bc6f36c9e04">llvm::M1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lowertypetests/#a28baf2df0f23eab12b60755416e83adaa6adf97f83acf6453d4a6a4b1070f3754">llvm::lowertypetests::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#adc55e223d70c06a924fd5cb248052d9d">llvm::NamedMDNode::operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a687973de03d041e04b50a76d19d4fd36">llvm::GlobalValue::setLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa242d8ab89216c14beab812e07009b2a">llvm::GlobalValue::setVisibility</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ae855357b6c5e6e7ed1869272708a3a84">llvm::Value::takeName</a>, <a href="/web-llvm/docs/api/structs/anonymous-lowertypetests-cpp-/icallbranchfunnel/#a28a681b85ff61a1b164a453f3705d73b">anonymous{LowerTypeTests.cpp}::ICallBranchFunnel::UniqueId</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">llvm::GlobalValue::WeakAnyLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### allocateByteArrays() {#a22fdda5c9c80aad8223539f7f0d5062a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerTypeTestsModule::allocateByteArrays ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### buildBitSet() {#a221dda8ab4a0bb084a701257a07428c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitSetInfo LowerTypeTestsModule::buildBitSet (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * TypeId, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/globaltypemember">GlobalTypeMember</a> *, uint64_t &gt; &amp; GlobalLayout)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build a bit set for TypeId using the object layouts in GlobalLayout.</p>

<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### buildBitSetsFromDisjointSet() {#a08ad046e76851fc124c6ac07c419849f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerTypeTestsModule::buildBitSetsFromDisjointSet (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; TypeIds, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/globaltypemember">GlobalTypeMember</a> * &gt; Globals, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-lowertypetests-cpp-/icallbranchfunnel">ICallBranchFunnel</a> * &gt; ICallBranchFunnels)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### buildBitSetsFromFunctions() {#a92e2c347426e422c469ee0cb010edeb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerTypeTestsModule::buildBitSetsFromFunctions (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; TypeIds, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/globaltypemember">GlobalTypeMember</a> * &gt; Functions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a disjoint set of type identifiers and functions, build the bit sets and lower the llvm.type.test calls, architecture dependently.</p>

<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### buildBitSetsFromFunctionsNative() {#ab8549418fa0a783eb1f0fca4a8771cc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerTypeTestsModule::buildBitSetsFromFunctionsNative (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; TypeIds, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/globaltypemember">GlobalTypeMember</a> * &gt; Functions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a disjoint set of type identifiers and functions, build a jump table for the functions, build the bit sets and lower the llvm.type.test calls.</p>

<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### buildBitSetsFromFunctionsWASM() {#a99d2617756f5892c363ed2af3e616560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerTypeTestsModule::buildBitSetsFromFunctionsWASM (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; TypeIds, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/globaltypemember">GlobalTypeMember</a> * &gt; Functions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assign a dummy layout using an incrementing counter, tag each function with its index represented as metadata, and lower each type test to an integer range comparison.</p>


<p>During generation of the indirect function call table in the backend, it will assign the given indexes. Note: Dynamic linking is not supported, as the <a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> ABI has not yet been finalized.</p>


<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### buildBitSetsFromGlobalVariables() {#a17691199c7cdd4ccbf0248fa92531d67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerTypeTestsModule::buildBitSetsFromGlobalVariables (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; TypeIds, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/globaltypemember">GlobalTypeMember</a> * &gt; Globals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a disjoint set of type identifiers and globals, lay out the globals, build the bit sets and lower the llvm.type.test calls.</p>

<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### createBitSetTest() {#a96d852aa0330460be287d711a802c192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * LowerTypeTestsModule::createBitSetTest (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TypeIdLowering &amp; TIL, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * BitOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build a test that bit BitOffset is set in the type identifier that was lowered to TIL, which must be either an Inline or a ByteArray.</p>

<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### createByteArray() {#a0e6b194b0dac3ea1ff1ea51716d9ed6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ByteArrayInfo * LowerTypeTestsModule::createByteArray (<a href="/web-llvm/docs/api/structs/llvm/lowertypetests/bitsetinfo">BitSetInfo</a> &amp; BSI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### createJumpTable() {#acaeaca0d27e6723c4ed90620c6d47c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerTypeTestsModule::createJumpTable (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/globaltypemember">GlobalTypeMember</a> * &gt; Functions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### createJumpTableEntry() {#a28dd5783c6807ab61f9efe69a8509745}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerTypeTestsModule::createJumpTableEntry (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; AsmOS, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; ConstraintOS, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154">Triple::ArchType</a> JumpTableArch, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; AsmArgs, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### exportTypeId() {#a1de20375a8b144f6575927a84de8a797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t * LowerTypeTestsModule::exportTypeId (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TypeId, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TypeIdLowering &amp; TIL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Export the given type identifier so that ThinLTO backends may import it.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> identifiers are exported by adding coarse-grained information about how to test the type identifier to the summary, and creating symbols in the object file (aliases and absolute symbols) containing fine-grained information about the type identifier.</p>


<p>Returns a pointer to the location in which to store the bitmask, if applicable.</p>


<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### findGlobalVariableUsersOf() {#ad2bbf858b0779d51c8a6518c77c37d69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerTypeTestsModule::findGlobalVariableUsersOf (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *, 8 &gt; &amp; Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### getJumpTableEntrySize() {#a714a1341783d6cde03fd8ddd89a0d246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LowerTypeTestsModule::getJumpTableEntrySize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### getJumpTableEntryType() {#ad800ac9e601328a17ffbc5a8e606542e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * LowerTypeTestsModule::getJumpTableEntryType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### hasBranchTargetEnforcement() {#af2b826b640d4a5b558193fd5076f231d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LowerTypeTestsModule::hasBranchTargetEnforcement ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### importFunction() {#a6478298c1f13d2b70830f2a53df82cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerTypeTestsModule::importFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, bool isJumpTableCanonical, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> * &gt; &amp; AliasesToErase)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### importTypeId() {#a65461b6bab8b4fff734cd4235b381d0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LowerTypeTestsModule::TypeIdLowering LowerTypeTestsModule::importTypeId (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TypeId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### importTypeTest() {#a1e3ff751d7678ed59f9f5acca59deff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerTypeTestsModule::importTypeTest (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### isFunctionAnnotation() {#a607c72673949a1623b0474c02940bfa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::isFunctionAnnotation (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### lowerTypeTestCall() {#a365ae5a92dab048d15851e11a76196c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * LowerTypeTestsModule::lowerTypeTestCall (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * TypeId, <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TypeIdLowering &amp; TIL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower a llvm.type.test call to its implementation.</p>


<p>Returns the value to replace the call with.</p>


<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### lowerTypeTestCalls() {#acf363e473e0f8f93eb380007c5f3ab11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerTypeTestsModule::lowerTypeTestCalls (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; TypeIds, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * CombinedGlobalAddr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/globaltypemember">GlobalTypeMember</a> *, uint64_t &gt; &amp; GlobalLayout)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### moveInitializerToModuleConstructor() {#ac188b4e969634b038b06ddc017a84a3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerTypeTestsModule::moveInitializerToModuleConstructor (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### replaceCfiUses() {#a8ad2c240bfbf9ffb2ea67902f3b49260}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerTypeTestsModule::replaceCfiUses (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * New, bool IsJumpTableCanonical)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>replaceCfiUses - Go through the uses list for this definition and make each use point to "V" instead of "this" when the use is outside the block.</p>


<p>'This's use list is expected to have at least one element. Unlike replaceAllUsesWith this function skips blockaddr and direct call uses.</p>


<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### replaceDirectCalls() {#a2b2b49dc024d7287d3b987178f294ec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerTypeTestsModule::replaceDirectCalls (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * New)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>replaceDirectCalls - Go through the uses list for this definition and replace each use, which is a direct function call.</p>

<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### replaceWeakDeclarationWithJumpTablePtr() {#a6f2e98c910db3c49e8c9b35369597cbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerTypeTestsModule::replaceWeakDeclarationWithJumpTablePtr (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * JT, bool IsJumpTableCanonical)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### selectJumpTableArmEncoding() {#ad270ec8a52eea297248e45fcdb713e00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ArchType LowerTypeTestsModule::selectJumpTableArmEncoding (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/globaltypemember">GlobalTypeMember</a> * &gt; Functions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### shouldExportConstantsAsAbsoluteSymbols() {#a624f16ec9a3e60fc7fb15571ae0b076e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LowerTypeTestsModule::shouldExportConstantsAsAbsoluteSymbols ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### verifyTypeMDNode() {#a1c8199b4908da567065bb3382820b7e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerTypeTestsModule::verifyTypeMDNode (<a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Arch {#aeebc9897ba59126e64a6b9c2ab927e56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ArchType anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::Arch</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### ByteArrayInfos {#afa1bcd2522a52bd015a6864c21a8956f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ByteArrayInfo&gt; anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::ByteArrayInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### CanUseArmJumpTable {#a20b35d990964f7e557a29a8f11adff16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::CanUseArmJumpTable = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### CanUseThumbBWJumpTable {#a9bf41b435d381dc0046c93250be38d4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::CanUseThumbBWJumpTable = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### DropTypeTests {#abf4a90d97532aa8f00d29a39c6e4a5da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DropTestKind anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::DropTypeTests</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### ExportSummary {#a598456848bde937abc9a5cdb206cae60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleSummaryIndex* anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::ExportSummary</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### FunctionAnnotations {#a813af3a43b691ecbdb820d57945883c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;Value *&gt; anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::FunctionAnnotations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### GlobalAnnotation {#a52ce1e1d921897f0bb4bbc19727f5543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable* anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::GlobalAnnotation</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### HasBranchTargetEnforcement {#ab2004b5e8af3151913e78688407080b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::HasBranchTargetEnforcement = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### ImportSummary {#aafdac9d332655f457997fc210c965528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ModuleSummaryIndex* anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::ImportSummary</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### IndirectIndex {#ae5755ede96b98dfe8431da9edaeb5e57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::IndirectIndex = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### Int1Ty {#aea28ba6edce52f7af0c98bf2121e4a93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType* anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::Int1Ty = Type::getInt1Ty(M.getContext())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### Int32PtrTy {#a2246bee82a0242ae43cead0f15d286f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType* anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::Int32PtrTy = PointerType::getUnqual(M.getContext())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### Int32Ty {#a7876d811fcc983dd36170d15b5fb2523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType* anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::Int32Ty = Type::getInt32Ty(M.getContext())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### Int64Ty {#ace43619a6eb3255e3ac3afb22ee1b15a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType* anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::Int64Ty = Type::getInt64Ty(M.getContext())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### Int8Arr0Ty {#afd4c8f35e086003fc934b87d81fb800b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayType* anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::Int8Arr0Ty = ArrayType::get(Type::getInt8Ty(M.getContext()), 0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### Int8PtrTy {#a9538bde2c64e9f0a309a547c813d2e76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType* anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::Int8PtrTy = PointerType::getUnqual(M.getContext())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### Int8Ty {#a2fe54d4940e3fe982765580c4e293ec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType* anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::Int8Ty = Type::getInt8Ty(M.getContext())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### IntPtrTy {#a00b6e30397804dd372b5ae5e627d56ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType* anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::IntPtrTy = M.getDataLayout().getIntPtrType(M.getContext(), 0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### JumpTableArch {#a62050974d264c832320de36b23491325}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ArchType anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::JumpTableArch = Triple::UnknownArch</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### M {#ad14721f622d19e2d964df7ec6a8a282a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module&amp; anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### ObjectFormat {#a6c842abb6fd87693c9fdefc90213b0e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ObjectFormatType anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::ObjectFormat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### OS {#a3a69eb5e40c0d5e3fe712c81bd2c7b65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::OSType anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### TypeIdUsers {#a6412b5f6bc2cb0664e9d3871ceaf2841}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Metadata *, TypeIdUserInfo&gt; anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::TypeIdUsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### WeakInitializerFn {#adb722413d5c17a796db06f3f2036c429}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::WeakInitializerFn = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### runForTesting() {#a2fee796681f58a9d96414dcaac5bb642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LowerTypeTestsModule::runForTesting (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; AM)</td>
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



<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#a4231130e271f81a2e2b33f55e6233dae">ClReadSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#a9020e4076f17c245550360c81bb4702e">ClSummaryAction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#ac7f3d084756d2a946dcd9c1ecd50daab">ClWriteSummary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab97c9dc8dec5b044b551639baf324053">llvm::errorOrToExpected</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38a0bdae7fb49d99f161aa6de0379d7ea0095a9fa74d1713e43e370a7d7846224">llvm::Export</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38a0bdae7fb49d99f161aa6de0379d7ea72d6d7a1885885bb55a565fd1070581a">llvm::Import</a>, <a href="#a41245c88cdf19ddbfe8a2dffba0a500d">LowerTypeTestsModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lowertypetests/#a28baf2df0f23eab12b60755416e83adaa6adf97f83acf6453d4a6a4b1070f3754">llvm::lowertypetests::None</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695ab505c2c79499fbe180989bffbf108a50">llvm::sys::fs::OF_TextWithCRLF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lowertypetestspass/#af14b972caecee35ee8e3a66b85ea3842">llvm::LowerTypeTestsPass::run</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
