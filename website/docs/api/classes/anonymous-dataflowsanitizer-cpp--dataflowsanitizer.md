---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DataFlowSanitizer` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a1ebf815ab381e6f8a73223e1c9de76d0">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a3119efb83d6a32654d1cfcc2c8f54e1e">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">WrapperKind { <a href="#a4ed6624b8550ac7c386a035b071bb146">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>How should calls to uninstrumented functions be handled? <a href="#a4ed6624b8550ac7c386a035b071bb146">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dec59d71404a456614a683add0bfe3d">DFSanFunction</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceb263f615e22f971042423416ae3fa6">DFSanVisitor</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a991cf3988b07a606932e1d69f8f8507f">DataFlowSanitizer</a> (const std::vector&lt; std::string &gt; &amp;ABIListFiles)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4d94a2774e8420abe5e331d94334cec">runImpl</a> (Module &amp;M, llvm::function_ref&lt; TargetLibraryInfo &amp;(Function &amp;)&gt; GetTLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf6731a1898359749cdedf238ac1e894">getShadowOffset</a> (Value *Addr, IRBuilder&lt;&gt; &amp;IRB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the integer shadow offset that corresponds to a given application address. <a href="#aaf6731a1898359749cdedf238ac1e894">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcb011db9998768c26a2290896a9bd5c">getShadowAddress</a> (Value *Addr, BasicBlock::iterator Pos)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aced4af9c5c975627a7af594c0fa20c46">getShadowAddress</a> (Value *Addr, BasicBlock::iterator Pos, Value *ShadowOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d2f7f1ea8bed18220b87f1df9d6aaea">getShadowOriginAddress</a> (Value *Addr, Align InstAlignment, BasicBlock::iterator Pos)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf94e45972cd254a2a3c2357628a84a6">isInstrumented</a> (const Function *F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56af0944bb63f10741c1ebb3925a44cd">isInstrumented</a> (const GlobalAlias *GA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a732af76e7162e9bb2d3031b88448d0ec">isForceZeroLabels</a> (const Function *F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/transformedfunction">TransformedFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d88b1fc86674d83660da0270c178162">getCustomFunctionType</a> (FunctionType *T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">WrapperKind</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55593fe2cb0ef59e919d4a80b4b5ab9c">getWrapperKind</a> (Function *F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9093a83183ca97ed3ee2eca49b2b5590">addGlobalNameSuffix</a> (GlobalValue *GV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1217c19ba21e7f38e61aea20e7d99384">buildExternWeakCheckIfNeeded</a> (IRBuilder&lt;&gt; &amp;IRB, Function *F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46874a8a72ff18a48442d92d3d0d411a">buildWrapperFunction</a> (Function *F, StringRef NewFName, GlobalValue::LinkageTypes NewFLink, FunctionType *NewFT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fed08bc4bd40a9e4a3eeafe8ad3a454">initializeCallbackFunctions</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b2a1c1e427b673588435715eeb593c">initializeRuntimeFunctions</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8f178cde96fc04cffd36a6d1f1953ca">initializeModule</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac3591ead82d5fc91e01cdf41c10b811">loadNextOrigin</a> (BasicBlock::iterator Pos, Align OriginAlign, Value **OriginAddr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Advances <span class="doxyComputerOutput">OriginAddr</span> to point to the next 32-bit origin and then loads from it. <a href="#aac3591ead82d5fc91e01cdf41c10b811">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0991b5578a63e4be6906c33c707df2f">hasLoadSizeForFastPath</a> (uint64_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether the given load byte size is amenable to inlined optimization patterns. <a href="#aa0991b5578a63e4be6906c33c707df2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5a308220a3406dda0fb6941b8371182">shouldTrackOrigins</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether the pass tracks origins. Supports only TLS ABI mode. <a href="#aa5a308220a3406dda0fb6941b8371182">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b3b464b378246a9357a508953aa4b5c">getZeroShadow</a> (Type *OrigTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a zero constant with the shadow type of OrigTy. <a href="#a9b3b464b378246a9357a508953aa4b5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e237c595da05006442e9aa0d617639b">getZeroShadow</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a zero constant with the shadow type of V's type. <a href="#a9e237c595da05006442e9aa0d617639b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4521f978d4e97584adef4f0109e04e5">isZeroShadow</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if V is a zero shadow. <a href="#ac4521f978d4e97584adef4f0109e04e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43cfb1acb3e88dfdd1333b628c63fdaf">getShadowTy</a> (Type *OrigTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the shadow type of OrigTy. <a href="#a43cfb1acb3e88dfdd1333b628c63fdaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14a2759cdc3ad78f6bfe33963403c596">getShadowTy</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the shadow type of V's type. <a href="#a14a2759cdc3ad78f6bfe33963403c596">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9be38cbf6d9d176d75f73ea76757a645">Mod</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f71a42dbee90806a6127bf9563bd0e1">Ctx</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78c53ddcb677ad201ecf6b06b836908f">Int8Ptr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3a632aa46c6335a7bd5eb393b168864">OriginTy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01a0cdb014344908472a12e96b792e13">OriginPtrTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a105da1ec96c4003a297daa273ab0569f">ZeroOrigin</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aa88e99846e00e913a27fa6b659cdd4">PrimitiveShadowTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The shadow type for all primitive types and vector types. <a href="#a7aa88e99846e00e913a27fa6b659cdd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09d291e9558aae491c304b1e0e7e1254">PrimitiveShadowPtrTy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60eb4e909b5e5017959ec7193ab9404a">IntptrTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cd2cb89ed013a9214b666285511fa95">ZeroPrimitiveShadow</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e32165418c0b5618783ce02b9d7d063">ArgTLS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba8d3bd2a719922a7a033442fb8ff487">ArgOriginTLSTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a307b327ef42107291ce985623e2686cf">ArgOriginTLS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a3b9b0d136feafb7433109c81e19ad7">RetvalTLS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5982672197efeb4b9349e97c0d79320d">RetvalOriginTLS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a5ddaf3411b59477743700af3e0c76d">DFSanUnionLoadFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7051237998b6dd9201258965173c1da">DFSanLoadLabelAndOriginFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa565ee9bff9514cc5fd044def4f70fbe">DFSanUnimplementedFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a659633b195011e193817d980369c8940">DFSanWrapperExternWeakNullFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41aa2900bc50a5b4fb0e97f98758dc74">DFSanSetLabelFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4526ab454491eae39c026c266ca4add">DFSanNonzeroLabelFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b951f4043ce57f020392c6759a5d83e">DFSanVarargWrapperFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fe5607a03d2db1d16a475640d43c16f">DFSanConditionalCallbackFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f2cab8c3f573d7d1e5d5ef5e3332e3d">DFSanConditionalCallbackOriginFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ab4aa062cee5f6be59f7b61e643f2c">DFSanReachesFunctionCallbackFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1b202c1b37761bccb6e39dae6d00736">DFSanReachesFunctionCallbackOriginFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1726082357b084bb5032353097f6bf30">DFSanCmpCallbackFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa920d2ee0c3aa8e10b8f5996b26a1d03">DFSanLoadStoreCallbackFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54a6563a8515ed806490c315d6d965ca">DFSanMemTransferCallbackFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a460c87abe71c22056f01ae0440c04f97">DFSanChainOriginFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40b5a0050ac85c5e8e891b11673a22fb">DFSanChainOriginIfTaintedFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a563daf57b3b28e378910c63eb604fbd1">DFSanMemOriginTransferFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae370a86944bc7138beb8c02218848254">DFSanMemShadowOriginTransferFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aae8f1fee6f80ecbf9c1f9a752c1052">DFSanMemShadowOriginConditionalExchangeFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a7318379e35a762b57c7df397f4d8d9">DFSanMaybeStoreOriginFnTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add9687cb5553f9b049808c0be2dfd215">DFSanUnionLoadFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af427203f922e9feb29f8baba261f5835">DFSanLoadLabelAndOriginFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13d07eeaa0039c9c510a4171e545e0e2">DFSanUnimplementedFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9c0e6782c1547d8db81542a9097a496">DFSanWrapperExternWeakNullFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae067f1a6b6d0df05d7ad3ab56e12eb2b">DFSanSetLabelFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1df6bb2bf43ae5a6bb4f11acd7f622c9">DFSanNonzeroLabelFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af79b16cfbc76d1900051a86a437ac94b">DFSanVarargWrapperFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3df7553b4a56b49f1f6e7dfb0c44853d">DFSanLoadCallbackFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa813fd587185ad9aaa4bba6e21cd16f5">DFSanStoreCallbackFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2d54bf2c3f0e632486c44369765c77a">DFSanMemTransferCallbackFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a2ebdb16c25e4bb8812c71dea9893d9">DFSanConditionalCallbackFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e89e5aab591dcb37bf8920f89403039">DFSanConditionalCallbackOriginFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61602215158e8f62fb2e0be06deb4cd9">DFSanReachesFunctionCallbackFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8752a046bc4d1104da886f6b2bcdda0">DFSanReachesFunctionCallbackOriginFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a431b97f6ec0e0f164d70c70e8e3a9ec8">DFSanCmpCallbackFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14e2c43ceba9fed9eeb2c0043c58e8b5">DFSanChainOriginFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d9b427678985573d4aaf4c1592b8266">DFSanChainOriginIfTaintedFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4534554a4e54c960fe3a9ccf5c034c63">DFSanMemOriginTransferFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2395ca0c401d0a34c9ef0d8ce5d28673">DFSanMemShadowOriginTransferFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbde488bb6401e2bb87b4eff2c1e13a2">DFSanMemShadowOriginConditionalExchangeFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dbfc38bf97c263aa58716c9905e18bd">DFSanMaybeStoreOriginFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84894464ef513590a0f7d014bcf22c29">DFSanRuntimeFunctions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6ea0dce190e0d9b3820f56d94884435">ColdCallWeights</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d939c6a77939f9c3eeed4c000893397">OriginStoreWeights</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanabilist">DFSanABIList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13b1ec79d8281c95610a252e42df32db">ABIList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4690109abbb15632ff41d1979d05541a">UnwrappedFnMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6edb169b4ba85db9039f7728195272c6">ReadOnlyNoneAttrs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a823393766361afefde5b59f58d7d8968">CombineTaintLookupTableNames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/memorymapparams">MemoryMapParams</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab879196c418458ea2ce935152bfda1e1">MapParams</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> map parameters used in calculation mapping application addresses to shadow addresses and origin addresses. <a href="#ab879196c418458ea2ce935152bfda1e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fb08b62f22af10df04fd460b5cb4494">NumOfElementsInArgOrgTLS</a> = <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#ad30c696cca6f4b772507385a14bbfdfe">ArgTLSSize</a> / OriginWidthBytes</td>
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


<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a1ebf815ab381e6f8a73223e1c9de76d0}

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
<td class="doxyEnumItemName">ShadowWidthBits<a id="a1ebf815ab381e6f8a73223e1c9de76d0a22d5e85e39fac901f3b97a4f0b83151d"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ShadowWidthBytes<a id="a1ebf815ab381e6f8a73223e1c9de76d0affd08317864d6ecab37057dd339b4f49"></a></td>
<td class="doxyEnumItemDescription"> (= ShadowWidthBits / 8)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### anonymous enum  {#a3119efb83d6a32654d1cfcc2c8f54e1e}

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
<td class="doxyEnumItemName">OriginWidthBits<a id="a3119efb83d6a32654d1cfcc2c8f54e1eae72029d71011c8bf3bd0bfe393f9d18b"></a></td>
<td class="doxyEnumItemDescription"> (= 32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OriginWidthBytes<a id="a3119efb83d6a32654d1cfcc2c8f54e1eaf812dc0aa9ec3457c94d0f3d7d4615a4"></a></td>
<td class="doxyEnumItemDescription"> (= OriginWidthBits / 8)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### WrapperKind {#a4ed6624b8550ac7c386a035b071bb146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::WrapperKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>How should calls to uninstrumented functions be handled?</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WK_Warning<a id="a4ed6624b8550ac7c386a035b071bb146aa9d9fe93b4ffc14d7bcd009a4e0c1c85"></a></td>
<td class="doxyEnumItemDescription">This function is present in an uninstrumented form but we don't know how it should be handled</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WK_Discard<a id="a4ed6624b8550ac7c386a035b071bb146ae21cdf092a1c9a3dd67444232c6458f3"></a></td>
<td class="doxyEnumItemDescription">This function does not write to (user-accessible) memory, and its return value is unlabelled</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WK_Functional<a id="a4ed6624b8550ac7c386a035b071bb146ac4b2abb51dd422c4447f0c9b55aefb3f"></a></td>
<td class="doxyEnumItemDescription">This function does not write to (user-accessible) memory, and the label of its return value is the union of the label of its arguments</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WK_Custom<a id="a4ed6624b8550ac7c386a035b071bb146a4eb81fef5a997ecfa8847ac9ec75d8b1"></a></td>
<td class="doxyEnumItemDescription">Instead of calling the function, a custom wrapper __dfsw_F is called, where F is the name of the function</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DFSanFunction {#a1dec59d71404a456614a683add0bfe3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction">DFSanFunction</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Reference <a href="#a1dec59d71404a456614a683add0bfe3d">DFSanFunction</a>.</p>


<p>Referenced by <a href="#a1dec59d71404a456614a683add0bfe3d">DFSanFunction</a> and <a href="#ab4d94a2774e8420abe5e331d94334cec">runImpl</a>.</p>

</div>
</div>

### DFSanVisitor {#aceb263f615e22f971042423416ae3fa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor">DFSanVisitor</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Reference <a href="#aceb263f615e22f971042423416ae3fa6">DFSanVisitor</a>.</p>


<p>Referenced by <a href="#aceb263f615e22f971042423416ae3fa6">DFSanVisitor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DataFlowSanitizer() {#a991cf3988b07a606932e1d69f8f8507f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataFlowSanitizer::DataFlowSanitizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::string &gt; &amp; ABIListFiles)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#a512552844843860182e5376df0ff2e15">ClABIListFiles</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#a38e9edcb526a3647ecb73a1eabab237b">ClCombineTaintLookupTables</a>, <a href="/web-llvm/docs/api/classes/llvm/specialcaselist/#a6c0343ae2b29d3a9882c0cfc4bee8c03">llvm::SpecialCaseList::createOrDie</a> and <a href="/web-llvm/docs/api/namespaces/llvm/vfs/#a9878c6a5a53d24e17c7c1002be31364c">llvm::vfs::getRealFileSystem</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### runImpl() {#ab4d94a2774e8420abe5e331d94334cec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DataFlowSanitizer::runImpl (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetTLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#ac04b6d4e5d3715d33fee0cf6c80a15c8">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::addReachesFunctionCallbacksIfEnabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#ad30c696cca6f4b772507385a14bbfdfe">ArgTLSSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#a60271da6df28421978d5ab731d16173c">ClDebugNonzeroLabels</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#a7338d768a449232c93e9ab354031a800">ClIgnorePersonalityRoutine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#a5780a333f75f22ac7d0c24e0a8e29b3a">ClReachesFunctionCallbacks</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#a4b65c40648346b8d99dd58a2d3d318e9">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::collapseToPrimitiveShadow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e19a09aeed4c56617c284e099c81de">llvm::depth_first</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#ae5891c006deae56c728ecb8f22aec419">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::DFS</a>, <a href="#a1dec59d71404a456614a683add0bfe3d">DFSanFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a403f79ea06f5abde47b80bd865d9a020">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::DFSanVisitor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a60a348350395aef11d68f58111bcf499">llvm::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a09b07d472515f1d307c0e8229f6856fb">llvm::GlobalAlias::eraseFromParent</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#a95173e429ac64ad7584ff95a36d39b98">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4848d1a141ddc7cf0068460fba53ba37">llvm::BasicBlock::front</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a311a097af4f0f77da22ac7acddc496f5">llvm::GlobalAlias::getAliaseeObject</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a169f0c26ef46161741fdd120a806f853">llvm::Function::getEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3547d58a060ee2e4a29cbea85bef91af">llvm::GlobalValue::getLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a62ee7ece4986606d41363bc1f70d5ab2">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a104d6154321899b53e40455e71d8e83a">llvm::FunctionType::getNumParams</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#a9e596bf4044aed2cf004290fe49a1a03">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::getOrigin</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#ad65790aa94dd4678a1d339d8304e1965">llvm::FunctionType::getReturnType</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#a7b7b17b8c343bd803b7381e95331701c">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a92e26a4a1218d351f5a91e7385a3a320">llvm::GlobalValue::InitialExecTLSModel</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a7653277511df1034148a37520a585bb5">llvm::Instruction::isTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#aa9d770048c7ab9e08222a50b7bc1be1c">llvm::FunctionType::isVarArg</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae8eaa0b4eeac52a2b2282cb1bfd981ae">llvm::Type::isVoidTy</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dataflowsanitizer-cpp-/#ab27c518b9b08626cf7d724c26cb0856b">anonymous{DataFlowSanitizer.cpp}::LibAtomicFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">llvm::GlobalValue::LinkOnceODRLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#a76b93b5c0d047eba65daf2d3afcf31b9">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::NonZeroChecks</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#aefe636103263c2f6bb2f30b56cc339d0">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::PHIFixups</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a6875de46fcb2a74ca95bce67edd215a0">llvm::Function::removeFnAttrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec88b7682025edff7984c3b6c8da8ac9">llvm::removeUnreachableBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#ae113878cee8d330c91e109f381fe6d2b">RetvalTLSSize</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#ae661edba632a774dfa41217e00b02300">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::SkipInsts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad957413955739c91204c96e33e0cc933">llvm::SplitBlockAndInsertIfThen</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ae855357b6c5e6e7ed1869272708a3a84">llvm::Value::takeName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addGlobalNameSuffix() {#a9093a83183ca97ed3ee2eca49b2b5590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DataFlowSanitizer::addGlobalNameSuffix (<a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### buildExternWeakCheckIfNeeded() {#a1217c19ba21e7f38e61aea20e7d99384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DataFlowSanitizer::buildExternWeakCheckIfNeeded (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### buildWrapperFunction() {#a46874a8a72ff18a48442d92d3d0d411a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * DataFlowSanitizer::buildWrapperFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NewFName, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> NewFLink, <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * NewFT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### getCustomFunctionType() {#a3d88b1fc86674d83660da0270c178162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TransformedFunction DataFlowSanitizer::getCustomFunctionType (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### getShadowAddress() {#abcb011db9998768c26a2290896a9bd5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DataFlowSanitizer::getShadowAddress (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### getShadowAddress() {#aced4af9c5c975627a7af594c0fa20c46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DataFlowSanitizer::getShadowAddress (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Pos, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ShadowOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### getShadowOffset() {#aaf6731a1898359749cdedf238ac1e894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DataFlowSanitizer::getShadowOffset (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the integer shadow offset that corresponds to a given application address.</p>


<p>Offset = (Addr &amp; ~AndMask) ^ XorMask</p>


<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### getShadowOriginAddress() {#a0d2f7f1ea8bed18220b87f1df9d6aaea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Value *, Value * &gt; DataFlowSanitizer::getShadowOriginAddress (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> InstAlignment, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### getShadowTy() {#a43cfb1acb3e88dfdd1333b628c63fdaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * DataFlowSanitizer::getShadowTy (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * OrigTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the shadow type of OrigTy.</p>


<p>getShadowTy({T1,T2,...}) = {getShadowTy(T1),getShadowTy(T2),...} getShadowTy([n x T]) = [n x getShadowTy(T)] getShadowTy(other type) = i16</p>


<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### getShadowTy() {#a14a2759cdc3ad78f6bfe33963403c596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * DataFlowSanitizer::getShadowTy (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the shadow type of V's type.</p>

<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### getWrapperKind() {#a55593fe2cb0ef59e919d4a80b4b5ab9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataFlowSanitizer::WrapperKind DataFlowSanitizer::getWrapperKind (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### getZeroShadow() {#a9b3b464b378246a9357a508953aa4b5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * DataFlowSanitizer::getZeroShadow (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * OrigTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a zero constant with the shadow type of OrigTy.</p>


<p>getZeroShadow({T1,T2,...}) = {getZeroShadow(T1),getZeroShadow(T2,...} getZeroShadow([n x T]) = [n x getZeroShadow(T)] getZeroShadow(other type) = i16(0)</p>


<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### getZeroShadow() {#a9e237c595da05006442e9aa0d617639b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * DataFlowSanitizer::getZeroShadow (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a zero constant with the shadow type of V's type.</p>

<p>Definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### hasLoadSizeForFastPath() {#aa0991b5578a63e4be6906c33c707df2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DataFlowSanitizer::hasLoadSizeForFastPath (uint64_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns whether the given load byte size is amenable to inlined optimization patterns.</p>

<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### initializeCallbackFunctions() {#a9fed08bc4bd40a9e4a3eeafe8ad3a454}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DataFlowSanitizer::initializeCallbackFunctions (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### initializeModule() {#ae8f178cde96fc04cffd36a6d1f1953ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DataFlowSanitizer::initializeModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### initializeRuntimeFunctions() {#a05b2a1c1e427b673588435715eeb593c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DataFlowSanitizer::initializeRuntimeFunctions (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### isForceZeroLabels() {#a732af76e7162e9bb2d3031b88448d0ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DataFlowSanitizer::isForceZeroLabels (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### isInstrumented() {#abf94e45972cd254a2a3c2357628a84a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DataFlowSanitizer::isInstrumented (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### isInstrumented() {#a56af0944bb63f10741c1ebb3925a44cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DataFlowSanitizer::isInstrumented (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> * GA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### isZeroShadow() {#ac4521f978d4e97584adef4f0109e04e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DataFlowSanitizer::isZeroShadow (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if V is a zero shadow.</p>

<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### loadNextOrigin() {#aac3591ead82d5fc91e01cdf41c10b811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DataFlowSanitizer::loadNextOrigin (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Pos, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> OriginAlign, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ** OriginAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Advances <span class="doxyComputerOutput">OriginAddr</span> to point to the next 32-bit origin and then loads from it.</p>


<p>Returns the origin's loaded value.</p>


<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### shouldTrackOrigins() {#aa5a308220a3406dda0fb6941b8371182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DataFlowSanitizer::shouldTrackOrigins ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns whether the pass tracks origins. Supports only TLS ABI mode.</p>

<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ABIList {#a13b1ec79d8281c95610a252e42df32db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DFSanABIList anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::ABIList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### ArgOriginTLS {#a307b327ef42107291ce985623e2686cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::ArgOriginTLS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### ArgOriginTLSTy {#aba8d3bd2a719922a7a033442fb8ff487}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::ArgOriginTLSTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### ArgTLS {#a0e32165418c0b5618783ce02b9d7d063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::ArgTLS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### ColdCallWeights {#ae6ea0dce190e0d9b3820f56d94884435}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::ColdCallWeights</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### CombineTaintLookupTableNames {#a823393766361afefde5b59f58d7d8968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSet anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::CombineTaintLookupTableNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### Ctx {#a3f71a42dbee90806a6127bf9563bd0e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanChainOriginFn {#a14e2c43ceba9fed9eeb2c0043c58e8b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanChainOriginFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanChainOriginFnTy {#a460c87abe71c22056f01ae0440c04f97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanChainOriginFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanChainOriginIfTaintedFn {#a3d9b427678985573d4aaf4c1592b8266}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanChainOriginIfTaintedFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanChainOriginIfTaintedFnTy {#a40b5a0050ac85c5e8e891b11673a22fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanChainOriginIfTaintedFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanCmpCallbackFn {#a431b97f6ec0e0f164d70c70e8e3a9ec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanCmpCallbackFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanCmpCallbackFnTy {#a1726082357b084bb5032353097f6bf30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanCmpCallbackFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanConditionalCallbackFn {#a7a2ebdb16c25e4bb8812c71dea9893d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanConditionalCallbackFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanConditionalCallbackFnTy {#a9fe5607a03d2db1d16a475640d43c16f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanConditionalCallbackFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanConditionalCallbackOriginFn {#a6e89e5aab591dcb37bf8920f89403039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanConditionalCallbackOriginFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanConditionalCallbackOriginFnTy {#a5f2cab8c3f573d7d1e5d5ef5e3332e3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanConditionalCallbackOriginFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanLoadCallbackFn {#a3df7553b4a56b49f1f6e7dfb0c44853d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanLoadCallbackFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanLoadLabelAndOriginFn {#af427203f922e9feb29f8baba261f5835}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanLoadLabelAndOriginFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanLoadLabelAndOriginFnTy {#ab7051237998b6dd9201258965173c1da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanLoadLabelAndOriginFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanLoadStoreCallbackFnTy {#aa920d2ee0c3aa8e10b8f5996b26a1d03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanLoadStoreCallbackFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanMaybeStoreOriginFn {#a4dbfc38bf97c263aa58716c9905e18bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanMaybeStoreOriginFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanMaybeStoreOriginFnTy {#a2a7318379e35a762b57c7df397f4d8d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanMaybeStoreOriginFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanMemOriginTransferFn {#a4534554a4e54c960fe3a9ccf5c034c63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanMemOriginTransferFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanMemOriginTransferFnTy {#a563daf57b3b28e378910c63eb604fbd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanMemOriginTransferFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanMemShadowOriginConditionalExchangeFn {#abbde488bb6401e2bb87b4eff2c1e13a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanMemShadowOriginConditionalExchangeFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanMemShadowOriginConditionalExchangeFnTy {#a7aae8f1fee6f80ecbf9c1f9a752c1052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanMemShadowOriginConditionalExchangeFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanMemShadowOriginTransferFn {#a2395ca0c401d0a34c9ef0d8ce5d28673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanMemShadowOriginTransferFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanMemShadowOriginTransferFnTy {#ae370a86944bc7138beb8c02218848254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanMemShadowOriginTransferFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanMemTransferCallbackFn {#aa2d54bf2c3f0e632486c44369765c77a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanMemTransferCallbackFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanMemTransferCallbackFnTy {#a54a6563a8515ed806490c315d6d965ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanMemTransferCallbackFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanNonzeroLabelFn {#a1df6bb2bf43ae5a6bb4f11acd7f622c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanNonzeroLabelFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanNonzeroLabelFnTy {#ac4526ab454491eae39c026c266ca4add}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanNonzeroLabelFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanReachesFunctionCallbackFn {#a61602215158e8f62fb2e0be06deb4cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanReachesFunctionCallbackFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanReachesFunctionCallbackFnTy {#a65ab4aa062cee5f6be59f7b61e643f2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanReachesFunctionCallbackFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanReachesFunctionCallbackOriginFn {#ac8752a046bc4d1104da886f6b2bcdda0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanReachesFunctionCallbackOriginFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanReachesFunctionCallbackOriginFnTy {#ac1b202c1b37761bccb6e39dae6d00736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanReachesFunctionCallbackOriginFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanRuntimeFunctions {#a84894464ef513590a0f7d014bcf22c29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Value *, 16&gt; anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanRuntimeFunctions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanSetLabelFn {#ae067f1a6b6d0df05d7ad3ab56e12eb2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanSetLabelFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanSetLabelFnTy {#a41aa2900bc50a5b4fb0e97f98758dc74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanSetLabelFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanStoreCallbackFn {#aa813fd587185ad9aaa4bba6e21cd16f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanStoreCallbackFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanUnimplementedFn {#a13d07eeaa0039c9c510a4171e545e0e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanUnimplementedFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanUnimplementedFnTy {#aa565ee9bff9514cc5fd044def4f70fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanUnimplementedFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanUnionLoadFn {#add9687cb5553f9b049808c0be2dfd215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanUnionLoadFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanUnionLoadFnTy {#a3a5ddaf3411b59477743700af3e0c76d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanUnionLoadFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanVarargWrapperFn {#af79b16cfbc76d1900051a86a437ac94b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanVarargWrapperFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanVarargWrapperFnTy {#a8b951f4043ce57f020392c6759a5d83e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanVarargWrapperFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanWrapperExternWeakNullFn {#ae9c0e6782c1547d8db81542a9097a496}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanWrapperExternWeakNullFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### DFSanWrapperExternWeakNullFnTy {#a659633b195011e193817d980369c8940}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DFSanWrapperExternWeakNullFnTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### Int8Ptr {#a78c53ddcb677ad201ecf6b06b836908f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::Int8Ptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### IntptrTy {#a60eb4e909b5e5017959ec7193ab9404a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::IntptrTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### MapParams {#ab879196c418458ea2ce935152bfda1e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemoryMapParams* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::MapParams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> map parameters used in calculation mapping application addresses to shadow addresses and origin addresses.</p>

<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### Mod {#a9be38cbf6d9d176d75f73ea76757a645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::Mod</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### NumOfElementsInArgOrgTLS {#a7fb08b62f22af10df04fd460b5cb4494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::NumOfElementsInArgOrgTLS = <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#ad30c696cca6f4b772507385a14bbfdfe">ArgTLSSize</a> / OriginWidthBytes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### OriginPtrTy {#a01a0cdb014344908472a12e96b792e13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::OriginPtrTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### OriginStoreWeights {#a6d939c6a77939f9c3eeed4c000893397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::OriginStoreWeights</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### OriginTy {#ab3a632aa46c6335a7bd5eb393b168864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::OriginTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### PrimitiveShadowPtrTy {#a09d291e9558aae491c304b1e0e7e1254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::PrimitiveShadowPtrTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### PrimitiveShadowTy {#a7aa88e99846e00e913a27fa6b659cdd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::PrimitiveShadowTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The shadow type for all primitive types and vector types.</p>

<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### ReadOnlyNoneAttrs {#a6edb169b4ba85db9039f7728195272c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeMask anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::ReadOnlyNoneAttrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### RetvalOriginTLS {#a5982672197efeb4b9349e97c0d79320d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::RetvalOriginTLS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### RetvalTLS {#a0a3b9b0d136feafb7433109c81e19ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::RetvalTLS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### UnwrappedFnMap {#a4690109abbb15632ff41d1979d05541a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, Function *&gt; anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::UnwrappedFnMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### ZeroOrigin {#a105da1ec96c4003a297daa273ab0569f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantInt* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::ZeroOrigin</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### ZeroPrimitiveShadow {#a0cd2cb89ed013a9214b666285511fa95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantInt* anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::ZeroPrimitiveShadow</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
