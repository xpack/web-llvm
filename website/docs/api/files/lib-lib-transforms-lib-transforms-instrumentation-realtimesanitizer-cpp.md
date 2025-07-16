---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RealtimeSanitizer.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">llvm/IR/Analysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/institerator-h">llvm/IR/InstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/moduleutils-h">llvm/Transforms/Utils/ModuleUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">llvm/Demangle/Demangle.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/realtimesanitizer-h">llvm/Transforms/Instrumentation/RealtimeSanitizer.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1922f0fa6389aaa7596f303e96bd8507">getArgTypes</a> (ArrayRef&lt; Value * &gt; FunctionArgs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf5c6a95e57ae41b1bb74e87476d3dcc">insertCallBeforeInstruction</a> (Function &amp;Fn, Instruction &amp;Instruction, const char *FunctionName, ArrayRef&lt; Value * &gt; FunctionArgs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeab32388541e65c42e97d2ca8c7867d1">insertCallAtFunctionEntryPoint</a> (Function &amp;Fn, const char *InsertFnName, ArrayRef&lt; Value * &gt; FunctionArgs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3f63c5f611bcbbc920d49245a3b76ac">insertCallAtAllFunctionExitPoints</a> (Function &amp;Fn, const char *InsertFnName, ArrayRef&lt; Value * &gt; FunctionArgs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d9bbafb5550c98593c6100ca4c43416">rtsanPreservedCFGAnalyses</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4524f9f3a01f5c6ea32b417422dd56ca">runSanitizeRealtime</a> (Function &amp;Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63ce604ca599913727c7c8c7fbe4ca13">runSanitizeRealtimeBlocking</a> (Function &amp;Fn)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4e349f0344b4c9078e22042f1cf0d82">kRtsanModuleCtorName</a>[] = "rtsan.module_ctor"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6d924ffe2b1fef28033ce5933cb354d">kRtsanInitName</a>[] = "__rtsan_ensure_initialized"</td>
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


<div class="doxySectionDef">

## Functions

### getArgTypes() {#a1922f0fa6389aaa7596f303e96bd8507}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; Type * &gt; getArgTypes (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; FunctionArgs)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp">RealtimeSanitizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#aaf5c6a95e57ae41b1bb74e87476d3dcc">insertCallBeforeInstruction</a>.</p>

</div>
</div>

### insertCallAtAllFunctionExitPoints() {#aa3f63c5f611bcbbc920d49245a3b76ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void insertCallAtAllFunctionExitPoints (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * InsertFnName, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; FunctionArgs)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp">RealtimeSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aaf5c6a95e57ae41b1bb74e87476d3dcc">insertCallBeforeInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a4524f9f3a01f5c6ea32b417422dd56ca">runSanitizeRealtime</a>.</p>

</div>
</div>

### insertCallAtFunctionEntryPoint() {#aeab32388541e65c42e97d2ca8c7867d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void insertCallAtFunctionEntryPoint (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * InsertFnName, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; FunctionArgs)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp">RealtimeSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4848d1a141ddc7cf0068460fba53ba37">llvm::BasicBlock::front</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a3ec0b920bf30d0e15bace383192691da">llvm::Function::front</a> and <a href="#aaf5c6a95e57ae41b1bb74e87476d3dcc">insertCallBeforeInstruction</a>.</p>


<p>Referenced by <a href="#a4524f9f3a01f5c6ea32b417422dd56ca">runSanitizeRealtime</a> and <a href="#a63ce604ca599913727c7c8c7fbe4ca13">runSanitizeRealtimeBlocking</a>.</p>

</div>
</div>

### insertCallBeforeInstruction() {#aaf5c6a95e57ae41b1bb74e87476d3dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void insertCallBeforeInstruction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Instruction, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * FunctionName, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; FunctionArgs)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp">RealtimeSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="#a1922f0fa6389aaa7596f303e96bd8507">getArgTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#abb107e4edbf05eae92936cba6801c2d9">llvm::Module::getOrInsertFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>.</p>


<p>Referenced by <a href="#aa3f63c5f611bcbbc920d49245a3b76ac">insertCallAtAllFunctionExitPoints</a> and <a href="#aeab32388541e65c42e97d2ca8c7867d1">insertCallAtFunctionEntryPoint</a>.</p>

</div>
</div>

### rtsanPreservedCFGAnalyses() {#a4d9bbafb5550c98593c6100ca4c43416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses rtsanPreservedCFGAnalyses ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp">RealtimeSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a4524f9f3a01f5c6ea32b417422dd56ca">runSanitizeRealtime</a> and <a href="#a63ce604ca599913727c7c8c7fbe4ca13">runSanitizeRealtimeBlocking</a>.</p>

</div>
</div>

### runSanitizeRealtime() {#a4524f9f3a01f5c6ea32b417422dd56ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses runSanitizeRealtime (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp">RealtimeSanitizer.cpp</a>.</p>


<p>References <a href="#aa3f63c5f611bcbbc920d49245a3b76ac">insertCallAtAllFunctionExitPoints</a>, <a href="#aeab32388541e65c42e97d2ca8c7867d1">insertCallAtFunctionEntryPoint</a> and <a href="#a4d9bbafb5550c98593c6100ca4c43416">rtsanPreservedCFGAnalyses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/realtimesanitizerpass/#a6ef2f34cb129c3b7d3a996e88f3e2c9e">llvm::RealtimeSanitizerPass::run</a>.</p>

</div>
</div>

### runSanitizeRealtimeBlocking() {#a63ce604ca599913727c7c8c7fbe4ca13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses runSanitizeRealtimeBlocking (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp">RealtimeSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#af377188a476a2d71184b0498a136fd1d">llvm::IRBuilderBase::CreateGlobalString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab996639d406a5466d5c8a1586fb4a9d8">llvm::demangle</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4848d1a141ddc7cf0068460fba53ba37">llvm::BasicBlock::front</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a3ec0b920bf30d0e15bace383192691da">llvm::Function::front</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="#aeab32388541e65c42e97d2ca8c7867d1">insertCallAtFunctionEntryPoint</a> and <a href="#a4d9bbafb5550c98593c6100ca4c43416">rtsanPreservedCFGAnalyses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/realtimesanitizerpass/#a6ef2f34cb129c3b7d3a996e88f3e2c9e">llvm::RealtimeSanitizerPass::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### kRtsanInitName {#ae6d924ffe2b1fef28033ce5933cb354d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char kRtsanInitName[] = "__rtsan_ensure_initialized"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp">RealtimeSanitizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/realtimesanitizerpass/#a6ef2f34cb129c3b7d3a996e88f3e2c9e">llvm::RealtimeSanitizerPass::run</a>.</p>

</div>
</div>

### kRtsanModuleCtorName {#af4e349f0344b4c9078e22042f1cf0d82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char kRtsanModuleCtorName[] = "rtsan.module_ctor"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp">RealtimeSanitizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/realtimesanitizerpass/#a6ef2f34cb129c3b7d3a996e88f3e2c9e">llvm::RealtimeSanitizerPass::run</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
