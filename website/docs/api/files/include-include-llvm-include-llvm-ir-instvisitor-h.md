---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/ir/instvisitor-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `InstVisitor.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "llvm/IR/Instruction.def"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acec6f7e3c8f55141a25830332307d3ea">HANDLE_INST</a>(NUM, OPCODE, CLASS)&nbsp;&nbsp;&nbsp;class CLASS;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1731d8b09e6c62e50d2e39be54d910ec">DELEGATE</a>(CLASS_TO_VISIT)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4a45d8a5d13fcd4819f9501002a44da">HANDLE_INST</a>(NUM, OPCODE, CLASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a522ad9d6c02e690c8a124234f0255e40">HANDLE_INST</a>(NUM, OPCODE, CLASS)&nbsp;&nbsp;&nbsp;...</td>
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

## Macro Definitions

### DELEGATE {#a1731d8b09e6c62e50d2e39be54d910ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DELEGATE(CLASS_TO_VISIT)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  return static_cast&lt;SubClass*&gt;(this)-&gt; \
               <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#a090736355958192cac4db32336c48bbd">visit</a>##CLASS_TO_VISIT(static_cast&lt;CLASS_TO_VISIT&amp;&gt;(<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>))
</div>
</dd>
</dl>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#ab39b720f77593cfa9c056431b6bc3714">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitAddrSpaceCastInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#ab89f81b6570d21fd7eefa7b09439c149">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a4e7bf5ec2426970bd86bcd8599e9f89c">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitAtomicCmpXchgInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#aa9a8ed9a3652337776d1812cf9c7059b">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitAtomicRMWInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#ab9647b10528628944657473a225932bb">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitBinaryOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a5b052a3578e5c55ba04a8e8e87d7d584">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitBitCastInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a22ae80c2045ac48274ba65b1d91d89e7">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitCallBase</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a02c2e9a2433786968d7851059cb94ed5">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitCallBrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#ad52d3da08557d933a3555611b0cbf33b">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#adfea612bdc5ce7d2f5f1c08e979a152c">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitCastInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a32edf0d6349ce5d846f8471a909f5182">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitCatchPadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a61d3f7692decd5e4c52ff2e38f2f82b5">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitCleanupPadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a0da94277ceb54c8aee12739104aaa2df">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#ae9f6d19db01b61de6e0ae70fdf4e1fd7">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitDbgDeclareInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a16a6087f3368aa0f9f25b5dcc6e85688">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitDbgInfoIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a8d23862d4863dfc9c17eeba75baa5fe2">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitDbgLabelInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#aae5e79758347bcf52f16c2c90a2b5c4c">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitDbgValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#ae151028ffcbe839b57acfb3895b6f705">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitDbgVariableIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a1a6290ef96ff3b08c0e463afef012ac9">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a7b3008f24e9985fd9b427cbf65898e0a">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a15f219103dc6b25a859d629b0f1c0917">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitFCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#af738b980e998639ba3fd8d7f7893711c">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitFenceInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#ac268c92fdf2bf24b67ddbdf8e7d25a70">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitFPExtInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a11c6aea9cef4bcd537d4b63a47f3540b">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitFPToSIInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a86b8d0f19a5db86d56c0ae4050b13a50">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitFPToUIInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#ab7c5ff480bab1f39d52fc492194ad641">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitFPTruncInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a092dc67ced79a88abe201ea46da32de5">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitFreezeInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#aa352484fecc3e8e3e2afc97e30aee410">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitFuncletPadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#aefd0a9d7224ad6eb0a24c20197c5dc53">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#ac2b9d4f06e4126f2fbbc10a71c19a9d3">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#aa3db7419445c212f612d809c7b92300b">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a2f8025addd1e435a612fc680fe4e65e1">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitInsertValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a432d533de0923ad3b0fd6dfc22c7ebd6">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitIntrinsicInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a57ec53e925ab39d499405e2428fff31f">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitIntToPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a102d96db537eef02feda77636663eafb">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitInvokeInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a46ccc0f15a7079d10ec5ed554ed459dc">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitLandingPadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#af8829e5fbad4f9606b5b6c0b100493c5">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a9ecca3f390d384ef182978a68e60be25">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitMemCpyInlineInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a1d0bcd4737de80bdaaa85e094b102d97">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitMemCpyInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a0e3132f8f6a1e2d04287ad74a64766f3">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#aa883c5b93d6c4f4bf058abd06306a299">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitMemMoveInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#ab9dbd696d10f57db2ba417aeb4deccb4">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitMemSetInlineInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#ad401dce38c15719e37382c854618dd15">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitMemSetInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#ac9c2e0fa94f0314f41ff580962b31deb">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitMemSetPatternInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#acaad755824bda1ce0066749c8655d3df">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitMemTransferInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a6b5f364cdf10081c74343b149fbc325f">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a0cc6a72ad7d27065b1ad1c5d0b2cac21">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitPtrToIntInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#aeb67eff747cfcdb17ca1079aff8ed9ca">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitSelectInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a593a97b3a33a03397ab24c42049cb011">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitSExtInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a45623fa4891c507f3b430bcc3b2e7a90">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#abb8bc66ad0815944c7770346e789ec83">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitSIToFPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a8f006d606ec21cb0e454912ce36d17d8">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitStoreInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a1a1f70533fc480e3cad75489388477cc">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a2301fc6526da21ff42ecb733dfaf95d9">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitTruncInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#af332042b4c6d937cb7b58c48a64ffd97">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitUIToFPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#ab199d37220dd0341361cd45229981d60">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitUnaryInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a8c877135fb038567546d01c269d519ed">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitUnaryOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#af8f7dfddc1f55fb738f00a43270bce5e">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitVAArgInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a132027e36e429b65a9a6a245f4fc8eae">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitVACopyInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a7cefcc06639ac482ae979e1703a1b3fc">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitVAEndInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a1b8bec4e74a7318b69a421e8df11bb41">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitVAStartInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#afc055d8c7e9e2f430f19b2f6887d1d37">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitZExtInst</a>.</p>

</div>
</div>

### HANDLE\_INST {#acec6f7e3c8f55141a25830332307d3ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_INST(NUM, OPCODE, CLASS)&nbsp;&nbsp;&nbsp;class CLASS;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### HANDLE\_INST {#ae4a45d8a5d13fcd4819f9501002a44da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_INST(NUM, OPCODE, CLASS)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">    case Instruction::OPCODE: return \
           static_cast&lt;SubClass*&gt;(this)-&gt; \
                      <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#a090736355958192cac4db32336c48bbd">visit</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a6c9b5dc65aa7364c6e3ed632c9e9f02e">OPCODE</a>(static_cast&lt;CLASS&amp;&gt;(<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>));
</div>
</dd>
</dl>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### HANDLE\_INST {#a522ad9d6c02e690c8a124234f0255e40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_INST(NUM, OPCODE, CLASS)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">    RetTy <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#a090736355958192cac4db32336c48bbd">visit</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a6c9b5dc65aa7364c6e3ed632c9e9f02e">OPCODE</a>(CLASS &amp;<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>) { \
      <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (NUM == Instruction::Call) \
        return delegateCallInst(<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>); \
      <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a0544c3fe466e421738dae463968b70ba">else</a> \
        <a href="#a1731d8b09e6c62e50d2e39be54d910ec">DELEGATE</a>(CLASS); \
    }
</div>
</dd>
</dl>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
