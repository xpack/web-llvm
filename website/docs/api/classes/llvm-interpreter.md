---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/interpreter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Interpreter` Class



## Declaration

<div class="doxyDeclaration">
class llvm::Interpreter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">ExecutionEngine/Interpreter/Interpreter.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract interface for implementation execution of LLVM modules, designed to support both interpreter and just-in-time (JIT) compiler implementations. <a href="/web-llvm/docs/api/classes/llvm/executionengine/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instvisitor">InstVisitor&lt;SubClass, RetTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for instruction visitors. <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a742cab06ece0dfaa5fb512243e616bcc">Interpreter</a> (std::unique_ptr&lt; Module &gt; M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a176fa92633c4d8b9a610471772448583">~Interpreter</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a508808d7cffb7f4416ddfdc8eb76dd36">runAtExitHandlers</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runAtExitHandlers - Run any functions registered by the program's calls to atexit(3), which we intercept and store in AtExitHandlers. <a href="#a508808d7cffb7f4416ddfdc8eb76dd36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92bee9b9d1c7a9396f6d32bae5f7a563">runFunction</a> (Function *F, ArrayRef&lt; GenericValue &gt; ArgValues) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>run - Start execution with the specified function and arguments. <a href="#a92bee9b9d1c7a9396f6d32bae5f7a563">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a597b2f195f12edb6302f7c34fdeca405">getPointerToNamedFunction</a> (StringRef Name, bool AbortOnFailure=true) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPointerToNamedFunction - This method returns the address of the specified function by using the dlsym function call. <a href="#a597b2f195f12edb6302f7c34fdeca405">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e36a63781989accf846f2e78f510d33">callFunction</a> (Function *F, ArrayRef&lt; GenericValue &gt; ArgVals)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b9367cdd0a810a103f13bb649cf697f">run</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c91ee4a2eb25c80ee8795a57afddf5e">visitReturnInst</a> (ReturnInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51022186d1e4b04b893bc5d76c5da587">visitBranchInst</a> (BranchInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a562abb53521e5d5930bb086374da2628">visitSwitchInst</a> (SwitchInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ff48dd8f0dc888cae0759083a0759f0">visitIndirectBrInst</a> (IndirectBrInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b2b94ef14cca14e32542e221b3303f5">visitUnaryOperator</a> (UnaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad931a9b6a516452142c12592afe8968d">visitBinaryOperator</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a382f8209946dc96b1cb2a30589c06f1c">visitICmpInst</a> (ICmpInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06c639b057f4b02e4ea274c3e059c95f">visitFCmpInst</a> (FCmpInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ce4069e58167789a23552d4cab66114">visitAllocaInst</a> (AllocaInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d9427c6aacb65d962854ea8bfe5c23b">visitLoadInst</a> (LoadInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a552ef98be3146773854e33c8548d202b">visitStoreInst</a> (StoreInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e0b0ae6ad80cac2ce881d61147d25ec">visitGetElementPtrInst</a> (GetElementPtrInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bff26390aaf227ab24fbf78fc040965">visitPHINode</a> (PHINode &amp;PN)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6187006e0146e42ba68ea7b0a36f8612">visitTruncInst</a> (TruncInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2cb4303f15332b4ecb8ae8cd9e2f2d0">visitZExtInst</a> (ZExtInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac55fd7a63e2f2beeb7ed4ecc05305c5a">visitSExtInst</a> (SExtInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6c27060516049d30db09aab83ce8e2a">visitFPTruncInst</a> (FPTruncInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d6f9c796d975ed192c0b004feb0d181">visitFPExtInst</a> (FPExtInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a398c50e793136ad369479408206bb4a8">visitUIToFPInst</a> (UIToFPInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05cde965fd9be8eab699f1fbfa661b9b">visitSIToFPInst</a> (SIToFPInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70ebc74064b9abcb424d33b3e8a1e95c">visitFPToUIInst</a> (FPToUIInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8faf6742ce6199babb1b5072ae40da4">visitFPToSIInst</a> (FPToSIInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09f6cc56fdb2d7b2ea817665147c7d8d">visitPtrToIntInst</a> (PtrToIntInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e92cc7536cb0d667a0225a25810af08">visitIntToPtrInst</a> (IntToPtrInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd8ab3044cbed9d96925639c54ac89cb">visitBitCastInst</a> (BitCastInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1df708fd8aa2d183afcafa641e96ccc1">visitSelectInst</a> (SelectInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab12c231bbdababc7fddf09a0c2825ae9">visitVAStartInst</a> (VAStartInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6139a7d5a94867405dbb9fe51a46c89c">visitVAEndInst</a> (VAEndInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac2392669a11cf5fc17003be773c7d7">visitVACopyInst</a> (VACopyInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9010576cc8633859d712499ff9d895f">visitIntrinsicInst</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1975c911e3c868b234f76251d70e676a">visitCallBase</a> (CallBase &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a359dfb4c781e8f18bf3b2a6cad1aee8f">visitUnreachableInst</a> (UnreachableInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaccb8a2292bd0d7fecec1c16d177cd3">visitShl</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39600b19581391dccc382a54d6b79be2">visitLShr</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac56427a25d7626e4b748e8fbf1fdf9bb">visitAShr</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54b80362711a465bb0430383cbf50837">visitVAArgInst</a> (VAArgInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582723c984e76cf38ba855426a60a235">visitExtractElementInst</a> (ExtractElementInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86b39d8533c9fd7c518a6ebc3456e6d1">visitInsertElementInst</a> (InsertElementInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1023db1599beb0118dd1ffe91d85f172">visitShuffleVectorInst</a> (ShuffleVectorInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a555a1a7ce9538b817e65c911ed7da13a">visitExtractValueInst</a> (ExtractValueInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47c795f3e83fbfbd37c1b890c850dbe7">visitInsertValueInst</a> (InsertValueInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affbc0703b97afc6f7691ebf2f7cf001a">visitInstruction</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac90cfcdb0c2a25c0969106ebff1be9f8">callExternalFunction</a> (Function *F, ArrayRef&lt; GenericValue &gt; ArgVals)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27a48d828a2227311270264ae0e78f8c">exitCalled</a> (GenericValue GV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14691519e5b8fc508cabd95ec94d98d2">addAtExitHandler</a> (Function *F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dfe034bb20ec240394573379e91996f">getFirstVarArg</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cbe23bf8bda80a6b273843a375bf902">executeGEPOperation</a> (Value *Ptr, gep_type_iterator I, gep_type_iterator E, ExecutionContext &amp;SF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c066a0b76b8f96080cd7099377d3a5f">SwitchToNewBasicBlock</a> (BasicBlock *Dest, ExecutionContext &amp;SF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af27195bc8f3f35515473473fe296dc57">getPointerToFunction</a> (Function *F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPointerToFunction - The different EE's represent function bodies in different ways. <a href="#af27195bc8f3f35515473473fe296dc57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0276739c27d919b7cbcd1e6459b694e4">initializeExecutionEngine</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b4945b6acaa315b3be4f1b19c387258">initializeExternalFunctions</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a060b3764fd88225c5aa71dc356928775">getConstantExprValue</a> (ConstantExpr *CE, ExecutionContext &amp;SF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8d5d1947dacc3e9bff6ef432138b6f5">getOperandValue</a> (Value *V, ExecutionContext &amp;SF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb17d961f05a3d2626183ba52505a317">executeTruncInst</a> (Value *SrcVal, Type *DstTy, ExecutionContext &amp;SF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a822e2c218e54b71cc338cbe9f08a9eab">executeSExtInst</a> (Value *SrcVal, Type *DstTy, ExecutionContext &amp;SF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79c82f42606d04a31e8869c671d86e7a">executeZExtInst</a> (Value *SrcVal, Type *DstTy, ExecutionContext &amp;SF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8a6d0fc2280e0da66805c80c7f088a2">executeFPTruncInst</a> (Value *SrcVal, Type *DstTy, ExecutionContext &amp;SF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5a9bea077fad97c08d3c89f8d85cad3">executeFPExtInst</a> (Value *SrcVal, Type *DstTy, ExecutionContext &amp;SF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a6bc8a94e2b143bb0d5bacf58001d8">executeFPToUIInst</a> (Value *SrcVal, Type *DstTy, ExecutionContext &amp;SF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9a37c4e27c8c3ff1979ca6855dfcfa2">executeFPToSIInst</a> (Value *SrcVal, Type *DstTy, ExecutionContext &amp;SF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15aa20eae9f02b9d38694b908122d2b6">executeUIToFPInst</a> (Value *SrcVal, Type *DstTy, ExecutionContext &amp;SF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87f8132d128f1bce5dbc80a6a4b1efba">executeSIToFPInst</a> (Value *SrcVal, Type *DstTy, ExecutionContext &amp;SF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a596ab479cadc8d1beb7dd240609417d2">executePtrToIntInst</a> (Value *SrcVal, Type *DstTy, ExecutionContext &amp;SF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7579f49a43a80a96379d4e24e437871e">executeIntToPtrInst</a> (Value *SrcVal, Type *DstTy, ExecutionContext &amp;SF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dba8e96b0d79e8c9c1ecb2033dbaee9">executeBitCastInst</a> (Value *SrcVal, Type *DstTy, ExecutionContext &amp;SF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01cc29d4e94b347c0fc8271e334dccab">popStackAndReturnValueToCaller</a> (Type *RetTy, GenericValue Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pop the last stack frame off of ECStack and then copy the result back into the result variable if we are not returning void. <a href="#a01cc29d4e94b347c0fc8271e334dccab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b79c8c03637d0940fffdaec876357f">ExitValue</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering">IntrinsicLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6380a88f849899e1cd21b1452dd29e6f">IL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ce643b974cd057e6cbe0ba537f175a1">ECStack</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a375d2940c0f6ca8fa50167fe1bbefc1d">AtExitHandlers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a152334c0d8a032d91d4c90b5197cb902">Register</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec4c8f10c02e58107d0372b5de57b819">create</a> (std::unique_ptr&lt; Module &gt; M, std::string *ErrorStr=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an interpreter <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a>. <a href="#aec4c8f10c02e58107d0372b5de57b819">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Interpreter() {#a742cab06ece0dfaa5fb512243e616bcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Interpreter::Interpreter (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; M)</td>
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



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-cpp">Interpreter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/executionengine/#aca88a09e03611e624c1b6ac0aad41ce3">llvm::ExecutionEngine::emitGlobals</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a92eef8691cfbe4446ee15d34258c3185">llvm::ExecutionEngine::ExecutionEngine</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a221f82626a9fd6d8dc7c76e097940b07">llvm::ExecutionEngine::getDataLayout</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#aec4c8f10c02e58107d0372b5de57b819">create</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Interpreter() {#a176fa92633c4d8b9a610471772448583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Interpreter::~Interpreter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-cpp">Interpreter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAtExitHandler() {#a14691519e5b8fc508cabd95ec94d98d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Interpreter::addAtExitHandler (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### callExternalFunction() {#ac90cfcdb0c2a25c0969106ebff1be9f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue Interpreter::callExternalFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &gt; ArgVals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp">ExternalFunctions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a221f82626a9fd6d8dc7c76e097940b07">llvm::ExecutionEngine::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a29b4671f69facc701332f9510ca436aa">llvm::ExecutionEngine::getPointerToGlobalIfAvailable</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp/#a290f71a162bc8e8fd0bc72b222c029fc">lookupFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary/#ae003d16a33e81b88943d3e3aa179fcc4">llvm::sys::DynamicLibrary::SearchForAddressOfSymbol</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp/#a5f422dfbc738ed5acebbbff28996ba95">TheInterpreter</a>.</p>


<p>Referenced by <a href="#a7e36a63781989accf846f2e78f510d33">callFunction</a>.</p>

</div>
</div>

### callFunction() {#a7e36a63781989accf846f2e78f510d33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::callFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &gt; ArgVals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 2037 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="#ac90cfcdb0c2a25c0969106ebff1be9f8">callExternalFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/executioncontext/#ad73bc5948f16852e64c40cd342e5f889">llvm::ExecutionContext::CurBB</a>, <a href="/web-llvm/docs/api/structs/llvm/executioncontext/#ab239c684fe957cb5de9b212866b4a5e1">llvm::ExecutionContext::CurFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/executioncontext/#a82698df4906274f624ea4c6d161e8ad0">llvm::ExecutionContext::CurInst</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/structs/llvm/executioncontext/#a94db05d568d855979a89805b91b1ebb5">llvm::ExecutionContext::VarArgs</a>.</p>


<p>Referenced by <a href="#a508808d7cffb7f4416ddfdc8eb76dd36">runAtExitHandlers</a>, <a href="#a92bee9b9d1c7a9396f6d32bae5f7a563">runFunction</a> and <a href="#a1975c911e3c868b234f76251d70e676a">visitCallBase</a>.</p>

</div>
</div>

### exitCalled() {#a27a48d828a2227311270264ae0e78f8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::exitCalled (<a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 839 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>, <a href="#a508808d7cffb7f4416ddfdc8eb76dd36">runAtExitHandlers</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a2ed912a28808268e35bd58e8f11251aa">llvm::APInt::zextOrTrunc</a>.</p>

</div>
</div>

### getFirstVarArg() {#a4dfe034bb20ec240394573379e91996f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue * llvm::Interpreter::getFirstVarArg ()</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>.</p>

</div>
</div>

### getPointerToNamedFunction() {#a597b2f195f12edb6302f7c34fdeca405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::Interpreter::getPointerToNamedFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool AbortOnFailure=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>getPointerToNamedFunction - This method returns the address of the specified function by using the dlsym function call.</p>


<p>As such it is only useful for resolving library symbols, not code generated symbols.</p>


<p>If AbortOnFailure is false and no function with the given name is found, this function silently returns a null pointer. Otherwise, it prints a message to stderr and aborts.</p>


<p>This function is deprecated for the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> execution engine.</p>


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>.</p>

</div>
</div>

### run() {#a4b9367cdd0a810a103f13bb649cf697f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 2074 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a6352e72d11377a9c62f24434ae869bf0">llvm::InstVisitor&lt; Interpreter &gt;::visit</a>.</p>


<p>Referenced by <a href="#a508808d7cffb7f4416ddfdc8eb76dd36">runAtExitHandlers</a> and <a href="#a92bee9b9d1c7a9396f6d32bae5f7a563">runFunction</a>.</p>

</div>
</div>

### runAtExitHandlers() {#a508808d7cffb7f4416ddfdc8eb76dd36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::runAtExitHandlers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>runAtExitHandlers - Run any functions registered by the program's calls to atexit(3), which we intercept and store in AtExitHandlers.</p>

<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-cpp">Interpreter.cpp</a>.</p>


<p>References <a href="#a7e36a63781989accf846f2e78f510d33">callFunction</a> and <a href="#a4b9367cdd0a810a103f13bb649cf697f">run</a>.</p>


<p>Referenced by <a href="#a27a48d828a2227311270264ae0e78f8c">exitCalled</a>.</p>

</div>
</div>

### runFunction() {#a92bee9b9d1c7a9396f6d32bae5f7a563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue Interpreter::runFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &gt; ArgValues)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>run - Start execution with the specified function and arguments.</p>

<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-cpp">Interpreter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7e36a63781989accf846f2e78f510d33">callFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a4b9367cdd0a810a103f13bb649cf697f">run</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>.</p>

</div>
</div>

### visitAllocaInst() {#a1ce4069e58167789a23552d4cab66114}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitAllocaInst (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 981 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a221f82626a9fd6d8dc7c76e097940b07">llvm::ExecutionEngine::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#aa48b3b7e554b44f4e513d5dd8d9f9343">llvm::DataLayout::getTypeAllocSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77905b5e34e8754df1ed4051e0ad9d1a">llvm::PTOGV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bb931812d78f470d4ca775ac8b88e61">llvm::safe_malloc</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitAShr() {#ac56427a25d7626e4b748e8fbf1fdf9bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitAShr (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1204 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#aa46325f5b23e83bb49e497cfce2f1b89">llvm::GenericValue::AggregateVal</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab6006923d1a3139d70abc8f6552a7960">llvm::APInt::ashr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#ab9de4ecd5d07314b56d5a0d1fad6f6fc">getShiftAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitBinaryOperator() {#ad931a9b6a516452142c12592afe8968d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitBinaryOperator (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 700 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#aa46325f5b23e83bb49e497cfce2f1b89">llvm::GenericValue::AggregateVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a46d49ce365aa2b814bb9b25f332757df">executeFAddInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a2dcd6bdc8271cf5a7a963933e7a18c66">executeFDivInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#af8cce347f31a3057d0d8a61a4ade64e4">executeFMulInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#ab2b2089ccf34571233f731db1c299b85">executeFRemInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a1ba822e8185395389ff297d86335506b">executeFSubInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a1ecc89a903a39fa91e98829c7a768fb9">FLOAT_VECTOR_OP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a772ad021946611dccd72512addffaa8e">INTEGER_VECTOR_FUNCTION</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a35d25f42428e57ca9b363fe5c8ea2b74">INTEGER_VECTOR_OPERATION</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a71f7f6e3a4774296efc7274196a74793">llvm::APInt::sdiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac131d830427393332e440e1d6e3013b6">llvm::APInt::srem</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a05d674becc60ba4ef8cd4dd4d38ac27a">llvm::APInt::udiv</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a4e3a2187cacdec76028617a403c47d89">llvm::APInt::urem</a>.</p>

</div>
</div>

### visitBitCastInst() {#abd8ab3044cbed9d96925639c54ac89cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitBitCastInst (<a href="/web-llvm/docs/api/classes/llvm/bitcastinst">BitCastInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1721 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitBranchInst() {#a51022186d1e4b04b893bc5d76c5da587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitBranchInst (<a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 900 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitCallBase() {#a1975c911e3c868b234f76251d70e676a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitCallBase (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1122 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/executioncontext/#a2f68bec9366af2e5141fd30521213e01">llvm::ExecutionContext::Caller</a>, <a href="#a7e36a63781989accf846f2e78f510d33">callFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3ff7c50d6ac50925243afaa521aa36a">llvm::GVTOP</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitExtractElementInst() {#a582723c984e76cf38ba855426a60a235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitExtractElementInst (<a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1758 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#aa46325f5b23e83bb49e497cfce2f1b89">llvm::GenericValue::AggregateVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a9810b36b4c4c17901d491f5aac030623">llvm::GenericValue::DoubleVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a5160197592bd1fc5c8cc81cd803e0629">llvm::GenericValue::FloatVal</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitExtractValueInst() {#a555a1a7ce9538b817e65c911ed7da13a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitExtractValueInst (<a href="/web-llvm/docs/api/classes/llvm/extractvalueinst">ExtractValueInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1890 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#aa46325f5b23e83bb49e497cfce2f1b89">llvm::GenericValue::AggregateVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa2989d3024a84b4dda9d77419b1648554">llvm::Type::ArrayTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a9810b36b4c4c17901d491f5aac030623">llvm::GenericValue::DoubleVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa98aa825426dd4de2d19a3de9983a2d5d">llvm::Type::FixedVectorTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a5160197592bd1fc5c8cc81cd803e0629">llvm::GenericValue::FloatVal</a>, <a href="/web-llvm/docs/api/classes/llvm/extractvalueinst/#a32a446b2a178bcd482521e3d273beeaf">llvm::ExtractValueInst::getIndexedType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac7b0ed5c6d30bad74769c6e87ab0edb8">llvm::Type::getTypeID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaae68df805bc15b023748c2a78b80563ff">llvm::Type::PointerTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a23f8c75218aea0cfcfe0f3e4223d3b02">llvm::GenericValue::PointerVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6188e4e2fb839d904debf0cbe7fc11f6">llvm::Type::ScalableVectorTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa812a573d23fbb37aacd025e2a0588156">llvm::Type::StructTyID</a>.</p>

</div>
</div>

### visitFCmpInst() {#a06c639b057f4b02e4ea274c3e059c95f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitFCmpInst (<a href="/web-llvm/docs/api/classes/llvm/fcmpinst">FCmpInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 665 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a9dbb09eb50c3c8609ff46bf6add8c2ee">executeFCMP_BOOL</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a53a0f3f250d2ad3ab79b96b2d7b12527">executeFCMP_OEQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a0473b23318c3e81617e969e5d34b6c65">executeFCMP_OGE</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a35b4530505dca524726752e6a20883e1">executeFCMP_OGT</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a687130dc367d99c69d3c7c611169d6b6">executeFCMP_OLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a88f7c3a00a5fc3920f305094bf381798">executeFCMP_OLT</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#ad84c8e547a3add8cc581d6fbec1ea5cb">executeFCMP_ONE</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a9a1b97d63e55b8f92d4d2e5468fb7cf6">executeFCMP_ORD</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#adc7da546e2638a58b40f8236f43e91c0">executeFCMP_UEQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a03c3b9faab810a8a847dee1c1024db92">executeFCMP_UGE</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aed4e397ad7ab2921318cf474e0b8320e">executeFCMP_UGT</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a1ca29b39b2e1fbf95a750c13d2035f61">executeFCMP_ULE</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a8f7dd1881517874a4850e4d1cb970a66">executeFCMP_ULT</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a42019dfdf44962124bfc3ed1e7dda826">executeFCMP_UNE</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a4ecb49f4c2b5b1041e0ad44dc213f5b0">executeFCMP_UNO</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bae9c013750fff3023001d7e3af8df2d6d">llvm::CmpInst::FCMP_FALSE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba024db78a5ed74f64666f3ca4955e6eca">llvm::CmpInst::FCMP_OEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">llvm::CmpInst::FCMP_OGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">llvm::CmpInst::FCMP_OGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a">llvm::CmpInst::FCMP_OLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">llvm::CmpInst::FCMP_OLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba8a80b27ca29fe2076b9bbdee02c65464">llvm::CmpInst::FCMP_ONE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">llvm::CmpInst::FCMP_ORD</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba0a33c71e3c5e8f128ca47539a85962f5">llvm::CmpInst::FCMP_TRUE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba919643b83ce3c9af2e4296ed5e413a1f">llvm::CmpInst::FCMP_UEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344">llvm::CmpInst::FCMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba959268ceeae23abe5c9ad9e895669d0c">llvm::CmpInst::FCMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba396dda2571cd3c575f1d9cb44dc2cc09">llvm::CmpInst::FCMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474">llvm::CmpInst::FCMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad601460c9371d0f0ada5ae006bdba2bd">llvm::CmpInst::FCMP_UNE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">llvm::CmpInst::FCMP_UNO</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitFPExtInst() {#a9d6f9c796d975ed192c0b004feb0d181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitFPExtInst (<a href="/web-llvm/docs/api/classes/llvm/fpextinst">FPExtInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1686 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitFPToSIInst() {#ae8faf6742ce6199babb1b5072ae40da4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitFPToSIInst (<a href="/web-llvm/docs/api/classes/llvm/fptosiinst">FPToSIInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1706 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitFPToUIInst() {#a70ebc74064b9abcb424d33b3e8a1e95c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitFPToUIInst (<a href="/web-llvm/docs/api/classes/llvm/fptouiinst">FPToUIInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1701 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitFPTruncInst() {#ad6c27060516049d30db09aab83ce8e2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitFPTruncInst (<a href="/web-llvm/docs/api/classes/llvm/fptruncinst">FPTruncInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1681 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitGetElementPtrInst() {#a7e0b0ae6ad80cac2ce881d61147d25ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitGetElementPtrInst (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1051 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac828b9b52935f87659a4adf237f820a3">llvm::gep_type_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a43c6ebb4fd35ebd815d66a2df4eed0b9">llvm::gep_type_end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitICmpInst() {#a382f8209946dc96b1cb2a30589c06f1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitICmpInst (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#ae7670586abfe3aed532c70997b0d4424">executeICMP_EQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a908bbe72c94bd551dcbd394a8817c2d7">executeICMP_NE</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a34085170841ce0d5eb1687c8cefd9234">executeICMP_SGE</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a2d592b5002f3855f9fa9f486a55087b2">executeICMP_SGT</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a2f5002419dfa68ad8a3be90f9e591a1d">executeICMP_SLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a0b809b83b0c40ad9dcb8bbd8ea4591a7">executeICMP_SLT</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a0c84af3c90fae95a8ea40029ddceb3b0">executeICMP_UGE</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a072f11ea1ef8304f96662d1f385f5ad3">executeICMP_UGT</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a826efd0d1d8bbe269183e89ea5514e2f">executeICMP_ULE</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#af9477a1cada9e071e78a65a75f09247b">executeICMP_ULT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitIndirectBrInst() {#a3ff48dd8f0dc888cae0759083a0759f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitIndirectBrInst (<a href="/web-llvm/docs/api/classes/llvm/indirectbrinst">IndirectBrInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 932 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac3ff7c50d6ac50925243afaa521aa36a">llvm::GVTOP</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitInsertElementInst() {#a86b39d8533c9fd7c518a6ebc3456e6d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitInsertElementInst (<a href="/web-llvm/docs/api/classes/llvm/insertelementinst">InsertElementInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1791 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#aa46325f5b23e83bb49e497cfce2f1b89">llvm::GenericValue::AggregateVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a9810b36b4c4c17901d491f5aac030623">llvm::GenericValue::DoubleVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a5160197592bd1fc5c8cc81cd803e0629">llvm::GenericValue::FloatVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac7b0ed5c6d30bad74769c6e87ab0edb8">llvm::Type::getTypeID</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitInsertValueInst() {#a47c795f3e83fbfbd37c1b890c850dbe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitInsertValueInst (<a href="/web-llvm/docs/api/classes/llvm/insertvalueinst">InsertValueInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1933 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#aa46325f5b23e83bb49e497cfce2f1b89">llvm::GenericValue::AggregateVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa2989d3024a84b4dda9d77419b1648554">llvm::Type::ArrayTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a9810b36b4c4c17901d491f5aac030623">llvm::GenericValue::DoubleVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa98aa825426dd4de2d19a3de9983a2d5d">llvm::Type::FixedVectorTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a5160197592bd1fc5c8cc81cd803e0629">llvm::GenericValue::FloatVal</a>, <a href="/web-llvm/docs/api/classes/llvm/extractvalueinst/#a32a446b2a178bcd482521e3d273beeaf">llvm::ExtractValueInst::getIndexedType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac7b0ed5c6d30bad74769c6e87ab0edb8">llvm::Type::getTypeID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaae68df805bc15b023748c2a78b80563ff">llvm::Type::PointerTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a23f8c75218aea0cfcfe0f3e4223d3b02">llvm::GenericValue::PointerVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6188e4e2fb839d904debf0cbe7fc11f6">llvm::Type::ScalableVectorTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa812a573d23fbb37aacd025e2a0588156">llvm::Type::StructTyID</a>.</p>

</div>
</div>

### visitInstruction() {#affbc0703b97afc6f7691ebf2f7cf001a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Interpreter::visitInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### visitIntrinsicInst() {#ae9010576cc8633859d712499ff9d895f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitIntrinsicInst (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1099 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitIntToPtrInst() {#a2e92cc7536cb0d667a0225a25810af08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitIntToPtrInst (<a href="/web-llvm/docs/api/classes/llvm/inttoptrinst">IntToPtrInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1716 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitLoadInst() {#a7d9427c6aacb65d962854ea8bfe5c23b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitLoadInst (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1057 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3ff7c50d6ac50925243afaa521aa36a">llvm::GVTOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#adec0e730f80de19f31127faedf39008c">llvm::ExecutionEngine::LoadValueFromMemory</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a748be8883cec545a336485a26d8fc097">PrintVolatile</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitLShr() {#a39600b19581391dccc382a54d6b79be2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitLShr (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1177 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#aa46325f5b23e83bb49e497cfce2f1b89">llvm::GenericValue::AggregateVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#ab9de4ecd5d07314b56d5a0d1fad6f6fc">getShiftAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af34549c39d6f741fbdaf9a795aa306e9">llvm::APInt::lshr</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitPHINode() {#a0bff26390aaf227ab24fbf78fc040965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Interpreter::visitPHINode (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> &amp; PN)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### visitPtrToIntInst() {#a09f6cc56fdb2d7b2ea817665147c7d8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitPtrToIntInst (<a href="/web-llvm/docs/api/classes/llvm/ptrtointinst">PtrToIntInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1711 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitReturnInst() {#a2c91ee4a2eb25c80ee8795a57afddf5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitReturnInst (<a href="/web-llvm/docs/api/classes/llvm/returninst">ReturnInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 882 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitSelectInst() {#a1df708fd8aa2d183afcafa641e96ccc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitSelectInst (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 825 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a4f71481be990c1361b473eea6c18df11">executeSelectInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitSExtInst() {#ac55fd7a63e2f2beeb7ed4ecc05305c5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitSExtInst (<a href="/web-llvm/docs/api/classes/llvm/sextinst">SExtInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1671 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitShl() {#adaccb8a2292bd0d7fecec1c16d177cd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitShl (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1150 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#aa46325f5b23e83bb49e497cfce2f1b89">llvm::GenericValue::AggregateVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#ab9de4ecd5d07314b56d5a0d1fad6f6fc">getShiftAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#acb9c55b6986369948507ca5241b4e411">llvm::APInt::shl</a>.</p>

</div>
</div>

### visitShuffleVectorInst() {#a1023db1599beb0118dd1ffe91d85f172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitShuffleVectorInst (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1823 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#aa46325f5b23e83bb49e497cfce2f1b89">llvm::GenericValue::AggregateVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac7b0ed5c6d30bad74769c6e87ab0edb8">llvm::Type::getTypeID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitSIToFPInst() {#a05cde965fd9be8eab699f1fbfa661b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitSIToFPInst (<a href="/web-llvm/docs/api/classes/llvm/sitofpinst">SIToFPInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1696 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitStoreInst() {#a552ef98be3146773854e33c8548d202b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitStoreInst (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1068 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3ff7c50d6ac50925243afaa521aa36a">llvm::GVTOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a748be8883cec545a336485a26d8fc097">PrintVolatile</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a08ed33d3b3f8b9e21167918d5de40014">llvm::ExecutionEngine::StoreValueToMemory</a>.</p>

</div>
</div>

### visitSwitchInst() {#a562abb53521e5d5930bb086374da2628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitSwitchInst (<a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 913 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#ae7670586abfe3aed532c70997b0d4424">executeICMP_EQ</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitTruncInst() {#a6187006e0146e42ba68ea7b0a36f8612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitTruncInst (<a href="/web-llvm/docs/api/classes/llvm/truncinst">TruncInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1666 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitUIToFPInst() {#a398c50e793136ad369479408206bb4a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitUIToFPInst (<a href="/web-llvm/docs/api/classes/llvm/uitofpinst">UIToFPInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1691 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitUnaryOperator() {#a8b2b94ef14cca14e32542e221b3303f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitUnaryOperator (<a href="/web-llvm/docs/api/classes/llvm/unaryoperator">UnaryOperator</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a6afbe60697d1b461028d733f1380e22d">executeFNegInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitUnreachableInst() {#a359dfb4c781e8f18bf3b2a6cad1aee8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitUnreachableInst (<a href="/web-llvm/docs/api/classes/llvm/unreachableinst">UnreachableInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 896 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### visitVAArgInst() {#a54b80362711a465bb0430383cbf50837}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitVAArgInst (<a href="/web-llvm/docs/api/classes/llvm/vaarginst">VAArgInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1729 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/intpair/#aa000019e123176bd9c6a0654ece313fe">llvm::GenericValue::IntPair::first</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">Float</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#ab17082b5668396b9c47660397a72c0e6">IMPLEMENT_VAARG</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/intpair/#acc5ab9c71b8081bb8c5b9ef4bf909468">llvm::GenericValue::IntPair::second</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a> and <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a7495c89b67b21446ed9951586a17b345">llvm::GenericValue::UIntPairVal</a>.</p>

</div>
</div>

### visitVACopyInst() {#a5ac2392669a11cf5fc17003be773c7d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitVACopyInst (<a href="/web-llvm/docs/api/classes/llvm/vacopyinst">VACopyInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1094 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

### visitVAEndInst() {#a6139a7d5a94867405dbb9fe51a46c89c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitVAEndInst (<a href="/web-llvm/docs/api/classes/llvm/vaendinst">VAEndInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1090 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitVAStartInst() {#ab12c231bbdababc7fddf09a0c2825ae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitVAStartInst (<a href="/web-llvm/docs/api/classes/llvm/vastartinst">VAStartInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1082 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericvalue/intpair/#aa000019e123176bd9c6a0654ece313fe">llvm::GenericValue::IntPair::first</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/intpair/#acc5ab9c71b8081bb8c5b9ef4bf909468">llvm::GenericValue::IntPair::second</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a> and <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#a7495c89b67b21446ed9951586a17b345">llvm::GenericValue::UIntPairVal</a>.</p>

</div>
</div>

### visitZExtInst() {#ae2cb4303f15332b4ecb8ae8cd9e2f2d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::visitZExtInst (<a href="/web-llvm/docs/api/classes/llvm/zextinst">ZExtInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1676 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#aa43f5ded794bbaa78a7d7b3b72caed8b">SetValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### executeBitCastInst() {#a6dba8e96b0d79e8c9c1ecb2033dbaee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue Interpreter::executeBitCastInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcVal, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy, <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &amp; SF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1501 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### executeFPExtInst() {#ad5a9bea077fad97c08d3c89f8d85cad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue Interpreter::executeFPExtInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcVal, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy, <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &amp; SF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1315 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### executeFPToSIInst() {#ac9a37c4e27c8c3ff1979ca6855dfcfa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue Interpreter::executeFPToSIInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcVal, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy, <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &amp; SF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1375 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### executeFPToUIInst() {#ad1a6bc8a94e2b143bb0d5bacf58001d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue Interpreter::executeFPToUIInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcVal, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy, <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &amp; SF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1337 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### executeFPTruncInst() {#ab8a6d0fc2280e0da66805c80c7f088a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue Interpreter::executeFPTruncInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcVal, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy, <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &amp; SF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1292 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### executeGEPOperation() {#a9cbe23bf8bda80a6b273843a375bf902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue Interpreter::executeGEPOperation (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/namespaces/llvm/#a81c0916829c13ba5279ca0e5480aef0c">gep_type_iterator</a> I, <a href="/web-llvm/docs/api/namespaces/llvm/#a81c0916829c13ba5279ca0e5480aef0c">gep_type_iterator</a> E, <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &amp; SF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1012 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### executeIntToPtrInst() {#a7579f49a43a80a96379d4e24e437871e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue Interpreter::executeIntToPtrInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcVal, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy, <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &amp; SF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1488 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### executePtrToIntInst() {#a596ab479cadc8d1beb7dd240609417d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue Interpreter::executePtrToIntInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcVal, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy, <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &amp; SF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1478 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### executeSExtInst() {#a822e2c218e54b71cc338cbe9f08a9eab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue Interpreter::executeSExtInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcVal, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy, <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &amp; SF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1251 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### executeSIToFPInst() {#a87f8132d128f1bce5dbc80a6a4b1efba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue Interpreter::executeSIToFPInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcVal, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy, <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &amp; SF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1444 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### executeTruncInst() {#adb17d961f05a3d2626183ba52505a317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue Interpreter::executeTruncInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcVal, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy, <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &amp; SF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1231 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### executeUIToFPInst() {#a15aa20eae9f02b9d38694b908122d2b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue Interpreter::executeUIToFPInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcVal, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy, <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &amp; SF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1412 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### executeZExtInst() {#a79c82f42606d04a31e8869c671d86e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue Interpreter::executeZExtInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcVal, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy, <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &amp; SF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1271 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### getConstantExprValue() {#a060b3764fd88225c5aa71dc356928775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue Interpreter::getConstantExprValue (<a href="/web-llvm/docs/api/classes/llvm/constantexpr">ConstantExpr</a> * CE, <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &amp; SF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 1981 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### getOperandValue() {#ac8d5d1947dacc3e9bff6ef432138b6f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue Interpreter::getOperandValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &amp; SF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 2018 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### getPointerToFunction() {#af27195bc8f3f35515473473fe296dc57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::Interpreter::getPointerToFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
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

<p>getPointerToFunction - The different EE's represent function bodies in different ways.</p>


<p>They should each implement this to say what a function pointer should look like. When F is destroyed, the <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> will remove its global mapping and free any machine code. Be sure no threads are running inside F when that happens.</p>


<p>This function is deprecated for the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> execution engine. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> getFunctionAddress instead.</p>


<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>.</p>

</div>
</div>

### initializeExecutionEngine() {#a0276739c27d919b7cbcd1e6459b694e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Interpreter::initializeExecutionEngine ()</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>.</p>

</div>
</div>

### initializeExternalFunctions() {#a8b4945b6acaa315b3be4f1b19c387258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::initializeExternalFunctions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp">ExternalFunctions.cpp</a>.</p>

</div>
</div>

### popStackAndReturnValueToCaller() {#a01cc29d4e94b347c0fc8271e334dccab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::popStackAndReturnValueToCaller (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy, <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pop the last stack frame off of ECStack and then copy the result back into the result variable if we are not returning void.</p>


<p>The result variable may be the ExitValue, or the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of the calling <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> if there was a previous stack frame. This method may invalidate any ECStack iterators you have. This method also takes care of switching to the normal destination BB, if we are returning from an invoke.</p>


<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 856 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

### SwitchToNewBasicBlock() {#a2c066a0b76b8f96080cd7099377d3a5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Interpreter::SwitchToNewBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Dest, <a href="/web-llvm/docs/api/structs/llvm/executioncontext">ExecutionContext</a> &amp; SF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 949 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AtExitHandlers {#a375d2940c0f6ca8fa50167fe1bbefc1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Function*&gt; llvm::Interpreter::AtExitHandlers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>.</p>

</div>
</div>

### ECStack {#a2ce643b974cd057e6cbe0ba537f175a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ExecutionContext&gt; llvm::Interpreter::ECStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>.</p>

</div>
</div>

### ExitValue {#a51b79c8c03637d0940fffdaec876357f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue llvm::Interpreter::ExitValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>.</p>

</div>
</div>

### IL {#a6380a88f849899e1cd21b1452dd29e6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrinsicLowering* llvm::Interpreter::IL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#aec4c8f10c02e58107d0372b5de57b819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionEngine * Interpreter::create (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; M, std::string * ErrorStr=nullptr)</td>
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

<p>Create an interpreter <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a>.</p>


<p>Create a new interpreter object.</p>


<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-cpp">Interpreter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a92eef8691cfbe4446ee15d34258c3185">llvm::ExecutionEngine::ExecutionEngine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">llvm::handleAllErrors</a>, <a href="#a742cab06ece0dfaa5fb512243e616bcc">Interpreter</a> and <a href="/web-llvm/docs/api/classes/llvm/errorinfobase/#a2b75e20ae30dbb4d4d96486653a9b710">llvm::ErrorInfoBase::message</a>.</p>


<p>Referenced by <a href="#a152334c0d8a032d91d4c90b5197cb902">Register</a>.</p>

</div>
</div>

### Register() {#a152334c0d8a032d91d4c90b5197cb902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Interpreter::Register ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>.</p>


<p>References <a href="#aec4c8f10c02e58107d0372b5de57b819">create</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a6947cede6cdd00042e82b3597606a515">llvm::ExecutionEngine::InterpCtor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-interpreter-cpp-/registerinterp/#abff839376f050d7e6e7a794a58ea6afd">anonymous{Interpreter.cpp}::RegisterInterp::RegisterInterp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp">Execution.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp">ExternalFunctions.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-cpp">Interpreter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
