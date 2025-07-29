---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vpuser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VPUser` Class

<p>This class augments <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> with operands which provide the inverse def-use edges from <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>'s users to their defs. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPUser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">Transforms/Vectorize/VPlanValue.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> is a base class modeling a sequence of one or more output IR instructions. <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt;::iterator <a href="#ac2dfaa1026ad07d1302a080e7141155c">operand_iterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt;::const_iterator <a href="#a5ea0a5220c528d6a965f8ede4267b247">const_operand_iterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ac2dfaa1026ad07d1302a080e7141155c">operand_iterator</a> &gt; <a href="#af1560d68b73e1e26fc29ceabefdb1b35">operand_range</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a5ea0a5220c528d6a965f8ede4267b247">const_operand_iterator</a> &gt; <a href="#aa022f3fb82d03217ef283e7eef7c6d03">const_operand_range</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8335b3a1aa6f1565ff932ff492856465">VPUser</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80639df55b6091fbc710f6751b8c89cc">VPUser</a> (const VPUser &amp;)=delete</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76244ee883849bc5ec7c6091697ecaa2">VPUser</a> (ArrayRef&lt; VPValue * &gt; Operands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a041dfcc8bd2b23699fd5b428bfc6c2d5">VPUser</a> (std::initializer_list&lt; VPValue * &gt; Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a8d2fb652895152da339d94ed712d257b">VPUser</a> (iterator_range&lt; IterT &gt; Operands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca05978aa053572a7303fc4affec9804">~VPUser</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28f0f90c8469906c16f2456762eb9378">operator=</a> (const VPUser &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4a3b471097ab37b1672a0d88869ea51">addOperand</a> (VPValue *Operand)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b21038d9b822b20c59e7ce5b12582e1">getNumOperands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e1b252a9bbdc1a440fb57a6257b97f4">getOperand</a> (unsigned N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19c3591dc1eeb5648552b33f70e04b65">setOperand</a> (unsigned I, VPValue *New)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac2dfaa1026ad07d1302a080e7141155c">operand_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b1fcd7575eca39b654ed96202958e14">op_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5ea0a5220c528d6a965f8ede4267b247">const_operand_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a632c04688f9bff71d4e9d69a4df0cc2a">op_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac2dfaa1026ad07d1302a080e7141155c">operand_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a634b1fa5443baf5d70ede2f674c46e54">op_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5ea0a5220c528d6a965f8ede4267b247">const_operand_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5f751860ed63da73505c504c2239c22">op_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af1560d68b73e1e26fc29ceabefdb1b35">operand_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11d83265a9e4ff6c6ecd3cf222ad0208">operands</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa022f3fb82d03217ef283e7eef7c6d03">const_operand_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6809a232915c0cde07c457334e3287c0">operands</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aece4fb85b179c528cb8740fa0f25be81">usesScalars</a> (const VPValue *Op) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> uses scalars of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#aece4fb85b179c528cb8740fa0f25be81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a896c572410e1fc4e7b726af80baac80f">onlyFirstLaneUsed</a> (const VPValue *Op) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> only uses the first lane of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#a896c572410e1fc4e7b726af80baac80f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0bf53a7cc41335c6e2a309c9cd149d4">onlyFirstPartUsed</a> (const VPValue *Op) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> only uses the first part of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#ad0bf53a7cc41335c6e2a309c9cd149d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0112474f9dc69912e4c067594692d15b">printOperands</a> (raw_ostream &amp;O, VPSlotTracker &amp;SlotTracker) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the operands to <span class="doxyComputerOutput">O</span>. <a href="#a0112474f9dc69912e4c067594692d15b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87de6cf891a606b740530b0e1cb0d239">Operands</a></td>
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

<p>This class augments <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> with operands which provide the inverse def-use edges from <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>'s users to their defs.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_operand\_iterator {#a5ea0a5220c528d6a965f8ede4267b247}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallVectorImpl&lt;VPValue*&gt;::const_iterator llvm::VPUser::const_operand_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### const\_operand\_range {#aa022f3fb82d03217ef283e7eef7c6d03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef iterator_range&lt;const_operand_iterator&gt; llvm::VPUser::const_operand_range</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### operand\_iterator {#ac2dfaa1026ad07d1302a080e7141155c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallVectorImpl&lt;VPValue*&gt;::iterator llvm::VPUser::operand_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### operand\_range {#af1560d68b73e1e26fc29ceabefdb1b35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef iterator_range&lt;operand_iterator&gt; llvm::VPUser::operand_range</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VPUser() {#a8335b3a1aa6f1565ff932ff492856465}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPUser::VPUser ()</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### VPUser() {#a80639df55b6091fbc710f6751b8c89cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPUser::VPUser (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> &amp;)</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#a76244ee883849bc5ec7c6091697ecaa2">VPUser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### VPUser() {#a76244ee883849bc5ec7c6091697ecaa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPUser::VPUser (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#af4a3b471097ab37b1672a0d88869ea51">addOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#adc8662faed8d6e19081308d8f3d418a2">llvm::VPRecipeBase::classof</a>, <a href="#a28f0f90c8469906c16f2456762eb9378">operator=</a>, <a href="#a80639df55b6091fbc710f6751b8c89cc">VPUser</a> and <a href="#a041dfcc8bd2b23699fd5b428bfc6c2d5">VPUser</a>.</p>

</div>
</div>

### VPUser() {#a041dfcc8bd2b23699fd5b428bfc6c2d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPUser::VPUser (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#a76244ee883849bc5ec7c6091697ecaa2">VPUser</a>.</p>

</div>
</div>

### VPUser() {#a8d2fb652895152da339d94ed712d257b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPUser::VPUser (<a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; IterT &gt; Operands)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#af4a3b471097ab37b1672a0d88869ea51">addOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VPUser() {#aca05978aa053572a7303fc4affec9804}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::VPUser::~VPUser ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#a11d83265a9e4ff6c6ecd3cf222ad0208">operands</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a28f0f90c8469906c16f2456762eb9378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPUser &amp; llvm::VPUser::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> &amp;)</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#a76244ee883849bc5ec7c6091697ecaa2">VPUser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addOperand() {#af4a3b471097ab37b1672a0d88869ea51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPUser::addOperand (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Operand)</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a552567714f74a84ee150e906e8020c5a">llvm::VPValue::addUser</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a4d2a943e39c98ccce6fd53e8df9c5c2b">addCanonicalIVRecipes</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenphirecipe/#a324b1f1ee681ab357d9d8949ab91d7f5">llvm::VPWidenPHIRecipe::addIncoming</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a02106664ead4e0c4e755457dbac7f7b3">addScalarResumePhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5a9cb34d61fa4930ff585649d1d5b2ed">addVPLaneMaskPhiAndUpdateExitBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#ae98489d1a78f9b06b62f2ef84ead26b6">llvm::VPWidenMemoryRecipe::setMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a1f66dc01846bbe322d2a8268c86d9f9b">llvm::VPReductionRecipe::VPReductionRecipe</a>, <a href="#a76244ee883849bc5ec7c6091697ecaa2">VPUser</a> and <a href="#a8d2fb652895152da339d94ed712d257b">VPUser</a>.</p>

</div>
</div>

### getNumOperands() {#a5b21038d9b822b20c59e7ce5b12582e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VPUser::getNumOperands ()</td>
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



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#ad7b5f223572e275e14a1f4ad6b158657">llvm::VPWidenCallRecipe::arg_operands</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#a100db8065cfdce9c6b8470af2d0a9607">llvm::VPWidenCallRecipe::arg_operands</a>, <a href="/web-llvm/docs/api/classes/llvm/vpactivelanemaskphirecipe/#a0f37ded87f1369ecdfb1a2584e12e1a4">llvm::VPActiveLaneMaskPHIRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#ae8d6a4dd88f6b0c4ac0c4c8a46b024e0">llvm::VPWidenIntrinsicRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#a82c7920e0c53dc071f1ac55f91a2895f">llvm::VPIRInstruction::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a703a08e4f8a8f64b8be733d194070cd1">llvm::VPWidenEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidengeprecipe/#a1b84446d2e199358a8406e7c92f51f03">llvm::VPWidenGEPRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#ad326bf7574f239b4177d077e513403aa">llvm::VPIRInstruction::extractLastLaneOfOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#accb5ce221150790c36b2d96af1be821c">llvm::InnerLoopVectorizer::fixNonInductionPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#aa9790ed243f5fd6c42b4b95453401d84">llvm::VPWidenCallRecipe::getCalledScalarFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a5a5560ef4d8c8565cb319d9b4f25fb8e">llvm::VPReductionRecipe::getCondOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a983022a3d3a46601b3cda23292365c21">llvm::VPWidenEVLRecipe::getEVL</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a1def6f3ff6398b4215f1a574cc3a5ecb">llvm::VPWidenEVLRecipe::getEVL</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#acea678698f2960bf21d86373ab549057">llvm::VPWidenIntOrFpInductionRecipe::getLastUnrolledPartOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbranchonmaskrecipe/#a1ab03a4ed322d1fbdd9b36a2ae5bc3a4">llvm::VPBranchOnMaskRecipe::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#aa8f8009fac3925355595375f9d3f458f">llvm::VPHistogramRecipe::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#a90af27768c9857a4a4f395908ac18985">llvm::VPInterleaveRecipe::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#aec678e1ae306c61d14f856a3eb0d6bac">llvm::VPReplicateRecipe::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a6dab5a878379d5ee92940853d3feb53d">llvm::VPWidenMemoryRecipe::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblendrecipe/#a4f0a937b4e04952fc07607effb9866a7">llvm::VPBlendRecipe::getNumIncomingValues</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#ad74d52a1deeb58e2a6afd245acd041c2">llvm::VPInterleaveRecipe::getNumStoreOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#af0169a980b0bfef931d2066da2a0ef9a">llvm::VPWidenIntOrFpInductionRecipe::getSplatVFValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpheaderphirecipe/#a92c12c8e69e03cc781dd010cdaa5f0e6">llvm::VPHeaderPHIRecipe::getStartValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpheaderphirecipe/#ac0c5343977fde1fa159ea1d190267b23">llvm::VPHeaderPHIRecipe::getStartValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#ac1722de15a2c5feb7571ffcdd2fd3bfe">llvm::VPInterleaveRecipe::getStoredValues</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblendrecipe/#af90bcb1df94143ecfb840bfe359f86d1">llvm::VPBlendRecipe::isNormalized</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#a0bb37b35edadea8a2bf62165276e0c5d">llvm::VPWidenIntrinsicRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#a47f98f05e3636d60f0ff58b81e497c9a">llvm::VPReverseVectorPointerRecipe::onlyFirstPartUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvectorpointerrecipe/#abad9bb37a7a01ad5276ca2ec9a9bc31d">llvm::VPVectorPointerRecipe::onlyFirstPartUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#ada5844051cef5e6e1fc7a5158c8047b7">llvm::VPIRInstruction::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#a202af2dd775be9a857e92e8ca6190b4f">llvm::VPReplicateRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidengeprecipe/#a0bc2944c24608efc8476b4bb1bc5606f">llvm::VPWidenGEPRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenphirecipe/#a62f66120ee7769cdadceaaf593e365de">llvm::VPWidenPHIRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#acb6e3f81767df2fcf8a7d2875cda28d4">llvm::VPWidenPointerInductionRecipe::print</a> and <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#ae6a91bbf1cfed2d6ba572ca974c94161">llvm::VPRecipeWithIRFlags::printFlags</a>.</p>

</div>
</div>

### getOperand() {#a6e1b252a9bbdc1a440fb57a6257b97f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPUser::getOperand (unsigned N)</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpactivelanemaskphirecipe/#a0f37ded87f1369ecdfb1a2584e12e1a4">llvm::VPActiveLaneMaskPHIRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbranchonmaskrecipe/#a73d49017590566d5c798bc3f5d15d515">llvm::VPBranchOnMaskRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#a79f07fcd4bfc94aa84346e34ad963f4e">llvm::VPCanonicalIVPHIRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpderivedivrecipe/#a82a9de490127f8f7a869b09dd2f83fd6">llvm::VPDerivedIVRecipe::clone</a>, <a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe/#a1d1e4090a90b16611c6f5257d33574b5">llvm::VPFirstOrderRecurrencePHIRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vppartialreductionrecipe/#af2417331ca3f8910d59e5f187de0c640">llvm::VPPartialReductionRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vppredinstphirecipe/#a9819963ec9063787a1face68ae70a3ed">llvm::VPPredInstPHIRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#a28cfe0563ab668a94408a75e7a852f06">llvm::VPReductionPHIRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#a35baec6b7c56d47b6b7e002a92b0621f">llvm::VPReverseVectorPointerRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarcastrecipe/#a7b5806a160a44f78155a4efc60ff0cdb">llvm::VPScalarCastRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#a80d30778f28687b5c3bddf019b55478c">llvm::VPScalarIVStepsRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvectorpointerrecipe/#af0756969ccfa0f31807a67c9b0caf92f">llvm::VPVectorPointerRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencanonicalivrecipe/#ab74584ceaa954f7eb5898f1b04480e49">llvm::VPWidenCanonicalIVRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#aeeba8e3d6e6936847e0ca7ceffab9937">llvm::VPWidenCastRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#a04e6730b77aac431d36f2cdba6a873ee">llvm::VPWidenPointerInductionRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#a6def10381cc09d92342a6846fe1174e0">llvm::VPHistogramRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vppartialreductionrecipe/#a66409a988f6c39ff0a8d9a5e64e612aa">llvm::VPPartialReductionRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a45ff90e525c3f3879a1a7f5297d8857d">llvm::VPReductionRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#ac2e757808f897dbb866fac9b8ad2f045">llvm::VPWidenCastRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#ae8d6a4dd88f6b0c4ac0c4c8a46b024e0">llvm::VPWidenIntrinsicRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a0075161c54fc525d16130fa2e1891ad2">llvm::VPWidenRecipe::computeCost</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a7805b21c1397d70002fd216481351f5e">llvm::VPWidenSelectRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpactivelanemaskphirecipe/#a0b6f2c0e5bec17e3b7fddc78e12cd5d1">llvm::VPActiveLaneMaskPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpderivedivrecipe/#a0f37fe11b57d14686c7ca5e7a3846174">llvm::VPDerivedIVRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#a19aa4af9c02f8e3571cc82c0634a25f6">llvm::VPHistogramRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vppartialreductionrecipe/#a29641e0ae49abc7a19221cc882c08da6">llvm::VPPartialReductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vppredinstphirecipe/#a3e63796e123d5ba9cbfa023983328c37">llvm::VPPredInstPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#a2ed5b7b284097278ee4e550897b1f057">llvm::VPReplicateRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#ab76c8b759635aabfadc49dc1292aec2c">llvm::VPReverseVectorPointerRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#acdd340f122251b99aaee3308d31f1230">llvm::VPScalarIVStepsRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvectorpointerrecipe/#a82d57109b0437debe570e7dae895f3e3">llvm::VPVectorPointerRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencanonicalivrecipe/#a06435ca2ee49b05bd4d93bdbb3b7d8e6">llvm::VPWidenCanonicalIVRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#a9b432a2a53b6ec71e9290e6f9d7582ea">llvm::VPWidenCastRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a703a08e4f8a8f64b8be733d194070cd1">llvm::VPWidenEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidengeprecipe/#a1b84446d2e199358a8406e7c92f51f03">llvm::VPWidenGEPRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenphirecipe/#afd60b87e0eaaccd0f8c122208ac1049d">llvm::VPWidenPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#ac53a5d033ba641288b6e15344d880186">llvm::VPWidenPointerInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a1217df326ed753111e60d3eaef272ded">llvm::VPWidenRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a8ab6a201a32f4db51d8f030c5d3ba5c6">llvm::VPWidenSelectRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#ad326bf7574f239b4177d077e513403aa">llvm::VPIRInstruction::extractLastLaneOfOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#a836a687c8159f9f598942689cf10f1ec">llvm::VPInterleaveRecipe::getAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#af3caef2aa9a6ef6739a11c87df6f511f">llvm::VPWidenMemoryRecipe::getAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/vpheaderphirecipe/#a80333e8d5f353fb9e929388e577a593f">llvm::VPHeaderPHIRecipe::getBackedgeValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#aa9790ed243f5fd6c42b4b95453401d84">llvm::VPWidenCallRecipe::getCalledScalarFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a917ddbb65611fb8da66ee02a75742696">llvm::VPReductionRecipe::getChainOp</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a63d9005eafec780dfb441a256a79e4ca">llvm::VPWidenSelectRecipe::getCond</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a5a5560ef4d8c8565cb319d9b4f25fb8e">llvm::VPReductionRecipe::getCondOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionevlrecipe/#a5fb58a50b3b232848a0ad7a641559586">llvm::VPReductionEVLRecipe::getEVL</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a983022a3d3a46601b3cda23292365c21">llvm::VPWidenEVLRecipe::getEVL</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a1def6f3ff6398b4215f1a574cc3a5ecb">llvm::VPWidenEVLRecipe::getEVL</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a6aa813347887ce533adf6f76c42c4bf0">llvm::VPWidenLoadEVLRecipe::getEVL</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#ae2ed3e1edcea346d3a7e76e766b2ff51">llvm::VPWidenStoreEVLRecipe::getEVL</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#ab93ade258875dd2960b151068ff8a506">llvm::VPWidenPointerInductionRecipe::getFirstUnrolledPartOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblendrecipe/#a2019700bf97441cc4fcf162a09247210">llvm::VPBlendRecipe::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenphirecipe/#a48a84a2d77d942f724c87bc7657c4355">llvm::VPWidenPHIRecipe::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#acea678698f2960bf21d86373ab549057">llvm::VPWidenIntOrFpInductionRecipe::getLastUnrolledPartOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblendrecipe/#a26df1ec06cf75ead168070b305c1344d">llvm::VPBlendRecipe::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbranchonmaskrecipe/#a1ab03a4ed322d1fbdd9b36a2ae5bc3a4">llvm::VPBranchOnMaskRecipe::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#aa8f8009fac3925355595375f9d3f458f">llvm::VPHistogramRecipe::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#a90af27768c9857a4a4f395908ac18985">llvm::VPInterleaveRecipe::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#aec678e1ae306c61d14f856a3eb0d6bac">llvm::VPReplicateRecipe::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a6dab5a878379d5ee92940853d3feb53d">llvm::VPWidenMemoryRecipe::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#af0169a980b0bfef931d2066da2a0ef9a">llvm::VPWidenIntOrFpInductionRecipe::getSplatVFValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpderivedivrecipe/#aeb71527486a6730ec967f207fe2ac4fd">llvm::VPDerivedIVRecipe::getStartValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpheaderphirecipe/#a92c12c8e69e03cc781dd010cdaa5f0e6">llvm::VPHeaderPHIRecipe::getStartValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpheaderphirecipe/#ac0c5343977fde1fa159ea1d190267b23">llvm::VPHeaderPHIRecipe::getStartValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpderivedivrecipe/#a49cc736389970ff14e3f53d8b5664674">llvm::VPDerivedIVRecipe::getStepValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#a3780a6f64a1197f49de33db3f6987a78">llvm::VPScalarIVStepsRecipe::getStepValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwideninductionrecipe/#a74f9beabcc57857ae7a7ba943e72776b">llvm::VPWidenInductionRecipe::getStepValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwideninductionrecipe/#addd733cfc8722afa95d5b085e621543c">llvm::VPWidenInductionRecipe::getStepValue</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#a0a9373eaa0b8d7072cd86c71a783e6b0">llvm::VPWidenStoreEVLRecipe::getStoredValue</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a93408766f5852c2fd01c55ffd668bcbc">llvm::VPWidenStoreRecipe::getStoredValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a4dce99c106a96a31be97370d5c7b0e22">llvm::VPReductionRecipe::getVecOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#abfedc7c9108829e4082a30dfe60e5de5">llvm::VPReverseVectorPointerRecipe::getVFValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#af1beb1c2bf9633578e61f4b9121fca92">llvm::VPReverseVectorPointerRecipe::getVFValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#ad708199fa5b904868996a507096d7fa6">llvm::VPWidenIntOrFpInductionRecipe::getVFValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#a23c3b225abd1add13f06a60c4cba9e67">llvm::VPWidenIntOrFpInductionRecipe::getVFValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#a0bb37b35edadea8a2bf62165276e0c5d">llvm::VPWidenIntrinsicRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a13368acf4fbb5816c3d82099b11519b1">preparePlanForMainVectorLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/vpderivedivrecipe/#a26e4971aa029b70786933757974a302b">llvm::VPDerivedIVRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#afc22e4ac9c148e2145862b17b9aa3f98">llvm::VPHistogramRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#a942db1b770fa4cb70c66a2546d88cfb0">llvm::VPInterleaveRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#acb6e3f81767df2fcf8a7d2875cda28d4">llvm::VPWidenPointerInductionRecipe::print</a> and <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a75740005a7cfb534940606c60654527e">llvm::VPWidenSelectRecipe::print</a>.</p>

</div>
</div>

### onlyFirstLaneUsed() {#a896c572410e1fc4e7b726af80baac80f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::VPUser::onlyFirstLaneUsed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Op)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> only uses the first lane of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>


<p>Conservatively returns false.</p>


<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="#a11d83265a9e4ff6c6ecd3cf222ad0208">operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#acd93ffe413319e78d7c62688cc86eb6c">llvm::VPWidenCallRecipe::execute</a> and <a href="#aece4fb85b179c528cb8740fa0f25be81">usesScalars</a>.</p>

</div>
</div>

### onlyFirstPartUsed() {#ad0bf53a7cc41335c6e2a309c9cd149d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::VPUser::onlyFirstPartUsed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Op)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> only uses the first part of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>


<p>Conservatively returns false.</p>


<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="#a11d83265a9e4ff6c6ecd3cf222ad0208">operands</a>.</p>

</div>
</div>

### op\_begin() {#a6b1fcd7575eca39b654ed96202958e14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">operand_iterator llvm::VPUser::op_begin ()</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#ad7b5f223572e275e14a1f4ad6b158657">llvm::VPWidenCallRecipe::arg_operands</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#a100db8065cfdce9c6b8470af2d0a9607">llvm::VPWidenCallRecipe::arg_operands</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#a23c6cd965aca4e811f1d5b0e5b7eb204">llvm::VPWidenCallRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#a5eac4b4a3d8c1941d57b6c10750e72d7">llvm::VPWidenIntrinsicRecipe::clone</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ac967ad551e77554a15e20cac14877ac7">createReplicateRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#ac1722de15a2c5feb7571ffcdd2fd3bfe">llvm::VPInterleaveRecipe::getStoredValues</a>, <a href="#a11d83265a9e4ff6c6ecd3cf222ad0208">operands</a>, <a href="#a6809a232915c0cde07c457334e3287c0">operands</a> and <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#a202af2dd775be9a857e92e8ca6190b4f">llvm::VPReplicateRecipe::print</a>.</p>

</div>
</div>

### op\_begin() {#a632c04688f9bff71d4e9d69a4df0cc2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_operand_iterator llvm::VPUser::op_begin ()</td>
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



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### op\_end() {#a634b1fa5443baf5d70ede2f674c46e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">operand_iterator llvm::VPUser::op_end ()</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#a23c6cd965aca4e811f1d5b0e5b7eb204">llvm::VPWidenCallRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#a5eac4b4a3d8c1941d57b6c10750e72d7">llvm::VPWidenIntrinsicRecipe::clone</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ac967ad551e77554a15e20cac14877ac7">createReplicateRegion</a>, <a href="#a11d83265a9e4ff6c6ecd3cf222ad0208">operands</a> and <a href="#a6809a232915c0cde07c457334e3287c0">operands</a>.</p>

</div>
</div>

### op\_end() {#ae5f751860ed63da73505c504c2239c22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_operand_iterator llvm::VPUser::op_end ()</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### operands() {#a11d83265a9e4ff6c6ecd3cf222ad0208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">operand_range llvm::VPUser::operands ()</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="#a6b1fcd7575eca39b654ed96202958e14">op_begin</a> and <a href="#a634b1fa5443baf5d70ede2f674c46e54">op_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpblendrecipe/#ad05094de15d05295d9e769d815cd076d">llvm::VPBlendRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#a4c02a215b23361553e82137c023b5556">llvm::VPHistogramRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a4a5678fa8d469e9dd49b7e389c22d5c7">llvm::VPInstruction::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#aab4024c25d39ff91a093eb06b900f56d">llvm::VPIRInstruction::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#ac115374c10d14c504419b9f75e7ca9e5">llvm::VPReplicateRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidengeprecipe/#a750b0fe1be4d52b023cd30515d584681">llvm::VPWidenGEPRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a306ded79f0c24ba14d204f2081297648">llvm::VPWidenRecipe::clone</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a05529e945c1921455afbca3be97f42b5">llvm::VPWidenSelectRecipe::clone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62219a4c97e27d64593245e4e9187cd1">llvm::collectEphemeralRecipesForVPlan</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#ae8d6a4dd88f6b0c4ac0c4c8a46b024e0">llvm::VPWidenIntrinsicRecipe::computeCost</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a7805b21c1397d70002fd216481351f5e">llvm::VPWidenSelectRecipe::computeCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ad0faf4b8ff1cf3306958d056dcb2fde2">createEVLRecipe</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aa0f143b8d4693978b984f0639c90e508">llvm::VPlanTransforms::dropPoisonGeneratingRecipes</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#a82c7920e0c53dc071f1ac55f91a2895f">llvm::VPIRInstruction::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#ad6ab589f9da183bfc7227344c30aab78">llvm::VPWidenIntrinsicRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a1217df326ed753111e60d3eaef272ded">llvm::VPWidenRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a9396319801f74828cfbd94177f38eabc">hoistPreviousBeforeFORUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a002a77cdbc23293b8f7a8458ffd0f905">llvm::vputils::isUniformAfterVectorization</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblendrecipe/#a0dc849c5a55d8fc876ea6deca991b264">llvm::VPBlendRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#ab21cd8ac594bdf79d7fd74ab1e977767">llvm::VPCanonicalIVPHIRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpderivedivrecipe/#adf60b46670f4cd2e96a4268683c0477a">llvm::VPDerivedIVRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpevlbasedivphirecipe/#afdb9115c8b4efb7b680b9a1c8faa6ca3">llvm::VPEVLBasedIVPHIRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#accc830d2b6d4d03922cf5e6a238ae9c1">llvm::VPInstruction::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#a77dca92362b686e51f4d7297f4fab630">llvm::VPInterleaveRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#aa659aea6cdcfa2f24d9af6cc68f5eb5b">llvm::VPIRInstruction::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionevlrecipe/#a327c7ee2465b3f3afa825f94bb9b1ef8">llvm::VPReductionEVLRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#a6a8503acb5bcb0bb1765bdc31b97d5ff">llvm::VPReplicateRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#acb8172f417bc3a850179acb096a27f2c">llvm::VPReverseVectorPointerRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarcastrecipe/#a9898af103110771e7946826d82b0ca4d">llvm::VPScalarCastRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#a12d7b76bd054abbf5cc6594186f80004">llvm::VPScalarIVStepsRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarphirecipe/#a13f66f91b9133d45b6614e59adf4ff95">llvm::VPScalarPHIRecipe::onlyFirstLaneUsed</a>, <a href="#a896c572410e1fc4e7b726af80baac80f">onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvectorpointerrecipe/#ae4c5a9c1b0255e0baad70069e8daca8e">llvm::VPVectorPointerRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#aa2af49cdd11b0200dfc4d8576db20666">llvm::VPWidenEVLRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#a0bb37b35edadea8a2bf62165276e0c5d">llvm::VPWidenIntrinsicRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#abed0bd6ee69b8083deba69aa189aebc3">llvm::VPWidenLoadEVLRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a769d05569a9befd640244f159ba7f82a">llvm::VPWidenLoadRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#a7a37ffac00db5fca0c5df19b1ebe4980">llvm::VPWidenStoreEVLRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a1ea8913439b690e47eae67c829cf0d24">llvm::VPWidenStoreRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#a406029ae6521421e1cf3808aed2bbfab">llvm::VPCanonicalIVPHIRecipe::onlyFirstPartUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#aa0b84f190dbf600165d9b79f4cf51d6c">llvm::VPInstruction::onlyFirstPartUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#a621f72b076ead24886f3e3408a3051df">llvm::VPIRInstruction::onlyFirstPartUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#a47f98f05e3636d60f0ff58b81e497c9a">llvm::VPReverseVectorPointerRecipe::onlyFirstPartUsed</a>, <a href="#ad0bf53a7cc41335c6e2a309c9cd149d4">onlyFirstPartUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvectorpointerrecipe/#abad9bb37a7a01ad5276ca2ec9a9bc31d">llvm::VPVectorPointerRecipe::onlyFirstPartUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#ada5844051cef5e6e1fc7a5158c8047b7">llvm::VPIRInstruction::print</a>, <a href="#a0112474f9dc69912e4c067594692d15b">printOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a4690286163882c35068b1908f4d752fd">llvm::InnerLoopVectorizer::scalarizeInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a1536feae2abb3570ac032768a53ddd00">sinkScalarOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbranchonmaskrecipe/#a7de68edec2a0bc3ab2ebebd66d96b82e">llvm::VPBranchOnMaskRecipe::usesScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#adee88d30bbcc68edcdec7a3bd7f3eb19">llvm::VPIRInstruction::usesScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/vppredinstphirecipe/#a18022e503aa4aa7c84e141d40031531d">llvm::VPPredInstPHIRecipe::usesScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#a8ba8706a684c296645948a2e30225dc1">llvm::VPReplicateRecipe::usesScalars</a>, <a href="#aece4fb85b179c528cb8740fa0f25be81">usesScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a6b46c5bfbb9611348fa79017122b9d66">llvm::VPWidenEVLRecipe::VPWidenEVLRecipe</a> and <a href="#aca05978aa053572a7303fc4affec9804">~VPUser</a>.</p>

</div>
</div>

### operands() {#a6809a232915c0cde07c457334e3287c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_operand_range llvm::VPUser::operands ()</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="#a6b1fcd7575eca39b654ed96202958e14">op_begin</a> and <a href="#a634b1fa5443baf5d70ede2f674c46e54">op_end</a>.</p>

</div>
</div>

### setOperand() {#a19c3591dc1eeb5648552b33f70e04b65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPUser::setOperand (unsigned I, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * New)</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a453563e4ed7e249a7f3e92b98b9052df">addExitUsersForFirstOrderRecurrences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ac967ad551e77554a15e20cac14877ac7">createReplicateRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#ad326bf7574f239b4177d077e513403aa">llvm::VPIRInstruction::extractLastLaneOfOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/vpheaderphirecipe/#a977dedf43194597a17f6a7a3e58b7c75">llvm::VPHeaderPHIRecipe::setStartValue</a>.</p>

</div>
</div>

### usesScalars() {#aece4fb85b179c528cb8740fa0f25be81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::VPUser::usesScalars (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Op)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> uses scalars of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>


<p>Conservatively returns if only first (scalar) lane is used, as default.</p>


<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="#a896c572410e1fc4e7b726af80baac80f">onlyFirstLaneUsed</a> and <a href="#a11d83265a9e4ff6c6ecd3cf222ad0208">operands</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### printOperands() {#a0112474f9dc69912e4c067594692d15b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPUser::printOperands (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/classes/llvm/vpslottracker">VPSlotTracker</a> &amp; SlotTracker)</td>
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

<p>Print the operands to <span class="doxyComputerOutput">O</span>.</p>

<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>, definition at line 1455 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3b4daeeeabc6cdcff5627aace66de8a3">llvm::interleaveComma</a> and <a href="#a11d83265a9e4ff6c6ecd3cf222ad0208">operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpactivelanemaskphirecipe/#af47ca872e4ed34916046cb05efe31520">llvm::VPActiveLaneMaskPHIRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#aec4269de8eafb1f6c92c574dc294c4e7">llvm::VPCanonicalIVPHIRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpevlbasedivphirecipe/#a5d5b65c20b3d92c79eb49194a6d14549">llvm::VPEVLBasedIVPHIRecipe::print</a>, <a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe/#ace0ce61d3eaf2f2269401946cea45402">llvm::VPFirstOrderRecurrencePHIRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#aca839409ad4f4fb66241f6b97da6674f">llvm::VPInstruction::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vppartialreductionrecipe/#a547b8cb4c97345c9b9f78fbcd4b4da89">llvm::VPPartialReductionRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vppredinstphirecipe/#ac2926669bdf000e31cf50efdab898bac">llvm::VPPredInstPHIRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#ab8d22b8717052bd87b3d06329bc16313">llvm::VPReductionPHIRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#a202af2dd775be9a857e92e8ca6190b4f">llvm::VPReplicateRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#a9c7a98f9a6cf962c378e7e733295a009">llvm::VPReverseVectorPointerRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarcastrecipe/#a344cb72b5808ac915cbb3ca2ab53d6e1">llvm::VPScalarCastRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#a05c6e525343e482ff033cae3e624e752">llvm::VPScalarIVStepsRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarphirecipe/#a1857ef1592a73e3a1458f635fb407cc3">llvm::VPScalarPHIRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvectorpointerrecipe/#a240688a9252bdfe411b157159b5aaf69">llvm::VPVectorPointerRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencanonicalivrecipe/#a249155094ad547ed977e3c3517b45fb8">llvm::VPWidenCanonicalIVRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#a30fd23ee3def3f12fad8496e85755c2a">llvm::VPWidenCastRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a64949951a81f6c67ecbd51ad90374828">llvm::VPWidenEVLRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidengeprecipe/#a0bc2944c24608efc8476b4bb1bc5606f">llvm::VPWidenGEPRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#aed59fc8e16abed2a289c006b347f354f">llvm::VPWidenIntOrFpInductionRecipe::print</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a86fd40dcbb7bf4bd5c2765ff07353fef">llvm::VPWidenLoadEVLRecipe::print</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#ac293be3f7d76772b820f58925b6b14e1">llvm::VPWidenLoadRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenphirecipe/#a62f66120ee7769cdadceaaf593e365de">llvm::VPWidenPHIRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a5ad4e4df14b5a3c6905892a8f4bcb580">llvm::VPWidenRecipe::print</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#a62d6c125728278eddd0bf38364a471f9">llvm::VPWidenStoreEVLRecipe::print</a> and <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#adb05bb4921b88025b8b296459e4d2af4">llvm::VPWidenStoreRecipe::print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Operands {#a87de6cf891a606b740530b0e1cb0d239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VPValue *, 2&gt; llvm::VPUser::Operands</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
