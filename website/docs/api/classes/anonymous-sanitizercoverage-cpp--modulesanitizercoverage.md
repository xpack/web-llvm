---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ModuleSanitizerCoverage` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a297bc4ec2576b843d586d32ceaaf4f16">DomTreeCallback</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92d3ca97406c6b7ea42058abbea19458">PostDomTreeCallback</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac87cbab72d705563ec6feb1929d783f0">ModuleSanitizerCoverage</a> (Module &amp;M, DomTreeCallback DTCallback, PostDomTreeCallback PDTCallback, const SanitizerCoverageOptions &amp;Options, const SpecialCaseList *Allowlist, const SpecialCaseList *Blocklist)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00b535566c2050fdc979d248b4dae4b8">instrumentModule</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fc5b0910eacdac698254bb79cea38d8">createFunctionControlFlow</a> (Function &amp;F)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab340cf5173a4766c0e974c7625167f8f">instrumentFunction</a> (Function &amp;F)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a524b1398ab5f7900dc2fd897a60853fd">InjectCoverageForIndirectCalls</a> (Function &amp;F, ArrayRef&lt; Instruction * &gt; IndirCalls)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaa1149f93e040065628e69310febec0">InjectTraceForCmp</a> (Function &amp;F, ArrayRef&lt; Instruction * &gt; CmpTraceTargets, Value *&amp;FunctionGateCmp)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1db9ebaf618d13559352ca49d07071d7">InjectTraceForDiv</a> (Function &amp;F, ArrayRef&lt; BinaryOperator * &gt; DivTraceTargets)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaef7fea1749b2b395872cbcd0977bbba">InjectTraceForGep</a> (Function &amp;F, ArrayRef&lt; GetElementPtrInst * &gt; GepTraceTargets)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bfbe8d20b86c5de1c21a2f45d4ed3ad">InjectTraceForLoadsAndStores</a> (Function &amp;F, ArrayRef&lt; LoadInst * &gt; Loads, ArrayRef&lt; StoreInst * &gt; Stores)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f39fdc01052ad66541f6a2e22501ed2">InjectTraceForSwitch</a> (Function &amp;F, ArrayRef&lt; Instruction * &gt; SwitchTraceTargets, Value *&amp;FunctionGateCmp)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8574e2d8fbc3debd75db69748560e0d1">InjectCoverage</a> (Function &amp;F, ArrayRef&lt; BasicBlock * &gt; AllBlocks, Value *&amp;FunctionGateCmp, bool IsLeafFunc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae28fe22cedf9b0817e233c6d0667c821">CreateFunctionLocalArrayInSection</a> (size_t NumElements, Function &amp;F, Type *Ty, const char *Section)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27e127125d0f3bd1ecfe57730e23e0e9">CreatePCArray</a> (Function &amp;F, ArrayRef&lt; BasicBlock * &gt; AllBlocks)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0612413c16f60b6f2f736116adf879a">CreateFunctionLocalArrays</a> (Function &amp;F, ArrayRef&lt; BasicBlock * &gt; AllBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28951da7cf703d3a8fa06bbf5eddaccb">CreateGateBranch</a> (Function &amp;F, Value *&amp;FunctionGateCmp, Instruction *I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1d70a5819aa415d8e38b4947268325f">CreateFunctionLocalGateCmp</a> (IRBuilder&lt;&gt; &amp;IRB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f40a1fbd10bf420fa143a759fde06cf">InjectCoverageAtBlock</a> (Function &amp;F, BasicBlock &amp;BB, size_t Idx, Value *&amp;FunctionGateCmp, bool IsLeafFunc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1b7df5895fbd5f407590aafafd82a16">CreateInitCallsForSections</a> (Module &amp;M, const char *CtorName, const char *InitFunctionName, Type *Ty, const char *Section)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dcce7b14f9e00fd69615723f7814272">CreateSecStartEnd</a> (Module &amp;M, const char *Section, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a186f223b35f5a7056d296bf57ef99816">getSectionName</a> (const std::string &amp;Section) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a325f11435dbcd704fcc06155decae1c8">getSectionStart</a> (const std::string &amp;Section) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e03b093f920cde485eaf09c30bf4212">getSectionEnd</a> (const std::string &amp;Section) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7394eb092a7762e788a7262a3aaa626f">M</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a297bc4ec2576b843d586d32ceaaf4f16">DomTreeCallback</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0504b8be6d30c9b66990952f8b3897b7">DTCallback</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a92d3ca97406c6b7ea42058abbea19458">PostDomTreeCallback</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2af4ce1e1ca284774a45142914a47a16">PDTCallback</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6785f8684b0946db288779588c47afcd">SanCovTracePCIndir</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f072c80e962d29ebe907a7dd309fc32">SanCovTracePC</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac16ad85786011b5fd335723ea6cf7f53">SanCovTracePCGuard</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ccf8b004b328666ed90fb2d5a54e94b">SanCovTraceCmpFunction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22b3553221cf7db0159445fcf9d6427e">SanCovTraceConstCmpFunction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a>, 5 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ad12bd98190e222305327021c5cc42">SanCovLoadFunction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a>, 5 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf66f1b39b0e54aebf91ed9955f000e9">SanCovStoreFunction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a428f7dd987c9cd5c1362406005f387e9">SanCovTraceDivFunction</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9857888cdb88c852fc34edb071ab5544">SanCovTraceGepFunction</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78f26c2be9cffe2708e396429e03952d">SanCovTraceSwitchFunction</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4f2de3737b1c2507211516ea8548b28">SanCovLowestStack</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a997a3fd9bc109c94e62ff477d7ce4b59">SanCovCallbackGate</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4ad5bececdd69d150870575c211e680">PtrTy</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9db1dfb05268c989138d3c07f2259b1">IntptrTy</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c4a14acebd7b67a0720dab757ba8bc">Int64Ty</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86f303f81a03b29e85355bf976be858b">Int32Ty</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade255b989ebe86bb29ec2a322b37ac5b">Int16Ty</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc77d7576199553c45c9c6428ba1d7e9">Int8Ty</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affec4d2bb2265db1f3cae48d595604cd">Int1Ty</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37fb0eced0460f37ad49955434b47fed">CurModule</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03e8d813c63fabf5a7315b74a8f3db2a">CurModuleUniqueId</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a8af107e9c614017accf62df8070528">TargetTriple</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a505f1d6ca44cf33ed0d5db7e089c075c">C</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0970eab90b7e492ad85fa53af5e109a7">DL</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a260461e6158f842337d5795f3387ca">FunctionGuardArray</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9bf2cf9948e62ae38fe552ef114ea6d">Function8bitCounterArray</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24f09b0d13e01f7777e4d09df86236d0">FunctionBoolArray</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae3dfce6fb3d1d1e8bec2e73d862e9fb">FunctionPCsArray</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1146506ba82561e7c2dd0eed05176604">FunctionCFsArray</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, 20 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a596282472e48191cdf2f08438f95e836">GlobalsToAppendToUsed</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, 20 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22e66f008c6bd44563db617c9a59befe">GlobalsToAppendToCompilerUsed</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sanitizercoverageoptions">SanitizerCoverageOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a612283c9ecbbb2b32fa5d6210428b3ab">Options</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/specialcaselist">SpecialCaseList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a997546813c5af9a4c75c5682307deb91">Allowlist</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/specialcaselist">SpecialCaseList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e13447bdd3b462b103bdbac92c8e5c1">Blocklist</a></td>
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


<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### DomTreeCallback {#a297bc4ec2576b843d586d32ceaaf4f16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::DomTreeCallback =  function_ref&lt;const DominatorTree &amp;(Function &amp;F)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### PostDomTreeCallback {#a92d3ca97406c6b7ea42058abbea19458}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::PostDomTreeCallback = 
      function_ref&lt;const PostDominatorTree &amp;(Function &amp;F)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ModuleSanitizerCoverage() {#ac87cbab72d705563ec6feb1929d783f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::ModuleSanitizerCoverage (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="#a297bc4ec2576b843d586d32ceaaf4f16">DomTreeCallback</a> DTCallback, <a href="#a92d3ca97406c6b7ea42058abbea19458">PostDomTreeCallback</a> PDTCallback, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sanitizercoverageoptions">SanitizerCoverageOptions</a> &amp; Options, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/specialcaselist">SpecialCaseList</a> * Allowlist, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/specialcaselist">SpecialCaseList</a> * Blocklist)</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### instrumentModule() {#a00b535566c2050fdc979d248b4dae4b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ModuleSanitizerCoverage::instrumentModule ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributelist/#af3a6727ecc3f601729c11f37a19f93f8">llvm::AttributeList::addParamAttribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab730f72aa213d5ecc7d1101efda8811">llvm::appendToCompilerUsed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae879dd14ccc28696f3d8c7b484df3c9a">llvm::appendToUsed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a5d736bf277e14e3b7f72c7165e4e03f6">ClGatedCallbacks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67d90c79914c0bdfadad630647f8843b">llvm::declareSanitizerInitFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a169f0c26ef46161741fdd120a806f853">llvm::Function::getEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7325c05ca5ad3b239d1e88b933324c01">llvm::IRBuilderBase::getInt16Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1fb6e8365dbf4ef3a7426ff3d531ff87">llvm::IRBuilderBase::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64748b5a9f8d8dd4499f84312e2c1336">llvm::IRBuilderBase::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a2da32c7f0735e4bcb64c34222a79a6c1">llvm::dwarf_linker::getSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b8599f07b1b0181899c650b7b385b26">llvm::getUniqueModuleId</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a7eade123587a08e674f2ca72e2443771">llvm::GlobalValue::HiddenVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a92e26a4a1218d351f5a91e7385a3a320">llvm::GlobalValue::InitialExecTLSModel</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca5ebf288ceb5bbeb7025564727db6d705">llvm::GlobalValue::LinkOnceAnyLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a20c9d78b627349947124112474977f1d">SanCov8bitCountersInitName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a56709052d5986f23318c4d13ce269166">SanCovBoolFlagInitName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a1cb6e0753894ad3fe119c934f2eb9e39">SanCovBoolFlagSectionName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a9143a774df60b31a39ebcc08211a0225">SanCovCallbackGateName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#ac74ce28e7af43e45ba6730c32931a039">SanCovCallbackGateSectionName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#aa2785fd8dca205a2915dfa3ba3bf8ea6">SanCovCFsInitName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a055a5fdb0c33d76f1c0a33306c90aaec">SanCovCFsSectionName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a3f6e16ce6987f6c7bb88a79a28f8aae7">SanCovCountersSectionName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a6d10fdcebd302c010ddb8b4923f7b410">SanCovGuardsSectionName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#ab23c9c52fc5ba5b80f0ba5e9f445a3f7">SanCovLoad1</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a625c71e7f07b74322842c8ba2f520d67">SanCovLoad16</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#af3d39995945171c82827aac57b609496">SanCovLoad2</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a964a8a789ada569eb2d77e1448b00556">SanCovLoad4</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a323a2ec4205253d32835820dea38f001">SanCovLoad8</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#af7c266d86a3587137724fe9c8d40b87a">SanCovLowestStackName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a4aa27cb010d7c5f282a819b2aa37aab3">SanCovModuleCtor8bitCountersName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#ad208a7c19bcaa7810d6079ff9b0a372b">SanCovModuleCtorBoolFlagName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a39a3eeade6f6668e57278d912c9071a4">SanCovModuleCtorTracePcGuardName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a438e6f841820a9536d96a24c3d91cf64">SanCovPCsInitName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#ab0c59cb1bbdc19206ecaf120e457167b">SanCovPCsSectionName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a79d633a1a1de145d2888a394e4d33dc3">SanCovStore1</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#ac8b05cbc4494c7a61cecc6f83e00cfa5">SanCovStore16</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#aa8b4d8adcaa4a0e6ee7ca5771432e968">SanCovStore2</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#af14ece56d32bbda978ab5c2367955be9">SanCovStore4</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#ae2d4c3cca15d25504808ad9c02a2d622">SanCovStore8</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a38f1c65c3525599ee83e57b75463ebd1">SanCovTraceCmp1</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#adfc8f50a539e2e4e4abe594728c670cd">SanCovTraceCmp2</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#af63a7c660ceaaf868892d35c2f280559">SanCovTraceCmp4</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#ac0d730ef6fbded762b8e056ceec21dba">SanCovTraceCmp8</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a813298e826be69472cddee86a8f975c7">SanCovTraceConstCmp1</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a802cd9d2e91474b5369c09ee34b9a969">SanCovTraceConstCmp2</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a1b379fc684f80f3704ef93e3c2511532">SanCovTraceConstCmp4</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a6c778fa4e1d70ca75766a57eba1622d9">SanCovTraceConstCmp8</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a4ebecab3bbccc9fdd57f4db77a0e9bfd">SanCovTraceDiv4</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a95def6f72117e9b44c137dba5aa8d7f7">SanCovTraceDiv8</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a5f5695be293ad7d81a5cd76030a2055e">SanCovTraceGep</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a4dbe4e5bb925ceeea30be3c33a7281cb">SanCovTracePCGuardInitName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a4429a97a75a264cec7fee0dabcfe673a">SanCovTracePCGuardName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#afe4669da69bc647cbc2c6ce195b34f36">SanCovTracePCIndirName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#ae4e4c059ec99b6218c182b1574fcbd8a">SanCovTracePCName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a38adaa9af5390a1e64c8fd0207e1963b">SanCovTraceSwitchName</a> and <a href="/web-llvm/docs/api/structs/llvm/sanitizercoverageoptions/#a6fbd9e46b04866c157520732aaaa99bea8d35016762982753aec6d7aed4be8142">llvm::SanitizerCoverageOptions::SCK_None</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createFunctionControlFlow() {#a1fc5b0910eacdac698254bb79cea38d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSanitizerCoverage::createFunctionControlFlow (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### CreateFunctionLocalArrayInSection() {#ae28fe22cedf9b0817e233c6d0667c821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * ModuleSanitizerCoverage::CreateFunctionLocalArrayInSection (size_t NumElements, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### CreateFunctionLocalArrays() {#aa0612413c16f60b6f2f736116adf879a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSanitizerCoverage::CreateFunctionLocalArrays (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; AllBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### CreateFunctionLocalGateCmp() {#ac1d70a5819aa415d8e38b4947268325f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ModuleSanitizerCoverage::CreateFunctionLocalGateCmp (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### CreateGateBranch() {#a28951da7cf703d3a8fa06bbf5eddaccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * ModuleSanitizerCoverage::CreateGateBranch (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; FunctionGateCmp, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### CreateInitCallsForSections() {#ab1b7df5895fbd5f407590aafafd82a16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * ModuleSanitizerCoverage::CreateInitCallsForSections (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CtorName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * InitFunctionName, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### CreatePCArray() {#a27e127125d0f3bd1ecfe57730e23e0e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * ModuleSanitizerCoverage::CreatePCArray (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; AllBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### CreateSecStartEnd() {#a4dcce7b14f9e00fd69615723f7814272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Value *, Value * &gt; ModuleSanitizerCoverage::CreateSecStartEnd (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Section, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### getSectionEnd() {#a8e03b093f920cde485eaf09c30bf4212}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string ModuleSanitizerCoverage::getSectionEnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### getSectionName() {#a186f223b35f5a7056d296bf57ef99816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string ModuleSanitizerCoverage::getSectionName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### getSectionStart() {#a325f11435dbcd704fcc06155decae1c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string ModuleSanitizerCoverage::getSectionStart (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### InjectCoverage() {#a8574e2d8fbc3debd75db69748560e0d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ModuleSanitizerCoverage::InjectCoverage (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; AllBlocks, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; FunctionGateCmp, bool IsLeafFunc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### InjectCoverageAtBlock() {#a9f40a1fbd10bf420fa143a759fde06cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSanitizerCoverage::InjectCoverageAtBlock (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, size_t Idx, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; FunctionGateCmp, bool IsLeafFunc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### InjectCoverageForIndirectCalls() {#a524b1398ab5f7900dc2fd897a60853fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSanitizerCoverage::InjectCoverageForIndirectCalls (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; IndirCalls)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### InjectTraceForCmp() {#adaa1149f93e040065628e69310febec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSanitizerCoverage::InjectTraceForCmp (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; CmpTraceTargets, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; FunctionGateCmp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### InjectTraceForDiv() {#a1db9ebaf618d13559352ca49d07071d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSanitizerCoverage::InjectTraceForDiv (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * &gt; DivTraceTargets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### InjectTraceForGep() {#aaef7fea1749b2b395872cbcd0977bbba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSanitizerCoverage::InjectTraceForGep (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * &gt; GepTraceTargets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### InjectTraceForLoadsAndStores() {#a6bfbe8d20b86c5de1c21a2f45d4ed3ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSanitizerCoverage::InjectTraceForLoadsAndStores (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * &gt; Loads, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * &gt; Stores)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### InjectTraceForSwitch() {#a0f39fdc01052ad66541f6a2e22501ed2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSanitizerCoverage::InjectTraceForSwitch (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; SwitchTraceTargets, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; FunctionGateCmp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### instrumentFunction() {#ab340cf5173a4766c0e974c7625167f8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSanitizerCoverage::instrumentFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allowlist {#a997546813c5af9a4c75c5682307deb91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SpecialCaseList* anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::Allowlist</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### Blocklist {#a8e13447bdd3b462b103bdbac92c8e5c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SpecialCaseList* anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::Blocklist</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### C {#a505f1d6ca44cf33ed0d5db7e089c075c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext* anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::C</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### CurModule {#a37fb0eced0460f37ad49955434b47fed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module* anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::CurModule</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### CurModuleUniqueId {#a03e8d813c63fabf5a7315b74a8f3db2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::CurModuleUniqueId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### DL {#a0970eab90b7e492ad85fa53af5e109a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout* anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### DTCallback {#a0504b8be6d30c9b66990952f8b3897b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeCallback anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::DTCallback</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### Function8bitCounterArray {#ad9bf2cf9948e62ae38fe552ef114ea6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable* anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::Function8bitCounterArray</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### FunctionBoolArray {#a24f09b0d13e01f7777e4d09df86236d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable* anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::FunctionBoolArray</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### FunctionCFsArray {#a1146506ba82561e7c2dd0eed05176604}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable* anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::FunctionCFsArray</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### FunctionGuardArray {#a4a260461e6158f842337d5795f3387ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable* anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::FunctionGuardArray</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### FunctionPCsArray {#aae3dfce6fb3d1d1e8bec2e73d862e9fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable* anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::FunctionPCsArray</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### GlobalsToAppendToCompilerUsed {#a22e66f008c6bd44563db617c9a59befe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;GlobalValue *, 20&gt; anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::GlobalsToAppendToCompilerUsed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### GlobalsToAppendToUsed {#a596282472e48191cdf2f08438f95e836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;GlobalValue *, 20&gt; anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::GlobalsToAppendToUsed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### Int16Ty {#ade255b989ebe86bb29ec2a322b37ac5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::Int16Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### Int1Ty {#affec4d2bb2265db1f3cae48d595604cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::Int1Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### Int32Ty {#a86f303f81a03b29e85355bf976be858b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::Int32Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### Int64Ty {#ac8c4a14acebd7b67a0720dab757ba8bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::Int64Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### Int8Ty {#abc77d7576199553c45c9c6428ba1d7e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::Int8Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### IntptrTy {#ae9db1dfb05268c989138d3c07f2259b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::IntptrTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### M {#a7394eb092a7762e788a7262a3aaa626f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module&amp; anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### Options {#a612283c9ecbbb2b32fa5d6210428b3ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SanitizerCoverageOptions anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::Options</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### PDTCallback {#a2af4ce1e1ca284774a45142914a47a16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PostDomTreeCallback anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::PDTCallback</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### PtrTy {#ae4ad5bececdd69d150870575c211e680}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::PtrTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### SanCovCallbackGate {#a997a3fd9bc109c94e62ff477d7ce4b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable* anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::SanCovCallbackGate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### SanCovLoadFunction {#af9ad12bd98190e222305327021c5cc42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;FunctionCallee, 5&gt; anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::SanCovLoadFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### SanCovLowestStack {#ae4f2de3737b1c2507211516ea8548b28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable* anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::SanCovLowestStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### SanCovStoreFunction {#abf66f1b39b0e54aebf91ed9955f000e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;FunctionCallee, 5&gt; anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::SanCovStoreFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### SanCovTraceCmpFunction {#a3ccf8b004b328666ed90fb2d5a54e94b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;FunctionCallee, 4&gt; anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::SanCovTraceCmpFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### SanCovTraceConstCmpFunction {#a22b3553221cf7db0159445fcf9d6427e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;FunctionCallee, 4&gt; anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::SanCovTraceConstCmpFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### SanCovTraceDivFunction {#a428f7dd987c9cd5c1362406005f387e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;FunctionCallee, 2&gt; anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::SanCovTraceDivFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### SanCovTraceGepFunction {#a9857888cdb88c852fc34edb071ab5544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::SanCovTraceGepFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### SanCovTracePC {#a4f072c80e962d29ebe907a7dd309fc32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::SanCovTracePC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### SanCovTracePCGuard {#ac16ad85786011b5fd335723ea6cf7f53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::SanCovTracePCGuard</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### SanCovTracePCIndir {#a6785f8684b0946db288779588c47afcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::SanCovTracePCIndir</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### SanCovTraceSwitchFunction {#a78f26c2be9cffe2708e396429e03952d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::SanCovTraceSwitchFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

### TargetTriple {#a8a8af107e9c614017accf62df8070528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::TargetTriple</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
