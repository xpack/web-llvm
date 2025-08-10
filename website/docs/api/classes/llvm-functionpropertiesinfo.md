---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/functionpropertiesinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FunctionPropertiesInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::FunctionPropertiesInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">llvm/Analysis/FunctionPropertiesAnalysis.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a886864b4db05ccf27a372a475521511a">FunctionPropertiesUpdater</a></td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cb372b19419778250762c60ff7ffe9a">operator==</a> (const FunctionPropertiesInfo &amp;FPI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1afbdf7e5e533d1eae71d8e1ed98b2a5">operator!=</a> (const FunctionPropertiesInfo &amp;FPI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a2c669ab53b8f4a51eb2c9d744cae0d">updateForBB</a> (const BasicBlock &amp;BB, int64_t Direction)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66da9a4eae78f9c1b58b11f34d8a8e34">updateAggregateStats</a> (const Function &amp;F, const LoopInfo &amp;LI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac1ed2fcefdf96840b13ab32a5892bc0">reIncludeBB</a> (const BasicBlock &amp;BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b7e1c18db3d25b69a62d65a0cba8534">BasicBlockCount</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of basic blocks. <a href="#a2b7e1c18db3d25b69a62d65a0cba8534">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a663748cdd1091a504e2dde978d147892">BlocksReachedFromConditionalInstruction</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of blocks reached from a conditional instruction, or that are 'cases' of a SwitchInstr. <a href="#a663748cdd1091a504e2dde978d147892">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ca2637b684b923ec6836f54a464dadd">Uses</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of uses of this function, plus 1 if the function is callable outside the module. <a href="#a2ca2637b684b923ec6836f54a464dadd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa568a5b2ab440f02bbc9eef3863a619">DirectCallsToDefinedFunctions</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of direct calls made from this function to other functions defined in this module. <a href="#afa568a5b2ab440f02bbc9eef3863a619">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a490e2c5ef224a61db5d5819703163670">LoadInstCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2770ff2459fe32e31fda286e27a33fbb">StoreInstCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9af69ccb450a5f5cd164f6176e24f7e6">MaxLoopDepth</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a534d23cdf9db6e5b7d49e36d61f23726">TopLevelLoopCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0ec2659390ab61b126f336e2727d0c7">TotalInstructionCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c77f25ebf21adb8f65d8e61579d64d2">BasicBlocksWithSingleSuccessor</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dc9ab6610aba119c67518b47582203b">BasicBlocksWithTwoSuccessors</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00f3b57cfbec2df727b1fff9d35f7ebb">BasicBlocksWithMoreThanTwoSuccessors</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02c8dc4158b8028a250c19e6f47a1c88">BasicBlocksWithSinglePredecessor</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbaaedd51d50e8e5d4f12936b6092afe">BasicBlocksWithTwoPredecessors</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae60674a99c5124a11da30ee89fefe0a6">BasicBlocksWithMoreThanTwoPredecessors</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30fb3d6c9e3d445628128a9331202a31">BigBasicBlocks</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3e2ec6e66b73ef9ed8cede604d3cb2c">MediumBasicBlocks</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2c17872c13c258a49267ed0d5175fb0">SmallBasicBlocks</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25c01b3edcb7847ce4a513fc983c0ca5">CastInstructionCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5054257d37951c5fb9c0b2c39c28492e">FloatingPointInstructionCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf6ba82d34a98be344d086912685c37f">IntegerInstructionCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed88a5e62e7ddbb06e413f889139f199">ConstantIntOperandCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ced99726c7114e40ce280476f1a5693">ConstantFPOperandCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7bed2afee172dd9df892cdd341be315">ConstantOperandCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b4514ef1c282109ceb4680713418db6">InstructionOperandCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa51c47c6bee2b5506e777b14f81795ab">BasicBlockOperandCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7099d10bb88ea5057bdf7aee07969d36">GlobalValueOperandCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cd475cd379bdd1e88b95867bbef22f7">InlineAsmOperandCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76c7b4a909412fd403d587b007dc63c0">ArgumentOperandCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9d5817f647dba946a0e9cf4bd31f7c2">UnknownOperandCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c82c8f1af81057852ebaf083f2a3a53">CriticalEdgeCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaa1754a10405904f78fda855d32b69a">ControlFlowEdgeCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72a5702c34b439dd98e27dbc18b5c019">UnconditionalBranchCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a730f855eea60b41c111149b27f5376dc">IntrinsicCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3077f49bbefa2efcd290d03023ad86a1">DirectCallCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afce1f373db719882044f60202313703d">IndirectCallCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5850e660458a9aec3920c617c6b7234c">CallReturnsIntegerCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb357c2abd551aa75c94660fc777e52f">CallReturnsFloatCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0be1fc7b5d68e3460772dac1ad8d55d5">CallReturnsPointerCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ef9b29638eb97ee82c642883746c6d0">CallReturnsVectorIntCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13aee3dd64d41d828167a140676ca053">CallReturnsVectorFloatCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04e9de2f2d5cd46d398f4f56391e5207">CallReturnsVectorPointerCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c1dd06b48c444920aca34346e4a475b">CallWithManyArgumentsCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fb5d40fd1f64e6059d6494a5948cdc9">CallWithPointerArgumentCount</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo">FunctionPropertiesInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68ed7ba6b7bd3212a48c4fb730e1bc4e">getFunctionPropertiesInfo</a> (const Function &amp;F, const DominatorTree &amp;DT, const LoopInfo &amp;LI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo">FunctionPropertiesInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33b6380c72c488ab1713ff6b70cf2a66">getFunctionPropertiesInfo</a> (Function &amp;F, FunctionAnalysisManager &amp;FAM)</td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Friends

### FunctionPropertiesUpdater {#a886864b4db05ccf27a372a475521511a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesupdater">FunctionPropertiesUpdater</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a> and <a href="#a886864b4db05ccf27a372a475521511a">FunctionPropertiesUpdater</a>.</p>


<p>Referenced by <a href="#a886864b4db05ccf27a372a475521511a">FunctionPropertiesUpdater</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a1afbdf7e5e533d1eae71d8e1ed98b2a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FunctionPropertiesInfo::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo">FunctionPropertiesInfo</a> &amp; FPI)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>

</div>
</div>

### operator==() {#a3cb372b19419778250762c60ff7ffe9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FunctionPropertiesInfo::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo">FunctionPropertiesInfo</a> &amp; FPI)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### print() {#adede9cdc7aba484c6cdbd3f25bd03e24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionPropertiesInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>, definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/functionpropertiesanalysis-cpp">FunctionPropertiesAnalysis.cpp</a>.</p>


<p>References <a href="#a76c7b4a909412fd403d587b007dc63c0">ArgumentOperandCount</a>, <a href="#a2b7e1c18db3d25b69a62d65a0cba8534">BasicBlockCount</a>, <a href="#aa51c47c6bee2b5506e777b14f81795ab">BasicBlockOperandCount</a>, <a href="#ae60674a99c5124a11da30ee89fefe0a6">BasicBlocksWithMoreThanTwoPredecessors</a>, <a href="#a00f3b57cfbec2df727b1fff9d35f7ebb">BasicBlocksWithMoreThanTwoSuccessors</a>, <a href="#a02c8dc4158b8028a250c19e6f47a1c88">BasicBlocksWithSinglePredecessor</a>, <a href="#a8c77f25ebf21adb8f65d8e61579d64d2">BasicBlocksWithSingleSuccessor</a>, <a href="#abbaaedd51d50e8e5d4f12936b6092afe">BasicBlocksWithTwoPredecessors</a>, <a href="#a2dc9ab6610aba119c67518b47582203b">BasicBlocksWithTwoSuccessors</a>, <a href="#a30fb3d6c9e3d445628128a9331202a31">BigBasicBlocks</a>, <a href="#a663748cdd1091a504e2dde978d147892">BlocksReachedFromConditionalInstruction</a>, <a href="#adb357c2abd551aa75c94660fc777e52f">CallReturnsFloatCount</a>, <a href="#a5850e660458a9aec3920c617c6b7234c">CallReturnsIntegerCount</a>, <a href="#a0be1fc7b5d68e3460772dac1ad8d55d5">CallReturnsPointerCount</a>, <a href="#a13aee3dd64d41d828167a140676ca053">CallReturnsVectorFloatCount</a>, <a href="#a0ef9b29638eb97ee82c642883746c6d0">CallReturnsVectorIntCount</a>, <a href="#a04e9de2f2d5cd46d398f4f56391e5207">CallReturnsVectorPointerCount</a>, <a href="#a0c1dd06b48c444920aca34346e4a475b">CallWithManyArgumentsCount</a>, <a href="#a4fb5d40fd1f64e6059d6494a5948cdc9">CallWithPointerArgumentCount</a>, <a href="#a25c01b3edcb7847ce4a513fc983c0ca5">CastInstructionCount</a>, <a href="#a2ced99726c7114e40ce280476f1a5693">ConstantFPOperandCount</a>, <a href="#aed88a5e62e7ddbb06e413f889139f199">ConstantIntOperandCount</a>, <a href="#ae7bed2afee172dd9df892cdd341be315">ConstantOperandCount</a>, <a href="#aaaa1754a10405904f78fda855d32b69a">ControlFlowEdgeCount</a>, <a href="#a2c82c8f1af81057852ebaf083f2a3a53">CriticalEdgeCount</a>, <a href="#a3077f49bbefa2efcd290d03023ad86a1">DirectCallCount</a>, <a href="#afa568a5b2ab440f02bbc9eef3863a619">DirectCallsToDefinedFunctions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a33b44dc8fd22604268cf644a6a60e1d4">llvm::EnableDetailedFunctionProperties</a>, <a href="#a5054257d37951c5fb9c0b2c39c28492e">FloatingPointInstructionCount</a>, <a href="#a7099d10bb88ea5057bdf7aee07969d36">GlobalValueOperandCount</a>, <a href="#afce1f373db719882044f60202313703d">IndirectCallCount</a>, <a href="#a2cd475cd379bdd1e88b95867bbef22f7">InlineAsmOperandCount</a>, <a href="#a4b4514ef1c282109ceb4680713418db6">InstructionOperandCount</a>, <a href="#acf6ba82d34a98be344d086912685c37f">IntegerInstructionCount</a>, <a href="#a730f855eea60b41c111149b27f5376dc">IntrinsicCount</a>, <a href="#a490e2c5ef224a61db5d5819703163670">LoadInstCount</a>, <a href="#a9af69ccb450a5f5cd164f6176e24f7e6">MaxLoopDepth</a>, <a href="#ac3e2ec6e66b73ef9ed8cede604d3cb2c">MediumBasicBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/functionpropertiesanalysis-cpp/#a6393165576213aae83b511a24c80f665">PRINT_PROPERTY</a>, <a href="#ae2c17872c13c258a49267ed0d5175fb0">SmallBasicBlocks</a>, <a href="#a2770ff2459fe32e31fda286e27a33fbb">StoreInstCount</a>, <a href="#a534d23cdf9db6e5b7d49e36d61f23726">TopLevelLoopCount</a>, <a href="#ae0ec2659390ab61b126f336e2727d0c7">TotalInstructionCount</a>, <a href="#a72a5702c34b439dd98e27dbc18b5c019">UnconditionalBranchCount</a>, <a href="#af9d5817f647dba946a0e9cf4bd31f7c2">UnknownOperandCount</a> and <a href="#a2ca2637b684b923ec6836f54a464dadd">Uses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### reIncludeBB() {#aac1ed2fcefdf96840b13ab32a5892bc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionPropertiesInfo::reIncludeBB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/functionpropertiesanalysis-cpp">FunctionPropertiesAnalysis.cpp</a>.</p>

</div>
</div>

### updateAggregateStats() {#a66da9a4eae78f9c1b58b11f34d8a8e34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionPropertiesInfo::updateAggregateStats (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/functionpropertiesanalysis-cpp">FunctionPropertiesAnalysis.cpp</a>.</p>

</div>
</div>

### updateForBB() {#a0a2c669ab53b8f4a51eb2c9d744cae0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionPropertiesInfo::updateForBB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, int64_t Direction)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/functionpropertiesanalysis-cpp">FunctionPropertiesAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ArgumentOperandCount {#a76c7b4a909412fd403d587b007dc63c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::ArgumentOperandCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### BasicBlockCount {#a2b7e1c18db3d25b69a62d65a0cba8534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::BasicBlockCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of basic blocks.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### BasicBlockOperandCount {#aa51c47c6bee2b5506e777b14f81795ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::BasicBlockOperandCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### BasicBlocksWithMoreThanTwoPredecessors {#ae60674a99c5124a11da30ee89fefe0a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::BasicBlocksWithMoreThanTwoPredecessors = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### BasicBlocksWithMoreThanTwoSuccessors {#a00f3b57cfbec2df727b1fff9d35f7ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::BasicBlocksWithMoreThanTwoSuccessors = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### BasicBlocksWithSinglePredecessor {#a02c8dc4158b8028a250c19e6f47a1c88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::BasicBlocksWithSinglePredecessor = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### BasicBlocksWithSingleSuccessor {#a8c77f25ebf21adb8f65d8e61579d64d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::BasicBlocksWithSingleSuccessor = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### BasicBlocksWithTwoPredecessors {#abbaaedd51d50e8e5d4f12936b6092afe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::BasicBlocksWithTwoPredecessors = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### BasicBlocksWithTwoSuccessors {#a2dc9ab6610aba119c67518b47582203b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::BasicBlocksWithTwoSuccessors = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### BigBasicBlocks {#a30fb3d6c9e3d445628128a9331202a31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::BigBasicBlocks = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### BlocksReachedFromConditionalInstruction {#a663748cdd1091a504e2dde978d147892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::BlocksReachedFromConditionalInstruction = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of blocks reached from a conditional instruction, or that are 'cases' of a SwitchInstr.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### CallReturnsFloatCount {#adb357c2abd551aa75c94660fc777e52f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::CallReturnsFloatCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### CallReturnsIntegerCount {#a5850e660458a9aec3920c617c6b7234c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::CallReturnsIntegerCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### CallReturnsPointerCount {#a0be1fc7b5d68e3460772dac1ad8d55d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::CallReturnsPointerCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### CallReturnsVectorFloatCount {#a13aee3dd64d41d828167a140676ca053}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::CallReturnsVectorFloatCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### CallReturnsVectorIntCount {#a0ef9b29638eb97ee82c642883746c6d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::CallReturnsVectorIntCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### CallReturnsVectorPointerCount {#a04e9de2f2d5cd46d398f4f56391e5207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::CallReturnsVectorPointerCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### CallWithManyArgumentsCount {#a0c1dd06b48c444920aca34346e4a475b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::CallWithManyArgumentsCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### CallWithPointerArgumentCount {#a4fb5d40fd1f64e6059d6494a5948cdc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::CallWithPointerArgumentCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### CastInstructionCount {#a25c01b3edcb7847ce4a513fc983c0ca5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::CastInstructionCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### ConstantFPOperandCount {#a2ced99726c7114e40ce280476f1a5693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::ConstantFPOperandCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### ConstantIntOperandCount {#aed88a5e62e7ddbb06e413f889139f199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::ConstantIntOperandCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### ConstantOperandCount {#ae7bed2afee172dd9df892cdd341be315}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::ConstantOperandCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### ControlFlowEdgeCount {#aaaa1754a10405904f78fda855d32b69a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::ControlFlowEdgeCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### CriticalEdgeCount {#a2c82c8f1af81057852ebaf083f2a3a53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::CriticalEdgeCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### DirectCallCount {#a3077f49bbefa2efcd290d03023ad86a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::DirectCallCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### DirectCallsToDefinedFunctions {#afa568a5b2ab440f02bbc9eef3863a619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::DirectCallsToDefinedFunctions = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of direct calls made from this function to other functions defined in this module.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#abdcccbb9d3934f1685accebaf51f5aef">llvm::MLInlineAdvisor::getLocalCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#a8116ffdfb54f7d195eb185c8bf7c060c">llvm::MLInlineAdvisor::onSuccessfulInlining</a> and <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### FloatingPointInstructionCount {#a5054257d37951c5fb9c0b2c39c28492e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::FloatingPointInstructionCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### GlobalValueOperandCount {#a7099d10bb88ea5057bdf7aee07969d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::GlobalValueOperandCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### IndirectCallCount {#afce1f373db719882044f60202313703d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::IndirectCallCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### InlineAsmOperandCount {#a2cd475cd379bdd1e88b95867bbef22f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::InlineAsmOperandCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### InstructionOperandCount {#a4b4514ef1c282109ceb4680713418db6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::InstructionOperandCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### IntegerInstructionCount {#acf6ba82d34a98be344d086912685c37f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::IntegerInstructionCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### IntrinsicCount {#a730f855eea60b41c111149b27f5376dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::IntrinsicCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### LoadInstCount {#a490e2c5ef224a61db5d5819703163670}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::LoadInstCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### MaxLoopDepth {#a9af69ccb450a5f5cd164f6176e24f7e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::MaxLoopDepth = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### MediumBasicBlocks {#ac3e2ec6e66b73ef9ed8cede604d3cb2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::MediumBasicBlocks = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### SmallBasicBlocks {#ae2c17872c13c258a49267ed0d5175fb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::SmallBasicBlocks = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### StoreInstCount {#a2770ff2459fe32e31fda286e27a33fbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::StoreInstCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### TopLevelLoopCount {#a534d23cdf9db6e5b7d49e36d61f23726}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::TopLevelLoopCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### TotalInstructionCount {#ae0ec2659390ab61b126f336e2727d0c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::TotalInstructionCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#ad64807412969a3708f691675898a58c0">llvm::MLInlineAdvisor::getIRSize</a> and <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### UnconditionalBranchCount {#a72a5702c34b439dd98e27dbc18b5c019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::UnconditionalBranchCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### UnknownOperandCount {#af9d5817f647dba946a0e9cf4bd31f7c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::UnknownOperandCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

### Uses {#a2ca2637b684b923ec6836f54a464dadd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::FunctionPropertiesInfo::Uses = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of uses of this function, plus 1 if the function is callable outside the module.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>Referenced by <a href="#adede9cdc7aba484c6cdbd3f25bd03e24">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getFunctionPropertiesInfo() {#a68ed7ba6b7bd3212a48c4fb730e1bc4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPropertiesInfo FunctionPropertiesInfo::getFunctionPropertiesInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI)</td>
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



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>, definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/functionpropertiesanalysis-cpp">FunctionPropertiesAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a1a70f2c359aadd76a72aaaede16aca4a">llvm::DominatorTree::isReachableFromEntry</a>.</p>


<p>Referenced by <a href="#a33b6380c72c488ab1713ff6b70cf2a66">getFunctionPropertiesInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesanalysis/#a99dfe51a88eeff9511a30dbf83429642">llvm::FunctionPropertiesAnalysis::run</a>.</p>

</div>
</div>

### getFunctionPropertiesInfo() {#a33b6380c72c488ab1713ff6b70cf2a66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPropertiesInfo FunctionPropertiesInfo::getFunctionPropertiesInfo (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; FAM)</td>
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



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/functionpropertiesanalysis-cpp">FunctionPropertiesAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a> and <a href="#a68ed7ba6b7bd3212a48c4fb730e1bc4e">getFunctionPropertiesInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/functionpropertiesanalysis-cpp">FunctionPropertiesAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
