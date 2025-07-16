---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/randomirbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RandomIRBuilder` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::RandomIRBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">llvm/FuzzMutate/RandomIRBuilder.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SourceType { <a href="#afc8fc540b727697fd76b8fec899237cc">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">SinkType { <a href="#ab56a2db639492477ac49bd3305c83ecb">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41c54af34530c5d13465a26a69df00d2">RandomIRBuilder</a> (int Seed, ArrayRef&lt; Type * &gt; AllowedTypes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50ee598578572bbfadfb9279f650cdd7">createStackMemory</a> (Function *F, Type *Ty, Value *Init=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a stack memory at the head of the function, store <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/init">Init</a></span> to the memory if provided. <a href="#a50ee598578572bbfadfb9279f650cdd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45a66620cecb92a4ffdc36042859c575">findOrCreateGlobalVariable</a> (Module *M, ArrayRef&lt; Value * &gt; Srcs, fuzzerop::SourcePred Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find or create a global variable. <a href="#a45a66620cecb92a4ffdc36042859c575">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47a923aecde90d3d6e66e00bab23318d">findOrCreateSource</a> (BasicBlock &amp;BB, ArrayRef&lt; Instruction * &gt; Insts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find a "source" for some operation, which will be used in one of the operation's operands. <a href="#a47a923aecde90d3d6e66e00bab23318d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8688fe7e12511bba710a19b4aaf027a1">findOrCreateSource</a> (BasicBlock &amp;BB, ArrayRef&lt; Instruction * &gt; Insts, ArrayRef&lt; Value * &gt; Srcs, fuzzerop::SourcePred Pred, bool allowConstant=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find a "source" for some operation, which will be used in one of the operation's operands. <a href="#a8688fe7e12511bba710a19b4aaf027a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b569b7040c15c2e2233b3064caa8f4f">newSource</a> (BasicBlock &amp;BB, ArrayRef&lt; Instruction * &gt; Insts, ArrayRef&lt; Value * &gt; Srcs, fuzzerop::SourcePred Pred, bool allowConstant=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create some <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> suitable as a source for some operation. <a href="#a8b569b7040c15c2e2233b3064caa8f4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a993771e7c58c60044cbc4c57f689406e">connectToSink</a> (BasicBlock &amp;BB, ArrayRef&lt; Instruction * &gt; Insts, Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find a viable user for <span class="doxyComputerOutput">V</span> in <span class="doxyComputerOutput">Insts</span>, which should all be contained in <span class="doxyComputerOutput">BB</span>. <a href="#a993771e7c58c60044cbc4c57f689406e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a679d0966b3083f647af785f24936d3d9">newSink</a> (BasicBlock &amp;BB, ArrayRef&lt; Instruction * &gt; Insts, Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a user for <span class="doxyComputerOutput">V</span> in <span class="doxyComputerOutput">BB</span>. <a href="#a679d0966b3083f647af785f24936d3d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc37df924da7f46c47c5f04d20d52c3e">findPointer</a> (BasicBlock &amp;BB, ArrayRef&lt; Instruction * &gt; Insts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afde61f758ce6c73015640b4cf6087a76">randomType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a uniformly choosen type from <span class="doxyComputerOutput">AllowedTypes</span>. <a href="#afde61f758ce6c73015640b4cf6087a76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a272d004d22ae2326fa35628cff91dd69">createFunctionDeclaration</a> (Module &amp;M, uint64_t ArgNum)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe7b90feed41b783460d4bde52f328a9">createFunctionDeclaration</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ba6b711f3cab802b6e29a1595d223bb">createFunctionDefinition</a> (Module &amp;M, uint64_t ArgNum)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f27711fdb6185ce6f93a65b2f08cd7">createFunctionDefinition</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8160fd650436368290f5722231f731fd">RandomEngine</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01056e939ac37a0452cd1992ff8005ef">Rand</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b95175df9fb4eb569d18aec29c82159">KnownTypes</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae28ff8b1137dd062a8f23d7554631838">MinArgNum</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcdead6726c7a77ef991c020a0699eaa">MaxArgNum</a> = 5</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19a79375c427ba944afadf6c14314cbf">MinFunctionNum</a> = 1</td>
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


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### SinkType {#ab56a2db639492477ac49bd3305c83ecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::RandomIRBuilder::SinkType </td>
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
<td class="doxyEnumItemName">SinkToInstInCurBlock<a id="ab56a2db639492477ac49bd3305c83ecba27a2b4f186aa1ae115c6876ec840956e"></a></td>
<td class="doxyEnumItemDescription">TODO: Also consider pointers in function argument</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PointersInDominator<a id="ab56a2db639492477ac49bd3305c83ecba26163bf801aec5cdabb9ea9023e29939"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InstInDominatee<a id="ab56a2db639492477ac49bd3305c83ecba3ffee30a398eb75e961c4f2a66727dcf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NewStore<a id="ab56a2db639492477ac49bd3305c83ecba0311270301d33de763eb4efccd957f63"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SinkToGlobalVariable<a id="ab56a2db639492477ac49bd3305c83ecba88b3b2f3449155ee8bdcc40f53eb5576"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EndOfValueSink<a id="ab56a2db639492477ac49bd3305c83ecba004a89faafc5f4a30e987ba67d775540"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>.</p>

</div>
</div>

### SourceType {#afc8fc540b727697fd76b8fec899237cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::RandomIRBuilder::SourceType </td>
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
<td class="doxyEnumItemName">SrcFromInstInCurBlock<a id="afc8fc540b727697fd76b8fec899237cca810b2bd5bed5da88982ee7a2ff81d9e6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FunctionArgument<a id="afc8fc540b727697fd76b8fec899237cca0a9098057aeb2f738bff9e305777bb34"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InstInDominator<a id="afc8fc540b727697fd76b8fec899237cca2d9ebfb9a11cc816e7f870a4c62a830c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SrcFromGlobalVariable<a id="afc8fc540b727697fd76b8fec899237ccaeb5c43a6fff8e66f2d4c7b57cd529cb5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NewConstOrStack<a id="afc8fc540b727697fd76b8fec899237cca51d1677574dfb35d07d7c8101ace27e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EndOfValueSource<a id="afc8fc540b727697fd76b8fec899237ccaf1c63139722b2158137dd19c51dfffe9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RandomIRBuilder() {#a41c54af34530c5d13465a26a69df00d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RandomIRBuilder::RandomIRBuilder (int Seed, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; AllowedTypes)</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>.</p>


<p>References <a href="#a2b95175df9fb4eb569d18aec29c82159">KnownTypes</a>, <a href="#a01056e939ac37a0452cd1992ff8005ef">Rand</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/randomnumbergenerator-cpp/#a0c7bb0b4761ae4c3f875fb9b0a235a93">Seed</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### connectToSink() {#a993771e7c58c60044cbc4c57f689406e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * RandomIRBuilder::connectToSink (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; Insts, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find a viable user for <span class="doxyComputerOutput">V</span> in <span class="doxyComputerOutput">Insts</span>, which should all be contained in <span class="doxyComputerOutput">BB</span>.</p>


<p>This may also create some new instruction in <span class="doxyComputerOutput">BB</span> and use that.</p>


<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>, definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp">RandomIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a291ac49156942529f159a9ec003cc25f">llvm::ArrayRef&lt; T &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#ab56a2db639492477ac49bd3305c83ecba004a89faafc5f4a30e987ba67d775540">EndOfValueSink</a>, <a href="#a45a66620cecb92a4ffdc36042859c575">findOrCreateGlobalVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp/#afd194fd0bfdd8b288bb7f1e9585a1679">getDominatees</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp/#a93819e91559afbcefbe8c8d90f0499ed">getDominators</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ab56a2db639492477ac49bd3305c83ecba3ffee30a398eb75e961c4f2a66727dcf">InstInDominatee</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp/#a04a8af897aa17e64fedac0215ae4e705">isCompatibleReplacement</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6695fbc0cb8edb5aede4af74f2ef95d0">llvm::makeSampler</a>, <a href="#a679d0966b3083f647af785f24936d3d9">newSink</a>, <a href="#ab56a2db639492477ac49bd3305c83ecba0311270301d33de763eb4efccd957f63">NewStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a8069953a59ba2891578b351ccf2a6bf3">llvm::fuzzerop::onlyType</a>, <a href="#ab56a2db639492477ac49bd3305c83ecba26163bf801aec5cdabb9ea9023e29939">PointersInDominator</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a01056e939ac37a0452cd1992ff8005ef">Rand</a>, <a href="#ab56a2db639492477ac49bd3305c83ecba88b3b2f3449155ee8bdcc40f53eb5576">SinkToGlobalVariable</a> and <a href="#ab56a2db639492477ac49bd3305c83ecba27a2b4f186aa1ae115c6876ec840956e">SinkToInstInCurBlock</a>.</p>

</div>
</div>

### createFunctionDeclaration() {#a272d004d22ae2326fa35628cff91dd69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * RandomIRBuilder::createFunctionDeclaration (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, uint64_t ArgNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>, definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp">RandomIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a> and <a href="#afde61f758ce6c73015640b4cf6087a76">randomType</a>.</p>


<p>Referenced by <a href="#afe7b90feed41b783460d4bde52f328a9">createFunctionDeclaration</a> and <a href="#a7ba6b711f3cab802b6e29a1595d223bb">createFunctionDefinition</a>.</p>

</div>
</div>

### createFunctionDeclaration() {#afe7b90feed41b783460d4bde52f328a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * RandomIRBuilder::createFunctionDeclaration (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>, definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp">RandomIRBuilder.cpp</a>.</p>


<p>References <a href="#a272d004d22ae2326fa35628cff91dd69">createFunctionDeclaration</a>, <a href="#abcdead6726c7a77ef991c020a0699eaa">MaxArgNum</a>, <a href="#ae28ff8b1137dd062a8f23d7554631838">MinArgNum</a>, <a href="#a01056e939ac37a0452cd1992ff8005ef">Rand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af2a9add76255a5e6dc09b1a5f9505f21">llvm::uniform</a>.</p>

</div>
</div>

### createFunctionDefinition() {#a7ba6b711f3cab802b6e29a1595d223bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * RandomIRBuilder::createFunctionDefinition (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, uint64_t ArgNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>, definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp">RandomIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/returninst/#a932710d4c1c965497707751eb4f7948f">llvm::ReturnInst::Create</a>, <a href="#a272d004d22ae2326fa35628cff91dd69">createFunctionDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>.</p>


<p>Referenced by <a href="#a39f27711fdb6185ce6f93a65b2f08cd7">createFunctionDefinition</a>.</p>

</div>
</div>

### createFunctionDefinition() {#a39f27711fdb6185ce6f93a65b2f08cd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * RandomIRBuilder::createFunctionDefinition (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>, definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp">RandomIRBuilder.cpp</a>.</p>


<p>References <a href="#a7ba6b711f3cab802b6e29a1595d223bb">createFunctionDefinition</a>, <a href="#abcdead6726c7a77ef991c020a0699eaa">MaxArgNum</a>, <a href="#ae28ff8b1137dd062a8f23d7554631838">MinArgNum</a>, <a href="#a01056e939ac37a0452cd1992ff8005ef">Rand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af2a9add76255a5e6dc09b1a5f9505f21">llvm::uniform</a>.</p>

</div>
</div>

### createStackMemory() {#a50ee598578572bbfadfb9279f650cdd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst * RandomIRBuilder::createStackMemory (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Init=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a stack memory at the head of the function, store <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/init">Init</a></span> to the memory if provided.</p>

<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp">RandomIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a161fd4e9fa5367f64c2a4c9e921c3ad3">llvm::BasicBlock::getFirstInsertionPt</a> and <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>.</p>


<p>Referenced by <a href="#a679d0966b3083f647af785f24936d3d9">newSink</a> and <a href="#a8b569b7040c15c2e2233b3064caa8f4f">newSource</a>.</p>

</div>
</div>

### findOrCreateGlobalVariable() {#a45a66620cecb92a4ffdc36042859c575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; GlobalVariable *, bool &gt; RandomIRBuilder::findOrCreateGlobalVariable (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Srcs, <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">fuzzerop::SourcePred</a> Pred)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find or create a global variable.</p>


<p>It will be initialized by random constants that satisfies <span class="doxyComputerOutput">Pred</span>. It will also report whether this global variable found or created.</p>


<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp">RandomIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="#a2b95175df9fb4eb569d18aec29c82159">KnownTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6695fbc0cb8edb5aede4af74f2ef95d0">llvm::makeSampler</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a01056e939ac37a0452cd1992ff8005ef">Rand</a>.</p>


<p>Referenced by <a href="#a993771e7c58c60044cbc4c57f689406e">connectToSink</a> and <a href="#a8688fe7e12511bba710a19b4aaf027a1">findOrCreateSource</a>.</p>

</div>
</div>

### findOrCreateSource() {#a47a923aecde90d3d6e66e00bab23318d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * RandomIRBuilder::findOrCreateSource (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; Insts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find a "source" for some operation, which will be used in one of the operation's operands.</p>


<p>This either selects an instruction in <span class="doxyComputerOutput">Insts</span> or returns some new arbitrary <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>


<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>, definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp">RandomIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#af3c5de240d0947d7b2abb53690cdce7b">llvm::fuzzerop::anyType</a> and <a href="#a47a923aecde90d3d6e66e00bab23318d">findOrCreateSource</a>.</p>


<p>Referenced by <a href="#a47a923aecde90d3d6e66e00bab23318d">findOrCreateSource</a>.</p>

</div>
</div>

### findOrCreateSource() {#a8688fe7e12511bba710a19b4aaf027a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * RandomIRBuilder::findOrCreateSource (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; Insts, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Srcs, <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">fuzzerop::SourcePred</a> Pred, bool allowConstant=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find a "source" for some operation, which will be used in one of the operation's operands.</p>


<p>This either selects an instruction in <span class="doxyComputerOutput">Insts</span> that matches <span class="doxyComputerOutput">Pred</span>, or returns some new <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> that matches <span class="doxyComputerOutput">Pred</span>. The values in <span class="doxyComputerOutput">Srcs</span> should be source operands that have already been selected.</p>


<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp">RandomIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#afc8fc540b727697fd76b8fec899237ccaf1c63139722b2158137dd19c51dfffe9">EndOfValueSource</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a45a66620cecb92a4ffdc36042859c575">findOrCreateGlobalVariable</a>, <a href="#afc8fc540b727697fd76b8fec899237cca0a9098057aeb2f738bff9e305777bb34">FunctionArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp/#a93819e91559afbcefbe8c8d90f0499ed">getDominators</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a161fd4e9fa5367f64c2a4c9e921c3ad3">llvm::BasicBlock::getFirstInsertionPt</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#afc8fc540b727697fd76b8fec899237cca2d9ebfb9a11cc816e7f870a4c62a830c">InstInDominator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6695fbc0cb8edb5aede4af74f2ef95d0">llvm::makeSampler</a>, <a href="#afc8fc540b727697fd76b8fec899237cca51d1677574dfb35d07d7c8101ace27e3">NewConstOrStack</a>, <a href="#a8b569b7040c15c2e2233b3064caa8f4f">newSource</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a01056e939ac37a0452cd1992ff8005ef">Rand</a>, <a href="#afc8fc540b727697fd76b8fec899237ccaeb5c43a6fff8e66f2d4c7b57cd529cb5">SrcFromGlobalVariable</a> and <a href="#afc8fc540b727697fd76b8fec899237cca810b2bd5bed5da88982ee7a2ff81d9e6">SrcFromInstInCurBlock</a>.</p>

</div>
</div>

### findPointer() {#adc37df924da7f46c47c5f04d20d52c3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * RandomIRBuilder::findPointer (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; Insts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>, definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp">RandomIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6695fbc0cb8edb5aede4af74f2ef95d0">llvm::makeSampler</a> and <a href="#a01056e939ac37a0452cd1992ff8005ef">Rand</a>.</p>


<p>Referenced by <a href="#a679d0966b3083f647af785f24936d3d9">newSink</a> and <a href="#a8b569b7040c15c2e2233b3064caa8f4f">newSource</a>.</p>

</div>
</div>

### newSink() {#a679d0966b3083f647af785f24936d3d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * RandomIRBuilder::newSink (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; Insts, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a user for <span class="doxyComputerOutput">V</span> in <span class="doxyComputerOutput">BB</span>.</p>

<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>, definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp">RandomIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a291ac49156942529f159a9ec003cc25f">llvm::ArrayRef&lt; T &gt;::back</a>, <a href="#a50ee598578572bbfadfb9279f650cdd7">createStackMemory</a>, <a href="#adc37df924da7f46c47c5f04d20d52c3e">findPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="#a01056e939ac37a0452cd1992ff8005ef">Rand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af2a9add76255a5e6dc09b1a5f9505f21">llvm::uniform</a>.</p>


<p>Referenced by <a href="#a993771e7c58c60044cbc4c57f689406e">connectToSink</a>.</p>

</div>
</div>

### newSource() {#a8b569b7040c15c2e2233b3064caa8f4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * RandomIRBuilder::newSource (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; Insts, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Srcs, <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">fuzzerop::SourcePred</a> Pred, bool allowConstant=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create some <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> suitable as a source for some operation.</p>

<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp">RandomIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a50ee598578572bbfadfb9279f650cdd7">createStackMemory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#adc37df924da7f46c47c5f04d20d52c3e">findPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a161fd4e9fa5367f64c2a4c9e921c3ad3">llvm::BasicBlock::getFirstInsertionPt</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a2b95175df9fb4eb569d18aec29c82159">KnownTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6695fbc0cb8edb5aede4af74f2ef95d0">llvm::makeSampler</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="#a01056e939ac37a0452cd1992ff8005ef">Rand</a>.</p>


<p>Referenced by <a href="#a8688fe7e12511bba710a19b4aaf027a1">findOrCreateSource</a>.</p>

</div>
</div>

### randomType() {#afde61f758ce6c73015640b4cf6087a76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * RandomIRBuilder::randomType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a uniformly choosen type from <span class="doxyComputerOutput">AllowedTypes</span>.</p>

<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>, definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp">RandomIRBuilder.cpp</a>.</p>


<p>References <a href="#a2b95175df9fb4eb569d18aec29c82159">KnownTypes</a>, <a href="#a01056e939ac37a0452cd1992ff8005ef">Rand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af2a9add76255a5e6dc09b1a5f9505f21">llvm::uniform</a>.</p>


<p>Referenced by <a href="#a272d004d22ae2326fa35628cff91dd69">createFunctionDeclaration</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### KnownTypes {#a2b95175df9fb4eb569d18aec29c82159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Type *, 16&gt; llvm::RandomIRBuilder::KnownTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a45a66620cecb92a4ffdc36042859c575">findOrCreateGlobalVariable</a>, <a href="#a8b569b7040c15c2e2233b3064caa8f4f">newSource</a>, <a href="#a41c54af34530c5d13465a26a69df00d2">RandomIRBuilder</a> and <a href="#afde61f758ce6c73015640b4cf6087a76">randomType</a>.</p>

</div>
</div>

### MaxArgNum {#abcdead6726c7a77ef991c020a0699eaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::RandomIRBuilder::MaxArgNum = 5</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>.</p>


<p>Referenced by <a href="#afe7b90feed41b783460d4bde52f328a9">createFunctionDeclaration</a> and <a href="#a39f27711fdb6185ce6f93a65b2f08cd7">createFunctionDefinition</a>.</p>

</div>
</div>

### MinArgNum {#ae28ff8b1137dd062a8f23d7554631838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::RandomIRBuilder::MinArgNum = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>.</p>


<p>Referenced by <a href="#afe7b90feed41b783460d4bde52f328a9">createFunctionDeclaration</a> and <a href="#a39f27711fdb6185ce6f93a65b2f08cd7">createFunctionDefinition</a>.</p>

</div>
</div>

### MinFunctionNum {#a19a79375c427ba944afadf6c14314cbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::RandomIRBuilder::MinFunctionNum = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>.</p>

</div>
</div>

### Rand {#a01056e939ac37a0452cd1992ff8005ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RandomEngine llvm::RandomIRBuilder::Rand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a993771e7c58c60044cbc4c57f689406e">connectToSink</a>, <a href="#afe7b90feed41b783460d4bde52f328a9">createFunctionDeclaration</a>, <a href="#a39f27711fdb6185ce6f93a65b2f08cd7">createFunctionDefinition</a>, <a href="#a45a66620cecb92a4ffdc36042859c575">findOrCreateGlobalVariable</a>, <a href="#a8688fe7e12511bba710a19b4aaf027a1">findOrCreateSource</a>, <a href="#adc37df924da7f46c47c5f04d20d52c3e">findPointer</a>, <a href="#a679d0966b3083f647af785f24936d3d9">newSink</a>, <a href="#a8b569b7040c15c2e2233b3064caa8f4f">newSource</a>, <a href="#a41c54af34530c5d13465a26a69df00d2">RandomIRBuilder</a> and <a href="#afde61f758ce6c73015640b4cf6087a76">randomType</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/randomirbuilder-h">RandomIRBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp">RandomIRBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
