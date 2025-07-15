---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PruningFunctionCloner` Struct Reference

<p>This is a private class used to implement CloneAndPruneFunctionInto. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{CloneFunction.cpp}::PruningFunctionCloner { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5de55400f4775802364eefb3a1fe20fd">PruningFunctionCloner</a> (Function *newFunc, const Function *oldFunc, ValueToValueMapTy &amp;valueMap, bool moduleLevelChanges, const char *nameSuffix, ClonedCodeInfo *codeInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbf9fd3d3729664031c88766bcefcdf0">cloneInstruction</a> (BasicBlock::const_iterator II)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80ad3b35cf775718eb472f8810e73092">CloneBlock</a> (const BasicBlock *BB, BasicBlock::const_iterator StartingInst, std::vector&lt; const BasicBlock * &gt; &amp;ToClone)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The specified block is found to be reachable, clone it and anything that it can reach. <a href="#a80ad3b35cf775718eb472f8810e73092">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb99e32a6598ff91148ac33beb3ab37a">NewFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a347adb9a3c152d95e3f1081183af80ef">OldFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4cb932ef3340c579cc8a1711aefa564">VMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a857e4c16520963a73e0a49ce96c92a25">ModuleLevelChanges</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a416965fd8e758d893668d26fb9456ec5">NameSuffix</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/clonedcodeinfo">ClonedCodeInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2285be4b5a67dbea156668dc6af5cd46">CodeInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5671451e760be5835595699d5d7b812a">HostFuncIsStrictFP</a></td>
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

<p>This is a private class used to implement CloneAndPruneFunctionInto.</p>

<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/clonefunction-cpp">CloneFunction.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PruningFunctionCloner() {#a5de55400f4775802364eefb3a1fe20fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CloneFunction.cpp}::PruningFunctionCloner::PruningFunctionCloner (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * newFunc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * oldFunc, <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; valueMap, bool moduleLevelChanges, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * nameSuffix, <a href="/web-llvm/docs/api/structs/llvm/clonedcodeinfo">ClonedCodeInfo</a> * codeInfo)</td>
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



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/clonefunction-cpp">CloneFunction.cpp</a>.</p>


<p>References <a href="#a2285be4b5a67dbea156668dc6af5cd46">CodeInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a7477aafbbe989ad35b96fac186d8e9fd">llvm::Function::getAttributes</a>, <a href="#a5671451e760be5835595699d5d7b812a">HostFuncIsStrictFP</a>, <a href="#a857e4c16520963a73e0a49ce96c92a25">ModuleLevelChanges</a>, <a href="#a416965fd8e758d893668d26fb9456ec5">NameSuffix</a>, <a href="#adb99e32a6598ff91148ac33beb3ab37a">NewFunc</a>, <a href="#a347adb9a3c152d95e3f1081183af80ef">OldFunc</a> and <a href="#ac4cb932ef3340c579cc8a1711aefa564">VMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### CloneBlock() {#a80ad3b35cf775718eb472f8810e73092}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PruningFunctionCloner::CloneBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a42a7d51fdde6913db72d098356c2c019">BasicBlock::const_iterator</a> StartingInst, std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; ToClone)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The specified block is found to be reachable, clone it and anything that it can reach.</p>

<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/clonefunction-cpp">CloneFunction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0a4d51e372293abe5e5f6dac133e80a6">llvm::Instruction::clone</a>, <a href="#afbf9fd3d3729664031c88766bcefcdf0">cloneInstruction</a>, <a href="#a2285be4b5a67dbea156668dc6af5cd46">CodeInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab6be6270337c6f7620007555247401ce">llvm::ConstantFoldInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a3ec0b920bf30d0e15bace383192691da">llvm::Function::front</a>, <a href="/web-llvm/docs/api/classes/llvm/blockaddress/#af6e2f535824d8f9b4bf1b1a75e5ab57c">llvm::BlockAddress::get</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#aa832438a6843b75f7d0ef2cc563153f6">llvm::SwitchInst::CaseHandleImpl&lt; SwitchInstT, ConstantIntT, BasicBlockT &gt;::getCaseSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aa286a0f7f5d38488d593bb7ef0ba183e">llvm::BasicBlock::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a858cab21fd29000697171b2f5b4bde31">llvm::BasicBlock::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a1b4bf7c97cdc8159fd73d48063f0b250">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aef9e9fcf4c5dfce90276ca16d91b8e46">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a315f26c899f5ea8a780db4740ba95ef4">llvm::BasicBlock::hasAddressTaken</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ad9d88ae321b98d8a3b7f394977ae6d7f">llvm::Value::hasName</a>, <a href="#a5671451e760be5835595699d5d7b812a">HostFuncIsStrictFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#afcd9d2ea284c4d90541291ff9c47d332">llvm::Instruction::insertInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a627b2f86ac433d829482d5a5a0f50668">llvm::isInstructionTriviallyDead</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#ab571b8358a3a8b6db1327d06bdc5e9f4">llvm::BasicBlock::IsNewDbgInfoFormat</a>, <a href="#a857e4c16520963a73e0a49ce96c92a25">ModuleLevelChanges</a>, <a href="#a416965fd8e758d893668d26fb9456ec5">NameSuffix</a>, <a href="#adb99e32a6598ff91148ac33beb3ab37a">NewFunc</a>, <a href="#a347adb9a3c152d95e3f1081183af80ef">OldFunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7da684e1cead3524bdd9b0d171aad161">llvm::RemapInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77724415203930efd07d7098cb1e437da9a24bd8dba1bef2753bc3f087435ae7f">llvm::RF_NoModuleLevelChanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77724415203930efd07d7098cb1e437da89b60f3b4ad8c1e0ddb9a31b57cb13f9">llvm::RF_None</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a> and <a href="#ac4cb932ef3340c579cc8a1711aefa564">VMap</a>.</p>

</div>
</div>

### cloneInstruction() {#afbf9fd3d3729664031c88766bcefcdf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * PruningFunctionCloner::cloneInstruction (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a42a7d51fdde6913db72d098356c2c019">BasicBlock::const_iterator</a> II)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/clonefunction-cpp">CloneFunction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor/#a4bdf4f1a432b628d6c78a4942244c0fca486b75e3989ba93a6cdc34431291c3b3">llvm::Intrinsic::IITDescriptor::Argument</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#aa04721251be00370fbde6d21f47fed1a">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#a3188a1aa0df768d8f254cd8d8fdeface">llvm::MetadataAsValue::get</a>, <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor/#aaa6dc7ef06077494d709103a44248763">llvm::Intrinsic::IITDescriptor::getArgumentKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8fc51f3b43eb780b3a2bcd8ef027288d">llvm::getConstrainedIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa68a2d2c06a10b1e5a5bc778a107c0ba">llvm::CmpInst::getPredicateName</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a3dbd4447f1241859563534da87edfa1f">llvm::Intrinsic::hasConstrainedFPRoundingModeOperand</a>, <a href="#a5671451e760be5835595699d5d7b812a">HostFuncIsStrictFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor/#a03351835850db3fc6d4f4430fc35b481">llvm::Intrinsic::IITDescriptor::Kind</a>, <a href="#adb99e32a6598ff91148ac33beb3ab37a">NewFunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a35fedf4db6d756bd82501607f93c1e79aab5fb650050f184fa7c19c26abde5226">llvm::Intrinsic::not_intrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor/#a4bdf4f1a432b628d6c78a4942244c0fca0f4d1d546be9b2dcd98447aa2025c865">llvm::Intrinsic::IITDescriptor::SameVecWidthArgument</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a80ad3b35cf775718eb472f8810e73092">CloneBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CodeInfo {#a2285be4b5a67dbea156668dc6af5cd46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClonedCodeInfo* anonymous{CloneFunction.cpp}::PruningFunctionCloner::CodeInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/clonefunction-cpp">CloneFunction.cpp</a>.</p>


<p>Referenced by <a href="#a80ad3b35cf775718eb472f8810e73092">CloneBlock</a> and <a href="#a5de55400f4775802364eefb3a1fe20fd">PruningFunctionCloner</a>.</p>

</div>
</div>

### HostFuncIsStrictFP {#a5671451e760be5835595699d5d7b812a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CloneFunction.cpp}::PruningFunctionCloner::HostFuncIsStrictFP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/clonefunction-cpp">CloneFunction.cpp</a>.</p>


<p>Referenced by <a href="#a80ad3b35cf775718eb472f8810e73092">CloneBlock</a>, <a href="#afbf9fd3d3729664031c88766bcefcdf0">cloneInstruction</a> and <a href="#a5de55400f4775802364eefb3a1fe20fd">PruningFunctionCloner</a>.</p>

</div>
</div>

### ModuleLevelChanges {#a857e4c16520963a73e0a49ce96c92a25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CloneFunction.cpp}::PruningFunctionCloner::ModuleLevelChanges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/clonefunction-cpp">CloneFunction.cpp</a>.</p>


<p>Referenced by <a href="#a80ad3b35cf775718eb472f8810e73092">CloneBlock</a> and <a href="#a5de55400f4775802364eefb3a1fe20fd">PruningFunctionCloner</a>.</p>

</div>
</div>

### NameSuffix {#a416965fd8e758d893668d26fb9456ec5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* anonymous{CloneFunction.cpp}::PruningFunctionCloner::NameSuffix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/clonefunction-cpp">CloneFunction.cpp</a>.</p>


<p>Referenced by <a href="#a80ad3b35cf775718eb472f8810e73092">CloneBlock</a> and <a href="#a5de55400f4775802364eefb3a1fe20fd">PruningFunctionCloner</a>.</p>

</div>
</div>

### NewFunc {#adb99e32a6598ff91148ac33beb3ab37a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* anonymous{CloneFunction.cpp}::PruningFunctionCloner::NewFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/clonefunction-cpp">CloneFunction.cpp</a>.</p>


<p>Referenced by <a href="#a80ad3b35cf775718eb472f8810e73092">CloneBlock</a>, <a href="#afbf9fd3d3729664031c88766bcefcdf0">cloneInstruction</a> and <a href="#a5de55400f4775802364eefb3a1fe20fd">PruningFunctionCloner</a>.</p>

</div>
</div>

### OldFunc {#a347adb9a3c152d95e3f1081183af80ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function* anonymous{CloneFunction.cpp}::PruningFunctionCloner::OldFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/clonefunction-cpp">CloneFunction.cpp</a>.</p>


<p>Referenced by <a href="#a80ad3b35cf775718eb472f8810e73092">CloneBlock</a> and <a href="#a5de55400f4775802364eefb3a1fe20fd">PruningFunctionCloner</a>.</p>

</div>
</div>

### VMap {#ac4cb932ef3340c579cc8a1711aefa564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueToValueMapTy&amp; anonymous{CloneFunction.cpp}::PruningFunctionCloner::VMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/clonefunction-cpp">CloneFunction.cpp</a>.</p>


<p>Referenced by <a href="#a80ad3b35cf775718eb472f8810e73092">CloneBlock</a> and <a href="#a5de55400f4775802364eefb3a1fe20fd">PruningFunctionCloner</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/clonefunction-cpp">CloneFunction.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
