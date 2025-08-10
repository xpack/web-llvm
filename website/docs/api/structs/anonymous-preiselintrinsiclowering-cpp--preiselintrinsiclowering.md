---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-preiselintrinsiclowering-cpp-/preiselintrinsiclowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `PreISelIntrinsicLowering` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLowering { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b784958192f7f9b4b2557c2486d9100">PreISelIntrinsicLowering</a> (const TargetMachine *TM_, function_ref&lt; TargetTransformInfo &amp;(Function &amp;)&gt; LookupTTI_, function_ref&lt; TargetLibraryInfo &amp;(Function &amp;)&gt; LookupTLI_, bool UseMemIntrinsicLibFunc_=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6399ae03a799911dd8f5adcdff15dc8f">expandMemIntrinsicUses</a> (Function &amp;F) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a333bc33c92a4288cf0b3e4514f4cb075">lowerIntrinsics</a> (Module &amp;M) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac30c208ca0fcf76eed347fde03527835">TM</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c6a09848c1b6693ca21413318006c6a">LookupTTI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a152126794fc394841be8477fbb2ad1">LookupTLI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63d1c2a033b564cd4322943220265fdd">UseMemIntrinsicLibFunc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is true, assume it's preferably to leave memory intrinsic calls for replacement with a library call later. <a href="#a63d1c2a033b564cd4322943220265fdd">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44581a73bfff282e515ff1df662ee1cf">shouldExpandMemIntrinsicWithSize</a> (Value *Size, const TargetTransformInfo &amp;TTI)</td>
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


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PreISelIntrinsicLowering() {#a4b784958192f7f9b4b2557c2486d9100}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLowering::PreISelIntrinsicLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> * TM_, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; LookupTTI_, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; LookupTLI_, bool UseMemIntrinsicLibFunc_=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>


<p>References <a href="#a3a152126794fc394841be8477fbb2ad1">LookupTLI</a>, <a href="#a5c6a09848c1b6693ca21413318006c6a">LookupTTI</a>, <a href="#ac30c208ca0fcf76eed347fde03527835">TM</a> and <a href="#a63d1c2a033b564cd4322943220265fdd">UseMemIntrinsicLibFunc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### expandMemIntrinsicUses() {#a6399ae03a799911dd8f5adcdff15dc8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PreISelIntrinsicLowering::expandMemIntrinsicUses (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp/#ab3ab61efb16b5365178039250c68aa89">canEmitLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad5625618c73d17563d851631e27444e6">llvm::expandMemCpyAsLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35f13ead4222c0c45fb21f7e63025bbc">llvm::expandMemMoveAsLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff2c3179f5913a4a4d6c80e3d7e564c0">llvm::expandMemSetAsLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b152a4602737ffe1ac280df188402f8">llvm::expandMemSetPatternAsLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a8743c58384e11cb6228f6f871304ad35">llvm::Function::getFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a5c6a09848c1b6693ca21413318006c6a">LookupTTI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="#a44581a73bfff282e515ff1df662ee1cf">shouldExpandMemIntrinsicWithSize</a>, <a href="#ac30c208ca0fcf76eed347fde03527835">TM</a> and <a href="#a63d1c2a033b564cd4322943220265fdd">UseMemIntrinsicLibFunc</a>.</p>


<p>Referenced by <a href="#a333bc33c92a4288cf0b3e4514f4cb075">lowerIntrinsics</a>.</p>

</div>
</div>

### lowerIntrinsics() {#a333bc33c92a4288cf0b3e4514f4cb075}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PreISelIntrinsicLowering::lowerIntrinsics (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a6399ae03a799911dd8f5adcdff15dc8f">expandMemIntrinsicUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98ae6eba06bb737a1dd3e3c4e1662e29">llvm::expandVectorPredicationIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp/#a57e48e140e75da173a7ec5c681a1f2cc">forEachCall</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a5db8faf73cf29bcefdb3bdfadf3dc2c1">llvm::EVT::getEVT</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad593da8fb5bea5280b58aa0d7abfe16e">llvm::TargetLoweringBase::IntrinsicIDToISD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae53f11eb819a6e1a1249ef582fb25010a5adbe9a4214c6ce7438a7afa6c8544ed">llvm::IntrinsicReplaced</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae53f11eb819a6e1a1249ef582fb25010a237d5181e52c3a0d77bd78abe497ba20">llvm::IntrinsicUnchanged</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0248ed29f933c5faa55cbdfebf3139bd">llvm::TargetLoweringBase::isOperationExpand</a>, <a href="#a3a152126794fc394841be8477fbb2ad1">LookupTLI</a>, <a href="#a5c6a09848c1b6693ca21413318006c6a">LookupTTI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2763beadd2a14bcdb482f2b66a802019">llvm::lowerConstantIntrinsics</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp/#aed95721a1abb7ab2af1b35f3f282b1fe">lowerLoadRelative</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp/#aa5369c9d1c15e1c2fe5106461ae89334">lowerObjCCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0947c6f5b0bdcd54aa4a8447602f8283">llvm::lowerUnaryVectorIntrinsicAsLoop</a> and <a href="#ac30c208ca0fcf76eed347fde03527835">TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LookupTLI {#a3a152126794fc394841be8477fbb2ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const function_ref&lt;TargetLibraryInfo &amp;(Function &amp;)&gt; anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLowering::LookupTLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>


<p>Referenced by <a href="#a333bc33c92a4288cf0b3e4514f4cb075">lowerIntrinsics</a> and <a href="#a4b784958192f7f9b4b2557c2486d9100">PreISelIntrinsicLowering</a>.</p>

</div>
</div>

### LookupTTI {#a5c6a09848c1b6693ca21413318006c6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const function_ref&lt;TargetTransformInfo &amp;(Function &amp;)&gt; anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLowering::LookupTTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>


<p>Referenced by <a href="#a6399ae03a799911dd8f5adcdff15dc8f">expandMemIntrinsicUses</a>, <a href="#a333bc33c92a4288cf0b3e4514f4cb075">lowerIntrinsics</a> and <a href="#a4b784958192f7f9b4b2557c2486d9100">PreISelIntrinsicLowering</a>.</p>

</div>
</div>

### TM {#ac30c208ca0fcf76eed347fde03527835}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetMachine* anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLowering::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>


<p>Referenced by <a href="#a6399ae03a799911dd8f5adcdff15dc8f">expandMemIntrinsicUses</a>, <a href="#a333bc33c92a4288cf0b3e4514f4cb075">lowerIntrinsics</a> and <a href="#a4b784958192f7f9b4b2557c2486d9100">PreISelIntrinsicLowering</a>.</p>

</div>
</div>

### UseMemIntrinsicLibFunc {#a63d1c2a033b564cd4322943220265fdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLowering::UseMemIntrinsicLibFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is true, assume it's preferably to leave memory intrinsic calls for replacement with a library call later.</p>


<p>Otherwise this depends on TargetLoweringInfo availability of the corresponding function.</p>


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>


<p>Referenced by <a href="#a6399ae03a799911dd8f5adcdff15dc8f">expandMemIntrinsicUses</a> and <a href="#a4b784958192f7f9b4b2557c2486d9100">PreISelIntrinsicLowering</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### shouldExpandMemIntrinsicWithSize() {#a44581a73bfff282e515ff1df662ee1cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PreISelIntrinsicLowering::shouldExpandMemIntrinsicWithSize (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#ac09a21c371a9c535cbc13e8f82503aec">llvm::ConstantInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp/#a09580b94a258009643d4ddb3d2426a8d">MemIntrinsicExpandSizeThresholdOpt</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a6399ae03a799911dd8f5adcdff15dc8f">expandMemIntrinsicUses</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
