---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ssaupdater
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SSAUpdater` Class Reference

<p>Helper class for SSA formation on a set of values defined in multiple blocks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SSAUpdater { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">llvm/Transforms/Utils/SSAUpdater.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4d9ee7af6013309bc08eb7b3a95ea3b">SSAUpdaterTraits&lt; SSAUpdater &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8450e3821baaad374cd2e01184e07b9c">SSAUpdater</a> (SmallVectorImpl&lt; PHINode * &gt; *InsertedPHIs=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If InsertedPHIs is specified, it will be filled in with all PHI Nodes created by rewriting. <a href="#a8450e3821baaad374cd2e01184e07b9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab12d8b019d8a4561686fa1493476eb7f">SSAUpdater</a> (const SSAUpdater &amp;)=delete</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a1cb31475d8d5088cbe0e04e3b27a64">~SSAUpdater</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a372e48a7ebee2344db07fef48667604e">operator=</a> (const SSAUpdater &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fe3279aae4f726813a672d4a9b26cb1">Initialize</a> (Type *Ty, StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset this object to get ready for a new set of SSA updates with type 'Ty'. <a href="#a4fe3279aae4f726813a672d4a9b26cb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0d1a82b4e629e834c2ed53e5cbe22ef">AddAvailableValue</a> (BasicBlock *BB, Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate that a rewritten value is available in the specified block with the specified value. <a href="#af0d1a82b4e629e834c2ed53e5cbe22ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab671042c23924e0216c4a0b830ad2a04">HasValueForBlock</a> (BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> already has a value for the specified block. <a href="#ab671042c23924e0216c4a0b830ad2a04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24eaf55565ed385982d147ce3c354b40">FindValueForBlock</a> (BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value for the specified block if the <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> has one, otherwise return nullptr. <a href="#a24eaf55565ed385982d147ce3c354b40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acecfb9d97da9885264b3bde6bd6a64e8">GetValueAtEndOfBlock</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct SSA form, materializing a value that is live at the end of the specified block. <a href="#acecfb9d97da9885264b3bde6bd6a64e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b0e45dbba53e985f1b9c532fb5f200b">GetValueInMiddleOfBlock</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct SSA form, materializing a value that is live in the middle of the specified block. <a href="#a5b0e45dbba53e985f1b9c532fb5f200b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05c4f6837ee786e83246beeb01e3aa8d">RewriteUse</a> (Use &amp;U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite a use of the symbolic value. <a href="#a05c4f6837ee786e83246beeb01e3aa8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3e6b78bbdd6959f19055f44fa4b7021">UpdateDebugValues</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite debug value intrinsics to conform to a new SSA form. <a href="#aa3e6b78bbdd6959f19055f44fa4b7021">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73a042579083174d928dbb6634d72281">UpdateDebugValues</a> (Instruction *I, SmallVectorImpl&lt; DbgValueInst * &gt; &amp;DbgValues)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a446a2ccd27cfa4837a6d10c745c86592">UpdateDebugValues</a> (Instruction *I, SmallVectorImpl&lt; DbgVariableRecord * &gt; &amp;DbgValues)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a248544705875de8ef1c533827ec73a2e">RewriteUseAfterInsertions</a> (Use &amp;U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite a use like <span class="doxyComputerOutput">RewriteUse</span> but handling in-block definitions. <a href="#a248544705875de8ef1c533827ec73a2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67a394f855b0f4c1fa9bed70e30b98b2">GetValueAtEndOfBlockInternal</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> to see if AvailableVals has an entry for the specified BB and if so, return it. <a href="#a67a394f855b0f4c1fa9bed70e30b98b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07c7b0a444408fce9bd5edbe9eb5acf1">UpdateDebugValue</a> (Instruction *I, DbgValueInst *DbgValue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e1f53b0774c198e1b9b0c8ce7fed39b">UpdateDebugValue</a> (Instruction *I, DbgVariableRecord *DbgValue)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3441b2d33dae53d1ba3b1fb1140beb09">AV</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This keeps track of which value to use on a per-block basis. <a href="#a3441b2d33dae53d1ba3b1fb1140beb09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f6e7a2b978b9cd09bd809eb3e7aecd7">ProtoType</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ProtoType holds the type of the values being rewritten. <a href="#a2f6e7a2b978b9cd09bd809eb3e7aecd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e6bf477754392b94c0cbed9c9cfb350">ProtoName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PHI nodes are given a name based on ProtoName. <a href="#a2e6bf477754392b94c0cbed9c9cfb350">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f1f737229326f00844f518017cd0eea">InsertedPHIs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is non-null, the <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> adds all PHI nodes that it creates to the vector. <a href="#a9f1f737229326f00844f518017cd0eea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper class for SSA formation on a set of values defined in multiple blocks.</p>


<p>This is used when code duplication or another unstructured transformation wants to rewrite a set of uses of one value with uses of a set of values.</p>


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>.</p>


<div class="doxySectionDef">

## Friends

### SSAUpdaterTraits&lt; SSAUpdater &gt; {#ae4d9ee7af6013309bc08eb7b3a95ea3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits">SSAUpdaterTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SSAUpdater() {#a8450e3821baaad374cd2e01184e07b9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SSAUpdater::SSAUpdater (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * &gt; * InsertedPHIs=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If InsertedPHIs is specified, it will be filled in with all PHI Nodes created by rewriting.</p>

<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>Referenced by <a href="#a372e48a7ebee2344db07fef48667604e">operator=</a> and <a href="#ab12d8b019d8a4561686fa1493476eb7f">SSAUpdater</a>.</p>

</div>
</div>

### SSAUpdater() {#ab12d8b019d8a4561686fa1493476eb7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SSAUpdater::SSAUpdater (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>.</p>


<p>Reference <a href="#a8450e3821baaad374cd2e01184e07b9c">SSAUpdater</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SSAUpdater() {#a5a1cb31475d8d5088cbe0e04e3b27a64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SSAUpdater::~SSAUpdater ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a372e48a7ebee2344db07fef48667604e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SSAUpdater &amp; llvm::SSAUpdater::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a8450e3821baaad374cd2e01184e07b9c">SSAUpdater</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddAvailableValue() {#af0d1a82b4e629e834c2ed53e5cbe22ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSAUpdater::AddAvailableValue (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicate that a rewritten value is available in the specified block with the specified value.</p>

<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp/#a8c3648be397b04fce3a02bd44212659e">getAvailableVals</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#a6ef72ec0104739f72e030a7438753638">ConstructSSAForLoadSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/callbrprepare-cpp/#a0723d02f6ada882d6893701f43cddc23">InsertIntrinsicCalls</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a0321e28cc3da73c666a6f5e58a541de8">llvm::PhiLoweringHelper::lowerPhis</a> and <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a26d6acb7d8248e5d25f190b5d8fecbd3">llvm::JumpThreadingPass::updateSSA</a>.</p>

</div>
</div>

### FindValueForBlock() {#a24eaf55565ed385982d147ce3c354b40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SSAUpdater::FindValueForBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the value for the specified block if the <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> has one, otherwise return nullptr.</p>

<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp/#a8c3648be397b04fce3a02bd44212659e">getAvailableVals</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>.</p>

</div>
</div>

### GetValueAtEndOfBlock() {#acecfb9d97da9885264b3bde6bd6a64e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SSAUpdater::GetValueAtEndOfBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct SSA form, materializing a value that is live at the end of the specified block.</p>

<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>Referenced by <a href="#a5b0e45dbba53e985f1b9c532fb5f200b">GetValueInMiddleOfBlock</a>, <a href="#a05c4f6837ee786e83246beeb01e3aa8d">RewriteUse</a> and <a href="#a248544705875de8ef1c533827ec73a2e">RewriteUseAfterInsertions</a>.</p>

</div>
</div>

### GetValueInMiddleOfBlock() {#a5b0e45dbba53e985f1b9c532fb5f200b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SSAUpdater::GetValueInMiddleOfBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct SSA form, materializing a value that is live in the middle of the specified block.</p>


<p><span class="doxyComputerOutput">GetValueInMiddleOfBlock</span> is the same as <span class="doxyComputerOutput">GetValueAtEndOfBlock</span> except in one important case: if there is a definition of the rewritten value after the 'use' in BB. Consider code like this:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   X1 = ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">SomeBB:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/localizer-cpp/#a428090a453f41a199ef67fc3f2179fbc">use</a>(<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   X2 = ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   br <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, SomeBB, OutBB</span></span></div>

</div>


<p>In this case, there are two values (X1 and X2) added to the AvailableVals set by the client of the rewriter, and those values are both live out of their respective blocks. However, the use of X happens in the <em>middle</em> of a block. Because of this, we need to insert a new PHI node in SomeBB to merge the appropriate values, and this value isn't live out of the block.</p>


<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#af4aba918a76ca15bde1be3e14572e475">llvm::PHINode::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a858cab21fd29000697171b2f5b4bde31">llvm::BasicBlock::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a362b5e6097732cbc0d2fb555a1f73400">llvm::BasicBlock::getFirstNonPHIIt</a>, <a href="#acecfb9d97da9885264b3bde6bd6a64e8">GetValueAtEndOfBlock</a>, <a href="#ab671042c23924e0216c4a0b830ad2a04">HasValueForBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp/#aa8af038511783f111fd72d2361df7506">IsEquivalentPHI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a13da92d2694197fbcb5b95fd94e7570d">llvm::BasicBlock::phis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57feb935aaafd1bd4bfbb8dc56ad2129">llvm::simplifyInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#a6ef72ec0104739f72e030a7438753638">ConstructSSAForLoadSet</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a0321e28cc3da73c666a6f5e58a541de8">llvm::PhiLoweringHelper::lowerPhis</a> and <a href="#a05c4f6837ee786e83246beeb01e3aa8d">RewriteUse</a>.</p>

</div>
</div>

### HasValueForBlock() {#ab671042c23924e0216c4a0b830ad2a04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SSAUpdater::HasValueForBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> already has a value for the specified block.</p>

<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp/#a8c3648be397b04fce3a02bd44212659e">getAvailableVals</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#a6ef72ec0104739f72e030a7438753638">ConstructSSAForLoadSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a> and <a href="#a5b0e45dbba53e985f1b9c532fb5f200b">GetValueInMiddleOfBlock</a>.</p>

</div>
</div>

### Initialize() {#a4fe3279aae4f726813a672d4a9b26cb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSAUpdater::Initialize (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset this object to get ready for a new set of SSA updates with type 'Ty'.</p>


<p>PHI nodes get a name based on 'Name'.</p>


<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adf4e7878fc0b3b8dcde545178564190d">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::clear</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp/#a8c3648be397b04fce3a02bd44212659e">getAvailableVals</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#a6ef72ec0104739f72e030a7438753638">ConstructSSAForLoadSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/callbrprepare-cpp/#a0723d02f6ada882d6893701f43cddc23">InsertIntrinsicCalls</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a0321e28cc3da73c666a6f5e58a541de8">llvm::PhiLoweringHelper::lowerPhis</a> and <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a26d6acb7d8248e5d25f190b5d8fecbd3">llvm::JumpThreadingPass::updateSSA</a>.</p>

</div>
</div>

### RewriteUse() {#a05c4f6837ee786e83246beeb01e3aa8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSAUpdater::RewriteUse (<a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rewrite a use of the symbolic value.</p>


<p>This handles PHI nodes, which use their value in the corresponding predecessor. Note that this will not work if the use is supposed to be rewritten to a value defined in the same block as the use, but above it. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> 'AddAvailableValue's added for the use's block will be considered to be below it.</p>


<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#acecfb9d97da9885264b3bde6bd6a64e8">GetValueAtEndOfBlock</a> and <a href="#a5b0e45dbba53e985f1b9c532fb5f200b">GetValueInMiddleOfBlock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/callbrprepare-cpp/#a5109075f25d18bf4127922f2ab403dca">UpdateSSA</a> and <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a26d6acb7d8248e5d25f190b5d8fecbd3">llvm::JumpThreadingPass::updateSSA</a>.</p>

</div>
</div>

### RewriteUseAfterInsertions() {#a248544705875de8ef1c533827ec73a2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSAUpdater::RewriteUseAfterInsertions (<a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rewrite a use like <span class="doxyComputerOutput">RewriteUse</span> but handling in-block definitions.</p>


<p>This version of the method can rewrite uses in the same block as a definition, because it assumes that all uses of a value are below any inserted values.</p>


<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#acecfb9d97da9885264b3bde6bd6a64e8">GetValueAtEndOfBlock</a>.</p>

</div>
</div>

### UpdateDebugValues() {#aa3e6b78bbdd6959f19055f44fa4b7021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSAUpdater::UpdateDebugValues (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rewrite debug value intrinsics to conform to a new SSA form.</p>


<p>This will scout out all the debug value intrinsics associated with the instruction. Anything outside of its block will have its value set to the new SSA value if available, and undef if not.</p>


<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d7448a42ae4db532d3ba40e250ec825">llvm::findDbgValues</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a26d6acb7d8248e5d25f190b5d8fecbd3">llvm::JumpThreadingPass::updateSSA</a>.</p>

</div>
</div>

### UpdateDebugValues() {#a73a042579083174d928dbb6634d72281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSAUpdater::UpdateDebugValues (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgvalueinst">DbgValueInst</a> * &gt; &amp; DbgValues)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### UpdateDebugValues() {#a446a2ccd27cfa4837a6d10c745c86592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSAUpdater::UpdateDebugValues (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> * &gt; &amp; DbgValues)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### GetValueAtEndOfBlockInternal() {#a67a394f855b0f4c1fa9bed70e30b98b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SSAUpdater::GetValueAtEndOfBlockInternal (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> to see if AvailableVals has an entry for the specified BB and if so, return it.</p>


<p>If not, construct SSA form by first calculating the required placement of PHIs and then inserting new PHIs where needed.</p>


<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>

</div>
</div>

### UpdateDebugValue() {#a07c7b0a444408fce9bd5edbe9eb5acf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSAUpdater::UpdateDebugValue (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/dbgvalueinst">DbgValueInst</a> * DbgValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>

</div>
</div>

### UpdateDebugValue() {#a5e1f53b0774c198e1b9b0c8ce7fed39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSAUpdater::UpdateDebugValue (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> * DbgValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AV {#a3441b2d33dae53d1ba3b1fb1140beb09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::SSAUpdater::AV = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This keeps track of which value to use on a per-block basis.</p>


<p>When we insert PHI nodes, we keep track of them here.</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>.</p>

</div>
</div>

### InsertedPHIs {#a9f1f737229326f00844f518017cd0eea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt;PHINode *&gt;* llvm::SSAUpdater::InsertedPHIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is non-null, the <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> adds all PHI nodes that it creates to the vector.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>.</p>

</div>
</div>

### ProtoName {#a2e6bf477754392b94c0cbed9c9cfb350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::SSAUpdater::ProtoName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PHI nodes are given a name based on ProtoName.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>.</p>

</div>
</div>

### ProtoType {#a2f6e7a2b978b9cd09bd809eb3e7aecd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::SSAUpdater::ProtoType = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ProtoType holds the type of the values being rewritten.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
