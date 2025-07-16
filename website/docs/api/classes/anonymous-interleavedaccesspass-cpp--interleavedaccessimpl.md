---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-interleavedaccesspass-cpp-/interleavedaccessimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InterleavedAccessImpl` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{InterleavedAccessPass.cpp}::InterleavedAccessImpl { ... }
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac128e8e4331785aa6c16ad8c4f249ad1">InterleavedAccess</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cfab47af909659ea96752f6a65dccc3">InterleavedAccessImpl</a> ()=default</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45755f68e5dbea47cc5b03ebe9f5900b">InterleavedAccessImpl</a> (DominatorTree *DT, const TargetLowering *TLI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57458b96a1b67f927f7a6e552338a81e">runOnFunction</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47a36a54525f841168b46f4425be2a2a">lowerInterleavedLoad</a> (LoadInst *LI, SmallSetVector&lt; Instruction *, 32 &gt; &amp;DeadInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform an interleaved load into target specific intrinsics. <a href="#a47a36a54525f841168b46f4425be2a2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ed7f40fd56c363f6b4e2ec900729845">lowerInterleavedStore</a> (StoreInst *SI, SmallSetVector&lt; Instruction *, 32 &gt; &amp;DeadInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform an interleaved store into target specific intrinsics. <a href="#a3ed7f40fd56c363f6b4e2ec900729845">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a786e6ac7512c7a6117b1aa5ca661362a">lowerDeinterleaveIntrinsic</a> (IntrinsicInst *II, SmallSetVector&lt; Instruction *, 32 &gt; &amp;DeadInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform a load and a deinterleave intrinsic into target specific instructions. <a href="#a786e6ac7512c7a6117b1aa5ca661362a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac44dffd4de5c2629e583d4a392d27ec1">lowerInterleaveIntrinsic</a> (IntrinsicInst *II, SmallSetVector&lt; Instruction *, 32 &gt; &amp;DeadInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform an interleave intrinsic and a store into target specific instructions. <a href="#ac44dffd4de5c2629e583d4a392d27ec1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae50a889f6997ce638bf14d267d283bb3">tryReplaceExtracts</a> (ArrayRef&lt; ExtractElementInst * &gt; Extracts, ArrayRef&lt; ShuffleVectorInst * &gt; Shuffles)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the uses of an interleaved load by the extractelement instructions in <span class="doxyComputerOutput">Extracts</span> can be replaced by uses of the shufflevector instructions in <span class="doxyComputerOutput">Shuffles</span> instead. <a href="#ae50a889f6997ce638bf14d267d283bb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcca7aba196d68ce10fa885c7827fb95">replaceBinOpShuffles</a> (ArrayRef&lt; ShuffleVectorInst * &gt; BinOpShuffles, SmallVectorImpl&lt; ShuffleVectorInst * &gt; &amp;Shuffles, LoadInst *LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a number of shuffles of the form shuffle(binop(x,y)), convert them to binop(shuffle(x), shuffle(y)) to allow the formation of an interleaving load. <a href="#abcca7aba196d68ce10fa885c7827fb95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fdd86d54f17fe11b245a1a18fd31f10">DT</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dfc96a50c81faf1fadb47bd37a69892">TLI</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad87691bf67571bc86f2f9fcd7d963683">MaxFactor</a> = 0u</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum supported interleave factor. <a href="#ad87691bf67571bc86f2f9fcd7d963683">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp">InterleavedAccessPass.cpp</a>.</p>


<div class="doxySectionDef">

## Friends

### InterleavedAccess {#ac128e8e4331785aa6c16ad8c4f249ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/anonymous-interleavedaccesspass-cpp-/interleavedaccess">InterleavedAccess</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp">InterleavedAccessPass.cpp</a>.</p>


<p>Reference <a href="#ac128e8e4331785aa6c16ad8c4f249ad1">InterleavedAccess</a>.</p>


<p>Referenced by <a href="#ac128e8e4331785aa6c16ad8c4f249ad1">InterleavedAccess</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InterleavedAccessImpl() {#a4cfab47af909659ea96752f6a65dccc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InterleavedAccessPass.cpp}::InterleavedAccessImpl::InterleavedAccessImpl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp">InterleavedAccessPass.cpp</a>.</p>

</div>
</div>

### InterleavedAccessImpl() {#a45755f68e5dbea47cc5b03ebe9f5900b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InterleavedAccessPass.cpp}::InterleavedAccessImpl::InterleavedAccessImpl (<a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> * TLI)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp">InterleavedAccessPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### runOnFunction() {#a57458b96a1b67f927f7a6e552338a81e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InterleavedAccessImpl::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp">InterleavedAccessPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### lowerDeinterleaveIntrinsic() {#a786e6ac7512c7a6117b1aa5ca661362a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InterleavedAccessImpl::lowerDeinterleaveIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 32 &gt; &amp; DeadInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform a load and a deinterleave intrinsic into target specific instructions.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp">InterleavedAccessPass.cpp</a>.</p>

</div>
</div>

### lowerInterleavedLoad() {#a47a36a54525f841168b46f4425be2a2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InterleavedAccessImpl::lowerInterleavedLoad (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 32 &gt; &amp; DeadInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform an interleaved load into target specific intrinsics.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp">InterleavedAccessPass.cpp</a>.</p>

</div>
</div>

### lowerInterleavedStore() {#a3ed7f40fd56c363f6b4e2ec900729845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InterleavedAccessImpl::lowerInterleavedStore (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 32 &gt; &amp; DeadInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform an interleaved store into target specific intrinsics.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp">InterleavedAccessPass.cpp</a>.</p>

</div>
</div>

### lowerInterleaveIntrinsic() {#ac44dffd4de5c2629e583d4a392d27ec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InterleavedAccessImpl::lowerInterleaveIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 32 &gt; &amp; DeadInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform an interleave intrinsic and a store into target specific instructions.</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp">InterleavedAccessPass.cpp</a>.</p>

</div>
</div>

### replaceBinOpShuffles() {#abcca7aba196d68ce10fa885c7827fb95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InterleavedAccessImpl::replaceBinOpShuffles (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> * &gt; BinOpShuffles, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> * &gt; &amp; Shuffles, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a number of shuffles of the form shuffle(binop(x,y)), convert them to binop(shuffle(x), shuffle(y)) to allow the formation of an interleaving load.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> newly created shuffles that operate on <span class="doxyComputerOutput">LI</span> will be added to <span class="doxyComputerOutput">Shuffles</span>. Returns true, if any changes to the IR have been made.</p>


<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp">InterleavedAccessPass.cpp</a>.</p>

</div>
</div>

### tryReplaceExtracts() {#ae50a889f6997ce638bf14d267d283bb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InterleavedAccessImpl::tryReplaceExtracts (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a> * &gt; Extracts, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> * &gt; Shuffles)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the uses of an interleaved load by the extractelement instructions in <span class="doxyComputerOutput">Extracts</span> can be replaced by uses of the shufflevector instructions in <span class="doxyComputerOutput">Shuffles</span> instead.</p>


<p>If so, the necessary replacements are also performed.</p>


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp">InterleavedAccessPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DT {#a2fdd86d54f17fe11b245a1a18fd31f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{InterleavedAccessPass.cpp}::InterleavedAccessImpl::DT = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp">InterleavedAccessPass.cpp</a>.</p>

</div>
</div>

### MaxFactor {#ad87691bf67571bc86f2f9fcd7d963683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InterleavedAccessPass.cpp}::InterleavedAccessImpl::MaxFactor = 0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum supported interleave factor.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp">InterleavedAccessPass.cpp</a>.</p>

</div>
</div>

### TLI {#a0dfc96a50c81faf1fadb47bd37a69892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering* anonymous{InterleavedAccessPass.cpp}::InterleavedAccessImpl::TLI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp">InterleavedAccessPass.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp">InterleavedAccessPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
